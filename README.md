# opensafely-core.r-universe.dev :rocket:

[![:name status badge](https://opensafely-core.r-universe.dev/badges/:name)](https://opensafely-core.r-universe.dev/)
[![:registry status badge](https://opensafely-core.r-universe.dev/badges/:registry)](https://github.com/r-universe/opensafely-core/actions/workflows/sync.yml)
[![:total status badge](https://opensafely-core.r-universe.dev/badges/:total)](https://opensafely-core.r-universe.dev/)

This is the repo specifying which R packages contribute to <https://opensafely-core.r-universe.dev/>.

This repo is for use in v2 of the r image.
We use it to build packages which are not on CRAN and install these binary packages in the v2 r image.
This means that packages do not have to be built from source when building the v2 r image.
This greatly reduces the build time of the v2 r image.

For info, the corresponding source universe repository (managed by r-universe) is at <https://github.com/r-universe/opensafely-core>.
