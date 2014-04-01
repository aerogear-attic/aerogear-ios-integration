# aerogear-ios-integration [![Build Status](https://travis-ci.org/aerogear/aerogear-ios-integration.png)](https://travis-ci.org/aerogear/aerogear-ios-integration)

Integration Tests for the [aerogear-ios](https://github.com/aerogear/aerogear-ios) library.

The project requires [CocoaPods](http://cocoapods.org/) for dependency management;

## SETUP

_BEFORE_ you can run the test, you need to run the following command inside of the AeroGear-iOS-Integration folder:

    pod install

This installs all the required dependencies and generates the _AeroGear-iOS-Integration.xcworkspace_ project file.

## Test cases

The test cases are executed against either a backend deployed on OpenShift in:

- for [AGRestAuthenticationSpec](http://jaxrs-aerogear.rhcloud.com/aerogear-jaxrs-demo/rest/)
- for [AGHttpAuthentication](http://controller-aerogear.rhcloud.com/aerogear-controller-demo): to be migrated to jaxrs

or an Open Backend like:

- [WorldOfWarcraft](http://us.battle.net/api/wow)
- [Github API](https://api.github.com/users/matzew/gists)

NOTE: If some tests are failing, please check the availability of the backend end first. 

## Getting started

Open the [AeroGear-iOS-Integration.xcworkspace](aerogear-ios-integration/tree/master/AeroGear-iOS-Integration/AeroGear-iOS-Integration.xcworkspace) in Xcode, if you want to get the project...

## Running the tests

* Install JBoss
* Deploy the TODO app (make sure it's not already deployed...)
* Run the test by executing the _runTests.sh_ script
