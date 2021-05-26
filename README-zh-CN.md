> 该项目受 [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) 启发
>
> 原本是希望在原仓库中提供中文版，但跟该作者沟通，作者不希望添加本地化翻译增加维护工作量；且该库有很多国内用户常见的库并未收录，分类体系也不符合我的预期
>
> 故此另开分支，希望可以更好的满足国内开发者的需求。

[English](./README.md) | 简体中文

## 目录

- [目录](#目录)
- [官方资源](#官方资源)
- [GIT仓库](#git仓库)
  - [文本](#文本)
  - [数字](#数字)
  - [数学运算](#数学运算)
  - [日期 和 时间](#日期-和-时间)
  - [URL](#url)
  - [JSON](#json)
  - [图像处理](#图像处理)
  - [颜色](#颜色)
  - [加解密](#加解密)
  - [流](#流)
  - [类型判断](#类型判断)
  - [数据校验](#数据校验)
  - [函数式编程](#函数式编程)
  - [控制反转/依赖注入](#控制反转依赖注入)
  - [Shell](#shell)
  - [环境变量](#环境变量)
  - [事件](#事件)
  - [命令行工具](#命令行工具)
  - [Node.js管理工具](#nodejs管理工具)
  - [NPM](#npm)
  - [文件系统](#文件系统)
  - [解析工具](#解析工具)
  - [Git](#git)
  - [日志](#日志)
  - [进程管理](#进程管理)
  - [代码校验 和 格式化工具](#代码校验-和-格式化工具)
  - [构建工具](#构建工具)
  - [模板引擎](#模板引擎)
  - [Web框架](#web框架)
  - [静态网站生成 & 博客](#静态网站生成--博客)
  - [文档生成](#文档生成)
  - [实时通信](#实时通信)
  - [任务队列](#任务队列)
  - [定时任务](#定时任务)
  - [调试和剖析](#调试和剖析)
  - [论坛](#论坛)
  - [数据库](#数据库)
  - [缓存](#缓存)
  - [自动化 & 机器人流程自动化 - RPA](#自动化--机器人流程自动化---rpa)
  - [测试相关](#测试相关)
  - [办公软件](#办公软件)
  - [操作系统识别](#操作系统识别)
  - [文件压缩解压](#文件压缩解压)
  - [最小化](#最小化)
  - [邮箱](#邮箱)
  - [网络](#网络)
  - [HTTP](#http)
  - [验证](#验证)
  - [授权](#授权)
  - [分布式](#分布式)
  - [RPC](#rpc)
  - [爬虫](#爬虫)
  - [AST](#ast)
  - [设计稿转代码（D2C）](#设计稿转代码d2c)
  - [沙箱](#沙箱)
  - [机器学习 和 神经网络](#机器学习-和-神经网络)
  - [自然语言处理](#自然语言处理)

## 官方资源

- [官网](https://nodejs.org)
- [文档](https://nodejs.org/dist/latest/docs/api/)
- [仓库](https://github.com/nodejs/node)

## GIT仓库

### 文本

- 通用
  - [dedent](https://github.com/dmnd/dedent) - ES6模板字符串函数，用于去除多行字符串的缩进。
  - [camelcase](https://github.com/sindresorhus/camelcase) - 将破折号/点号/下划线/空格分隔的字符串转换为驼峰式, 案例：foo-bar→fooBar。
  - [string-width](https://github.com/sindresorhus/string-width) - 获取字符串的可视宽度-显示字符串所需的列数。
  - [decamelize](https://github.com/sindresorhus/decamelize) - 将驼峰式字符串转化成小写带分隔符带字符串, 案例：unicornRainbow → unicorn_rainbow
  - [detect-indent](https://github.com/sindresorhus/detect-indent) - 检查代码缩进。
  - [string-length](https://github.com/sindresorhus/string-length) - 获取字符串的真实长度 - 通过正确计算星号并忽略ansi转义码。
  - [strip-indent](https://github.com/sindresorhus/strip-indent) - 将字符串每一行中前置的空格删除。
  - [strip-bom](https://github.com/sindresorhus/strip-bom) - 从字符串中删除UTF-8字节顺序标记（BOM）。
  - [indent-string](https://github.com/sindresorhus/indent-string) - 将字符串每一行缩进。
  - [redent](https://github.com/sindresorhus/redent) - 去除多余的缩进并缩进字符串。
  - [min-indent](https://github.com/jamiebuilds/min-indent) - 取每一行最少前置空格数。
  - [splice-string](https://github.com/sindresorhus/splice-string) - 移除或替换字符串的一部分。类似`Array#splice`.

- 国际化
  - [i18next](https://github.com/i18next/i18next) - 国际化框架。
  - [i18n-node](https://github.com/mashpie/i18n-node) - 具有动态JSON存储的简单翻译模块。
  - [babelfish](https://github.com/nodeca/babelfish) - 适用于JavaScript的人性化i18n（node.js +浏览器）。

- 唯一ID
  - [nanoid](https://github.com/ai/nanoid) - 小巧、安全、URL友好、唯一的字符串ID生成器。
  - [uuid](https://github.com/uuidjs/uuid) - 在JavaScript中生成符合RFC规范的UUID。
  - [shortid](https://github.com/dylang/shortid) - 短ID生成器。 网址友好。 不可预测的。 集群兼容。
  - [ulid](https://github.com/ulid/javascript) - 通用唯一词典分类排序标识符。
  - [pure-uuid](https://github.com/rse/pure-uuid) - 基于纯JavaScript全局唯一ID(UUID)。

- 编码/解码
  - [he](https://github.com/mathiasbynens/he) - HTML实体编码器/解码器。
  - [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - 转换字符编码。
  - [jschardet](https://github.com/aadsm/jschardet) - JavaScript编码自动识别 (Python版chardet的实现)。

- 正则/通配符匹配
  - [path-to-regexp](https://github.com/pillarjs/path-to-regexp) - 将路径字符串（如`/user/:name`）转化为正则。
  - [minimatch](https://github.com/isaacs/minimatch) - 最小匹配工具。
  - [micromatch](https://github.com/micromatch/micromatch) - 高度优化的通配符和全局匹配库。更快，直接替换到 minimatch 和 multimatch。由webpack、babel core、yarn、jest、browser-sync、documentation.js、stylelint、nyc、ava以及许多其他资源使用！
  - [matcher](https://github.com/sindresorhus/matcher) - 简单通配符匹配。
  - [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - 转义特殊正则字符。
  - [multimatch](https://github.com/sindresorhus/multimatch) - 扩展 minimatch.match() 以支持多种模式。
  - [execall](https://github.com/sindresorhus/execall) - 在字符串中查找多个RegExp匹配项。

- 差异对比
  - [jsdiff](https://github.com/kpdecker/jsdiff) - 一种JavaScript文本差异实现。
  - [recursive-diff](https://github.com/cosmicanant/recursive-diff) - 查找两个JavaScript对象的差异，支持数组、数字、日期和其他原始数据类型。


- 其他
  - [StegCloak](https://github.com/kurolabs/stegcloak) - 基于纯JavaScript开发的隐写功能模块，StegCloak可以对文本中的机密信息进行压缩和加密，然后再使用特殊的Unicode不可见字符来隐藏它。
  - [unhomoglyph](https://github.com/nodeca/unhomoglyph) - 规范视觉上相似的unicode字符。

### 数字

- [Numeral.js](https://github.com/adamwdraper/Numeral-js) - 格式化和操作数字。
- [decimal.js](https://github.com/MikeMcl/decimal.js) - JavaScript的任意精度的十进制类型。
- [big.js](https://github.com/MikeMcl/big.js) - 一个小型，快速的JavaScript库，用于任意精度的十进制算术运算。
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
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - 将毫秒转换为人类可读的字符串，如: `1337000000` → `15d 11h 23m 20s`
- [date-utils](https://github.com/JerrySievert/date-utils) - 用于Node.js和浏览器的日期垫片（Polyfills）。

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
- [json-stable-stringify](https://github.com/substack/json-stable-stringify) - 具有自定义排序功能的确定性JSON.stringify(), 可以从字符串化结果中获取确定性哈希值。
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - 去除JSON文件中的注释。让你可以在JSON中使用注释。
- [json-stringify-safe](https://github.com/moll/json-stringify-safe) - 类似于JSON.stringify，但不会引发循环引用。
- [load-json-file](https://github.com/sindresorhus/load-json-file) - 读取并解析JSON文件。
- [write-json-file](https://github.com/sindresorhus/write-json-file) - 序列化并写入JSON文件。
- [fast-json-stable-stringify](https://github.com/epoberezkin/fast-json-stable-stringify) - 确定性JSON.stringify() - 比 @substack 的 json-stable-stringify 更快的版本，不带jsonify。
- [jsonuri](https://github.com/aligay/jsonuri) - 使用”URI样式“的方法来操作数据。

### 图像处理

- [sharp](https://github.com/lovell/sharp) - 调整JPEG，PNG，WebP和TIFF格式图像大小的最快模块。
- [jimp](https://github.com/oliver-moran/jimp) - 纯JavaScript中的图像处理。
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick 和 ImageMagick 封装。
- [qrcode](https://github.com/soldair/node-qrcode) - 二维码和条形码生成器。
- [pica](https://github.com/nodeca/pica) - 使用纯JS中的高质量和快速调整大小（lanczos3）。 当不允许像素化时替代canvas drawImage()。
- [lwip](https://github.com/EyalAr/lwip) - 不需要ImageMagick的轻量级图像处理器.
- [probe-image-size](https://github.com/nodeca/probe-image-size) - 无需完全下载即可获取大多数图像格式的大小.
- [image-type](https://github.com/sindresorhus/image-type) - 检测Buffer / Uint8Array的图像类型.

### 颜色

- [chroma](https://github.com/gka/chroma.js) - JavaScript库，用于各种颜色处理。
- [rgbaster](https://github.com/briangonzalez/rgbaster.js) - 🎨一个简单的库，用于从图像中提取主色。

### 加解密

- [crypto-js](https://github.com/brix/crypto-js) - JavaScript加密标准库。
- [bcrypt](https://github.com/kelektiv/node.bcrypt.js) - Node.js版Bcrypt。
- [jsencrypt](https://github.com/travist/jsencrypt) - 用于执行OpenSSL RSA加密、解密和密钥生成的Javascript库。
- [bcrypt.js](https://github.com/dcodeIO/bcrypt.js) - 经过优化bcrypt库，使用纯JavaScript的零依赖。
- [node-rsa](https://github.com/rzcoder/node-rsa) - Node.js RSA库。
- [aes-js](https://github.com/ricmoo/aes-js) - AES的纯JavaScript实现。
- [node-md5](https://github.com/pvorb/node-md5) - 一个JavaScript函数，用于使用MD5对消息进行哈希处理。
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - 微型哈希模块，在Node.js和浏览器中使用原生crypto API。
- [hash.js](https://github.com/indutny/hash.js) - 使用纯JavaScript的哈希实现。
- [pbkdf2](https://github.com/crypto-browserify/pbkdf2) - 在Node中具有任何受支持的哈希算法PBKDF2。

### 流

- [event-stream](https://github.com/dominictarr/event-stream) - EventStream就像函数式编程遇到IO。
- [through2](https://github.com/rvagg/through2) - 基于Node stream2 的封装进行转换以避免显式的子类化噪声。
- [JSONStream](https://github.com/dominictarr/JSONStream) - 流JSON.parse和stringify。
- [mississippi](https://github.com/maxogden/mississippi) - 有用的流实用程序模块的集合，用于更好编写的使用流的代码。
- [readable-stream](https://github.com/nodejs/readable-stream) - 可读流。
- [pump](https://github.com/mafintosh/pump) - 将流连接在一起，如果其中一个关闭，则关闭所有流。
- [concat-stream](https://github.com/maxogden/concat-stream) - 可写流，它将字符串或数据连接起来并执行回调。
- [stream-json](https://github.com/uhop/stream-json) - stream-json是用于创建自定义标准兼容JSON处理器的nod​​e.js流组件的集合，该组件所需的内存占用最少。它可以解析远远超出可用内存的JSON文件。甚至单个原始数据项（键，字符串和数字）也可以分段流式传输。还包括流式SAX启发式的基于事件的API。
- [split](https://github.com/dominictarr/split) - 分解流并重新组装它，以便每一行都是一块。匹配器可以是字符串，也可以是正则表达式。
- [tar-stream](https://github.com/mafintosh/tar-stream) - tar-stream是一个流式tar解析器和生成器。
- [node-byline](https://github.com/jahewson/node-byline) - 逐行流阅读器。
- [ndjson](https://github.com/maxogden/ndjson) - 流逐行分隔的json解析器 + 序列化器。
- [oppressor](https://github.com/substack/oppressor) - 流HTTP压缩响应协商程序。
- [multistream](https://github.com/feross/multistream) - 一种流，一个接一个地发出多个其他流（streams2）。
- [get-stream](https://github.com/sindresorhus/get-stream) - 以字符串，缓冲区或数组的形式获取流。
- [node-stream-buffer](https://github.com/samcday/node-stream-buffer) - 使用缓存的可读和可写流。
- [split2](https://github.com/mcollina/split2) - 拆分stream3样式。
- [fstream](https://github.com/npm/fstream) - 高级的Node.js文件操作流。
- [pumpify](https://github.com/mafintosh/pumpify) - 使用泵和全双工，将一系列流合并为单个双工流。
- [progress-stream](https://github.com/freeall/progress-stream) - 读取流的进度。
- [merge-stream](https://github.com/grncdr/merge-stream) - 将多个流合并为一个交错流。
- [duplexify](https://github.com/mafintosh/duplexify) - 将可写和可读流转换为具有异步初始化和stream1/streams2输入支持的stream2双工流。
- [into-stream](https://github.com/sindresorhus/into-stream) - 将缓存/字符串/数组/对象转换为流。
- [merge2](https://github.com/teambition/merge2) - 按顺序或并行的方式将多个流合并为一个流。
- [end-of-stream](https://github.com/mafintosh/end-of-stream) - 当可读/可写/双工流已完成或失败时，调用回调。
- [stream-to-promise](https://github.com/bendrucker/stream-to-promise) - 将流（可读或可写流）转换为Promise。
- [node-streamifier](https://github.com/gagle/node-streamifier) - 将 Buffer/String 转换为可读流。
- [stream-spec](https://github.com/dominictarr/stream-spec) - Stream的可执行规范（让测试流变得更容易）。
- [from2](https://github.com/hughsk/from2) - ReadableStream的便捷封装，其灵感来自through2。
- [dmap-stream](https://github.com/dominictarr/map-stream) - 基于Event-stream事件流重构。
- [emit-stream](https://github.com/substack/emit-stream) - 将event-emiiters转换为流 和 将流转换为event-emiiters。
- [stream-combiner](https://github.com/dominictarr/stream-combiner) - 将管道变成单个流。合并返回的流，写入第一个流并从最后一个流读取的流。
- [duplexer](https://github.com/raynos/duplexer) - 创建一个双工流。
- [promise-streams](https://github.com/spion/promise-streams) - Node.js流的集合，可以很好地与Promises (through, map, reduce等）一起使用。
- [binary-split](https://github.com/maxogden/binary-split) - 快速的换行符（或任何分隔符）分隔符流。
- [stream-combiner2](https://github.com/substack/stream-combiner2) - stream3的stream-combiner。
- [through2-concurrent](https://github.com/almost/through2-concurrent) - 简单的Node.JS流（streams2）转换，可并行执行转换功能（可设置的最大并发数）。
- [cloneable-readable](https://github.com/mcollina/cloneable-readable) - 安全地克隆可读流。
- [destroy](https://github.com/stream-utils/destroy) - 如果可能，销毁流。
- [peek-stream](https://github.com/mafintosh/peek-stream) - 转换流，可让您在决定如何解析前先窥视第一行。
- [resumer](https://github.com/substack/resumer) - 通过流开始暂停，并在下一个tick恢复。
- [stream-each](https://github.com/mafintosh/stream-each) - 迭代流中的所有数据。
- [flush-write-stream](https://github.com/mafintosh/flush-write-stream) - 一种写入流构造函数，支持流完成之前调用的flush函数。
- [multi-write-stream](https://github.com/mafintosh/multi-write-stream) - 创建一个可写流，其可写入多个其他可写流。
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - 缓冲并转换流的前n个字节。
- [multi-read-stream](https://github.com/mafintosh/multi-read-stream) - 可读流，它同时从多个可读流中读取。
- [node-stream-reduce](https://github.com/parshap/node-stream-reduce) - 将流数据减少为单个值。
- [stream-shift](https://github.com/mafintosh/stream-shift) - 返回流可读队列中的下一个缓冲区/对象。
- [stream-assert](https://github.com/floatdrop/stream-assert) - 流的断言库。
- [stream-from-promise](https://github.com/schnittstabil/stream-from-promise) - 根据Promise创建流。
- [stromjs](https://github.com/lewisdiamond/stromjs) - 无依赖的流实用程序。流的Lodash。
- [exec-stream](https://github.com/suarasaur/exec-stream) - 将流传入到子进程。
- [stream-callback](https://github.com/kikobeats/stream-callback) – 将流转换为一个回调函数。

### 类型判断

- [is-promise](https://github.com/then/is-promise) - 测试对象是否看起来像一个 Promises-a+ promise。
- [is](https://github.com/enricomarino/is) - JavaScript类型测试库。
- [is-type-of](https://github.com/node-modules/is-type-of) - Node.js完整类型判断。
- [is-stream](https://github.com/sindresorhus/is-stream) - 判断对象是否为流对象。
- [core-util-is](https://github.com/isaacs/core-util-is) - Node.js核心工具 util.is* 函数。
- [isstream](https://github.com/rvagg/isstream) - 判断对象是否为流对象。
- [is-class](https://github.com/miguelmota/is-class) - 判断函数是否为 ES6类(class) 类型。
- [is-type](https://github.com/juliangruber/is-type) - Node.js核心类型判断。
- [is-md5](https://github.com/imanhodjaev/is-md5) - JavaScript实用程序，用于检查字符串是否为md5加密。

### 数据校验

- [validator.js](https://github.com/validatorjs/validator.js) - 字符串校验库。
- [joi](https://github.com/hapijs/joi) - 基于JavaScript对象的对象模式描述语言和验证器。
- [async-validator](https://github.com/yiminghe/async-validator) - 异步校验。
- [class-validator](https://github.com/typestack/class-validator) - 基于装饰器属性校验的类校验器。
- [ajv](https://github.com/epoberezkin/ajv) - 最快的JSON Schema验证器。支持JSON Schema draft-04/06/07/2019-09/2020-12 and JSON类型定义(RFC8927)。
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - 用简单和可组合的方式在JavaScript和TypeScript中校验数据。
- [v8n](https://github.com/imbrn/v8n) - 流畅的JavaScript校验库。
- [forgJs](https://github.com/oussamahamdaoui/forgJs) - 轻量的JavaScript对象校验器。
- [validatorjs](https://github.com/mikeerickson/validatorjs) - 受Laravel的校验器启发，在浏览器和Node.JS上的数据校验库。
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - 极快的JSON Schema校验工具。
- [property-validator](https://github.com/nettofarah/property-validator) - 用于JavaScript、Node和Express的易用的属性校验工具。
- [schema-inspector](https://github.com/Atinux/schema-inspector) - 用于净化和验证JS对象的强大工具。

### 函数式编程

- [lodash](https://github.com/lodash/lodash) - 可提供一致性、自定义、性能和其他功能的实用程序库，比Underscore.js更好更快。
- [immutable](https://github.com/facebook/immutable-js) - 不可变的数据集合。
- [RxJS](https://github.com/reactivex/rxjs) - 用于转换、组合和查询各种数据的函数式响应式库。
- [Ramda](https://github.com/ramda/ramda) - 实用程序库着重于通过自动计算和相反的参数顺序实现的灵活功能组合，避免数据变化。
- [immer](https://github.com/immerjs/immer) - 函数式响应式编程。
- [Bacon.js](https://github.com/baconjs/bacon.js) - 函数式响应式编程。
- [Lazy.js](https://github.com/dtao/lazy.js) - 类似于lodash/underline的工具库，但具有惰性计算，在许多情况下可以转换为卓越的性能.
- [Folktale](https://github.com/origamitower/folktale) - 一套用于JavaScript中的通用函数编程的库，它允许您编写优雅的、模块化的应用程序，并且bug更少及更强的重用性。
- [Kefir.js](https://github.com/kefirjs/kefir) - 响应式库，专注于高性能和低内存使用。
- [Mout](https://github.com/mout/mout) - 该库与其他现有解决方案之间最大的区别是，您可以选择只加载需要的模块/函数，而不需要额外开销。.

### 控制反转/依赖注入

- [InversifyJS](https://github.com/inversify/InversifyJS) - 功能强大且轻便的控制反转容器。
- [injection-js](https://github.com/mgechev/injection-js) - 5.1K中的JavaScript和TypeScript的依赖注入库。它提取自Angular的ReflectiveInjector，这意味着它设计合理，功能完整、快速、可靠且经过良好测试。
- [power-di](https://github.com/zhang740/power-di) - 轻量的依赖注入库。

### Shell

- [shelljs](https://github.com/shelljs/shelljs) - 跨平台Unix shell命令。
- [execa](https://github.com/sindresorhus/execa) - 跨平台实现子进程执行 `child_process.{execFile,exec}`。
- [node-windows](https://github.com/coreybutler/node-windows) - Node.js上支持的Windows脚本。如(daemons, eventlog, UAC等)。
- [shx](https://github.com/shelljs/shx) - Node的可移植Shell命令。
- [clipboardy](https://github.com/sindresorhus/clipboardy) - 跨平台的复制/粘贴。
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - 跨平台实现 `child_process.spawn()`。
- [figures](https://github.com/sindresorhus/figures) - Windows兜底的Unicode符号。
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - 跨平台的复制/粘贴。
- [gulp-execa](https://github.com/ehmicky/gulp-execa) - 在Gulp中跨平台命令执行。
- [cross-spawn-promise](https://github.com/zentrick/cross-spawn-promise) - Promise化的cross-spawn。

### 环境变量

- [dotenv](https://github.com/motdotla/dotenv) - 从 .env文件 加载用于nodejs项目的环境变量。
- [cross-env](https://github.com/kentcdodds/cross-env) - 跨平台设置环境变量。
- [which](https://github.com/npm/node-which) - 跨平台实现的Unix `which`.
- [user-home](https://github.com/sindresorhus/user-home) - 跨平台获取用户home目录路径。
- [username](https://github.com/sindresorhus/username) - 获取当前用户名。
- [osenv](https://github.com/npm/osenv) - 跨平台环境变量。
- [is-elevated](https://github.com/sindresorhus/is-elevated) - 检查进程是否以提升的权限运行。

### 事件
- [ee-first](https://github.com/jonathanong/ee-first) - 获取一组EventEmitter和Event对中的第一个事件，然后对其进行清理。

### 命令行工具

- 框架/解决方案
  - [Commander.js](https://github.com/tj/commander.js) - Node.JS命令行界面完整解决方案。
  - [yargs](https://github.com/yargs/yargs) - 通用可交互命令行工具集合。
  - [oclif](https://github.com/oclif/oclif) - 基于Heroku开源Node.js CLI框架。
  - [meow](https://github.com/sindresorhus/meow) - CLI应用助手。
  - [cac](https://github.com/cacjs/cac) - 用于构建命令行应用的强大框架。
  - [Cliffy](https://github.com/drew-y/cliffy) - 可交互命令行框架。
  - [common-bin](https://github.com/node-modules/common-bin) - 基于yargs的命令行工具抽象，提供更方便的使用，支持async/generator。

- 命令行参数解析
  - [minimist](https://github.com/substack/minimist) - 命令行参数解析引擎。
  - [arg](https://github.com/vercel/arg) - 简单的参数解析。
  - [nopt](https://github.com/npm/nopt) - Node/npm参数解析。
  - [yargs-parser](https://github.com/yargs/yargs-parser) - yargs在使用，优雅参数解析库.

- Prompt提示
  - [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - 通用可交互命令行工具集合。
  - [prompts](https://github.com/terkelg/prompts) - 轻量、美观、用户友好的交互式命令行提示。
  - [Enquirer](https://github.com/enquirer/enquirer) - 用户友好、直观且易于创建的时尚CLI提示。

- 进度条
  - [progress](https://github.com/visionmedia/node-progress) - Node.js的灵活ascii进度条。
  - [progress-estimator](https://github.com/bvaughn/progress-estimator) - 记录进度条并估计完成承诺所需的时间。
  - [cli-progress](https://github.com/AndiDittrich/Node.CLI-Progress) - 在命令行/终端应用中轻松的使用进度条。

- 样式
  - [chalk](https://github.com/chalk/chalk) - 命令行字符串样式美化工具。
  - [ora](https://github.com/sindresorhus/ora) - 优雅的命令行loading效果。
  - [colors.js](https://github.com/Marak/colors.js) - 获取Node.js控制台的颜色。
  - [listr](https://github.com/SamVerschueren/listr) - 命令行任务列表。
  - [kleur](https://github.com/lukeed/kleur) - 最快的Node.js库，使用ANSI颜色格式化命令行文本。
  - [boxen](https://github.com/sindresorhus/boxen) - 控制台中创建盒子。
  - [terminal-image](https://github.com/sindresorhus/terminal-image) - 在终端中展示图片。
  - [log-symbols](https://github.com/sindresorhus/log-symbols) - 为不同日志级别添加色彩图标。
  - [gradient-string](https://github.com/bokub/gradient-string) - 终端输出中漂亮的颜色渐变。
  - [terminal-link](https://github.com/sindresorhus/terminal-link) - 在终端中创建可点击的链接。
  - [cli-table3](https://github.com/cli-table/cli-table3) - 命令行的漂亮unicode表。
  - [easy-table](https://github.com/eldargab/easy-table) - 漂亮的文本表格。
  - [treeify](https://github.com/notatestuser/treeify) - 将javascript对象漂亮地打印为树。
  - [kolorist](https://github.com/marvinhagemeister/kolorist) - 使用输入和输出色彩化的小工具。
  - [console-png](https://github.com/aantthony/console-png) - 在命令行输出中打印PNG图片。

- 其他
  - [commitizen](https://github.com/commitizen/cz-cli) - Commitizen命令行实用程序。
  - [concurrently](https://github.com/kimmobrunfeldt/concurrently) - 并行执行命令，类似 `npm run watch-js & npm run watch-less`但更优。
  - [update-notifier](https://github.com/yeoman/update-notifier) - 为你的CLI应用提供的更新提示。
  - [console-clear](https://github.com/lukeed/console-clear) - 跨平台清空控制台。

### Node.js管理工具

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
  - [read-pkg-up](https://github.com/sindresorhus/read-pkg-up) - 读取最近的package.json文件。
  - [node-pkginfo](https://github.com/indexzero/node-pkginfo) - 从package.json读取属性的简单方法。
  - [read-pkg](https://github.com/sindresorhus/read-pkg) - 读取package.json文件。
  - [write-pkg](https://github.com/sindresorhus/write-pkg) - 写入package.json文件。

- 语义化版本
  - [semver](https://github.com/npm/node-semver) - NPM使用的JavaScript语义化版本号解析器。

- 工具
  - [npm-check-updates](https://github.com/raineorshine/npm-check-updates) - 查找当前package.json依赖允许的更新的版本。
  - [npm-run-all](https://github.com/mysticatea/npm-run-all) - 命令行工具，同时运行多个npm脚本（并行或串行）。
  - [depcheck](https://github.com/depcheck/depcheck) - 检查你的NPM模块未使用的依赖。
  - [npminstall](https://github.com/cnpm/npminstall) - 使 `npm install` 更快更容易。
  - [npm-home](https://github.com/sindresorhus/npm-home) - 打开npm包页面。
  - [npm-name](https://github.com/sindresorhus/npm-name) - 在npm上检查软件包名称的可用性。
  - [pacote](https://github.com/npm/pacote) - 从npm注册商下载tar压缩文件，并获取包的资源信息。
  - [npm-package-arg](https://github.com/npm/npm-package-arg) - 根据包名解析信息。
  - [npm-registry-fetch](https://github.com/npm/npm-registry-fetch) - 类型fetch()函数，但用于npm仓库。
  - [npm-updater](https://github.com/node-modules/npm-updater) - 检查npm包的更新。

### 文件系统

- 通用
  - [fs-extra](https://github.com/jprichardson/node-fs-extra) - 为 `fs` 模块提供额外方法。
  - [rimraf](https://github.com/isaacs/rimraf) - 递归删除文件，类似 `rm -rf`。
  - [del](https://github.com/sindresorhus/del) - 删除文件/文件夹。
  - [graceful-fs](https://github.com/isaacs/node-graceful-fs) - graceful-fs可以替代fs模块，并做了各种改进。
  - [filesize.js](https://github.com/avoidwork/filesize.js) - 生成人类可读的文件大小字符串。
  - [make-dir](https://github.com/sindresorhus/make-dir) - 递归创建文件夹，类似 `mkdir -p`。
  - [memfs](https://github.com/streamich/memfs) - Node.js API内存文件系统。
  - [ncp](https://github.com/AvianFlu/ncp) - 使用Node.js进行异步递归文件复制。
  - [temp](https://github.com/bruce/node-temp) - Node.js临时文件、文件夹、流。
  - [find-up](https://github.com/sindresorhus/find-up) - 通过上级父目录查找文件或目录。
  - [cpy](https://github.com/sindresorhus/cpy) - 文件拷贝。
  - [mkdirp](https://github.com/isaacs/node-mkdirp) - 递归创建文件夹，类似 `mkdir -p`。
  - [temp-dir](https://github.com/sindresorhus/temp-dir) - 获取系统临时文件夹的真实路径。

- 监控
  - [chokidar](https://github.com/paulmillr/chokidar) - 最小且高效的跨平台Watch库。
  - [watchpack](https://github.com/webpack/watchpack) - Watch文件和文件夹。

- 遍历查找
  - [glob](https://github.com/isaacs/node-glob) - Node.js版glob功能。
  - [globby](https://github.com/sindresorhus/globby) - 基于fast-glob，但添加了很多有用的特性。
  - [fast-glob](https://github.com/mrmlnc/fast-glob) - 非常快速且高效的Node.js glob库。

### 解析工具

- Markdown
  - [marked](https://github.com/markedjs/marked) - Markdown解析器和编译器，专为提高速度而设计。
  - [remark](https://github.com/wooorm/remark) - Markdown处理工具。
  - [markdown-it](https://github.com/markdown-it/markdown-it) - 支持100%通用Markdown标签解析的扩展&语法插件。

- CSV
  - [node-csv](https://github.com/adaltas/node-csv) - 具有简单api的全功能CSV解析器，并针对大型数据集进行了测试。
  - [csv-parser](https://github.com/mafintosh/csv-parser) - 旨在比其他任何人都快的流式CSV解析器。
  - [neat-csv](https://github.com/sindresorhus/neat-csv) - 快速的CSV解析器。

- YAML
  - [js-yaml](https://github.com/nodeca/js-yaml) - 快速的YAML解析器。

- XML
  - [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - 将XML转换为JavaScript对象的转换器。
  - [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - 验证&解析 XML。
  - [xmlbuilder](https://github.com/oozcitak/xmlbuilder-js) - XML构建器。

- CSS
  - [PostCSS](https://github.com/postcss/postcss) - CSS解析工具。
  - [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - CSS注释剔除工具。

### Git

- [husky](https://github.com/typicode/husky) - 现代化的本地Git钩子使操作更加轻松！
- [nodegit](https://github.com/nodegit/nodegit) - [libgit2](https://libgit2.org/) 的 Node.js 绑定版本。
- [simple-git](https://github.com/steveukx/git-js) - 一个轻量级的接口，用于在任何 node.js 应用程序中运行 git 命令。
- [gitgraph-node](https://github.com/nicoespeon/gitgraph.js/tree/master/packages/gitgraph-node) - 在 Terminal 绘制 git 流程图（支持浏览器、React）。
- [pre-commit](https://github.com/observing/pre-commit) - 自动在您的git储存库中安装git pre-commit脚本，该脚本在pre-commit上运行您的`npm test`。
- [git-url-parse](https://github.com/IonicaBizau/git-url-parse) - 高级别git解析。
- [git-promise](https://github.com/piuccio/git-promise) - 简单的封装，可运行任何git命令，并使用promise处理其输出。
- [gittar](https://github.com/lukeed/gittar) - 下载/提取git仓库 (GitHub, GitLab, BitBucket)，跨平台和优先离线。
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
- [fancy-log](https://github.com/gulpjs/fancy-log) - 带上时间前缀的日志记录库。
- [captains-log](https://github.com/balderdashy/captains-log) - 通过简单的配置就可以使用的轻量日志记录库。

### 进程管理

- [PM2](https://github.com/Unitech/pm2) - 高级进程管理工具。
- [nodemon](https://github.com/remy/nodemon) - 监视应用程序中的更改并自动重新启动服务器。
- [forever](https://github.com/foreversd/forever) - 简单的CLI工具，用于确认提供的代码持续运行。
- [supervisor](https://github.com/petruisfan/node-supervisor) - 当脚本崩溃时重新启动脚本，或者当`*.js'文件更改时重新启动脚本。
- [node-windows](https://github.com/coreybutler/node-windows) - 将脚本作为本机Windows服务运行，并登录到事件查看器。
- [node-mac](https://github.com/coreybutler/node-mac) - 将脚本作为本机Mac守护进程运行，并登录到控制台应用程序。
- [node-linux](https://github.com/coreybutler/node-linux) - 将脚本作为本机系统服务运行，并登录到syslog。
- [current-processes](https://github.com/branneman/current-processes) - 可获取当前正在运行的进程快照（操作系统无关）。

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
- [pretty-quick](https://github.com/azz/pretty-quick) - 快速美化。

### 构建工具

- [webpack](https://github.com/webpack/webpack) - 打包浏览器的模块和资产。
- [parcel](https://github.com/parcel-bundler/parcel) - 快速，零配置的Web应用构建工具。
- [gulp](https://github.com/gulpjs/gulp) - 流式快速构建系统，支持代码而不是配置。
- [esbuild](https://github.com/evanw/esbuild) - 极快的JavaScript打包压缩工具。
- [rollup](https://github.com/rollup/rollup) - 新一代的 ES2015 打包构建工具。
- [pkg](https://github.com/zeit/pkg) - 将Node.js项目打包成可执行文件。
- [Grunt](https://github.com/gruntjs/grunt) - JavaScript任务执行器。
- [Brunch](https://github.com/brunch/brunch) - 前端web应用程序构建工具，具有简单的声明性配置、快速的增量编译和自定的工作流。
- [FuseBox](https://github.com/fuse-box/fuse-box) - 快速构建系统，结合了webpack，JSPM和SystemJS的强大功能，并具有一流的TypeScript支持。
- [Broccoli](https://github.com/broccolijs/broccoli) - 快速、可靠的资产管道，支持固定时间重建和紧凑的构建定义。

- ESM
  - [Vite](https://github.com/vitejs/vite) - 新一代前端构建工具。
  - [snowpack](https://github.com/snowpackjs/snowpack) - 由ESM支持的前端构建工具。 即时，轻量级，无捆绑开发。

### 模板引擎

- [Pug](https://github.com/pugjs/pug) - 受Haml启发的高性能模板引擎。
- [handlebars.js](https://github.com/wycats/handlebars.js) - Mustache 模板的超集，添加了强大的功能，如helper和更高级的block。
- [mustache.js](https://github.com/janl/mustache.js) - 轻量的JavaScript模板引擎{{八字须}}。
- [marko](https://github.com/marko-js/marko) - 基于HTML的模板引擎，编译成CommonJS模块，支持流、异步渲染和自定义标签。
- [art-template](https://github.com/aui/art-template) - 高性能JavaScript模板引擎。
- [nunjucks](https://github.com/mozilla/nunjucks) - 具有继承，异步控制等功能的模板引擎（受Jinja2启发）。
- [EJS](https://github.com/mde/ejs) - 超级简单的模板语言。
- [hogan.js](https://github.com/twitter/hogan.js) - {{八字须}} 样式的模板语言。
- [doT](https://github.com/olado/doT) - 最快简洁的JavaScript模板引擎。
- [dustjs](https://github.com/linkedin/dustjs) - 用于浏览器和服务器的异步Javascript模板。
- [jsrender](https://github.com/BorisMoore/jsrender) -  轻巧，功能强大且高度可扩展的模板引擎。
- [Twig.js](https://github.com/twigjs/twig.js) - Twig模板语言的JavaScript实现。
- [hbs](https://github.com/pillarjs/hbs) - Handlebars的Express版本封装。
- [Juicer](https://github.com/PaulGuo/Juicer) - 轻量级JavaScript模板引擎。
- [tempo](https://github.com/twigkit/tempo) - Tempo是一个简单，直观的JavaScript渲染引擎，使您能够以纯HTML格式制作数据模板。
- [xtemplate](https://github.com/xtemplate/xtemplate) - 用于浏览器和Node.js上的高速，可扩展模板引擎库。支持异步控制，继承，包含，逻辑表达式，自定义函数等。

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
- [Hemera](https://github.com/hemerajs/hemera) - 使用以下工具编写可靠且容错的微服务 [NATS](https://nats.io)。
- [restana](https://github.com/BackendStack21/restana) - 用于构建REST微服务的超快速和简约的框架。
- [Zeronode](https://github.com/sfast/zeronode) - 最小的构建块，可实现可靠且容错的微服务。

### 静态网站生成 & 博客

- [gatsby](https://github.com/gatsbyjs/gatsby) - 使用React构建快速、现代的应用程序和网站。
- [hexo](https://github.com/hexojs/hexo) - 使用Node.js的快速，简单，强大的博客框架。
- [vuepress](https://github.com/vuejs/vuepress) - 极简的Vue静态网站生成工具。
- [netlify-cms](https://github.com/netlify/netlify-cms) - 基于Git的静态网站生成工具。
- [react-static](https://github.com/react-static/react-static) - 渐进式的React静态网站生成工具。
- [gridsome](https://github.com/gridsome/gridsome) - Vue.js静态网站生成工具。
- [vitepress](https://github.com/vuejs/vitepress) - Vite & Vue.js静态网站生成工具。

### 文档生成

- [Docusaurus](https://github.com/facebook/docusaurus) - 使用React和Markdown并具有翻译和版本控制功能的文档站点生成器。
- [docsify](https://github.com/docsifyjs/docsify) - API文档生成器。
- [JSDoc](https://github.com/jsdoc3/jsdoc) - API文档生成器，类似于JavaDoc或PHPDoc。
- [documentation.js](https://github.com/documentationjs/documentation) - API文档生成器，支持ES2015+和流程注释。
- [Docco](https://github.com/jashkenas/docco) - 文档生成器，该生成器生成一个HTML文档，该文档显示与代码混合的注释。
- [ESDoc](https://github.com/esdoc/esdoc) - 针对ES2015的文档生成器，附加测试代码并衡量文档覆盖范围。

### 实时通信

- [Socket.io](https://github.com/socketio/socket.io) - 实现基于事件的实时双向通信。
- [ws](https://github.com/websockets/ws) - 简单易用，速度极快，经过全面测试的WebSocket客户端和服务器Node.js通信库。
- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - 高度可扩展的WebSocket服务器和客户端库。
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - MQTT客户端-基于Pub-sub的消息协议，用于TCP / IP。
- [SocketCluster](https://github.com/SocketCluster/socketcluster) -  可扩展的HTTP + WebSocket引擎，可以在多个CPU内核上运行。
- [Faye](https://github.com/faye/faye) - 基于Bayeux协议的实时客户端-服务器消息总线。
- [Primus](https://github.com/primus/primus) - 实时框架的抽象层，以防止模块锁定。
- [engine.io](https://github.com/socketio/engine.io) - 基于传输的跨浏览器/跨设备双向通信层的实现Socket.IO。
- [SockJS-node](https://github.com/sockjs/sockjs-node) - WebSocket Node.js服务端实现。
- [Aedes](https://github.com/mcollina/aedes) - 可以在任何流服务器上运行的准系统MQTT服务器。
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - 通过WebSocket实现JSON-RPC 2.0。
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - 可扩展的实时通信微服务框架。
- [Kalm](https://github.com/kalm/kalm.js) - 低级套接字路由器和中间件框架。

### 任务队列

- [bull](https://github.com/OptimalBits/bull) - 持久作业和消息队列。
- [amqp](https://github.com/squaremo/amqp.node)- AMQP 0-9-1 rabbit消息队列连接库。
- [kafka-node]( https://github.com/SOHU-Co/kafka-node)-  Apache Kafka 0.8 kafka客户端。
- [bee-queue](https://github.com/bee-queue/bee-queue) - 高性能的 基于Redis的任务队列。
  - [arena](https://github.com/bee-queue/arena) - bee-queue的交互式UI仪表盘。
- [kafkajs](https://github.com/tulios/kafkajs) - A modern Apache Kafka client for node.js.
- [rsmq](https://github.com/smrchy/rsmq) - 基于Redis的消息队列.
- [sqs-consumer](https://github.com/bbc/sqs-consumer) - 在没有样板文件的情况下构建基于Amazon简单队列服务（SQS）的应用程序.
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis支持的作业队列.
- [better-queue](https://github.com/diamondio/better-queue) - 当你无法使用Redis时，简单高效的作业队列.
- [RedisSMQ](https://github.com/weyoss/redis-smq) - 具有实时监控功能的简单高性能Redis消息队列.
- [idoit](https://github.com/nodeca/idoit) - 具有高级作业控制的Redis支持的作业队列引擎.

### 定时任务

- [node-schedule](https://github.com/node-schedule/node-schedule) - 类Cron和不类似Cron的Node.js定时任务。
- [agenda](https://github.com/agenda/agenda) - Node.js轻量级定时任务。
- [node-cron](https://github.com/kelektiv/node-cron) - 允许执行定时任务的工具。
- [cron-parser](https://github.com/harrisiirak/cron-parser) - 用于解析crontab指令的Node.js库。

### 调试和剖析

- [node-inspector](https://github.com/node-inspector/node-inspector) - 基于Blink开发者工具的调试器。
- [ndb](https://github.com/GoogleChromeLabs/ndb) - Chrome DevTools调试体验改进工具。
- [debug](https://github.com/visionmedia/debug) - 轻量调试工具。
- [Clinic.js](https://github.com/clinicjs/node-clinic) - Clinic.js诊断Node.js性能问题。
- [ironNode](https://github.com/s-a/iron-node) - 支持ES2015的Node.js开箱即用的调试器。
- [node-heapdump](https://github.com/bnoordhuis/node-heapdump) - 存储V8内存堆使用情况，以供以后诊断。
- [0x](https://github.com/davidmarkclements/0x) - 火焰图分析。
- [leakage](https://github.com/andywer/leakage) - 内存写入泄漏测试。
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - 当不明Node原因继续运行时，使用的分析工具。
- [llnode](https://github.com/nodejs/llnode) - 事后分析工具，使您可以检查对象并从崩溃的Node.js进程中获取信息。
- [swagger-stats](https://github.com/slanatech/swagger-stats) - 跟踪API调用并监视API性能，运行状况和使用情况指标。
- [njsTrace](https://github.com/valyouw/njstrace) - 跟踪API调用并监视API性能，运行状况和使用情况指标。
- [locus](https://github.com/alidavut/locus) - 检测并跟踪代码，查看所有函数调用、参数、返回值以及在每个函数中花费的时间。
- [stackman](https://github.com/watson/stackman) - 使用代码摘录和其他优点增强错误堆栈跟踪。
- [NiM](https://github.com/june07/nim) - 管理DevTools调试工具流。
- [thetool](https://github.com/sfninja/thetool) - 以Chrome DevTools友好格式为您的应用捕获不同的CPU，内存和其他配置文件。
- [ctrace](https://github.com/automation-stack/ctrace) - 格式正确且经过改进的跟踪系统调用和信号。
- [v8-profiler-next](https://github.com/hyj1991/v8-profiler-next) - V8性能探测器。
- [vstream](https://github.com/joyent/node-vstream) - 可检测的流混入以检查流的管道。

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

### 缓存

- [lru-cache](https://github.com/isaacs/node-lru-cache) - 最近最少使用的缓存（LRU）实现。
- [node-cache](https://github.com/node-cache/node-cache) - Node.js内存缓存模块。
- [memcached](https://github.com/3rd-Eden/memcached) - 功能齐全的Memcached Node.js客户端库。 考虑到扩展性，因此它将支持Memcached群集和一致的哈希。
- [node-cache-manager](https://github.com/BryanDonovan/node-cache-manager) - Node.js Cache模块。
- [hashlru](https://github.com/dominictarr/hashlru) - 更轻量更快的LRU算法。
- [ylru](https://github.com/node-modules/ylru) - 基于hashlru添加过期时间，允许空值。

### 自动化 & 机器人流程自动化 - RPA

- [puppeteer](https://github.com/puppeteer/puppeteer) - 无头Chrome Node.js API。
- [playwright](https://github.com/microsoft/playwright) - 使用单一API自动操作Chromium, Firefox and WebKi。
- [phantomjs](https://github.com/ariya/phantomjs) - 脚本化无头浏览器。
- [appium](https://github.com/appium/appium) - iOS, Android, and Windows Apps自动化。
- [robotjs](https://github.com/octalmage/robotjs) - Node.js桌面自动化。

### 测试相关

- 断言库
  - [chai](https://github.com/chaijs/chai) - 基于行为驱动开发(BDD)和测试驱动开发(TDD)理念的Node.js和浏览器断言库，可与任何 JavaScript 测试框架集成。
  - [power-assert](https://github.com/power-assert-js/power-assert) - 使用标准assert接口提供的描述型断言消息。
  - [expect.js](https://github.com/Automattic/expect.js) - 适用于Node.JS和浏览器的简约BDD风格的断言库。
  - [should.js](https://github.com/shouldjs/should.js) - Node.JS的行为驱动开发(BDD)风格断言库。
  - [better-assert](https://github.com/tj/better-assert) - C语言风格的Node.js断言，将表达式字符串报告为错误消息。
  - [http-assert](https://github.com/jshttp/http-assert) - 带状态码的断言。

- 假数据生成
  - [faker.js](https://github.com/marak/Faker.js/) - 在Node.js和浏览器中生成大量逼真的假数据。
  - [casual](https://github.com/boo1ean/casual) - JavaScript假数据生成。
  - [fony](https://github.com/captainsafia/fony) - 一个简单的命令行工具，从字符串模板中生成假数据。

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
  - [jasmine](https://github.com/jasmine/jasmine) - 简单的Node.js和浏览器测试框架。
  - [supertest](https://github.com/visionmedia/supertest) - 使用流畅的API，基于Super-agent库测试Node.js HTTP服务器。
  - [node-tap](https://github.com/tapjs/node-tap) - 用于Node.js测试任何协议的工具。

- 覆盖率
  - [nyc](https://github.com/istanbuljs/nyc) - Istanbul的命令行工具。
  - [node-coveralls](https://github.com/nickmerwin/node-coveralls) - 借助持续集成服务(Travis CI 或 Jenkins) 向用户报告自动测试的测试覆盖率；为README添加一个很酷的覆盖率按钮。
  - [codecov](https://github.com/codecov/codecov-node) - NodeJS中代码覆盖率报告上载器。

- 基准测试
  - [Benchmark.js](https://github.com/bestiejs/benchmark.js) - 基准测试库，支持高分辨率计时器并返回具有统计意义的结果。
  - [matcha](https://github.com/logicalparadox/matcha) - 基准测试的简化方法。
  - [node-wrk](https://github.com/sidorares/node-wrk) - Wrk负载测试工具Node.js版封装。

### 办公软件

- Excel
  - [sheetjs](https://github.com/SheetJS/sheetjs) - 电子表格数据工具箱。
  - [exceljs](https://github.com/exceljs/exceljs) - Excel工作表管理工具。
  - [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Excel XLSX生成和解析工具，可运行在Node和浏览器。

- Word
  - [officegen](https://github.com/Ziv-Barber/officegen) - 使用Javascript，生成可打开Word（docx）、PowerPoint（pptx）和Excel（xlsx）的XML文件（需Microsoft Office 2007及更高版本），输出是一个stream。
  - [Mammoth](https://github.com/mwilliamson/mammoth.js) - 将Word文档(.docx文件)转化为HTML。
  - [docx](https://github.com/dolanmiu/docx) - 通过良好定义的API,在NodeJS和浏览器中，使用JS/TS轻松的生成docx文件。

- PDF
  - [PDFKit](https://github.com/foliojs/pdfkit) - 在Node.js和浏览器中生成PDF的库。
  - [percollate](https://github.com/danburzo/percollate) - 一个命令行工具，可将网页转换为漂亮的，可读的PDF，EPUB或HTML文档。
  - [pdf-lib](https://github.com/Hopding/pdf-lib) - 在任意JavaScript环境中创建和修改PDF文档。
  - [pdf2json](https://github.com/modesty/pdf2json) - PDF文件解析器，它将PDF二进制文件转换为基于文本的JSON。

- PPT
  - [nodeppt](https://github.com/ksky521/nodeppt) - Web端展示端PPT工具。

### 操作系统识别

- [systeminformation](https://github.com/sebhildebrandt/systeminformation) - 获取硬件和软件系统信息。
- [is-wsl](https://github.com/sindresorhus/is-wsl) - 判断当前是否是否为WSL (适用于Linux的Windows子系统)。
- [os-name](https://github.com/sindresorhus/os-name) - 获取当前操作系统的名字。
- [getos](https://github.com/retrohacker/getos) - 获取当前操作系统名称，包括Linux的发行版名称。
- [is-windows](https://github.com/jonschlinkert/is-windows) - 判断当前系统是否为Windows。

### 文件压缩解压

- [jszip](https://github.com/Stuk/jszip) - 使用JavaScript创建、读取、编辑.zip文件。
- [adm-zip](https://github.com/cthackers/adm-zip) - 使用JavaScript创建、读取、编辑.zip文件。
- [node-tar](https://github.com/npm/node-tar) - 快速且功能齐全的Tar。
- [tar-fs](https://github.com/mafintosh/tar-fs) - tar-fs允许您将目录打包到tar格式压缩包中，并将tar格式压缩包提取到目录中。
- [7zip](https://github.com/fritx/win-7zip) - Windows包压缩/解压 - 7zip。

### 最小化

- [UglifyJS](https://github.com/mishoo/UglifyJS) - JavaScript压缩工具。
- [imagemin](https://github.com/imagemin/imagemin) - Image压缩工具。
- [babel-minify](https://github.com/babel/minify) - 基于Babel工具链的 ES6+ 压缩库。
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS压缩工具。
- [minimize](https://github.com/Swaagie/minimize) - HTML压缩工具。

### 邮箱

- [Nylas Mail](https://github.com/nylas/nylas-mail) - 构建在现代Web技术的高扩展性邮件客户端程序。
- [Nodemailer](https://github.com/nodemailer/nodemailer) - 使用Node.js轻松发送电子邮件。
- [Email Templates](https://github.com/forwardemail/email-templates) - 创建、预览和发送自定义电子邮件模板。
- [emailjs](https://github.com/eleith/emailjs) - 向任何SMTP服务器发送带有附件的文本/HTML电子邮件。
- [mjml](https://github.com/mjmlio/mjml) - 旨在减少创建响应电子邮件的痛苦的标记语言。

### 网络

- [get-port](https://github.com/sindresorhus/get-port) - 获取一个可用的端口。
- [request-ip](https://github.com/pbojinov/request-ip) - 在服务器中获取请求的IP地址。
- [netcat](https://github.com/roccomuso/netcat) - 纯JS中的Netcat端口。
- [getmac](https://github.com/bevry/getmac) -  获取电脑的MAC地址。
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP客户端和服务器。
- [ipify](https://github.com/sindresorhus/ipify) - 获取你的公网IP地址。
- [address](https://github.com/node-modules/address) - 获取当前机器IP地址和MAC地址。

### HTTP

- 请求库
  - [axios](https://github.com/mzabriskie/axios) - 基于Promise 的HTTP客户端（也可以在浏览器中工作）。
  - [request](https://github.com/request/request) - 🏊🏾 简单的 HTTP 请求客户端。
  - [superagent](https://github.com/visionmedia/superagent) - HTTP请求库。
  - [got](https://github.com/sindresorhus/got) - 更好的基于内建“http”模块接口实现。
  - [node-fetch](https://github.com/bitinn/node-fetch) - Node.js的 `window.fetch` 实现。
  - [needle](https://github.com/tomas/needle) - 灵活，基于流的HTTP Node.js客户端请求库。支持proxy，iconv，cookie，deflate和multipart。
  - [download](https://github.com/kevva/download) - 轻松下载和提取文件。
  - [urllib](https://github.com/node-modules/urllib) - 在复杂世界中请求HTTP/HTTPS的URL。
  - [gotql](https://github.com/khaosdoctor/gotql) - 基于[got](https://github.com/sindresorhus/got)构建的GraphQL请求库。
  - [wreck](https://github.com/hapijs/wreck) - HTTP 客户端工具。
  - [cacheable-request](https://github.com/lukechilds/cacheable-request) - 使用符合RFC的缓存封装的本机HTTP请求库。
  - [gh-got](https://github.com/sindresorhus/gh-got) - 基于"got"封装，与GitHub API更方便的交互。
  - [flashheart](https://github.com/bbc/flashheart) - REST 客户端。

- 服务端库
  - [http-server](https://github.com/http-party/http-server) - 零配置的命令行Http服务端。
  - [anywhere](https://github.com/JacksonTian/anywhere) - 随启随用的静态文件服务器。
  - [http-fake-backend](https://github.com/micromata/http-fake-backend) - 通过可配置的路由，提供JSON文件或JavaScript对象来构建伪造的后端。
  - [json-server](https://github.com/typicode/json-server) - 在不到30秒的时间内获得具有零编码的完整伪造的REST API。

- 代理
  - [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP代理。
  - [https-proxy-agent](https://github.com/TooTallNate/node-https-proxy-agent) - HTTP(S) 代理 `http.Agent`实现。
  - [global-agent](https://github.com/gajus/global-agent) - 可以使用环境变量配置的全局 HTTP/HTTPS 代理。
  - [fast-proxy](https://github.com/fastify/fast-proxy) - Node.js框架，使您可以将http请求转发到另一个HTTP服务器。 支持的协议：HTTP，HTTPS，HTTP2。

- 中间件
  - [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) - ⚡用于connect，express和browser-sync的单线Node.js Http代理中间件。

### 验证

- [Passport](https://github.com/jaredhanson/passport) - 简单的身份验证。
- [Grant](https://github.com/simov/grant) - 适用于Express，Koa，Hapi，Fastify，AWS Lambda，Azure，Google Cloud，Vercel等的OAuth程序。
- [permit](https://github.com/ianstormtaylor/permit) - 用于构建Node.js API的非标准认证库。

### 授权

- [CASL](https://github.com/stalniy/casl) - 同构授权用于可视化界面和API。
- [node-casbin](https://github.com/casbin/node-casbin) - 支持访问控制模型（如ACL，RBAC和ABAC）的授权库。

### 分布式

- [node-zookeeper-client](https://github.com/alexguan/node-zookeeper-client) - 纯JavaScript ZooKeeper客户端。

### RPC

- [grpc-js](https://github.com/grpc/grpc-node/tree/master/packages/grpc-js) - 纯JavaScript gRPC客户端。
- [jayson](https://github.com/tedeh/jayson) - Jayson是用于Node.js的简单但功能强大的JSON-RPC 2.0 / 1.0客户端和服务器。
- [sofa-rpc-node](https://github.com/sofastack/sofa-rpc-node) - SOFARPC Node是高性能、高可扩展性、产品级Node.js RPC框架。

### 爬虫

- [node-crawler](https://github.com/bda-research/node-crawler) - NodeJS Web爬虫 + 服务端jQuery。
- [x-ray](https://github.com/lapwinglabs/x-ray) - 具有分页的Web抓取爬虫。
- [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - 使用Chrome无头浏览器的分布式爬虫。
- [node-osmosis](https://github.com/rchipka/node-osmosis) - Node.js的HTML / XML解析器和Web抓取工具。
- [scrape-it](https://github.com/IonicaBizau/scrape-it) - 适用于人类的Node.js抓取工具。
- [scraperjs](https://github.com/ruipgil/scraperjs) - 完整而多功能的Web抓取器。
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - 事件驱动的Web爬虫。
- [web-scraper-chrome-extension](https://github.com/martinsbalodis/web-scraper-chrome-extension) -实现为Chrome插件的Web数据抽取工具。
- [webster](https://github.com/zhuyingda/webster) - 一个可靠的Web爬虫框架，可以在网页中抓取Ajax和js呈现的内容。
- [supercrawler](https://github.com/brendonboshell/supercrawler) - 定义自定义处理程序以解析内容。 遵守robots.txt，速率限制和并发限制。
- [Squidwarc](https://github.com/n0tan3rd/squidwarc) - 高保真度，用户可编写脚本的归档爬虫程序，使用带头或不带头的Chrome或Chromium。
- [js-crawler](https://github.com/antivanov/js-crawler) - 适用于Node.JS的Web爬虫，同时支持HTTP和HTTPS。

### AST

- 解析器
  - [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript解析器。
  - [antlr](https://github.com/antlr/antlr4) - ANTLR (ANother Tool for Language Recognition)是一个用于阅读、处理、执行和翻译结构化文本或二进制文件的强大的解析生成器。
  - [acorn](https://github.com/acornjs/acorn/tree/master/acorn) - 小巧、快速的JavaScript解析器。
  - [esprima](https://github.com/jquery/esprima) - 高性能、符合ECMASCRIPT标准的解析器。
  - [recast](https://github.com/benjamn/recast) - JavaScript语法树转换器，非破坏性漂亮print和自动source map生成器。
  - [espree](https://github.com/eslint/espree) - 与Esprima兼容的JavaScript解析器。
  - [csstree](https://github.com/csstree/csstree) - 基于W3C标准和浏览器标准实现，包含快速详细的解析器、遍历器、生成器、词法解析的CSS工具集。
  - [himalaya](https://github.com/andrejewski/himalaya) - 将HTML转化为JSON的解析器。
  - [es-module-lexer](https://github.com/guybedford/es-module-lexer) - 低开销的词法分析器，专门用于ES模块快速分析解析。
  - [dt-sql-parser](https://github.com/DTStack/dt-sql-parser) - 大数据的SQL解析器，用antlr4构建。

- 遍历
  - [acorn-walker](https://github.com/acornjs/acorn/tree/master/acorn-walk) - 小巧、快速的JavaScript解析器。
  - [estraverse](https://github.com/estools/estraverse) - ECMAScript JS AST遍历功能。

- 代码生成
  - [escodegen](https://github.com/estools/escodegen) - ECMAScript代码生成。
  - [astring](https://github.com/davidbonnet/astring) - 🌳 小巧快速的JavaScript代码生成器（通过ESTree兼容的AST）。

- JavaScript解释器
  - [JS-Interpreter](https://github.com/NeilFraser/JS-Interpreter) - JavaScript中沙箱解释器。
  - [jsjs](https://github.com/bramblex/jsjs) - 简易的 JavaScript 元循环解释器。
  - [sval](https://github.com/Siubaak/sval) - 使用JavaScript编写的JavaScript解释器。

- 其他
  - [astexplorer](https://github.com/fkling/astexplorer) - 使用多种解析器的AST Web可视化工具。
  - [estree-walker](https://github.com/Rich-Harris/estree-walker) - 用于遍历ESTree兼容树的AST。
  - [periscopic](https://github.com/Rich-Harris/periscopic) - 用于分析符合ESTree的AST的作用域的工具。

### 设计稿转代码（D2C）
- [psd.js](https://github.com/meltingice/psd.js) - 在Node.js和浏览器中解析Photoshop PSD文件。

### 沙箱

- [vm2](https://github.com/patriksimek/vm2) - Node.js高级虚拟机/沙箱。
- [sandbox](https://github.com/gf3/sandbox) - 用于Node.js漂亮的JavaScript沙箱。

### 机器学习 和 神经网络

- [tfjs](https://github.com/tensorflow/tfjs) - 一个WebGL加速的JavaScript库，用于训练和部署ML模型（Tensorflow官方）。
- [brain.js](https://github.com/BrainJS/brain.js) - 基于模型训练的神经网络 JS 库，支持浏览器和 Node.js。
- [pipcook](https://github.com/alibaba/pipcook) - 为Web开发者提供的机器学习平台。
- [onnxjs](https://github.com/microsoft/onnxjs) - 使用JavaScript运行ONNX模型。
- [tensorflow-nodejs](https://github.com/yorkie/tensorflow-nodejs) - TensorFlow Node.js为Node.js用户提供常用的JavaScript语言绑定和高级API。

### 自然语言处理

- [compromise](https://github.com/spencermountain/compromise) - 自然语言处理。
- [natural](https://github.com/NaturalNode/natural) - 自然语言设施。
- [nlp.js](https://github.com/axa-group/nlp.js) - 构建机器人，具有实体提取、情感分析、自动语言识别等功能。
- [franc](https://github.com/wooorm/franc) - 检测文本使用的语言。
- [sentiment](https://github.com/thisandagain/sentiment) - 基于AFINN的Node.js情感判断库。
- [retext](https://github.com/wooorm/retext) - 一个可扩展的自然语言系统。
- [leven](https://github.com/sindresorhus/leven) - 使用Levenshtein距离算法测量两个字符串之间的差异。