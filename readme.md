## Npm package starter

[![npm]()]()
[![Build Status]()]()
[![Codecov]()]()
[![Codacy Badge]()]()
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

### About
A simple npm package boilerplate with:
* Typescript
* Prettier
* TSLint
* Jest testing
* Travis (test, build, publish) CI
* Codecov test coverage
	

### Travis
To enable npm package auto publishing, building and testing with Travis CI, 
add NPM_TOKEN and NPM_EMAIL environment variables to Travis repo settings.
After that every new tag on master branch will create a new release on NPM.

For easy version updated use:
```
npm version [patch, minor, major] -m "Upgrade to %s for reasons"
```