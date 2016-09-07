[![npm dependencies][project-npm-dependencies]][project-npm-dependencies-url]
[![npm dev dependencies][project-npm-dev-dependencies]][project-npm-dev-dependencies-url]

# node-seed

NodeJS project boilerplate for new modules.

Reduce wasted time creating all these little files

## Usage

1. Clone this repository: `git clone https://github.com/n2geoff/node-seed --bare`
2. Remove .git directory
3. Update package.json
  - set "name"
  - set "version"(0.0.0 by default)
  - set "description"
  - set "author"
  - set "license"
  - set right "keywords" or remove this section
  - set your "repository" or remove this section
  - set "bugs" or remove this section
  - set "homepage" or remove this section
4. Update README.md

## Included

- Code style checker - [jscs](http://jscs.info/)
- Test runner - [tape](https://github.com/substack/tape);
- Test coverage checker - [istanbul](https://github.com/gotwarlost/istanbul/)
- JsDoc generation - [jsdoc](http://usejsdoc.org/)

## Directory Layout

```
  src/                    --> source code
    index.js              --> entry point
  test/                   --> tests
    index.test.js         --> test entry point
  .jscsrc                 --> style checker: crockford
```

[project-npm-dependencies]: https://david-dm.org/n2geoff/node-seed/status.svg
[project-npm-dependencies-url]: https://david-dm.org/n2geoff/node-seed
[project-npm-dev-dependencies]: https://david-dm.org/n2geoff/node-seed/dev-status.svg
[project-npm-dev-dependencies-url]: https://david-dm.org/n2geoff/node-seed#info=devDependencies&view=table
