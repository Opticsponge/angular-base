# Angular Base for Apps

An open source, community-driven fork of [Foundation for Apps by Zurb](https://github.com/zurb/foundation-apps). Read about the [why](https://github.com/zurb/foundation-apps/issues/812) behind this fork.

[![Build Status](https://travis-ci.org/base-apps/angular-base.svg)](https://travis-ci.org/base-apps/angular-base)

This is Angular Base for Apps, an Angular-powered framework for building powerful responsive web apps and an unofficial fork of [Foundation for Apps by Zurb](https://github.com/zurb/foundation-apps).

## Requirements

You'll need the following software installed to get started.

  * [Node.js](http://nodejs.org): Use the installer provided on the NodeJS website.
  * [Git](http://git-scm.com/downloads): Use the installer for your OS.
    * Windows users can also try [Git for Windows](http://git-for-windows.github.io/).
  * [Gulp](http://gulpjs.com/) and [Bower](http://bower.io): Run `[sudo] npm install -g gulp bower`

## Get Started

The Sass and JavaScript components are available on Bower and npm.
```
bower install angular-base --save
npm install angular-base --save
```

You can also use our command-line interface to quickly setup a basic Angular Base for Apps project. It includes a pre-built Gulpfile that compiles an Angular-powered web app for you.

Install it with this command:
```
npm install -g angular-base-cli bower gulp
```

Now you can make a new project:
```
angular-base new myApp
cd myApp
```

**note:** The CLI is not yet available.

While working on your project, run:
```
npm start
```

This will assemble the templates, static assets, Sass, and JavaScript. You can view the test server at this URL:
```
http://localhost:8080
```

## Building this Repo

If you want to work with the source code directly or compile our documentation, follow these steps:
```
git clone https://github.com/base-apps/angular-base.git
cd angular-base
npm install
```

While you're working on the code, run:
```
npm start
```

The documentation can be viewed at the same URL as above.

### Directory Structure

* `build`: This is where our documentation is assembled. **Don't edit these files directly, as they're overwritten every time you make a change!**
* `docs`: The Foundation for Apps documentation.
* `scss`: The Sass components.
* `js`: The Angular modules and directives, and other external libraries.
* `iconic`: A set of 24 icons from the folks at [Iconic](https://useiconic.com/).
* `dist`: Compiled CSS and JavaScript files, in minified and unmified flavors.
* `tests`: Unit tests for the Angular modules.

## Versioning

Foundation for Apps follows semver, so we won't introduce breaking changes in minor or patch versions. The `master` branch will always have the newest changes, so it's not necessarily production ready. The `stable` branch will always have the most recent stable version of the framework.

## Contributing

We love feedback! Help us find bugs and suggest improvements or new features.

If you find a problem or have an idea, open a [new issue](https://github.com/base-apps/angular-base/issues) on GitHub. When filing a bug report, make sure you specify the browser and operating system you're on, and toss us a screenshot or show us how we can recreate the issue.
