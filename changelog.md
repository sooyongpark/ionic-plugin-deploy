Changelog
=========

## 0.3.1

* Updated the Download Manager (https://github.com/robertmryan/download-manager)
* Deploy service url is now pulled from the platform config

## 0.3.0

* Changed plugin id from `com.ionic.deploy` to `ionic-plugin-deploy`

## 0.2.3

* Adding deploy info. Fixes #11
* Fix for ios deploys not sticking around after force quitting. Fixes #21


## 0.2.2

* Firing error callback in the event the deploy check is unable to receive a valid response. Fixes #14
* Removed StandardCharset dependency to support older Android platforms. Fixes #19
