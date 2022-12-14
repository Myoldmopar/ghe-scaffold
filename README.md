# GHE Designer (Scaffold Repo)

This repo is a starting point for developing a GHE model repo, but really, it's just a scaffold for a Python library I guess.

## Code Quality

[![Flake8](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/flake8.yml/badge.svg)](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/flake8.yml)
[![Tests](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/test.yml/badge.svg)](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/test.yml)

Code is checked for style and with unit tests by GitHub Actions using nosetests to sniff out the tests.

## Documentation

[![Sphinx docs to gh-pages](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/docs.yml/badge.svg)](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/docs.yml)

[![gh-pages](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/pages/pages-build-deployment/badge.svg?branch=gh-pages)](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/pages/pages-build-deployment)

Docs are built from Sphinx by GitHub Actions and followed up with a deployment to GH-Pages using Actions, available at https://myoldmopar.github.io/ghe-scaffold/

## Releases

[![PyPIRelease](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/release.yml/badge.svg)](https://github.com/Myoldmopar/ghe-scaffold/actions/workflows/release.yml)

When a release is tagged, a GitHub Action workflow will create a Python wheel and upload it to the TestPyPi server.

To install into an existing Python environment, execute `pip install -i https://test.pypi.org/simple/ GHE-Designer-Scaffold`
