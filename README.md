# UniteJS Test Polymer JavaScript

## UniteJS Operations

* unite configure --packageName=polymer-javascript --title="Polymer JavaScript" --profile=PolymerJavaScript --outputDirectory=./app
* unite generate --type=class --name=MyClass --outputDirectory=./app
* unite generate --type=component --name=MyComponent --outputDirectory=./app
* unite generate --type=enum --name=MyEnum --outputDirectory=./app
* unite generate --type=interface --name=MyInterface --outputDirectory=./app
* unite platform --operation=add --platformName=Cordova --outputDirectory=./app
* unite platform --operation=add --platformName=Docker --outputDirectory=./app
* unite platform --operation=add --platformName=Electron --outputDirectory=./app

## Build Operations

* gulp build
* gulp theme-build
* gulp unit
* gulp e2e-install
* gulp e2e
* gulp build --buildConfiguration=prod
* gulp e2e
* gulp doc-build
* gulp platform-web-package --buildConfiguration=prod
* gulp platform-electron-dev
* gulp platform-electron-package --buildConfiguration=prod
* gulp platform-docker-package --buildConfiguration=prod
* gulp platform-cordova-dev --buildConfiguration=prod
* gulp platform-cordova-theme --buildConfiguration=prod
