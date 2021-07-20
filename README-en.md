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
  - [JSON](#json)
  - [Image](#image)
  - [Video](#video)
  - [Font](#font)
  - [Color](#color)
  - [Crypto](#crypto)
  - [Streams](#streams)
  - [Check/Detect](#checkdetect)
  - [Data Validation](#data-validation)
  - [Functional programming](#functional-programming)
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
  - [Content management systems (CMS)](#content-management-systems-cms)
  - [Static Site Generator & Blogging](#static-site-generator--blogging)
  - [Documentation](#documentation)
  - [Desktop Apps](#desktop-apps)
  - [Real-time](#real-time)
  - [Job Queues](#job-queues)
  - [Job Scheduling](#job-scheduling)
  - [Debugging](#debugging)
  - [Profiling/Analysis](#profilinganalysis)
  - [Application Performance Monitoring (APM)](#application-performance-monitoring-apm)
  - [Forum](#forum)
  - [Database](#database)
  - [Cache](#cache)
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
  - [dedent](https://github.com/dmnd/dedent) - ES6 string tag that strips indentation from multi-line strings.
  - [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
  - [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it.
  - [decamelize](https://github.com/sindresorhus/decamelize) - Convert a camelized string into a lowercased one with a custom separator: unicornRainbow → unicorn_rainbow
  - [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code.
  - [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes.
  - [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string.
  - [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string.
  - [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string.
  - [redent](https://github.com/sindresorhus/redent) - Strip redundant indentation and indent the string.
  - [normalize-newline](https://github.com/sindresorhus/normalize-newline) - Normalize the newline characters in a string to `\n`.
  - [min-indent](https://github.com/jamiebuilds/min-indent) - Get the shortest leading whitespace from lines in a string.
  - [trim-right](https://github.com/sindresorhus/trim-right) - Similar to String#trim() but removes only whitespace on the right.
  - [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`.

- i18n
  - [i18next](https://github.com/i18next/i18next) - Internationalization framework.
  - [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.
  - [babelfish](https://github.com/nodeca/babelfish) - human friendly i18n for javascript (node.js + browser).

- Unique Id
  - [nanoid](https://github.com/ai/nanoid) - Tiny, secure, URL-friendly, unique string ID generator.
  - [uuid](https://github.com/uuidjs/uuid) - Generate RFC-compliant UUIDs in JavaScript.
  - [shortid](https://github.com/dylang/shortid) - Short id generator. Url-friendly. Non-predictable. Cluster-compatible.
  - [ulid](https://github.com/ulid/javascript) - Universally Unique Lexicographically Sortable Identifier.
  - [uuid-js](https://github.com/pnegri/uuid-js) - A js library to generate and parse UUIDs,TimeUUIDs and generate TimeUUID based on Date for range selections.
  - [pure-uuid](https://github.com/rse/pure-uuid) - Pure JavaScript Based Universally Unique Identifiers (UUID).

- Encode/Decode
  - [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder.
  - [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings.
  - [jschardet](https://github.com/aadsm/jschardet) - Character encoding auto-detection in JavaScript (port of python's chardet)

- Comparison
  - [jsdiff](https://github.com/kpdecker/jsdiff) - A javascript text differencing implementation.
  - [recursive-diff](https://github.com/cosmicanant/recursive-diff) - A JavaScript library to find diff between two JavaScript Objects. Support for Array, Number, Date and other primitive data types.

- Other
  - [StegCloak](https://github.com/kurolabs/stegcloak) - Conceal secrets within strings, in plain sight.
  - [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters.

### Number

- [Numeral.js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers.
- [bignumber.js](https://github.com/MikeMcl/bignumber.js) - A JavaScript library for arbitrary-precision decimal and non-decimal arithmetic.
- [decimal.js](https://github.com/MikeMcl/decimal.js) - An arbitrary-precision Decimal type for JavaScript.
- [big.js](https://github.com/MikeMcl/big.js) - A small, fast JavaScript library for arbitrary-precision decimal arithmetic.
- [random-js](https://github.com/ckknight/random-js) - A mathematically correct random number generator library for JavaScript.
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`.
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique.
- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer.
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float.

### Math

- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.
- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays.
- [algebra](https://github.com/fibo/algebra) - Algebraic structures.
- [multimath](https://github.com/nodeca/multimath) - Core to create fast image math in WebAssembly and JS.

### Date & Time

- [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript.
- [dayjs](https://github.com/iamkun/dayjs) - Day.js 2KB immutable date-time library alternative to Moment.js with the same modern API.
- [date-fns](https://github.com/date-fns/date-fns) - Modern JavaScript date utility library.
- [luxon](https://github.com/moment/luxon) - Library for working with dates and times.
- [timeago.js](https://github.com/hustcc/timeago.js) - 🕗 ⌛ timeago.js is a tiny(2.0 kb) library used to format date with `*** time ago` statement.
- [ms](https://github.com/vercel/ms) - Tiny millisecond conversion utility.
- [dateformat](https://github.com/felixge/node-dateformat) - A node.js package for Steven Levithan's excellent dateFormat() function.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`
- [strftime](https://github.com/samsonjs/strftime) - Strftime for JavaScript.
- [node-microtime](https://github.com/wadey/node-microtime) - Get the current time in microseconds.
- [date-utils](https://github.com/JerrySievert/date-utils) - Date Pollyfills for Node.js and Browser.
- [pretty-hrtime](https://github.com/robrich/pretty-hrtime) - process.hrtime() to words.
- [humanize-ms](https://github.com/node-modules/humanize-ms) - Transform humanize time to ms.

### RegExp/Glob

- [path-to-regexp](https://github.com/pillarjs/path-to-regexp) - Turn a path string such as `/user/:name` into a regular expression.
- [minimatch](https://github.com/isaacs/minimatch) - A minimal matching utility.
- [micromatch](https://github.com/micromatch/micromatch) - Highly optimized wildcard and glob matching library. Faster, drop-in replacement to minimatch and multimatch. Used by webpack, babel core, yarn, jest, browser-sync, documentation.js, stylelint, nyc, ava, and many others!
- [randexp.js](https://github.com/fent/randexp.js) - Create random strings that match a given regular expression.
- [safe-regex](https://github.com/substack/safe-regex) - Detect possibly catastrophic, exponential-time regular expressions.
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching.
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters.
- [multimatch](https://github.com/sindresorhus/multimatch) - Extends minimatch.match() with support for multiple patterns.
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string.

### URL

- [URI.js](https://github.com/medialize/URI.js) - Javascript URL mutation library.
- [qs](https://github.com/ljharb/qs) - Querystring parser with nesting support.
- [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings.
- [url-parse](https://github.com/unshiftio/url-parse) - Small footprint URL parser that works seamlessly across Node.js and browser environments.
- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL.
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. turn strings into data or data into strings.
- [native-url](https://github.com/GoogleChromeLabs/native-url) - Node's url module implemented using the built-in URL API.
- [url-join](https://github.com/jfromaniello/url-join) - Join all arguments together and normalize the resulting url.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: https://sindresorhus.com → sindresorhus.com.
- [parseurl](https://github.com/pillarjs/parseurl) - Parse a url with memoization.
- [file-url](https://github.com/sindresorhus/file-url) - Convert a file path to a file URL: `unicorn.jpg` → `file:///Users/sindresorhus/unicorn.jpg`
- [encodeurl](https://github.com/pillarjs/encodeurl) - Encode a URL to a percent-encoded form, excluding already-encoded sequences.

### JSON

- [json5](https://github.com/json5/json5) - JSON5 — JSON for humans.
- [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - Diff & patch JavaScript objects.
- [fast-json-stringify](https://github.com/fastify/fast-json-stringify) - 2x faster than JSON.stringify()
- [jsonfile](https://github.com/jprichardson/node-jsonfile) - Easily read/write JSON files.
- [jsonata](https://github.com/jsonata-js/jsonata) - JSONata query and transformation language - http://jsonata.org
- [json-stable-stringify](https://github.com/substack/json-stable-stringify) - Deterministic JSON.stringify() with custom sorting to get deterministic hashes from stringified results.
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON. Lets you use comments in your JSON files.
- [json-stringify-safe](https://github.com/moll/json-stringify-safe) - Like JSON.stringify, but doesn't throw on circular references.
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors.
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file.
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically.
- [fast-json-stable-stringify](https://github.com/epoberezkin/fast-json-stable-stringify) - Deterministic JSON.stringify() - a faster version of @substack's json-stable-strigify without jsonify.
- [jsonuri](https://github.com/aligay/jsonuri) - Use URI style methods to operate data.

### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images.
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript.
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper.
- [qrcode](https://github.com/soldair/node-qrcode) - QR code and bar code generator.
- [pixelmatch](https://github.com/mapbox/pixelmatch) - The smallest, simplest and fastest JavaScript pixel-level image comparison library.
- [Resemble.js](https://github.com/rsmbl/Resemble.js) - Image analysis and comparison.
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed.
- [jsQR](https://github.com/cozmo/jsQR) - A pure javascript QR code reading library. This library takes in raw images and will locate, extract and parse any QR code found within.
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick.
- [gifski](https://github.com/ImageOptim/gifski) - GIF encoder based on libimagequant (pngquant). Squeezes maximum possible quality from the awful GIF format.
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download.
- [omggif](https://github.com/deanm/omggif) - JavaScript implementation of a GIF 89a encoder and decoder.
- [jpeg-js](https://github.com/jpeg-js/jpeg-js) - A pure javascript JPEG encoder and decoder for node.js.
- [pngjs](https://github.com/lukeapage/pngjs) - Simple PNG encoder/decoder.
- [get-pixels](https://github.com/scijs/get-pixels) - Reads an image into an ndarray.
- [gifencoder](https://github.com/eugeneware/gifencoder) - Server side animated gif generation for node.js.
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array.
- [node-pngquant](https://github.com/papandreou/node-pngquant) - The pngquant utility as a readable/writable stream.
- [node-bitmap](https://github.com/nowelium/node-bitmap) - Pure javascript Bitmap library.

### Video

- [fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) - A fluent API to FFMPEG (http://www.ffmpeg.org)
- [FFCreator](https://github.com/tnfe/FFCreator) - A fast short video processing library based on node.js.
- [node-ffmpeg](https://github.com/damianociarla/node-ffmpeg) - Ffmpeg module for nodejs.

### Font

- [font-spider](https://github.com/aui/font-spider) - Smart webfont compression and format conversion tool.

### Color

- [chroma](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations.
- [randomColor](https://github.com/davidmerfield/randomColor) - A tiny script for generating attractive colors.
- [rgbaster](https://github.com/briangonzalez/rgbaster.js) - 🎨 A simple library for extracting dominant colors from images.
- [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript.
- [onecolor](https://github.com/One-com/one-color) - An OO-based JavaScript color parser/computation toolkit with support for RGB, HSV, HSL, CMYK, and alpha channels. Conversion between color spaces occurs implicitly, and all methods return new objects rather than mutating existing instances. Works in the browser and node.js.

### Crypto

- [crypto-js](https://github.com/brix/crypto-js) - JavaScript library of crypto standards.
- [bcrypt](https://github.com/kelektiv/node.bcrypt.js) - Bcrypt for NodeJs.
- [jsencrypt](https://github.com/travist/jsencrypt) - A Javascript library to perform OpenSSL RSA Encryption, Decryption, and Key Generation.
- [bcrypt.js](https://github.com/dcodeIO/bcrypt.js) - Optimized bcrypt in plain JavaScript with zero dependencies.
- [jsrsasign](https://github.com/kjur/jsrsasign) - The 'jsrsasign' (RSA-Sign JavaScript Library) is an opensource free cryptography library supporting RSA/RSAPSS/ECDSA/DSA signing/validation, ASN.1, PKCS#1/5/8 private/public key, X.509 certificate, CRL, OCSP, CMS SignedData, TimeStamp, CAdES JSON Web Signature/Token in pure JavaScript.
- [node-rsa](https://github.com/rzcoder/node-rsa) - Node.js RSA library.
- [aes-js](https://github.com/ricmoo/aes-js) - A pure JavaScript implementation of the AES block cipher and all common modes of operation for node.js or web browsers.
- [node-md5](https://github.com/pvorb/node-md5) - A JavaScript function for hashing messages with MD5.
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - Tiny hashing module that uses the native crypto API in Node.js and the browser.
- [sm-crypto](https://github.com/JuneAndGreen/sm-crypto) - JavaScript library of sm2, sm3, sm4.
- [sha.js](https://github.com/crypto-browserify/sha.js) - Streamable SHA hashes in pure javascript.
- [cryptr](https://github.com/MauriceButler/cryptr) - Very basic encrypt and decrypt node module.
- [hash.js](https://github.com/indutny/hash.js) - Hash functions in pure javascript.
- [pbkdf2](https://github.com/crypto-browserify/pbkdf2) - PBKDF2 with any supported hashing algorithm in Node.
- [bcrypt-pbkdf](https://github.com/joyent/node-bcrypt-pbkdf) - Port of the OpenBSD `bcrypt_pbkdf` function to pure Javascript.

### Streams

- [event-stream](https://github.com/dominictarr/event-stream) - EventStream is like functional programming meets IO.
- [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise.
- [JSONStream](https://github.com/dominictarr/JSONStream) - streaming JSON.parse and stringify.
- [mississippi](https://github.com/maxogden/mississippi) - A collection of useful stream utility modules for writing better code using streams.
- [readable-stream](https://github.com/nodejs/readable-stream) - Node-core streams for userland.
- [pump](https://github.com/mafintosh/pump) - pipe streams together and close all of them if one of them closes.
- [concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result.
- [stream-json](https://github.com/uhop/stream-json) - stream-json is a collection of node.js stream components for creating custom standard-compliant JSON processors, which requires a minimal memory footprint. It can parse JSON files far exceeding available memory. Even individual primitive data items (keys, strings, and numbers) can be streamed piece-wise. Streaming SAX-inspired event-based API is included as well.
- [split](https://github.com/dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk. matcher may be a String, or a RegExp.
- [tar-stream](https://github.com/mafintosh/tar-stream) - tar-stream is a streaming tar parser and generator.
- [node-byline](https://github.com/jahewson/node-byline) - Line-by-line Stream reader.
- [ndjson](https://github.com/maxogden/ndjson) - streaming line delimited json parser + serializer](https://github.com/mcollina/cloneable-readable).
- [oppressor](https://github.com/substack/oppressor) - streaming http compression response negotiator.
- [multistream](https://github.com/feross/multistream) - A stream that emits multiple other streams one after another (streams2).
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string, buffer, or array.
- [node-stream-buffer](https://github.com/samcday/node-stream-buffer) - Readable and Writable Streams that use backing Buffers.
- [split2](https://github.com/mcollina/split2) - Split streams3 style.
- [fstream](https://github.com/npm/fstream) - Advanced FS Streaming for Node.
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream using pump and duplexify.
- [progress-stream](https://github.com/freeall/progress-stream) - Read the progress of a stream.
- [merge-stream](https://github.com/grncdr/merge-stream) - Merge multiple streams into one interleaved stream.
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a streams2 duplex stream with support for async initialization and streams1/streams2 input.
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream.
- [merge2](https://github.com/teambition/merge2) - Merge multiple streams into one stream in sequence or parallel.
- [end-of-stream](https://github.com/mafintosh/end-of-stream) - Call a callback when a readable/writable/duplex stream has completed or failed.
- [stream-to-promise](https://github.com/bendrucker/stream-to-promise) - Convert streams (readable or writable) to promises.
- [node-streamifier](https://github.com/gagle/node-streamifier) - Converts a Buffer/String to a readable stream.
- [stream-spec](https://github.com/dominictarr/stream-spec) - executable specification for Stream (make testing streams easy).
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by through2.
- [dmap-stream](https://github.com/dominictarr/map-stream) - refactored out of event-stream.
- [emit-stream](https://github.com/substack/emit-stream) - turn event emitters into streams and streams into event emitters.
- [stream-combiner](https://github.com/dominictarr/stream-combiner) - Turn a pipeline into a single stream. Combine returns a stream that writes to the first stream and reads from the last stream.
- [duplexer](https://github.com/raynos/duplexer) - Creates a duplex stream.
- [promise-streams](https://github.com/spion/promise-streams) - A collection of node.js streams that work well with promises (through, map, reduce, etc...).
- [binary-split](https://github.com/maxogden/binary-split) - A fast newline (or any delimiter) splitter stream.
- [stream-combiner2](https://github.com/substack/stream-combiner2) - stream-combiner for streams3.
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Simple Node.JS stream (streams2) Transform that runs the transform functions concurrently (with a set max concurrency).
- [cloneable-readable](https://github.com/mcollina/cloneable-readable) - Clone a Readable stream, safely.
- [destroy](https://github.com/stream-utils/destroy) - destroy a stream if possible.
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it.
- [resumer](https://github.com/substack/resumer) - a through stream that starts paused and resumes on the next tick.
- [stream-each](https://github.com/mafintosh/stream-each) - Iterate all the data in a stream.
- [flush-write-stream](https://github.com/mafintosh/flush-write-stream) - A write stream constructor that supports a flush function that is called before finish is emitted.
- [multi-write-stream](https://github.com/mafintosh/multi-write-stream) - Create a writable stream that writes to multiple other writeable streams.
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Buffer and transform the n first bytes of a stream.
- [multi-read-stream](https://github.com/mafintosh/multi-read-stream) - Readable stream that reads from multiple readable streams at the same time.
- [node-stream-reduce](https://github.com/parshap/node-stream-reduce) - Reduce stream data to a single value.
- [stream-shift](https://github.com/mafintosh/stream-shift) - Returns the next buffer/object in a stream's readable queue.
- [stream-assert](https://github.com/floatdrop/stream-assert) - Assertion library for streams.
- [stream-from-promise](https://github.com/schnittstabil/stream-from-promise) - Create streams from promises.
- [stromjs](https://github.com/lewisdiamond/stromjs) - Dependency-free stream utils. The Lodash of streams.
- [exec-stream](https://github.com/suarasaur/exec-stream) - stream to a child process.
- [stream-callback](https://github.com/kikobeats/stream-callback) – Turns a stream into a callback.

### Check/Detect

- [is.js](https://github.com/arasatasaygin/is.js) - Micro check library.
- [is-promise](https://github.com/then/is-promise) - Test whether an object looks like a promises-a+ promise.
- [is-ci](https://github.com/watson/is-ci) - Detect if the current environment is a CI server.
- [is](https://github.com/enricomarino/is) - The definitive JavaScript type testing library.
- [is-type-of](https://github.com/node-modules/is-type-of) - Complete type checking for node.
- [is-stream](https://github.com/sindresorhus/is-stream) - Check if something is a Node.js stream.
- [is-utf8](https://github.com/wayfind/is-utf8) - Detect if a buffer is utf8 encoded.
- [core-util-is](https://github.com/isaacs/core-util-is) - The util.is* functions from Node core.
- [is-ip](https://github.com/sindresorhus/is-ip) - Check if a string is an IP address.
- [isstream](https://github.com/rvagg/isstream) - Determine if an object is a Node.js Stream.
- [is-class](https://github.com/miguelmota/is-class) - Check if function is an ES6 class.
- [isexe](https://github.com/isaacs/isexe) - Minimal module to check if a file is executable.
- [is-type](https://github.com/juliangruber/is-type) - Type checking from node core.
- [is-md5](https://github.com/imanhodjaev/is-md5) - JavaScript utility to check if string is md5 encrypted.
- [is-core-module](https://github.com/inspect-js/is-core-module) - Is this specifier a node.js core module?

### Data Validation

- [validator.js](https://github.com/validatorjs/validator.js) - A library of string validators and sanitizers.
- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [async-validator](https://github.com/yiminghe/async-validator) - Validate form asynchronous.
- [class-validator](https://github.com/typestack/class-validator) - Decorator-based property validation for classes.
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON schema Validator. Supports JSON Schema draft-04/06/07/2019-09/2020-12 and JSON Type Definition (RFC8927).
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - Simple and composable way to validate data in JavaScript (and TypeScript).
- [v8n](https://github.com/imbrn/v8n) - JavaScript fluent validation library
- [forgJs](https://github.com/oussamahamdaoui/forgJs) - Javascript lightweight object validator.
- [jsonschema](https://github.com/tdegrunt/jsonschema) - JSON Schema validation.
- [validatorjs](https://github.com/mikeerickson/validatorjs) - Data validation library in JavaScript for the browser and Node.js, inspired by Laravel's Validator.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast.
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for JavaScript, Node and Express.
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation.

### Functional programming

- [lodash](https://github.com/lodash/lodash) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [RxJS](https://github.com/reactivex/rxjs) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [Bacon.js](https://github.com/baconjs/bacon.js) - Functional reactive programming.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.
- [Folktale](https://github.com/origamitower/folktale) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [Kefir.js](https://github.com/kefirjs/kefir) - Reactive library with focus on high performance and low memory usage.
- [Mout](https://github.com/mout/mout) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.

### Inversion of control / Dependency Injection (Ioc/DI)

- [InversifyJS](https://github.com/inversify/InversifyJS) - A powerful and lightweight inversion of control container for JavaScript & Node.js apps powered by TypeScript.
- [injection-js](https://github.com/mgechev/injection-js) - Dependency injection library for JavaScript and TypeScript in 5.1K. It is an extraction of the Angular's ReflectiveInjector which means that it's well designed, feature complete, fast, reliable and well tested.
- [power-di](https://github.com/zhang740/power-di) - A lightweight Dependency Injection library.

### Shell

- [zx](https://github.com/google/zx) - A tool for writing better scripts.
- [shelljs](https://github.com/shelljs/shelljs) - Cross-platform Unix shell commands.
- [execa](https://github.com/sindresorhus/execa) - Cross-platform implementation of `child_process.{execFile,exec}`.
- [node-windows](https://github.com/coreybutler/node-windows) - Windows support for Node.js scripts (daemons, eventlog, UAC, etc).
- [shx](https://github.com/shelljs/shx) - Portable Shell Commands for Node.
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Cross-platform copy/paste.
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - Cross-platform implementation of `child_process.spawn()`.
- [parallelshell](https://github.com/darkguy2008/parallelshell) - Run multiple shell commands in parallel.
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Cross-platform copy/paste.
- [gulp-execa](https://github.com/ehmicky/gulp-execa) - Cross-platform command execution in Gulp.js.
- [runscript](https://github.com/node-modules/runscript) - Run script easy!
- [cross-spawn-promise](https://github.com/zentrick/cross-spawn-promise) - Promisified cross-spawn.
- [shell-exec](https://github.com/tiaanduplessis/shell-exec) - Execute a command through the system shell.

### Environment

- [dotenv](https://github.com/motdotla/dotenv) - Loads environment variables from .env for nodejs projects.
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform.
- [envinfo](https://github.com/tabrindle/envinfo) - Generate a report about your development environment for debugging and issue reporting.
- [which](https://github.com/npm/node-which) - Cross-platform implementation of Unix's `which`.
- [user-home](https://github.com/sindresorhus/user-home) - Get the path to the user home directory. Cross-platform.
- [username](https://github.com/sindresorhus/username) - Get the current username.
- [osenv](https://github.com/npm/osenv) - Cross-platform environment variables.
- [is-elevated](https://github.com/sindresorhus/is-elevated) - Check if the process is running with elevated privileges.

### Event
- [ee-first](https://github.com/jonathanong/ee-first) - Get the first event in a set of event emitters and event pairs, then clean up after itself.

### Command-line Utilities

- Framework/Solution
  - [Commander.js](https://github.com/tj/commander.js) - The complete solution for node.js command-line interfaces.
  - [yargs](https://github.com/yargs/yargs) - Collection of common interactive command line user interfaces.
  - [oclif](https://github.com/oclif/oclif) - Node.js Open CLI Framework. Built with 💜 by Heroku.
  - [meow](https://github.com/sindresorhus/meow) - CLI app helper.
  - [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
  - [Cliffy](https://github.com/drew-y/cliffy) - Framework for interactive CLIs.
  - [common-bin](https://github.com/node-modules/common-bin) - Abstraction bin tool wrap yargs, to provide more convenient usage, support async / generator.

- Option/Argument parser
  - [minimist](https://github.com/substack/minimist) - Guts of optimist's argument parser without all the fanciful decoration.
  - [arg](https://github.com/vercel/arg) - Simple argument parsing.
  - [nopt](https://github.com/npm/nopt) - Node/npm Option Parsing.
  - [argparse](https://github.com/nodeca/argparse) - CLI arguments parser for node.js.
  - [yargs-parser](https://github.com/yargs/yargs-parser) - 💪 the mighty option parser used by yargs.

- Prompt
  - [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Collection of common interactive command line user interfaces.
  - [prompts](https://github.com/terkelg/prompts) - Lightweight, beautiful and user-friendly interactive prompts.
  - [Enquirer](https://github.com/enquirer/enquirer) - Stylish CLI prompts that are user-friendly, intuitive and easy to create.
  - [node-promptly](https://github.com/moxystudio/node-promptly) - Simple command line prompting utility for nodejs.

- Progress
  - [progress](https://github.com/visionmedia/node-progress) - Flexible ascii progress bar for nodejs.
  - [progress-estimator](https://github.com/bvaughn/progress-estimator) - Logs a progress bar and estimation for how long a Promise will take to complete.
  - [cli-progress](https://github.com/AndiDittrich/Node.CLI-Progress) - Easy to use progress-bar for command-line/terminal applications.

- Style
  - [chalk](https://github.com/chalk/chalk) - Terminal string styling done right.
  - [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner.
  - [colors.js](https://github.com/Marak/colors.js) - Get colors in your node.js console.
  - [listr](https://github.com/SamVerschueren/listr) - Terminal task list.
  - [figlet.js](https://github.com/patorjk/figlet.js) - A FIG Driver written in JavaScript which aims to fully implement the FIGfont spec.
  - [kleur](https://github.com/lukeed/kleur) - The fastest Node.js library for formatting terminal text with ANSI colors~!
  - [colorette](https://github.com/jorgebucaran/colorette) - Easily set the color and style of text in the terminal.
  - [qrcode-terminal](https://github.com/gtanner/qrcode-terminal) - QRCodes in your terminal.
  - [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal.
  - [terminal-image](https://github.com/sindresorhus/terminal-image) - Display images in the terminal.
  - [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels.
  - [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output.
  - [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows fallbacks.
  - [terminal-link](https://github.com/sindresorhus/terminal-link) - Create clickable links in the terminal.
  - [snazzy](https://github.com/standard/snazzy) - Format JavaScript Standard Style as Stylish (i.e. snazzy) output.
  - [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping.
  - [cli-table3](https://github.com/cli-table/cli-table3) - Pretty unicode tables for the command line.
  - [easy-table](https://github.com/eldargab/easy-table) - Nice text table for Node.js.
  - [cli-highlight](https://github.com/felixfbecker/cli-highlight) - Syntax highlighting for your terminal 💻✨.
  - [treeify](https://github.com/notatestuser/treeify) - Pretty-print a javascript object as a tree.
  - [kolorist](https://github.com/marvinhagemeister/kolorist) - A tiny utility to colorize stdin/stdout.
  - [console-png](https://github.com/aantthony/console-png) - Print PNG images to terminal output.

- Editor
  - [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor.

- Other
  - [commitizen](https://github.com/commitizen/cz-cli) - The commitizen command line utility.
  - [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app.
  - [console-clear](https://github.com/lukeed/console-clear) - Clear the console, cross-platform.

### Node.js Management

- [nvm](https://github.com/nvm-sh/nvm) - Node Version Manager。
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows.
- [n](https://github.com/tj/n) - Node.js version management.
- [fnm](https://github.com/Schniz/fnm) - 🚀 Fast and simple Node.js version manager, built in Rust.
- [nodenv](https://github.com/nodenv/nodenv) - Version manager that is similar to Ruby's rbenv. It supports auto version switching.
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js.
- [nvs](https://github.com/jasongin/nvs) - Node Version Switcher - A cross-platform tool for switching between versions and forks of Node.js
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv.

### NPM

- NPM Management
  - [pnpm](https://github.com/pnpm/pnpm) - Fast, disk space efficient package manager.
  - [npm](https://github.com/npm/cli) - The package manager for JavaScript.
  - [yarn](https://github.com/yarnpkg/berry) - A modern package manager split into various packages.
  - [yalc](https://github.com/wclr/yalc) - Work with yarn/npm packages locally like a boss.
  - [nrm](https://github.com/Pana/nrm) - About NPM registry manager, fast switch between different registries: npm, cnpm, nj, taobao.
  - [cnpm](https://github.com/cnpm/cnpm) - Npm client for China mirror of npm.

- package.json
  - [read-pkg-up](https://github.com/sindresorhus/read-pkg-up) - Read the closest package.json file.
  - [node-pkginfo](https://github.com/indexzero/node-pkginfo) - An easy way to expose properties on a module from a package.json.
  - [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package.
  - [read-pkg](https://github.com/sindresorhus/read-pkg) - Read a package.json file.
  - [write-pkg](https://github.com/sindresorhus/write-pkg) - Write a package.json file.
  - [read-package-json-fast](https://github.com/npm/read-package-json-fast) - Like read-package-json, but faster.

- Semantic Version
  - [semver](https://github.com/npm/node-semver) - The semver parser for node (the one npm uses).
  - [compare-versions](https://github.com/omichelsen/compare-versions) - Compare semver version strings to find which is greater, equal or lesser.

- Private Npm Registry
  - [verdaccio](https://github.com/verdaccio/verdaccio) - A lightweight private proxy registry build in Node.js.
  - [cnpmjs.org](https://github.com/cnpm/cnpmjs.org) - Private npm registry and web for Enterprise.

- Utilities
  - [npm-check-updates](https://github.com/raineorshine/npm-check-updates) - Find newer versions of package dependencies than what your package.json allows.
  - [concurrently](https://github.com/kimmobrunfeldt/concurrently) - Run commands concurrently. Like `npm run watch-js & npm run watch-less` but better.
  - [npm-run-all](https://github.com/mysticatea/npm-run-all) - A CLI tool to run multiple npm-scripts in parallel or sequential.
  - [depcheck](https://github.com/depcheck/depcheck) - Check your npm module for unused dependencies.
  - [npminstall](https://github.com/cnpm/npminstall) - Make `npm install` fast and easy.
  - [validate-npm-package-name](https://github.com/npm/validate-npm-package-name) - Is the given string an acceptable npm package name?
  - [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package.
  - [npm-name](https://github.com/sindresorhus/npm-name) - Check a package name's availability on npm.
  - [pacote](https://github.com/npm/pacote) - Fetches package manifests and tarballs from the npm registry.
  - [npm-package-arg](https://github.com/npm/npm-package-arg) - Parse the things that can be arguments to `npm install`.
  - [npm-registry-fetch](https://github.com/npm/npm-registry-fetch) - Like fetch() but for the npm registry
  - [npm-updater](https://github.com/node-modules/npm-updater) - Check update of npm package.

### Monorepo
*(You might like [awesome-monorepo](https://github.com/korfuri/awesome-monorepo))*

- [lerna](https://github.com/lerna/lerna) - A tool for managing JavaScript projects with multiple packages.

### Filesystem

- Common
  - [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.
  - [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Graceful-fs functions as a drop-in replacement for the fs module, making various improvements.
  - [filesize.js](https://github.com/avoidwork/filesize.js) - Generate a human readable String describing the file size.
  - [memfs](https://github.com/streamich/memfs) - In-memory filesystem with Node's API.
  - [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use.
  - [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like mkdir -p.
  - [find-up](https://github.com/sindresorhus/find-up) - Find a file or directory by walking up parent directories.
  - [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename.
  - [copyfiles](https://github.com/calvinmetcalf/copyfiles) - Copy files on the command line.
  - [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system.
  - [move-file](https://github.com/sindresorhus/move-file) - Move a file, even works across devices.
  - [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility.
  - [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary.
  - [mkdirp](https://github.com/isaacs/node-mkdirp) - Recursively mkdir, like `mkdir -p`.
  - [dir-compare](https://github.com/gliviu/dir-compare) - Node JS directory compare.
  - [folder-hash](https://github.com/marc136/node-folder-hash) - Create a hash checksum over a folder or a file.
  - [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`.

- Copy
  - [ncp](https://github.com/AvianFlu/ncp) - Asynchronous recursive file copying with Node.js.
  - [cpy](https://github.com/sindresorhus/cpy) - Copy files.

- Delete
  - [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like rm -rf.
  - [del](https://github.com/sindresorhus/del) - Delete files and directories.

- Temporary
  - [temp](https://github.com/bruce/node-temp) - Temporary File, Directory, and Stream support for Node.js.
  - [tempy](https://github.com/sindresorhus/tempy) - Get a random temporary file or directory path. 302
  - [temp-dir](https://github.com/sindresorhus/temp-dir) - Get the real path of the system temp directory.

- Watch
  - [chokidar](https://github.com/paulmillr/chokidar) - Minimal and efficient cross-platform file watching library.
  - [watchpack](https://github.com/webpack/watchpack) - Wrapper library for directory and file watching.

- Glob
  - [glob](https://github.com/isaacs/node-glob) - Glob functionality for node.js.
  - [globby](https://github.com/sindresorhus/globby) - Based on fast-glob but adds a bunch of useful features.
  - [fast-glob](https://github.com/mrmlnc/fast-glob) - Very fast and efficient glob library for Node.js.
  - [node-sync-glob](https://github.com/AndyOGo/node-sync-glob) - Synchronize files and folders locally by glob patterns, watch option included.

### Parsing

- Markdown
  - [marked](https://github.com/markedjs/marked) - A markdown parser and compiler. Built for speed.
  - [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins.
  - [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins.
  - [turndown](https://www.npmjs.com/package/turndown) - An HTML to Markdown converter written in JavaScript.

- CSV
  - [PapaParse](https://github.com/mholt/PapaParse) - Fast and powerful CSV (delimited text) parser that gracefully handles large files and malformed input.
  - [node-csv](https://github.com/adaltas/node-csv) - Full featured CSV parser with simple api and tested against large datasets.
  - [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else.
  - [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above.

- YAML
  - [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser.
  - [yaml](https://github.com/eemeli/yaml) - JavaScript parser and stringifier for YAML.

- XML
  - [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.
  - [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Validate and parse XML.
  - [xmlbuilder](https://github.com/oozcitak/xmlbuilder-js) - An XML builder for node.js.
  - [js2xmlparser](https://github.com/michaelkourlas/node-js2xmlparser) - Popular Node.js module for parsing JavaScript objects into XML.

- HTML
  - [htmlparser2](https://github.com/fb55/htmlparser2) - Forgiving HTML and XML parser.
  - [himalaya](https://github.com/andrejewski/himalaya) - JavaScript HTML to JSON Parser.

- CSS
  - [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier.
  - [less](https://github.com/less/less.js) - Less. The dynamic stylesheet language.

- SQL
  - [pgsql-ast-parser](https://github.com/oguimbal/pgsql-ast-parser) - Yet another simple Postgres SQL parser.
  - [dt-sql-parser](https://github.com/DTStack/dt-sql-parser) - SQL Parsers for BigData, built with antlr4.

- Plist
  - [node-bplist-parser](https://github.com/joeferner/node-bplist-parser) - Binary plist parser.

- ini
  - [ini](https://github.com/npm/ini) - An ini parser/serializer in JavaScript.

- Other
  - [readability](https://github.com/mozilla/readability) - A standalone version of the readability library used for Firefox Reader View.

### Git

- [husky](https://github.com/typicode/husky) - Modern native Git hooks made easy 🐶 woof!
- [nodegit](https://github.com/nodegit/nodegit) - Node bindings to the libgit2 project.
- [simple-git](https://github.com/steveukx/git-js) - A light weight interface for running git commands in any node.js application.
- [gitgraph-node](https://github.com/nicoespeon/gitgraph.js/tree/master/packages/gitgraph-node) - Draw pretty git graphs in your terminal.
- [pre-commit](https://github.com/observing/pre-commit) - Automatically installs a git pre-commit script in your git repository which runs your `npm test` on pre-commit.
- [yorkie](https://github.com/yyx990803/yorkie) -  A fork of husky, 🐶 Git hooks made easy, used in vue3.
- [git-url-parse](https://github.com/IonicaBizau/git-url-parse) - A high level git url parser for common git providers.
- [git-promise](https://github.com/piuccio/git-promise) - Simple wrapper to run any git command and process it's output using promises.
- [gittar](https://github.com/lukeed/gittar) - Download and/or Extract git repositories (GitHub, GitLab, BitBucket). Cross-platform and Offline-first.
- [parse-git-config](https://github.com/jonschlinkert/parse-git-config) - Parse `.git/config` into a JavaScript object. sync or async.
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. Using only JS.
- [giturl](https://github.com/repo-utils/giturl) - Transfer git url to web url.
- [download-git-repo](https://gitlab.com/flippidippi/download-git-repo) - Download and extract a git repository (GitHub, GitLab, Bitbucket) from node.

### Logging

- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library.
- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan.
- [signale](https://github.com/klauscfhq/signale) - Highly configurable logging utility.
- [bunyan](https://github.com/trentm/node-bunyan) - A simple and fast JSON logging module for node.js services.
- [log4js-node](https://github.com/log4js-node/log4js-node) - A logging library which different from Java log4j.
- [consola](https://github.com/nuxt/consola) - Elegant Console Logger for Node.js and Browser.
- [loglevel](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods.
- [storyboard](https://github.com/guigrpa/storyboard) - A library, plus a Chrome DevTools extension.
- [cabin](https://github.com/cabinjs/cabin) - Best JavaScript and Node.js logging service and logging npm package.
- [fancy-log](https://github.com/gulpjs/fancy-log) - Log things, prefixed with a timestamp.
- [captains-log](https://www.npmjs.com/package/captains-log) - Lightweight logger with a simple pass-through configuration for use with fancier logging librarie.

### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager.
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server.
- [forever](https://github.com/foreversd/forever) - A simple CLI tool for ensuring that a given script runs continuously.
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes.
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer.
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app.
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog.
- [current-processes](https://github.com/branneman/current-processes) - Node.js library to get a snapshot of the currently running processes, OS-agnostic.

### Linter & Formatter

- [prettier](https://github.com/prettier/prettier) - ❤Prettier is an opinionated code formatter.
- [standard](https://github.com/standard/standard) - JavaScript Style Guide, with linter & automatic code fixer.
- [eslint](https://github.com/eslint/eslint) - Find and fix problems in your JavaScript code.
- [stylelint](https://github.com/stylelint/stylelint) - Mighty, modern linter that helps you avoid errors and enforce conventions in your styles.
- [lint-staged](https://github.com/okonet/lint-staged) - Run linters on git staged files.
- [commitlint](https://github.com/conventional-changelog/commitlint) - Lint commit messages.
- [js-beautify](https://github.com/beautify-web/js-beautify) - Beautifier for javascript.
- [xo](https://github.com/xojs/xo) - JavaScript/TypeScript linter (ESLint wrapper) with great defaults
- [markdownlint](https://github.com/DavidAnson/markdownlint) - A Node.js style checker and lint tool for Markdown/CommonMark files.
- [textlint](https://github.com/textlint/textlint) - The pluggable natural language linter for text and markdown.
- [pretty-quick](https://github.com/azz/pretty-quick) - ⚡ Get Pretty Quick.

### Configuration Tools

- [node-config](https://github.com/lorenwest/node-config) - Node.js Application Configuration.
- [nconf](https://github.com/indexzero/nconf) - Hierarchical node.js configuration with files, environment variables, command-line arguments, and atomic object merging.
- [convict](https://github.com/mozilla/node-convict/tree/master/packages/convict) - Convict expands on the standard pattern of configuring node.js applications in a way that is more robust and accessible to collaborators.
- [rc](https://github.com/dominictarr/rc) - The non-configurable configuration loader for lazy people.

### Build Tools

- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser.
- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler.
- [gulp](https://github.com/gulpjs/gulp) - Streaming and fast build system that favors code over config.
- [esbuild](https://github.com/evanw/esbuild) - An extremely fast JavaScript bundler and minifier.
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler.
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable.
- [Grunt](https://github.com/gruntjs/grunt) - JavaScript Task Runner
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support.
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.

- ESM
  - [Vite](https://github.com/vitejs/vite) - Next Generation Frontend Tooling.
  - [snowpack](https://github.com/snowpackjs/snowpack) - ESM-powered frontend build tool. Instant, lightweight, unbundled development.

### Templating

- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml.
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript.
- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags.
- [art-template](https://github.com/aui/art-template) - High performance JavaScript templating engine.
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired).
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language.
- [hogan.js](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language.
- [doT](https://github.com/olado/doT) - Fastest + concise javascript template engine for nodejs and browsers. Partials, custom delimiters and more.
- [jsrender](https://github.com/BorisMoore/jsrender) - A lightweight, powerful and highly extensible templating engine. In the browser or on Node.js, with or without jQuery.
- [Twig.js](https://github.com/twigjs/twig.js) - JS implementation of the Twig Templating Language.
- [hbs](https://github.com/pillarjs/hbs) - Express view engine wrapper for Handlebars.
- [Juicer](https://github.com/PaulGuo/Juicer) - A Lightweight JavaScript Template Engine.
- [tempo](https://github.com/twigkit/tempo) - Tempo is an easy, intuitive JavaScript rendering engine that enables you to craft data templates in pure HTML.
- [xtemplate](https://github.com/xtemplate/xtemplate) - High Speed, eXtensible Template Engine lib on browser and nodejs. support async control, inheritance, include, logic expression, custom function and more.

### Web Frameworks

- [Express](https://github.com/expressjs/express) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps.
  - [blitz](https://github.com/blitz-js/blitz) - ⚡️The Fullstack React Framework — built on Next.js.
- [Meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps.
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps. *(You might like [awesome-nestjs](https://github.com/juliandavidmr/awesome-nestjs))*
- [Koa](https://github.com/koajs/koa) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [sails](https://github.com/balderdashy/sails) - Realtime MVC Framework for Node.js.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework.
- [Hapi](https://github.com/hapijs/hapi) - Framework for building applications and services.
- [Egg](https://github.com/eggjs/egg) - Born to build better enterprise frameworks and apps with Node.js & Koa.
- [Feathers](https://github.com/feathersjs/feathers) - Microservice framework built in the spirit of Express.
- [LoopBack](https://github.com/strongloop/loopback-next) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Restify](https://github.com/restify/node-restify) - Enables you to build correct REST web services.
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API.
- [Midway](https://github.com/midwayjs/midway) - A Node.js framework for building Serverless services, traditional server-side applications, microservices, and small programs.
- [total.js](https://github.com/totaljs/framework) - A framework for Node.js platfrom written in pure JavaScript similar to PHP's Laravel or Python's Django or ASP.NET MVC
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach.
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - Modern framework for creating GraphQL APIs with TypeScript, using classes and decorators.
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices.
- [beidou](https://github.com/alibaba/beidou) - Isomorphic framework for server-rendered React apps.
- [Marble.js](https://github.com/marblejs/marble) - Functional reactive framework for building server-side apps, based on TypeScript and RxJS.
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients.
- [lad](https://github.com/ladjs/lad) - The best Node.js framework. Made by a former Express TC and Koa team member.
- [Tinyhttp](https://github.com/talentlessguy/tinyhttp) - Modern and fast Express-like web framework.
- [daruk](https://github.com/darukjs/daruk) - A node.js web framework based on typescript.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io).
- [restana](https://github.com/BackendStack21/restana) - Super fast and minimalist framework for building REST micro-services.
- [CabloyJS](https://github.com/zhennann/Cabloy) - A Node.js full-stack framework with workflow engine, based on koa + egg + vue + framework7.
- [malagu](https://github.com/cellbang/malagu) - Malagu is a serverless First, scalable and componentized application framework developed by TypeScript.
- [Zeronode](https://github.com/sfast/zeronode) - Minimal building block for reliable and fault-tolerant microservices.

### Content management systems (CMS)

- [Ghost](https://github.com/TryGhost/Ghost) - The headless Node.js CMS for professional publishing.
- [Strapi](https://github.com/strapi/strapi) - Content Management Framework (headless-CMS) to build powerful APIs.
- [KeystoneJS](https://github.com/keystonejs/keystone) - CMS and web application platform built on Express and MongoDB.
- [AdminBro](https://github.com/SoftwareBrothers/admin-bro) - Auto-generated admin panel with CRUD for all your resources.
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.
- [Tipe](https://github.com/tipeio/tipe) - Next Generation API-first CMS for developers. Generate an API-first CMS from a GraphQL schema with offline prototyping and an inline editor.
- [Factor](https://github.com/fiction-com/factor) - Vue.js dashboard framework and headless CMS.

### Static Site Generator & Blogging

- [gatsby](https://github.com/gatsbyjs/gatsby) - Build blazing fast, modern apps and websites with React.
- [hexo](https://github.com/hexojs/hexo) - A fast, simple & powerful blog framework, powered by Node.js.
- [vuepress](https://github.com/vuejs/vuepress) - Minimalistic Vue-powered static site generator.
- [netlify-cms](https://github.com/netlify/netlify-cms) - A Git-based CMS for Static Site Generators.
- [react-static](https://github.com/react-static/react-static) - A progressive static site generator for React.
- [gridsome](https://github.com/gridsome/gridsome) - The Jamstack framework for Vue.js.
- [vitepress](https://github.com/vuejs/vitepress) - Vite & Vue powered static site generator.
- [scully](https://github.com/scullyio/scully) - The Static Site Generator for Angular apps.

### Documentation

- [Docusaurus](https://github.com/facebook/docusaurus) - Documentation website generator that leverages React and Markdown, and comes with translation and versioning features.
- [docsify](https://github.com/docsifyjs/docsify) - 🃏 A magical documentation site generator.
- [JSDoc](https://github.com/jsdoc3/jsdoc) - API documentation generator similar to JavaDoc or PHPDoc.
- [documentation.js](https://github.com/documentationjs/documentation) - API documentation generator with support for ES2015+ and flow annotation.
- [Docco](https://github.com/jashkenas/docco) - Documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [docute](https://github.com/egoist/docute) - Effortless documentation, done right.
- [ESDoc](https://github.com/esdoc/esdoc) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage.

### Desktop Apps

- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))*
- [nw.js](https://github.com/nwjs/nw.js) - Call all Node.js modules directly from DOM/WebWorker and enable a new way of writing applications with all Web technologies.

### Real-time

- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication.
- [ws](https://github.com/websockets/ws) - Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js.
- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library.
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP.
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol.
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
- [engine.io](https://github.com/socketio/engine.io) - The implementation of transport-based cross-browser/cross-device bi-directional communication layer for Socket.IO.
- [SockJS-node](https://github.com/sockjs/sockjs-node) - WebSocket emulation - Node.js server.
- [Aedes](https://github.com/mcollina/aedes) - Barebone MQTT server that can run on any stream server.
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets.
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - Scalable real-time microservice framework.
- [isomorphic-ws](https://github.com/heineiuo/isomorphic-ws) - Isomorphic implementation of WebSocket.
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework.

### Job Queues

- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue.
- [amqp](https://github.com/squaremo/amqp.node)- AMQP 0-9-1 library and client for Node.JS.
- [kafka-node]( https://github.com/SOHU-Co/kafka-node)- Node.js client for Apache Kafka 0.8 and later.
- [bee-queue](https://github.com/bee-queue/bee-queue) - High-performance Redis-backed job queue.
  - [arena](https://github.com/bee-queue/arena) - An interactive UI dashboard for Bee Queue.
- [kafkajs](https://github.com/tulios/kafkajs) - A modern Apache Kafka client for node.js.
- [rsmq](https://github.com/smrchy/rsmq) - Redis-backed message queue.
- [sqs-consumer](https://github.com/bbc/sqs-consumer) - Build Amazon Simple Queue Service (SQS) based apps without the boilerplate.
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue.
- [better-queue](https://github.com/diamondio/better-queue) - Simple and efficient job queue when you cannot use Redis.
- [RedisSMQ](https://github.com/weyoss/redis-smq) - Simple high-performance Redis message queue with real-time monitoring.
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control.

### Job Scheduling

- [node-schedule](https://github.com/node-schedule/node-schedule) - A cron-like and not-cron-like job scheduler for Node.
- [agenda](https://github.com/agenda/agenda) - Lightweight job scheduling for Node.js.
- [node-cron](https://github.com/kelektiv/node-cron) - A tool that allows you to execute something on a schedule.
- [cron-parser](https://github.com/harrisiirak/cron-parser) - Node.js library for parsing crontab instructions.

### Debugging

- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [ndb](https://github.com/GoogleChromeLabs/ndb) - Improved debugging experience, enabled by Chrome DevTools.
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility.
- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box.
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why?
- [llnode](https://github.com/nodejs/llnode) - Post-mortem analysis tool which allows you to inspect objects and get insights from a crashed Node.js process.
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function.
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables.
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies.
- [NiM](https://github.com/june07/nim) - Manages DevTools debugging workflow.
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals.
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams.

### Profiling/Analysis

- [Clinic.js](https://github.com/clinicjs/node-clinic) - Clinic.js diagnoses your Node.js performance issues.
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling.
- [node-heapdump](https://github.com/bnoordhuis/node-heapdump) - Make a dump of the V8 heap for later inspection.
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests.
- [v8-profiler](https://github.com/node-inspector/v8-profiler) - Node bindings for the v8 profiler.
- [node-memwatch](https://github.com/marcominetti/node-memwatch) - A NodeJS library to keep an eye on your memory usage, and discover and isolate leaks.
- [v8-analytics](https://github.com/hyj1991/v8-analytics) - V8 engine's cpu & heap-memory analytics.
- [thetool](https://github.com/sfninja/thetool) - Capture different CPU, memory, and other profiles for your app in Chrome DevTools friendly format.
- [flamegraph](https://github.com/thlorenz/flamegraph) - Generates flamegraphs with Node.js or in the browser.
- [v8-profiler-next](https://github.com/hyj1991/v8-profiler-next) - Node bindings for the v8 profiler.
- [cpu-memory-monitor](https://github.com/nswbmw/cpu-memory-monitor) - CPU & Memory Monitor, auto dump.

### Application Performance Monitoring (APM)

- Solution
  - [easy-monitor](https://github.com/hyj1991/easy-monitor) - Enterprise-level Node.js application performance monitoring and online fault location solutions.
  - [webfunny_monitor](https://github.com/a597873885/webfunny_monitor) - Webfunny is a lightweight front-end monitoring system and webfunny is also a front-end performance monitoring system. It monitors front-end logs and analyzes front-end health status in real time.

- Middleware
  - [swagger-stats](https://github.com/slanatech/swagger-stats) - Trace API calls and monitor API performance, health, and usage metrics.

- Agent
  - [prom-client](https://github.com/siimon/prom-client) - Prometheus client for node.js.
  - [apm-agent-nodejs](https://github.com/elastic/apm-agent-nodejs) - Elastic APM Node.js Agent.
  - [skywalking-nodejs](https://github.com/apache/skywalking-nodejs) - The NodeJS agent for Apache SkyWalking.

### Forum

- [NodeBB](https://github.com/NodeBB/NodeBB) - Node.js based forum software built for the modern web
- [nodeclub](https://github.com/cnodejs/nodeclub/) - A forum software based on Node.js and MongoDB.

### Database

- Drivers
  - [MySQL](https://github.com/mysqljs/mysql) - A pure node.js JavaScript Client implementing the MySQL protocol.
  - [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client for node.js.
  - [MongoDB](https://github.com/mongodb/node-mongodb-native) - The Official MongoDB Node.js Driver.
  - [ioredis](https://github.com/luin/ioredis) - A robust, performance-focused and full-featured Redis client for Node.js.
  - [LevelUP](https://github.com/Level/levelup) - A wrapper for abstract-leveldown compliant stores, for Node.js and browsers.
  - [couchdb-nano](https://github.com/apache/couchdb-nano) - Nano: The official Apache CouchDB library for Node.js.
  - [Couchbase](https://github.com/couchbase/couchnode) - Couchbase Node.js Client Library (Official).
  - [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Node.js client for the Aerospike database.

- ODM / ORM
  - [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL, and more.
  - [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more.
  - [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling.
    - [typegoose](https://github.com/typegoose/typegoose) - Typegoose - Define Mongoose models using TypeScript classes.
  - [Prisma](https://github.com/prisma/prisma) - Modern database access (ORM alternative). Auto-generated and type-safe query builder in TypeScript. Supports PostgreSQL, MySQL & SQLite.
  - [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
  - [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex.
  - [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.
  - [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises.
  - [MikroORM](https://github.com/mikro-orm/mikro-orm) - TypeScript ORM based on Data Mapper, Unit of Work and Identity Map patterns. Supports MongoDB, PostgreSQL, MySQL and SQLite.
  - [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool.
  - [slonik](https://github.com/gajus/slonik) - PostgreSQL client with strict types, detailed logging and assertions.
  - [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord.

- Query builder
  - [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.

- SQL
  - [sqlstring](https://github.com/mysqljs/sqlstring) - Simple SQL escape and format for MySQL.

- Other
  - [Lowdb](https://github.com/typicode/lowdb) - Tiny local JSON database for small projects (supports Node, Electron and the browser).
  - [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent or in memory database for Node.js, nw.js, Electron and browsers.
  - [Keyv](https://github.com/lukechilds/keyv) - Simple key-value storage with support for multiple backends.
  - [pg-mem](https://github.com/oguimbal/pg-mem) - In-memory PostgreSQL instance.
  - [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - Populate MongoDB databases with JavaScript and JSON files.
  - [@databases](https://github.com/ForbesLindesay/atdatabases) - Query PostgreSQL, MySQL and SQLite3 with plain SQL without risking SQL injection.
  - [Finale](https://github.com/tommybananas/finale) - RESTful endpoint generator for your Sequelize models.
  - [database-js](https://github.com/mlaanderson/database-js) - Wrapper for multiple databases with a JDBC-like connection.

### Cache

- [lru-cache](https://github.com/isaacs/node-lru-cache) - A cache object that deletes the least-recently-used items.
- [node-cache](https://github.com/node-cache/node-cache) - A node internal (in-memory) caching module.
- [memcached](https://github.com/3rd-Eden/memcached) - A fully featured Memcached client build on top of Node.js. Build with scaling in mind so it will support Memcached clusters and consistent hashing.
- [node-cache-manager](https://github.com/BryanDonovan/node-cache-manager) - Cache module for Node.JS.
- [hashlru](https://github.com/dominictarr/hashlru) - Simpler, faster LRU cache algorithm.
- [flat-cache](https://github.com/royriojas/flat-cache) - A stupidly simple key/value storage using files to persist the data.
- [ylru](https://github.com/node-modules/ylru) - Add "expire", "allow set empty value" extends on hashlru.

### Serverless

- [serverless](https://github.com/serverless/serverless) - Serverless Framework – Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more!
- [@midway/faas](https://github.com/midwayjs/midway/tree/2.x/packages/faas) - Midway FaaS is the Serverless framework used to build Node.js cloud functions.
- [malagu](https://github.com/cellbang/malagu) - Malagu is a Serverless First, componentized, platform-independent progressive application framework based on TypeScript.

### Automation & RPA

- [puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome Node.js API.
- [playwright](https://github.com/microsoft/playwright) - Automate Chromium, Firefox and WebKit with a single API.
- [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless Browser.
- [appium](https://github.com/appium/appium) - Automation for iOS, Android, and Windows Apps.
- [robotjs](https://github.com/octalmage/robotjs) - Node.js Desktop Automation.
- [nut.js](https://github.com/nut-tree/nut.js) - Native UI testing / controlling with node.

### Testing

- Assertion
  - [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
  - [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface.
  - [expect.js](https://github.com/Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser.
  - [should.js](https://github.com/shouldjs/should.js) - BDD style assertions for node.js.
  - [better-assert](https://github.com/tj/better-assert) - C-style assert() for nodejs, reporting the expression string as the error message.
  - [http-assert](https://github.com/jshttp/http-assert) - Assert with status codes.

- Faker Generator
  - [faker.js](https://github.com/marak/Faker.js/) - Generate massive amounts of realistic fake data in Node.js and the browser.
  - [casual](https://github.com/boo1ean/casual) - Fake data generator for javascript.
  - [fony](https://github.com/captainsafia/fony) - A simple command line tool for generating fake data from a template string.

- Mock
  - [Mock.js](https://github.com/nuysoft/Mock) - A simulation data generator.
  - [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations.
  - [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks.
  - [easy-mock](https://github.com/easy-mock/easy-mock) - A persistent service that generates mock data quickly and provids visualization view.
  - [mm](https://github.com/node-modules/mm) - An simple but flexible mock(or say stub) package, mock mate.
  - [smoke](https://github.com/sinedied/smoke) - 💨 Simple yet powerful file-based mock server with recording abilities.

- End-to-end Testing / Automated UI
  - [nightwatch](https://github.com/nightwatchjs/nightwatch) - End-to-end testing framework written in Node.js and using the Webdriver API.
  - [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - End 2 End Testing Framework for NodeJS.

- Testing Framework
  - [jest](https://github.com/facebook/jest) - Delightful JavaScript Testing.
  - [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser.
  - [ava](https://github.com/avajs/ava) - Node.js test runner that lets you develop with confidence 🚀.
  - [jasmine](https://github.com/jasmine/jasmine) - Simple JavaScript testing framework for browsers and node.js.
  - [supertest](https://github.com/visionmedia/supertest) - Super-agent driven library for testing node.js HTTP servers using a fluent API.
  - [node-tap](https://github.com/tapjs/node-tap) - Test Anything Protocol tools for node.

- Coverage
  - [nyc](https://github.com/istanbuljs/nyc) - The Istanbul command line interface.
  - [node-coveralls](https://github.com/nickmerwin/node-coveralls) - Coveralls.io support for Node.js. Get the great coverage reporting of coveralls.io and add a cool coverage button (like the one above) to your README.
  - [codecov](https://github.com/codecov/codecov-node) - Global coverage report uploader for Codecov in NodeJS.

- Benchmarking
  - [Benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking library that supports high-resolution timers and returns statistically significant results.
  - [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking.
  - [benny](https://github.com/caderek/benny) - A dead simple benchmarking framework for JS/TS libs.
  - [node-wrk](https://github.com/sidorares/node-wrk) - Wrk load testing tool node wrapper.

- Solution
  - [macaca](https://github.com/alibaba/macaca) - Automation solution for multi-platform.

### Office

- Excel
  - [sheetjs](https://github.com/SheetJS/sheetjs) - Spreadsheet Data Toolkit.
  - [exceljs](https://github.com/exceljs/exceljs) - Excel Workbook Manager.
  - [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Excel XLSX parser/generator written in JavaScript with Node.js and browser support.

- Word
  - [officegen](https://github.com/Ziv-Barber/officegen) - Standalone Office Open XML files (Microsoft Office 2007 and later) generator for Word (docx), PowerPoint (pptx) and Excell (xlsx) in javascript. The output is a stream.
  - [Mammoth](https://github.com/mwilliamson/mammoth.js) - Convert Word documents (.docx files) to HTML.
  - [docx](https://github.com/dolanmiu/docx) - Easily generate .docx files with JS/TS with a nice declarative API. Works for Node and on the Browser.

- PDF
  - [jsPDF](https://github.com/MrRio/jsPDF) - A library to generate PDFs in JavaScript.
  - [PDFKit](https://github.com/foliojs/pdfkit) - JavaScript PDF generation library for Node and the browser.
  - [percollate](https://github.com/danburzo/percollate) - A command-line tool to turn web pages into beautiful, readable PDF, EPUB, or HTML docs.
  - [pdf-lib](https://github.com/Hopding/pdf-lib) - Create and modify PDF documents in any JavaScript environment.
  - [pdf2json](https://github.com/modesty/pdf2json) - A PDF file parser that converts PDF binaries to text based JSON.

- PPT
  - [nodeppt](https://github.com/ksky521/nodeppt) - This is probably the best web presentation tool so far!

### OS Identification

- [systeminformation](https://github.com/sebhildebrandt/systeminformation) - Hardware/software system information.
- [is-wsl](https://github.com/sindresorhus/is-wsl) - Detect whether current platform is WSL (Windows Subsystem for Linux).
- [os-name](https://github.com/sindresorhus/os-name) - Get the name of the current operating system.
- [getos](https://github.com/retrohacker/getos) - Retrieve the current OS, including Linux distribution.
- [is-windows](https://github.com/jonschlinkert/is-windows) - Detect whether the current platform is Windows.

### Compression / Decompression

- [jszip](https://github.com/Stuk/jszip) - Create, read and edit .zip files with Javascript.
- [adm-zip](https://github.com/cthackers/adm-zip) - Create, read and edit .zip files with Javascript.
- [node-tar](https://github.com/npm/node-tar) - Fast and full-featured Tar for Node.js.
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Yet another unzip library for node.
- [unzipper](https://github.com/ZJONSSON/node-unzipper) - Node.js cross-platform unzip using streams.
- [tar-fs](https://github.com/mafintosh/tar-fs) - Tar-fs allows you to pack directories into tarballs and extract tarballs into directories.
- [extract-zip](https://github.com/maxogden/extract-zip) - Zip extraction written in pure JavaScript. Extracts a zip into a directory.
- [compressing](https://github.com/node-modules/compressing) - Everything you need for compressing and uncompressing.
- [yazl](https://github.com/thejoshwolfe/yazl) - Yet another zip library for node.
- [7zip](https://github.com/fritx/win-7zip) - 7zip Windows Package via Node.js.

###  Minifiers

- [UglifyJS](https://github.com/mishoo/UglifyJS) - JavaScript minifier.
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier.
- [babel-minify](https://github.com/babel/minify) - ES6+ aware minifier based on the Babel toolchain.
- [cssnano](https://github.com/cssnano/cssnano) - A modular minifier, built on top of the PostCSS ecosystem.
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier.
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier.
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS.

### Email

- [Nylas Mail](https://github.com/nylas/nylas-mail) - An extensible desktop mail app built on the modern web.
- [Nodemailer](https://github.com/nodemailer/nodemailer) - Send e-mails with Node.JS – easy as cake!
- [Email Templates](https://github.com/forwardemail/email-templates) - Create, preview, and send custom email templates for Node.js.
- [emailjs](https://github.com/eleith/emailjs) - Html emails and attachments to any smtp server with nodejs.
- [mjml](https://github.com/mjmlio/mjml) - Makes responsive-email easy.

### Network

- IP
  - [node-ip](https://github.com/indutny/node-ip) - IP address tools for node.js.
  - [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address - very fast!
  - [request-ip](https://github.com/pbojinov/request-ip) - A Node.js module for retrieving a request's IP address on the server.
  - [ipaddr.js](https://github.com/whitequark/ipaddr.js) - IP address manipulation library in JavaScript.
  - [internal-ip](https://github.com/sindresorhus/internal-ip) - Get your internal IP address.
  - [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address.
  - [address](https://github.com/node-modules/address) - Get current machine IP and MAC address.

- Port
  - [node-portfinder](https://github.com/http-party/node-portfinder) - A simple tool to find an open port or domain socket on the current machine.
  - [get-port](https://github.com/sindresorhus/get-port) - Get an available port.
  - [detect-port](https://github.com/node-modules/detect-port) - Node.js implementation of port detector.

- Tunnel Agent
  - [node-tunnel](https://github.com/koichik/node-tunnel) - Node HTTP/HTTPS Agents for tunneling proxies.
  - [tunnel-agent](https://github.com/request/tunnel-agent) - HTTP proxy tunneling agent. Formerly part of mikeal/request, now a standalone module.

- Other
  - [netcat](https://github.com/roccomuso/netcat) - Netcat port in pure JS.
  - [getmac](https://github.com/bevry/getmac) - Get the computer MAC address.
  - [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server.
  - [default-gateway](https://github.com/silverwind/default-gateway) - Get the default network gateway, cross-platform.

### HTTP

- Request Client
  - [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too).
  - [superagent](https://github.com/visionmedia/superagent) - HTTP request library.
  - [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module.
  - [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js.
  - [undici](https://github.com/nodejs/undici) - An HTTP/1.1 client, written from scratch for Node.js.
  - [needle](https://github.com/tomas/needle) - Nimble, streamable HTTP client for Node.js. With proxy, iconv, cookie, deflate & multipart support.
  - [urllib](https://github.com/node-modules/urllib) - Request HTTP(s) URLs in a complex world.
  - [phin](https://github.com/ethanent/phin) - Node HTTP client.
  - [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got).
  - [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities.
  - [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support.
  - [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API.
  - [flashheart](https://github.com/bbc/flashheart) - REST client.

- HTTP Server
  - [http-server](https://github.com/http-party/http-server) - A simple zero-configuration command-line http server.
  - [anywhere](https://github.com/JacksonTian/anywhere) - Running static file server anywhere.
  - [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes.
  - [json-server](https://github.com/typicode/json-server) - Get a full fake REST API with zero coding in less than 30 seconds.

- Proxy
  - [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy.
  - [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) - ⚡ The one-liner node.js http-proxy middleware for connect, express and browser-sync.
  - [https-proxy-agent](https://github.com/TooTallNate/node-https-proxy-agent) - An HTTP(s) proxy `http.Agent` implementation for HTTPS endpoints.
  - [global-agent](https://github.com/gajus/global-agent) - Global HTTP/HTTPS proxy agent that is configurable using environment variables.
  - [fast-proxy](https://github.com/fastify/fast-proxy) - Node.js framework agnostic library that enables you to forward an http request to another HTTP server. Supported protocols: HTTP, HTTPS, HTTP2.
  - [argo](https://github.com/argo/argo) - An extensible, asynchronous HTTP reverse proxy and origin server.

- Download
  - [download](https://github.com/kevva/download) - Download and extract files effortlessly.
  - [nugget](https://github.com/maxogden/nugget) - Minimalist wget clone written in node. HTTP GET files and downloads them into the current directory.

### Authentication

- [Passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication.
- [Grant](https://github.com/simov/grant) - OAuth providers for Express, Koa, Hapi, Fastify, AWS Lambda, Azure, Google Cloud, Vercel, and many more.
- [permit](https://github.com/ianstormtaylor/permit) - An unopinionated authentication library for building Node.js APIs.

### Authorization

- [CASL](https://github.com/stalniy/casl) - Isomorphic authorization for UI and API.
- [node-casbin](https://github.com/casbin/node-casbin) - Authorization library that supports access control models like ACL, RBAC and ABAC.
- [jose](https://github.com/panva/jose) - Universal "JSON Web Almost Everything" - JWA, JWS, JWE, JWT, JWK with no dependencies.
- [basic-auth](https://github.com/jshttp/basic-auth) - Generic basic auth Authorization header field parser.

### Distribute

- [node-zookeeper-client](https://github.com/alexguan/node-zookeeper-client) - A pure Javascript ZooKeeper client for Node.js.

### Serialization

- [protobuf](https://github.com/protobufjs/protobuf.js) - Implementation of Protocol Buffers.
- [snappy](https://github.com/kesla/node-snappy) - Native bindings for Google's Snappy compression library.
- [hessian.js](https://github.com/node-modules/hessian.js) - JavaScript hessian binary web service protocol, support communicate with java.
- [compactr](https://github.com/compactr/compactr.js) - Implementation of the Compactr protocol.

### RPC

- [grpc-js](https://github.com/grpc/grpc-node/tree/master/packages/grpc-js) - Pure JavaScript gRPC Client.
- [jayson](https://github.com/tedeh/jayson) - Jayson is a simple but featureful JSON-RPC 2.0/1.0 client and server for node.js.
- [sofa-rpc-node](https://github.com/sofastack/sofa-rpc-node) - SOFARPC Node is a high-performance, high-extensibility, production-level Nodejs RPC framework.

### Server-side DOM

- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.
- [jsdom](https://github.com/jsdom/jsdom) - A JavaScript implementation of various web standards, for use with Node.js.
- [domino](https://github.com/fgnass/domino) - Server-side DOM implementation based on Mozilla's dom.js.

### Crawler

- [node-crawler](https://github.com/bda-research/node-crawler) - Web Crawler/Spider for NodeJS + server-side jQuery.
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraper with pagination and crawler support.
- [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Headless Chrome crawls with jQuery support.
- [node-osmosis](https://github.com/rchipka/node-osmosis) - HTML/XML parser and web scraper for Node.js.
- [scrape-it](https://github.com/IonicaBizau/scrape-it) - A Node.js scraper for humans.
- [scraperjs](https://github.com/ruipgil/scraperjs) - A complete and versatile web scraper.
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler.
- [web-scraper-chrome-extension](https://github.com/martinsbalodis/web-scraper-chrome-extension) - Web data extraction tool implemented as chrome extension.
- [webster](https://github.com/zhuyingda/webster) - A reliable web crawling framework which can scrape ajax and js rendered content in a web page.
- [supercrawler](https://github.com/brendonboshell/supercrawler) - Define custom handlers to parse content. Obeys robots.txt, rate limits and concurrency limits.
- [Squidwarc](https://github.com/n0tan3rd/squidwarc) - High fidelity, user scriptable, archival crawler that uses Chrome or Chromium with or without a head.
- [js-crawler](https://github.com/antivanov/js-crawler) - Web crawler for Node.JS, both HTTP and HTTPS are supported.

### AST

- Parser
  - [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript parser.
  - [antlr](https://github.com/antlr/antlr4) - ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files.
  - [acorn](https://github.com/acornjs/acorn/tree/master/acorn) - Small, fast, JavaScript-based JavaScript parser.
  - [esprima](https://github.com/jquery/esprima) - High performance, standard-compliant ECMAScript parser.
  - [recast](https://github.com/benjamn/recast) - JavaScript syntax tree transformer, nondestructive pretty-printer, and automatic source map generator.
  - [nearley](https://github.com/kach/nearley) - Simple, fast, powerful parser toolkit for JavaScript.
  - [espree](https://github.com/eslint/espree) - Esprima-compatible JavaScript parser.
  - [csstree](https://github.com/csstree/csstree) - Tool set for CSS including fast detailed parser, walker, generator and lexer based on W3C specs and browser implementations.
  - [es-module-lexer](https://github.com/guybedford/es-module-lexer) - Low-overhead lexer dedicated to ES module parsing for fast analysis.

- Traversal
  - [acorn-walker](https://github.com/acornjs/acorn/tree/master/acorn-walk) - Small, fast, JavaScript-based JavaScript parser.
  - [estraverse](https://github.com/estools/estraverse) - ECMAScript JS AST traversal functions.

- Codegen
  - [escodegen](https://github.com/estools/escodegen) - ECMAScript code generator.
  - [astring](https://github.com/davidbonnet/astring) - 🌳 Tiny and fast JavaScript code generator from an ESTree-compliant AST.

- JavaScript interpreter
  - [JS-Interpreter](https://github.com/NeilFraser/JS-Interpreter) - A sandboxed JavaScript interpreter in JavaScript.
  - [jsjs](https://github.com/bramblex/jsjs) - A simple JavaScript interpreter.
  - [sval](https://github.com/Siubaak/sval) - A javascript interpreter written in javascript.

- Other
  - [astexplorer](https://github.com/fkling/astexplorer) - Web tool to explore the ASTs generated by various parsers.
  - [periscopic](https://github.com/Rich-Harris/periscopic) - Utility for analyzing scopes belonging to an ESTree-compliant AST.
  - [estree-walker](https://github.com/Rich-Harris/estree-walker) - Traverse an ESTree-compliant AST.

### WebAssembly

- [webassembly](https://github.com/dcodeIO/webassembly) - A minimal toolkit and runtime to produce and run WebAssembly modules.

### Design To Code（D2C）
- [psd.js](https://github.com/meltingice/psd.js) - A Photoshop PSD file parser for NodeJS and browsers.

### Sandbox

- [vm2](https://github.com/patriksimek/vm2) - Advanced vm/sandbox for Node.js.
- [sandbox](https://github.com/gf3/sandbox) - A nifty javascript sandbox for node.js.
- [safeify](https://github.com/Houfeng/safeify) - Safe sandbox that can be used to execute untrusted code.

### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework.
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing.
- [usb](https://github.com/nonolith/node-usb) - USB library.
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection.
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi.
- [node-escpos](https://github.com/song940/node-escpos) - ESC/POS Printer driver for node.
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access.
- [gps](https://github.com/infusion/GPS.js) - NMEA parser for handling GPS receivers.
- [node-bluetooth](https://github.com/song940/node-bluetooth) - Bluetooth serial port communication for Node.js.
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access.

### IoT

- [zetta](https://github.com/zettajs/zetta) - An API-first, open source software platform for the Internet of Things.
- [iot-nodejs](https://github.com/ibm-watson-iot/iot-nodejs) - Client libraries and samples for connecting to IBM Watson IoT using nodejs.

### Machine learning & Neural networks

- [tfjs](https://github.com/tensorflow/tfjs) - A WebGL accelerated JavaScript library for training and deploying ML models.
- [netron](https://github.com/lutzroeder/netron) - Visualizer for neural network, deep learning, and machine learning models.
- [brain.js](https://github.com/BrainJS/brain.js) - GPU accelerated Neural networks in JavaScript for Browsers and Node.js.
- [pipcook](https://github.com/alibaba/pipcook) - Machine learning platform for Web developers.
- [onnxjs](https://github.com/microsoft/onnxjs) - ONNX.js: run ONNX models using JavaScript.
- [tensorflow-nodejs](https://github.com/yorkie/tensorflow-nodejs) - TensorFlow Node.js provides idiomatic JavaScript language bindings and a high layer API for Node.js users.

### Natural language processing

- [compromise](https://github.com/spencermountain/compromise) - Modest natural-language processing.
- [natural](https://github.com/NaturalNode/natural) - Natural language facility.
- [nlp.js](https://github.com/axa-group/nlp.js) - Building bots, with entity extraction, sentiment analysis, automatic language identify, and more.
- [franc](https://github.com/wooorm/franc) - Detect the language of text.
- [sentiment](https://github.com/thisandagain/sentiment) - AFINN-based sentiment analysis for Node.js.
- [retext](https://github.com/wooorm/retext) - An extensible natural language system.
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm.

### OCR

- [tesseract.js](https://github.com/naptha/tesseract.js) - Pure Javascript OCR for more than 100 Languages.
- [Parsr](https://github.com/axa-group/Parsr) - Transforms PDF, Documents and Images into Enriched Structured Data.

### Bitcoin

- [GitTorrent](https://github.com/cjb/GitTorrent) - A decentralization of GitHub using BitTorrent and Bitcoin.
- [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) - A javascript Bitcoin library for node.js and browsers.
- [bitcore](https://github.com/bitpay/bitcore) - A full stack for bitcoin and blockchain-based applications.

## Project

### Lowcode

- H5/PC
  - [amis](https://github.com/baidu/amis) - LowCode Framework, Generate various pages through JSON configuration.

- H5
  - [h5-Dooring](https://github.com/MrXujiang/h5-Dooring) - H5 Page Maker, H5 Editor, LowCode. Make H5 as easy as building blocks.
  - [luban-h5](https://github.com/ly525/luban-h5) - Web design tool || mobile page builder/editor || mini webflow for mobile page.
  - [gods-pen](https://github.com/ymm-tech/gods-pen) - A mobile page builder/editor, similar with amolink.

- PC
  - [pc-Dooring](https://github.com/MrXujiang/pc-Dooring) - LowCode, PC Page Maker, PC Editor. Make PC as easy as building blocks.

- Logical Arrangement
  - [node-red](https://github.com/node-red/node-red) - Low-code programming for event-driven applications.
  - [imove](https://github.com/ykfe/imove) - Move your mouse, generate code from flow chart.
