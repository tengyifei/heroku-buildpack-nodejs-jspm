# Heroku Buildpack for Node.js and JSPM

Fork of the [official Node.js buildpack](https://github.com/heroku/heroku-buildpack-nodejs) adding [JSPM](https://jspm.io) support and a `jspm install` step. This is for getting around Heroku's 60 second startup timeout.

It doesn't feature caching yet since it would need to read `package.json` to figure out where `jspm_packages` is.
