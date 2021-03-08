# scalingo-playwright-buildpack

Installs required dependencies run playwright on Scalingo.
This repo is heavily inspired by https://github.com/mxschmitt/heroku-playwright-buildpack, if not almost completely cloned/adapted for Scalingo stacks.

## Usage

To use the latest stable version, add the repository url to the `.buildpacks` file at the root of your project.

## Issues

If you run into any issues with this buildpack, please open an issue on this repo and/or submit a PR that resolves it. Different versions of chromium/firefox/webkit have different dependencies and so some issues can creep in without knowing. Thanks!
