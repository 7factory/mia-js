## 1.3.5 (April 11, 2021)
* Fixed React Static Router incompatibility with History npm package version > 4.7.2

## 1.3.4 (April 10, 2021)
* Updated generic notification manager and processor to use Apple APN HTTP2
* Run ensureIndex in sequence instead of creating all indexes in parallel
* Bugfix routes handler HMR for Windows machines 

## 1.3.3 (September 28, 2020)
* Added bundle version hash to all build processes

## 1.3.2 (August 22, 2020)
* Updated mia-js-core to version 2.8.1
* NPM audit

## 1.3.1 (April 14, 2020)
* Updated mia-js-core to version 2.7.8
* NPM audit

## 1.3.0 (March 16, 2020)
* Added StandardJS linting
* Linted whole project
* Consolidated generic project

## 1.2.0 (March 12, 2020)
* Updated mia-js-core to version 2.7.0
* Updated README regarding "allowMultiple" precondition
* Hid requestdate and signature method from generic auth controller as its not needed
* Changed all errors to MiaError

## 1.1.1. (October 21, 2019)
* Updated mia-js-core
* Updated README regarding "extend" precondition

## 1.1.0 (October 8, 2019)
* Updated mia-js-core
* Added two new example projects for a simple React site:
** One with a client bundle which is rendered in the browser only
** Another one including a server bundle which is used for static site generation (like gatsby.js etc)
* Refactored webpack configuration files
* Fixed npm vulnerabilities

## 1.0.7 (April 18, 2019)
* Consolidated development and build process of frontend projects and HMR devServer
* Fixed security vulnerabilities

## 1.0.6 (March 27, 2019)
* Updated packages

## 1.0.5 (January 21, 2019)
* Optimized webpack publicPath handling
* Fixed HMR error with redux store
* Updated mia-js-core to version 2.3.3
* Fixed potential security vulnerabilities

## 1.0.4 (January 17, 2019)
* Updated mia-js-core to version 2.3.1
* Some webpack configuration improvements
* Some React component improvements

## 1.0.3 (October 4, 2018)
* Updated mia-js-core to version 2.2.0
* Skip indexing Database on test env and by setting the env var skipDatabaseIndexing
* Refactored q.fail() to .catch(); Removed q.done()

## 1.0.2 (May 23, 2018)
* Interoperation between native promises and Q promises
* Bumped mia-js-core version to 2.1.2

## 1.0.1 (May 16, 2018)
* Updated mia-js-core to version 2.1.1

## 1.0.0 (April 24, 2018)
* Updated mia-js-core to version 2.1.0
* Updated Babel and webpack to latest versions
* Updated README.md to reflect latest features

## 0.9.7 (February 1, 2018)

* Updated mia-js-core to version 1.0.5
* Set different value fpr cache control generic controller
* Split up output and cache controllers
* Serval bugfixes in generic

## 0.9.6 (January 12, 2018)

* Updated mia-js-core to version 1.0.1
* Removed base model function tests from user.spec.js

## 0.9.5 (January 10, 2018)

* Updated mia-js-core to version 0.9.10
* MongoDB and driver update (3.6.1/3.0.1)
* Reactivated jasmine tests, see "npm test"
* Refactored express deprecations

## 0.9.4 (December 20, 2017)

* Refactored frontend demo project (/web) to use React.js v16 and all the fun stuff like redux, server-side-rendering, isomorphic style loading, declarative routing, etc
* Replaced grunt with webpack as build tool

## 0.9.3 (November 30, 2017)

* Implemented cronjob to sync database indexes with those defined in model schema
* Added Babel to use ES6+ syntax
* Updated MongoDB config object

## 0.8.9 (Dezember 8, 2016)

* Updated mia.js-core and generic projects
* Removed unneeded node-modules

## 0.8.7 (October 19, 2016)

* Updated mia.js-core and generic projects


## 0.8.6 (May 27, 2016)

* Updated mia.js-core and generic projects to run mia.js with optional db connection

## 0.8.5 (May 27, 2016)

* Added language support for notification templates
* Bugfix notification processor on APNS error
* Bugfix notification processor log


## 0.8.4 (March 4, 2016)

* Added rate limiter functionallity
* Renamed identifier of generic default output controller
 
## 0.8.2 (January 07, 2016)

* Added node 0.12x support
* Added xml default output controller
* Added reply-to field to notifications mail
* Bugfix email regex to support new domains like .email .international

## 0.8.1 (Sepember 18, 2015)

* Updated modules mongodb, memcache and q to latest version due to memory leak
* Reengineered mia.ja to work with updated modules
* Reengineered mia.js logger

## 0.8.0 (August 28, 2015)

* Initial public release
