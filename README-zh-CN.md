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
  - [文本](#文本)
  - [数字](#数字)
  - [数学运算](#数学运算)
  - [日期 和 时间](#日期-和-时间)
  - [URL](#url)
  - [JSON](#json)
  - [类型判断](#类型判断)
  - [数据校验](#数据校验)
  - [Shell命令](#shell命令)
  - [环境变量](#环境变量)
  - [命令行工具](#命令行工具)
  - [Node.js Management](#nodejs-management)
  - [NPM](#npm)
  - [文件系统](#文件系统)
  - [Git](#git)
  - [日志](#日志)
  - [进程管理](#进程管理)
  - [代码校验 和 格式化工具](#代码校验-和-格式化工具)
  - [构建工具](#构建工具)
  - [模板引擎](#模板引擎)
  - [Web框架](#web框架)
  - [静态网站生成 & 博客](#静态网站生成--博客)
  - [论坛](#论坛)
  - [数据库](#数据库)
  - [自动化 & 机器人流程自动化 - RPA](#自动化--机器人流程自动化---rpa)
  - [测试相关](#测试相关)
  - [办公软件](#办公软件)
  - [操作系统识别](#操作系统识别)
  - [Email](#email)
  - [HTTP](#http)
  - [爬虫](#爬虫)
  - [定时任务](#定时任务)
  - [AST](#ast)
  - [机器学习](#机器学习)

## 官方资源

- [官网](https://nodejs.org)
- [文档](https://nodejs.org/dist/latest/docs/api/)
- [仓库](https://github.com/nodejs/node)

## NPM包

### 文本
  - 通用
    - [dedent](https://github.com/dmnd/dedent) - ES6模板字符串函数，用于去除多行字符串的缩进。
    - [camelcase](https://github.com/sindresorhus/camelcase) - 将破折号/点号/下划线/空格分隔的字符串转换为驼峰式, 案例：foo-bar→fooBar。
    - [detect-indent](https://github.com/sindresorhus/detect-indent) - 检查代码缩进。
    - [string-length](https://github.com/sindresorhus/string-length) - 获取字符串的真实长度 - 通过正确计算星号并忽略ansi转义码。
    - [strip-indent](https://github.com/sindresorhus/strip-indent) - 将字符串每一行中前置的空格删除。
    - [indent-string](https://github.com/sindresorhus/indent-string) - 将字符串每一行缩进。
    - [min-indent](https://github.com/jamiebuilds/min-indent) - 取每一行最少前置空格数。
    - [splice-string](https://github.com/sindresorhus/splice-string) - 移除或替换字符串的一部分。类似`Array#splice`.

  - 国际化
    - [i18next](https://github.com/i18next/i18next) - 国际化框架。
    - [i18n-node](https://github.com/mashpie/i18n-node) - 具有动态JSON存储的简单翻译模块。
    - [babelfish](https://github.com/nodeca/babelfish) - 适用于JavaScript的人性化i18n（node.js +浏览器）。

  - 唯一ID
    - [nanoid](https://github.com/ai/nanoid) - 小巧、安全、URL友好、唯一的字符串ID生成器。
    - [uuid](https://github.com/uuidjs/uuid) - 在JavaScript中生成符合RFC规范的UUID。

  - 编码/解码
    - [he](https://github.com/mathiasbynens/he) - HTML实体编码器/解码器。
    - [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - 转换字符编码。
    - [jschardet](https://github.com/aadsm/jschardet) - JavaScript编码自动识别 (Python版chardet的实现)。

  - 正则/通配符匹配
    - [matcher](https://github.com/sindresorhus/matcher) - 简单通配符匹配。
    - [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - 转义特殊正则字符。
    - [execall](https://github.com/sindresorhus/execall) - 在字符串中查找多个RegExp匹配项。

  - 其他
    - [StegCloak](https://github.com/kurolabs/stegcloak) - 基于纯JavaScript开发的隐写功能模块，StegCloak可以对文本中的机密信息进行压缩和加密，然后再使用特殊的Unicode不可见字符来隐藏它。
    - [unhomoglyph](https://github.com/nodeca/unhomoglyph) - 规范视觉上相似的unicode字符。

### 数字
- [Numeral.js](https://github.com/adamwdraper/Numeral-js) - 格式化和操作数字。
- [decimal.js](https://github.com/MikeMcl/decimal.js) - JavaScript的任意精度的十进制类型。
- [round-to](https://github.com/sindresorhus/round-to) - 将数字四舍五入到指定的小数位数：`1.234`→1.2`。
- [unique-random](https://github.com/sindresorhus/unique-random) - 生成连续唯一的随机数。
- [random-int](https://github.com/sindresorhus/random-int) - 生成随机整数。
- [random-float](https://github.com/sindresorhus/random-float) - 生成随机浮点数。

### 数学运算
- [mathjs](https://github.com/josdejong/mathjs) - 广泛的数学运算库。
- [ndarray](https://github.com/scijs/ndarray) - 多维数组。
- [algebra](https://github.com/fibo/algebra) - 代数结构。
- [multimath](https://github.com/nodeca/multimath) - 在WebAssembly和JS中进行快速图像数学运算。

### 日期 和 时间
- [moment](https://github.com/moment/moment) - 解析、校验、操作和显示日期。
- [dayjs](https://github.com/iamkun/dayjs) - 仅2KB，不可变的日期时间库。使用与Moment.js同样的API，Moment.js的替代库。
- [date-fns](https://github.com/date-fns/date-fns) - 现代JavaScript日期工具库。
- [luxon](https://github.com/moment/luxon) - 用于处理日期和时间的库。
- [ms](https://github.com/vercel/ms) - 毫秒转换工具。
- [dateformat](https://github.com/felixge/node-dateformat) - 日期格式化。

### URL
- [URI.js](https://github.com/medialize/URI.js) - URL转换库。
- [qs](https://github.com/ljharb/qs) - 请求字符串解析器。
- [query-string](https://github.com/sindresorhus/query-string) - 解析和字符串化URL查询字符串。
- [url-parse](https://github.com/unshiftio/url-parse) - 轻量URL解析器，可跨Node.js和浏览器环境无缝运行。
- [normalize-url](https://github.com/sindresorhus/normalize-url) - 规范化URL.
- [url-pattern](https://github.com/snd/url-pattern) - 比正则表达式更易匹配URL和其他字符串，将字符串转化成数据 或 将数据转换成字符串。
- [native-url](https://github.com/GoogleChromeLabs/native-url) - 使用内建URL API实现的NodeJS URL模块。
- [url-join](https://github.com/jfromaniello/url-join) - 将所有参数连接在一起，并将结果url规范化。
- [humanize-url](https://github.com/sindresorhus/humanize-url) - 使URL更可读: http://sindresorhus.com → sindresorhus.com。
- [parseurl](https://github.com/pillarjs/parseurl) - 使用记忆化方式解析URL.
- [file-url](https://github.com/sindresorhus/file-url) - 将文件路径转化为文件URL: `unicorn.jpg` → `file:///Users/sindresorhus/unicorn.jpg`
- [encodeurl](https://github.com/pillarjs/encodeurl) - 将URL编码为"百分比"形式，不编码已编码部分。

### JSON
- [json5](https://github.com/json5/json5) - JSON5是对JSON的扩展，其目的是能够更加容易的阅读和编写。
- [fast-json-stringify](https://github.com/fastify/fast-json-stringify) - 比JSON.stringify()快2倍。
- [jsonfile](https://github.com/jprichardson/node-jsonfile) - 轻松读写JSON文件。
- [load-json-file](https://github.com/sindresorhus/load-json-file) - 读取并解析JSON文件。
- [write-json-file](https://github.com/sindresorhus/write-json-file) - 序列化并写入JSON文件。

### 类型判断
- [is-type-of](https://github.com/node-modules/is-type-of) - Node.js完整类型判断。
- [core-util-is](https://github.com/isaacs/core-util-is) - Node.js核心工具 util.is* 函数。
- [isstream](https://github.com/rvagg/isstream) - 判断对象是否为流对象。
- [is-class](https://github.com/miguelmota/is-class) - 判断函数是否为 ES6类(class) 类型。
- [is-type](https://github.com/juliangruber/is-type) - Node.js核心类型判断。

### 数据校验
- [validator.js](https://github.com/validatorjs/validator.js) - 字符串校验库。
- [joi](https://github.com/hapijs/joi) - 基于JavaScript对象的对象模式描述语言和验证器。
- [class-validator](https://github.com/typestack/class-validator) - 基于装饰器属性校验的类校验器。
- [ajv](https://github.com/epoberezkin/ajv) - 最快的JSON Schema验证器。支持JSON Schema draft-04/06/07/2019-09/2020-12 and JSON类型定义(RFC8927)。
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - 用简单和可组合的方式在JavaScript和TypeScript中校验数据。
- [v8n](https://github.com/imbrn/v8n) - 流畅的JavaScript校验库。
- [forgJs](https://github.com/oussamahamdaoui/forgJs) - 轻量的JavaScript对象校验器。
- [validatorjs](https://github.com/mikeerickson/validatorjs) - 受Laravel的校验器启发，在浏览器和Node.JS上的数据校验库。
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - 极快的JSON Schema校验工具。
- [property-validator](https://github.com/nettofarah/property-validator) - 用于JavaScript、Node和Express的易用的属性校验工具。
- [schema-inspector](https://github.com/Atinux/schema-inspector) - 用于净化和验证JS对象的强大工具。

### Shell命令
- [shelljs](https://github.com/shelljs/shelljs) - 跨平台Unix shell命令。
- [execa](https://github.com/sindresorhus/execa) - 跨平台实现子进程执行 `child_process.{execFile,exec}`。
- [clipboardy](https://github.com/sindresorhus/clipboardy) - 跨平台的复制/粘贴。
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - 跨平台实现 `child_process.spawn()`。
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - 跨平台的复制/粘贴。
- [gulp-execa](https://github.com/ehmicky/gulp-execa) - 在Gulp中跨平台命令执行。

### 环境变量
- [cross-env](https://github.com/kentcdodds/cross-env) - 跨平台设置环境变量。
- [which](https://github.com/npm/node-which) - 跨平台实现的Unix `which`.
- [user-home](https://github.com/sindresorhus/user-home) - 跨平台获取用户home目录路径。
- [username](https://github.com/sindresorhus/username) - 获取当前用户名。
- [osenv](https://github.com/npm/osenv) - 跨平台环境变量。
- [is-elevated](https://github.com/sindresorhus/is-elevated) - 检查进程是否以提升的权限运行。

### 命令行工具
- [Commander.js](https://github.com/tj/commander.js) - Node.JS命令行界面完整解决方案。
- [chalk](https://github.com/chalk/chalk) - 命令行字符串样式美化工具。
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - 通用可交互命令行工具集合。
- [yargs](https://github.com/yargs/yargs) - 通用可交互命令行工具集合。
- [Enquirer](https://github.com/enquirer/enquirer) - 用户友好、直观且易于创建的时尚CLI提示。
- [minimist](https://github.com/substack/minimist) - 命令行参数解析引擎。
- [concurrently](https://github.com/kimmobrunfeldt/concurrently) - 并行执行命令，类似 `npm run watch-js & npm run watch-less`但更优。
- [colors.js](https://github.com/Marak/colors.js) - 获取Node.js控制台的颜色。
- [progress](https://github.com/visionmedia/node-progress) - Node.js的灵活ascii进度条。
- [depcheck](https://github.com/depcheck/depcheck) - 检查项目中未使用的依赖。
- [cac](https://github.com/cacjs/cac) - 用于构建命令行应用的强大框架。
- [log-symbols](https://github.com/sindresorhus/log-symbols) - 为不同日志级别添加色彩图标。
- [cli-progress](https://github.com/AndiDittrich/Node.CLI-Progress) - 在命令行/终端应用中轻松的使用进度条。
- [common-bin](https://github.com/node-modules/common-bin) - 基于yargs的命令行工具抽象，提供更方便的使用，支持async/generator。

### Node.js Management
- [nvm](https://github.com/nvm-sh/nvm) - Node.js版本管理工具。
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) -  Node.js版本管理工具Windows版。
- [n](https://github.com/tj/n) - Node.js版本管理工具。
- [fnm](https://github.com/Schniz/fnm) - 🚀 快速、轻量的Node.js版本管理工具，由Rust构建。
- [nave](https://github.com/isaacs/nave) - Node.js虚拟环境。
- [nodenv](https://github.com/nodenv/nodenv) - 版本管理工具（类似Ruby的 rbenv ），它支持自动切换。
- [nodeenv](https://github.com/ekalinin/nodeenv) - 与Python的 virtualenv 兼容的Node.js虚拟环境。

### NPM
  - NPM管理工具
    - [npm](https://github.com/npm/cli) - JavaScript包管理工具。
    - [yarn](https://github.com/yarnpkg/berry) - 现代包管理工具，拆分成多个不同的包。
    - [nrm](https://github.com/Pana/nrm) - 快速切换npm注册服务商，如npm、cnpm、nj、taobao。
    - [cnpm](https://github.com/cnpm/cnpm) - NPM中国区镜像客户端。

  - package.json
    - [read-pkg](https://github.com/sindresorhus/read-pkg) - 读取package.json文件。
    - [write-pkg](https://github.com/sindresorhus/write-pkg) - 写入package.json文件。

  - Semantic Version
    - [semver](https://github.com/npm/node-semver) - NPM使用的JavaScript语义化版本号解析器。

  - 工具
    - [npm-check-updates](https://github.com/raineorshine/npm-check-updates) - 查找当前package.json依赖允许的更新的版本。
    - [npm-run-all](https://github.com/mysticatea/npm-run-all) - 命令行工具，同时运行多个npm脚本（并行或串行）。
    - [npminstall](https://github.com/cnpm/npminstall) - 使 `npm install` 更快更容易。
    - [npm-home](https://github.com/sindresorhus/npm-home) - 打开npm包页面。
    - [npm-name](https://github.com/sindresorhus/npm-name) - 在npm上检查软件包名称的可用性。
    - [pacote](https://github.com/npm/pacote) - 从npm注册商下载tar压缩文件，并获取包的资源信息。
    - [npm-package-arg](https://github.com/npm/npm-package-arg) - 根据包名解析信息。
    - [npm-registry-fetch](https://github.com/npm/npm-registry-fetch) - 类型fetch()函数，但用于npm仓库。
    - [npm-updater](https://github.com/node-modules/npm-updater) - 检查npm包的更新。

### 文件系统
- [chokidar](https://github.com/paulmillr/chokidar) - 最小且高效的跨平台Watch库。
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - 为 `fs` 模块提供额外方法。
- [glob](https://github.com/isaacs/node-glob) - Node.js版glob功能。
- [ora](https://github.com/sindresorhus/ora) - 优雅的命令行loading效果。
- [rimraf](https://github.com/isaacs/rimraf) - 递归删除文件，类似 `rm -rf`。
- [progress-estimator](https://github.com/bvaughn/progress-estimator) - 记录进度条并估计完成承诺所需的时间。
- [globby](https://github.com/sindresorhus/globby) - 基于fast-glob，但添加了很多有用的特性。
- [fast-glob](https://github.com/mrmlnc/fast-glob) - 非常快速且高效的Node.js glob库。
- [del](https://github.com/sindresorhus/del) - 删除文件/文件夹。
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - graceful-fs可以替代fs模块，并做了各种改进。
- [filesize.js](https://github.com/avoidwork/filesize.js) - 生成人类可读的文件大小字符串。
- [make-dir](https://github.com/sindresorhus/make-dir) - 递归创建文件夹，类似 `mkdir -p`。
- [memfs](https://github.com/streamich/memfs) - Node.js API内存文件系统。
- [temp](https://github.com/bruce/node-temp) - Node.js临时文件、文件夹、流。
- [watchpack](https://github.com/webpack/watchpack) - Watch文件和文件夹。
- [tar-fs](https://github.com/mafintosh/tar-fs) - tar-fs允许您将目录打包到tar格式压缩包中，并将tar格式压缩包提取到目录中。
- [cpy](https://github.com/sindresorhus/cpy) - 文件拷贝。
- [mkdirp](https://github.com/isaacs/node-mkdirp) - 递归创建文件夹，类似 `mkdir -p`.

### Git
- [nodegit](https://github.com/nodegit/nodegit) - [libgit2](https://libgit2.org/) 的 Node.js 绑定版本。
- [simple-git](https://github.com/steveukx/git-js) - 一个轻量级的接口，用于在任何 node.js 应用程序中运行 git 命令。
- [gitgraph-node](https://github.com/nicoespeon/gitgraph.js/tree/master/packages/gitgraph-node) - 在 Terminal 绘制 git 流程图（支持浏览器、React）。
- [git-url-parse](https://github.com/IonicaBizau/git-url-parse) - 高级别git解析。
- [git-promise](https://github.com/piuccio/git-promise) - 简单的封装，可运行任何git命令，并使用promise处理其输出。
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - 从远程仓库中获取标签。
- [giturl](https://github.com/repo-utils/giturl) - 将Git链接转化成Web链接。
- [download-git-repo](https://gitlab.com/flippidippi/download-git-repo) - 下载和提取Git仓库 (支持GitHub, GitLab, Bitbucket)。

### 日志
- [winston](https://github.com/winstonjs/winston) - 多传输异步日志记录库。
- [pino](https://github.com/pinojs/pino) - 受Bunyan启发的超快日志记录库。
- [signale](https://github.com/klauscfhq/signale) - 高度可配置的日志工具。
- [log4js-node](https://github.com/log4js-node/log4js-node) - 不同于Java log4j的日志记录库。
- [consola](https://github.com/nuxt/consola) - 优雅的Node.js和浏览器日志记录库。
- [storyboard](https://github.com/guigrpa/storyboard) - 一个Chrome浏览器插件，用于查看日志。
- [cabin](https://github.com/cabinjs/cabin) - 提供日志服务和NPM包。
- [captains-log](https://www.npmjs.com/package/captains-log) - 通过简单的配置就可以使用的轻量日志记录库。

### 进程管理
- [PM2](https://github.com/Unitech/pm2) - 高级进程管理工具。
- [nodemon](https://github.com/remy/nodemon) - 监视应用程序中的更改并自动重新启动服务器。
- [forever](https://github.com/foreversd/forever) - 简单的CLI工具，用于确认提供的代码持续运行。
- [supervisor](https://github.com/petruisfan/node-supervisor) - 当脚本崩溃时重新启动脚本，或者当`*.js'文件更改时重新启动脚本。
- [node-windows](https://github.com/coreybutler/node-windows) - 将脚本作为本机Windows服务运行，并登录到事件查看器。
- [node-mac](https://github.com/coreybutler/node-mac) - 将脚本作为本机Mac守护进程运行，并登录到控制台应用程序。
- [node-linux](https://github.com/coreybutler/node-linux) - 将脚本作为本机系统服务运行，并登录到syslog。

### 代码校验 和 格式化工具
- [prettier](https://github.com/prettier/prettier) - ❤"有主见"的多语言代码格式化程序。
- [standard](https://github.com/standard/standard) - JavaScript 代码规范，自带 linter & 代码自动修正。
- [eslint](https://github.com/eslint/eslint) - 插件化并且可配置的 JavaScript 语法规则和代码风格的检查工具。
- [stylelint](https://github.com/stylelint/stylelint) - 功能强大现代风格检查工具，帮助你避免错误和强制约定样式风格。
- [lint-staged](https://github.com/okonet/lint-staged) - 在Git暂存文件上运行风格检查工具。
- [commitlint](https://github.com/conventional-changelog/commitlint) - Git提交信息风格检查工具。
- [xo](https://github.com/xojs/xo) - 带出色默认配置的JavaScript/TypeScript代码校验 (基于ESLint封装)
- [markdownlint](https://github.com/DavidAnson/markdownlint) - Markdown/CommonMark风格检查工具。
- [textlint](https://github.com/textlint/textlint) - Text 和 Markdown 校验和格式化。

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

### 模板引擎
- [Pug](https://github.com/pugjs/pug) - 受Haml启发的高性能模板引擎。
- [handlebars.js](https://github.com/wycats/handlebars.js) - Mustache 模板的超集，添加了强大的功能，如helper和更高级的block。
- [mustache.js](https://github.com/janl/mustache.js) - 轻量的JavaScript模板引擎{{八字须}}。
- [marko](https://github.com/marko-js/marko) - 基于HTML的模板引擎，编译成CommonJS模块，支持流、异步渲染和自定义标签。
- [art-template](https://github.com/aui/art-template) - 高性能JavaScript模板引擎。
- [nunjucks](https://github.com/mozilla/nunjucks) - 具有继承，异步控制等功能的模板引擎（受Jinja2启发）。
- [EJS](https://github.com/mde/ejs) - 超级简单的模板语言。
- [doT](https://github.com/olado/doT) - 最快简洁的JavaScript模板引擎。
- [Twig.js](https://github.com/twigjs/twig.js) - Twig模板语言的JavaScript实现。
- [hbs](https://github.com/pillarjs/hbs) - Handlebars的Expresss版本封装。

### Web框架
- [Express](https://github.com/expressjs/express) - Web应用程序框架，为构建单页和多页以及混合Web应用程序提供了一组强大的功能。
- [Next.js](https://github.com/zeit/next.js) - React服务端渲染框架。
- [Meteor](https://github.com/meteor/meteor) - 超简单，无处不在的数据库，在线数据，纯Javascript Web框架。 *（你也许会喜欢 [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Vue服务端渲染框架。
- [Nest](https://github.com/nestjs/nest) -受Angular启发的框架，用于构建高效且可扩展的服务器端应用程序。*(你也许会喜欢 [awesome-nestjs](https://github.com/juliandavidmr/awesome-nestjs))*
- [Koa](https://github.com/koajs/koa) - 由Express背后的团队设计的框架，旨在为Web应用程序和API提供更小，更富表现力和更强大的基础。
- [sails](https://github.com/balderdashy/sails) - Node.js实时MVC框架。
- [Fastify](https://github.com/fastify/fastify) - 快速和低开销的Web框架。
- [Hapi](https://github.com/hapijs/hapi) - 用于创建应用和服务的框架。
- [Egg](https://github.com/eggjs/egg) - 为企业级框架和应用而生。
- [Feathers](https://github.com/feathersjs/feathers) - 基于Express精神构建的微服务框架。
- [LoopBack](https://github.com/strongloop/loopback) - 用于创建REST API并轻松连接到后端数据源的强大框架。
- [Restify](https://github.com/restify/node-restify) - 使你能够构建正确的REST Web服务。
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 支持ES2015 +的框架，WebSockets，REST API。
- [Midway](https://github.com/midwayjs/midway) - 一个面向未来的云端一体 Node.js 框架。
- [total.js](https://github.com/totaljs/framework) - 使用纯JavaScript编写的Node.js框架，类似PHP's Laravel或Python's Django或ASP.NET MVC
- [AdonisJs](http://adonisjs.com) - 基于依赖注入和IoC容器的坚实基础构建的Node.js的真正MVC框架。
- [Micro](https://github.com/zeit/micro) - 具有异步方法的简约微服务框架。
- [Moleculer](https://moleculer.services) - 快速而强大的微服务框架。
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - 使用类和装饰器使用TypeScript创建GraphQL API的现代框架。
- [seneca](https://github.com/senecajs/seneca) - 编写微服务的工具包。
- [beidou](https://github.com/alibaba/beidou) - NodeJS & React 同构框架，基于Egg.js开发。
- [Marble.js](https://github.com/marblejs/marble) - 基于TypeScript和RxJS，用于构建服务端应用的函数响应式框架。
- [ActionHero](https://github.com/actionhero/actionhero) - 用于为TCP套接字，WebSocket和HTTP客户端制作可重用和可扩展的API的框架。
- [lad](https://github.com/ladjs/lad) - 最好的Node.js框架，由前Express和Koa团队成员创建。
- [Tinyhttp](https://github.com/talentlessguy/tinyhttp) - 类Express更现代更快的Web框架。
- [Hemera](https://github.com/hemerajs/hemera) -使用以下工具编写可靠且容错的微服务 [NATS](https://nats.io)。
- [Zeronode](https://github.com/sfast/zeronode) - 最小的构建块，可实现可靠且容错的微服务。

### 静态网站生成 & 博客
- [gatsby](https://github.com/gatsbyjs/gatsby) - 使用React构建快速、现代的应用程序和网站。
- [hexo](https://github.com/hexojs/hexo) - 使用Node.js的快速，简单，强大的博客框架。
- [vuepress](https://github.com/vuejs/vuepress) - 极简的Vue静态网站生成工具。
- [netlify-cms](https://github.com/netlify/netlify-cms) - 基于Git的静态网站生成工具。
- [react-static](https://github.com/react-static/react-static) - 渐进式的React静态网站生成工具。
- [gridsome](https://github.com/gridsome/gridsome) - Vue.js静态网站生成工具。
- [vitepress](https://github.com/vuejs/vitepress) - Vite & Vue.js静态网站生成工具。

### 论坛
- [NodeBB](https://github.com/NodeBB/NodeBB) - 基于Node.js的现代Web论坛。
- [nodeclub](https://github.com/cnodejs/nodeclub/) -  Nodeclub 是使用 Node.js 和 MongoDB 开发的社区系统

### 数据库
- 驱动
  - [MySQL](https://github.com/mysqljs/mysql) - MySQL 客户端。
  - [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL客户端。
  - [MongoDB](https://github.com/mongodb/node-mongodb-native) - 官方MongoDB驱动。
  - [ioredis](https://github.com/luin/ioredis) - Redis客户端。
  - [LevelUP](https://github.com/Level/levelup) - LevelDB客户端。
  - [couchdb-nano](https://github.com/apache/couchdb-nano) - 官方CouchDB客户端。
  - [Couchbase](https://github.com/couchbase/couchnode) - Couchbase客户端（官方）。
  - [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike客户端。

- ODM / ORM
  - [Sequelize](https://github.com/sequelize/sequelize) - 多方ORM。 支持PostgreSQL，SQLite，MySQL。
  - [TypeORM](https://github.com/typeorm/typeorm) - PostgreSQL，MariaDB，MySQL，SQLite等的ORM。
  - [Mongoose](https://github.com/Automattic/mongoose) - 优雅的MongoDB对象建模。
  - [Prisma](https://github.com/prisma/prisma) - 支持PostgreSQL, MySQL & SQLite，自动生成、类型安全的query builder。
  - [Bookshelf](https://github.com/bookshelf/bookshelf) - Backbone.js风格的PostgreSQL，MySQL和SQLite3的ORM。
  - [Objection.js](https://github.com/Vincit/objection.js) - 基于SQL查询生成器Knex的轻量级ORM。
  - [Waterline](https://github.com/balderdashy/waterline) - 与数据存储区无关的工具，可大大简化与一个或多个数据库的交互。
  - [Massive](https://github.com/robconery/massive-js) - PostgreSQL数据访问工具。
  - [pg-promise](https://github.com/vitaly-t/pg-promise) - 用于使用Promise的本机SQL的PostgreSQL框架。
  - [MikroORM](https://github.com/mikro-orm/mikro-orm) - 基于数据映射器，工作单元和身份映射模式的TypeScript ORM。 支持MongoDB，PostgreSQL，MySQL和SQLite。
  - [slonik](https://github.com/gajus/slonik) - 具有严格类型，详细日志记录和断言的PostgreSQL客户端。
  - [OpenRecord](https://github.com/PhilWaldmann/openrecord) - PostgreSQL，MySQL，SQLite3和RESTful数据存储的ORM。 类似于ActiveRecord。

- Query builder
  - [Knex](https://github.com/tgriesser/knex) - PostgreSQL，MySQL和SQLite3的查询构建器，旨在灵活，可移植且易于使用。

### 自动化 & 机器人流程自动化 - RPA
 - [puppeteer](https://github.com/puppeteer/puppeteer) - 无头Chrome Node.js API。
 - [playwright](https://github.com/microsoft/playwright) - 使用单一API自动操作Chromium, Firefox and WebKi。
 - [phantomjs](https://github.com/ariya/phantomjs) - 脚本化无头浏览器。
 - [appium](https://github.com/appium/appium) - iOS, Android, and Windows Apps自动化。

### 测试相关
- 断言库
  - [chai](https://github.com/chaijs/chai) - 基于行为驱动开发(BDD)和测试驱动开发(TDD)理念的Node.js和浏览器断言库，可与任何 JavaScript 测试框架集成。
  - [power-assert](https://github.com/power-assert-js/power-assert) - 使用标准assert接口提供的描述型断言消息。
  - [expect.js](https://github.com/Automattic/expect.js) - 适用于Node.JS和浏览器的简约BDD风格的断言库。
  - [should.js](https://github.com/shouldjs/should.js) - Node.JS的行为驱动开发(BDD)风格断言库。
  - [better-assert](https://github.com/tj/better-assert) - C语言风格的Node.js断言，将表达式字符串报告为错误消息。
  - [http-assert](https://github.com/jshttp/http-assert) - 带状态码的断言。

- Mock
  - [Mock.js](https://github.com/nuysoft/Mock) - 浏览器和 Node 均可用，支持自定义 schema 和 随机数据。
  - [Nock](https://github.com/pgte/nock) - HTTP mock和期望。
  - [Sinon.JS](https://github.com/sinonjs/sinon) - 通过间谍函数(spies), 目标函数替换（stubs）和mocks功能提供的Mock库。
  - [easy-mock](https://github.com/easy-mock/easy-mock) - 可视化，并且能快速生成模拟数据的持久化服务。
  - [mm](https://github.com/node-modules/mm) - 简单但灵活的 mock(或者叫stub) 包, mock伴侣。
  - [smoke](https://github.com/sinedied/smoke) - 具有记录功能的，简单但功能强大的基于文件的Mock服务器。

- 测试框架
  - [jest](https://github.com/facebook/jest) - 愉悦的JavaScript测试。
  - [mocha](https://github.com/mochajs/mocha) - 简单、灵活、有趣的功能丰富的Node.js和浏览器测试框架。
  - [ava](https://github.com/avajs/ava) - 面向未来的测试运行程序。
  - [supertest](https://github.com/visionmedia/supertest) - 使用流畅的API，基于Super-agent库测试Node.js HTTP服务器。

### 办公软件
- [sheetjs](https://github.com/SheetJS/sheetjs) - 电子表格数据工具箱。
- [nodeppt](https://github.com/ksky521/nodeppt) - Web端展示端PPT工具。
- [PDFKit](https://github.com/foliojs/pdfkit) - 在Node.js和浏览器中生成PDF的库。
- [exceljs](https://github.com/exceljs/exceljs) - Excel工作表管理工具。
- [officegen](https://github.com/Ziv-Barber/officegen) - 使用Javascript，生成可打开Word（docx）、PowerPoint（pptx）和Excel（xlsx）的XML文件（需Microsoft Office 2007及更高版本），输出是一个stream。
- [Mammoth](https://github.com/mwilliamson/mammoth.js) - 将Word文档(.docx文件)转化为HTML。
- [docx](https://github.com/dolanmiu/docx) - 通过良好定义的API,在NodeJS和浏览器中，使用JS/TS轻松的生成docx文件。
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Excel XLSX生成和解析工具，可运行在Node和浏览器。

### 操作系统识别
- [systeminformation](https://github.com/sebhildebrandt/systeminformation) - 获取硬件和软件系统信息。
- [is-wsl](https://github.com/sindresorhus/is-wsl) - 判断当前是否是否为WSL (适用于Linux的Windows子系统)。
- [os-name](https://github.com/sindresorhus/os-name) - 获取当前操作系统的名字。
- [getos](https://github.com/retrohacker/getos) - 获取当前操作系统名称，包括Linux的发行版名称。
- [is-windows](https://github.com/jonschlinkert/is-windows) - 判断当前系统是否为Windows。

### Email
- [Nylas Mail](https://github.com/nylas/nylas-mail) - 构建在现代Web技术的高扩展性邮件客户端程序。
- [Nodemailer](https://github.com/nodemailer/nodemailer) - 使用Node.js轻松发送电子邮件。
- [Email Templates](https://github.com/forwardemail/email-templates) - 创建、预览和发送自定义电子邮件模板。
- [emailjs](https://github.com/eleith/emailjs) - 向任何SMTP服务器发送带有附件的文本/HTML电子邮件。
- [mjml](https://github.com/mjmlio/mjml) - 旨在减少创建响应电子邮件的痛苦的标记语言。

### HTTP
  - 请求库
    - [axios](https://github.com/mzabriskie/axios) - 基于Promise 的HTTP客户端（也可以在浏览器中工作）。
    - [request](https://github.com/request/request) - 🏊🏾 简单的 HTTP 请求客户端。
    - [superagent](https://github.com/visionmedia/superagent) - HTTP请求库。
    - [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP代理。
    - [got](https://github.com/sindresorhus/got) - 更好的基于内建“http”模块接口实现。
    - [node-fetch](https://github.com/bitinn/node-fetch) - Node.js的 `window.fetch` 实现。
    - [needle](https://github.com/tomas/needle) - 灵活，基于流的HTTP Node.js客户端请求库。支持proxy，iconv，cookie，deflate和multipart。
    - [download](https://github.com/kevva/download) - 轻松下载和提取文件。
    - [urllib](https://github.com/node-modules/urllib) - 在复杂世界中请求HTTP/HTTPS的URL。
    - [gotql](https://github.com/khaosdoctor/gotql) - 基于[got](https://github.com/sindresorhus/got)构建的GraphQL请求库。
    - [wreck](https://github.com/hapijs/wreck) - HTTP 客户端工具。
    - [http-fake-backend](https://github.com/micromata/http-fake-backend) - 通过可配置的路由，提供JSON文件或JavaScript对象来构建伪造的后端。
    - [cacheable-request](https://github.com/lukechilds/cacheable-request) - 使用符合RFC的缓存封装的本机HTTP请求库。
    - [global-agent](https://github.com/gajus/global-agent) - 可以使用环境变量配置的全局 HTTP/HTTPS 代理。
    - [gh-got](https://github.com/sindresorhus/gh-got) - 基于"got"封装，与GitHub API更方便的交互。
    - [flashheart](https://github.com/bbc/flashheart) - REST 客户端。

  - 服务端库
    - [http-server](https://github.com/http-party/http-server) - 零配置的命令行Http服务端。
    - [anywhere](https://github.com/JacksonTian/anywhere) - 随启随用的静态文件服务器。

### 爬虫
- [node-crawler](https://github.com/bda-research/node-crawler) - NodeJS Web爬虫 + 服务端jQuery。
- [Headless Chrome Crawler](https://github.com/yujiosaka/headless-chrome-crawler) - 使用Chrome无头浏览器的分布式爬虫。

### 定时任务
- [agenda](https://github.com/agenda/agenda) - Node.js轻量级定时任务。
- [node-cron](https://github.com/kelektiv/node-cron) - 允许执行定时任务的工具。
- [cron-parser](https://github.com/harrisiirak/cron-parser) - 用于解析crontab指令的Node.js库。

### AST
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript解析器。
- [antlr](https://github.com/antlr/antlr4) - ANTLR (ANother Tool for Language Recognition)是一个用于阅读、处理、执行和翻译结构化文本或二进制文件的强大的解析生成器。
- [acorn](https://github.com/acornjs/acorn) - 小巧、快速的JavaScript解析器。
- [esprima](https://github.com/jquery/esprima) - 高性能、符合ECMASCRIPT标准的解析器。
- [astexplorer](https://github.com/fkling/astexplorer) - 使用多种解析器的AST Web可视化工具。
- [espree](https://github.com/eslint/espree) - 与Esprima兼容的JavaScript解析器。
- [csstree](https://github.com/csstree/csstree) - 基于W3C标准和浏览器标准实现，包含快速详细的解析器、遍历器、生成器、词法解析的CSS工具集。

### 机器学习
- [tfjs](https://github.com/tensorflow/tfjs) - Tensorflow官方提供JS版本。
- [brain.js](https://github.com/BrainJS/brain.js) - 基于模型训练的神经网络 JS 库，支持浏览器和 Node.js。
- [pipcook](https://github.com/alibaba/pipcook) - 为Web开发者提供的机器学习平台。
