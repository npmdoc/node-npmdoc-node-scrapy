# api documentation for  [node-scrapy (v0.3.1)](https://github.com/eeshi/node-scrapy)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-scrapy.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-scrapy) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-scrapy.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-scrapy)
#### Simple, lightweight and expressive web scraping with Node.js

[![NPM](https://nodei.co/npm/node-scrapy.png?downloads=true)](https://www.npmjs.com/package/node-scrapy)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-scrapy/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node-scrapy_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-scrapy/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-scrapy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-scrapy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stefan Maric",
        "email": "me@stefanmaric.com"
    },
    "bugs": {
        "url": "http://github.com/eeshi/node-scrapy/issues"
    },
    "dependencies": {
        "cheerio": "~0.19.0",
        "request": "^2.46.0"
    },
    "description": "Simple, lightweight and expressive web scraping with Node.js",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "ac6b0e95f94e29e90793cc932655e28253252e18",
        "tarball": "https://registry.npmjs.org/node-scrapy/-/node-scrapy-0.3.1.tgz"
    },
    "engines": [
        "node >= 0.8.0"
    ],
    "gitHead": "071f29ac5cc6eab0e3f4919709002a3bdbfc19ad",
    "homepage": "https://github.com/eeshi/node-scrapy",
    "keywords": [
        "web",
        "html",
        "scraping",
        "scrape",
        "scraper",
        "scrapy",
        "crawler"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "stefanmaric",
            "email": "me@stefanmaric.com"
        }
    ],
    "name": "node-scrapy",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eeshi/node-scrapy.git"
    },
    "scripts": {},
    "version": "0.3.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node-scrapy](#apidoc.module.node-scrapy)
1.  [function <span class="apidocSignatureSpan">node-scrapy.</span>lodash_custom (value)](#apidoc.element.node-scrapy.lodash_custom)
1.  [function <span class="apidocSignatureSpan">node-scrapy.</span>scrape (url, model, options, cb)](#apidoc.element.node-scrapy.scrape)
1.  object <span class="apidocSignatureSpan">node-scrapy.</span>lodash_custom.prototype

#### [module node-scrapy.lodash_custom](#apidoc.module.node-scrapy.lodash_custom)
1.  [function <span class="apidocSignatureSpan">node-scrapy.</span>lodash_custom (value)](#apidoc.element.node-scrapy.lodash_custom.lodash_custom)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>_ (value)](#apidoc.element.node-scrapy.lodash_custom._)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>assign (object, source, guard)](#apidoc.element.node-scrapy.lodash_custom.assign)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>bind (func, thisArg)](#apidoc.element.node-scrapy.lodash_custom.bind)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>chain (value)](#apidoc.element.node-scrapy.lodash_custom.chain)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>cloneDeep (value, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.cloneDeep)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>defaultsDeep ()](#apidoc.element.node-scrapy.lodash_custom.defaultsDeep)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>each (collection, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.each)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>extend (object, source, guard)](#apidoc.element.node-scrapy.lodash_custom.extend)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>forEach (collection, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.forEach)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>forIn (collection, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.forIn)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>forOwn (collection, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.forOwn)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>functions (object)](#apidoc.element.node-scrapy.lodash_custom.functions)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>identity (value)](#apidoc.element.node-scrapy.lodash_custom.identity)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>isArray ()](#apidoc.element.node-scrapy.lodash_custom.isArray)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>isFunction (value)](#apidoc.element.node-scrapy.lodash_custom.isFunction)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>isObject (value)](#apidoc.element.node-scrapy.lodash_custom.isObject)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>isPlainObject (value)](#apidoc.element.node-scrapy.lodash_custom.isPlainObject)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>keys (object)](#apidoc.element.node-scrapy.lodash_custom.keys)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>merge (object)](#apidoc.element.node-scrapy.lodash_custom.merge)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>methods (object)](#apidoc.element.node-scrapy.lodash_custom.methods)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>mixin (object, source, options)](#apidoc.element.node-scrapy.lodash_custom.mixin)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>noop ()](#apidoc.element.node-scrapy.lodash_custom.noop)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>partialRight (func)](#apidoc.element.node-scrapy.lodash_custom.partialRight)
1.  object <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>support
1.  string <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>VERSION

#### [module node-scrapy.lodash_custom.prototype](#apidoc.module.node-scrapy.lodash_custom.prototype)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>assign ()](#apidoc.element.node-scrapy.lodash_custom.prototype.assign)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>bind ()](#apidoc.element.node-scrapy.lodash_custom.prototype.bind)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>chain ()](#apidoc.element.node-scrapy.lodash_custom.prototype.chain)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>cloneDeep ()](#apidoc.element.node-scrapy.lodash_custom.prototype.cloneDeep)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>concat ()](#apidoc.element.node-scrapy.lodash_custom.prototype.concat)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>defaultsDeep ()](#apidoc.element.node-scrapy.lodash_custom.prototype.defaultsDeep)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>each ()](#apidoc.element.node-scrapy.lodash_custom.prototype.each)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>extend ()](#apidoc.element.node-scrapy.lodash_custom.prototype.extend)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>forEach ()](#apidoc.element.node-scrapy.lodash_custom.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>forIn ()](#apidoc.element.node-scrapy.lodash_custom.prototype.forIn)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>forOwn ()](#apidoc.element.node-scrapy.lodash_custom.prototype.forOwn)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>functions ()](#apidoc.element.node-scrapy.lodash_custom.prototype.functions)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>identity ()](#apidoc.element.node-scrapy.lodash_custom.prototype.identity)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>isArray ()](#apidoc.element.node-scrapy.lodash_custom.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>isFunction ()](#apidoc.element.node-scrapy.lodash_custom.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>isObject ()](#apidoc.element.node-scrapy.lodash_custom.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>isPlainObject ()](#apidoc.element.node-scrapy.lodash_custom.prototype.isPlainObject)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>join ()](#apidoc.element.node-scrapy.lodash_custom.prototype.join)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>keys ()](#apidoc.element.node-scrapy.lodash_custom.prototype.keys)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>merge ()](#apidoc.element.node-scrapy.lodash_custom.prototype.merge)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>methods ()](#apidoc.element.node-scrapy.lodash_custom.prototype.methods)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>mixin ()](#apidoc.element.node-scrapy.lodash_custom.prototype.mixin)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>noop ()](#apidoc.element.node-scrapy.lodash_custom.prototype.noop)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>partialRight ()](#apidoc.element.node-scrapy.lodash_custom.prototype.partialRight)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>pop ()](#apidoc.element.node-scrapy.lodash_custom.prototype.pop)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>push ()](#apidoc.element.node-scrapy.lodash_custom.prototype.push)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>reverse ()](#apidoc.element.node-scrapy.lodash_custom.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>shift ()](#apidoc.element.node-scrapy.lodash_custom.prototype.shift)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>slice ()](#apidoc.element.node-scrapy.lodash_custom.prototype.slice)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>sort ()](#apidoc.element.node-scrapy.lodash_custom.prototype.sort)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>splice ()](#apidoc.element.node-scrapy.lodash_custom.prototype.splice)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>support (n, guard)](#apidoc.element.node-scrapy.lodash_custom.prototype.support)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>toString ()](#apidoc.element.node-scrapy.lodash_custom.prototype.toString)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>unshift ()](#apidoc.element.node-scrapy.lodash_custom.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>value ()](#apidoc.element.node-scrapy.lodash_custom.prototype.value)
1.  [function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>valueOf ()](#apidoc.element.node-scrapy.lodash_custom.prototype.valueOf)



# <a name="apidoc.module.node-scrapy"></a>[module node-scrapy](#apidoc.module.node-scrapy)

#### <a name="apidoc.element.node-scrapy.lodash_custom"></a>[function <span class="apidocSignatureSpan">node-scrapy.</span>lodash_custom (value)](#apidoc.element.node-scrapy.lodash_custom)
- description and source-code
```javascript
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
  return (value && typeof value == 'object' && !isArray(value) && hasOwnProperty.call(value, '__wrapped__'))
   ? value
   : new lodashWrapper(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.scrape"></a>[function <span class="apidocSignatureSpan">node-scrapy.</span>scrape (url, model, options, cb)](#apidoc.element.node-scrapy.scrape)
- description and source-code
```javascript
function scrape(url, model, options, cb) {

<span class="apidocCodeCommentSpan">  /**
   * Make 'options' argument optional
   */
</span>
  if ('function' === typeof options) {

    /**
     * Interchange 'cb''s position and fill 'options' with nice defaults
     */

    cb = options;
    options = _.cloneDeep(DEFAULTS);

  } else {

    /**
     * Merge all options from 'DEFAULTS' not present in 'options'
     */

    _.defaultsDeep(options, DEFAULTS);

  }

  /**
   * Set 'request''s Uniform Resource Identifier to provied 'url'
   * @type {string}
   */

  options.requestOptions.uri = url;

  /**
   * Call 'request()' to get the resource
   */

  request(options.requestOptions, processResponse);

  /**
   * Handle 'request()''s result: Chain 'err' or proceed to parse the resource.
   */

  function processResponse(err, res, body) {

    if (err) { return cb(err); }

    if (res.statusCode !== 200) {
      return cb(new ScrapeError('Not OK response from server.', res, body));
    }

    parseBody(body, model, options, cb);

  }
}
```
- example usage
```shell
...
## Scraping made simple

'''js
var scrapy = require('node-scrapy')
  , url = 'https://github.com/strongloop/express'
  , selector = '.repository-description'

scrapy.scrape(url, selector, function(err, data) {
    if (err) return console.error(err)
    console.log(data)
});

// 'Fast, unopinionated, minimalist web framework for node.'
'''
...
```



# <a name="apidoc.module.node-scrapy.lodash_custom"></a>[module node-scrapy.lodash_custom](#apidoc.module.node-scrapy.lodash_custom)

#### <a name="apidoc.element.node-scrapy.lodash_custom.lodash_custom"></a>[function <span class="apidocSignatureSpan">node-scrapy.</span>lodash_custom (value)](#apidoc.element.node-scrapy.lodash_custom.lodash_custom)
- description and source-code
```javascript
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
  return (value && typeof value == 'object' && !isArray(value) && hasOwnProperty.call(value, '__wrapped__'))
   ? value
   : new lodashWrapper(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom._"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>_ (value)](#apidoc.element.node-scrapy.lodash_custom._)
- description and source-code
```javascript
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
  return (value && typeof value == 'object' && !isArray(value) && hasOwnProperty.call(value, '__wrapped__'))
   ? value
   : new lodashWrapper(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.assign"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>assign (object, source, guard)](#apidoc.element.node-scrapy.lodash_custom.assign)
- description and source-code
```javascript
assign = function (object, source, guard) {
  var index, iterable = object, result = iterable;
  if (!iterable) return result;
  var args = arguments,
      argsIndex = 0,
      argsLength = typeof guard == 'number' ? 2 : args.length;
  if (argsLength > 3 && typeof args[argsLength - 2] == 'function') {
    var callback = baseCreateCallback(args[--argsLength - 1], args[argsLength--], 2);
  } else if (argsLength > 2 && typeof args[argsLength - 1] == 'function') {
    callback = args[--argsLength];
  }
  while (++argsIndex < argsLength) {
    iterable = args[argsIndex];
    if (iterable && objectTypes[typeof iterable]) {
    var ownIndex = -1,
        ownProps = objectTypes[typeof iterable] && keys(iterable),
        length = ownProps ? ownProps.length : 0;

    while (++ownIndex < length) {
      index = ownProps[ownIndex];
      result[index] = callback ? callback(result[index], iterable[index]) : iterable[index];
    }
    }
  }
  return result
}
```
- example usage
```shell
...
* @param {Object} object The destination object.
* @param {...Object} [source] The source objects.
* @param {Function} [callback] The function to customize assigning values.
* @param {*} [thisArg] The 'this' binding of 'callback'.
* @returns {Object} Returns the destination object.
* @example
*
* _.assign({ 'name': 'fred' }, { 'employer': 'slate' });
* // => { 'name': 'fred', 'employer': 'slate' }
*
* var defaults = _.partialRight(_.assign, function(a, b) {
*   return typeof a == 'undefined' ? b : a;
* });
*
* var object = { 'name': 'barney' };
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.bind"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>bind (func, thisArg)](#apidoc.element.node-scrapy.lodash_custom.bind)
- description and source-code
```javascript
function bind(func, thisArg) {
  return arguments.length > 2
    ? createWrapper(func, 17, slice(arguments, 2), null, thisArg)
    : createWrapper(func, 1, null, null, thisArg);
}
```
- example usage
```shell
...
 * @returns {Function} Returns the new bound function.
 * @example
 *
 * var func = function(greeting) {
 *   return greeting + ' ' + this.name;
 * };
 *
 * func = _.bind(func, { 'name': 'fred' }, 'hi');
 * func();
 * // => 'hi fred'
 */
function bind(func, thisArg) {
  return arguments.length > 2
    ? createWrapper(func, 17, slice(arguments, 2), null, thisArg)
    : createWrapper(func, 1, null, null, thisArg);
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.chain"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>chain (value)](#apidoc.element.node-scrapy.lodash_custom.chain)
- description and source-code
```javascript
function chain(value) {
  value = new lodashWrapper(value);
  value.__chain__ = true;
  return value;
}
```
- example usage
```shell
...
 *
 * var characters = [
 *   { 'name': 'barney',  'age': 36 },
 *   { 'name': 'fred',    'age': 40 },
 *   { 'name': 'pebbles', 'age': 1 }
 * ];
 *
 * var youngest = _.chain(characters)
 *     .sortBy('age')
 *     .map(function(chr) { return chr.name + ' is ' + chr.age; })
 *     .first()
 *     .value();
 * // => 'pebbles is 1'
 */
function chain(value) {
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.cloneDeep"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>cloneDeep (value, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.cloneDeep)
- description and source-code
```javascript
function cloneDeep(value, callback, thisArg) {
  return baseClone(value, true, typeof callback == 'function' && baseCreateCallback(callback, thisArg, 1));
}
```
- example usage
```shell
...
  if ('function' === typeof options) {

/**
 * Interchange 'cb''s position and fill 'options' with nice defaults
 */

cb = options;
options = _.cloneDeep(DEFAULTS);

  } else {

/**
 * Merge all options from 'DEFAULTS' not present in 'options'
 */
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.defaultsDeep"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>defaultsDeep ()](#apidoc.element.node-scrapy.lodash_custom.defaultsDeep)
- description and source-code
```javascript
function bound() {
  var thisBinding = isBind ? thisArg : this;
  if (partialArgs) {
    var args = slice(partialArgs);
    push.apply(args, arguments);
  }
  if (partialRightArgs || isCurry) {
    args || (args = slice(arguments));
    if (partialRightArgs) {
      push.apply(args, partialRightArgs);
    }
    if (isCurry && args.length < arity) {
      bitmask |= 16 & ~32;
      return baseCreateWrapper([func, (isCurryBound ? bitmask : bitmask & ~3), args, null, thisArg, arity]);
    }
  }
  args || (args = arguments);
  if (isBindKey) {
    func = thisBinding[key];
  }
  if (this instanceof bound) {
    thisBinding = baseCreate(func.prototype);
    var result = func.apply(thisBinding, args);
    return isObject(result) ? result : thisBinding;
  }
  return func.apply(thisBinding, args);
}
```
- example usage
```shell
...
 *   likes: ['html','css'],
 *   active: true,
 *   mainProject: {
 *     name: 'supervisor'
 *   }
 * }
 *
 * _.defaultsDeep(sam, DEFAULTS)
 * // {name:"Sam",likes:["html","css"],active:true,mainProject:{name:"supervisor",org:"esshi"},org:"eeshi"}
 *
 * sam.mainProject === DEFAULTS.mainProject
 * // false
 */

_.mixin({
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.each"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>each (collection, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.each)
- description and source-code
```javascript
function forEach(collection, callback, thisArg) {
  var index = -1,
      length = collection ? collection.length : 0;

  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    while (++index < length) {
      if (callback(collection[index], index, collection) === false) {
        break;
      }
    }
  } else {
    forOwn(collection, callback);
  }
  return collection;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.extend"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>extend (object, source, guard)](#apidoc.element.node-scrapy.lodash_custom.extend)
- description and source-code
```javascript
extend = function (object, source, guard) {
  var index, iterable = object, result = iterable;
  if (!iterable) return result;
  var args = arguments,
      argsIndex = 0,
      argsLength = typeof guard == 'number' ? 2 : args.length;
  if (argsLength > 3 && typeof args[argsLength - 2] == 'function') {
    var callback = baseCreateCallback(args[--argsLength - 1], args[argsLength--], 2);
  } else if (argsLength > 2 && typeof args[argsLength - 1] == 'function') {
    callback = args[--argsLength];
  }
  while (++argsIndex < argsLength) {
    iterable = args[argsIndex];
    if (iterable && objectTypes[typeof iterable]) {
    var ownIndex = -1,
        ownProps = objectTypes[typeof iterable] && keys(iterable),
        length = ownProps ? ownProps.length : 0;

    while (++ownIndex < length) {
      index = ownProps[ownIndex];
      result[index] = callback ? callback(result[index], iterable[index]) : iterable[index];
    }
    }
  }
  return result
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.forEach"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>forEach (collection, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.forEach)
- description and source-code
```javascript
function forEach(collection, callback, thisArg) {
  var index = -1,
      length = collection ? collection.length : 0;

  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    while (++index < length) {
      if (callback(collection[index], index, collection) === false) {
        break;
      }
    }
  } else {
    forOwn(collection, callback);
  }
  return collection;
}
```
- example usage
```shell
...
 * @category Collections
 * @param {Array|Object|string} collection The collection to iterate over.
 * @param {Function} [callback=identity] The function called per iteration.
 * @param {*} [thisArg] The 'this' binding of 'callback'.
 * @returns {Array|Object|string} Returns 'collection'.
 * @example
 *
 * _([1, 2, 3]).forEach(function(num) { console.log(num); }).join(',');
 * // => logs each number and returns '1,2,3'
 *
 * _.forEach({ 'one': 1, 'two': 2, 'three': 3 }, function(num) { console.log(num); });
 * // => logs each number and returns the object (property order is not guaranteed across environments)
 */
function forEach(collection, callback, thisArg) {
  var index = -1,
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.forIn"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>forIn (collection, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.forIn)
- description and source-code
```javascript
forIn = function (collection, callback, thisArg) {
  var index, iterable = collection, result = iterable;
  if (!iterable) return result;
  if (!objectTypes[typeof iterable]) return result;
  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
    for (index in iterable) {
      if (callback(iterable[index], index, collection) === false) return result;
    }
  return result
}
```
- example usage
```shell
...
 * }
 *
 * Shape.prototype.move = function(x, y) {
 *   this.x += x;
 *   this.y += y;
 * };
 *
 * _.forIn(new Shape, function(value, key) {
 *   console.log(key);
 * });
 * // => logs 'x', 'y', and 'move' (property order is not guaranteed across environments)
 */
var forIn = function(collection, callback, thisArg) {
  var index, iterable = collection, result = iterable;
  if (!iterable) return result;
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.forOwn"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>forOwn (collection, callback, thisArg)](#apidoc.element.node-scrapy.lodash_custom.forOwn)
- description and source-code
```javascript
forOwn = function (collection, callback, thisArg) {
  var index, iterable = collection, result = iterable;
  if (!iterable) return result;
  if (!objectTypes[typeof iterable]) return result;
  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
    var ownIndex = -1,
        ownProps = objectTypes[typeof iterable] && keys(iterable),
        length = ownProps ? ownProps.length : 0;

    while (++ownIndex < length) {
      index = ownProps[ownIndex];
      if (callback(iterable[index], index, collection) === false) return result;
    }
  return result
}
```
- example usage
```shell
...
 * @category Objects
 * @param {Object} object The object to iterate over.
 * @param {Function} [callback=identity] The function called per iteration.
 * @param {*} [thisArg] The 'this' binding of 'callback'.
 * @returns {Object} Returns 'object'.
 * @example
 *
 * _.forOwn({ '0': 'zero', '1': 'one', 'length': 2 }, function(num, key) {
 *   console.log(key);
 * });
 * // => logs '0', '1', and 'length' (property order is not guaranteed across environments)
 */
var forOwn = function(collection, callback, thisArg) {
  var index, iterable = collection, result = iterable;
  if (!iterable) return result;
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.functions"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>functions (object)](#apidoc.element.node-scrapy.lodash_custom.functions)
- description and source-code
```javascript
function functions(object) {
  var result = [];
  forIn(object, function(value, key) {
    if (isFunction(value)) {
      result.push(key);
    }
  });
  return result.sort();
}
```
- example usage
```shell
...
 * @memberOf _
 * @alias methods
 * @category Objects
 * @param {Object} object The object to inspect.
 * @returns {Array} Returns an array of property names that have function values.
 * @example
 *
 * _.functions(_);
 * // => ['all', 'any', 'bind', 'bindAll', 'clone', 'compact', 'compose', ...]
 */
function functions(object) {
  var result = [];
  forIn(object, function(value, key) {
    if (isFunction(value)) {
      result.push(key);
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.identity"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>identity (value)](#apidoc.element.node-scrapy.lodash_custom.identity)
- description and source-code
```javascript
function identity(value) {
  return value;
}
```
- example usage
```shell
...
 * @memberOf _
 * @category Utilities
 * @param {*} value Any value.
 * @returns {*} Returns 'value'.
 * @example
 *
 * var object = { 'name': 'fred' };
 * _.identity(object) === object;
 * // => true
 */
function identity(value) {
  return value;
}

/**
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.isArray"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>isArray ()](#apidoc.element.node-scrapy.lodash_custom.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
...
 * // => 6
 *
 * // returns a wrapped value
 * var squares = wrapped.map(function(num) {
 *   return num * num;
 * });
 *
 * _.isArray(squares);
 * // => false
 *
 * _.isArray(squares.value());
 * // => true
 */
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.isFunction"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>isFunction (value)](#apidoc.element.node-scrapy.lodash_custom.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  return typeof value == 'function';
}
```
- example usage
```shell
...
 * @static
 * @memberOf _
 * @category Objects
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if the 'value' is a function, else 'false'.
 * @example
 *
 * _.isFunction(_);
 * // => true
 */
function isFunction(value) {
  return typeof value == 'function';
}

/**
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.isObject"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>isObject (value)](#apidoc.element.node-scrapy.lodash_custom.isObject)
- description and source-code
```javascript
function isObject(value) {
  // check if the value is the ECMAScript language type of Object
  // http://es5.github.io/#x8
  // and avoid a V8 bug
  // http://code.google.com/p/v8/issues/detail?id=2291
  return !!(value && objectTypes[typeof value]);
}
```
- example usage
```shell
...
* @static
* @memberOf _
* @category Objects
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if the 'value' is an object, else 'false'.
* @example
*
* _.isObject({});
* // => true
*
* _.isObject([1, 2, 3]);
* // => true
*
* _.isObject(1);
* // => false
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.isPlainObject"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>isPlainObject (value)](#apidoc.element.node-scrapy.lodash_custom.isPlainObject)
- description and source-code
```javascript
isPlainObject = function (value) {
  if (!(value && toString.call(value) == objectClass)) {
    return false;
  }
  var valueOf = value.valueOf,
      objProto = isNative(valueOf) && (objProto = getPrototypeOf(valueOf)) && getPrototypeOf(objProto);

  return objProto
    ? (value == objProto || getPrototypeOf(value) == objProto)
    : shimIsPlainObject(value);
}
```
- example usage
```shell
...
* @example
*
* function Shape() {
*   this.x = 0;
*   this.y = 0;
* }
*
* _.isPlainObject(new Shape);
* // => false
*
* _.isPlainObject([1, 2, 3]);
* // => false
*
* _.isPlainObject({ 'x': 0, 'y': 0 });
* // => true
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.keys"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>keys (object)](#apidoc.element.node-scrapy.lodash_custom.keys)
- description and source-code
```javascript
keys = function (object) {
  if (!isObject(object)) {
    return [];
  }
  return nativeKeys(object);
}
```
- example usage
```shell
...
 * @static
 * @memberOf _
 * @category Objects
 * @param {Object} object The object to inspect.
 * @returns {Array} Returns an array of property names.
 * @example
 *
 * _.keys({ 'one': 1, 'two': 2, 'three': 3 });
 * // => ['one', 'two', 'three'] (property order is not guaranteed across environments)
 */
var keys = !nativeKeys ? shimKeys : function(object) {
  if (!isObject(object)) {
    return [];
  }
  return nativeKeys(object);
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.merge"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>merge (object)](#apidoc.element.node-scrapy.lodash_custom.merge)
- description and source-code
```javascript
function merge(object) {
  var args = arguments,
      length = 2;

  if (!isObject(object)) {
    return object;
  }
  // allows working with '_.reduce' and '_.reduceRight' without using
  // their 'index' and 'collection' arguments
  if (typeof args[2] != 'number') {
    length = args.length;
  }
  if (length > 3 && typeof args[length - 2] == 'function') {
    var callback = baseCreateCallback(args[--length - 1], args[length--], 2);
  } else if (length > 2 && typeof args[length - 1] == 'function') {
    callback = args[--length];
  }
  var sources = slice(arguments, 1, length),
      index = -1,
      stackA = getArray(),
      stackB = getArray();

  while (++index < length) {
    baseMerge(object, sources[index], callback, stackA, stackB);
  }
  releaseArray(stackA);
  releaseArray(stackB);
  return object;
}
```
- example usage
```shell
...
 *
 * sam.mainProject === DEFAULTS.mainProject
 * // false
 */

_.mixin({
  'defaultsDeep': _.partialRight(_.merge, function deep(value, other) {
      return _.merge(value, other, deep);
    })
});

/**
 * Custom Error for node-scrapy
 */
function ScrapeError(msg, response, bodyString) {
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.methods"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>methods (object)](#apidoc.element.node-scrapy.lodash_custom.methods)
- description and source-code
```javascript
function functions(object) {
  var result = [];
  forIn(object, function(value, key) {
    if (isFunction(value)) {
      result.push(key);
    }
  });
  return result.sort();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.mixin"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>mixin (object, source, options)](#apidoc.element.node-scrapy.lodash_custom.mixin)
- description and source-code
```javascript
function mixin(object, source, options) {
  var chain = true,
      methodNames = source && functions(source);

  if (!source || (!options && !methodNames.length)) {
    if (options == null) {
      options = source;
    }
    ctor = lodashWrapper;
    source = object;
    object = lodash;
    methodNames = functions(source);
  }
  if (options === false) {
    chain = false;
  } else if (isObject(options) && 'chain' in options) {
    chain = options.chain;
  }
  var ctor = object,
      isFunc = isFunction(ctor);

  forEach(methodNames, function(methodName) {
    var func = object[methodName] = source[methodName];
    if (isFunc) {
      ctor.prototype[methodName] = function() {
        var chainAll = this.__chain__,
            value = this.__wrapped__,
            args = [value];

        push.apply(args, arguments);
        var result = func.apply(object, args);
        if (chain || chainAll) {
          if (value === result && isObject(result)) {
            return this;
          }
          result = new ctor(result);
          result.__chain__ = chainAll;
        }
        return result;
      };
    }
  });
}
```
- example usage
```shell
...
* _.defaultsDeep(sam, DEFAULTS)
* // {name:"Sam",likes:["html","css"],active:true,mainProject:{name:"supervisor",org:"esshi"},org:"eeshi"}
*
* sam.mainProject === DEFAULTS.mainProject
* // false
*/

_.mixin({
 'defaultsDeep': _.partialRight(_.merge, function deep(value, other) {
     return _.merge(value, other, deep);
   })
});

/**
* Custom Error for node-scrapy
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.noop"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>noop ()](#apidoc.element.node-scrapy.lodash_custom.noop)
- description and source-code
```javascript
function noop() {
  // no operation performed
}
```
- example usage
```shell
...
 *
 * @static
 * @memberOf _
 * @category Utilities
 * @example
 *
 * var object = { 'name': 'fred' };
 * _.noop(object) === undefined;
 * // => true
 */
function noop() {
  // no operation performed
}

/*--------------------------------------------------------------------------*/
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.partialRight"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.</span>partialRight (func)](#apidoc.element.node-scrapy.lodash_custom.partialRight)
- description and source-code
```javascript
function partialRight(func) {
  return createWrapper(func, 32, null, slice(arguments, 1));
}
```
- example usage
```shell
...
* // {name:"Sam",likes:["html","css"],active:true,mainProject:{name:"supervisor",org:"esshi"},org:"eeshi"}
*
* sam.mainProject === DEFAULTS.mainProject
* // false
*/

_.mixin({
 'defaultsDeep': _.partialRight(_.merge, function deep(value, other) {
     return _.merge(value, other, deep);
   })
});

/**
* Custom Error for node-scrapy
*/
...
```



# <a name="apidoc.module.node-scrapy.lodash_custom.prototype"></a>[module node-scrapy.lodash_custom.prototype](#apidoc.module.node-scrapy.lodash_custom.prototype)

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.assign"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>assign ()](#apidoc.element.node-scrapy.lodash_custom.prototype.assign)
- description and source-code
```javascript
assign = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
* @param {Object} object The destination object.
* @param {...Object} [source] The source objects.
* @param {Function} [callback] The function to customize assigning values.
* @param {*} [thisArg] The 'this' binding of 'callback'.
* @returns {Object} Returns the destination object.
* @example
*
* _.assign({ 'name': 'fred' }, { 'employer': 'slate' });
* // => { 'name': 'fred', 'employer': 'slate' }
*
* var defaults = _.partialRight(_.assign, function(a, b) {
*   return typeof a == 'undefined' ? b : a;
* });
*
* var object = { 'name': 'barney' };
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.bind"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>bind ()](#apidoc.element.node-scrapy.lodash_custom.prototype.bind)
- description and source-code
```javascript
bind = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * @returns {Function} Returns the new bound function.
 * @example
 *
 * var func = function(greeting) {
 *   return greeting + ' ' + this.name;
 * };
 *
 * func = _.bind(func, { 'name': 'fred' }, 'hi');
 * func();
 * // => 'hi fred'
 */
function bind(func, thisArg) {
  return arguments.length > 2
    ? createWrapper(func, 17, slice(arguments, 2), null, thisArg)
    : createWrapper(func, 1, null, null, thisArg);
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.chain"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>chain ()](#apidoc.element.node-scrapy.lodash_custom.prototype.chain)
- description and source-code
```javascript
function wrapperChain() {
  this.__chain__ = true;
  return this;
}
```
- example usage
```shell
...
 *
 * var characters = [
 *   { 'name': 'barney',  'age': 36 },
 *   { 'name': 'fred',    'age': 40 },
 *   { 'name': 'pebbles', 'age': 1 }
 * ];
 *
 * var youngest = _.chain(characters)
 *     .sortBy('age')
 *     .map(function(chr) { return chr.name + ' is ' + chr.age; })
 *     .first()
 *     .value();
 * // => 'pebbles is 1'
 */
function chain(value) {
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.cloneDeep"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>cloneDeep ()](#apidoc.element.node-scrapy.lodash_custom.prototype.cloneDeep)
- description and source-code
```javascript
cloneDeep = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
  if ('function' === typeof options) {

/**
 * Interchange 'cb''s position and fill 'options' with nice defaults
 */

cb = options;
options = _.cloneDeep(DEFAULTS);

  } else {

/**
 * Merge all options from 'DEFAULTS' not present in 'options'
 */
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.concat"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>concat ()](#apidoc.element.node-scrapy.lodash_custom.prototype.concat)
- description and source-code
```javascript
concat = function () {
  return new lodashWrapper(func.apply(this.__wrapped__, arguments), this.__chain__);
}
```
- example usage
```shell
...
 *
 * var otherFood = {
 *   'fruits': ['banana'],
 *   'vegetables': ['carrot']
 * };
 *
 * _.merge(food, otherFood, function(a, b) {
 *   return _.isArray(a) ? a.concat(b) : undefined;
 * });
 * // => { 'fruits': ['apple', 'banana'], 'vegetables': ['beet', 'carrot] }
 */
function merge(object) {
  var args = arguments,
      length = 2;
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.defaultsDeep"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>defaultsDeep ()](#apidoc.element.node-scrapy.lodash_custom.prototype.defaultsDeep)
- description and source-code
```javascript
defaultsDeep = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 *   likes: ['html','css'],
 *   active: true,
 *   mainProject: {
 *     name: 'supervisor'
 *   }
 * }
 *
 * _.defaultsDeep(sam, DEFAULTS)
 * // {name:"Sam",likes:["html","css"],active:true,mainProject:{name:"supervisor",org:"esshi"},org:"eeshi"}
 *
 * sam.mainProject === DEFAULTS.mainProject
 * // false
 */

_.mixin({
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.each"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>each ()](#apidoc.element.node-scrapy.lodash_custom.prototype.each)
- description and source-code
```javascript
each = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.extend"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>extend ()](#apidoc.element.node-scrapy.lodash_custom.prototype.extend)
- description and source-code
```javascript
extend = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.forEach"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>forEach ()](#apidoc.element.node-scrapy.lodash_custom.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * @category Collections
 * @param {Array|Object|string} collection The collection to iterate over.
 * @param {Function} [callback=identity] The function called per iteration.
 * @param {*} [thisArg] The 'this' binding of 'callback'.
 * @returns {Array|Object|string} Returns 'collection'.
 * @example
 *
 * _([1, 2, 3]).forEach(function(num) { console.log(num); }).join(',');
 * // => logs each number and returns '1,2,3'
 *
 * _.forEach({ 'one': 1, 'two': 2, 'three': 3 }, function(num) { console.log(num); });
 * // => logs each number and returns the object (property order is not guaranteed across environments)
 */
function forEach(collection, callback, thisArg) {
  var index = -1,
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.forIn"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>forIn ()](#apidoc.element.node-scrapy.lodash_custom.prototype.forIn)
- description and source-code
```javascript
forIn = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * }
 *
 * Shape.prototype.move = function(x, y) {
 *   this.x += x;
 *   this.y += y;
 * };
 *
 * _.forIn(new Shape, function(value, key) {
 *   console.log(key);
 * });
 * // => logs 'x', 'y', and 'move' (property order is not guaranteed across environments)
 */
var forIn = function(collection, callback, thisArg) {
  var index, iterable = collection, result = iterable;
  if (!iterable) return result;
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.forOwn"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>forOwn ()](#apidoc.element.node-scrapy.lodash_custom.prototype.forOwn)
- description and source-code
```javascript
forOwn = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * @category Objects
 * @param {Object} object The object to iterate over.
 * @param {Function} [callback=identity] The function called per iteration.
 * @param {*} [thisArg] The 'this' binding of 'callback'.
 * @returns {Object} Returns 'object'.
 * @example
 *
 * _.forOwn({ '0': 'zero', '1': 'one', 'length': 2 }, function(num, key) {
 *   console.log(key);
 * });
 * // => logs '0', '1', and 'length' (property order is not guaranteed across environments)
 */
var forOwn = function(collection, callback, thisArg) {
  var index, iterable = collection, result = iterable;
  if (!iterable) return result;
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.functions"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>functions ()](#apidoc.element.node-scrapy.lodash_custom.prototype.functions)
- description and source-code
```javascript
functions = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * @memberOf _
 * @alias methods
 * @category Objects
 * @param {Object} object The object to inspect.
 * @returns {Array} Returns an array of property names that have function values.
 * @example
 *
 * _.functions(_);
 * // => ['all', 'any', 'bind', 'bindAll', 'clone', 'compact', 'compose', ...]
 */
function functions(object) {
  var result = [];
  forIn(object, function(value, key) {
    if (isFunction(value)) {
      result.push(key);
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.identity"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>identity ()](#apidoc.element.node-scrapy.lodash_custom.prototype.identity)
- description and source-code
```javascript
identity = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * @memberOf _
 * @category Utilities
 * @param {*} value Any value.
 * @returns {*} Returns 'value'.
 * @example
 *
 * var object = { 'name': 'fred' };
 * _.identity(object) === object;
 * // => true
 */
function identity(value) {
  return value;
}

/**
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.isArray"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>isArray ()](#apidoc.element.node-scrapy.lodash_custom.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * // => 6
 *
 * // returns a wrapped value
 * var squares = wrapped.map(function(num) {
 *   return num * num;
 * });
 *
 * _.isArray(squares);
 * // => false
 *
 * _.isArray(squares.value());
 * // => true
 */
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>isFunction ()](#apidoc.element.node-scrapy.lodash_custom.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * @static
 * @memberOf _
 * @category Objects
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if the 'value' is a function, else 'false'.
 * @example
 *
 * _.isFunction(_);
 * // => true
 */
function isFunction(value) {
  return typeof value == 'function';
}

/**
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.isObject"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>isObject ()](#apidoc.element.node-scrapy.lodash_custom.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
* @static
* @memberOf _
* @category Objects
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if the 'value' is an object, else 'false'.
* @example
*
* _.isObject({});
* // => true
*
* _.isObject([1, 2, 3]);
* // => true
*
* _.isObject(1);
* // => false
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.isPlainObject"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>isPlainObject ()](#apidoc.element.node-scrapy.lodash_custom.prototype.isPlainObject)
- description and source-code
```javascript
isPlainObject = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
* @example
*
* function Shape() {
*   this.x = 0;
*   this.y = 0;
* }
*
* _.isPlainObject(new Shape);
* // => false
*
* _.isPlainObject([1, 2, 3]);
* // => false
*
* _.isPlainObject({ 'x': 0, 'y': 0 });
* // => true
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.join"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>join ()](#apidoc.element.node-scrapy.lodash_custom.prototype.join)
- description and source-code
```javascript
join = function () {
  var chainAll = this.__chain__,
      result = func.apply(this.__wrapped__, arguments);

  return chainAll
    ? new lodashWrapper(result, chainAll)
    : result;
}
```
- example usage
```shell
...
 * @category Collections
 * @param {Array|Object|string} collection The collection to iterate over.
 * @param {Function} [callback=identity] The function called per iteration.
 * @param {*} [thisArg] The 'this' binding of 'callback'.
 * @returns {Array|Object|string} Returns 'collection'.
 * @example
 *
 * _([1, 2, 3]).forEach(function(num) { console.log(num); }).join(',');
 * // => logs each number and returns '1,2,3'
 *
 * _.forEach({ 'one': 1, 'two': 2, 'three': 3 }, function(num) { console.log(num); });
 * // => logs each number and returns the object (property order is not guaranteed across environments)
 */
function forEach(collection, callback, thisArg) {
  var index = -1,
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.keys"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>keys ()](#apidoc.element.node-scrapy.lodash_custom.prototype.keys)
- description and source-code
```javascript
keys = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 * @static
 * @memberOf _
 * @category Objects
 * @param {Object} object The object to inspect.
 * @returns {Array} Returns an array of property names.
 * @example
 *
 * _.keys({ 'one': 1, 'two': 2, 'three': 3 });
 * // => ['one', 'two', 'three'] (property order is not guaranteed across environments)
 */
var keys = !nativeKeys ? shimKeys : function(object) {
  if (!isObject(object)) {
    return [];
  }
  return nativeKeys(object);
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.merge"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>merge ()](#apidoc.element.node-scrapy.lodash_custom.prototype.merge)
- description and source-code
```javascript
merge = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 *
 * sam.mainProject === DEFAULTS.mainProject
 * // false
 */

_.mixin({
  'defaultsDeep': _.partialRight(_.merge, function deep(value, other) {
      return _.merge(value, other, deep);
    })
});

/**
 * Custom Error for node-scrapy
 */
function ScrapeError(msg, response, bodyString) {
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.methods"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>methods ()](#apidoc.element.node-scrapy.lodash_custom.prototype.methods)
- description and source-code
```javascript
methods = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.mixin"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>mixin ()](#apidoc.element.node-scrapy.lodash_custom.prototype.mixin)
- description and source-code
```javascript
mixin = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
* _.defaultsDeep(sam, DEFAULTS)
* // {name:"Sam",likes:["html","css"],active:true,mainProject:{name:"supervisor",org:"esshi"},org:"eeshi"}
*
* sam.mainProject === DEFAULTS.mainProject
* // false
*/

_.mixin({
 'defaultsDeep': _.partialRight(_.merge, function deep(value, other) {
     return _.merge(value, other, deep);
   })
});

/**
* Custom Error for node-scrapy
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.noop"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>noop ()](#apidoc.element.node-scrapy.lodash_custom.prototype.noop)
- description and source-code
```javascript
noop = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
 *
 * @static
 * @memberOf _
 * @category Utilities
 * @example
 *
 * var object = { 'name': 'fred' };
 * _.noop(object) === undefined;
 * // => true
 */
function noop() {
  // no operation performed
}

/*--------------------------------------------------------------------------*/
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.partialRight"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>partialRight ()](#apidoc.element.node-scrapy.lodash_custom.prototype.partialRight)
- description and source-code
```javascript
partialRight = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
...
* // {name:"Sam",likes:["html","css"],active:true,mainProject:{name:"supervisor",org:"esshi"},org:"eeshi"}
*
* sam.mainProject === DEFAULTS.mainProject
* // false
*/

_.mixin({
 'defaultsDeep': _.partialRight(_.merge, function deep(value, other) {
     return _.merge(value, other, deep);
   })
});

/**
* Custom Error for node-scrapy
*/
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.pop"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>pop ()](#apidoc.element.node-scrapy.lodash_custom.prototype.pop)
- description and source-code
```javascript
pop = function () {
  var chainAll = this.__chain__,
      result = func.apply(this.__wrapped__, arguments);

  return chainAll
    ? new lodashWrapper(result, chainAll)
    : result;
}
```
- example usage
```shell
...
/**
 * Gets an array from the array pool or creates a new one if the pool is empty.
 *
 * @private
 * @returns {Array} The array from the pool.
 */
function getArray() {
  return arrayPool.pop() || [];
}

/**
 * Releases the given array back to the array pool.
 *
 * @private
 * @param {Array} [array] The array to release.
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.push"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>push ()](#apidoc.element.node-scrapy.lodash_custom.prototype.push)
- description and source-code
```javascript
push = function () {
  func.apply(this.__wrapped__, arguments);
  return this;
}
```
- example usage
```shell
...
 *
 * @private
 * @param {Array} [array] The array to release.
 */
function releaseArray(array) {
  array.length = 0;
  if (arrayPool.length < maxPoolSize) {
    arrayPool.push(array);
  }
}

/**
 * Slices the 'collection' from the 'start' index up to, but not including,
 * the 'end' index.
 *
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.reverse"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>reverse ()](#apidoc.element.node-scrapy.lodash_custom.prototype.reverse)
- description and source-code
```javascript
reverse = function () {
  func.apply(this.__wrapped__, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.shift"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>shift ()](#apidoc.element.node-scrapy.lodash_custom.prototype.shift)
- description and source-code
```javascript
shift = function () {
  var chainAll = this.__chain__,
      result = func.apply(this.__wrapped__, arguments);

  return chainAll
    ? new lodashWrapper(result, chainAll)
    : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.slice"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>slice ()](#apidoc.element.node-scrapy.lodash_custom.prototype.slice)
- description and source-code
```javascript
slice = function () {
  return new lodashWrapper(func.apply(this.__wrapped__, arguments), this.__chain__);
}
```
- example usage
```shell
...
* @param {Function|Object} [object=lodash] object The destination object.
* @param {Object} source The object of functions to add.
* @param {Object} [options] The options object.
* @param {boolean} [options.chain=true] Specify whether the functions added are chainable.
* @example
*
* function capitalize(string) {
*   return string.charAt(0).toUpperCase() + string.slice(1).toLowerCase();
* }
*
* _.mixin({ 'capitalize': capitalize });
* _.capitalize('fred');
* // => 'Fred'
*
* _('fred').capitalize().value();
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.sort"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>sort ()](#apidoc.element.node-scrapy.lodash_custom.prototype.sort)
- description and source-code
```javascript
sort = function () {
  func.apply(this.__wrapped__, arguments);
  return this;
}
```
- example usage
```shell
...
function functions(object) {
  var result = [];
  forIn(object, function(value, key) {
    if (isFunction(value)) {
      result.push(key);
    }
  });
  return result.sort();
}

/**
 * Checks if 'value' is a function.
 *
 * @static
 * @memberOf _
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.splice"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>splice ()](#apidoc.element.node-scrapy.lodash_custom.prototype.splice)
- description and source-code
```javascript
splice = function () {
  return new lodashWrapper(func.apply(this.__wrapped__, arguments), this.__chain__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.support"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>support (n, guard)](#apidoc.element.node-scrapy.lodash_custom.prototype.support)
- description and source-code
```javascript
support = function (n, guard) {
  var chainAll = this.__chain__,
      result = func(this.__wrapped__, n, guard);

  return !chainAll && (n == null || (guard && !(callbackable && typeof n == 'function')))
    ? result
    : new lodashWrapper(result, chainAll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.toString"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>toString ()](#apidoc.element.node-scrapy.lodash_custom.prototype.toString)
- description and source-code
```javascript
function wrapperToString() {
  return String(this.__wrapped__);
}
```
- example usage
```shell
...

Default: 'true'

##### transform

A 'function' applied after all other operations and transformations.

Default: 'function() { return this.toString(); }'

##### prefix

A 'string' to be prefixed to the result(s). Useful to transform relative URLs into absolute ones.

Default: '''' (empty string)
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.unshift"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>unshift ()](#apidoc.element.node-scrapy.lodash_custom.prototype.unshift)
- description and source-code
```javascript
unshift = function () {
  func.apply(this.__wrapped__, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.value"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>value ()](#apidoc.element.node-scrapy.lodash_custom.prototype.value)
- description and source-code
```javascript
function wrapperValueOf() {
  return this.__wrapped__;
}
```
- example usage
```shell
...
 * var squares = wrapped.map(function(num) {
 *   return num * num;
 * });
 *
 * _.isArray(squares);
 * // => false
 *
 * _.isArray(squares.value());
 * // => true
 */
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
  return (value && typeof value == 'object' && !isArray(value) && hasOwnProperty.call(value, '__wrapped__'))
   ? value
   : new lodashWrapper(value);
...
```

#### <a name="apidoc.element.node-scrapy.lodash_custom.prototype.valueOf"></a>[function <span class="apidocSignatureSpan">node-scrapy.lodash_custom.prototype.</span>valueOf ()](#apidoc.element.node-scrapy.lodash_custom.prototype.valueOf)
- description and source-code
```javascript
function wrapperValueOf() {
  return this.__wrapped__;
}
```
- example usage
```shell
...
 * @name valueOf
 * @memberOf _
 * @alias value
 * @category Chaining
 * @returns {*} Returns the wrapped value.
 * @example
 *
 * _([1, 2, 3]).valueOf();
 * // => [1, 2, 3]
 */
function wrapperValueOf() {
  return this.__wrapped__;
}

/*--------------------------------------------------------------------------*/
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
