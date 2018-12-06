# Ionic-wp-mag

Construire une application de votre blog Wordpress avec [Ionic](https://ionicframework.com/)

# Installation

Vous avez besoin d'installer [WP REST API v2](http://v2.wp-api.org/) in your Wordpress Site.

```bash
npm install -g ionic cordova
git clone https://github.com/tuayo77/ionic-wp-mag.git
cd ionic-wp-mag/
npm install
```

# Configure
To configure your app, go to src/app and open app.config.ts

If you want change colors of your app, go to src/theme and open variable.scss

# Use
## Android
```bash
ionic cordova platform add android
ionic cordova run android
```
## iOS
```bash
ionic cordova platform add ios
ionic cordova run ios
```
## Web
```bash
ionic serve
```

# Package Build
See [Ionic Package Build](https://ionicframework.com/docs/cli/package/build/) to build package.

# Requirements

* [Ionic](https://ionicframework.com/)
* [Cordova](https://cordova.apache.org/)
* [WP REST API v2](http://v2.wp-api.org/)
* [WP API ANGULAR](https://github.com/wordpress-clients/wp-api-angular)

# Author

**TUAYO Borel** [tuayo77](https://github.com/tuayo77)
