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
### ios do_test_app
```
fastlane ios do_test_app
```
Run unit tests
### ios do_increment_build_number
```
fastlane ios do_increment_build_number
```
Increment build number
### ios do_build_app
```
fastlane ios do_build_app
```
Building app
### ios do_upload_app_to_testflight
```
fastlane ios do_upload_app_to_testflight
```
Upload app to Testflight
### ios alpha
```
fastlane ios alpha
```
Build & Upload app to Testflight

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
