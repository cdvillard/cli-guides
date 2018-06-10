# Installing and upgrading the CLI

## Prerequisites

* npm
* Mac users need [Watchman](https://facebook.github.io/watchman/) (not the npm version!)

To install the CLI, we first need to have `npm` working. Visit <!-- LINK --> for instructions.

We'll know it is successful when `npm -v` returns the version number. It is recommend to install the most recent LTS (long term support) version of `node`. Restart the console after installing `npm`.

Mac users can install [Watchman](https://facebook.github.io/watchman/) via [Homebrew](http://brew.sh/). Watchman helps correct for some buggy file watching behavior in MacOS. Do not use the `npm` package by the same name.

```
brew install watchman
```

## Installing

```
npm install -g ember-cli
```

This will make the `ember` command available throughout your project folders. The installation is successful if `ember -v` returns a version number. When it is run inside of an Ember app directory, it will show the version of the app, otherwise it will show the globally installed version of the CLI.

## Versioning

The Ember CLI is backwards compatible, meaning that the latest CLI can be used on older app versions. New versions of the CLI are released roughly every 6 weeks, in step with versions of Ember.js itself.

A list of CLI releases and their features can be found on the GitHub repository for [ember-cli](https://github.com/ember-cli/ember-cli/releases).

## Upgrading the CLI version

The Ember CLI can be updated independently of the apps it is used with.
Upgrade instructions are published with [each release](https://github.com/ember-cli/ember-cli/releases).

## Upgrading the Ember app itself

There are automated Ember CLI tools available to help upgrade Ember apps, including codemods that help with syntax changes. Visit
[ember-cli-update](https://github.com/ember-cli/ember-cli-update for the latest instructions.

## Getting help

Users of all operating systems can get community support for installation problems. A list of chat rooms, forums, and more is available [here](https://www.emberjs.com/learn/).