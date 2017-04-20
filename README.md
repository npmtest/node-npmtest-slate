# npmtest-slate

#### basic test coverage for  slate (v0.19.20)  [![npm package](https://img.shields.io/npm/v/npmtest-slate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slate.svg)](https://travis-ci.org/npmtest/node-npmtest-slate)

#### A completely customizable framework for building rich text editors.

[![NPM](https://nodei.co/npm/slate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slate/build/test-report.html](https://npmtest.github.io/node-npmtest-slate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "slate",
    "description": "A completely customizable framework for building rich text editors.",
    "version": "0.19.20",
    "license": "MIT",
    "repository": "git://github.com/ianstormtaylor/slate.git",
    "main": "./lib/index.js",
    "dependencies": {
        "cheerio": "^0.22.0",
        "debug": "^2.3.2",
        "direction": "^0.1.5",
        "es6-map": "^0.1.4",
        "esrever": "^0.2.0",
        "get-window": "^1.1.1",
        "immutable": "^3.8.1",
        "is-empty": "^1.0.0",
        "is-in-browser": "^1.1.3",
        "keycode": "^2.1.2",
        "react-portal": "^3.0.0",
        "selection-is-backward": "^1.0.0",
        "type-of": "^2.0.1"
    },
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-core": "^6.9.1",
        "babel-eslint": "^6.1.0",
        "babel-polyfill": "^6.16.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "babelify": "^7.3.0",
        "browserify": "^13.0.1",
        "browserify-global-shim": "^1.0.3",
        "browserify-shim": "^3.8.12",
        "chalk": "^1.1.3",
        "disc": "^1.3.2",
        "envify": "^3.4.1",
        "eslint": "^3.8.1",
        "eslint-plugin-import": "^2.0.1",
        "eslint-plugin-react": "^6.4.1",
        "faker": "^3.1.0",
        "fbjs": "^0.8.3",
        "fs-promise": "^1.0.0",
        "gh-pages": "^0.11.0",
        "http-server": "^0.9.0",
        "is-image": "^1.0.1",
        "is-url": "^1.2.2",
        "jest": "^17.0.3",
        "jsdom": "9.6.0",
        "jsdom-global": "2.1.0",
        "matcha": "^0.7.0",
        "microtime": "2.1.1",
        "mocha": "^2.5.3",
        "np": "^2.9.0",
        "npm-run-all": "^2.3.0",
        "prismjs": "^1.5.1",
        "react": "^15.4.2",
        "react-addons-perf": "^15.4.2",
        "react-dom": "^15.4.2",
        "react-frame-aware-selection-plugin": "^1.0.0",
        "react-frame-component": "^0.6.2",
        "react-router": "^2.5.1",
        "read-metadata": "^1.0.0",
        "read-yaml-promise": "^1.0.2",
        "slate-auto-replace-text": "^0.3.0",
        "slate-collapse-on-escape": "^0.2.0",
        "slate-soft-break": "^0.2.0",
        "source-map-support": "^0.4.0",
        "to-camel-case": "^1.0.0",
        "to-title-case": "^1.0.0",
        "uglify-js": "^2.7.0",
        "uglifyify": "^3.0.2",
        "watchify": "^3.7.0"
    },
    "scripts": {
        "clean": "rm -rf ./lib ./node_modules ./examples/build.dev.js ./examples/build.prod.js",
        "disc": "npm-run-all build disc:build disc:open",
        "disc:build": "mkdir -p ./tmp && browserify ./lib/index.js --full-paths --transform uglifyify --standalone Slate | uglifyjs > ./tmp/build.js",
        "disc:open": "discify ./tmp/build.js --open",
        "build": "mkdir -p ./dist && npm-run-all build:npm build:max build:min",
        "build:max": "NODE_ENV=production browserify ./src/index.js --transform babelify --transform envify --transform [ browserify-global-shim --global ] --standalone Slate > ./dist/slate.js",
        "build:min": "NODE_ENV=production browserify ./src/index.js --transform babelify --transform envify --transform [ browserify-global-shim --global ] --transform uglifyify --standalone Slate | uglifyjs > ./dist/slate.min.js",
        "build:npm": "babel --out-dir ./lib ./src",
        "build:test": "babel --out-dir ./lib ./src --source-maps inline",
        "examples": "npm-run-all examples:dev examples:prod",
        "examples:dev": "browserify --debug --transform babelify ./examples/index.js > ./examples/build.dev.js",
        "examples:prod": "NODE_ENV=production browserify --transform babelify ./examples/index.js > ./examples/build.prod.js",
        "gh-pages": "npm run build && npm run examples && gh-pages --dist ./examples",
        "lint": "eslint --ignore-pattern 'build.dev.js' --ignore-pattern 'build.prod.js' '{examples,src}/**/*.js'",
        "open": "open http://localhost:8080/dev.html",
        "bench": "npm-run-all build:npm benchs",
        "benchs": "babel-node ./node_modules/.bin/_matcha --reporter ./benchmark/reporter ./benchmark/index.js > ./tmp/benchmark-comparison.json && babel-node ./benchmark/compare",
        "benchs:save": "babel-node ./node_modules/.bin/_matcha --reporter ./benchmark/reporter ./benchmark/index.js > ./tmp/benchmark-baseline.json",
        "prepublish": "npm run build",
        "postpublish": "npm run gh-pages",
        "release": "np",
        "release:next": "np --tag=next",
        "start": "http-server ./examples",
        "test": "npm-run-all build:test tests",
        "tests": "mocha --compilers js:babel-core/register ./test/index.js",
        "watch": "npm-run-all --parallel --print-label watch:lib watch:examples start",
        "watch:lib": "babel --watch --out-dir ./lib ./src",
        "watch:examples": "watchify --debug --transform babelify ./examples/index.js -o ./examples/build.dev.js -v"
    },
    "browserify-global-shim": {
        "immutable": "Immutable",
        "react": "React",
        "react-dom": "ReactDOM",
        "react-dom/server": "ReactDOMServer"
    },
    "keywords": [
        "canvas",
        "contenteditable",
        "doc",
        "docs",
        "document",
        "edit",
        "editor",
        "html",
        "immutable",
        "markdown",
        "medium",
        "paper",
        "react",
        "rich",
        "rich-text",
        "richtext",
        "slate",
        "text",
        "wysiwyg",
        "wysiwym"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
