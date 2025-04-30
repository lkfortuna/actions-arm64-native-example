This is an example of how to use the [native github actions arm runners](https://github.blog/changelog/2025-01-16-linux-arm64-hosted-runners-now-available-for-free-in-public-repositories-public-preview/) to accelerate docker builds. I've started with the [official docker distributed build guide](https://docs.docker.com/build/ci/github-actions/multi-platform/#distribute-build-across-multiple-runners) and made some modifications:

- add runner to the matrix and parameterize runs-on
