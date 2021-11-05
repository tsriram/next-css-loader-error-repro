To see the error, run `npm install` first and then run `npm run export`.

Here's the error text:

```
Import trace for requested module:
./styles/cursor.css
./pages/_app.js

./styles/cursor.css
URIError: URI malformed
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/styles/cursor.css:2:3
    at decodeURIComponent (<anonymous>)
    at Object.normalizeUrl (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/utils.js:43:12)
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/plugins/postcss-url-parser.js:101:31
    at walk (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/postcss-value-parser/index.js:1:5010)
    at ValueParser.walk (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/postcss-value-parser/index.js:1:326)
    at parseDeclaration (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/plugins/postcss-url-parser.js:85:12)
    at Declaration (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/plugins/postcss-url-parser.js:206:39)
    at LazyResult.visitTick (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/postcss/lib/lazy-result.js:456:16)
    at LazyResult.runAsync (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/postcss/lib/lazy-result.js:372:30)
    at LazyResult.async (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/postcss/lib/lazy-result.js:205:30)
    at tryRunOrWebpackError (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:45579:9)
    at __webpack_require_module__ (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:31387:12)
    at __nested_webpack_require_150254__ (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:31344:18)
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:31415:20
    at symbolIterator (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/neo-async/async.js:1:14452)
    at done (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/neo-async/async.js:1:14832)
    at Hook.eval [as callAsync] (eval at create (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:141008:10), <anonymous>:15:1)
    at Hook.CALL_ASYNC_DELEGATE [as _callAsync] (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:140810:14)
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:31322:43
    at symbolIterator (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/neo-async/async.js:1:14410)
-- inner error --
URIError: URI malformed
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/styles/cursor.css:2:3
    at decodeURIComponent (<anonymous>)
    at Object.normalizeUrl (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/utils.js:43:12)
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/plugins/postcss-url-parser.js:101:31
    at walk (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/postcss-value-parser/index.js:1:5010)
    at ValueParser.walk (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/postcss-value-parser/index.js:1:326)
    at parseDeclaration (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/plugins/postcss-url-parser.js:85:12)
    at Declaration (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/plugins/postcss-url-parser.js:206:39)
    at LazyResult.visitTick (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/postcss/lib/lazy-result.js:456:16)
    at LazyResult.runAsync (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/postcss/lib/lazy-result.js:372:30)
    at LazyResult.async (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/postcss/lib/lazy-result.js:205:30)
    at Object.<anonymous> (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/index.js??ruleSet[1].rules[2].oneOf[9].use[1]!/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/postcss-loader/src/index.js??ruleSet[1].rules[2].oneOf[9].use[2]!/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/styles/cursor.css:1:7)
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:89923:11
    at Hook.eval [as call] (eval at create (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:140994:10), <anonymous>:7:1)
    at Hook.CALL_DELEGATE [as _call] (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:140806:14)
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:31389:39
    at tryRunOrWebpackError (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:45574:7)
    at __webpack_require_module__ (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:31387:12)
    at __nested_webpack_require_150254__ (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:31344:18)
    at /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/webpack/bundle5.js:31415:20
    at symbolIterator (/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/compiled/neo-async/async.js:1:14452)

Generated code for /Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/css-loader/src/index.js??ruleSet[1].rules[2].oneOf[9].use[1]!/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/node_modules/next/dist/build/webpack/loaders/postcss-loader/src/index.js??ruleSet[1].rules[2].oneOf[9].use[2]!/Users/cb-sriram.thiagarajan/code/playground/next-css-loader-error-repro/styles/cursor.css

Import trace for requested module:
./pages/_app.js
```
