# Information comes from [dustinspecker/awesome-eslint](https://github.com/dustinspecker/awesome-eslint)
# Awesome ESLint [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="http://eslint.org/img/logo.svg" width="160" align="right" alt="eslint">](http://eslint.org)

> A list of awesome ESLint configs, plugins, etc.

If you want to contribute, please read the [contribution guidelines](contributing.md).

## Contents

- [Configs](#configs)
- [Parsers](#parsers)
- [Plugins](#plugins)
  - [Frameworks and Libraries](#frameworks-and-libraries)
  - [Misc](#misc)
  - [Practices](#practices)
  - [Style](#style)
- [Preconfigured Tools with ESLint Set up](#preconfigured-tools-with-eslint-set-up)
- [Tools](#tools)
- [Developing for ESLint](#developing-for-eslint)
- [Tutorials](#tutorials)

## Configs

- [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Shareable config for [Airbnb's style guide](https://github.com/airbnb/javascript). :star:77420
- [Canonical](https://github.com/gajus/eslint-config-canonical) - Shareable config for [Canonical style guide](https://github.com/gajus/canonical). :star:74
- [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) - Contains the ESLint configuration used for projects maintained by the ESLint team. :star:12588
- [ES](https://github.com/thenativeweb/eslint-config-es) - Shareable config for very strict code. :star:10
- [Facebook](https://www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.
- [Google](https://github.com/google/eslint-config-google) - Shareable config for the [Google style](http://google.github.io/styleguide/javascriptguide.xml). :star:911
- [Problems](https://github.com/RyanZim/eslint-config-problems) - Shareable config that only catches actual problems, and doesn't enforce stylistic preferences. :star:11
- [Shopify](https://github.com/Shopify/eslint-plugin-shopify) - Shareable config for [Shopify's style guide](https://github.com/Shopify/javascript). :star:32
- [Standard](https://github.com/feross/eslint-config-standard) - Shareable config for JavaScript [Standard Style](https://github.com/feross/standard). :star:1244
- [Supermind](https://github.com/supermind/eslint-config-supermind) - Shareable config for Supermind style. :star:2
- [XO](https://github.com/sindresorhus/eslint-config-xo) - Shareable config for [XO](https://github.com/sindresorhus/xo). :star:133

## Parsers

- [Babel](https://github.com/babel/babel-eslint) - Use Babel's parser for linting all Babel features. :star:2369
- [TypeScript](https://github.com/eslint/typescript-eslint-parser) - A TypeScript parser that produces output compatible with ESLint. :star:764
- [BrightScript](https://github.com/RokuRoad/eslint-plugin-roku) - BrightScript plugin for Roku development. Includes Parser and Rules. :star:30

## Plugins

### Frameworks and Libraries

- [Angular](https://github.com/Gillespie59/eslint-plugin-angular) - Linting rules to adhere to the [John Papa's Angular Styleguide](https://github.com/johnpapa/angular-styleguide). :star:580
- [AVA](https://github.com/sindresorhus/eslint-plugin-ava) - Linting rules for AVA. :star:166
- [Backbone](https://github.com/ilyavolodin/eslint-plugin-backbone) - Linting rules for Backbone. :star:93
- [Chai](https://github.com/turbo87/eslint-plugin-chai-expect) - Linting rules for Chai. :star:8
- [Ember](https://github.com/netguru/eslint-plugin-ember) - Linting rules for Ember. :star:194
- [Hapi](https://github.com/continuationlabs/eslint-plugin-hapi) - Linting rules for hapi. :star:17
- [Jasmine](https://github.com/tlvince/eslint-plugin-jasmine) - Linting rules for Jasmine. :star:63
- [Jest](https://github.com/jest-community/eslint-plugin-jest) - Linting rules for Jest. :star:218
- [JSDoc](https://github.com/gajus/eslint-plugin-jsdoc) - Linting rules for JSDoc comments. :star:151
- [Lodash](https://github.com/wix/eslint-plugin-lodash) - Lodash specific linting rules. :star:152
- [Lodash/fp](https://github.com/jfmengels/eslint-plugin-lodash-fp) - Lodash/fp specific linting rules. :star:111
- [Lodash template](https://github.com/ota-meshi/eslint-plugin-lodash-template) - Plugin for Lodash template/Underscore template. :star:2
- [Meteor](https://github.com/dferber90/eslint-plugin-meteor) - Meteor specific linting rules. :star:101
- [Mocha](https://github.com/lo1tuma/eslint-plugin-mocha) - Linting rules for Mocha. :star:184
- [Mongodb](https://github.com/nfroidure/eslint-plugin-mongodb) - Mongodb native Node.js driver linting rules. :star:13
- [Ramda](https://github.com/ramda/eslint-plugin-ramda) - Ramda specific linting rules. :star:78
- [React](https://github.com/yannickcr/eslint-plugin-react) - Linting rules for React and JSX. :star:4619
- [React Native](https://github.com/Intellicode/eslint-plugin-react-native) - React Native specific linting rules. :star:391
- [RequireJS](https://github.com/cvisco/eslint-plugin-requirejs) - Linting rules for RequireJS. :star:24
- [VueJS](https://github.com/vuejs/eslint-plugin-vue) - Plugin for VueJS. :star:1871

### Misc

- [Babel](https://github.com/babel/eslint-plugin-babel) - Adds replacements for built-in rules to include Babel features. :star:294
- [Compat](https://github.com/amilajack/eslint-plugin-compat) - Lint browser compatability of APIs used ([caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin). :star:1987
- [Coffee](https://github.com/aminland/eslint-plugin-coffee) - Enables linting CoffeeScript files with, with optional linting rules from the Coffeelint library. :star:3
- [deprecate](https://github.com/AlexMost/eslint-plugin-deprecate) - Mark functions or modules as deprecated and get lint messages when they are used. :star:28
- [disable](https://github.com/mradionov/eslint-plugin-disable) - Disable specified plugins using file path patterns and inline comments. :star:23
- [es5](https://github.com/nkt/eslint-plugin-es5) - ESLint plugin for ES5 users (forbid ES2015+ usage). :star:21
- [Flow](https://github.com/gajus/eslint-plugin-flowtype) - Flow type linting rules. :star:906
- [Flow Errors](https://github.com/amilajack/eslint-plugin-flowtype-errors) - Run Flow as an ESLint plugin. :star:388
- [GraphQL](https://github.com/apollostack/eslint-plugin-graphql) - Check your GraphQL query strings against a schema. :star:599
- [HTML](https://github.com/BenoitZugmeyer/eslint-plugin-html) - Linting for JavaScript inside of HTML `<script>` tags. :star:240
- [import](https://github.com/benmosher/eslint-plugin-import) - Linting of ES2015+  import/export syntax, and prevent issues with misspelling of file paths and import names. :star:1425
- [JSON](https://github.com/azeemba/eslint-plugin-json) - Lint your JSON files. :star:39
- [Markdown](https://github.com/eslint/eslint-plugin-markdown) - Linting JavaScript in Markdown. :star:153
- [Node](https://github.com/mysticatea/eslint-plugin-node) - Linting rules for Node.js (checking importing paths, ES syntax, ...). :star:359
- [Notice](https://github.com/nickdeis/eslint-plugin-notice) - An eslint rule that checks the top of files and fixes them too! :star:6
- [Optimize Regex](https://github.com/BrainMaestro/eslint-plugin-optimize-regex) - Optimize regex literals. :star:27
- [SonarJS](https://github.com/SonarSource/eslint-plugin-sonarjs) - Rules detecting bugs and suspicious patterns. :star:31
- [SQL](https://github.com/gajus/eslint-plugin-sql) - SQL linting rules for ESLint. :star:12
- [TypeLint](https://github.com/yarax/typelint) - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors. :star:149
- [unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn) - Various awesome ESLint rules. :star:345
- [ESLint Comments](https://github.com/mysticatea/eslint-plugin-eslint-comments) - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc...). :star:63
- [eslint-plugin-eslint-plugin](https://github.com/not-an-aardvark/eslint-plugin-eslint-plugin) - An ESLint plugin for linting ESLint plugins. :star:15

### Practices

- [array-func](https://github.com/freaktechnik/eslint-plugin-array-func) - Avoid redundancy when using es2015 array methods and functions.. :star:9
- [fp](https://github.com/jfmengels/eslint-plugin-fp) - ESLint rules for functional programming. :star:529
- [Immutable](https://github.com/jhusain/eslint-plugin-immutable) - Disable all mutation in JavaScript. :star:770
- [JSX a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y) - Accessibility rules on JSX elements. :star:1157
- [new-with-error](https://github.com/Trott/eslint-plugin-new-with-error) - Require errors to be thrown using `new`. :star:16
- [no-inferred-method-name](https://github.com/johnstonbl01/eslint-no-inferred-method-name) - Custom rule for ESLint that checks for inferred method names within object literals.. :star:27
- [no-loops](https://github.com/buildo/eslint-plugin-no-loops) - It's 2017 and you still use loops? :star:45
- [no-use-extend-native](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) - Prevent using extended native objects. :star:30
- [Promise](https://github.com/xjamundx/eslint-plugin-promise) - Best practices when working with promises. :star:315
- [Security](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node Security. :star:827
- [this](https://github.com/matijs/eslint-plugin-this) - Write pure functions, don't allow `this`. :star:6
- [XSS](https://github.com/Rantanen/eslint-plugin-xss) - Tries to detect XSS issues in codebase before they end up in production. :star:17

### Style

- [filenames](https://github.com/selaux/eslint-plugin-filenames) - Ensure consistent filenames for your JavaScript files. :star:120

## Preconfigured Tools with ESLint Set up

- [Node.js Standard Style](https://github.com/geek/node-style) - Node.js core config. :star:3
- [prettier-standard](https://github.com/sheerun/prettier-standard) - Prettier formatter with custom eslint rules allowed. :star:506
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style. :star:19470
- [Superlint](https://github.com/supermind/superlint) - JavaScript Supermind Style.
- [XO](https://github.com/sindresorhus/xo) - JavaScript happiness style linter ❤️. :star:4099
- [Zoe](https://github.com/jorgegonzalez/zoe) - Universal JavaScript linter and formatter. :star:85

## Tools

- [eslint-cli](https://github.com/eslint/eslint-cli) - This is the `eslint` command that executes a local installed ESLint. :star:42
- [eslint-find-rules](https://github.com/sarbbottam/eslint-find-rules) - Find built-in ESLint rules you don't have in your custom config. :star:100
- [eslint-index](https://github.com/wagerfield/eslint-index) - CLI for finding and managing rules in ESLint config files. :star:10
- [eslint-multiplexer](https://github.com/pimlie/eslint-multiplexer) - Multiplex eslint results and merge results for common files. :star:6
- [eslint-nibble](https://github.com/IanVS/eslint-nibble) - Ease into ESLint, by fixing one rule at a time. :star:185
- [eslint-rule-documentation](https://github.com/jfmengels/eslint-rule-documentation) - Find the url for the documentation of an ESLint rule. :star:22
- [eslint-watch](https://github.com/rizowski/eslint-watch) - Run ESLint with watch mode. :star:116
- [codacy-eslint](https://github.com/codacy/codacy-eslint) - Docker used at [Codacy](https://www.codacy.com) to run ESLint. :star:11
- [esprint](https://github.com/pinterest/esprint) - Run ESLint across multiple threads. :star:302

## Developing for ESLint

- [eslint-docs](https://github.com/j-f1/eslint-docs) - Keep your rule descriptions up-to-date across the repository. :star:1

## Tutorials

- [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin.
- [Lint Like It’s 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint.
- [Linting JavaScript with ESLint](https://egghead.io/lessons/javascript-linting-javascript-with-eslint) - Video showing ESLint setup and basics.
- [Linting React JSX with ESLint (in ES6)](https://egghead.io/lessons/react-linting-react-jsx-with-eslint-in-es6) - Video showing how to use React and JSX with ESLint.
- [Plugin Module with Mixins](https://chrysanthium.com/eslint-integration) - Article on how to write a plugin as a node module containing modular mixin configuration.
- [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

