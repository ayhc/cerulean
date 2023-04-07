# Cerulean
## An opinionated Fedora Kinoite spin using uBlue-os tooling

[![build-ublue](https://github.com/ayhc/cerulean/actions/workflows/build.yml/badge.svg)](https://github.com/ayhc/cerulean/actions/workflows/build.yml)

This repo generates a customized Fedora Kinoite image, with numerous added (and removed) packages to suit my (ayhc's) personal preferences. You may like the selection of packages. Then again, you might not.

For more info, check out the [uBlue homepage](https://ublue.it/) and the [main uBlue repo](https://github.com/ublue-os/main/)

## Building your own

You're not me, so you probably want a different set of packages.

See the [Make Your Own page in the documentation](https://ublue.it/making-your-own/) for quick setup instructions for setting up your own repository based on the upstream template.

Don't worry, it only requires some basic knowledge about using the terminal and git.

## Verification

These images are signed with sisgstore's cosign. You can verify the signature by downloading the cosign.pub key from this repo and running the following command:

    cosign verify --key cosign.pub ghcr.io/ayhc/cerulean

