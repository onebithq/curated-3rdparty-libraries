# Curated 3rd Party Libraries

This repository contains list of 3rd party libraries used by Onebit in our day to day development.

## Table of Contents

- [Backend]()
	- [Go](#goto-go)
	- [PHP](#goto-php)
	- [NodeJS](#goto-nodejs)
	- [AngularJS](#goto-angularjs)
  	- [Rails](#goto-rails)
  	- [Web Dev Tools](#goto-web-dev-tools)

- [Android](#goto-android)
	- [Gradle](#goto-gradle)

- [iOS]()
	- [Objective-C](#goto-objc)
	- [Swift](#goto-swift)


## <a name="goto-go"></a>Go
* [go-simplejson](https://github.com/bitly/go-simplejson) - Easy-to-use package to interact with JSON. Provide struct, getter, setter and marshal to create/read JSON.
* [gorilla-mux](https://github.com/gorilla/mux) - Easy and powerful URL router. Provide custom routers and interface to comply with golang's http.
* [amqp](https://github.com/streadway/amqp) - Complete AMQP client. Self-explanatory
* [profile](https://github.com/davecheney/profile) - Simple profiling package without too much complicated configurations or http.
* [uuid](https://github.com/twinj/uuid) - RFC4122-compliant UUID generator
* [log15](https://gopkg.in/inconshreveable/log15.v2) - Pretty and simple logging package. Provides multiple transports, log-levels and use key-value.

## <a name="goto-php"></a>PHP
* [intervention](http://image.intervention.io/) Image handling and manipulation in PHP
* [faker](https://github.com/fzaninotto/Faker) Generates fake data
* [sentinel](https://github.com/cartalyst/sentinel) Auth & authorize system
* [ardent](https://github.com/laravel-ardent/ardent) Self validating models
* [debugbar](https://github.com/barryvdh/laravel-debugbar) Debugging tools
* [carbon](https://github.com/briannesbitt/Carbon) Extension of PHP DateTime


## <a name="goto-nodejs"></a>NodeJS

* [express](http://expressjs.com/) - Fast, minimalist and robust web framework for NodeJS. One of the most popular web framework in NodeJS.
* [moment](http://momentjs.com) - Provide easy methods to manipulate date in JS.
* [lodash](https://lodash.com/) - Must have utility library for JS project. Provide a lot of useful functions such as  **map, filter, omit, extend, chain**, etc.
* [winston](https://www.npmjs.com/package/winston) - Logging library that provides multiple transports.
* [kaiseki](https://www.npmjs.com/package/kaiseki) - Wrapper of Parse API.
* [socket-io](https://www.npmjs.com/package/socket.io) - Provides realtime engine that can be used for chat, notifications, etc.
* [sequelize](http://sequelize.readthedocs.org/) - ORM for SQL-based RDBMS. This library using promises with various features and easy to use.
* [mongoskin](https://www.npmjs.com/package/mongoskin) - MongoDB lightweight driver. Based on node-mongodb-native.
* [Settings](https://www.npmjs.com/package/settings) - Simple environment-based settings.
* [formidable](https://www.npmjs.com/package/formidable) - Library for form-data parsing. Fast and able to write uploaded file to disk automatically. 
* [debug](https://www.npmjs.com/package/debug) - small and pretty library for debugging.
* [node-oauth2-server](https://www.npmjs.com/package/node-oauth2-server) - Complete and battle-tested library for Oauth2 server/provider. Used as middleware in expressJS.


## <a name="goto-angularjs"></a>AngularJS
* [textAngular](https://github.com/fraywing/textAngular) - Provide customisable WYSIWYG text editor for angularJS.
* [angular-busy](https://github.com/cgross/angular-busy) - Provide loading/busy indicator during any promises.
* [alertify](http://fabien-d.github.io/alertify.js/) Easy to use dialog and provide nice callback. Unfortunately, the maintenance has stopped.
* [angular-geolocation](https://github.com/arunisrael/angularjs-geolocation) - angularjs wrapper for window.navigate.geolocation. Useful to get user's location.
* [angular-flot](https://www.npmjs.com/package/angular-flot) - angular wrapper for Flotcharts (plotting library for jQuery)


## <a name="goto-rails"></a>Rails
* [carrierwave](https://github.com/carrierwaveuploader/carrierwave) - Image Uploader Engine, support for S3
* [kaminari](https://github.com/amatsuda/kaminari) - Scoped Engine Paginator
* [god](http://godrb.com/) - A Process Monitoring
* [foreman](https://github.com/ddollar/foreman) - Daemonize tools support for upstart, supervisord
* [pg_search](https://github.com/Casecommons/pg_search) - Utilize Postgres Full Text Search Engine
* [puma](http://puma.io/) - Ruby web server app
* [paranoia](https://github.com/radar/paranoia) - Acs as paranoid on destroy
* [byebug](https://github.com/deivid-rodriguez/byebug) - Debugging tools in ruby
* [feedjira](https://github.com/feedjira/feedjira) - Fetch and parse feeds
* [delayed_job_active_record](https://github.com/collectiveidea/delayed_job_active_record) - Background job using rails active record


## <a name="goto-web-dev-tools"></a>Web Dev Tools
* [npm](https://www.npmjs.com/) - Package manager for Javascript and NodeJS. 
* [bower](http://bower.io/) - Package manager for web development. It will hunt any package we need.
* [Grunt](http://gruntjs.com/) - Automated task runner for web development. Configuration over code and uses JSON-like configuration
* [Gulp](http://gulpjs.com/) - Automated task runner for web development. Code over configuration with simple javascript code.
* [Composer](https://getcomposer.org/) - PHP Dependency manager
* [Bundler](http://bundler.io/) - Ruby dependency manager


## <a name="goto-android"></a>Android

* [picasso](http://square.github.io/picasso/) - **Simple image loader** with caching and fluent interface. Supports image transformations as well.
* [retrofit](http://square.github.io/retrofit/) - **Type-safe REST client**. Easy to define endpoints using java annotations.
* [okhttp](http://square.github.io/okhttp/) - **Better Android HTTP client**. Works well with picasso & retrofit.
* [timber](https://github.com/JakeWharton/timber) - **Logging wrapper**. We use it to redirect logcat to Crashlytics in non-debug builds.
* [butterknife](http://jakewharton.github.io/butterknife/) - **Android view "injection"** made easy. No need to type boilerplate `findViewById` for each views in activity.
* [leakcanary](https://github.com/square/leakcanary) - **Android leak detector**.
* [gson](https://github.com/google/gson) - **Simple POJO-based JSON (de)serializer**
* [calligraphy](https://github.com/chrisjenx/Calligraphy) - **Easy tools for defining custom font in Android widget**.

### <a name="goto-gradle"></a>Gradle Plugins

* [android-check](https://github.com/noveogroup/android-check) - **PMD and checkstyle in one plugin**.
* [sdk-manager-plugin](https://github.com/JakeWharton/sdk-manager-plugin) - **Automatically download required SDK version and support libraries**.
* [icon-version](https://github.com/akonior/icon-version) - **Show version number in debug app icon**.
* [dexcount](https://github.com/KeepSafe/dexcount-gradle-plugin) - **Show method count on every build**. Stay away from 65536 method limit.
* [retro-lambda](https://github.com/evant/gradle-retrolambda) - **Build java or android project with retrolambda**. Require **Java 8 SDK**.

## <a name="goto-objc"></a>Objective-C

* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and OS X networking framework

## <a name="goto-swift"></a>Swift

* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and OS X networking framework
* [Quick](https://github.com/Quick/Quick) - The Swift (and Objective-C) testing framework.
* [Nimble](https://github.com/Quick/Nimble) - A Matcher Framework for Swift and Objective-C
