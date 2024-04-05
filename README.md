A minimal example pushing to PyPI on Github release.

## Release with auto versioning

Create a GitHub release and `setuptools` will stamp the package with the version
defined in your tag.

## PyPI trusted publishers

The configuration does not use any credentials, you allow the release with
[trusted publishers](https://docs.pypi.org/trusted-publishers/) on PyPI.
