# Contribution
Thank you for deciding to contribute a feature or bug fix to ProjectName! Please read the following to get started.

## Installation
Latest dev version:
```sh
docker pull ghcr.io/warriors-life/.warriors-life-template-docker:dev
```

Latest release version:
```sh
docker pull ghcr.io/warriors-life/.warriors-life-template-docker:latest
```

Building from source:
```sh
docker build --tag your-test-tag src
```

## Running tests
Running unit tests:
```sh
cd test && npm run test
```

It may be useful to inspect logs in Docker Desktop.

## Preparing PR
It is suggested that you add unit tests if you are adding a new functionality or fix a bug. Please also update [changelog](CHANGELOG.md).

## Sending PR
You can do this [on GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).