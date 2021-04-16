English | [简体中文](./README-zh-CN.md)

## Contents

- [Contents](#contents)
- [Official](#official)
- [Packages](#packages)
  - [Date & Time](#date--time)
  - [Data validation](#data-validation)
  - [Command-line utilities](#command-line-utilities)
  - [Filesystem](#filesystem)
  - [Git](#git)
  - [Logging](#logging)
  - [URL](#url)
  - [Build tools](#build-tools)
  - [Templating](#templating)
  - [Web Frameworks](#web-frameworks)
  - [Static Site Generator & blogging](#static-site-generator--blogging)
  - [Forum](#forum)
  - [Database](#database)
  - [Office](#office)
  - [Email](#email)
  - [Crawler](#crawler)
  - [AST](#ast)
  - [Automation & RPA](#automation--rpa)

## Official

- [Website](https://nodejs.org)
- [Documentation](https://nodejs.org/dist/latest/docs/api/)
- [Repository](https://github.com/nodejs/node)

## Packages

### Date & Time
- [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript.
- [dayjs](https://github.com/iamkun/dayjs) - Day.js 2KB immutable date-time library alternative to Moment.js with the same modern API.
- [date-fns](https://github.com/date-fns/date-fns) - Modern JavaScript date utility library.
- [luxon](https://github.com/moment/luxon) - Library for working with dates and times.
- [ms](https://github.com/vercel/ms) - Tiny millisecond conversion utility.
- [dateformat](https://github.com/felixge/node-dateformat) - A node.js package for Steven Levithan's excellent dateFormat() function.

### Data validation
- [validator.js](https://github.com/validatorjs/validator.js) - A library of string validators and sanitizers.
- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [class-validator](https://github.com/typestack/class-validator) - Decorator-based property validation for classes.
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON schema Validator. Supports JSON Schema draft-04/06/07/2019-09/2020-12 and JSON Type Definition (RFC8927).
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - Simple and composable way to validate data in JavaScript (and TypeScript).
- [v8n](https://github.com/imbrn/v8n) - JavaScript fluent validation library
- [forgJs](https://github.com/oussamahamdaoui/forgJs) - Javascript lightweight object validator.
- [validatorjs](https://github.com/mikeerickson/validatorjs) - Data validation library in JavaScript for the browser and Node.js, inspired by Laravel's Validator.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast.
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for JavaScript, Node and Express.
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation.

### Command-line utilities
- [Commander.js](https://github.com/tj/commander.js) - The complete solution for node.js command-line interfaces.
- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Collection of common interactive command line user interfaces.
- [yargs](https://github.com/yargs/yargs) - Collection of common interactive command line user interfaces.
- [Enquirer](https://github.com/enquirer/enquirer) - Stylish CLI prompts that are user-friendly, intuitive and easy to create.
- [minimist](https://github.com/substack/minimist) - Guts of optimist's argument parser without all the fanciful decoration.
- [progress](https://github.com/visionmedia/node-progress) - Flexible ascii progress bar for nodejs.
- [depcheck]https://github.com/depcheck/depcheck) - Check your npm module for unused dependencies.
- [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels.

### Filesystem
- [chokidar](https://github.com/paulmillr/chokidar) - Minimal and efficient cross-platform file watching library.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.
- [glob](https://github.com/isaacs/node-glob) - Glob functionality for node.js.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like rm -rf.
- [globby](https://github.com/sindresorhus/globby) - Based on fast-glob but adds a bunch of useful features.
- [fast-glob](https://github.com/mrmlnc/fast-glob) - Very fast and efficient glob library for Node.js.
- [del](https://github.com/sindresorhus/del) - Delete files and directories.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Graceful-fs functions as a drop-in replacement for the fs module, making various improvements.
- [jsonfile](https://github.com/jprichardson/node-jsonfile) - Easily read/write JSON files.
- [filesize.js](https://github.com/avoidwork/filesize.js) - Generate a human readable String describing the file size.
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like mkdir -p.
- [memfs](https://github.com/streamich/memfs) - In-memory filesystem with Node's API.
- [watchpack](https://github.com/webpack/watchpack) - Wrapper library for directory and file watching.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [mkdirp](https://github.com/isaacs/node-mkdirp) - Recursively mkdir, like `mkdir -p`.

### Git
- [nodegit](https://github.com/nodegit/nodegit) - Node bindings to the libgit2 project.
- [simple-git](https://github.com/steveukx/git-js) - A light weight interface for running git commands in any node.js application.
- [@gitgraph/node](https://github.com/nicoespeon/gitgraph.js) - Draw pretty git graphs in your terminal.
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. Using only JS.
- [download-git-repo](https://gitlab.com/flippidippi/download-git-repo) - Download and extract a git repository (GitHub, GitLab, Bitbucket) from node.

### Logging
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library.
- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan.
- [signale](https://github.com/klauscfhq/signale) - Highly configurable logging utility.
- [log4js-node](https://github.com/log4js-node/log4js-node) - A logging library which different from Java log4j.
- [consola](https://github.com/nuxt/consola) - Elegant Console Logger for Node.js and Browser.
- [storyboard](https://github.com/guigrpa/storyboard) - A library, plus a Chrome DevTools extension.
- [cabin](https://github.com/cabinjs/cabin) - Best JavaScript and Node.js logging service and logging npm package.
- [captains-log](https://www.npmjs.com/package/captains-log) - Lightweight logger with a simple pass-through configuration for use with fancier logging librarie.

### URL
- [URI.js](https://github.com/medialize/URI.js) - Javascript URL mutation library.
- [qs](https://github.com/ljharb/qs) - Querystring parser with nesting support.
- [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings.
- [url-parse](https://github.com/unshiftio/url-parse) - Small footprint URL parser that works seamlessly across Node.js and browser environments.
- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL.
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. turn strings into data or data into strings.
- [native-url](https://github.com/GoogleChromeLabs/native-url) - Node's url module implemented using the built-in URL API.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Node's url module implemented using the built-in URL API.
- [parseurl](https://github.com/pillarjs/parseurl) - Parse a url with memoization.
- [encodeurl](https://github.com/pillarjs/encodeurl) - Encode a URL to a percent-encoded form, excluding already-encoded sequences.

### Build tools
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser.
- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler.
- [gulp](https://github.com/gulpjs/gulp) - Streaming and fast build system that favors code over config.
- [Vite](https://github.com/vitejs/vite) - Next Generation Frontend Tooling
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler.
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable.
- [Grunt](https://github.com/gruntjs/grunt) - JavaScript Task Runner
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support.
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.

### Templating
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml.
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript.
- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags.
- [art-template](https://github.com/aui/art-template) - High performance JavaScript templating engine.
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired).
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language.
- [doT](https://github.com/olado/doT) - Fastest + concise javascript template engine for nodejs and browsers. Partials, custom delimiters and more.
- [Twig.js](https://github.com/twigjs/twig.js) - JS implementation of the Twig Templating Language.

### Web Frameworks
- [Express](https://github.com/expressjs/express) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps.
- [Meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps.
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps.
*(You might like [awesome-nestjs](https://github.com/juliandavidmr/awesome-nestjs))*
- [Koa](https://github.com/koajs/koa) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [sails](https://github.com/balderdashy/sails) - Realtime MVC Framework for Node.js.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework.
- [Hapi](https://github.com/hapijs/hapi) - Framework for building applications and services.
- [Egg](https://github.com/eggjs/egg) - Born to build better enterprise frameworks and apps with Node.js & Koa.
- [Feathers](https://github.com/feathersjs/feathers) - Microservice framework built in the spirit of Express.
- [LoopBack](https://github.com/strongloop/loopback) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Restify](https://github.com/restify/node-restify) - Enables you to build correct REST web services.
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API.
- [Midway](https://github.com/midwayjs/midway) - A Node.js framework for building Serverless services, traditional server-side applications, microservices, and small programs.
- [total.js](https://github.com/totaljs/framework) - A framework for Node.js platfrom written in pure JavaScript similar to PHP's Laravel or Python's Django or ASP.NET MVC
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach.
- [beidou](https://github.com/alibaba/beidou) - Isomorphic framework for server-rendered React apps.
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - Modern framework for creating GraphQL APIs with TypeScript, using classes and decorators.
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices.
- [beidou](https://github.com/alibaba/beidou) - Isomorphic framework for server-rendered React apps.
- [Marble.js](https://github.com/marblejs/marble) - Functional reactive framework for building server-side apps, based on TypeScript and RxJS.
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients.
- [lad](https://github.com/ladjs/lad) - The best Node.js framework. Made by a former Express TC and Koa team member.
- [Tinyhttp](https://github.com/talentlessguy/tinyhttp) - Modern and fast Express-like web framework.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io).
- [Zeronode](https://github.com/sfast/zeronode) - Minimal building block for reliable and fault-tolerant microservices.

### Static Site Generator & blogging
- [gatsby](https://github.com/gatsbyjs/gatsby) - Build blazing fast, modern apps and websites with React.
- [hexo](https://github.com/hexojs/hexo) - A fast, simple & powerful blog framework, powered by Node.js.
- [vuepress](https://github.com/vuejs/vuepress) - Minimalistic Vue-powered static site generator.
- [react-static](https://github.com/react-static/react-static) - A progressive static site generator for React.
- [gridsome](https://github.com/gridsome/gridsome) - The Jamstack framework for Vue.js.

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

### Office
- [sheetjs](https://github.com/SheetJS/sheetjs) - Spreadsheet Data Toolkit.
- [PDFKit](https://github.com/foliojs/pdfkit) - JavaScript PDF generation library for Node and the browser.
- [exceljs](https://github.com/exceljs/exceljs) - Excel Workbook Manager.
- [officegen](https://github.com/Ziv-Barber/officegen) - Standalone Office Open XML files (Microsoft Office 2007 and later) generator for Word (docx), PowerPoint (pptx) and Excell (xlsx) in javascript. The output is a stream.
- [Mammoth](https://github.com/mwilliamson/mammoth.js) - Convert Word documents (.docx files) to HTML.
- [docx](https://github.com/dolanmiu/docx) - Easily generate .docx files with JS/TS with a nice declarative API. Works for Node and on the Browser.
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Excel XLSX parser/generator written in JavaScript with Node.js and browser support.

### Email
- [Nylas Mail](https://github.com/nylas/nylas-mail) - An extensible desktop mail app built on the modern web.
- [Nodemailer](https://github.com/nodemailer/nodemailer) - Send e-mails with Node.JS – easy as cake!
- [Email Templates](https://github.com/forwardemail/email-templates) - Create, preview, and send custom email templates for Node.js.
- [emailjs](https://github.com/eleith/emailjs) - Html emails and attachments to any smtp server with nodejs.
- [mjml](https://github.com/mjmlio/mjml) - Makes responsive-email easy.

### Crawler
- [node-crawler](https://github.com/bda-research/node-crawler) - Web Crawler/Spider for NodeJS + server-side jQuery.
- [Headless Chrome Crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Distributed crawler powered by Headless Chrome.

### AST
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript parser.
- [antlr](https://github.com/antlr/antlr4) - ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files.
- [acorn](https://github.com/acornjs/acorn) - Small, fast, JavaScript-based JavaScript parser.
- [esprima](https://github.com/jquery/esprima) - High performance, standard-compliant ECMAScript parser.
- [astexplorer](https://github.com/fkling/astexplorer) - Web tool to explore the ASTs generated by various parsers.
- [espree](https://github.com/eslint/espree) - Esprima-compatible JavaScript parser.
- [csstree](https://github.com/csstree/csstree) - Tool set for CSS including fast detailed parser, walker, generator and lexer based on W3C specs and browser implementations.

### Automation & RPA
 - [puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome Node.js API.
 - [playwright](https://github.com/microsoft/playwright) - Automate Chromium, Firefox and WebKit with a single API.
 - [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless Browser.
 - [appium](https://github.com/appium/appium) - Automation for iOS, Android, and Windows Apps.
