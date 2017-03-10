# Node Module Template

[![Build Status](https://travis-ci.org/tur-nr/node-module-template.svg?branch=master)](https://travis-ci.org/tur-nr/node-module-template)
[![Coverage Status](https://coveralls.io/repos/github/tur-nr/node-module-template/badge.svg?branch=master)](https://coveralls.io/github/tur-nr/node-module-template?branch=master)
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)


Opinionated boilerplate for creating new node modules.

## Usage

Fork repository. Write your code in `src/` and tests in `test/`.

### Building

```sh
yarn run build
```

### What's Inside

- [Yarn](https://yarnpkg.com) package manager.
- [Babel](https://babeljs.io), esnext ([`babel-preset-env`](https://github.com/babel/babel-preset-env)).
- [Gulp](http://gulpjs.com), task and build tool.
- [Jest](https://facebook.github.io/jest), test and coverage.
- [XO](https://github.com/sindresorhus/xo), linting and styling.
- [EditorConfig](http://editorconfig.org/), multi editor configuration.
- [TravisCI](https://travis-ci.org/), CI ready.
- [Coveralls](https://coveralls.io/), coverage reporter.
- [VSCode](https://code.visualstudio.com/), editor linting and fixing ([`vscode-linter-xo`](https://github.com/SamVerschueren/vscode-linter-xo)).

## License

[MIT](LICENSE)

Copyright (c) 2017 [Christopher Turner](https://github.com/tur-nr)
