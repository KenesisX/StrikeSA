# StrikeSA

StrikeSA (Strike Spectrum Analyzer)
For RPI02W with PiSugar Whisplay

## GitHub Actions image build

This repo includes a GitHub Actions workflow that builds a Raspberry Pi OS image using `pi-gen` and uploads the final `StrikeSA.img.xz` as a workflow artifact.

### Build it

1. Open the repository on GitHub.
2. Go to Actions.
3. Select "Build StrikeSA .img".
4. Run the workflow.
5. Wait ~15–25 minutes.
6. Download the `StrikeSA-image` artifact.
7. Extract the `.img.xz` file.
8. In Raspberry Pi Imager, choose "Use custom" and select the generated image.

### Notes

- The workflow is intentionally cloud-build friendly and does not require a local Raspberry Pi or local image build setup.
- The image is generated from a `pi-gen` configuration in this repository.
- 
