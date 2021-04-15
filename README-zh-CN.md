> 该项目受 [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) 启发
>
> 原本是希望在原仓库中提供中文版，但跟该作者沟通，作者不希望添加本地化翻译增加维护工作量；且该库有很多国内用户常见的库并未收录，分类体系也不符合我的预期
>
> 故此另开分支，希望可以更好的满足国内开发者的需求。

[English](./README.md) | 简体中文

## 目录

- [目录](#目录)
- [官方资源](#官方资源)
- [NPM包](#npm包)
  - [命令行工具](#命令行工具)
  - [文件系统](#文件系统)
  - [日志](#日志)
  - [构建工具](#构建工具)
  - [Web框架](#web框架)
  - [日期 和 时间](#日期-和-时间)
  - [数据校验](#数据校验)
  - [办公软件](#办公软件)
  - [Email](#email)
  - [爬虫](#爬虫)
  - [AST](#ast)

## 官方资源

- [官网](https://nodejs.org)
- [文档](https://nodejs.org/dist/latest/docs/api/)
- [仓库](https://github.com/nodejs/node)

## NPM包

### 命令行工具
- [Commander.js](https://github.com/tj/commander.js) - Node.JS命令行界面完整解决方案。
- [chalk](https://github.com/chalk/chalk) - 命令行字符串样式美化工具。
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - 通用可交互命令行工具集合。
- [Enquirer](https://github.com/enquirer/enquirer) - 用户友好、直观且易于创建的时尚CLI提示。
- [minimist](https://github.com/substack/minimist) - 命令行参数解析引擎。
- [cac](https://github.com/cacjs/cac) - 用于构建命令行应用的强大框架。
- [log-symbols](https://github.com/sindresorhus/log-symbols) - 为不同日志级别添加色彩图标。

### 文件系统
- [chokidar](https://github.com/paulmillr/chokidar) - 最小且高效的跨平台Watch库。
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - 为 `fs` 模块提供额外方法。
- [rimraf](https://github.com/isaacs/rimraf) - 递归删除文件，类似 `rm -rf`。
- [globby](https://github.com/sindresorhus/globby) - 基于fast-glob，但添加了很多有用的特性。
- [fast-glob](https://github.com/mrmlnc/fast-glob) - 非常快速且高效的Node.js glob库。
- [del](https://github.com/sindresorhus/del) - 删除文件/文件夹。
- [make-dir](https://github.com/sindresorhus/make-dir) - 递归创建文件夹，类似 `mkdir -p`。
- [cpy](https://github.com/sindresorhus/cpy) - 文件拷贝。

### 日志
- [winston](https://github.com/winstonjs/winston) - 多传输异步日志记录库。
- [pino](https://github.com/pinojs/pino) - 受Bunyan启发的超快日志记录库。
- [signale](https://github.com/klauscfhq/signale) - 高度可配置的日志工具。
- [log4js-node](https://github.com/log4js-node/log4js-node) - 不同于Java log4j的日志记录库。
- [consola](https://github.com/nuxt/consola) - 优雅的Node.js和浏览器日志记录库。
- [storyboard](https://github.com/guigrpa/storyboard) - 一个Chrome浏览器插件，用于查看日志。
- [cabin](https://github.com/cabinjs/cabin) - 提供日志服务和NPM包。

### 构建工具
- [webpack](https://github.com/webpack/webpack) - 打包浏览器的模块和资产。
- [parcel](https://github.com/parcel-bundler/parcel) - 快速，零配置的Web应用构建工具。
- [gulp](https://github.com/gulpjs/gulp) - 流式快速构建系统，支持代码而不是配置。
- [Vite](https://github.com/vitejs/vite) - 新一代前端构建工具。
- [rollup](https://github.com/rollup/rollup) - 新一代的 ES2015 打包构建工具。
- [pkg](https://github.com/zeit/pkg) - 将Node.js项目打包成可执行文件。
- [Grunt](https://github.com/gruntjs/grunt) - JavaScript任务执行器。
- [Brunch](https://github.com/brunch/brunch) - 前端web应用程序构建工具，具有简单的声明性配置、快速的增量编译和自定的工作流。
- [FuseBox](https://github.com/fuse-box/fuse-box) - 快速构建系统，结合了webpack，JSPM和SystemJS的强大功能，并具有一流的TypeScript支持。
- [Broccoli](https://github.com/broccolijs/broccoli) - 快速、可靠的资产管道，支持固定时间重建和紧凑的构建定义。

### Web框架
- [Express](https://github.com/expressjs/express) - Web应用程序框架，为构建单页和多页以及混合Web应用程序提供了一组强大的功能。
- [Nest](https://github.com/nestjs/nest) -受Angular启发的框架，用于构建高效且可扩展的服务器端应用程序。*(你也许会喜欢 [awesome-nestjs](https://github.com/juliandavidmr/awesome-nestjs))*
- [Koa](https://github.com/koajs/koa) - 由Express背后的团队设计的框架，旨在为Web应用程序和API提供更小，更富表现力和更强大的基础。
- [Next.js](https://github.com/zeit/next.js) - React服务端渲染框架。
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Vue服务端渲染框架。
- [Meteor](https://github.com/meteor/meteor) - 超简单，无处不在的数据库，在线数据，纯Javascript Web框架。 *（你也许会喜欢 [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Fastify](https://github.com/fastify/fastify) - 快速和低开销的Web框架。
- [Hapi](https://github.com/hapijs/hapi) - 用于创建应用和服务的框架。
- [Egg](https://github.com/eggjs/egg) - 为企业级框架和应用而生。
- [Feathers](https://github.com/feathersjs/feathers) - 基于Express精神构建的微服务框架。
- [LoopBack](https://github.com/strongloop/loopback) - 用于创建REST API并轻松连接到后端数据源的强大框架。
- [Restify](https://github.com/restify/node-restify) - 使你能够构建正确的REST Web服务。
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 支持ES2015 +的框架，WebSockets，REST API。
- [Midway](https://github.com/midwayjs/midway) - 一个面向未来的云端一体 Node.js 框架。
- [AdonisJs](http://adonisjs.com) - 基于依赖注入和IoC容器的坚实基础构建的Node.js的真正MVC框架。
- [Micro](https://github.com/zeit/micro) - 具有异步方法的简约微服务框架。
- [Moleculer](https://moleculer.services) - 快速而强大的微服务框架。
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - 使用类和装饰器使用TypeScript创建GraphQL API的现代框架。
- [seneca](https://github.com/senecajs/seneca) - 编写微服务的工具包。
- [Marble.js](https://github.com/marblejs/marble) - 基于TypeScript和RxJS，用于构建服务端应用的函数响应式框架。
- [ActionHero](https://github.com/actionhero/actionhero) - 用于为TCP套接字，WebSocket和HTTP客户端制作可重用和可扩展的API的框架。
- [lad](https://github.com/ladjs/lad) - 最好的Node.js框架，由前Express和Koa团队成员创建。
- [Tinyhttp](https://github.com/talentlessguy/tinyhttp) - 类Express更现代更快的Web框架。
- [Hemera](https://github.com/hemerajs/hemera) -使用以下工具编写可靠且容错的微服务 [NATS](https://nats.io)。
- [Zeronode](https://github.com/sfast/zeronode) - 最小的构建块，可实现可靠且容错的微服务。

### 日期 和 时间
- [moment](https://github.com/moment/moment) - 解析、校验、操作和显示日期。
- [dayjs](https://github.com/iamkun/dayjs) - 仅2KB，不可变的日期时间库。使用与Moment.js同样的API，Moment.js的替代库。
- [date-fns](https://github.com/date-fns/date-fns) - 现代JavaScript日期工具库。
- [luxon](https://github.com/moment/luxon) - 用于处理日期和时间的库。
- [ms](https://github.com/vercel/ms) - 毫秒转换工具。

### 数据校验
- [validator.js](https://github.com/validatorjs/validator.js) - 字符串校验库。
- [joi](https://github.com/hapijs/joi) - 基于JavaScript对象的对象模式描述语言和验证器。
- [class-validator](https://github.com/typestack/class-validator) - 基于装饰器属性校验的类校验器。
- [ajv](https://github.com/epoberezkin/ajv) - 最快的JSON Schema验证器。支持JSON Schema draft-04/06/07/2019-09/2020-12 and JSON类型定义(RFC8927)。
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - 用简单和可组合的方式在JavaScript和TypeScript中校验数据。
- [v8n](https://github.com/imbrn/v8n) - 流畅的JavaScript校验库。
- [forgJs](https://github.com/oussamahamdaoui/forgJs) - 轻量的JavaScript对象校验器。
- [validatorjs](https://github.com/mikeerickson/validatorjs) - 受Laravel的校验器启发，在浏览器和Node.JS上的数据校验库.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - 极快的JSON Schema校验工具。
- [property-validator](https://github.com/nettofarah/property-validator) - 用于JavaScript、Node和Express的易用的属性校验工具。
- [schema-inspector](https://github.com/Atinux/schema-inspector) - 用于净化和验证JS对象的强大工具。

### 办公软件
- [sheetjs](https://github.com/SheetJS/sheetjs) - 电子表格数据工具箱。
- [PDFKit](https://github.com/foliojs/pdfkit) - 在Node.js和浏览器中生成PDF的库。
- [exceljs](https://github.com/exceljs/exceljs) - Excel工作表管理工具。
- [officegen](https://github.com/Ziv-Barber/officegen) - 使用Javascript，生成可打开Word（docx）、PowerPoint（pptx）和Excel（xlsx）的XML文件（需Microsoft Office 2007及更高版本），输出是一个stream。
- [Mammoth](https://github.com/mwilliamson/mammoth.js) - 将Word文档(.docx文件)转化为HTML。
- [docx](https://github.com/dolanmiu/docx) - 通过良好定义的API,在NodeJS和浏览器中，使用JS/TS轻松的生成docx文件。
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Excel XLSX生成和解析工具，可运行在Node和浏览器。

### Email
- [Nylas Mail](https://github.com/nylas/nylas-mail) - 构建在现代Web技术的高扩展性邮件客户端程序。
- [Nodemailer](https://github.com/nodemailer/nodemailer) - 使用Node.js轻松发送电子邮件。
- [Email Templates](https://github.com/forwardemail/email-templates) - 创建、预览和发送自定义电子邮件模板。
- [emailjs](https://github.com/eleith/emailjs) - 向任何SMTP服务器发送带有附件的文本/HTML电子邮件。
- [mjml](https://github.com/mjmlio/mjml) - 旨在减少创建响应电子邮件的痛苦的标记语言。

### 爬虫
- [node-crawler](https://github.com/bda-research/node-crawler) - NodeJS Web爬虫 + 服务端jQuery。
- [Headless Chrome Crawler](https://github.com/yujiosaka/headless-chrome-crawler) - 使用Chrome无头浏览器的分布式爬虫。

### AST
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript解析器。
- [antlr](https://github.com/antlr/antlr4) - ANTLR (ANother Tool for Language Recognition)是一个用于阅读、处理、执行和翻译结构化文本或二进制文件的强大的解析生成器。
- [acorn](https://github.com/acornjs/acorn) - 小巧、快速的JavaScript解析器。
- [astexplorer](https://github.com/fkling/astexplorer) - 使用多种解析器的AST Web可视化工具。
- [csstree](https://github.com/csstree/csstree) - 基于W3C标准和浏览器标准实现，包含快速详细的解析器、遍历器、生成器、词法解析的CSS工具集。