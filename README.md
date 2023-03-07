# Mobile application automation test project

## Libraries

| groupId                 | artifactId          | version | description                                    | homepage                                                               |
|:------------------------|:--------------------|:-------:|:-----------------------------------------------|:-----------------------------------------------------------------------|
| io.appium               | java-client         | 6.1.0   | Java client for Appium Mobile Webdriver        | [appium/java-client](https://github.com/appium/java-client)            |
| junit                   | junit               | 4.12    | Unit testing framework for Java                | [junit-team/junit4](https://junit.org/junit4/)                         |

## App's

#### Locations (*.apk, *.app)

_src/test/resources/apks_

#### Description and version

| name                 | version | description                                   | homepage                                                                             |
|:---------------------|:-------:|:----------------------------------------------|:-------------------------------------------------------------------------------------|
| org.wikipedia.apk    | unknown | Old version up to date 02/18/2018             | [wikipedia](https://play.google.com/store/apps/details?id=org.wikipedia&hl=ru&gl=US) |
| Wikipedia.app        | unknown | Actual official version up to date 05/05/2021 | [wikipedia-ios](https://github.com/wikimedia/wikipedia-ios)                          |

## Install Jenkins

Install the latest LTS version: brew install jenkins-lts

Install a specific LTS version: brew install jenkins-lts@YOUR_VERSION

Start the Jenkins service: brew services start jenkins-lts

Restart the Jenkins service: brew services restart jenkins-lts

Update the Jenkins version: brew upgrade jenkins-lts

## Install Appium

[Getting Started](http://appium.io/docs/en/about-appium/getting-started/?lang=en)

#### Install Node.js

brew install node 

#### Install appium

npm install -g appium 

#### Install scoop

Set-ExecutionPolicy RemoteSigned -scope CurrentUser

iwr -useb get.scoop.sh | iex

#### Install Allure 

scoop install allure