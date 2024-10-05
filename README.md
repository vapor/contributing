# Contributing

This repo contains files used when contributing to Vapor, such as our [Swift Format](https://github.com/swiftlang/swift-format) configuration file.

## Setting Up

### Swift Format

To set up your local environment to use the Swift Format configuration file, this repo assumes you have a directory containing all Vapor repos you work on and this repo is checked out in a `contributing` directory at the same level as other repos.

Run the script from the directory containing all your Vapor repos:

```bash
./contributing/setup.sh
```

This will create a symbolic link to the Swift Format configuration file in the top level directory that will be picked up when you run `swift format` in any of your Vapor repos.

## Contributing to Vapor

For information on how to contribute to Vapor, see the [contributing guide](https://docs.vapor.codes/contributing/contributing/) in our documentation.
