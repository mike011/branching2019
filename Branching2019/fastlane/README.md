fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios major_release
```
fastlane ios major_release
```
Creates a new version of Service Framework by bumping the major version (X.0.0)
### ios release
```
fastlane ios release
```
Creates a new version of Service Framework by bumping the minor version (*.X.0)
### ios hotfix
```
fastlane ios hotfix
```
Creates a new hotfix of Service Framework by bumping the patch version (*.*.X)

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
