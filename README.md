# ember-cli-deploy-firebase-pack

> An ember-cli-deploy plugin pack implementing a simple firebase hosting deploy pattern

This package bundles the plugins you need to have a deployment pipeline for your Ember app that deploys to Firebase hosting.

## Installation

```
ember install ember-cli-deploy
ember install ember-cli-deploy-firebase-pack
```

The necessary set of plugins will be available to ember-cli-deploy.

## What is a plugin pack?

A "plugin pack" is a concept supported by ember-cli-deploy that allows a single addon to make multiple plugins available by adding a single direct dependency to your project.

## What plugins are made available?

* [ember-cli-deploy-build](https://github.com/ember-cli-deploy/ember-cli-deploy-build)
* [ember-cli-deploy-firebase](https://github.com/ibroadfo/ember-cli-deploy-firebase)
* [ember-cli-deploy-revision-data](https://github.com/ember-cli-deploy/ember-cli-deploy-revision-data)
