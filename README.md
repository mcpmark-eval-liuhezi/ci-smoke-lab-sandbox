# ci-smoke-lab-sandbox
Throwaway sandbox for release-readiness smoke test of contribution + CI loop

## Build artifact

The CI pipeline produces an artifact named `demo-build` (uploaded via `actions/upload-artifact@v4`). It contains a short text file (`demo-build.txt`) written by the `build` job on `ubuntu-latest` and can be downloaded from the Actions tab of this repository.
