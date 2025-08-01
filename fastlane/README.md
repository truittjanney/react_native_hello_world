fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

### test_all

```sh
[bundle exec] fastlane test_all
```

Run all tests and checks before building

### run_unit_tests

```sh
[bundle exec] fastlane run_unit_tests
```

Run Jest unit tests

### run_linting

```sh
[bundle exec] fastlane run_linting
```

Run ESLint code linting

### ci

```sh
[bundle exec] fastlane ci
```

Full CI pipeline: test, then build for both platforms

----


## iOS

### ios build

```sh
[bundle exec] fastlane ios build
```

Build the iOS app using Xcode

### ios ios_build

```sh
[bundle exec] fastlane ios ios_build
```

Run iOS-specific tests and build

### ios ios_test

```sh
[bundle exec] fastlane ios ios_test
```

Run iOS unit tests with Xcode

----


## Android

### android build

```sh
[bundle exec] fastlane android build
```

Build android app

### android android_build

```sh
[bundle exec] fastlane android android_build
```

Run Android-specific tests and build

### android android_test

```sh
[bundle exec] fastlane android android_test
```

Run Android unit tests

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
