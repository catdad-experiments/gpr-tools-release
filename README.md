# gpr-tools-release

[![travis][travis.svg]][travis.link]

[travis.svg]: https://travis-ci.com/catdad-experiments/gpr-tools-release.svg?branch=master
[travis.link]: https://travis-ci.com/catdad-experiments/gpr-tools-release

This repository is meant to build GoPro's [gpr_tools](https://github.com/gopro/gpr) and provide binaries for popular operating systems. The source code is build unmodified... in fact, it is pulled in as a submodule. Get the latest version from the [releases page](https://github.com/catdad-experiments/gpr-tools-release/releases).

## Versions

Release versions will first use the version of `gpr_tools` itself, followed by an rc version based on rebuilding the binaries for various needs. The version will look something like this: `1.0.0-rc-1.0.7`. I suggest parsing the version with something like [`semver`](https://www.npmjs.com/package/semver) to make sure you are downloading a binary that does not include breaking changes (both in the `gpr_tools` version and in the rebuild version).

## License

The binaries are distributed under either:

* Apache License, Version 2.0, (LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
* MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)

at your option. This is the same license as the source code. Please see the license in the original repository for details.

To the extent possible under law, I am waiving all copyright and related or neighboring rights to the build scripts and build-related code in this repository.
