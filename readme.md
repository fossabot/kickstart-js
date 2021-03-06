# Kickstart JS

Minimal modern starter for client and server JS projects. Including common dependencies, to kickstart JS projects rapidly.

- Eslint: Code style
- Prettier: Code formatting
- babel: Transpile from es6+ (stage 2)
- Webpack: Build and bundle
- SCSS: for working with styles
- Jest: Testing framework
- dotenv: use .env files for environmental config
- git: Source control, basic setup
- editorconfig: consistency between editor setups
- Flow: Unobtrusive Type Annotations for JS

## Why

Starting a JS project with a full setup takes a lot of grunt work. Many boiler-plates and starter projects obscure configs, or are project type specific (react, node, vue etc). This project attempts to create a simple working config with sensible defaults, that is easy to change or extend for your use case, and provides the right foundation for modern, professional development.

## Getting Started

The following will get you going.

1.  Download the zip folder, and unzip this into your project directory.
2.  run `yarn install` (or `npm install` if you prefer)
3.  setup your editor or IDE to use eslint and prettier if necessary
4.  create a `dev.env` and a `prod.env` files. These should be backed up securely, as they are ignored in git.
5.  implement the `start` script in `package.json`
6.  Customize and extend to your preferences
7.  build great things for fun and profit.

## Scripts

a minimal set of scripts have been included in the `package.json` file to get you going quickly. These can be run with `npm run <script>` or `yarn run <script>`.

- start - not implemented, you will need to set this for the kind of project you're building
- test - kicks off the jest test runner, which expects files like `[name].test.js` in the `./tests` folder
- test:watch - run tests in watch mode, rerunning on file change
- build:dev - runs webpack with the `webpack.dev.js` config
- build:prod - runs webpack with the `webpack.prod.js` config
- lint - runs eslint on the src directory
- serve:coverage - serves the html coverage report from jest on `http://localhost:7357`

## Webpack

Webpack has been setup, with a few simple and common plugins. There is a common config, as well as config for `dev` and `prod` in the root directory. Whats included:

- JS es6+ (Babel stage-2)
- copying static assets from src/public to dist/public
- SCSS with autoprefixer

## Project Specific Branches

COMING SOON.

## EXAMPLES

COMING SOON.

---

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FPushplaybang%2Fkickstart-js.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FPushplaybang%2Fkickstart-js?ref=badge_shield)

Copyright 2018 Paul van Zyl

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FPushplaybang%2Fkickstart-js.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FPushplaybang%2Fkickstart-js?ref=badge_large)