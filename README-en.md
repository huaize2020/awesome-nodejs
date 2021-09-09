English | [简体中文](./README.md)

> You can also see [awesome-frontend](https://github.com/huaize2020/awesome-frontend)!

## Table of contents

- [Table of contents](#table-of-contents)
- [Official](#official)
- [Resources](#resources)
  - [Tools](#tools)
  - [Tutorials](#tutorials)
- [Repository](#repository)
  - [Text](#text)
  - [Number](#number)
  - [Math](#math)
  - [Date & Time](#date--time)
  - [RegExp/Glob](#regexpglob)
  - [URL](#url)
  - [JSON / JSON Schema](#json--json-schema)
  - [Image](#image)
  - [Audio / Video](#audio--video)
  - [Font](#font)
  - [Color](#color)
  - [Crypto](#crypto)
  - [Streams](#streams)
  - [Check/Detect](#checkdetect)
  - [Data Validation](#data-validation)
  - [Functional programming](#functional-programming)
  - [Control flow](#control-flow)
  - [Inversion of control / Dependency Injection (Ioc/DI)](#inversion-of-control--dependency-injection-iocdi)
  - [Shell](#shell)
  - [Environment](#environment)
  - [Event](#event)
  - [Command-line Utilities](#command-line-utilities)
  - [Node.js Management](#nodejs-management)
  - [NPM](#npm)
  - [Monorepo](#monorepo)
  - [Filesystem](#filesystem)
  - [Parsing](#parsing)
  - [Git](#git)
  - [Logging](#logging)
  - [Process management](#process-management)
  - [Linter & Formatter](#linter--formatter)
  - [Configuration Tools](#configuration-tools)
  - [Build Tools](#build-tools)
  - [Templating](#templating)
  - [Web Frameworks](#web-frameworks)
  - [GraphQL](#graphql)
  - [Content management systems (CMS)](#content-management-systems-cms)
  - [Static Site Generator & Blogging](#static-site-generator--blogging)
  - [Documentation](#documentation)
  - [API Management](#api-management)
  - [Desktop Apps](#desktop-apps)
  - [Real-time](#real-time)
  - [Job Queues](#job-queues)
  - [Job Scheduling](#job-scheduling)
  - [Debugging](#debugging)
  - [Profiling/Analysis](#profilinganalysis)
  - [Performance Optimization](#performance-optimization)
  - [Application Performance Monitoring (APM)](#application-performance-monitoring-apm)
  - [Forum](#forum)
  - [Database](#database)
  - [Cache](#cache)
  - [Search Engine](#search-engine)
  - [Serverless](#serverless)
  - [Automation & RPA](#automation--rpa)
  - [Testing](#testing)
  - [Office](#office)
  - [OS Identification](#os-identification)
  - [Compression / Decompression](#compression--decompression)
  - [Minifiers](#minifiers)
  - [Email](#email)
  - [Network](#network)
  - [HTTP](#http)
  - [Authentication](#authentication)
  - [Authorization](#authorization)
  - [Distribute](#distribute)
  - [Serialization](#serialization)
  - [RPC](#rpc)
  - [Server-side DOM](#server-side-dom)
  - [Crawler](#crawler)
  - [AST](#ast)
  - [WebAssembly](#webassembly)
  - [Design To Code（D2C）](#design-to-coded2c)
  - [Sandbox](#sandbox)
  - [Hardware](#hardware)
  - [IoT](#iot)
  - [Machine learning & Neural networks](#machine-learning--neural-networks)
  - [Natural language processing](#natural-language-processing)
  - [OCR](#ocr)
  - [Bitcoin](#bitcoin)
- [Project](#project)
  - [Lowcode](#lowcode)

## Official
- [Website](https://nodejs.org)
- [Documentation](https://nodejs.org/dist/latest/docs/api/)
- [Repository](https://github.com/nodejs/node)

## Resources

### Tools

- [openbase](https://openbase.com/) - Choose the right package every time. JavaScript supported, more languages coming soon.
- [npm.devtool](https://npm.devtool.tech/) - Find the best package for you, Analyze tech stack for your project.

### Tutorials

- [Node.js Best Practices](https://github.com/goldbergyoni/nodebestpractices) - The Node.js best practices list.

## Repository

### Text

- Common
  - [dedent](https://github.com/dmnd/dedent) - ES6 string tag that strips indentation from multi-line strings. ![](https://img.shields.io/github/stars/dmnd/dedent.svg?style=social&label=Star)
  - [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar. ![](https://img.shields.io/github/stars/sindresorhus/camelcase.svg?style=social&label=Star)
  - [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. ![](https://img.shields.io/github/stars/sindresorhus/string-width.svg?style=social&label=Star)
  - [decamelize](https://github.com/sindresorhus/decamelize) - Convert a camelized string into a lowercased one with a custom separator: unicornRainbow → unicorn_rainbow ![](https://img.shields.io/github/stars/sindresorhus/decamelize.svg?style=social&label=Star)
  - [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code. ![](https://img.shields.io/github/stars/sindresorhus/detect-indent.svg?style=social&label=Star)
  - [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes. ![](https://img.shields.io/github/stars/sindresorhus/string-length.svg?style=social&label=Star)
  - [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string. ![](https://img.shields.io/github/stars/sindresorhus/strip-indent.svg?style=social&label=Star)
  - [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string. ![](https://img.shields.io/github/stars/sindresorhus/strip-bom.svg?style=social&label=Star)
  - [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string. ![](https://img.shields.io/github/stars/sindresorhus/indent-string.svg?style=social&label=Star)
  - [redent](https://github.com/sindresorhus/redent) - Strip redundant indentation and indent the string. ![](https://img.shields.io/github/stars/sindresorhus/redent.svg?style=social&label=Star)
  - [normalize-newline](https://github.com/sindresorhus/normalize-newline) - Normalize the newline characters in a string to `\n`. ![](https://img.shields.io/github/stars/sindresorhus/normalize-newline.svg?style=social&label=Star)
  - [min-indent](https://github.com/jamiebuilds/min-indent) - Get the shortest leading whitespace from lines in a string. ![](https://img.shields.io/github/stars/jamiebuilds/min-indent.svg?style=social&label=Star)
  - [trim-right](https://github.com/sindresorhus/trim-right) - Similar to String#trim() but removes only whitespace on the right. ![](https://img.shields.io/github/stars/sindresorhus/trim-right.svg?style=social&label=Star)
  - [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`. ![](https://img.shields.io/github/stars/sindresorhus/splice-string.svg?style=social&label=Star)

- i18n
  - [i18next](https://github.com/i18next/i18next) - Internationalization framework. ![](https://img.shields.io/github/stars/i18next/i18next.svg?style=social&label=Star)
  - [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage. ![](https://img.shields.io/github/stars/mashpie/i18n-node.svg?style=social&label=Star)
  - [babelfish](https://github.com/nodeca/babelfish) - human friendly i18n for javascript (node.js + browser). ![](https://img.shields.io/github/stars/nodeca/babelfish.svg?style=social&label=Star)

- Unique Id
  - [nanoid](https://github.com/ai/nanoid) - Tiny, secure, URL-friendly, unique string ID generator. ![](https://img.shields.io/github/stars/ai/nanoid.svg?style=social&label=Star)
  - [uuid](https://github.com/uuidjs/uuid) - Generate RFC-compliant UUIDs in JavaScript. ![](https://img.shields.io/github/stars/uuidjs/uuid.svg?style=social&label=Star)
  - [shortid](https://github.com/dylang/shortid) - Short id generator. Url-friendly. Non-predictable. Cluster-compatible. ![](https://img.shields.io/github/stars/dylang/shortid.svg?style=social&label=Star)
  - [cuid](https://github.com/ericelliott/cuid) - Collision-resistant ids optimized for horizontal scaling and performance. ![](https://img.shields.io/github/stars/ericelliott/cuid.svg?style=social&label=Star)
  - [ulid](https://github.com/ulid/javascript) - Universally Unique Lexicographically Sortable Identifier. ![](https://img.shields.io/github/stars/ulid/javascript.svg?style=social&label=Star)
  - [uuid-js](https://github.com/pnegri/uuid-js) - A js library to generate and parse UUIDs,TimeUUIDs and generate TimeUUID based on Date for range selections. ![](https://img.shields.io/github/stars/pnegri/uuid-js.svg?style=social&label=Star)
  - [pure-uuid](https://github.com/rse/pure-uuid) - Pure JavaScript Based Universally Unique Identifiers (UUID). ![](https://img.shields.io/github/stars/rse/pure-uuid.svg?style=social&label=Star)

- Encode/Decode
  - [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder. ![](https://img.shields.io/github/stars/mathiasbynens/he.svg?style=social&label=Star)
  - [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings. ![](https://img.shields.io/github/stars/ashtuchkin/iconv-lite.svg?style=social&label=Star)
  - [jschardet](https://github.com/aadsm/jschardet) - Character encoding auto-detection in JavaScript (port of python's chardet) ![](https://img.shields.io/github/stars/aadsm/jschardet.svg?style=social&label=Star)

- Comparison
  - [jsdiff](https://github.com/kpdecker/jsdiff) - A javascript text differencing implementation. ![](https://img.shields.io/github/stars/kpdecker/jsdiff.svg?style=social&label=Star)
  - [recursive-diff](https://github.com/cosmicanant/recursive-diff) - A JavaScript library to find diff between two JavaScript Objects. Support for Array, Number, Date and other primitive data types. ![](https://img.shields.io/github/stars/cosmicanant/recursive-diff.svg?style=social&label=Star)

- Random
  - [generate-password](https://github.com/brendanashworth/generate-password) - NodeJS library for generating cryptographically-secure passwords. ![](https://img.shields.io/github/stars/brendanashworth/generate-password.svg?style=social&label=Star)
  - [randomatic](https://github.com/jonschlinkert/randomatic) - Easily generate random strings like passwords, with simple options for specifying a length and for using patterns of numeric, alpha-numeric, alphabetical, special or custom characters. (the original "generate-password") ![](https://img.shields.io/github/stars/jonschlinkert/randomatic.svg?style=social&label=Star)

- Other
  - [StegCloak](https://github.com/kurolabs/stegcloak) - Conceal secrets within strings, in plain sight. ![](https://img.shields.io/github/stars/kurolabs/stegcloak.svg?style=social&label=Star)
  - [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters. ![](https://img.shields.io/github/stars/nodeca/unhomoglyph.svg?style=social&label=Star)

### Number

- [Numeral.js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers. ![](https://img.shields.io/github/stars/adamwdraper/Numeral-js.svg?style=social&label=Star)
- [bignumber.js](https://github.com/MikeMcl/bignumber.js) - A JavaScript library for arbitrary-precision decimal and non-decimal arithmetic. ![](https://img.shields.io/github/stars/MikeMcl/bignumber.js.svg?style=social&label=Star)
- [decimal.js](https://github.com/MikeMcl/decimal.js) - An arbitrary-precision Decimal type for JavaScript. ![](https://img.shields.io/github/stars/MikeMcl/decimal.js.svg?style=social&label=Star)
- [big.js](https://github.com/MikeMcl/big.js) - A small, fast JavaScript library for arbitrary-precision decimal arithmetic. ![](https://img.shields.io/github/stars/MikeMcl/big.js.svg?style=social&label=Star)
- [random-js](https://github.com/ckknight/random-js) - A mathematically correct random number generator library for JavaScript. ![](https://img.shields.io/github/stars/ckknight/random-js.svg?style=social&label=Star)
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`. ![](https://img.shields.io/github/stars/sindresorhus/round-to.svg?style=social&label=Star)
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique. ![](https://img.shields.io/github/stars/sindresorhus/unique-random.svg?style=social&label=Star)
- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer. ![](https://img.shields.io/github/stars/sindresorhus/random-int.svg?style=social&label=Star)
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float. ![](https://img.shields.io/github/stars/sindresorhus/random-float.svg?style=social&label=Star)

### Math

- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library. ![](https://img.shields.io/github/stars/josdejong/mathjs.svg?style=social&label=Star)
- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays. ![](https://img.shields.io/github/stars/scijs/ndarray.svg?style=social&label=Star)
- [algebra](https://github.com/fibo/algebra) - Algebraic structures. ![](https://img.shields.io/github/stars/fibo/algebra.svg?style=social&label=Star)
- [multimath](https://github.com/nodeca/multimath) - Core to create fast image math in WebAssembly and JS. ![](https://img.shields.io/github/stars/nodeca/multimath.svg?style=social&label=Star)

### Date & Time

- [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript. ![](https://img.shields.io/github/stars/moment/moment.svg?style=social&label=Star)
- [dayjs](https://github.com/iamkun/dayjs) - Day.js 2KB immutable date-time library alternative to Moment.js with the same modern API. ![](https://img.shields.io/github/stars/iamkun/dayjs.svg?style=social&label=Star)
- [date-fns](https://github.com/date-fns/date-fns) - Modern JavaScript date utility library. ![](https://img.shields.io/github/stars/date-fns/date-fns.svg?style=social&label=Star)
- [luxon](https://github.com/moment/luxon) - Library for working with dates and times. ![](https://img.shields.io/github/stars/moment/luxon.svg?style=social&label=Star)
- [timeago.js](https://github.com/hustcc/timeago.js) - 🕗 ⌛ timeago.js is a tiny(2.0 kb) library used to format date with `*** time ago` statement. ![](https://img.shields.io/github/stars/hustcc/timeago.js.svg?style=social&label=Star)
- [ms](https://github.com/vercel/ms) - Tiny millisecond conversion utility. ![](https://img.shields.io/github/stars/vercel/ms.svg?style=social&label=Star)
- [dateformat](https://github.com/felixge/node-dateformat) - A node.js package for Steven Levithan's excellent dateFormat() function. ![](https://img.shields.io/github/stars/felixge/node-dateformat.svg?style=social&label=Star)
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s` ![](https://img.shields.io/github/stars/sindresorhus/pretty-ms.svg?style=social&label=Star)
- [strftime](https://github.com/samsonjs/strftime) - Strftime for JavaScript. ![](https://img.shields.io/github/stars/samsonjs/strftime.svg?style=social&label=Star)
- [node-microtime](https://github.com/wadey/node-microtime) - Get the current time in microseconds. ![](https://img.shields.io/github/stars/wadey/node-microtime.svg?style=social&label=Star)
- [date-utils](https://github.com/JerrySievert/date-utils) - Date Pollyfills for Node.js and Browser. ![](https://img.shields.io/github/stars/JerrySievert/date-utils.svg?style=social&label=Star)
- [pretty-hrtime](https://github.com/robrich/pretty-hrtime) - process.hrtime() to words. ![](https://img.shields.io/github/stars/robrich/pretty-hrtime.svg?style=social&label=Star)
- [humanize-ms](https://github.com/node-modules/humanize-ms) - Transform humanize time to ms. ![](https://img.shields.io/github/stars/node-modules/humanize-ms.svg?style=social&label=Star)

### RegExp/Glob

- [path-to-regexp](https://github.com/pillarjs/path-to-regexp) - Turn a path string such as `/user/:name` into a regular expression. ![](https://img.shields.io/github/stars/pillarjs/path-to-regexp.svg?style=social&label=Star)
- [minimatch](https://github.com/isaacs/minimatch) - A minimal matching utility. ![](https://img.shields.io/github/stars/isaacs/minimatch.svg?style=social&label=Star)
- [micromatch](https://github.com/micromatch/micromatch) - Highly optimized wildcard and glob matching library. Faster, drop-in replacement to minimatch and multimatch. Used by webpack, babel core, yarn, jest, browser-sync, documentation.js, stylelint, nyc, ava, and many others! ![](https://img.shields.io/github/stars/micromatch/micromatch.svg?style=social&label=Star)
- [randexp.js](https://github.com/fent/randexp.js) - Create random strings that match a given regular expression. ![](https://img.shields.io/github/stars/fent/randexp.js.svg?style=social&label=Star)
- [safe-regex](https://github.com/substack/safe-regex) - Detect possibly catastrophic, exponential-time regular expressions. ![](https://img.shields.io/github/stars/substack/safe-regex.svg?style=social&label=Star)
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching. ![](https://img.shields.io/github/stars/sindresorhus/matcher.svg?style=social&label=Star)
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters. ![](https://img.shields.io/github/stars/sindresorhus/escape-string-regexp.svg?style=social&label=Star)
- [multimatch](https://github.com/sindresorhus/multimatch) - Extends minimatch.match() with support for multiple patterns. ![](https://img.shields.io/github/stars/sindresorhus/multimatch.svg?style=social&label=Star)
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string. ![](https://img.shields.io/github/stars/sindresorhus/execall.svg?style=social&label=Star)

### URL

- [URI.js](https://github.com/medialize/URI.js) - Javascript URL mutation library. ![](https://img.shields.io/github/stars/medialize/URI.js.svg?style=social&label=Star)
- [qs](https://github.com/ljharb/qs) - Querystring parser with nesting support. ![](https://img.shields.io/github/stars/ljharb/qs.svg?style=social&label=Star)
- [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings. ![](https://img.shields.io/github/stars/sindresorhus/query-string.svg?style=social&label=Star)
- [url-parse](https://github.com/unshiftio/url-parse) - Small footprint URL parser that works seamlessly across Node.js and browser environments. ![](https://img.shields.io/github/stars/unshiftio/url-parse.svg?style=social&label=Star)
- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL. ![](https://img.shields.io/github/stars/sindresorhus/normalize-url.svg?style=social&label=Star)
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. turn strings into data or data into strings. ![](https://img.shields.io/github/stars/snd/url-pattern.svg?style=social&label=Star)
- [native-url](https://github.com/GoogleChromeLabs/native-url) - Node's url module implemented using the built-in URL API. ![](https://img.shields.io/github/stars/GoogleChromeLabs/native-url.svg?style=social&label=Star)
- [url-join](https://github.com/jfromaniello/url-join) - Join all arguments together and normalize the resulting url. ![](https://img.shields.io/github/stars/jfromaniello/url-join.svg?style=social&label=Star)
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: https://sindresorhus.com → sindresorhus.com. ![](https://img.shields.io/github/stars/sindresorhus/humanize-url.svg?style=social&label=Star)
- [parseurl](https://github.com/pillarjs/parseurl) - Parse a url with memoization. ![](https://img.shields.io/github/stars/pillarjs/parseurl.svg?style=social&label=Star)
- [file-url](https://github.com/sindresorhus/file-url) - Convert a file path to a file URL: `unicorn.jpg` → `file:///Users/sindresorhus/unicorn.jpg` ![](https://img.shields.io/github/stars/sindresorhus/file-url.svg?style=social&label=Star)
- [encodeurl](https://github.com/pillarjs/encodeurl) - Encode a URL to a percent-encoded form, excluding already-encoded sequences. ![](https://img.shields.io/github/stars/pillarjs/encodeurl.svg?style=social&label=Star)

### JSON / JSON Schema

- [json5](https://github.com/json5/json5) - JSON5 — JSON for humans. ![](https://img.shields.io/github/stars/json5/json5.svg?style=social&label=Star)
- [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - Diff & patch JavaScript objects. ![](https://img.shields.io/github/stars/benjamine/jsondiffpatch.svg?style=social&label=Star)
- [fast-json-stringify](https://github.com/fastify/fast-json-stringify) - 2x faster than JSON.stringify() ![](https://img.shields.io/github/stars/fastify/fast-json-stringify.svg?style=social&label=Star)
- [jsonfile](https://github.com/jprichardson/node-jsonfile) - Easily read/write JSON files. ![](https://img.shields.io/github/stars/jprichardson/node-jsonfile.svg?style=social&label=Star)
- [jsonata](https://github.com/jsonata-js/jsonata) - JSONata query and transformation language - http://jsonata.org ![](https://img.shields.io/github/stars/jsonata-js/jsonata.svg?style=social&label=Star)
- [json-stable-stringify](https://github.com/substack/json-stable-stringify) - Deterministic JSON.stringify() with custom sorting to get deterministic hashes from stringified results. ![](https://img.shields.io/github/stars/substack/json-stable-stringify.svg?style=social&label=Star)
- [json-mask](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting specific parts of a JS object, hiding the rest. ![](https://img.shields.io/github/stars/nemtsov/json-mask.svg?style=social&label=Star)
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON. Lets you use comments in your JSON files. ![](https://img.shields.io/github/stars/sindresorhus/strip-json-comments.svg?style=social&label=Star)
- [json-stringify-safe](https://github.com/moll/json-stringify-safe) - Like JSON.stringify, but doesn't throw on circular references. ![](https://img.shields.io/github/stars/moll/json-stringify-safe.svg?style=social&label=Star)
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors. ![](https://img.shields.io/github/stars/sindresorhus/parse-json.svg?style=social&label=Star)
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file. ![](https://img.shields.io/github/stars/sindresorhus/load-json-file.svg?style=social&label=Star)
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically. ![](https://img.shields.io/github/stars/sindresorhus/write-json-file.svg?style=social&label=Star)
- [fast-json-stable-stringify](https://github.com/epoberezkin/fast-json-stable-stringify) - Deterministic JSON.stringify() - a faster version of @substack's json-stable-strigify without jsonify. ![](https://img.shields.io/github/stars/epoberezkin/fast-json-stable-stringify.svg?style=social&label=Star)
- [jsonuri](https://github.com/aligay/jsonuri) - Use URI style methods to operate data. ![](https://img.shields.io/github/stars/aligay/jsonuri.svg?style=social&label=Star)

### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images. ![](https://img.shields.io/github/stars/lovell/sharp.svg?style=social&label=Star)
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript. ![](https://img.shields.io/github/stars/oliver-moran/jimp.svg?style=social&label=Star)
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper. ![](https://img.shields.io/github/stars/aheckmann/gm.svg?style=social&label=Star)
- [qrcode](https://github.com/soldair/node-qrcode) - QR code and bar code generator. ![](https://img.shields.io/github/stars/soldair/node-qrcode.svg?style=social&label=Star)
- [pixelmatch](https://github.com/mapbox/pixelmatch) - The smallest, simplest and fastest JavaScript pixel-level image comparison library. ![](https://img.shields.io/github/stars/mapbox/pixelmatch.svg?style=social&label=Star)
- [Resemble.js](https://github.com/rsmbl/Resemble.js) - Image analysis and comparison. ![](https://img.shields.io/github/stars/rsmbl/Resemble.js.svg?style=social&label=Star)
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed. ![](https://img.shields.io/github/stars/nodeca/pica.svg?style=social&label=Star)
- [jsQR](https://github.com/cozmo/jsQR) - A pure javascript QR code reading library. This library takes in raw images and will locate, extract and parse any QR code found within. ![](https://img.shields.io/github/stars/cozmo/jsQR.svg?style=social&label=Star)
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick. ![](https://img.shields.io/github/stars/EyalAr/lwip.svg?style=social&label=Star)
- [gifski](https://github.com/ImageOptim/gifski) - GIF encoder based on libimagequant (pngquant). Squeezes maximum possible quality from the awful GIF format. ![](https://img.shields.io/github/stars/ImageOptim/gifski.svg?style=social&label=Star)
- [svg-captcha](https://github.com/produck/svg-captcha) - Generate svg captcha in node. ![](https://img.shields.io/github/stars/produck/svg-captcha.svg?style=social&label=Star)
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download. ![](https://img.shields.io/github/stars/nodeca/probe-image-size.svg?style=social&label=Star)
- [omggif](https://github.com/deanm/omggif) - JavaScript implementation of a GIF 89a encoder and decoder. ![](https://img.shields.io/github/stars/deanm/omggif.svg?style=social&label=Star)
- [jpeg-js](https://github.com/jpeg-js/jpeg-js) - A pure javascript JPEG encoder and decoder for node.js. ![](https://img.shields.io/github/stars/jpeg-js/jpeg-js.svg?style=social&label=Star)
- [pngjs](https://github.com/lukeapage/pngjs) - Simple PNG encoder/decoder. ![](https://img.shields.io/github/stars/lukeapage/pngjs.svg?style=social&label=Star)
- [get-pixels](https://github.com/scijs/get-pixels) - Reads an image into an ndarray. ![](https://img.shields.io/github/stars/scijs/get-pixels.svg?style=social&label=Star)
- [gifencoder](https://github.com/eugeneware/gifencoder) - Server side animated gif generation for node.js. ![](https://img.shields.io/github/stars/eugeneware/gifencoder.svg?style=social&label=Star)
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array. ![](https://img.shields.io/github/stars/sindresorhus/image-type.svg?style=social&label=Star)
- [node-pngquant](https://github.com/papandreou/node-pngquant) - The pngquant utility as a readable/writable stream. ![](https://img.shields.io/github/stars/papandreou/node-pngquant.svg?style=social&label=Star)
- [node-bitmap](https://github.com/nowelium/node-bitmap) - Pure javascript Bitmap library. ![](https://img.shields.io/github/stars/nowelium/node-bitmap.svg?style=social&label=Star)

### Audio / Video

- [fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) - A fluent API to FFMPEG (http://www.ffmpeg.org) ![](https://img.shields.io/github/stars/fluent-ffmpeg/node-fluent-ffmpeg.svg?style=social&label=Star)
- [FFCreator](https://github.com/tnfe/FFCreator) - A fast short video processing library based on node.js. ![](https://img.shields.io/github/stars/tnfe/FFCreator.svg?style=social&label=Star)
- [node-ffmpeg](https://github.com/damianociarla/node-ffmpeg) - Ffmpeg module for nodejs. ![](https://img.shields.io/github/stars/damianociarla/node-ffmpeg.svg?style=social&label=Star)

### Font

- [font-spider](https://github.com/aui/font-spider) - Smart webfont compression and format conversion tool. ![](https://img.shields.io/github/stars/aui/font-spider.svg?style=social&label=Star)
- [svg2ttf](https://github.com/fontello/svg2ttf) - SVG -> TTF font convertor. ![](https://img.shields.io/github/stars/fontello/svg2ttf.svg?style=social&label=Star)
- [ttf2woff](https://github.com/fontello/ttf2woff) - Font convertor, TTF to WOFF, for node.js. ![](https://img.shields.io/github/stars/fontello/ttf2woff.svg?style=social&label=Star)
- [svgicons2svgfont](https://github.com/nfroidure/svgicons2svgfont) - Concatenate SVG icons and ouput an SVG font. ![](https://img.shields.io/github/stars/nfroidure/svgicons2svgfont.svg?style=social&label=Star)
- [webfont](https://github.com/itgalaxy/webfont) - Awesome generator of webfont. ![](https://img.shields.io/github/stars/itgalaxy/webfont.svg?style=social&label=Star)
- [ttf2eot](https://github.com/fontello/ttf2eot) - Font convertor, TTF to EOT, for node.js. ![](https://img.shields.io/github/stars/fontello/ttf2eot.svg?style=social&label=Star)
- [wawoff2](https://github.com/fontello/wawoff2) - WebAssembly build of Google's woff2. ![](https://img.shields.io/github/stars/fontello/wawoff2.svg?style=social&label=Star)

### Color

- [chroma](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations. ![](https://img.shields.io/github/stars/gka/chroma.js.svg?style=social&label=Star)
- [randomColor](https://github.com/davidmerfield/randomColor) - A tiny script for generating attractive colors. ![](https://img.shields.io/github/stars/davidmerfield/randomColor.svg?style=social&label=Star)
- [rgbaster](https://github.com/briangonzalez/rgbaster.js) - 🎨 A simple library for extracting dominant colors from images. ![](https://img.shields.io/github/stars/briangonzalez/rgbaster.js.svg?style=social&label=Star)
- [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript. ![](https://img.shields.io/github/stars/bgrins/TinyColor.svg?style=social&label=Star)
- [onecolor](https://github.com/One-com/one-color) - An OO-based JavaScript color parser/computation toolkit with support for RGB, HSV, HSL, CMYK, and alpha channels. Conversion between color spaces occurs implicitly, and all methods return new objects rather than mutating existing instances. Works in the browser and node.js. ![](https://img.shields.io/github/stars/One-com/one-color.svg?style=social&label=Star)

### Crypto

- [crypto-js](https://github.com/brix/crypto-js) - JavaScript library of crypto standards. ![](https://img.shields.io/github/stars/brix/crypto-js.svg?style=social&label=Star)
- [sjcl](https://github.com/bitwiseshiftleft/sjcl) - Stanford Javascript Crypto Library. ![](https://img.shields.io/github/stars/bitwiseshiftleft/sjcl.svg?style=social&label=Star)
- [bcrypt](https://github.com/kelektiv/node.bcrypt.js) - Bcrypt for NodeJs. ![](https://img.shields.io/github/stars/kelektiv/node.bcrypt.js.svg?style=social&label=Star)
- [jsencrypt](https://github.com/travist/jsencrypt) - A Javascript library to perform OpenSSL RSA Encryption, Decryption, and Key Generation. ![](https://img.shields.io/github/stars/travist/jsencrypt.svg?style=social&label=Star)
- [bcrypt.js](https://github.com/dcodeIO/bcrypt.js) - Optimized bcrypt in plain JavaScript with zero dependencies. ![](https://img.shields.io/github/stars/dcodeIO/bcrypt.js.svg?style=social&label=Star)
- [jsrsasign](https://github.com/kjur/jsrsasign) - The 'jsrsasign' (RSA-Sign JavaScript Library) is an opensource free cryptography library supporting RSA/RSAPSS/ECDSA/DSA signing/validation, ASN.1, PKCS#1/5/8 private/public key, X.509 certificate, CRL, OCSP, CMS SignedData, TimeStamp, CAdES JSON Web Signature/Token in pure JavaScript. ![](https://img.shields.io/github/stars/kjur/jsrsasign.svg?style=social&label=Star)
- [node-rsa](https://github.com/rzcoder/node-rsa) - Node.js RSA library. ![](https://img.shields.io/github/stars/rzcoder/node-rsa.svg?style=social&label=Star)
- [aes-js](https://github.com/ricmoo/aes-js) - A pure JavaScript implementation of the AES block cipher and all common modes of operation for node.js or web browsers. ![](https://img.shields.io/github/stars/ricmoo/aes-js.svg?style=social&label=Star)
- [node-md5](https://github.com/pvorb/node-md5) - A JavaScript function for hashing messages with MD5. ![](https://img.shields.io/github/stars/pvorb/node-md5.svg?style=social&label=Star)
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - Tiny hashing module that uses the native crypto API in Node.js and the browser. ![](https://img.shields.io/github/stars/sindresorhus/crypto-hash.svg?style=social&label=Star)
- [sm-crypto](https://github.com/JuneAndGreen/sm-crypto) - JavaScript library of sm2, sm3, sm4. ![](https://img.shields.io/github/stars/JuneAndGreen/sm-crypto.svg?style=social&label=Star)
- [sha.js](https://github.com/crypto-browserify/sha.js) - Streamable SHA hashes in pure javascript. ![](https://img.shields.io/github/stars/crypto-browserify/sha.js.svg?style=social&label=Star)
- [hash-sum](https://github.com/bevacqua/hash-sum) - Blazing fast unique hash generator. ![](https://img.shields.io/github/stars/bevacqua/hash-sum.svg?style=social&label=Star)
- [cryptr](https://github.com/MauriceButler/cryptr) - Very basic encrypt and decrypt node module. ![](https://img.shields.io/github/stars/MauriceButler/cryptr.svg?style=social&label=Star)
- [hash.js](https://github.com/indutny/hash.js) - Hash functions in pure javascript. ![](https://img.shields.io/github/stars/indutny/hash.js.svg?style=social&label=Star)
- [pbkdf2](https://github.com/crypto-browserify/pbkdf2) - PBKDF2 with any supported hashing algorithm in Node. ![](https://img.shields.io/github/stars/crypto-browserify/pbkdf2.svg?style=social&label=Star)
- [bcrypt-pbkdf](https://github.com/joyent/node-bcrypt-pbkdf) - Port of the OpenBSD `bcrypt_pbkdf` function to pure Javascript. ![](https://img.shields.io/github/stars/joyent/node-bcrypt-pbkdf.svg?style=social&label=Star)

### Streams

- [event-stream](https://github.com/dominictarr/event-stream) - EventStream is like functional programming meets IO. ![](https://img.shields.io/github/stars/dominictarr/event-stream.svg?style=social&label=Star)
- [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise. ![](https://img.shields.io/github/stars/rvagg/through2.svg?style=social&label=Star)
- [JSONStream](https://github.com/dominictarr/JSONStream) - streaming JSON.parse and stringify. ![](https://img.shields.io/github/stars/dominictarr/JSONStream.svg?style=social&label=Star)
- [mississippi](https://github.com/maxogden/mississippi) - A collection of useful stream utility modules for writing better code using streams. ![](https://img.shields.io/github/stars/maxogden/mississippi.svg?style=social&label=Star)
- [readable-stream](https://github.com/nodejs/readable-stream) - Node-core streams for userland. ![](https://img.shields.io/github/stars/nodejs/readable-stream.svg?style=social&label=Star)
- [pump](https://github.com/mafintosh/pump) - pipe streams together and close all of them if one of them closes. ![](https://img.shields.io/github/stars/mafintosh/pump.svg?style=social&label=Star)
- [concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result. ![](https://img.shields.io/github/stars/maxogden/concat-stream.svg?style=social&label=Star)
- [stream-json](https://github.com/uhop/stream-json) - stream-json is a collection of node.js stream components for creating custom standard-compliant JSON processors, which requires a minimal memory footprint. It can parse JSON files far exceeding available memory. Even individual primitive data items (keys, strings, and numbers) can be streamed piece-wise. Streaming SAX-inspired event-based API is included as well. ![](https://img.shields.io/github/stars/uhop/stream-json.svg?style=social&label=Star)
- [split](https://github.com/dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk. matcher may be a String, or a RegExp. ![](https://img.shields.io/github/stars/dominictarr/split.svg?style=social&label=Star)
- [tar-stream](https://github.com/mafintosh/tar-stream) - tar-stream is a streaming tar parser and generator. ![](https://img.shields.io/github/stars/mafintosh/tar-stream.svg?style=social&label=Star)
- [node-byline](https://github.com/jahewson/node-byline) - Line-by-line Stream reader. ![](https://img.shields.io/github/stars/jahewson/node-byline.svg?style=social&label=Star)
- [ndjson](https://github.com/maxogden/ndjson) - streaming line delimited json parser + serializer](https://github.com/mcollina/cloneable-readable). ![](https://img.shields.io/github/stars/maxogden/ndjson.svg?style=social&label=Star)
- [oppressor](https://github.com/substack/oppressor) - streaming http compression response negotiator. ![](https://img.shields.io/github/stars/substack/oppressor.svg?style=social&label=Star)
- [multistream](https://github.com/feross/multistream) - A stream that emits multiple other streams one after another (streams2). ![](https://img.shields.io/github/stars/feross/multistream.svg?style=social&label=Star)
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string, buffer, or array. ![](https://img.shields.io/github/stars/sindresorhus/get-stream.svg?style=social&label=Star)
- [node-stream-buffer](https://github.com/samcday/node-stream-buffer) - Readable and Writable Streams that use backing Buffers. ![](https://img.shields.io/github/stars/samcday/node-stream-buffer.svg?style=social&label=Star)
- [split2](https://github.com/mcollina/split2) - Split streams3 style. ![](https://img.shields.io/github/stars/mcollina/split2.svg?style=social&label=Star)
- [fstream](https://github.com/npm/fstream) - Advanced FS Streaming for Node. ![](https://img.shields.io/github/stars/npm/fstream.svg?style=social&label=Star)
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream using pump and duplexify. ![](https://img.shields.io/github/stars/mafintosh/pumpify.svg?style=social&label=Star)
- [progress-stream](https://github.com/freeall/progress-stream) - Read the progress of a stream. ![](https://img.shields.io/github/stars/freeall/progress-stream.svg?style=social&label=Star)
- [merge-stream](https://github.com/grncdr/merge-stream) - Merge multiple streams into one interleaved stream. ![](https://img.shields.io/github/stars/grncdr/merge-stream.svg?style=social&label=Star)
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a streams2 duplex stream with support for async initialization and streams1/streams2 input. ![](https://img.shields.io/github/stars/mafintosh/duplexify.svg?style=social&label=Star)
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream. ![](https://img.shields.io/github/stars/sindresorhus/into-stream.svg?style=social&label=Star)
- [merge2](https://github.com/teambition/merge2) - Merge multiple streams into one stream in sequence or parallel. ![](https://img.shields.io/github/stars/teambition/merge2.svg?style=social&label=Star)
- [end-of-stream](https://github.com/mafintosh/end-of-stream) - Call a callback when a readable/writable/duplex stream has completed or failed. ![](https://img.shields.io/github/stars/mafintosh/end-of-stream.svg?style=social&label=Star)
- [stream-to-promise](https://github.com/bendrucker/stream-to-promise) - Convert streams (readable or writable) to promises. ![](https://img.shields.io/github/stars/bendrucker/stream-to-promise.svg?style=social&label=Star)
- [node-streamifier](https://github.com/gagle/node-streamifier) - Converts a Buffer/String to a readable stream. ![](https://img.shields.io/github/stars/gagle/node-streamifier.svg?style=social&label=Star)
- [stream-spec](https://github.com/dominictarr/stream-spec) - executable specification for Stream (make testing streams easy). ![](https://img.shields.io/github/stars/dominictarr/stream-spec.svg?style=social&label=Star)
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by through2. ![](https://img.shields.io/github/stars/hughsk/from2.svg?style=social&label=Star)
- [dmap-stream](https://github.com/dominictarr/map-stream) - refactored out of event-stream. ![](https://img.shields.io/github/stars/dominictarr/map-stream.svg?style=social&label=Star)
- [emit-stream](https://github.com/substack/emit-stream) - turn event emitters into streams and streams into event emitters. ![](https://img.shields.io/github/stars/substack/emit-stream.svg?style=social&label=Star)
- [stream-combiner](https://github.com/dominictarr/stream-combiner) - Turn a pipeline into a single stream. Combine returns a stream that writes to the first stream and reads from the last stream. ![](https://img.shields.io/github/stars/dominictarr/stream-combiner.svg?style=social&label=Star)
- [duplexer](https://github.com/raynos/duplexer) - Creates a duplex stream. ![](https://img.shields.io/github/stars/raynos/duplexer.svg?style=social&label=Star)
- [promise-streams](https://github.com/spion/promise-streams) - A collection of node.js streams that work well with promises (through, map, reduce, etc...). ![](https://img.shields.io/github/stars/spion/promise-streams.svg?style=social&label=Star)
- [binary-split](https://github.com/maxogden/binary-split) - A fast newline (or any delimiter) splitter stream. ![](https://img.shields.io/github/stars/maxogden/binary-split.svg?style=social&label=Star)
- [stream-combiner2](https://github.com/substack/stream-combiner2) - stream-combiner for streams3. ![](https://img.shields.io/github/stars/substack/stream-combiner2.svg?style=social&label=Star)
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Simple Node.JS stream (streams2) Transform that runs the transform functions concurrently (with a set max concurrency). ![](https://img.shields.io/github/stars/almost/through2-concurrent.svg?style=social&label=Star)
- [cloneable-readable](https://github.com/mcollina/cloneable-readable) - Clone a Readable stream, safely. ![](https://img.shields.io/github/stars/mcollina/cloneable-readable.svg?style=social&label=Star)
- [destroy](https://github.com/stream-utils/destroy) - destroy a stream if possible. ![](https://img.shields.io/github/stars/stream-utils/destroy.svg?style=social&label=Star)
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it. ![](https://img.shields.io/github/stars/mafintosh/peek-stream.svg?style=social&label=Star)
- [resumer](https://github.com/substack/resumer) - a through stream that starts paused and resumes on the next tick. ![](https://img.shields.io/github/stars/substack/resumer.svg?style=social&label=Star)
- [stream-each](https://github.com/mafintosh/stream-each) - Iterate all the data in a stream. ![](https://img.shields.io/github/stars/mafintosh/stream-each.svg?style=social&label=Star)
- [flush-write-stream](https://github.com/mafintosh/flush-write-stream) - A write stream constructor that supports a flush function that is called before finish is emitted. ![](https://img.shields.io/github/stars/mafintosh/flush-write-stream.svg?style=social&label=Star)
- [multi-write-stream](https://github.com/mafintosh/multi-write-stream) - Create a writable stream that writes to multiple other writeable streams. ![](https://img.shields.io/github/stars/mafintosh/multi-write-stream.svg?style=social&label=Star)
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Buffer and transform the n first bytes of a stream. ![](https://img.shields.io/github/stars/sindresorhus/first-chunk-stream.svg?style=social&label=Star)
- [multi-read-stream](https://github.com/mafintosh/multi-read-stream) - Readable stream that reads from multiple readable streams at the same time. ![](https://img.shields.io/github/stars/mafintosh/multi-read-stream.svg?style=social&label=Star)
- [node-stream-reduce](https://github.com/parshap/node-stream-reduce) - Reduce stream data to a single value. ![](https://img.shields.io/github/stars/parshap/node-stream-reduce.svg?style=social&label=Star)
- [stream-shift](https://github.com/mafintosh/stream-shift) - Returns the next buffer/object in a stream's readable queue. ![](https://img.shields.io/github/stars/mafintosh/stream-shift.svg?style=social&label=Star)
- [stream-assert](https://github.com/floatdrop/stream-assert) - Assertion library for streams. ![](https://img.shields.io/github/stars/floatdrop/stream-assert.svg?style=social&label=Star)
- [stream-from-promise](https://github.com/schnittstabil/stream-from-promise) - Create streams from promises. ![](https://img.shields.io/github/stars/schnittstabil/stream-from-promise.svg?style=social&label=Star)
- [stromjs](https://github.com/lewisdiamond/stromjs) - Dependency-free stream utils. The Lodash of streams. ![](https://img.shields.io/github/stars/lewisdiamond/stromjs.svg?style=social&label=Star)
- [exec-stream](https://github.com/suarasaur/exec-stream) - stream to a child process. ![](https://img.shields.io/github/stars/suarasaur/exec-stream.svg?style=social&label=Star)
- [stream-callback](https://github.com/kikobeats/stream-callback) – Turns a stream into a callback. ![](https://img.shields.io/github/stars/kikobeats/stream-callback.svg?style=social&label=Star)

### Check/Detect

- [is.js](https://github.com/arasatasaygin/is.js) - Micro check library. ![](https://img.shields.io/github/stars/arasatasaygin/is.js.svg?style=social&label=Star)
- [is-promise](https://github.com/then/is-promise) - Test whether an object looks like a promises-a+ promise. ![](https://img.shields.io/github/stars/then/is-promise.svg?style=social&label=Star)
- [is-ci](https://github.com/watson/is-ci) - Detect if the current environment is a CI server. ![](https://img.shields.io/github/stars/watson/is-ci.svg?style=social&label=Star)
- [is](https://github.com/enricomarino/is) - The definitive JavaScript type testing library. ![](https://img.shields.io/github/stars/enricomarino/is.svg?style=social&label=Star)
- [is-type-of](https://github.com/node-modules/is-type-of) - Complete type checking for node. ![](https://img.shields.io/github/stars/node-modules/is-type-of.svg?style=social&label=Star)
- [is-stream](https://github.com/sindresorhus/is-stream) - Check if something is a Node.js stream. ![](https://img.shields.io/github/stars/sindresorhus/is-stream.svg?style=social&label=Star)
- [is-utf8](https://github.com/wayfind/is-utf8) - Detect if a buffer is utf8 encoded. ![](https://img.shields.io/github/stars/wayfind/is-utf8.svg?style=social&label=Star)
- [core-util-is](https://github.com/isaacs/core-util-is) - The util.is* functions from Node core. ![](https://img.shields.io/github/stars/isaacs/core-util-is.svg?style=social&label=Star)
- [is-ip](https://github.com/sindresorhus/is-ip) - Check if a string is an IP address. ![](https://img.shields.io/github/stars/sindresorhus/is-ip.svg?style=social&label=Star)
- [isstream](https://github.com/rvagg/isstream) - Determine if an object is a Node.js Stream. ![](https://img.shields.io/github/stars/rvagg/isstream.svg?style=social&label=Star)
- [is-class](https://github.com/miguelmota/is-class) - Check if function is an ES6 class. ![](https://img.shields.io/github/stars/miguelmota/is-class.svg?style=social&label=Star)
- [isexe](https://github.com/isaacs/isexe) - Minimal module to check if a file is executable. ![](https://img.shields.io/github/stars/isaacs/isexe.svg?style=social&label=Star)
- [is-type](https://github.com/juliangruber/is-type) - Type checking from node core. ![](https://img.shields.io/github/stars/juliangruber/is-type.svg?style=social&label=Star)
- [is-md5](https://github.com/imanhodjaev/is-md5) - JavaScript utility to check if string is md5 encrypted. ![](https://img.shields.io/github/stars/imanhodjaev/is-md5.svg?style=social&label=Star)
- [is-core-module](https://github.com/inspect-js/is-core-module) - Is this specifier a node.js core module? ![](https://img.shields.io/github/stars/inspect-js/is-core-module.svg?style=social&label=Star)

### Data Validation

- [validator.js](https://github.com/validatorjs/validator.js) - A library of string validators and sanitizers. ![](https://img.shields.io/github/stars/validatorjs/validator.js.svg?style=social&label=Star)
- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects. ![](https://img.shields.io/github/stars/hapijs/joi.svg?style=social&label=Star)
- [async-validator](https://github.com/yiminghe/async-validator) - Validate form asynchronous. ![](https://img.shields.io/github/stars/yiminghe/async-validator.svg?style=social&label=Star)
- [class-validator](https://github.com/typestack/class-validator) - Decorator-based property validation for classes. ![](https://img.shields.io/github/stars/typestack/class-validator.svg?style=social&label=Star)
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON schema Validator. Supports JSON Schema draft-04/06/07/2019-09/2020-12 and JSON Type Definition (RFC8927). ![](https://img.shields.io/github/stars/epoberezkin/ajv.svg?style=social&label=Star)
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - Simple and composable way to validate data in JavaScript (and TypeScript). ![](https://img.shields.io/github/stars/ianstormtaylor/superstruct.svg?style=social&label=Star)
- [v8n](https://github.com/imbrn/v8n) - JavaScript fluent validation library ![](https://img.shields.io/github/stars/imbrn/v8n.svg?style=social&label=Star)
- [forgJs](https://github.com/oussamahamdaoui/forgJs) - Javascript lightweight object validator. ![](https://img.shields.io/github/stars/oussamahamdaoui/forgJs.svg?style=social&label=Star)
- [jsonschema](https://github.com/tdegrunt/jsonschema) - JSON Schema validation. ![](https://img.shields.io/github/stars/tdegrunt/jsonschema.svg?style=social&label=Star)
- [validatorjs](https://github.com/mikeerickson/validatorjs) - Data validation library in JavaScript for the browser and Node.js, inspired by Laravel's Validator. ![](https://img.shields.io/github/stars/mikeerickson/validatorjs.svg?style=social&label=Star)
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast. ![](https://img.shields.io/github/stars/mafintosh/is-my-json-valid.svg?style=social&label=Star)
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for JavaScript, Node and Express. ![](https://img.shields.io/github/stars/nettofarah/property-validator.svg?style=social&label=Star)
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation. ![](https://img.shields.io/github/stars/Atinux/schema-inspector.svg?style=social&label=Star)

### Functional programming

- [lodash](https://github.com/lodash/lodash) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js. ![](https://img.shields.io/github/stars/lodash/lodash.svg?style=social&label=Star)
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. ![](https://img.shields.io/github/stars/facebook/immutable-js.svg?style=social&label=Star)
- [RxJS](https://github.com/reactivex/rxjs) - Functional reactive library for transforming, composing, and querying various kinds of data. ![](https://img.shields.io/github/stars/reactivex/rxjs.svg?style=social&label=Star)
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data. ![](https://img.shields.io/github/stars/ramda/ramda.svg?style=social&label=Star)
- [Bacon.js](https://github.com/baconjs/bacon.js) - Functional reactive programming. ![](https://img.shields.io/github/stars/baconjs/bacon.js.svg?style=social&label=Star)
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. ![](https://img.shields.io/github/stars/dtao/lazy.js.svg?style=social&label=Star)
- [Folktale](https://github.com/origamitower/folktale) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse. ![](https://img.shields.io/github/stars/origamitower/folktale.svg?style=social&label=Star)
- [Kefir.js](https://github.com/kefirjs/kefir) - Reactive library with focus on high performance and low memory usage. ![](https://img.shields.io/github/stars/kefirjs/kefir.svg?style=social&label=Star)
- [Mout](https://github.com/mout/mout) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead. ![](https://img.shields.io/github/stars/mout/mout.svg?style=social&label=Star)

### Control flow

- Promises
  - [Bluebird](https://github.com/petkaantonov/bluebird) - Bluebird is a fully featured promise library with focus on innovative features and performance. ![](https://img.shields.io/github/stars/petkaantonov/bluebird.svg?style=social&label=Star)
  - [co](https://github.com/tj/co) - The ultimate generator based flow-control goodness for nodejs (supports thunks, promises, etc). ![](https://img.shields.io/github/stars/tj/co.svg?style=social&label=Star)
  - [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function. ![](https://img.shields.io/github/stars/sindresorhus/pify.svg?style=social&label=Star)
  - [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently. ![](https://img.shields.io/github/stars/sindresorhus/p-map.svg?style=social&label=Star)
  - [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time. ![](https://img.shields.io/github/stars/sindresorhus/delay.svg?style=social&label=Star)
  - [thenify](https://github.com/thenables/thenify) - Promisify a callback-based function. ![](https://img.shields.io/github/stars/thenables/thenify.svg?style=social&label=Star)
  - [thenify-all](https://github.com/thenables/thenify-all) - Promisifies all the selected functions in an object. ![](https://img.shields.io/github/stars/thenables/thenify-all.svg?style=social&label=Star)
  - [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch. ![](https://img.shields.io/github/stars/nodeca/promise-memoize.svg?style=social&label=Star)
  - [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function. ![](https://img.shields.io/github/stars/lpinca/valvelet.svg?style=social&label=Star)

- Observables
  - [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming. ![](https://img.shields.io/github/stars/ReactiveX/RxJS.svg?style=social&label=Star)
  - [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables. ![](https://img.shields.io/github/stars/zenparsing/zen-observable.svg?style=social&label=Star)
  - [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise. ![](https://img.shields.io/github/stars/sindresorhus/awesome-observables.svg?style=social&label=Star)

- Callbacks
  - [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity. ![](https://img.shields.io/github/stars/caolan/async.svg?style=social&label=Star)

- Channels
  - [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go). ![](https://img.shields.io/github/stars/ubolonton/js-csp.svg?style=social&label=Star)

- Other
  - [mz](https://github.com/normalize/mz) - Modernize node.js to current ECMAScript standards. ![](https://img.shields.io/github/stars/normalize/mz.svg?style=social&label=Star)
  - [mz-modules](https://github.com/node-modules/mz-modules) - Same as `mz`, but wrap modules in the world rather than core API. ![](https://img.shields.io/github/stars/node-modules/mz-modules.svg?style=social&label=Star)

### Inversion of control / Dependency Injection (Ioc/DI)

- [InversifyJS](https://github.com/inversify/InversifyJS) - A powerful and lightweight inversion of control container for JavaScript & Node.js apps powered by TypeScript. ![](https://img.shields.io/github/stars/inversify/InversifyJS.svg?style=social&label=Star)
- [injection-js](https://github.com/mgechev/injection-js) - Dependency injection library for JavaScript and TypeScript in 5.1K. It is an extraction of the Angular's ReflectiveInjector which means that it's well designed, feature complete, fast, reliable and well tested. ![](https://img.shields.io/github/stars/mgechev/injection-js.svg?style=social&label=Star)
- [power-di](https://github.com/zhang740/power-di) - A lightweight Dependency Injection library. ![](https://img.shields.io/github/stars/zhang740/power-di.svg?style=social&label=Star)

### Shell

- [zx](https://github.com/google/zx) - A tool for writing better scripts. ![](https://img.shields.io/github/stars/google/zx.svg?style=social&label=Star)
- [shelljs](https://github.com/shelljs/shelljs) - Cross-platform Unix shell commands. ![](https://img.shields.io/github/stars/shelljs/shelljs.svg?style=social&label=Star)
- [execa](https://github.com/sindresorhus/execa) - Cross-platform implementation of `child_process.{execFile,exec}`. ![](https://img.shields.io/github/stars/sindresorhus/execa.svg?style=social&label=Star)
- [node-windows](https://github.com/coreybutler/node-windows) - Windows support for Node.js scripts (daemons, eventlog, UAC, etc). ![](https://img.shields.io/github/stars/coreybutler/node-windows.svg?style=social&label=Star)
- [shx](https://github.com/shelljs/shx) - Portable Shell Commands for Node. ![](https://img.shields.io/github/stars/shelljs/shx.svg?style=social&label=Star)
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Cross-platform copy/paste. ![](https://img.shields.io/github/stars/sindresorhus/clipboardy.svg?style=social&label=Star)
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - Cross-platform implementation of `child_process.spawn()`. ![](https://img.shields.io/github/stars/IndigoUnited/node-cross-spawn.svg?style=social&label=Star)
- [parallelshell](https://github.com/darkguy2008/parallelshell) - Run multiple shell commands in parallel. ![](https://img.shields.io/github/stars/darkguy2008/parallelshell.svg?style=social&label=Star)
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Cross-platform copy/paste. ![](https://img.shields.io/github/stars/sindresorhus/clipboard-cli.svg?style=social&label=Star)
- [gulp-execa](https://github.com/ehmicky/gulp-execa) - Cross-platform command execution in Gulp.js. ![](https://img.shields.io/github/stars/ehmicky/gulp-execa.svg?style=social&label=Star)
- [runscript](https://github.com/node-modules/runscript) - Run script easy! ![](https://img.shields.io/github/stars/node-modules/runscript.svg?style=social&label=Star)
- [cross-spawn-promise](https://github.com/zentrick/cross-spawn-promise) - Promisified cross-spawn. ![](https://img.shields.io/github/stars/zentrick/cross-spawn-promise.svg?style=social&label=Star)
- [shell-exec](https://github.com/tiaanduplessis/shell-exec) - Execute a command through the system shell. ![](https://img.shields.io/github/stars/tiaanduplessis/shell-exec.svg?style=social&label=Star)

### Environment

- [dotenv](https://github.com/motdotla/dotenv) - Loads environment variables from .env for nodejs projects. ![](https://img.shields.io/github/stars/motdotla/dotenv.svg?style=social&label=Star)
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. ![](https://img.shields.io/github/stars/kentcdodds/cross-env.svg?style=social&label=Star)
- [envinfo](https://github.com/tabrindle/envinfo) - Generate a report about your development environment for debugging and issue reporting. ![](https://img.shields.io/github/stars/tabrindle/envinfo.svg?style=social&label=Star)
- [which](https://github.com/npm/node-which) - Cross-platform implementation of Unix's `which`. ![](https://img.shields.io/github/stars/npm/node-which.svg?style=social&label=Star)
- [user-home](https://github.com/sindresorhus/user-home) - Get the path to the user home directory. Cross-platform. ![](https://img.shields.io/github/stars/sindresorhus/user-home.svg?style=social&label=Star)
- [username](https://github.com/sindresorhus/username) - Get the current username. ![](https://img.shields.io/github/stars/sindresorhus/username.svg?style=social&label=Star)
- [osenv](https://github.com/npm/osenv) - Cross-platform environment variables. ![](https://img.shields.io/github/stars/npm/osenv.svg?style=social&label=Star)
- [is-elevated](https://github.com/sindresorhus/is-elevated) - Check if the process is running with elevated privileges. ![](https://img.shields.io/github/stars/sindresorhus/is-elevated.svg?style=social&label=Star)

### Event
- [ee-first](https://github.com/jonathanong/ee-first) - Get the first event in a set of event emitters and event pairs, then clean up after itself. ![](https://img.shields.io/github/stars/jonathanong/ee-first.svg?style=social&label=Star)

### Command-line Utilities

- Framework/Solution
  - [Commander.js](https://github.com/tj/commander.js) - The complete solution for node.js command-line interfaces. ![](https://img.shields.io/github/stars/tj/commander.js.svg?style=social&label=Star)
  - [yargs](https://github.com/yargs/yargs) - Collection of common interactive command line user interfaces. ![](https://img.shields.io/github/stars/yargs/yargs.svg?style=social&label=Star)
  - [oclif](https://github.com/oclif/oclif) - Node.js Open CLI Framework. Built with 💜 by Heroku. ![](https://img.shields.io/github/stars/oclif/oclif.svg?style=social&label=Star)
  - [meow](https://github.com/sindresorhus/meow) - CLI app helper. ![](https://img.shields.io/github/stars/sindresorhus/meow.svg?style=social&label=Star)
  - [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps. ![](https://img.shields.io/github/stars/cacjs/cac.svg?style=social&label=Star)
  - [clipanion](https://github.com/arcanis/clipanion) - Type-safe CLI library with no runtime dependencies. ![](https://img.shields.io/github/stars/arcanis/clipanion.svg?style=social&label=Star)
  - [Cliffy](https://github.com/drew-y/cliffy) - Framework for interactive CLIs. ![](https://img.shields.io/github/stars/drew-y/cliffy.svg?style=social&label=Star)
  - [common-bin](https://github.com/node-modules/common-bin) - Abstraction bin tool wrap yargs, to provide more convenient usage, support async / generator. ![](https://img.shields.io/github/stars/node-modules/common-bin.svg?style=social&label=Star)

- Option/Argument parser
  - [minimist](https://github.com/substack/minimist) - Guts of optimist's argument parser without all the fanciful decoration. ![](https://img.shields.io/github/stars/substack/minimist.svg?style=social&label=Star)
  - [arg](https://github.com/vercel/arg) - Simple argument parsing. ![](https://img.shields.io/github/stars/vercel/arg.svg?style=social&label=Star)
  - [nopt](https://github.com/npm/nopt) - Node/npm Option Parsing. ![](https://img.shields.io/github/stars/npm/nopt.svg?style=social&label=Star)
  - [argparse](https://github.com/nodeca/argparse) - CLI arguments parser for node.js. ![](https://img.shields.io/github/stars/nodeca/argparse.svg?style=social&label=Star)
  - [yargs-parser](https://github.com/yargs/yargs-parser) - 💪 the mighty option parser used by yargs. ![](https://img.shields.io/github/stars/yargs/yargs-parser.svg?style=social&label=Star)

- Prompt
  - [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Collection of common interactive command line user interfaces. ![](https://img.shields.io/github/stars/SBoudrias/Inquirer.js.svg?style=social&label=Star)
  - [prompts](https://github.com/terkelg/prompts) - Lightweight, beautiful and user-friendly interactive prompts. ![](https://img.shields.io/github/stars/terkelg/prompts.svg?style=social&label=Star)
  - [Enquirer](https://github.com/enquirer/enquirer) - Stylish CLI prompts that are user-friendly, intuitive and easy to create. ![](https://img.shields.io/github/stars/enquirer/enquirer.svg?style=social&label=Star)
  - [node-promptly](https://github.com/moxystudio/node-promptly) - Simple command line prompting utility for nodejs. ![](https://img.shields.io/github/stars/moxystudio/node-promptly.svg?style=social&label=Star)

- Progress
  - [progress](https://github.com/visionmedia/node-progress) - Flexible ascii progress bar for nodejs. ![](https://img.shields.io/github/stars/visionmedia/node-progress.svg?style=social&label=Star)
  - [progress-estimator](https://github.com/bvaughn/progress-estimator) - Logs a progress bar and estimation for how long a Promise will take to complete. ![](https://img.shields.io/github/stars/bvaughn/progress-estimator.svg?style=social&label=Star)
  - [cli-progress](https://github.com/AndiDittrich/Node.CLI-Progress) - Easy to use progress-bar for command-line/terminal applications. ![](https://img.shields.io/github/stars/AndiDittrich/Node.CLI-Progress.svg?style=social&label=Star)

- Style
  - [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. ![](https://img.shields.io/github/stars/chalk/chalk.svg?style=social&label=Star)
  - [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. ![](https://img.shields.io/github/stars/sindresorhus/ora.svg?style=social&label=Star)
  - [colors.js](https://github.com/Marak/colors.js) - Get colors in your node.js console. ![](https://img.shields.io/github/stars/Marak/colors.js.svg?style=social&label=Star)
  - [listr](https://github.com/SamVerschueren/listr) - Terminal task list. ![](https://img.shields.io/github/stars/SamVerschueren/listr.svg?style=social&label=Star)
  - [figlet.js](https://github.com/patorjk/figlet.js) - A FIG Driver written in JavaScript which aims to fully implement the FIGfont spec. ![](https://img.shields.io/github/stars/patorjk/figlet.js.svg?style=social&label=Star)
  - [kleur](https://github.com/lukeed/kleur) - The fastest Node.js library for formatting terminal text with ANSI colors~! ![](https://img.shields.io/github/stars/lukeed/kleur.svg?style=social&label=Star)
  - [colorette](https://github.com/jorgebucaran/colorette) - Easily set the color and style of text in the terminal. ![](https://img.shields.io/github/stars/jorgebucaran/colorette.svg?style=social&label=Star)
  - [qrcode-terminal](https://github.com/gtanner/qrcode-terminal) - QRCodes in your terminal. ![](https://img.shields.io/github/stars/gtanner/qrcode-terminal.svg?style=social&label=Star)
  - [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. ![](https://img.shields.io/github/stars/sindresorhus/boxen.svg?style=social&label=Star)
  - [terminal-image](https://github.com/sindresorhus/terminal-image) - Display images in the terminal. ![](https://img.shields.io/github/stars/sindresorhus/terminal-image.svg?style=social&label=Star)
  - [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. ![](https://img.shields.io/github/stars/sindresorhus/log-symbols.svg?style=social&label=Star)
  - [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output. ![](https://img.shields.io/github/stars/bokub/gradient-string.svg?style=social&label=Star)
  - [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows fallbacks. ![](https://img.shields.io/github/stars/sindresorhus/figures.svg?style=social&label=Star)
  - [terminal-link](https://github.com/sindresorhus/terminal-link) - Create clickable links in the terminal. ![](https://img.shields.io/github/stars/sindresorhus/terminal-link.svg?style=social&label=Star)
  - [snazzy](https://github.com/standard/snazzy) - Format JavaScript Standard Style as Stylish (i.e. snazzy) output. ![](https://img.shields.io/github/stars/standard/snazzy.svg?style=social&label=Star)
  - [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping. ![](https://img.shields.io/github/stars/timoxley/columnify.svg?style=social&label=Star)
  - [cli-table3](https://github.com/cli-table/cli-table3) - Pretty unicode tables for the command line. ![](https://img.shields.io/github/stars/cli-table/cli-table3.svg?style=social&label=Star)
  - [easy-table](https://github.com/eldargab/easy-table) - Nice text table for Node.js. ![](https://img.shields.io/github/stars/eldargab/easy-table.svg?style=social&label=Star)
  - [cli-highlight](https://github.com/felixfbecker/cli-highlight) - Syntax highlighting for your terminal 💻✨. ![](https://img.shields.io/github/stars/felixfbecker/cli-highlight.svg?style=social&label=Star)
  - [treeify](https://github.com/notatestuser/treeify) - Pretty-print a javascript object as a tree. ![](https://img.shields.io/github/stars/notatestuser/treeify.svg?style=social&label=Star)
  - [kolorist](https://github.com/marvinhagemeister/kolorist) - A tiny utility to colorize stdin/stdout. ![](https://img.shields.io/github/stars/marvinhagemeister/kolorist.svg?style=social&label=Star)
  - [console-png](https://github.com/aantthony/console-png) - Print PNG images to terminal output. ![](https://img.shields.io/github/stars/aantthony/console-png.svg?style=social&label=Star)

- Editor
  - [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor. ![](https://img.shields.io/github/stars/slap-editor/slap.svg?style=social&label=Star)

- Other
  - [commitizen](https://github.com/commitizen/cz-cli) - The commitizen command line utility. ![](https://img.shields.io/github/stars/commitizen/cz-cli.svg?style=social&label=Star)
  - [plop](https://github.com/plopjs/plop) - Micro-generator framework that makes it easy for an entire team to create files with a level of uniformity. ![](https://img.shields.io/github/stars/plopjs/plop.svg?style=social&label=Star)
  - [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app. ![](https://img.shields.io/github/stars/yeoman/update-notifier.svg?style=social&label=Star)
  - [console-stamp](https://github.com/starak/node-console-stamp) - Patch NodeJS console methods in order to add timestamp information by pattern. ![](https://img.shields.io/github/stars/starak/node-console-stamp.svg?style=social&label=Star)
  - [didyoumean](https://github.com/dcporter/didyoumean.js) - A simple, optimized JS library & node.js module for matching short, human-quality input to a list of possibilities. ![](https://img.shields.io/github/stars/dcporter/didyoumean.js.svg?style=social&label=Star)
  - [console-clear](https://github.com/lukeed/console-clear) - Clear the console, cross-platform. ![](https://img.shields.io/github/stars/lukeed/console-clear.svg?style=social&label=Star)

### Node.js Management

- [nvm](https://github.com/nvm-sh/nvm) - Node Version Manager。 ![](https://img.shields.io/github/stars/nvm-sh/nvm.svg?style=social&label=Star)
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows. ![](https://img.shields.io/github/stars/coreybutler/nvm-windows.svg?style=social&label=Star)
- [n](https://github.com/tj/n) - Node.js version management. ![](https://img.shields.io/github/stars/tj/n.svg?style=social&label=Star)
- [fnm](https://github.com/Schniz/fnm) - 🚀 Fast and simple Node.js version manager, built in Rust. ![](https://img.shields.io/github/stars/Schniz/fnm.svg?style=social&label=Star)
- [nodenv](https://github.com/nodenv/nodenv) - Version manager that is similar to Ruby's rbenv. It supports auto version switching. ![](https://img.shields.io/github/stars/nodenv/nodenv.svg?style=social&label=Star)
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js. ![](https://img.shields.io/github/stars/isaacs/nave.svg?style=social&label=Star)
- [nvs](https://github.com/jasongin/nvs) - Node Version Switcher - A cross-platform tool for switching between versions and forks of Node.js ![](https://img.shields.io/github/stars/jasongin/nvs.svg?style=social&label=Star)
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv. ![](https://img.shields.io/github/stars/ekalinin/nodeenv.svg?style=social&label=Star)

### NPM

- NPM Management
  - [pnpm](https://github.com/pnpm/pnpm) - Fast, disk space efficient package manager. ![](https://img.shields.io/github/stars/pnpm/pnpm.svg?style=social&label=Star)
  - [npm](https://github.com/npm/cli) - The package manager for JavaScript. ![](https://img.shields.io/github/stars/npm/cli.svg?style=social&label=Star)
  - [yarn](https://github.com/yarnpkg/berry) - A modern package manager split into various packages. ![](https://img.shields.io/github/stars/yarnpkg/berry.svg?style=social&label=Star)
  - [yalc](https://github.com/wclr/yalc) - Work with yarn/npm packages locally like a boss. ![](https://img.shields.io/github/stars/wclr/yalc.svg?style=social&label=Star)
  - [nrm](https://github.com/Pana/nrm) - About NPM registry manager, fast switch between different registries: npm, cnpm, nj, taobao. ![](https://img.shields.io/github/stars/Pana/nrm.svg?style=social&label=Star)
  - [cnpm](https://github.com/cnpm/cnpm) - Npm client for China mirror of npm. ![](https://img.shields.io/github/stars/cnpm/cnpm.svg?style=social&label=Star)

- package.json
  - [read-pkg-up](https://github.com/sindresorhus/read-pkg-up) - Read the closest package.json file. ![](https://img.shields.io/github/stars/sindresorhus/read-pkg-up.svg?style=social&label=Star)
  - [node-pkginfo](https://github.com/indexzero/node-pkginfo) - An easy way to expose properties on a module from a package.json. ![](https://img.shields.io/github/stars/indexzero/node-pkginfo.svg?style=social&label=Star)
  - [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package. ![](https://img.shields.io/github/stars/sindresorhus/pkg-dir.svg?style=social&label=Star)
  - [read-pkg](https://github.com/sindresorhus/read-pkg) - Read a package.json file. ![](https://img.shields.io/github/stars/sindresorhus/read-pkg.svg?style=social&label=Star)
  - [write-pkg](https://github.com/sindresorhus/write-pkg) - Write a package.json file. ![](https://img.shields.io/github/stars/sindresorhus/write-pkg.svg?style=social&label=Star)
  - [read-package-json-fast](https://github.com/npm/read-package-json-fast) - Like read-package-json, but faster. ![](https://img.shields.io/github/stars/npm/read-package-json-fast.svg?style=social&label=Star)

- Semantic Version
  - [semver](https://github.com/npm/node-semver) - The semver parser for node (the one npm uses). ![](https://img.shields.io/github/stars/npm/node-semver.svg?style=social&label=Star)
  - [compare-versions](https://github.com/omichelsen/compare-versions) - Compare semver version strings to find which is greater, equal or lesser. ![](https://img.shields.io/github/stars/omichelsen/compare-versions.svg?style=social&label=Star)
  - [semver-diff](https://github.com/sindresorhus/semver-diff) - Get the diff type of two semver versions: 0.0.1 0.0.2 → patch. ![](https://img.shields.io/github/stars/sindresorhus/semver-diff.svg?style=social&label=Star)

- Private Npm Registry
  - [verdaccio](https://github.com/verdaccio/verdaccio) - A lightweight private proxy registry build in Node.js. ![](https://img.shields.io/github/stars/verdaccio/verdaccio.svg?style=social&label=Star)
  - [cnpmjs.org](https://github.com/cnpm/cnpmjs.org) - Private npm registry and web for Enterprise. ![](https://img.shields.io/github/stars/cnpm/cnpmjs.org.svg?style=social&label=Star)

- Utilities
  - [npm-check-updates](https://github.com/raineorshine/npm-check-updates) - Find newer versions of package dependencies than what your package.json allows. ![](https://img.shields.io/github/stars/raineorshine/npm-check-updates.svg?style=social&label=Star)
  - [concurrently](https://github.com/open-cli-tools/concurrently) - Run commands concurrently. Like `npm run watch-js & npm run watch-less` but better. ![](https://img.shields.io/github/stars/open-cli-tools/concurrently.svg?style=social&label=Star)
  - [npm-run-all](https://github.com/mysticatea/npm-run-all) - A CLI tool to run multiple npm-scripts in parallel or sequential. ![](https://img.shields.io/github/stars/mysticatea/npm-run-all.svg?style=social&label=Star)
  - [depcheck](https://github.com/depcheck/depcheck) - Check your npm module for unused dependencies. ![](https://img.shields.io/github/stars/depcheck/depcheck.svg?style=social&label=Star)
  - [npminstall](https://github.com/cnpm/npminstall) - Make `npm install` fast and easy. ![](https://img.shields.io/github/stars/cnpm/npminstall.svg?style=social&label=Star)
  - [validate-npm-package-name](https://github.com/npm/validate-npm-package-name) - Is the given string an acceptable npm package name? ![](https://img.shields.io/github/stars/npm/validate-npm-package-name.svg?style=social&label=Star)
  - [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. ![](https://img.shields.io/github/stars/sindresorhus/npm-home.svg?style=social&label=Star)
  - [npm-name](https://github.com/sindresorhus/npm-name) - Check a package name's availability on npm. ![](https://img.shields.io/github/stars/sindresorhus/npm-name.svg?style=social&label=Star)
  - [pacote](https://github.com/npm/pacote) - Fetches package manifests and tarballs from the npm registry. ![](https://img.shields.io/github/stars/npm/pacote.svg?style=social&label=Star)
  - [npm-package-arg](https://github.com/npm/npm-package-arg) - Parse the things that can be arguments to `npm install`. ![](https://img.shields.io/github/stars/npm/npm-package-arg.svg?style=social&label=Star)
  - [npm-registry-fetch](https://github.com/npm/npm-registry-fetch) - Like fetch() but for the npm registry ![](https://img.shields.io/github/stars/npm/npm-registry-fetch.svg?style=social&label=Star)
  - [npm-updater](https://github.com/node-modules/npm-updater) - Check update of npm package. ![](https://img.shields.io/github/stars/node-modules/npm-updater.svg?style=social&label=Star)

### Monorepo
*(You might like [awesome-monorepo](https://github.com/korfuri/awesome-monorepo))*

- [lerna](https://github.com/lerna/lerna) - A tool for managing JavaScript projects with multiple packages. ![](https://img.shields.io/github/stars/lerna/lerna.svg?style=social&label=Star)
- [rush](https://rushjs.io/) - The scalable monorepo build orchestrator。

### Filesystem

- Common
  - [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module. ![](https://img.shields.io/github/stars/jprichardson/node-fs-extra.svg?style=social&label=Star)
  - [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Graceful-fs functions as a drop-in replacement for the fs module, making various improvements. ![](https://img.shields.io/github/stars/isaacs/node-graceful-fs.svg?style=social&label=Star)
  - [filesize.js](https://github.com/avoidwork/filesize.js) - Generate a human readable String describing the file size. ![](https://img.shields.io/github/stars/avoidwork/filesize.js.svg?style=social&label=Star)
  - [memfs](https://github.com/streamich/memfs) - In-memory filesystem with Node's API. ![](https://img.shields.io/github/stars/streamich/memfs.svg?style=social&label=Star)
  - [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use. ![](https://img.shields.io/github/stars/szwacz/fs-jetpack.svg?style=social&label=Star)
  - [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like mkdir -p. ![](https://img.shields.io/github/stars/sindresorhus/make-dir.svg?style=social&label=Star)
  - [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename. ![](https://img.shields.io/github/stars/sindresorhus/filenamify.svg?style=social&label=Star)
  - [move-file](https://github.com/sindresorhus/move-file) - Move a file, even works across devices. ![](https://img.shields.io/github/stars/sindresorhus/move-file.svg?style=social&label=Star)
  - [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility. ![](https://img.shields.io/github/stars/IndigoUnited/node-proper-lockfile.svg?style=social&label=Star)
  - [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary. ![](https://img.shields.io/github/stars/bevry/istextorbinary.svg?style=social&label=Star)
  - [mkdirp](https://github.com/isaacs/node-mkdirp) - Recursively mkdir, like `mkdir -p`. ![](https://img.shields.io/github/stars/isaacs/node-mkdirp.svg?style=social&label=Star)
  - [dir-compare](https://github.com/gliviu/dir-compare) - Node JS directory compare. ![](https://img.shields.io/github/stars/gliviu/dir-compare.svg?style=social&label=Star)
  - [folder-hash](https://github.com/marc136/node-folder-hash) - Create a hash checksum over a folder or a file. ![](https://img.shields.io/github/stars/marc136/node-folder-hash.svg?style=social&label=Star)
  - [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`. ![](https://img.shields.io/github/stars/kevva/lnfs.svg?style=social&label=Star)

- Copy
  - [ncp](https://github.com/AvianFlu/ncp) - Asynchronous recursive file copying with Node.js. ![](https://img.shields.io/github/stars/AvianFlu/ncp.svg?style=social&label=Star)
  - [cpy](https://github.com/sindresorhus/cpy) - Copy files. ![](https://img.shields.io/github/stars/sindresorhus/cpy.svg?style=social&label=Star)
  - [copyfiles](https://github.com/calvinmetcalf/copyfiles) - Copy files on the command line. ![](https://img.shields.io/github/stars/calvinmetcalf/copyfiles.svg?style=social&label=Star)

- Delete
  - [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like rm -rf. ![](https://img.shields.io/github/stars/isaacs/rimraf.svg?style=social&label=Star)
  - [del](https://github.com/sindresorhus/del) - Delete files and directories. ![](https://img.shields.io/github/stars/sindresorhus/del.svg?style=social&label=Star)

- Temporary
  - [temp](https://github.com/bruce/node-temp) - Temporary File, Directory, and Stream support for Node.js. ![](https://img.shields.io/github/stars/bruce/node-temp.svg?style=social&label=Star)
  - [tempy](https://github.com/sindresorhus/tempy) - Get a random temporary file or directory path. 302 ![](https://img.shields.io/github/stars/sindresorhus/tempy.svg?style=social&label=Star)
  - [temp-dir](https://github.com/sindresorhus/temp-dir) - Get the real path of the system temp directory. ![](https://img.shields.io/github/stars/sindresorhus/temp-dir.svg?style=social&label=Star)

- Watch
  - [chokidar](https://github.com/paulmillr/chokidar) - Minimal and efficient cross-platform file watching library. ![](https://img.shields.io/github/stars/paulmillr/chokidar.svg?style=social&label=Star)
  - [watchpack](https://github.com/webpack/watchpack) - Wrapper library for directory and file watching. ![](https://img.shields.io/github/stars/webpack/watchpack.svg?style=social&label=Star)

- Find
  - [glob](https://github.com/isaacs/node-glob) - Glob functionality for node.js. ![](https://img.shields.io/github/stars/isaacs/node-glob.svg?style=social&label=Star)
  - [globby](https://github.com/sindresorhus/globby) - Based on fast-glob but adds a bunch of useful features. ![](https://img.shields.io/github/stars/sindresorhus/globby.svg?style=social&label=Star)
  - [fast-glob](https://github.com/mrmlnc/fast-glob) - Very fast and efficient glob library for Node.js. ![](https://img.shields.io/github/stars/mrmlnc/fast-glob.svg?style=social&label=Star)
  - [find-up](https://github.com/sindresorhus/find-up) - Find a file or directory by walking up parent directories. ![](https://img.shields.io/github/stars/sindresorhus/find-up.svg?style=social&label=Star)
  - [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system. ![](https://img.shields.io/github/stars/nspragg/filehound.svg?style=social&label=Star)
  - [node-sync-glob](https://github.com/AndyOGo/node-sync-glob) - Synchronize files and folders locally by glob patterns, watch option included. ![](https://img.shields.io/github/stars/AndyOGo/node-sync-glob.svg?style=social&label=Star)

### Parsing

- Markdown
  - [marked](https://github.com/markedjs/marked) - A markdown parser and compiler. Built for speed. ![](https://img.shields.io/github/stars/markedjs/marked.svg?style=social&label=Star)
  - [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins. ![](https://img.shields.io/github/stars/wooorm/remark.svg?style=social&label=Star)
  - [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins. ![](https://img.shields.io/github/stars/markdown-it/markdown-it.svg?style=social&label=Star)
  - [turndown](https://github.com/mixmark-io/turndown) - An HTML to Markdown converter written in JavaScript. ![](https://img.shields.io/github/stars/mixmark-io/turndown.svg?style=social&label=Star)
  - [remove-markdown](https://github.com/stiang/remove-markdown) - Strip Markdown stuff from text. ![](https://img.shields.io/github/stars/stiang/remove-markdown.svg?style=social&label=Star)

- CSV
  - [PapaParse](https://github.com/mholt/PapaParse) - Fast and powerful CSV (delimited text) parser that gracefully handles large files and malformed input. ![](https://img.shields.io/github/stars/mholt/PapaParse.svg?style=social&label=Star)
  - [node-csv](https://github.com/adaltas/node-csv) - Full featured CSV parser with simple api and tested against large datasets. ![](https://img.shields.io/github/stars/adaltas/node-csv.svg?style=social&label=Star)
  - [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else. ![](https://img.shields.io/github/stars/mafintosh/csv-parser.svg?style=social&label=Star)
  - [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above. ![](https://img.shields.io/github/stars/sindresorhus/neat-csv.svg?style=social&label=Star)

- YAML
  - [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser. ![](https://img.shields.io/github/stars/nodeca/js-yaml.svg?style=social&label=Star)
  - [yaml](https://github.com/eemeli/yaml) - JavaScript parser and stringifier for YAML. ![](https://img.shields.io/github/stars/eemeli/yaml.svg?style=social&label=Star)

- XML
  - [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter. ![](https://img.shields.io/github/stars/Leonidas-from-XIV/node-xml2js.svg?style=social&label=Star)
  - [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Validate and parse XML. ![](https://img.shields.io/github/stars/NaturalIntelligence/fast-xml-parser.svg?style=social&label=Star)
  - [xmlbuilder](https://github.com/oozcitak/xmlbuilder-js) - An XML builder for node.js. ![](https://img.shields.io/github/stars/oozcitak/xmlbuilder-js.svg?style=social&label=Star)
  - [js2xmlparser](https://github.com/michaelkourlas/node-js2xmlparser) - Popular Node.js module for parsing JavaScript objects into XML. ![](https://img.shields.io/github/stars/michaelkourlas/node-js2xmlparser.svg?style=social&label=Star)

- HTML
  - [htmlparser2](https://github.com/fb55/htmlparser2) - Forgiving HTML and XML parser. ![](https://img.shields.io/github/stars/fb55/htmlparser2.svg?style=social&label=Star)
  - [parse5](https://github.com/inikulin/parse5) - HTML parsing/serialization toolset for Node.js. WHATWG HTML Living Standard (aka HTML5)-compliant. ![](https://img.shields.io/github/stars/inikulin/parse5.svg?style=social&label=Star)
  - [sanitize-html](https://github.com/apostrophecms/sanitize-html) - Clean up user-submitted HTML, preserving whitelisted elements and whitelisted attributes on a per-element basis. Built on htmlparser2 for speed and tolerance. ![](https://img.shields.io/github/stars/apostrophecms/sanitize-html.svg?style=social&label=Star)
  - [himalaya](https://github.com/andrejewski/himalaya) - JavaScript HTML to JSON Parser. ![](https://img.shields.io/github/stars/andrejewski/himalaya.svg?style=social&label=Star)

- CSS
  - [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier. ![](https://img.shields.io/github/stars/postcss/postcss.svg?style=social&label=Star)
  - [less](https://github.com/less/less.js) - Less. The dynamic stylesheet language. ![](https://img.shields.io/github/stars/less/less.js.svg?style=social&label=Star)

- SQL
  - [pgsql-ast-parser](https://github.com/oguimbal/pgsql-ast-parser) - Yet another simple Postgres SQL parser. ![](https://img.shields.io/github/stars/oguimbal/pgsql-ast-parser.svg?style=social&label=Star)
  - [dt-sql-parser](https://github.com/DTStack/dt-sql-parser) - SQL Parsers for BigData, built with antlr4. ![](https://img.shields.io/github/stars/DTStack/dt-sql-parser.svg?style=social&label=Star)

- Plist
  - [node-bplist-parser](https://github.com/joeferner/node-bplist-parser) - Binary plist parser. ![](https://img.shields.io/github/stars/joeferner/node-bplist-parser.svg?style=social&label=Star)

- ini
  - [ini](https://github.com/npm/ini) - An ini parser/serializer in JavaScript. ![](https://img.shields.io/github/stars/npm/ini.svg?style=social&label=Star)

- Other
  - [readability](https://github.com/mozilla/readability) - A standalone version of the readability library used for Firefox Reader View. ![](https://img.shields.io/github/stars/mozilla/readability.svg?style=social&label=Star)

### Git

- [husky](https://github.com/typicode/husky) - Modern native Git hooks made easy 🐶 woof! ![](https://img.shields.io/github/stars/typicode/husky.svg?style=social&label=Star)
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - A pure JavaScript implementation of git for node and browsers! ![](https://img.shields.io/github/stars/isomorphic-git/isomorphic-git.svg?style=social&label=Star)
- [nodegit](https://github.com/nodegit/nodegit) - Node bindings to the libgit2 project. ![](https://img.shields.io/github/stars/nodegit/nodegit.svg?style=social&label=Star)
- [js-git](https://github.com/creationix/js-git) - A JavaScript implementation of Git. ![](https://img.shields.io/github/stars/creationix/js-git.svg?style=social&label=Star)
- [degit](https://github.com/Rich-Harris/degit) - Degit makes copies of git repositories. Straightforward project scaffolding. ![](https://img.shields.io/github/stars/Rich-Harris/degit.svg?style=social&label=Star)
- [simple-git](https://github.com/steveukx/git-js) - A light weight interface for running git commands in any node.js application. ![](https://img.shields.io/github/stars/steveukx/git-js.svg?style=social&label=Star)
- [gitgraph-node](https://github.com/nicoespeon/gitgraph.js/tree/master/packages/gitgraph-node) - Draw pretty git graphs in your terminal. ![](https://img.shields.io/github/stars/nicoespeon/gitgraph.js.svg?style=social&label=Star)
- [pre-commit](https://github.com/observing/pre-commit) - Automatically installs a git pre-commit script in your git repository which runs your `npm test` on pre-commit. ![](https://img.shields.io/github/stars/observing/pre-commit.svg?style=social&label=Star)
- [yorkie](https://github.com/yyx990803/yorkie) -  A fork of husky, 🐶 Git hooks made easy, used in vue3. ![](https://img.shields.io/github/stars/yyx990803/yorkie.svg?style=social&label=Star)
- [git-url-parse](https://github.com/IonicaBizau/git-url-parse) - A high level git url parser for common git providers. ![](https://img.shields.io/github/stars/IonicaBizau/git-url-parse.svg?style=social&label=Star)
- [git-promise](https://github.com/piuccio/git-promise) - Simple wrapper to run any git command and process it's output using promises. ![](https://img.shields.io/github/stars/piuccio/git-promise.svg?style=social&label=Star)
- [gittar](https://github.com/lukeed/gittar) - Download and/or Extract git repositories (GitHub, GitLab, BitBucket). Cross-platform and Offline-first. ![](https://img.shields.io/github/stars/lukeed/gittar.svg?style=social&label=Star)
- [parse-git-config](https://github.com/jonschlinkert/parse-git-config) - Parse `.git/config` into a JavaScript object. sync or async. ![](https://img.shields.io/github/stars/jonschlinkert/parse-git-config.svg?style=social&label=Star)
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. Using only JS. ![](https://img.shields.io/github/stars/sindresorhus/remote-git-tags.svg?style=social&label=Star)
- [giturl](https://github.com/repo-utils/giturl) - Transfer git url to web url. ![](https://img.shields.io/github/stars/repo-utils/giturl.svg?style=social&label=Star)
- [download-git-repo](https://gitlab.com/flippidippi/download-git-repo) - Download and extract a git repository (GitHub, GitLab, Bitbucket) from node.

### Logging

- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. ![](https://img.shields.io/github/stars/winstonjs/winston.svg?style=social&label=Star)
- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. ![](https://img.shields.io/github/stars/pinojs/pino.svg?style=social&label=Star)
- [signale](https://github.com/klauscfhq/signale) - Highly configurable logging utility. ![](https://img.shields.io/github/stars/klauscfhq/signale.svg?style=social&label=Star)
- [bunyan](https://github.com/trentm/node-bunyan) - A simple and fast JSON logging module for node.js services. ![](https://img.shields.io/github/stars/trentm/node-bunyan.svg?style=social&label=Star)
- [log4js-node](https://github.com/log4js-node/log4js-node) - A logging library which different from Java log4j. ![](https://img.shields.io/github/stars/log4js-node/log4js-node.svg?style=social&label=Star)
- [consola](https://github.com/nuxt/consola) - Elegant Console Logger for Node.js and Browser. ![](https://img.shields.io/github/stars/nuxt/consola.svg?style=social&label=Star)
- [loglevel](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods. ![](https://img.shields.io/github/stars/pimterry/loglevel.svg?style=social&label=Star)
- [roarr](https://github.com/gajus/roarr) - JSON logger for Node.js and browser. ![](https://img.shields.io/github/stars/gajus/roarr.svg?style=social&label=Star)
- [storyboard](https://github.com/guigrpa/storyboard) - A library, plus a Chrome DevTools extension. ![](https://img.shields.io/github/stars/guigrpa/storyboard.svg?style=social&label=Star)
- [cabin](https://github.com/cabinjs/cabin) - Best JavaScript and Node.js logging service and logging npm package. ![](https://img.shields.io/github/stars/cabinjs/cabin.svg?style=social&label=Star)
- [caterpillar](https://github.com/bevry/caterpillar) - Caterpillar is the ultimate logging system for Deno, Node.js, and Web Browsers. Log levels are implemented to the RFC standard. Log entries can be filtered and piped to various streams, including coloured output to the terminal, the browser's console, and debug files. You can even write your own transforms. ![](https://img.shields.io/github/stars/bevry/caterpillar.svg?style=social&label=Star)
- [fancy-log](https://github.com/gulpjs/fancy-log) - Log things, prefixed with a timestamp. ![](https://img.shields.io/github/stars/gulpjs/fancy-log.svg?style=social&label=Star)
- [captains-log](https://github.com/balderdashy/captains-log) - Lightweight logger with a simple pass-through configuration for use with fancier logging librarie. ![](https://img.shields.io/github/stars/balderdashy/captains-log.svg?style=social&label=Star)

### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager. ![](https://img.shields.io/github/stars/Unitech/pm2.svg?style=social&label=Star)
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server. ![](https://img.shields.io/github/stars/remy/nodemon.svg?style=social&label=Star)
- [forever](https://github.com/foreversd/forever) - A simple CLI tool for ensuring that a given script runs continuously. ![](https://img.shields.io/github/stars/foreversd/forever.svg?style=social&label=Star)
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes. ![](https://img.shields.io/github/stars/petruisfan/node-supervisor.svg?style=social&label=Star)
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer. ![](https://img.shields.io/github/stars/coreybutler/node-windows.svg?style=social&label=Star)
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app. ![](https://img.shields.io/github/stars/coreybutler/node-mac.svg?style=social&label=Star)
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog. ![](https://img.shields.io/github/stars/coreybutler/node-linux.svg?style=social&label=Star)
- [current-processes](https://github.com/branneman/current-processes) - Node.js library to get a snapshot of the currently running processes, OS-agnostic. ![](https://img.shields.io/github/stars/branneman/current-processes.svg?style=social&label=Star)

### Linter & Formatter

- [prettier](https://github.com/prettier/prettier) - ❤Prettier is an opinionated code formatter. ![](https://img.shields.io/github/stars/prettier/prettier.svg?style=social&label=Star)
- [standard](https://github.com/standard/standard) - JavaScript Style Guide, with linter & automatic code fixer. ![](https://img.shields.io/github/stars/standard/standard.svg?style=social&label=Star)
- [eslint](https://github.com/eslint/eslint) - Find and fix problems in your JavaScript code. ![](https://img.shields.io/github/stars/eslint/eslint.svg?style=social&label=Star)
- [stylelint](https://github.com/stylelint/stylelint) - Mighty, modern linter that helps you avoid errors and enforce conventions in your styles. ![](https://img.shields.io/github/stars/stylelint/stylelint.svg?style=social&label=Star)
- [lint-staged](https://github.com/okonet/lint-staged) - Run linters on git staged files. ![](https://img.shields.io/github/stars/okonet/lint-staged.svg?style=social&label=Star)
- [commitlint](https://github.com/conventional-changelog/commitlint) - Lint commit messages. ![](https://img.shields.io/github/stars/conventional-changelog/commitlint.svg?style=social&label=Star)
- [js-beautify](https://github.com/beautify-web/js-beautify) - Beautifier for javascript. ![](https://img.shields.io/github/stars/beautify-web/js-beautify.svg?style=social&label=Star)
- [xo](https://github.com/xojs/xo) - JavaScript/TypeScript linter (ESLint wrapper) with great defaults ![](https://img.shields.io/github/stars/xojs/xo.svg?style=social&label=Star)
- [markdownlint](https://github.com/DavidAnson/markdownlint) - A Node.js style checker and lint tool for Markdown/CommonMark files. ![](https://img.shields.io/github/stars/DavidAnson/markdownlint.svg?style=social&label=Star)
- [textlint](https://github.com/textlint/textlint) - The pluggable natural language linter for text and markdown. ![](https://img.shields.io/github/stars/textlint/textlint.svg?style=social&label=Star)
- [pretty-quick](https://github.com/azz/pretty-quick) - ⚡ Get Pretty Quick. ![](https://img.shields.io/github/stars/azz/pretty-quick.svg?style=social&label=Star)
- [dtslint](https://github.com/Microsoft/dtslint) - A utility built on TSLint for linting TypeScript declaration (.d.ts) files. ![](https://img.shields.io/github/stars/Microsoft/dtslint.svg?style=social&label=Star)

### Configuration Tools

- [node-config](https://github.com/lorenwest/node-config) - Node.js Application Configuration. ![](https://img.shields.io/github/stars/lorenwest/node-config.svg?style=social&label=Star)
- [nconf](https://github.com/indexzero/nconf) - Hierarchical node.js configuration with files, environment variables, command-line arguments, and atomic object merging. ![](https://img.shields.io/github/stars/indexzero/nconf.svg?style=social&label=Star)
- [convict](https://github.com/mozilla/node-convict/tree/master/packages/convict) - Convict expands on the standard pattern of configuring node.js applications in a way that is more robust and accessible to collaborators. ![](https://img.shields.io/github/stars/mozilla/node-convict.svg?style=social&label=Star)
- [rc](https://github.com/dominictarr/rc) - The non-configurable configuration loader for lazy people. ![](https://img.shields.io/github/stars/dominictarr/rc.svg?style=social&label=Star)

### Build Tools

- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser. ![](https://img.shields.io/github/stars/webpack/webpack.svg?style=social&label=Star)
- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler. ![](https://img.shields.io/github/stars/parcel-bundler/parcel.svg?style=social&label=Star)
- [gulp](https://github.com/gulpjs/gulp) - Streaming and fast build system that favors code over config. ![](https://img.shields.io/github/stars/gulpjs/gulp.svg?style=social&label=Star)
- [esbuild](https://github.com/evanw/esbuild) - An extremely fast JavaScript bundler and minifier. ![](https://img.shields.io/github/stars/evanw/esbuild.svg?style=social&label=Star)
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler. ![](https://img.shields.io/github/stars/rollup/rollup.svg?style=social&label=Star)
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable. ![](https://img.shields.io/github/stars/zeit/pkg.svg?style=social&label=Star)
- [Grunt](https://github.com/gruntjs/grunt) - JavaScript Task Runner ![](https://img.shields.io/github/stars/gruntjs/grunt.svg?style=social&label=Star)
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow. ![](https://img.shields.io/github/stars/brunch/brunch.svg?style=social&label=Star)
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support. ![](https://img.shields.io/github/stars/fuse-box/fuse-box.svg?style=social&label=Star)
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions. ![](https://img.shields.io/github/stars/broccolijs/broccoli.svg?style=social&label=Star)

- ESM
  - [Vite](https://github.com/vitejs/vite) - Next Generation Frontend Tooling. ![](https://img.shields.io/github/stars/vitejs/vite.svg?style=social&label=Star)
  - [snowpack](https://github.com/snowpackjs/snowpack) - ESM-powered frontend build tool. Instant, lightweight, unbundled development. ![](https://img.shields.io/github/stars/snowpackjs/snowpack.svg?style=social&label=Star)

### Templating

- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml. ![](https://img.shields.io/github/stars/pugjs/pug.svg?style=social&label=Star)
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks. ![](https://img.shields.io/github/stars/wycats/handlebars.js.svg?style=social&label=Star)
- [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript. ![](https://img.shields.io/github/stars/janl/mustache.js.svg?style=social&label=Star)
- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags. ![](https://img.shields.io/github/stars/marko-js/marko.svg?style=social&label=Star)
- [art-template](https://github.com/aui/art-template) - High performance JavaScript templating engine. ![](https://img.shields.io/github/stars/aui/art-template.svg?style=social&label=Star)
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired). ![](https://img.shields.io/github/stars/mozilla/nunjucks.svg?style=social&label=Star)
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language. ![](https://img.shields.io/github/stars/mde/ejs.svg?style=social&label=Star)
- [hogan.js](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language. ![](https://img.shields.io/github/stars/twitter/hogan.js.svg?style=social&label=Star)
- [doT](https://github.com/olado/doT) - Fastest + concise javascript template engine for nodejs and browsers. Partials, custom delimiters and more. ![](https://img.shields.io/github/stars/olado/doT.svg?style=social&label=Star)
- [jsrender](https://github.com/BorisMoore/jsrender) - A lightweight, powerful and highly extensible templating engine. In the browser or on Node.js, with or without jQuery. ![](https://img.shields.io/github/stars/BorisMoore/jsrender.svg?style=social&label=Star)
- [Twig.js](https://github.com/twigjs/twig.js) - JS implementation of the Twig Templating Language. ![](https://img.shields.io/github/stars/twigjs/twig.js.svg?style=social&label=Star)
- [hbs](https://github.com/pillarjs/hbs) - Express view engine wrapper for Handlebars. ![](https://img.shields.io/github/stars/pillarjs/hbs.svg?style=social&label=Star)
- [Juicer](https://github.com/PaulGuo/Juicer) - A Lightweight JavaScript Template Engine. ![](https://img.shields.io/github/stars/PaulGuo/Juicer.svg?style=social&label=Star)
- [tempo](https://github.com/twigkit/tempo) - Tempo is an easy, intuitive JavaScript rendering engine that enables you to craft data templates in pure HTML. ![](https://img.shields.io/github/stars/twigkit/tempo.svg?style=social&label=Star)
- [xtemplate](https://github.com/xtemplate/xtemplate) - High Speed, eXtensible Template Engine lib on browser and nodejs. support async control, inheritance, include, logic expression, custom function and more. ![](https://img.shields.io/github/stars/xtemplate/xtemplate.svg?style=social&label=Star)

### Web Frameworks

- [Express](https://github.com/expressjs/express) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications. ![](https://img.shields.io/github/stars/expressjs/express.svg?style=social&label=Star)
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps. ![](https://img.shields.io/github/stars/zeit/next.js.svg?style=social&label=Star)
  - [blitz](https://github.com/blitz-js/blitz) - ⚡️The Fullstack React Framework — built on Next.js. ![](https://img.shields.io/github/stars/blitz-js/blitz.svg?style=social&label=Star)
- [Meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))* ![](https://img.shields.io/github/stars/meteor/meteor.svg?style=social&label=Star)
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps. ![](https://img.shields.io/github/stars/nuxt/nuxt.js.svg?style=social&label=Star)
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps. *(You might like [awesome-nestjs](https://github.com/juliandavidmr/awesome-nestjs))* ![](https://img.shields.io/github/stars/nestjs/nest.svg?style=social&label=Star)
- [Koa](https://github.com/koajs/koa) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs. ![](https://img.shields.io/github/stars/koajs/koa.svg?style=social&label=Star)
  - *(You might like [awesome-koa](https://github.com/huaize2020/awesome-koa/blob/main/README-en.md))*
- [sails](https://github.com/balderdashy/sails) - Realtime MVC Framework for Node.js. ![](https://img.shields.io/github/stars/balderdashy/sails.svg?style=social&label=Star)
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework. ![](https://img.shields.io/github/stars/fastify/fastify.svg?style=social&label=Star)
- [Hapi](https://github.com/hapijs/hapi) - Framework for building applications and services. ![](https://img.shields.io/github/stars/hapijs/hapi.svg?style=social&label=Star)
- [Egg](https://github.com/eggjs/egg) - Born to build better enterprise frameworks and apps with Node.js & Koa. ![](https://img.shields.io/github/stars/eggjs/egg.svg?style=social&label=Star)
  - *(You might like [awesome-egg](https://github.com/huaize2020/awesome-egg))*
- [Feathers](https://github.com/feathersjs/feathers) - Microservice framework built in the spirit of Express. ![](https://img.shields.io/github/stars/feathersjs/feathers.svg?style=social&label=Star)
- [AdonisJs](https://github.com/adonisjs/core) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container. ![](https://img.shields.io/github/stars/adonisjs/core.svg?style=social&label=Star)
- [LoopBack](https://github.com/strongloop/loopback-next) - Powerful framework for creating REST APIs and easily connecting to backend data sources. v4 - ![](https://img.shields.io/github/stars/strongloop/loopback-next.svg?style=social&label=Star) v3 - ![](https://img.shields.io/github/stars/strongloop/loopback.svg?style=social&label=Star)
- [Restify](https://github.com/restify/node-restify) - Enables you to build correct REST web services. ![](https://img.shields.io/github/stars/restify/node-restify.svg?style=social&label=Star)
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API. ![](https://img.shields.io/github/stars/thinkjs/thinkjs.svg?style=social&label=Star)
- [total.js](https://github.com/totaljs/framework) - A framework for Node.js platfrom written in pure JavaScript similar to PHP's Laravel or Python's Django or ASP.NET MVC ![](https://img.shields.io/github/stars/totaljs/framework.svg?style=social&label=Star)
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach. ![](https://img.shields.io/github/stars/zeit/micro.svg?style=social&label=Star)
- [Midway](https://github.com/midwayjs/midway) - A Node.js framework for building Serverless services, traditional server-side applications, microservices, and small programs. ![](https://img.shields.io/github/stars/midwayjs/midway.svg?style=social&label=Star)
- [Moleculer](https://github.com/moleculerjs/moleculer) - Fast & powerful microservices framework. ![](https://img.shields.io/github/stars/moleculerjs/moleculer.svg?style=social&label=Star)
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices. ![](https://img.shields.io/github/stars/senecajs/seneca.svg?style=social&label=Star)
- [server](https://github.com/franciscop/server) - Simple and powerful server for Node.js. ![](https://img.shields.io/github/stars/franciscop/server.svg?style=social&label=Star)
- [beidou](https://github.com/alibaba/beidou) - Isomorphic framework for server-rendered React apps. ![](https://img.shields.io/github/stars/alibaba/beidou.svg?style=social&label=Star)
- [Marble.js](https://github.com/marblejs/marble) - Functional reactive framework for building server-side apps, based on TypeScript and RxJS. ![](https://img.shields.io/github/stars/marblejs/marble.svg?style=social&label=Star)
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients. ![](https://img.shields.io/github/stars/actionhero/actionhero.svg?style=social&label=Star)
- [lad](https://github.com/ladjs/lad) - The best Node.js framework. Made by a former Express TC and Koa team member. ![](https://img.shields.io/github/stars/ladjs/lad.svg?style=social&label=Star)
- [Tinyhttp](https://github.com/talentlessguy/tinyhttp) - Modern and fast Express-like web framework. ![](https://img.shields.io/github/stars/talentlessguy/tinyhttp.svg?style=social&label=Star)
- [daruk](https://github.com/darukjs/daruk) - A node.js web framework based on typescript. ![](https://img.shields.io/github/stars/darukjs/daruk.svg?style=social&label=Star)
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io). ![](https://img.shields.io/github/stars/hemerajs/hemera.svg?style=social&label=Star)
- [diet](https://github.com/adamhalasz/diet) - A tiny, fast and modular node.js web framework. Good for making fast & scalable apps and apis. ![](https://img.shields.io/github/stars/adamhalasz/diet.svg?style=social&label=Star)
- [restana](https://github.com/BackendStack21/restana) - Super fast and minimalist framework for building REST micro-services. ![](https://img.shields.io/github/stars/BackendStack21/restana.svg?style=social&label=Star)
- [CabloyJS](https://github.com/zhennann/Cabloy) - A Node.js full-stack framework with workflow engine, based on koa + egg + vue + framework7. ![](https://img.shields.io/github/stars/zhennann/Cabloy.svg?style=social&label=Star)
- [malagu](https://github.com/cellbang/malagu) - Malagu is a serverless First, scalable and componentized application framework developed by TypeScript. ![](https://img.shields.io/github/stars/cellbang/malagu.svg?style=social&label=Star)
- [Zeronode](https://github.com/sfast/zeronode) - Minimal building block for reliable and fault-tolerant microservices. ![](https://img.shields.io/github/stars/sfast/zeronode.svg?style=social&label=Star)

### GraphQL

- *(You might like [awesome-graphql](https://github.com/chentsulin/awesome-graphql#javascript-libraries))*

### Content management systems (CMS)

- [Ghost](https://github.com/TryGhost/Ghost) - The headless Node.js CMS for professional publishing. ![](https://img.shields.io/github/stars/TryGhost/Ghost.svg?style=social&label=Star)
- [Strapi](https://github.com/strapi/strapi) - Content Management Framework (headless-CMS) to build powerful APIs. ![](https://img.shields.io/github/stars/strapi/strapi.svg?style=social&label=Star)
- [KeystoneJS](https://github.com/keystonejs/keystone) - CMS and web application platform built on Express and MongoDB. ![](https://img.shields.io/github/stars/keystonejs/keystone.svg?style=social&label=Star)
- [AdminBro](https://github.com/SoftwareBrothers/admin-bro) - Auto-generated admin panel with CRUD for all your resources. ![](https://img.shields.io/github/stars/SoftwareBrothers/admin-bro.svg?style=social&label=Star)
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB. ![](https://img.shields.io/github/stars/apostrophecms/apostrophe.svg?style=social&label=Star)
- [Tipe](https://github.com/tipeio/tipe) - Next Generation API-first CMS for developers. Generate an API-first CMS from a GraphQL schema with offline prototyping and an inline editor. ![](https://img.shields.io/github/stars/tipeio/tipe.svg?style=social&label=Star)
- [Factor](https://github.com/fiction-com/factor) - Vue.js dashboard framework and headless CMS. ![](https://img.shields.io/github/stars/fiction-com/factor.svg?style=social&label=Star)

### Static Site Generator & Blogging

- [gatsby](https://github.com/gatsbyjs/gatsby) - Build blazing fast, modern apps and websites with React. ![](https://img.shields.io/github/stars/gatsbyjs/gatsby.svg?style=social&label=Star)
- [hexo](https://github.com/hexojs/hexo) - A fast, simple & powerful blog framework, powered by Node.js. ![](https://img.shields.io/github/stars/hexojs/hexo.svg?style=social&label=Star)
- [vuepress](https://github.com/vuejs/vuepress) - Minimalistic Vue-powered static site generator. ![](https://img.shields.io/github/stars/vuejs/vuepress.svg?style=social&label=Star)
- [netlify-cms](https://github.com/netlify/netlify-cms) - A Git-based CMS for Static Site Generators. ![](https://img.shields.io/github/stars/netlify/netlify-cms.svg?style=social&label=Star)
- [react-static](https://github.com/react-static/react-static) - A progressive static site generator for React. ![](https://img.shields.io/github/stars/react-static/react-static.svg?style=social&label=Star)
- [gridsome](https://github.com/gridsome/gridsome) - The Jamstack framework for Vue.js. ![](https://img.shields.io/github/stars/gridsome/gridsome.svg?style=social&label=Star)
- [vitepress](https://github.com/vuejs/vitepress) - Vite & Vue powered static site generator. ![](https://img.shields.io/github/stars/vuejs/vitepress.svg?style=social&label=Star)
- [scully](https://github.com/scullyio/scully) - The Static Site Generator for Angular apps. ![](https://img.shields.io/github/stars/scullyio/scully.svg?style=social&label=Star)

### Documentation

- [Docusaurus](https://github.com/facebook/docusaurus) - Documentation website generator that leverages React and Markdown, and comes with translation and versioning features. ![](https://img.shields.io/github/stars/facebook/docusaurus.svg?style=social&label=Star)
- [docsify](https://github.com/docsifyjs/docsify) - 🃏 A magical documentation site generator. ![](https://img.shields.io/github/stars/docsifyjs/docsify.svg?style=social&label=Star)
- [JSDoc](https://github.com/jsdoc3/jsdoc) - API documentation generator similar to JavaDoc or PHPDoc. ![](https://img.shields.io/github/stars/jsdoc3/jsdoc.svg?style=social&label=Star)
- [documentation.js](https://github.com/documentationjs/documentation) - API documentation generator with support for ES2015+ and flow annotation. ![](https://img.shields.io/github/stars/documentationjs/documentation.svg?style=social&label=Star)
- [Docco](https://github.com/jashkenas/docco) - Documentation generator which produces an HTML document that displays your comments intermingled with your code. ![](https://img.shields.io/github/stars/jashkenas/docco.svg?style=social&label=Star)
- [docute](https://github.com/egoist/docute) - Effortless documentation, done right. ![](https://img.shields.io/github/stars/egoist/docute.svg?style=social&label=Star)
- [ESDoc](https://github.com/esdoc/esdoc) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage. ![](https://img.shields.io/github/stars/esdoc/esdoc.svg?style=social&label=Star)
- [groc](https://github.com/nevir/groc) - Documentation generation, in the spirit of literate programming. ![](https://img.shields.io/github/stars/nevir/groc.svg?style=social&label=Star)

### API Management

- [yapi](https://github.com/YMFE/yapi) - YApi is a visual interface management platform that can be deployed locally, open up front and back ends, and QA. ![](https://img.shields.io/github/stars/YMFE/yapi.svg?style=social&label=Star)
- [swagger](https://github.com/swagger-api/swagger-node) - Swagger module for node.js。Swagger UI is a collection of HTML, JavaScript, and CSS assets that dynamically generate beautiful documentation from a Swagger-compliant API. ![](https://img.shields.io/github/stars/swagger-api/swagger-node.svg?style=social&label=Star)
- [rap2](https://github.com/thx/rap2-delos) - The second generation of RAP, an open source interface management tool produced by Alimama's front-end team. ![](https://img.shields.io/github/stars/thx/rap2-delos.svg?style=social&label=Star)

### Desktop Apps

- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))* ![](https://img.shields.io/github/stars/atom/electron.svg?style=social&label=Star)
- [nw.js](https://github.com/nwjs/nw.js) - Call all Node.js modules directly from DOM/WebWorker and enable a new way of writing applications with all Web technologies. ![](https://img.shields.io/github/stars/nwjs/nw.js.svg?style=social&label=Star)

### Real-time

- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication. ![](https://img.shields.io/github/stars/socketio/socket.io.svg?style=social&label=Star)
- [ws](https://github.com/websockets/ws) - Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js. ![](https://img.shields.io/github/stars/websockets/ws.svg?style=social&label=Star)
- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library. ![](https://img.shields.io/github/stars/uWebSockets/uWebSockets.svg?style=social&label=Star)
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP. ![](https://img.shields.io/github/stars/mqttjs/MQTT.js.svg?style=social&label=Star)
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores. ![](https://img.shields.io/github/stars/SocketCluster/socketcluster.svg?style=social&label=Star)
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol. ![](https://img.shields.io/github/stars/faye/faye.svg?style=social&label=Star)
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in. ![](https://img.shields.io/github/stars/primus/primus.svg?style=social&label=Star)
- [engine.io](https://github.com/socketio/engine.io) - The implementation of transport-based cross-browser/cross-device bi-directional communication layer for Socket.IO. ![](https://img.shields.io/github/stars/socketio/engine.io.svg?style=social&label=Star)
- [SockJS-node](https://github.com/sockjs/sockjs-node) - WebSocket emulation - Node.js server. ![](https://img.shields.io/github/stars/sockjs/sockjs-node.svg?style=social&label=Star)
- [Aedes](https://github.com/mcollina/aedes) - Barebone MQTT server that can run on any stream server. ![](https://img.shields.io/github/stars/mcollina/aedes.svg?style=social&label=Star)
- [nodejs-websocket](https://github.com/sitegui/nodejs-websocket) - A node.js module for websocket server and client. ![](https://img.shields.io/github/stars/sitegui/nodejs-websocket.svg?style=social&label=Star)
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets. ![](https://img.shields.io/github/stars/elpheria/rpc-websockets.svg?style=social&label=Star)
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - Scalable real-time microservice framework. ![](https://img.shields.io/github/stars/deepstreamIO/deepstream.io-client-js.svg?style=social&label=Star)
- [isomorphic-ws](https://github.com/heineiuo/isomorphic-ws) - Isomorphic implementation of WebSocket. ![](https://img.shields.io/github/stars/heineiuo/isomorphic-ws.svg?style=social&label=Star)
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework. ![](https://img.shields.io/github/stars/kalm/kalm.js.svg?style=social&label=Star)

### Job Queues

- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue. ![](https://img.shields.io/github/stars/OptimalBits/bull.svg?style=social&label=Star)
- [amqp](https://github.com/squaremo/amqp.node)- AMQP 0-9-1 library and client for Node.JS. ![](https://img.shields.io/github/stars/squaremo/amqp.node.svg?style=social&label=Star)
- [kafka-node](https://github.com/SOHU-Co/kafka-node)- Node.js client for Apache Kafka 0.8 and later. ![](https://img.shields.io/github/stars/SOHU-Co/kafka-node.svg?style=social&label=Star)
- [bee-queue](https://github.com/bee-queue/bee-queue) - High-performance Redis-backed job queue. ![](https://img.shields.io/github/stars/bee-queue/bee-queue.svg?style=social&label=Star)
  - [arena](https://github.com/bee-queue/arena) - An interactive UI dashboard for Bee Queue. ![](https://img.shields.io/github/stars/bee-queue/arena.svg?style=social&label=Star)
- [kafkajs](https://github.com/tulios/kafkajs) - A modern Apache Kafka client for node.js. ![](https://img.shields.io/github/stars/tulios/kafkajs.svg?style=social&label=Star)
- [bullmq](https://github.com/taskforcesh/bullmq) - BullMQ - Premium Message Queue for NodeJS based on Redis. ![](https://img.shields.io/github/stars/taskforcesh/bullmq.svg?style=social&label=Star)
- [rsmq](https://github.com/smrchy/rsmq) - Redis-backed message queue. ![](https://img.shields.io/github/stars/smrchy/rsmq.svg?style=social&label=Star)
- [sqs-consumer](https://github.com/bbc/sqs-consumer) - Build Amazon Simple Queue Service (SQS) based apps without the boilerplate. ![](https://img.shields.io/github/stars/bbc/sqs-consumer.svg?style=social&label=Star)
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue. ![](https://img.shields.io/github/stars/taskrabbit/node-resque.svg?style=social&label=Star)
- [better-queue](https://github.com/diamondio/better-queue) - Simple and efficient job queue when you cannot use Redis. ![](https://img.shields.io/github/stars/diamondio/better-queue.svg?style=social&label=Star)
- [RedisSMQ](https://github.com/weyoss/redis-smq) - Simple high-performance Redis message queue with real-time monitoring. ![](https://img.shields.io/github/stars/weyoss/redis-smq.svg?style=social&label=Star)
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control. ![](https://img.shields.io/github/stars/nodeca/idoit.svg?style=social&label=Star)

### Job Scheduling

- [node-schedule](https://github.com/node-schedule/node-schedule) - A cron-like and not-cron-like job scheduler for Node. ![](https://img.shields.io/github/stars/node-schedule/node-schedule.svg?style=social&label=Star)
- [agenda](https://github.com/agenda/agenda) - Lightweight job scheduling for Node.js. ![](https://img.shields.io/github/stars/agenda/agenda.svg?style=social&label=Star)
- [node-cron](https://github.com/kelektiv/node-cron) - A tool that allows you to execute something on a schedule. ![](https://img.shields.io/github/stars/kelektiv/node-cron.svg?style=social&label=Star)
- [cron-parser](https://github.com/harrisiirak/cron-parser) - Node.js library for parsing crontab instructions. ![](https://img.shields.io/github/stars/harrisiirak/cron-parser.svg?style=social&label=Star)

### Debugging

- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. ![](https://img.shields.io/github/stars/node-inspector/node-inspector.svg?style=social&label=Star)
- [ndb](https://github.com/GoogleChromeLabs/ndb) - Improved debugging experience, enabled by Chrome DevTools. ![](https://img.shields.io/github/stars/GoogleChromeLabs/ndb.svg?style=social&label=Star)
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. ![](https://img.shields.io/github/stars/visionmedia/debug.svg?style=social&label=Star)
- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. ![](https://img.shields.io/github/stars/s-a/iron-node.svg?style=social&label=Star)
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? ![](https://img.shields.io/github/stars/mafintosh/why-is-node-running.svg?style=social&label=Star)
- [llnode](https://github.com/nodejs/llnode) - Post-mortem analysis tool which allows you to inspect objects and get insights from a crashed Node.js process. ![](https://img.shields.io/github/stars/nodejs/llnode.svg?style=social&label=Star)
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. ![](https://img.shields.io/github/stars/valyouw/njstrace.svg?style=social&label=Star)
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. ![](https://img.shields.io/github/stars/alidavut/locus.svg?style=social&label=Star)
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. ![](https://img.shields.io/github/stars/watson/stackman.svg?style=social&label=Star)
- [NiM](https://github.com/june07/nim) - Manages DevTools debugging workflow. ![](https://img.shields.io/github/stars/june07/nim.svg?style=social&label=Star)
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. ![](https://img.shields.io/github/stars/automation-stack/ctrace.svg?style=social&label=Star)
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. ![](https://img.shields.io/github/stars/joyent/node-vstream.svg?style=social&label=Star)

### Profiling/Analysis

- [Clinic.js](https://github.com/clinicjs/node-clinic) - Clinic.js diagnoses your Node.js performance issues. ![](https://img.shields.io/github/stars/clinicjs/node-clinic.svg?style=social&label=Star)
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. ![](https://img.shields.io/github/stars/davidmarkclements/0x.svg?style=social&label=Star)
- [node-heapdump](https://github.com/bnoordhuis/node-heapdump) - Make a dump of the V8 heap for later inspection. ![](https://img.shields.io/github/stars/bnoordhuis/node-heapdump.svg?style=social&label=Star)
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. ![](https://img.shields.io/github/stars/andywer/leakage.svg?style=social&label=Star)
- [v8-profiler](https://github.com/node-inspector/v8-profiler) - Node bindings for the v8 profiler. ![](https://img.shields.io/github/stars/node-inspector/v8-profiler.svg?style=social&label=Star)
- [node-memwatch](https://github.com/marcominetti/node-memwatch) - A NodeJS library to keep an eye on your memory usage, and discover and isolate leaks. ![](https://img.shields.io/github/stars/marcominetti/node-memwatch.svg?style=social&label=Star)
- [v8-analytics](https://github.com/hyj1991/v8-analytics) - V8 engine's cpu & heap-memory analytics. ![](https://img.shields.io/github/stars/hyj1991/v8-analytics.svg?style=social&label=Star)
- [thetool](https://github.com/sfninja/thetool) - Capture different CPU, memory, and other profiles for your app in Chrome DevTools friendly format. ![](https://img.shields.io/github/stars/sfninja/thetool.svg?style=social&label=Star)
- [flamegraph](https://github.com/thlorenz/flamegraph) - Generates flamegraphs with Node.js or in the browser. ![](https://img.shields.io/github/stars/thlorenz/flamegraph.svg?style=social&label=Star)
- [v8-profiler-next](https://github.com/hyj1991/v8-profiler-next) - Node bindings for the v8 profiler. ![](https://img.shields.io/github/stars/hyj1991/v8-profiler-next.svg?style=social&label=Star)
- [cpu-memory-monitor](https://github.com/nswbmw/cpu-memory-monitor) - CPU & Memory Monitor, auto dump. ![](https://img.shields.io/github/stars/nswbmw/cpu-memory-monitor.svg?style=social&label=Star)

### Performance Optimization

- [v8-compile-cache](https://github.com/zertosh/v8-compile-cache) - Require hook for automatic V8 compile cache persistence ![](https://img.shields.io/github/stars/zertosh/v8-compile-cache.svg?style=social&label=Star)

### Application Performance Monitoring (APM)

- Solution
  - [easy-monitor](https://github.com/hyj1991/easy-monitor) - Enterprise-level Node.js application performance monitoring and online fault location solutions. ![](https://img.shields.io/github/stars/hyj1991/easy-monitor.svg?style=social&label=Star)
  - [webfunny_monitor](https://github.com/a597873885/webfunny_monitor) - Webfunny is a lightweight front-end monitoring system and webfunny is also a front-end performance monitoring system. It monitors front-end logs and analyzes front-end health status in real time. ![](https://img.shields.io/github/stars/a597873885/webfunny_monitor.svg?style=social&label=Star)

- Middleware
  - [swagger-stats](https://github.com/slanatech/swagger-stats) - Trace API calls and monitor API performance, health, and usage metrics. ![](https://img.shields.io/github/stars/slanatech/swagger-stats.svg?style=social&label=Star)

- Agent
  - [prom-client](https://github.com/siimon/prom-client) - Prometheus client for node.js. ![](https://img.shields.io/github/stars/siimon/prom-client.svg?style=social&label=Star)
  - [apm-agent-nodejs](https://github.com/elastic/apm-agent-nodejs) - Elastic APM Node.js Agent. ![](https://img.shields.io/github/stars/elastic/apm-agent-nodejs.svg?style=social&label=Star)
  - [skywalking-nodejs](https://github.com/apache/skywalking-nodejs) - The NodeJS agent for Apache SkyWalking. ![](https://img.shields.io/github/stars/apache/skywalking-nodejs.svg?style=social&label=Star)

### Forum

- [NodeBB](https://github.com/NodeBB/NodeBB) - Node.js based forum software built for the modern web ![](https://img.shields.io/github/stars/NodeBB/NodeBB.svg?style=social&label=Star)
- [nodeclub](https://github.com/cnodejs/nodeclub/) - A forum software based on Node.js and MongoDB. ![](https://img.shields.io/github/stars/cnodejs/nodeclub.svg?style=social&label=Star)

### Database

- Drivers
  - [MySQL](https://github.com/mysqljs/mysql) - A pure node.js JavaScript Client implementing the MySQL protocol. ![](https://img.shields.io/github/stars/mysqljs/mysql.svg?style=social&label=Star)
  - [redis](https://github.com/NodeRedis/node-redis) - A high performance Node.js Redis client. ![](https://img.shields.io/github/stars/NodeRedis/node-redis.svg?style=social&label=Star)
  - [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client for node.js. ![](https://img.shields.io/github/stars/brianc/node-postgres.svg?style=social&label=Star)
  - [MongoDB](https://github.com/mongodb/node-mongodb-native) - The Official MongoDB Node.js Driver. ![](https://img.shields.io/github/stars/mongodb/node-mongodb-native.svg?style=social&label=Star)
  - [ioredis](https://github.com/luin/ioredis) - A robust, performance-focused and full-featured Redis client for Node.js. ![](https://img.shields.io/github/stars/luin/ioredis.svg?style=social&label=Star)
  - [LevelUP](https://github.com/Level/levelup) - A wrapper for abstract-leveldown compliant stores, for Node.js and browsers. ![](https://img.shields.io/github/stars/Level/levelup.svg?style=social&label=Star)
  - [mysql2](https://github.com/sidorares/node-mysql2) - ⚡ Fast mysqljs/mysql compatible mysql driver for node.js. ![](https://img.shields.io/github/stars/sidorares/node-mysql2.svg?style=social&label=Star)
  - [rethinkdbdash](https://github.com/neumino/rethinkdbdash) - An advanced Node.js driver for RethinkDB with a connection pool, support for streams etc. ![](https://img.shields.io/github/stars/neumino/rethinkdbdash.svg?style=social&label=Star)
  - [couchdb-nano](https://github.com/apache/couchdb-nano) - Nano: The official Apache CouchDB library for Node.js. ![](https://img.shields.io/github/stars/apache/couchdb-nano.svg?style=social&label=Star)
  - [Couchbase](https://github.com/couchbase/couchnode) - Couchbase Node.js Client Library (Official). ![](https://img.shields.io/github/stars/couchbase/couchnode.svg?style=social&label=Star)
  - [mariadb](https://github.com/mariadb-corporation/mariadb-connector-nodejs) - MariaDB Connector/Node.js is used to connect applications developed on Node.js to MariaDB and MySQL databases. ![](https://img.shields.io/github/stars/mariadb-corporation/mariadb-connector-nodejs.svg?style=social&label=Star)
  - [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Node.js client for the Aerospike database. ![](https://img.shields.io/github/stars/aerospike/aerospike-client-nodejs.svg?style=social&label=Star)

- ODM / ORM
  - [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL, and more. ![](https://img.shields.io/github/stars/sequelize/sequelize.svg?style=social&label=Star)
    - [sequelize-typescript](https://github.com/RobinBuschmann/sequelize-typescript) - Decorators and some other features for sequelize. ![](https://img.shields.io/github/stars/RobinBuschmann/sequelize-typescript.svg?style=social&label=Star)
  - [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more. ![](https://img.shields.io/github/stars/typeorm/typeorm.svg?style=social&label=Star)
  - [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling. ![](https://img.shields.io/github/stars/Automattic/mongoose.svg?style=social&label=Star)
    - [typegoose](https://github.com/typegoose/typegoose) - Typegoose - Define Mongoose models using TypeScript classes. ![](https://img.shields.io/github/stars/typegoose/typegoose.svg?style=social&label=Star)
  - [Prisma](https://github.com/prisma/prisma) - Modern database access (ORM alternative). Auto-generated and type-safe query builder in TypeScript. Supports PostgreSQL, MySQL & SQLite. ![](https://img.shields.io/github/stars/prisma/prisma.svg?style=social&label=Star)
  - [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js. ![](https://img.shields.io/github/stars/bookshelf/bookshelf.svg?style=social&label=Star)
  - [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex. ![](https://img.shields.io/github/stars/Vincit/objection.js.svg?style=social&label=Star)
  - [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases. ![](https://img.shields.io/github/stars/balderdashy/waterline.svg?style=social&label=Star)
  - [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises. ![](https://img.shields.io/github/stars/vitaly-t/pg-promise.svg?style=social&label=Star)
  - [MikroORM](https://github.com/mikro-orm/mikro-orm) - TypeScript ORM based on Data Mapper, Unit of Work and Identity Map patterns. Supports MongoDB, PostgreSQL, MySQL and SQLite. ![](https://img.shields.io/github/stars/mikro-orm/mikro-orm.svg?style=social&label=Star)
  - [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool. ![](https://img.shields.io/github/stars/robconery/massive-js.svg?style=social&label=Star)
  - [slonik](https://github.com/gajus/slonik) - PostgreSQL client with strict types, detailed logging and assertions. ![](https://img.shields.io/github/stars/gajus/slonik.svg?style=social&label=Star)
  - [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord. ![](https://img.shields.io/github/stars/PhilWaldmann/openrecord.svg?style=social&label=Star)
  - [leoric](https://github.com/cyjake/leoric) - JavaScript ORM for MySQL, PostgreSQL, and SQLite. ![](https://img.shields.io/github/stars/cyjake/leoric.svg?style=social&label=Star)

- Query builder
  - [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use. ![](https://img.shields.io/github/stars/tgriesser/knex.svg?style=social&label=Star)

- SQL
  - [sqlstring](https://github.com/mysqljs/sqlstring) - Simple SQL escape and format for MySQL. ![](https://img.shields.io/github/stars/mysqljs/sqlstring.svg?style=social&label=Star)

- Other
  - [Lowdb](https://github.com/typicode/lowdb) - Tiny local JSON database for small projects (supports Node, Electron and the browser). ![](https://img.shields.io/github/stars/typicode/lowdb.svg?style=social&label=Star)
  - [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent or in memory database for Node.js, nw.js, Electron and browsers. ![](https://img.shields.io/github/stars/louischatriot/nedb.svg?style=social&label=Star)
  - [Keyv](https://github.com/lukechilds/keyv) - Simple key-value storage with support for multiple backends. ![](https://img.shields.io/github/stars/lukechilds/keyv.svg?style=social&label=Star)
  - [pg-mem](https://github.com/oguimbal/pg-mem) - In-memory PostgreSQL instance. ![](https://img.shields.io/github/stars/oguimbal/pg-mem.svg?style=social&label=Star)
  - [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - Populate MongoDB databases with JavaScript and JSON files. ![](https://img.shields.io/github/stars/pkosiec/mongo-seeding.svg?style=social&label=Star)
  - [@databases](https://github.com/ForbesLindesay/atdatabases) - Query PostgreSQL, MySQL and SQLite3 with plain SQL without risking SQL injection. ![](https://img.shields.io/github/stars/ForbesLindesay/atdatabases.svg?style=social&label=Star)
  - [Finale](https://github.com/tommybananas/finale) - RESTful endpoint generator for your Sequelize models. ![](https://img.shields.io/github/stars/tommybananas/finale.svg?style=social&label=Star)
  - [database-js](https://github.com/mlaanderson/database-js) - Wrapper for multiple databases with a JDBC-like connection. ![](https://img.shields.io/github/stars/mlaanderson/database-js.svg?style=social&label=Star)

### Cache

- [lru-cache](https://github.com/isaacs/node-lru-cache) - A cache object that deletes the least-recently-used items. ![](https://img.shields.io/github/stars/isaacs/node-lru-cache.svg?style=social&label=Star)
- [node-cache](https://github.com/node-cache/node-cache) - A node internal (in-memory) caching module. ![](https://img.shields.io/github/stars/node-cache/node-cache.svg?style=social&label=Star)
- [memcached](https://github.com/3rd-Eden/memcached) - A fully featured Memcached client build on top of Node.js. Build with scaling in mind so it will support Memcached clusters and consistent hashing. ![](https://img.shields.io/github/stars/3rd-Eden/memcached.svg?style=social&label=Star)
- [node-cache-manager](https://github.com/BryanDonovan/node-cache-manager) - Cache module for Node.JS. ![](https://img.shields.io/github/stars/BryanDonovan/node-cache-manager.svg?style=social&label=Star)
- [quick-lru](https://github.com/sindresorhus/quick-lru) - Simple “Least Recently Used” (LRU) cache. ![](https://img.shields.io/github/stars/sindresorhus/quick-lru.svg?style=social&label=Star)
- [hashlru](https://github.com/dominictarr/hashlru) - Simpler, faster LRU cache algorithm. ![](https://img.shields.io/github/stars/dominictarr/hashlru.svg?style=social&label=Star)
- [flat-cache](https://github.com/royriojas/flat-cache) - A stupidly simple key/value storage using files to persist the data. ![](https://img.shields.io/github/stars/royriojas/flat-cache.svg?style=social&label=Star)
- [ylru](https://github.com/node-modules/ylru) - Add "expire", "allow set empty value" extends on hashlru. ![](https://img.shields.io/github/stars/node-modules/ylru.svg?style=social&label=Star)

### Search Engine

- [elasticsearch-js](https://github.com/elastic/elasticsearch-js) - Official Elasticsearch client library for Node.js. ![](https://img.shields.io/github/stars/elastic/elasticsearch-js.svg?style=social&label=Star)
- [elasticsearch-js-legacy](https://github.com/elastic/elasticsearch-js-legacy) - Legacy Elasticsearch client library for Node.js and the browser. ![](https://img.shields.io/github/stars/elastic/elasticsearch-js-legacy.svg?style=social&label=Star)

### Serverless

- [serverless](https://github.com/serverless/serverless) - Serverless Framework – Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more! ![](https://img.shields.io/github/stars/serverless/serverless.svg?style=social&label=Star)
- [@midway/faas](https://github.com/midwayjs/midway/tree/2.x/packages/faas) - Midway FaaS is the Serverless framework used to build Node.js cloud functions. ![](https://img.shields.io/github/stars/midwayjs/midway.svg?style=social&label=Star)
- [malagu](https://github.com/cellbang/malagu) - Malagu is a Serverless First, componentized, platform-independent progressive application framework based on TypeScript. ![](https://img.shields.io/github/stars/cellbang/malagu.svg?style=social&label=Star)

### Automation & RPA

- [puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome Node.js API. ![](https://img.shields.io/github/stars/puppeteer/puppeteer.svg?style=social&label=Star)
- [playwright](https://github.com/microsoft/playwright) - Automate Chromium, Firefox and WebKit with a single API. ![](https://img.shields.io/github/stars/microsoft/playwright.svg?style=social&label=Star)
- [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless Browser. ![](https://img.shields.io/github/stars/ariya/phantomjs.svg?style=social&label=Star)
- [appium](https://github.com/appium/appium) - Automation for iOS, Android, and Windows Apps. ![](https://img.shields.io/github/stars/appium/appium.svg?style=social&label=Star)
- [wechaty](https://github.com/wechaty/wechaty) - Conversational RPA SDK. ![](https://img.shields.io/github/stars/wechaty/wechaty.svg?style=social&label=Star)
- [robotjs](https://github.com/octalmage/robotjs) - Node.js Desktop Automation. ![](https://img.shields.io/github/stars/octalmage/robotjs.svg?style=social&label=Star)
- [nut.js](https://github.com/nut-tree/nut.js) - Native UI testing / controlling with node. ![](https://img.shields.io/github/stars/nut-tree/nut.js.svg?style=social&label=Star)

### Testing

- Assertion
  - [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework. ![](https://img.shields.io/github/stars/chaijs/chai.svg?style=social&label=Star)
  - [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface. ![](https://img.shields.io/github/stars/power-assert-js/power-assert.svg?style=social&label=Star)
  - [expect.js](https://github.com/Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser. ![](https://img.shields.io/github/stars/Automattic/expect.js.svg?style=social&label=Star)
  - [should.js](https://github.com/shouldjs/should.js) - BDD style assertions for node.js. ![](https://img.shields.io/github/stars/shouldjs/should.js.svg?style=social&label=Star)
  - [unexpected](https://github.com/unexpectedjs/unexpected) - Unexpected - the extensible BDD assertion toolkit. ![](https://img.shields.io/github/stars/unexpectedjs/unexpected.svg?style=social&label=Star)
  - [better-assert](https://github.com/tj/better-assert) - C-style assert() for nodejs, reporting the expression string as the error message. ![](https://img.shields.io/github/stars/tj/better-assert.svg?style=social&label=Star)
  - [http-assert](https://github.com/jshttp/http-assert) - Assert with status codes. ![](https://img.shields.io/github/stars/jshttp/http-assert.svg?style=social&label=Star)

- Faker Generator
  - [faker.js](https://github.com/marak/Faker.js/) - Generate massive amounts of realistic fake data in Node.js and the browser. ![](https://img.shields.io/github/stars/marak/Faker.js.svg?style=social&label=Star)
  - [casual](https://github.com/boo1ean/casual) - Fake data generator for javascript. ![](https://img.shields.io/github/stars/boo1ean/casual.svg?style=social&label=Star)
  - [fony](https://github.com/captainsafia/fony) - A simple command line tool for generating fake data from a template string. ![](https://img.shields.io/github/stars/captainsafia/fony.svg?style=social&label=Star)

- Mock
  - [Mock.js](https://github.com/nuysoft/Mock) - A simulation data generator. ![](https://img.shields.io/github/stars/nuysoft/Mock.svg?style=social&label=Star)
  - [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations. ![](https://img.shields.io/github/stars/pgte/nock.svg?style=social&label=Star)
  - [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks. ![](https://img.shields.io/github/stars/sinonjs/sinon.svg?style=social&label=Star)
  - [mm](https://github.com/node-modules/mm) - An simple but flexible mock(or say stub) package, mock mate. ![](https://img.shields.io/github/stars/node-modules/mm.svg?style=social&label=Star)

- Mock Server
  - [json-server](https://github.com/typicode/json-server) - Get a full fake REST API with zero coding in less than 30 seconds. ![](https://img.shields.io/github/stars/typicode/json-server.svg?style=social&label=Star)
  - [easy-mock](https://github.com/easy-mock/easy-mock) - A persistent service that generates mock data quickly and provids visualization view. ![](https://img.shields.io/github/stars/easy-mock/easy-mock.svg?style=social&label=Star)
  - [miragejs](https://github.com/miragejs/miragejs) - A client-side server to build, test and share your JavaScript app. ![](https://img.shields.io/github/stars/miragejs/miragejs.svg?style=social&label=Star)
  - [pretender](https://github.com/pretenderjs/pretender) - A mock server library with a nice routing DSL. ![](https://img.shields.io/github/stars/pretenderjs/pretender.svg?style=social&label=Star)
  - [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. ![](https://img.shields.io/github/stars/micromata/http-fake-backend.svg?style=social&label=Star)
  - [smoke](https://github.com/sinedied/smoke) - 💨 Simple yet powerful file-based mock server with recording abilities. ![](https://img.shields.io/github/stars/sinedied/smoke.svg?style=social&label=Star)

- UI Recoder / Replay
  - [rrweb](https://github.com/rrweb-io/rrweb) - Record and replay the web. ![](https://img.shields.io/github/stars/rrweb-io/rrweb.svg?style=social&label=Star)
  - [uirecorder](https://github.com/alibaba/uirecorder) - UI Recorder is a multi-platform UI test recorder. ![](https://img.shields.io/github/stars/alibaba/uirecorder.svg?style=social&label=Star)

- End-to-end Testing
  - [cypress](https://github.com/cypress-io/cypress) - Fast, easy and reliable testing for anything that runs in a browser. ![](https://img.shields.io/github/stars/cypress-io/cypress.svg?style=social&label=Star)
  - [nightwatch](https://github.com/nightwatchjs/nightwatch) - End-to-end testing framework written in Node.js and using the Webdriver API. ![](https://img.shields.io/github/stars/nightwatchjs/nightwatch.svg?style=social&label=Star)
  - [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - End 2 End Testing Framework for NodeJS. ![](https://img.shields.io/github/stars/codeceptjs/CodeceptJS.svg?style=social&label=Star)

- Testing Framework
  - [jest](https://github.com/facebook/jest) - Delightful JavaScript Testing. ![](https://img.shields.io/github/stars/facebook/jest.svg?style=social&label=Star)
  - [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser. ![](https://img.shields.io/github/stars/mochajs/mocha.svg?style=social&label=Star)
  - [ava](https://github.com/avajs/ava) - Node.js test runner that lets you develop with confidence 🚀. ![](https://img.shields.io/github/stars/avajs/ava.svg?style=social&label=Star)
  - [jasmine](https://github.com/jasmine/jasmine) - Simple JavaScript testing framework for browsers and node.js. ![](https://img.shields.io/github/stars/jasmine/jasmine.svg?style=social&label=Star)
  - [supertest](https://github.com/visionmedia/supertest) - Super-agent driven library for testing node.js HTTP servers using a fluent API. ![](https://img.shields.io/github/stars/visionmedia/supertest.svg?style=social&label=Star)
  - [node-tap](https://github.com/tapjs/node-tap) - Test Anything Protocol tools for node. ![](https://img.shields.io/github/stars/tapjs/node-tap.svg?style=social&label=Star)

- Coverage
  - [nyc](https://github.com/istanbuljs/nyc) - The Istanbul command line interface. ![](https://img.shields.io/github/stars/istanbuljs/nyc.svg?style=social&label=Star)
  - [node-coveralls](https://github.com/nickmerwin/node-coveralls) - Coveralls.io support for Node.js. Get the great coverage reporting of coveralls.io and add a cool coverage button (like the one above) to your README. ![](https://img.shields.io/github/stars/nickmerwin/node-coveralls.svg?style=social&label=Star)
  - [codecov](https://github.com/codecov/codecov-node) - Global coverage report uploader for Codecov in NodeJS. ![](https://img.shields.io/github/stars/codecov/codecov-node.svg?style=social&label=Star)

- Benchmarking
  - [Benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking library that supports high-resolution timers and returns statistically significant results. ![](https://img.shields.io/github/stars/bestiejs/benchmark.js.svg?style=social&label=Star)
  - [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking. ![](https://img.shields.io/github/stars/logicalparadox/matcha.svg?style=social&label=Star)
  - [benny](https://github.com/caderek/benny) - A dead simple benchmarking framework for JS/TS libs. ![](https://img.shields.io/github/stars/caderek/benny.svg?style=social&label=Star)
  - [node-wrk](https://github.com/sidorares/node-wrk) - Wrk load testing tool node wrapper. ![](https://img.shields.io/github/stars/sidorares/node-wrk.svg?style=social&label=Star)

- Solution
  - [macaca](https://github.com/alibaba/macaca) - Automation solution for multi-platform. *(You might like [awesome-macaca](https://github.com/macacajs/awesome-macaca))* ![](https://img.shields.io/github/stars/alibaba/macaca.svg?style=social&label=Star)

### Office

- Excel
  - [sheetjs](https://github.com/SheetJS/sheetjs) - Spreadsheet Data Toolkit. ![](https://img.shields.io/github/stars/SheetJS/sheetjs.svg?style=social&label=Star)
  - [exceljs](https://github.com/exceljs/exceljs) - Excel Workbook Manager. ![](https://img.shields.io/github/stars/exceljs/exceljs.svg?style=social&label=Star)
  - [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Excel XLSX parser/generator written in JavaScript with Node.js and browser support. ![](https://img.shields.io/github/stars/dtjohnson/xlsx-populate.svg?style=social&label=Star)

- Word
  - [officegen](https://github.com/Ziv-Barber/officegen) - Standalone Office Open XML files (Microsoft Office 2007 and later) generator for Word (docx), PowerPoint (pptx) and Excell (xlsx) in javascript. The output is a stream. ![](https://img.shields.io/github/stars/Ziv-Barber/officegen.svg?style=social&label=Star)
  - [Mammoth](https://github.com/mwilliamson/mammoth.js) - Convert Word documents (.docx files) to HTML. ![](https://img.shields.io/github/stars/mwilliamson/mammoth.js.svg?style=social&label=Star)
  - [docx](https://github.com/dolanmiu/docx) - Easily generate .docx files with JS/TS with a nice declarative API. Works for Node and on the Browser. ![](https://img.shields.io/github/stars/dolanmiu/docx.svg?style=social&label=Star)

- PDF
  - [jsPDF](https://github.com/MrRio/jsPDF) - A library to generate PDFs in JavaScript. ![](https://img.shields.io/github/stars/MrRio/jsPDF.svg?style=social&label=Star)
  - [PDFKit](https://github.com/foliojs/pdfkit) - JavaScript PDF generation library for Node and the browser. ![](https://img.shields.io/github/stars/foliojs/pdfkit.svg?style=social&label=Star)
  - [percollate](https://github.com/danburzo/percollate) - A command-line tool to turn web pages into beautiful, readable PDF, EPUB, or HTML docs. ![](https://img.shields.io/github/stars/danburzo/percollate.svg?style=social&label=Star)
  - [pdf-lib](https://github.com/Hopding/pdf-lib) - Create and modify PDF documents in any JavaScript environment. ![](https://img.shields.io/github/stars/Hopding/pdf-lib.svg?style=social&label=Star)
  - [pdf2json](https://github.com/modesty/pdf2json) - A PDF file parser that converts PDF binaries to text based JSON. ![](https://img.shields.io/github/stars/modesty/pdf2json.svg?style=social&label=Star)

- PPT
  - [nodeppt](https://github.com/ksky521/nodeppt) - This is probably the best web presentation tool so far! ![](https://img.shields.io/github/stars/ksky521/nodeppt.svg?style=social&label=Star)

### OS Identification

- [systeminformation](https://github.com/sebhildebrandt/systeminformation) - Hardware/software system information. ![](https://img.shields.io/github/stars/sebhildebrandt/systeminformation.svg?style=social&label=Star)
- [is-wsl](https://github.com/sindresorhus/is-wsl) - Detect whether current platform is WSL (Windows Subsystem for Linux). ![](https://img.shields.io/github/stars/sindresorhus/is-wsl.svg?style=social&label=Star)
- [os-name](https://github.com/sindresorhus/os-name) - Get the name of the current operating system. ![](https://img.shields.io/github/stars/sindresorhus/os-name.svg?style=social&label=Star)
- [getos](https://github.com/retrohacker/getos) - Retrieve the current OS, including Linux distribution. ![](https://img.shields.io/github/stars/retrohacker/getos.svg?style=social&label=Star)
- [is-windows](https://github.com/jonschlinkert/is-windows) - Detect whether the current platform is Windows. ![](https://img.shields.io/github/stars/jonschlinkert/is-windows.svg?style=social&label=Star)

### Compression / Decompression

- [jszip](https://github.com/Stuk/jszip) - Create, read and edit .zip files with Javascript. ![](https://img.shields.io/github/stars/Stuk/jszip.svg?style=social&label=Star)
- [pako](https://github.com/nodeca/pako) - High speed zlib port to javascript, works in browser & node.js. ![](https://img.shields.io/github/stars/nodeca/pako.svg?style=social&label=Star)
- [adm-zip](https://github.com/cthackers/adm-zip) - Create, read and edit .zip files with Javascript. ![](https://img.shields.io/github/stars/cthackers/adm-zip.svg?style=social&label=Star)
- [node-tar](https://github.com/npm/node-tar) - Fast and full-featured Tar for Node.js. ![](https://img.shields.io/github/stars/npm/node-tar.svg?style=social&label=Star)
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Yet another unzip library for node. ![](https://img.shields.io/github/stars/thejoshwolfe/yauzl.svg?style=social&label=Star)
- [unzipper](https://github.com/ZJONSSON/node-unzipper) - Node.js cross-platform unzip using streams. ![](https://img.shields.io/github/stars/ZJONSSON/node-unzipper.svg?style=social&label=Star)
- [tar-fs](https://github.com/mafintosh/tar-fs) - Tar-fs allows you to pack directories into tarballs and extract tarballs into directories. ![](https://img.shields.io/github/stars/mafintosh/tar-fs.svg?style=social&label=Star)
- [extract-zip](https://github.com/maxogden/extract-zip) - Zip extraction written in pure JavaScript. Extracts a zip into a directory. ![](https://img.shields.io/github/stars/maxogden/extract-zip.svg?style=social&label=Star)
- [compressing](https://github.com/node-modules/compressing) - Everything you need for compressing and uncompressing. ![](https://img.shields.io/github/stars/node-modules/compressing.svg?style=social&label=Star)
- [yazl](https://github.com/thejoshwolfe/yazl) - Yet another zip library for node. ![](https://img.shields.io/github/stars/thejoshwolfe/yazl.svg?style=social&label=Star)
- [7zip](https://github.com/fritx/win-7zip) - 7zip Windows Package via Node.js. ![](https://img.shields.io/github/stars/fritx/win-7zip.svg?style=social&label=Star)

###  Minifiers

- [UglifyJS](https://github.com/mishoo/UglifyJS) - JavaScript minifier. ![](https://img.shields.io/github/stars/mishoo/UglifyJS.svg?style=social&label=Star)
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier. ![](https://img.shields.io/github/stars/imagemin/imagemin.svg?style=social&label=Star)
- [babel-minify](https://github.com/babel/minify) - ES6+ aware minifier based on the Babel toolchain. ![](https://img.shields.io/github/stars/babel/minify.svg?style=social&label=Star)
- [cssnano](https://github.com/cssnano/cssnano) - A modular minifier, built on top of the PostCSS ecosystem. ![](https://img.shields.io/github/stars/cssnano/cssnano.svg?style=social&label=Star)
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier. ![](https://img.shields.io/github/stars/jakubpawlowicz/clean-css.svg?style=social&label=Star)
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier. ![](https://img.shields.io/github/stars/Swaagie/minimize.svg?style=social&label=Star)
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS. ![](https://img.shields.io/github/stars/sindresorhus/strip-css-comments.svg?style=social&label=Star)

### Email

- [Nylas Mail](https://github.com/nylas/nylas-mail) - An extensible desktop mail app built on the modern web. ![](https://img.shields.io/github/stars/nylas/nylas-mail.svg?style=social&label=Star)
- [Nodemailer](https://github.com/nodemailer/nodemailer) - Send e-mails with Node.JS – easy as cake! ![](https://img.shields.io/github/stars/nodemailer/nodemailer.svg?style=social&label=Star)
- [Email Templates](https://github.com/forwardemail/email-templates) - Create, preview, and send custom email templates for Node.js. ![](https://img.shields.io/github/stars/forwardemail/email-templates.svg?style=social&label=Star)
- [emailjs](https://github.com/eleith/emailjs) - Html emails and attachments to any smtp server with nodejs. ![](https://img.shields.io/github/stars/eleith/emailjs.svg?style=social&label=Star)
- [mjml](https://github.com/mjmlio/mjml) - Makes responsive-email easy. ![](https://img.shields.io/github/stars/mjmlio/mjml.svg?style=social&label=Star)

### Network

- IP
  - [node-ip](https://github.com/indutny/node-ip) - IP address tools for node.js. ![](https://img.shields.io/github/stars/indutny/node-ip.svg?style=social&label=Star)
  - [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address - very fast! ![](https://img.shields.io/github/stars/sindresorhus/public-ip.svg?style=social&label=Star)
  - [request-ip](https://github.com/pbojinov/request-ip) - A Node.js module for retrieving a request's IP address on the server. ![](https://img.shields.io/github/stars/pbojinov/request-ip.svg?style=social&label=Star)
  - [ipaddr.js](https://github.com/whitequark/ipaddr.js) - IP address manipulation library in JavaScript. ![](https://img.shields.io/github/stars/whitequark/ipaddr.js.svg?style=social&label=Star)
  - [internal-ip](https://github.com/sindresorhus/internal-ip) - Get your internal IP address. ![](https://img.shields.io/github/stars/sindresorhus/internal-ip.svg?style=social&label=Star)
  - [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address. ![](https://img.shields.io/github/stars/sindresorhus/ipify.svg?style=social&label=Star)
  - [address](https://github.com/node-modules/address) - Get current machine IP and MAC address. ![](https://img.shields.io/github/stars/node-modules/address.svg?style=social&label=Star)

- Port
  - [node-portfinder](https://github.com/http-party/node-portfinder) - A simple tool to find an open port or domain socket on the current machine. ![](https://img.shields.io/github/stars/http-party/node-portfinder.svg?style=social&label=Star)
  - [get-port](https://github.com/sindresorhus/get-port) - Get an available port. ![](https://img.shields.io/github/stars/sindresorhus/get-port.svg?style=social&label=Star)
  - [detect-port](https://github.com/node-modules/detect-port) - Node.js implementation of port detector. ![](https://img.shields.io/github/stars/node-modules/detect-port.svg?style=social&label=Star)

- Tunnel
  - [localtunnel](https://github.com/localtunnel/localtunnel) - Localtunnel exposes your localhost to the world for easy testing and sharing! ![](https://img.shields.io/github/stars/localtunnel/localtunnel.svg?style=social&label=Star)
  - [node-tunnel](https://github.com/koichik/node-tunnel) - Node HTTP/HTTPS Agents for tunneling proxies. ![](https://img.shields.io/github/stars/koichik/node-tunnel.svg?style=social&label=Star)
  - [tunnel-agent](https://github.com/request/tunnel-agent) - HTTP proxy tunneling agent. Formerly part of mikeal/request, now a standalone module. ![](https://img.shields.io/github/stars/request/tunnel-agent.svg?style=social&label=Star)

- Other
  - [netcat](https://github.com/roccomuso/netcat) - Netcat port in pure JS. ![](https://img.shields.io/github/stars/roccomuso/netcat.svg?style=social&label=Star)
  - [getmac](https://github.com/bevry/getmac) - Get the computer MAC address. ![](https://img.shields.io/github/stars/bevry/getmac.svg?style=social&label=Star)
  - [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server. ![](https://img.shields.io/github/stars/infusion/node-dhcp.svg?style=social&label=Star)
  - [default-gateway](https://github.com/silverwind/default-gateway) - Get the default network gateway, cross-platform. ![](https://img.shields.io/github/stars/silverwind/default-gateway.svg?style=social&label=Star)

### HTTP

- Request Client
  - [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). ![](https://img.shields.io/github/stars/mzabriskie/axios.svg?style=social&label=Star)
  - [superagent](https://github.com/visionmedia/superagent) - HTTP request library. ![](https://img.shields.io/github/stars/visionmedia/superagent.svg?style=social&label=Star)
  - [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. ![](https://img.shields.io/github/stars/sindresorhus/got.svg?style=social&label=Star)
  - [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. ![](https://img.shields.io/github/stars/bitinn/node-fetch.svg?style=social&label=Star)
  - [undici](https://github.com/nodejs/undici) - An HTTP/1.1 client, written from scratch for Node.js. ![](https://img.shields.io/github/stars/nodejs/undici.svg?style=social&label=Star)
  - [needle](https://github.com/tomas/needle) - Nimble, streamable HTTP client for Node.js. With proxy, iconv, cookie, deflate & multipart support. ![](https://img.shields.io/github/stars/tomas/needle.svg?style=social&label=Star)
  - [urllib](https://github.com/node-modules/urllib) - Request HTTP(s) URLs in a complex world. ![](https://img.shields.io/github/stars/node-modules/urllib.svg?style=social&label=Star)
  - [phin](https://github.com/ethanent/phin) - Node HTTP client. ![](https://img.shields.io/github/stars/ethanent/phin.svg?style=social&label=Star)
  - [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got). ![](https://img.shields.io/github/stars/khaosdoctor/gotql.svg?style=social&label=Star)
  - [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. ![](https://img.shields.io/github/stars/hapijs/wreck.svg?style=social&label=Star)
  - [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. ![](https://img.shields.io/github/stars/lukechilds/cacheable-request.svg?style=social&label=Star)
  - [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. ![](https://img.shields.io/github/stars/sindresorhus/gh-got.svg?style=social&label=Star)
  - [flashheart](https://github.com/bbc/flashheart) - REST client. ![](https://img.shields.io/github/stars/bbc/flashheart.svg?style=social&label=Star)

- HTTP Server
  - [http-server](https://github.com/http-party/http-server) - A simple zero-configuration command-line http server. ![](https://img.shields.io/github/stars/http-party/http-server.svg?style=social&label=Star)
  - [anywhere](https://github.com/JacksonTian/anywhere) - Running static file server anywhere. ![](https://img.shields.io/github/stars/JacksonTian/anywhere.svg?style=social&label=Star)

- Mock Server
  - [json-server](https://github.com/typicode/json-server) - Get a full fake REST API with zero coding in less than 30 seconds. ![](https://img.shields.io/github/stars/typicode/json-server.svg?style=social&label=Star)
  - [easy-mock](https://github.com/easy-mock/easy-mock) - A persistent service that generates mock data quickly and provids visualization view. ![](https://img.shields.io/github/stars/easy-mock/easy-mock.svg?style=social&label=Star)
  - [miragejs](https://github.com/miragejs/miragejs) - A client-side server to build, test and share your JavaScript app. ![](https://img.shields.io/github/stars/miragejs/miragejs.svg?style=social&label=Star)
  - [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. ![](https://img.shields.io/github/stars/micromata/http-fake-backend.svg?style=social&label=Star)
  - [smoke](https://github.com/sinedied/smoke) - 💨 Simple yet powerful file-based mock server with recording abilities. ![](https://img.shields.io/github/stars/sinedied/smoke.svg?style=social&label=Star)

- Proxy
  - [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. ![](https://img.shields.io/github/stars/nodejitsu/node-http-proxy.svg?style=social&label=Star)
  - [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) - ⚡ The one-liner node.js http-proxy middleware for connect, express and browser-sync. ![](https://img.shields.io/github/stars/chimurai/http-proxy-middleware.svg?style=social&label=Star)
  - [https-proxy-agent](https://github.com/TooTallNate/node-https-proxy-agent) - An HTTP(s) proxy `http.Agent` implementation for HTTPS endpoints. ![](https://img.shields.io/github/stars/TooTallNate/node-https-proxy-agent.svg?style=social&label=Star)
  - [global-agent](https://github.com/gajus/global-agent) - Global HTTP/HTTPS proxy agent that is configurable using environment variables. ![](https://img.shields.io/github/stars/gajus/global-agent.svg?style=social&label=Star)
  - [fast-proxy](https://github.com/fastify/fast-proxy) - Node.js framework agnostic library that enables you to forward an http request to another HTTP server. Supported protocols: HTTP, HTTPS, HTTP2. ![](https://img.shields.io/github/stars/fastify/fast-proxy.svg?style=social&label=Star)
  - [argo](https://github.com/argo/argo) - An extensible, asynchronous HTTP reverse proxy and origin server. ![](https://img.shields.io/github/stars/argo/argo.svg?style=social&label=Star)

- Download
  - [download](https://github.com/kevva/download) - Download and extract files effortlessly. ![](https://img.shields.io/github/stars/kevva/download.svg?style=social&label=Star)
  - [nugget](https://github.com/maxogden/nugget) - Minimalist wget clone written in node. HTTP GET files and downloads them into the current directory. ![](https://img.shields.io/github/stars/maxogden/nugget.svg?style=social&label=Star)

### Authentication

- [Passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication. ![](https://img.shields.io/github/stars/jaredhanson/passport.svg?style=social&label=Star)
- [Grant](https://github.com/simov/grant) - OAuth providers for Express, Koa, Hapi, Fastify, AWS Lambda, Azure, Google Cloud, Vercel, and many more. ![](https://img.shields.io/github/stars/simov/grant.svg?style=social&label=Star)
- [permit](https://github.com/ianstormtaylor/permit) - An unopinionated authentication library for building Node.js APIs. ![](https://img.shields.io/github/stars/ianstormtaylor/permit.svg?style=social&label=Star)

### Authorization

- [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - JsonWebToken implementation for node.js ![](https://img.shields.io/github/stars/auth0/node-jsonwebtoken.svg?style=social&label=Star)
- [CASL](https://github.com/stalniy/casl) - Isomorphic authorization for UI and API. ![](https://img.shields.io/github/stars/stalniy/casl.svg?style=social&label=Star)
- [node-casbin](https://github.com/casbin/node-casbin) - Authorization library that supports access control models like ACL, RBAC and ABAC. ![](https://img.shields.io/github/stars/casbin/node-casbin.svg?style=social&label=Star)
- [jose](https://github.com/panva/jose) - Universal "JSON Web Almost Everything" - JWA, JWS, JWE, JWT, JWK with no dependencies. ![](https://img.shields.io/github/stars/panva/jose.svg?style=social&label=Star)
- [basic-auth](https://github.com/jshttp/basic-auth) - Generic basic auth Authorization header field parser. ![](https://img.shields.io/github/stars/jshttp/basic-auth.svg?style=social&label=Star)
- [selfsigned](https://github.com/jfromaniello/selfsigned) - Generate self-signed certificates from node.js. ![](https://img.shields.io/github/stars/jfromaniello/selfsigned.svg?style=social&label=Star)

### Distribute

- [redlock](https://github.com/mike-marcacci/node-redlock) - A node.js redlock implementation for distributed, highly-available redis locks. ![](https://img.shields.io/github/stars/mike-marcacci/node-redlock.svg?style=social&label=Star)
- [node-zookeeper-client](https://github.com/alexguan/node-zookeeper-client) - A pure Javascript ZooKeeper client for Node.js. ![](https://img.shields.io/github/stars/alexguan/node-zookeeper-client.svg?style=social&label=Star)

### Serialization

- [protobuf](https://github.com/protobufjs/protobuf.js) - Implementation of Protocol Buffers. ![](https://img.shields.io/github/stars/protobufjs/protobuf.js.svg?style=social&label=Star)
- [snappy](https://github.com/kesla/node-snappy) - Native bindings for Google's Snappy compression library. ![](https://img.shields.io/github/stars/kesla/node-snappy.svg?style=social&label=Star)
- [hessian.js](https://github.com/node-modules/hessian.js) - JavaScript hessian binary web service protocol, support communicate with java. ![](https://img.shields.io/github/stars/node-modules/hessian.js.svg?style=social&label=Star)
- [compactr](https://github.com/compactr/compactr.js) - Implementation of the Compactr protocol. ![](https://img.shields.io/github/stars/compactr/compactr.js.svg?style=social&label=Star)

### RPC

- [grpc-js](https://github.com/grpc/grpc-node/tree/master/packages/grpc-js) - Pure JavaScript gRPC Client. ![](https://img.shields.io/github/stars/grpc/grpc-node.svg?style=social&label=Star)
- [thrift](https://github.com/apache/thrift/tree/master/lib/nodejs) - Apache Thrift Node.js. ![](https://img.shields.io/github/stars/apache/thrift.svg?style=social&label=Star)
- [jayson](https://github.com/tedeh/jayson) - Jayson is a simple but featureful JSON-RPC 2.0/1.0 client and server for node.js. ![](https://img.shields.io/github/stars/tedeh/jayson.svg?style=social&label=Star)
- [sofa-rpc-node](https://github.com/sofastack/sofa-rpc-node) - SOFARPC Node is a high-performance, high-extensibility, production-level Nodejs RPC framework. ![](https://img.shields.io/github/stars/sofastack/sofa-rpc-node.svg?style=social&label=Star)

### Server-side DOM

- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server. ![](https://img.shields.io/github/stars/cheeriojs/cheerio.svg?style=social&label=Star)
- [jsdom](https://github.com/jsdom/jsdom) - A JavaScript implementation of various web standards, for use with Node.js. ![](https://img.shields.io/github/stars/jsdom/jsdom.svg?style=social&label=Star)
- [domino](https://github.com/fgnass/domino) - Server-side DOM implementation based on Mozilla's dom.js. ![](https://img.shields.io/github/stars/fgnass/domino.svg?style=social&label=Star)

### Crawler

- [node-crawler](https://github.com/bda-research/node-crawler) - Web Crawler/Spider for NodeJS + server-side jQuery. ![](https://img.shields.io/github/stars/bda-research/node-crawler.svg?style=social&label=Star)
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraper with pagination and crawler support. ![](https://img.shields.io/github/stars/lapwinglabs/x-ray.svg?style=social&label=Star)
- [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Headless Chrome crawls with jQuery support. ![](https://img.shields.io/github/stars/yujiosaka/headless-chrome-crawler.svg?style=social&label=Star)
- [node-osmosis](https://github.com/rchipka/node-osmosis) - HTML/XML parser and web scraper for Node.js. ![](https://img.shields.io/github/stars/rchipka/node-osmosis.svg?style=social&label=Star)
- [scrape-it](https://github.com/IonicaBizau/scrape-it) - A Node.js scraper for humans. ![](https://img.shields.io/github/stars/IonicaBizau/scrape-it.svg?style=social&label=Star)
- [scraperjs](https://github.com/ruipgil/scraperjs) - A complete and versatile web scraper. ![](https://img.shields.io/github/stars/ruipgil/scraperjs.svg?style=social&label=Star)
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler. ![](https://img.shields.io/github/stars/cgiffard/node-simplecrawler.svg?style=social&label=Star)
- [web-scraper-chrome-extension](https://github.com/martinsbalodis/web-scraper-chrome-extension) - Web data extraction tool implemented as chrome extension. ![](https://img.shields.io/github/stars/martinsbalodis/web-scraper-chrome-extension.svg?style=social&label=Star)
- [webster](https://github.com/zhuyingda/webster) - A reliable web crawling framework which can scrape ajax and js rendered content in a web page. ![](https://img.shields.io/github/stars/zhuyingda/webster.svg?style=social&label=Star)
- [supercrawler](https://github.com/brendonboshell/supercrawler) - Define custom handlers to parse content. Obeys robots.txt, rate limits and concurrency limits. ![](https://img.shields.io/github/stars/brendonboshell/supercrawler.svg?style=social&label=Star)
- [Squidwarc](https://github.com/n0tan3rd/squidwarc) - High fidelity, user scriptable, archival crawler that uses Chrome or Chromium with or without a head. ![](https://img.shields.io/github/stars/n0tan3rd/squidwarc.svg?style=social&label=Star)
- [js-crawler](https://github.com/antivanov/js-crawler) - Web crawler for Node.JS, both HTTP and HTTPS are supported. ![](https://img.shields.io/github/stars/antivanov/js-crawler.svg?style=social&label=Star)

### AST

- Parser
  - [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript parser. ![](https://img.shields.io/github/stars/babel/babel.svg?style=social&label=Star)
  - [antlr](https://github.com/antlr/antlr4) - ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. ![](https://img.shields.io/github/stars/antlr/antlr4.svg?style=social&label=Star)
  - [acorn](https://github.com/acornjs/acorn/tree/master/acorn) - Small, fast, JavaScript-based JavaScript parser. ![](https://img.shields.io/github/stars/acornjs/acorn.svg?style=social&label=Star)
  - [esprima](https://github.com/jquery/esprima) - High performance, standard-compliant ECMAScript parser. ![](https://img.shields.io/github/stars/jquery/esprima.svg?style=social&label=Star)
  - [recast](https://github.com/benjamn/recast) - JavaScript syntax tree transformer, nondestructive pretty-printer, and automatic source map generator. ![](https://img.shields.io/github/stars/benjamn/recast.svg?style=social&label=Star)
  - [nearley](https://github.com/kach/nearley) - Simple, fast, powerful parser toolkit for JavaScript. ![](https://img.shields.io/github/stars/kach/nearley.svg?style=social&label=Star)
  - [espree](https://github.com/eslint/espree) - Esprima-compatible JavaScript parser. ![](https://img.shields.io/github/stars/eslint/espree.svg?style=social&label=Star)
  - [csstree](https://github.com/csstree/csstree) - Tool set for CSS including fast detailed parser, walker, generator and lexer based on W3C specs and browser implementations. ![](https://img.shields.io/github/stars/csstree/csstree.svg?style=social&label=Star)
  - [es-module-lexer](https://github.com/guybedford/es-module-lexer) - Low-overhead lexer dedicated to ES module parsing for fast analysis. ![](https://img.shields.io/github/stars/guybedford/es-module-lexer.svg?style=social&label=Star)

- Traversal
  - [acorn-walker](https://github.com/acornjs/acorn/tree/master/acorn-walk) - Small, fast, JavaScript-based JavaScript parser. ![](https://img.shields.io/github/stars/acornjs/acorn.svg?style=social&label=Star)
  - [estraverse](https://github.com/estools/estraverse) - ECMAScript JS AST traversal functions. ![](https://img.shields.io/github/stars/estools/estraverse.svg?style=social&label=Star)

- Codegen
  - [escodegen](https://github.com/estools/escodegen) - ECMAScript code generator. ![](https://img.shields.io/github/stars/estools/escodegen.svg?style=social&label=Star)
  - [astring](https://github.com/davidbonnet/astring) - 🌳 Tiny and fast JavaScript code generator from an ESTree-compliant AST. ![](https://img.shields.io/github/stars/davidbonnet/astring.svg?style=social&label=Star)

- JavaScript interpreter
  - [JS-Interpreter](https://github.com/NeilFraser/JS-Interpreter) - A sandboxed JavaScript interpreter in JavaScript. ![](https://img.shields.io/github/stars/NeilFraser/JS-Interpreter.svg?style=social&label=Star)
  - [jsjs](https://github.com/bramblex/jsjs) - A simple JavaScript interpreter. ![](https://img.shields.io/github/stars/bramblex/jsjs.svg?style=social&label=Star)
  - [sval](https://github.com/Siubaak/sval) - A javascript interpreter written in javascript. ![](https://img.shields.io/github/stars/Siubaak/sval.svg?style=social&label=Star)
  - [notevil](https://github.com/mmckegg/notevil) - Evalulate javascript like the built-in javascript eval() method but safely. ![](https://img.shields.io/github/stars/mmckegg/notevil.svg?style=social&label=Star)

- Other
  - [astexplorer](https://github.com/fkling/astexplorer) - Web tool to explore the ASTs generated by various parsers. ![](https://img.shields.io/github/stars/fkling/astexplorer.svg?style=social&label=Star)
  - [periscopic](https://github.com/Rich-Harris/periscopic) - Utility for analyzing scopes belonging to an ESTree-compliant AST. ![](https://img.shields.io/github/stars/Rich-Harris/periscopic.svg?style=social&label=Star)
  - [estree-walker](https://github.com/Rich-Harris/estree-walker) - Traverse an ESTree-compliant AST. ![](https://img.shields.io/github/stars/Rich-Harris/estree-walker.svg?style=social&label=Star)

### WebAssembly

- [webassembly](https://github.com/dcodeIO/webassembly) - A minimal toolkit and runtime to produce and run WebAssembly modules. ![](https://img.shields.io/github/stars/dcodeIO/webassembly.svg?style=social&label=Star)

### Design To Code（D2C）
- [psd.js](https://github.com/meltingice/psd.js) - A Photoshop PSD file parser for NodeJS and browsers. ![](https://img.shields.io/github/stars/meltingice/psd.js.svg?style=social&label=Star)

### Sandbox

- [vm2](https://github.com/patriksimek/vm2) - Advanced vm/sandbox for Node.js. ![](https://img.shields.io/github/stars/patriksimek/vm2.svg?style=social&label=Star)
- [sandbox](https://github.com/gf3/sandbox) - A nifty javascript sandbox for node.js. ![](https://img.shields.io/github/stars/gf3/sandbox.svg?style=social&label=Star)
- [safeify](https://github.com/Houfeng/safeify) - Safe sandbox that can be used to execute untrusted code. ![](https://img.shields.io/github/stars/Houfeng/safeify.svg?style=social&label=Star)

### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework. ![](https://img.shields.io/github/stars/rwaldron/johnny-five.svg?style=social&label=Star)
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing. ![](https://img.shields.io/github/stars/voodootikigod/node-serialport.svg?style=social&label=Star)
- [usb](https://github.com/nonolith/node-usb) - USB library. ![](https://img.shields.io/github/stars/nonolith/node-usb.svg?style=social&label=Star)
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection. ![](https://img.shields.io/github/stars/fivdi/onoff.svg?style=social&label=Star)
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi. ![](https://img.shields.io/github/stars/fivdi/pigpio.svg?style=social&label=Star)
- [node-escpos](https://github.com/song940/node-escpos) - ESC/POS Printer driver for node. ![](https://img.shields.io/github/stars/song940/node-escpos.svg?style=social&label=Star)
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access. ![](https://img.shields.io/github/stars/fivdi/i2c-bus.svg?style=social&label=Star)
- [gps](https://github.com/infusion/GPS.js) - NMEA parser for handling GPS receivers. ![](https://img.shields.io/github/stars/infusion/GPS.js.svg?style=social&label=Star)
- [node-bluetooth](https://github.com/song940/node-bluetooth) - Bluetooth serial port communication for Node.js. ![](https://img.shields.io/github/stars/song940/node-bluetooth.svg?style=social&label=Star)
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access. ![](https://img.shields.io/github/stars/fivdi/spi-device.svg?style=social&label=Star)

### IoT

- [zetta](https://github.com/zettajs/zetta) - An API-first, open source software platform for the Internet of Things. ![](https://img.shields.io/github/stars/zettajs/zetta.svg?style=social&label=Star)
- [iot-nodejs](https://github.com/ibm-watson-iot/iot-nodejs) - Client libraries and samples for connecting to IBM Watson IoT using nodejs. ![](https://img.shields.io/github/stars/ibm-watson-iot/iot-nodejs.svg?style=social&label=Star)

### Machine learning & Neural networks

- [tfjs](https://github.com/tensorflow/tfjs) - A WebGL accelerated JavaScript library for training and deploying ML models. ![](https://img.shields.io/github/stars/tensorflow/tfjs.svg?style=social&label=Star)
- [netron](https://github.com/lutzroeder/netron) - Visualizer for neural network, deep learning, and machine learning models. ![](https://img.shields.io/github/stars/lutzroeder/netron.svg?style=social&label=Star)
- [face-api.js](https://github.com/justadudewhohacks/face-api.js) - JavaScript API for face detection and face recognition in the browser and nodejs with tensorflow.js. ![](https://img.shields.io/github/stars/justadudewhohacks/face-api.js.svg?style=social&label=Star)
- [brain.js](https://github.com/BrainJS/brain.js) - GPU accelerated Neural networks in JavaScript for Browsers and Node.js. ![](https://img.shields.io/github/stars/BrainJS/brain.js.svg?style=social&label=Star)
- [pipcook](https://github.com/alibaba/pipcook) - Machine learning platform for Web developers. ![](https://img.shields.io/github/stars/alibaba/pipcook.svg?style=social&label=Star)
- [onnxjs](https://github.com/microsoft/onnxjs) - ONNX.js: run ONNX models using JavaScript. ![](https://img.shields.io/github/stars/microsoft/onnxjs.svg?style=social&label=Star)
- [tensorflow-nodejs](https://github.com/yorkie/tensorflow-nodejs) - TensorFlow Node.js provides idiomatic JavaScript language bindings and a high layer API for Node.js users. ![](https://img.shields.io/github/stars/yorkie/tensorflow-nodejs.svg?style=social&label=Star)

### Natural language processing

- [compromise](https://github.com/spencermountain/compromise) - Modest natural-language processing. ![](https://img.shields.io/github/stars/spencermountain/compromise.svg?style=social&label=Star)
- [natural](https://github.com/NaturalNode/natural) - Natural language facility. ![](https://img.shields.io/github/stars/NaturalNode/natural.svg?style=social&label=Star)
- [nlp.js](https://github.com/axa-group/nlp.js) - Building bots, with entity extraction, sentiment analysis, automatic language identify, and more. ![](https://img.shields.io/github/stars/axa-group/nlp.js.svg?style=social&label=Star)
- [franc](https://github.com/wooorm/franc) - Detect the language of text. ![](https://img.shields.io/github/stars/wooorm/franc.svg?style=social&label=Star)
- [sentiment](https://github.com/thisandagain/sentiment) - AFINN-based sentiment analysis for Node.js. ![](https://img.shields.io/github/stars/thisandagain/sentiment.svg?style=social&label=Star)
- [retext](https://github.com/wooorm/retext) - An extensible natural language system. ![](https://img.shields.io/github/stars/wooorm/retext.svg?style=social&label=Star)
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm. ![](https://img.shields.io/github/stars/sindresorhus/leven.svg?style=social&label=Star)

### OCR

- [tesseract.js](https://github.com/naptha/tesseract.js) - Pure Javascript OCR for more than 100 Languages. ![](https://img.shields.io/github/stars/naptha/tesseract.js.svg?style=social&label=Star)
- [Parsr](https://github.com/axa-group/Parsr) - Transforms PDF, Documents and Images into Enriched Structured Data. ![](https://img.shields.io/github/stars/axa-group/Parsr.svg?style=social&label=Star)

### Bitcoin

- [GitTorrent](https://github.com/cjb/GitTorrent) - A decentralization of GitHub using BitTorrent and Bitcoin. ![](https://img.shields.io/github/stars/cjb/GitTorrent.svg?style=social&label=Star)
- [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) - A javascript Bitcoin library for node.js and browsers. ![](https://img.shields.io/github/stars/bitcoinjs/bitcoinjs-lib.svg?style=social&label=Star)
- [bitcore](https://github.com/bitpay/bitcore) - A full stack for bitcoin and blockchain-based applications. ![](https://img.shields.io/github/stars/bitpay/bitcore.svg?style=social&label=Star)

## Project

### Lowcode

- H5/PC
  - [amis](https://github.com/baidu/amis) - LowCode Framework, Generate various pages through JSON configuration. ![](https://img.shields.io/github/stars/baidu/amis.svg?style=social&label=Star)

- H5
  - [h5-Dooring](https://github.com/MrXujiang/h5-Dooring) - H5 Page Maker, H5 Editor, LowCode. Make H5 as easy as building blocks. ![](https://img.shields.io/github/stars/MrXujiang/h5-Dooring.svg?style=social&label=Star)
  - [luban-h5](https://github.com/ly525/luban-h5) - Web design tool || mobile page builder/editor || mini webflow for mobile page. ![](https://img.shields.io/github/stars/ly525/luban-h5.svg?style=social&label=Star)
  - [gods-pen](https://github.com/ymm-tech/gods-pen) - A mobile page builder/editor, similar with amolink. ![](https://img.shields.io/github/stars/ymm-tech/gods-pen.svg?style=social&label=Star)

- PC
  - [pc-Dooring](https://github.com/MrXujiang/pc-Dooring) - LowCode, PC Page Maker, PC Editor. Make PC as easy as building blocks. ![](https://img.shields.io/github/stars/MrXujiang/pc-Dooring.svg?style=social&label=Star)

- Logical Arrangement
  - [node-red](https://github.com/node-red/node-red) - Low-code programming for event-driven applications. ![](https://img.shields.io/github/stars/node-red/node-red.svg?style=social&label=Star)
  - [imove](https://github.com/ykfe/imove) - Move your mouse, generate code from flow chart. ![](https://img.shields.io/github/stars/ykfe/imove.svg?style=social&label=Star)
