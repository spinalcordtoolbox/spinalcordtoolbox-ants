# ANTs

This repository is used to build the 4 total ANTs binaries used by SCT:

* `antsApplyTransforms`
* `antsRegistration`
* `antsSliceRegularizedRegistration`
* `antsComposeMultiTransform`

These binaries are build across several different platforms provided by GitHub Action's CI runners.

### Using this repo

To rebuild the binaries, navigate to the [`build-ants.yml`](https://github.com/spinalcordtoolbox/build_ANTs/actions/workflows/build-ants.yml) Actions workflow, then click "Run workflow" and enter in the commit you want to build from.

Then, when the build has finished, navigate to the [Releases](https://github.com/spinalcordtoolbox/build_ANTs/releases) page, and edit the release to give it a suitable name and description.
