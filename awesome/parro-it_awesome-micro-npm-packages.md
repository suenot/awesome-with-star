# Information comes from [parro-it/awesome-micro-npm-packages](https://github.com/parro-it/awesome-micro-npm-packages)
# Awesome Micro npm Packages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of small, focused Node.js modules.

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.*


## Articles

* [One-line node modules](https://github.com/sindresorhus/ama/issues/10) :star:989
* [Build small single purpose modules](http://thenodeway.io/introduction/#build-small-single-purpose-modules)
* [Module best practices](https://github.com/mattdesl/module-best-practices) :star:1203
* [Evaluating Packages Part 1 - Turn to community](http://bytearcher.com/articles/evaluating-packages-1-check-community/) 
* [Evaluating Packages Part 2 - Review repository](http://bytearcher.com/articles/evaluating-packages-2-review-repository/)
* [Small modules: it’s not quite that simple](https://medium.com/@Rich_Harris/small-modules-it-s-not-quite-that-simple-3ca532d65de4)
* [Hyper Modular Packages: A Crazy Cult or a Reasonable Practice?](http://thefullstack.xyz/hyper-modular-packages-a-crazy-cult-or-a-reasonable-practice/)
* [In Defense of Hyper Modular JavaScript](https://medium.freecodecamp.com/in-defense-of-hyper-modular-javascript-33934c79e113)
* [Tiny npm package: Guidelines to create a Node.js module following the small package philosophy](http://g14n.info/2015/12/tiny-npm-package/)
* [The cost of small modules](https://nolanlawson.com/2016/08/15/the-cost-of-small-modules/)
* [Why I think "micro-packages" are a good thing.](http://codetunnel.io/why-i-think-micro-packages-are-a-good-thing/)

## Modules

### Array

* [is-sorted](https://github.com/dcousens/is-sorted) - A small module to check if an Array is sorted. :star:15
* [array-first](https://github.com/jonschlinkert/array-first) - Get the first element or first n elements of an array. :star:6
* [array-last](https://github.com/jonschlinkert/array-last) - Return the last element in an array. :star:20
* [arr-flatten](https://github.com/jonschlinkert/arr-flatten) - Recursively flatten an array or arrays. :star:40
* [dedupe](https://github.com/seriousManual/dedupe) - Remove duplicates from an array. :star:17
* [array-range](https://github.com/mattdesl/array-range) - Creates a new array with given range. :star:18
* [arr-diff](https://github.com/jonschlinkert/arr-diff) - Returns an array with only the unique values from the first array, by excluding all values from additional arrays using strict equality for comparisons. :star:27
* [filled-array](https://github.com/sindresorhus/filled-array) - Returns an array filled with the specified input :star:27
* [map-array](https://github.com/parro-it/map-array) - Map object keys and values into an array. :star:4
* [in-array](https://github.com/jonschlinkert/in-array) - Return true if any of passed values exists in array - faster than using indexOf. :star:15
* [unordered-array-remove](https://github.com/mafintosh/unordered-array-remove) - Efficiently remove an element from an unordered array without doing a splice. :star:106
* [array-swap](https://github.com/michaelzoidl/swap-array) - Swap position of two items in an array. :star:5
* [mirrarray](https://github.com/johnwquarles/mirrarray) - Creates a keymirror object from an array of valid keys. :star:3
* [group-array](https://github.com/doowb/group-array) - Group array of objects into lists. :star:26
* [array.chunk](https://github.com/zhiyelee/array.chunk) - Split array/TypedArray to chunks of given size. :star:5

### String

* [decamelize](https://github.com/sindresorhus/decamelize) - Convert a camelized string into a lowercased one with a custom separator: unicornRainbow → unicorn_rainbow. :star:105
* [pad-left](https://github.com/jonschlinkert/pad-left) - Left pad a string with zeros or a specified string. :star:34
* [to-camel-case](https://github.com/ianstormtaylor/to-camel-case) - Convert a string to a camel case. :star:25
* [to-capital-case](https://github.com/ianstormtaylor/to-capital-case) - Convert a string to a capital case. :star:6
* [to-constant-case](https://github.com/ianstormtaylor/to-constant-case) - Convert a string to a constant case. :star:1
* [to-dot-case](https://github.com/ianstormtaylor/to-dot-case) - Convert a string to a dot case. :star:2
* [to-no-case](https://github.com/ianstormtaylor/to-no-case) - Remove an existing case from a string. :star:8
* [to-pascal-case](https://github.com/ianstormtaylor/to-pascal-case) - Convert a string to a pascal case. :star:2
* [to-sentence-case](https://github.com/ianstormtaylor/to-sentence-case) - Convert a string to a sentence case. :star:1
* [to-snake-case](https://github.com/ianstormtaylor/to-snake-case) - Convert a string to a snake case. :star:18
* [to-space-case](https://github.com/ianstormtaylor/to-space-case) - Convert a string to a space case. :star:1
* [to-title-case](https://github.com/ianstormtaylor/to-title-case) - Convert a string to a title case. :star:13
* [node-slug](https://github.com/dodo/node-slug) - slugifies even utf-8 chars. :star:1007
* [rtrim](https://github.com/sergejmueller/rtrim) - Strip whitespace - or other characters - from the end of a string.
* [slice.js](https://github.com/hustcc/slice.js) - Javascript library to engance String.substring / Array.slice with python slice style. :star:23
* [strip-ansi](https://github.com/chalk/strip-ansi) - Strip ANSI escape codes. :star:155
* [striptags](https://github.com/ericnorris/striptags) - An implementation of PHP's strip_tags in Node.js. :star:295
* [parse-next-json-value](https://github.com/ErikOnBike/parse-next-json-value) - Parse next JSON value from string allowing extraneous characters after value. :star:1

### Date & Time

* [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: 1337000000 → 15d 11h 23m 20s. :star:341
* [hirestime](https://github.com/seriousManual/hirestime) - A wrapper around the built-in high resolution timer which simplifies the calculation of timestamps. :star:7
* [periods](https://github.com/timruffles/periods) - Defined time-periods constants for Javascript, in milliseconds. :star:3
* [fecha](https://github.com/taylorhakes/fecha) - Javascript Date formatting and parsing. :star:1580
* [akamai-time-reference](https://github.com/jucrouzet/akamai-time-reference) - Get reference time using Akamai's time reference service. :star:1
* [timeago.js](https://github.com/hustcc/timeago.js) - A tiny(~1.7kb) library used to format date with `*** time ago` statement. :star:3392
* [count-days-in-month](https://github.com/shinnn/count-days-in-month) - Get the number of days in a given month. :star:1
* [time-stamp](https://github.com/jonschlinkert/time-stamp) - Get a formatted timestamp. :star:63
* [twas](https://github.com/vutran/twas) - Generate a relative time string (Example: "3 seconds ago") :star:124

### Object

* [map-obj](https://github.com/sindresorhus/map-obj) - Map object keys and values into a new object. :star:56
* [filter-obj](https://github.com/sindresorhus/filter-obj) - Filter object keys and values into a new object. :star:27
* [object-values](https://github.com/sindresorhus/object-values) - Get the values of an object. :star:18
* [object-pairs](https://github.com/eush77/object-pairs) - Turn an object into list of [key, value] pairs for mapping, iterating or other purposes. :star:2
* [zipmap](https://github.com/landau/zipmap) - Returns a map with the keys mapped to the corresponding vals. zipmap also accepts a single value of objects or pairs. :star:4
* [just-pluck](https://github.com/jarofghosts/just-pluck) - Pluck without the madness. :star:6
* [deep-equal](https://github.com/substack/node-deep-equal) - Node's assert.deepEqual() algorithm as a standalone module. :star:345
* [deep-assign](https://github.com/sindresorhus/deep-assign) - Recursive Object.assign(). :star:246
* [set-value](https://github.com/jonschlinkert/set-value) - Create nested values and any intermediaries dot notation (`'a.b.c'`) paths. :star:77
* [get-value](https://github.com/jonschlinkert/get-value) - Use property paths (a.b.c) to get a nested value from an object. :star:91
* [has-value](https://github.com/jonschlinkert/has-value) - Returns true if a value exists, false if empty. Works with deeply nested values using dot notation (`'a.b.c'`) paths. :star:19
* [has-key-deep](https://github.com/ryanaghdam/has-key-deep) - Deep-search objects for keys. Keys can be searched by providing an array of keys, or using a dot-notiation. :star:1
* [flatkeys](https://github.com/ricardobeat/flatkeys) - Flatten object key hierarchies into a list of strings using a custom separator. :star:3
* [flatten-obj](https://github.com/watson/flatten-obj) - Converts an object literal with deeply nested nodes to a simple key/value object. :star:14
* [is-empty-object](https://github.com/gummesson/is-empty-object) - Check if an object is empty. :star:10
* [stringify-object](https://github.com/yeoman/stringify-object) - Stringify an object/array like JSON.stringify just without all the double-quotes. :star:169
* [sorted-object](https://github.com/domenic/sorted-object) - Returns a copy of an object with its keys sorted. :star:24
* [static-props](https://github.com/fibo/static-props) - Defines static object attributes using `Object.defineProperties` :star:2
* [missing-deep-keys](https://github.com/vladgolubev/missing-deep-keys) - Returns an array of keys from first object that are missing in second.
* [has-own-property](https://github.com/LinusU/has-own-property) - Check if an object has a local property.  :star:2
* [merge-objects](https://github.com/shevaroller/node-merge-objects) - Deep-merge two objects. Arrays that are values of the same object key get concatenated. :star:2
* [deep-object-diff](https://github.com/mattphillips/deep-object-diff) - Deep diff two JavaScript Objects while preserving the data structure. Including nested structures of Arrays and Objects. :star:193

### Function

* [compose-function](https://github.com/stoeffel/compose-function) - Compose a new function from smaller functions `f(g(x))`. :star:36
* [curry](https://github.com/dominictarr/curry) - A curry function without anything too clever. :star:297
* [once](https://github.com/isaacs/once) - Run a function exactly one time. :star:156
* [deep-bind](https://github.com/jonschlinkert/deep-bind) - Bind a context to all functions in an object, including deeply nested functions. :star:7
* [identity-function](https://github.com/substack/identity-function) - Always return the input argument.  :star:7
* [mem](https://github.com/sindresorhus/mem) - An optimization technique used to speed up consecutive function calls by caching the result of calls with identical input. :star:397
* [throttle-debounce](https://github.com/niksy/throttle-debounce) - Throttle/debounce your functions. :star:273
* [compose-tiny](https://github.com/hipstersmoothie/compose-tiny) - A very tiny and fast compose function. :star:35

### Math

* [is-number](https://github.com/jonschlinkert/is-number) - Returns `true` if the value is a number. :star:107

### Stream
* [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise. :star:1443
* [through2-filter](https://github.com/brycebaril/through2-filter) - A through2 to create an Array.prototype.filter analog for streams. :star:28
* [through2-map](https://github.com/brycebaril/through2-map) - A through2 to create an Array.prototype.map analog for streams. :star:62
* [stream-spigot](https://github.com/brycebaril/node-stream-spigot) - A readable stream generator, useful for testing or converting simple functions into Readable streams. :star:15
* [concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result. :star:481
* [JSONStream](https://github.com/dominictarr/JSONStream) - streaming JSON.parse and stringify :star:1581
* [through2-map-promise](https://github.com/RangerMauve/through2-map-promise) - A small promise-based wrapper for through2. :star:2
* [pump](https://github.com/mafintosh/pump) - pipe streams together and close all of them if one of them closes. :star:616
* [split](https://github.com/dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk. :star:325
* [is-stream](https://github.com/sindresorhus/is-stream) - Check if something is a Node.js stream. :star:57
* [syncthrough](https://github.com/mcollina/syncthrough) - Transform your data as it pass by, synchronously. :star:75


### Promise

* [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function. :star:1052
* [promise-all-props](https://github.com/Siilwyn/promise-all-props) - Like `Promise.all` but for object properties. :star:7
* [sleep-promise](https://github.com/brummelte/sleep-promise) - Resolves a promise after a specified delay. :star:35
* [is-promise](https://github.com/then/is-promise) - Test whether an object looks like a promises-a+ promise. :star:68

### File System

* [rimraf](https://github.com/isaacs/rimraf) - A deep deletion module for node (like rm -rf). :star:2782
* [mkdirp](https://github.com/substack/node-mkdirp) - Recursively mkdir, like mkdir -p. :star:1913
* [du](https://github.com/rvagg/node-du) - A simple JavaScript implementation of du -sb. :star:21
* [file-size](https://github.com/Nijikokun/file-size) - Lightweight filesize to human-readable / proportions w/o dependencies. :star:207
* [tmp](https://github.com/raszi/node-tmp) - Temporary file and directory creator for node.js. :star:424
* [fs-promise](https://github.com/kevinbeaty/fs-promise) - Node fs methods as Promise/A+ (optional fs-extra, graceful-fs). :star:173

### Browser

* [delegate](https://github.com/zenorocha/delegate) - Lightweight event delegation. :star:126
* [insert-css](https://github.com/substack/insert-css) - Insert a string of css into the head :star:193
* [dom-element-value](https://github.com/crysalead-js/dom-element-value) - DOM element value getter/setter. :star:4
* [image-promise](https://github.com/bfred-it/image-promise) - Load one or more `<img>`s in a Promise. :star:67
* [get-media-size](https://github.com/bfred-it/get-media-size) - Get the original size of any `img`/`video`/`svg`/`canvas` tags or canvas context. :star:8
* [document-ready](https://github.com/bendrucker/document-ready) - Document ready listener for modern browsers. :star:39
* [copee](https://github.com/styfle/copee) - Copy text from browser to clipboard...natively! :star:38

### Semver

* [semver](https://github.com/npm/node-semver) - The semantic version parser used by npm. :star:2437
* [semver-max](https://github.com/eush77/semver-max) - Find maximum (or minimum) version according to semver. :star:3
* [semver-first-satisfied](https://github.com/parro-it/semver-first-satisfied) - Find minimum in an array of version that satisfies a semver range. :star:2



### CLI

* [abbrev](https://github.com/isaacs/abbrev-js) - Calculate the set of unique abbreviations for a given set of strings. :star:129
* [glob](https://github.com/isaacs/node-glob) - Glob functionality for node.js. :star:5055
* [username](https://github.com/sindresorhus/username) - Get the username of the current user. :star:84
* [minimist](https://github.com/substack/minimist) - Parse argument options. :star:3259
* [png-to-ico](https://github.com/steambap/png-to-ico) - Convert png to windows ico format. :star:38
* [help-version](https://github.com/eush77/help-version) - Easily handle --help and --version arguments in your CLI application :star:2

### Module management

* [pkg-conf](https://github.com/sindresorhus/pkg-conf) - Get namespaced config from the closest package.json. :star:82
* [normalize-pkg](https://github.com/jonschlinkert/normalize-pkg) - Normalize values in package.json to improve compatibility, programmatic readability and usefulness with third party libs. :star:13

### Generators

* [is-generator](https://github.com/blakeembrey/is-generator) - Check whether a given value is a generator function. :star:12

### Other

* [uuid](https://github.com/kelektiv/node-uuid) - Generate RFC-compliant UUIDs in JavaScript. :star:6457
* [node-mime](https://github.com/broofa/node-mime) - Comprehensive MIME type mapping API based on mime-db module. :star:1252
* [not-defined](https://github.com/fibo/not-defined) - Checks if foo is not defined, i.e. undefined, null, an empty string, array or object. :star:1
* [is-fqdn](https://github.com/parro-it/is-fqdn) - Check if a string represent a fully qualified domain name. :star:13

## Related lists

This section contains awesome lists that you may find useful if you use or write small NPM modules.

* [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) - A curated list of delightful Node.js packages and resources. :star:26689
* [awesome-npm](https://github.com/sindresorhus/awesome-npm) - Awesome npm resources and tips. :star:3057

## Small modules rockstars to follow

These people are used to develop awesome NPM modules that follows the single responsibility philosophy.
Follow them to discover new great modules:

[![Sindre Sorhus](https://avatars.githubusercontent.com/u/170270?s=130)](https://github.com/sindresorhus) | [![James Halliday](https://avatars1.githubusercontent.com/u/12631?s=130)](https://github.com/substack) | [![Eugene Sharygin](https://avatars3.githubusercontent.com/u/4472489?s=130)](https://github.com/eush77) | [![Isaac Z. Schlueter](https://avatars3.githubusercontent.com/u/9287?s=130)](https://github.com/isaacs) | [![Jon Schlinkert](https://avatars1.githubusercontent.com/u/383994?s=130)](https://github.com/jonschlinkert) | [![Dominic Tarr](https://avatars3.githubusercontent.com/u/259374?s=130)](https://github.com/dominictarr)
---|---|---|---|---|---
[Sindre Sorhus](https://github.com/sindresorhus) | [James Halliday](https://github.com/substack) | [Eugene Sharygin](https://github.com/eush77) | [Isaac Z. Schlueter](https://github.com/isaacs) | [Jon Schlinkert](https://github.com/jonschlinkert) | [Dominic Tarr](https://github.com/dominictarr)

[![Rod Vagg](https://avatars0.githubusercontent.com/u/495647?s=130)](https://github.com/rvagg) | [![Max Ogden](https://avatars3.githubusercontent.com/u/39759?s=130)](https://github.com/maxogden) | [![Brian Woodward](https://avatars1.githubusercontent.com/u/995160?s=130)](https://github.com/doowb)
---|---|---
[Rod Vagg](https://github.com/rvagg) | [Max Ogden](https://github.com/maxogden) | [Brian Woodward](https://github.com/doowb)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Andrea Parodi](https://github.com/parro-it) has waived all copyright and related or neighboring rights to this work.

