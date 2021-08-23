> 该项目受 [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) 启发
>
> 原本是希望在原仓库中提供中文版，但跟该作者沟通，作者不希望添加本地化翻译增加维护工作量；且该库有很多国内用户常见的库并未收录，分类体系也不符合我的预期
>
> 故此另开仓库，希望可以更好的满足国内开发者的需求。

> 同时推荐你查看我另一个仓库 [awesome-frontend](https://github.com/huaize2020/awesome-frontend)!

[English](./README-en.md) | 简体中文

## 目录

- [目录](#目录)
- [官方资源](#官方资源)
- [资源](#资源)
  - [工具](#工具)
  - [教程](#教程)
- [GIT仓库](#git仓库)
  - [文本](#文本)
  - [数字](#数字)
  - [数学运算](#数学运算)
  - [日期 和 时间](#日期-和-时间)
  - [正则/通配符匹配](#正则通配符匹配)
  - [URL](#url)
  - [JSON / JSON Schema](#json--json-schema)
  - [图像处理](#图像处理)
  - [音频 / 视频处理](#音频--视频处理)
  - [字体](#字体)
  - [颜色](#颜色)
  - [加解密](#加解密)
  - [流](#流)
  - [检测/判断](#检测判断)
  - [数据校验](#数据校验)
  - [函数式编程](#函数式编程)
  - [流程控制](#流程控制)
  - [控制反转/依赖注入](#控制反转依赖注入)
  - [Shell](#shell)
  - [环境](#环境)
  - [事件](#事件)
  - [命令行工具](#命令行工具)
  - [Node.js管理工具](#nodejs管理工具)
  - [NPM](#npm)
  - [Monorepo](#monorepo)
  - [文件系统](#文件系统)
  - [解析工具](#解析工具)
  - [Git](#git)
  - [日志](#日志)
  - [进程管理](#进程管理)
  - [代码校验 和 格式化工具](#代码校验-和-格式化工具)
  - [配置工具](#配置工具)
  - [构建工具](#构建工具)
  - [模板引擎](#模板引擎)
  - [Web框架](#web框架)
  - [GraphQL](#graphql)
  - [内容管理系统 (CMS)](#内容管理系统-cms)
  - [静态网站生成 & 博客](#静态网站生成--博客)
  - [文档生成](#文档生成)
  - [接口管理](#接口管理)
  - [桌面应用程序](#桌面应用程序)
  - [实时通信](#实时通信)
  - [任务队列](#任务队列)
  - [定时任务](#定时任务)
  - [调试](#调试)
  - [剖析/分析](#剖析分析)
  - [性能优化](#性能优化)
  - [应用性能监控 (APM)](#应用性能监控-apm)
  - [论坛](#论坛)
  - [数据库](#数据库)
  - [缓存](#缓存)
  - [搜索引擎](#搜索引擎)
  - [Serverless](#serverless)
  - [自动化 & 机器人流程自动化 - RPA](#自动化--机器人流程自动化---rpa)
  - [测试相关](#测试相关)
  - [办公软件](#办公软件)
  - [操作系统识别](#操作系统识别)
  - [压缩解压](#压缩解压)
  - [最小化](#最小化)
  - [邮箱](#邮箱)
  - [网络](#网络)
  - [HTTP](#http)
  - [验证](#验证)
  - [授权 / 鉴权](#授权--鉴权)
  - [分布式](#分布式)
  - [序列化](#序列化)
  - [RPC](#rpc)
  - [服务端DOM](#服务端dom)
  - [爬虫](#爬虫)
  - [AST](#ast)
  - [WebAssembly](#webassembly)
  - [设计稿转代码（D2C）](#设计稿转代码d2c)
  - [沙箱](#沙箱)
  - [硬件](#硬件)
  - [物联网IoT](#物联网iot)
  - [机器学习 和 神经网络](#机器学习-和-神经网络)
  - [自然语言处理](#自然语言处理)
  - [OCR](#ocr)
  - [比特币](#比特币)
- [项目](#项目)
  - [低代码（Lowcode）](#低代码lowcode)

## 官方资源

- [官网](https://nodejs.org)
- [文档](https://nodejs.org/dist/latest/docs/api/)
- [仓库](https://github.com/nodejs/node)

## 资源

### 工具

- [openbase](https://openbase.com/) - 让你每次都要找到合适的包。目前支持JavaScript，即将推出更多语言。
- [npm.devtool](https://npm.devtool.tech/) - 找到最适合您的包，分析您的项目技术栈。

### 教程

- [Node.js Best Practices](https://github.com/goldbergyoni/nodebestpractices/blob/master/README.chinese.md) - Node.js最佳体验列表。

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
  - [normalize-newline](https://github.com/sindresorhus/normalize-newline) - Normalize the newline characters in a string to `\n`.
  - [min-indent](https://github.com/jamiebuilds/min-indent) - 取每一行最少前置空格数。
  - [trim-right](https://github.com/sindresorhus/trim-right) - 与 String#trim() 类似，但仅删除右侧的空格。
  - [splice-string](https://github.com/sindresorhus/splice-string) - 移除或替换字符串的一部分。类似`Array#splice`.

- 国际化
  - [i18next](https://github.com/i18next/i18next) - 国际化框架。
  - [i18n-node](https://github.com/mashpie/i18n-node) - 具有动态JSON存储的简单翻译模块。
  - [babelfish](https://github.com/nodeca/babelfish) - 适用于JavaScript的人性化i18n（node.js +浏览器）。

- 唯一ID
  - [nanoid](https://github.com/ai/nanoid) - 小巧、安全、URL友好、唯一的字符串ID生成器。
  - [uuid](https://github.com/uuidjs/uuid) - 在JavaScript中生成符合RFC规范的UUID。
  - [shortid](https://github.com/dylang/shortid) - 短ID生成器。 网址友好。 不可预测的。 集群兼容。
  - [cuid](https://github.com/ericelliott/cuid) - 针对水平扩展和性能优化的抗冲突ids。
  - [ulid](https://github.com/ulid/javascript) - 通用唯一词典分类排序标识符。
  - [uuid-js](https://github.com/pnegri/uuid-js) - 用于生成和解析 UUID、TimeUUID 并根据日期生成 TimeUUID 以供范围选择。
  - [pure-uuid](https://github.com/rse/pure-uuid) - 基于纯JavaScript全局唯一ID(UUID)。

- 编码/解码
  - [he](https://github.com/mathiasbynens/he) - HTML实体编码器/解码器。
  - [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - 转换字符编码。
  - [jschardet](https://github.com/aadsm/jschardet) - JavaScript编码自动识别 (Python版chardet的实现)。

- 差异对比
  - [jsdiff](https://github.com/kpdecker/jsdiff) - 一种JavaScript文本差异实现。
  - [recursive-diff](https://github.com/cosmicanant/recursive-diff) - 查找两个JavaScript对象的差异，支持数组、数字、日期和其他原始数据类型。

- 其他
  - [StegCloak](https://github.com/kurolabs/stegcloak) - 基于纯JavaScript开发的隐写功能模块，StegCloak可以对文本中的机密信息进行压缩和加密，然后再使用特殊的Unicode不可见字符来隐藏它。
  - [unhomoglyph](https://github.com/nodeca/unhomoglyph) - 规范视觉上相似的unicode字符。

### 数字

- [Numeral.js](https://github.com/adamwdraper/Numeral-js) - 格式化和操作数字。
- [bignumber.js](https://github.com/MikeMcl/bignumber.js) - 用于任意精度十进制和非十进制算术的 JavaScript 库。
- [decimal.js](https://github.com/MikeMcl/decimal.js) - JavaScript的任意精度的十进制类型。
- [big.js](https://github.com/MikeMcl/big.js) - 一个小型，快速的JavaScript库，用于任意精度的十进制算术运算。
- [random-js](https://github.com/ckknight/random-js) - 一个 JavaScript 随机数生成库。
- [round-to](https://github.com/sindresorhus/round-to) - 将数字四舍五入到指定的小数位数：`1.234`→`1.2`。
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
- [timeago.js](https://github.com/hustcc/timeago.js) - timeago.js是一个很小的（2.0 kb）库，用于使用 *** time ago 语句格式化日期。
- [ms](https://github.com/vercel/ms) - 毫秒转换工具。
- [dateformat](https://github.com/felixge/node-dateformat) - 日期格式化。
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - 将毫秒转换为人类可读的字符串，如: `1337000000` → `15d 11h 23m 20s`。
- [strftime](https://github.com/samsonjs/strftime) - JavaScript版时间格式化Strftime。
- [node-microtime](https://github.com/wadey/node-microtime) - 以微秒为单位获取当前时间。
- [date-utils](https://github.com/JerrySievert/date-utils) - 用于Node.js和浏览器的日期垫片（Polyfills）。
- [pretty-hrtime](https://github.com/robrich/pretty-hrtime) - 将process.hrtime()的结果转换为人可读性的字符串。
- [humanize-ms](https://github.com/node-modules/humanize-ms) - 将人类可读的时间转换为毫秒。

### 正则/通配符匹配

- [path-to-regexp](https://github.com/pillarjs/path-to-regexp) - 将路径字符串（如`/user/:name`）转化为正则。
- [minimatch](https://github.com/isaacs/minimatch) - 最小匹配工具。
- [micromatch](https://github.com/micromatch/micromatch) - 高度优化的通配符和全局匹配库。更快，直接替换到 minimatch 和 multimatch。由webpack、babel core、yarn、jest、browser-sync、documentation.js、stylelint、nyc、ava以及许多其他资源使用！
- [randexp.js](https://github.com/fent/randexp.js) - 根据给定的正则表达式，生成随机字符串。
- [safe-regex](https://github.com/substack/safe-regex) - 检测可能是灾难性的、指数时间的正则表达式。
- [matcher](https://github.com/sindresorhus/matcher) - 简单通配符匹配。
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - 转义特殊正则字符。
- [multimatch](https://github.com/sindresorhus/multimatch) - 扩展 minimatch.match() 以支持多种模式。
- [execall](https://github.com/sindresorhus/execall) - 在字符串中查找多个RegExp匹配项。

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

### JSON / JSON Schema

- [json5](https://github.com/json5/json5) - JSON5是对JSON的扩展，其目的是能够更加容易的阅读和编写。
- [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - 对比JSON对象，并生成差异和Patch信息。
- [json-schema-faker](https://github.com/json-schema-faker/json-schema-faker) - JSON-Schema + 假数据生成器。
- [fast-json-stringify](https://github.com/fastify/fast-json-stringify) - 比JSON.stringify()快2倍。
- [jsonfile](https://github.com/jprichardson/node-jsonfile) - 轻松读写JSON文件。
- [jsonata](https://github.com/jsonata-js/jsonata) - JSONata 查询和转换语言 - http://jsonata.org
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
- [pixelmatch](https://github.com/mapbox/pixelmatch) - 最小、最简单、最快的 JavaScript 像素级图像比较库。
- [Resemble.js](https://github.com/rsmbl/Resemble.js) - 图像分析和比较。
- [pica](https://github.com/nodeca/pica) - 使用纯JS中的高质量和快速调整大小（lanczos3）。 当不允许像素化时替代canvas drawImage()。
- [jsQR](https://github.com/cozmo/jsQR) - 一个纯javascript的二维码读取库。 该库接收原始图像，并将定位、提取和解析其中发现的任何二维码。
- [lwip](https://github.com/EyalAr/lwip) - 不需要ImageMagick的轻量级图像处理器。
- [gifski](https://github.com/ImageOptim/gifski) - 基于 libimagequant (pngquant) 的 GIF 编码器。 从糟糕的 GIF 格式中挤出最大可能的质量。
- [svg-captcha](https://github.com/produck/svg-captcha) - Node.js中生成SVG验证码。
- [probe-image-size](https://github.com/nodeca/probe-image-size) - 无需完全下载即可获取大多数图像格式的大小.
- [omggif](https://github.com/deanm/omggif) - GIF 89a编码解码器。
- [jpeg-js](https://github.com/jpeg-js/jpeg-js) - 使用纯JavaScript的JPEG编码和解码器。
- [pngjs](https://github.com/lukeapage/pngjs) - 简单的PNG编码解码器。
- [get-pixels](https://github.com/scijs/get-pixels) - 将图像读入ndarray。
- [gifencoder](https://github.com/eugeneware/gifencoder) - Node.js 服务器端动画 gif 生成。
- [image-type](https://github.com/sindresorhus/image-type) - 检测Buffer / Uint8Array的图像类型。
- [node-pngquant](https://github.com/papandreou/node-pngquant) - pngquant 作为可读/可写流操作png。
- [node-bitmap](https://github.com/nowelium/node-bitmap) - 纯JavaScript Bitmap库。

### 音频 / 视频处理

- [fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) - FFMPEG的流畅API (http://www.ffmpeg.org)
- [FFCreator](https://github.com/tnfe/FFCreator) - 一个基于node.js的高速短视频加工库。
- [node-ffmpeg](https://github.com/damianociarla/node-ffmpeg) - Nodejs版Ffmpeg模块。

### 字体

- [font-spider](https://github.com/aui/font-spider) - 字蛛是一个智能 WebFont 压缩工具，它能自动分析出页面使用的 WebFont 并进行按需压缩。
- [svg2ttf](https://github.com/fontello/svg2ttf) - 字体转换器, SVG格式转化为TTF。
- [ttf2woff](https://github.com/fontello/ttf2woff) - 字体转换器, TTF格式转化为WOFF。
- [svgicons2svgfont](https://github.com/nfroidure/svgicons2svgfont) - 连接 SVG 图标并输出 SVG 字体。
- [webfont](https://github.com/itgalaxy/webfont) - 很棒的网页字体生成器。
- [ttf2eot](https://github.com/fontello/ttf2eot) - 字体转换器, TTF格式转化为EOT。
- [wawoff2](https://github.com/fontello/wawoff2) - 使用 WebAssembly 构建 Google 的 woff2。

### 颜色

- [chroma](https://github.com/gka/chroma.js) - JavaScript库，用于各种颜色处理。
- [randomColor](https://github.com/davidmerfield/randomColor) - 一个小型脚本，用于优雅的生成颜色。
- [rgbaster](https://github.com/briangonzalez/rgbaster.js) - 🎨一个简单的库，用于从图像中提取主色。
- [TinyColor](https://github.com/bgrins/TinyColor) - 快速、小型的颜色操作和转换库。
- [onecolor](https://github.com/One-com/one-color) - 面向对象的JavaScript颜色解析器/计算工具包，支持RGB，HSV，HSL，CMYK和alpha通道。 颜色空间之间的转换是隐式进行的，并且所有方法都返回新对象，而不是对现有实例进行突变。 可在浏览器和Node.js中使用。

### 加解密

- [crypto-js](https://github.com/brix/crypto-js) - JavaScript加密标准库。
- [sjcl](https://github.com/bitwiseshiftleft/sjcl) - 斯坦福 Javascript 加密库。
- [bcrypt](https://github.com/kelektiv/node.bcrypt.js) - Node.js版Bcrypt。
- [jsencrypt](https://github.com/travist/jsencrypt) - 用于执行OpenSSL RSA加密、解密和密钥生成的Javascript库。
- [bcrypt.js](https://github.com/dcodeIO/bcrypt.js) - 经过优化bcrypt库，使用纯JavaScript且零依赖。
- [jsrsasign](https://github.com/kjur/jsrsasign) - "jsrsasign"（RSA Sign JavaScript库）是一个开源的免费加密库，支持纯JavaScript中的RSA/RSAPSS/ECDSA/DSA签名/验证、ASN.1、PKCS#1/5/8私钥/公钥、X.509证书、CRL、OCSP、CMS SignedData、TimeStamp、CAdES JSON Web签名/令牌。
- [node-rsa](https://github.com/rzcoder/node-rsa) - Node.js RSA库。
- [aes-js](https://github.com/ricmoo/aes-js) - AES的纯JavaScript实现。
- [node-md5](https://github.com/pvorb/node-md5) - 一个JavaScript函数，用于使用MD5对消息进行哈希处理。
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - 微型哈希模块，在Node.js和浏览器中使用原生crypto API。
- [hash.js](https://github.com/indutny/hash.js) - 使用纯JavaScript的哈希实现。
- [sm-crypto](https://github.com/JuneAndGreen/sm-crypto) - sm2, sm3, sm4的JavaScript实现。
- [sha.js](https://github.com/crypto-browserify/sha.js) - 使用纯JavaScript中的流式SHA哈希。
- [hash-sum](https://github.com/bevacqua/hash-sum) - 极快的唯一哈希生成器。
- [cryptr](https://github.com/MauriceButler/cryptr) - 非常基础的加密和解密Node.js模块。
- [pbkdf2](https://github.com/crypto-browserify/pbkdf2) - 在Node中具有任何受支持的哈希算法PBKDF2。
- [bcrypt-pbkdf](https://github.com/joyent/node-bcrypt-pbkdf) - POpenBSD `bcrypt_pbkdf` Javascript实现。

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

### 检测/判断

- [is.js](https://github.com/arasatasaygin/is.js) - 微型检查库。
- [is-promise](https://github.com/then/is-promise) - 测试对象是否看起来像一个 Promises-a+ promise。
- [is-ci](https://github.com/watson/is-ci) - 判断当前环境是否为CI服务器。
- [is](https://github.com/enricomarino/is) - JavaScript类型测试库。
- [is-type-of](https://github.com/node-modules/is-type-of) - Node.js完整类型判断。
- [is-stream](https://github.com/sindresorhus/is-stream) - 判断对象是否为流对象。
- [is-utf8](https://github.com/wayfind/is-utf8) - 判断Buffer对象是否UTF8编码。
- [core-util-is](https://github.com/isaacs/core-util-is) - Node.js核心工具 util.is* 函数。
- [is-ip](https://github.com/sindresorhus/is-ip) - 检查字符串是否为IP地址。
- [isstream](https://github.com/rvagg/isstream) - 判断对象是否为流对象。
- [is-class](https://github.com/miguelmota/is-class) - 判断函数是否为 ES6类(class) 类型。
- [isexe](https://github.com/isaacs/isexe) - 检查文件是否可执行文件。
- [is-type](https://github.com/juliangruber/is-type) - Node.js核心类型判断。
- [is-md5](https://github.com/imanhodjaev/is-md5) - JavaScript实用程序，用于检查字符串是否为md5加密。
- [is-core-module](https://github.com/inspect-js/is-core-module) - 判断一个说明符 是否为 Node.js 核心模块。

### 数据校验

- [validator.js](https://github.com/validatorjs/validator.js) - 字符串校验库。
- [joi](https://github.com/hapijs/joi) - 基于JavaScript对象的对象模式描述语言和验证器。
- [async-validator](https://github.com/yiminghe/async-validator) - 异步校验。
- [class-validator](https://github.com/typestack/class-validator) - 基于装饰器属性校验的类校验器。
- [ajv](https://github.com/epoberezkin/ajv) - 最快的JSON Schema验证器。支持JSON Schema draft-04/06/07/2019-09/2020-12 and JSON类型定义(RFC8927)。
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - 用简单和可组合的方式在JavaScript和TypeScript中校验数据。
- [v8n](https://github.com/imbrn/v8n) - 流畅的JavaScript校验库。
- [forgJs](https://github.com/oussamahamdaoui/forgJs) - 轻量的JavaScript对象校验器。
- [jsonschema](https://github.com/tdegrunt/jsonschema) - JSON Schema校验器.
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

### 流程控制

- Promises
  - [Bluebird](https://github.com/petkaantonov/bluebird) - Bluebird 是一个功能齐全的Promise库，专注于创新功能和性能。
  - [co](https://github.com/tj/co) - 拥有流程控制优势的Nodejs终极生成器（支持 thunks、promises 等）。
  - [pify](https://github.com/sindresorhus/pify) - 将回调式的函数 Promisify 化。
  - [p-map](https://github.com/sindresorhus/p-map) - 并发的Map执行 Promise 。
  - [delay](https://github.com/sindresorhus/delay) - 将 Promise 延迟指定的时间。
  - [promise-memoize](https://github.com/nodeca/promise-memoize) - 记忆化Promise返回函数，带过期和prefetch预取功能。
  - [valvelet](https://github.com/lpinca/valvelet) - 限制Promise返回函数的执行率(限流)。

- 可观察对象
  - [RxJS](https://github.com/ReactiveX/RxJS) - 响应式编程。
  - [zen-observable](https://github.com/zenparsing/zen-observable) - 可观察对象的实现。
  - [observable-to-promise](https://github.com/sindresorhus/observable-to-promise) - 将可观察对象转化为 Promise.

- 回调函数
  - [async](https://github.com/caolan/async) - 提供直接、强大的函数们来处理异步问题。

- 管道
  - [js-csp](https://github.com/ubolonton/js-csp) - 用于JavaScript的顺序通信进程CSP（如 ClojureScript core.async 或 Go）。

### 控制反转/依赖注入

- [InversifyJS](https://github.com/inversify/InversifyJS) - 功能强大且轻便的控制反转容器。
- [injection-js](https://github.com/mgechev/injection-js) - 5.1K中的JavaScript和TypeScript的依赖注入库。它提取自Angular的ReflectiveInjector，这意味着它设计合理，功能完整、快速、可靠且经过良好测试。
- [power-di](https://github.com/zhang740/power-di) - 轻量的依赖注入库。

### Shell

- [zx](https://github.com/google/zx) - 用于编写更好脚本的工具。
- [shelljs](https://github.com/shelljs/shelljs) - 跨平台Unix shell命令。
- [execa](https://github.com/sindresorhus/execa) - 跨平台实现子进程执行 `child_process.{execFile,exec}`。
- [node-windows](https://github.com/coreybutler/node-windows) - Node.js上支持的Windows脚本。如(daemons, eventlog, UAC等)。
- [shx](https://github.com/shelljs/shx) - Node的可移植Shell命令。
- [clipboardy](https://github.com/sindresorhus/clipboardy) - 跨平台的复制/粘贴。
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - 跨平台实现 `child_process.spawn()`。
- [parallelshell](https://github.com/darkguy2008/parallelshell) - 并行运行多个 shell 命令。
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - 跨平台的复制/粘贴。
- [gulp-execa](https://github.com/ehmicky/gulp-execa) - 在Gulp中跨平台命令执行。
- [runscript](https://github.com/node-modules/runscript) - 更容易的运行脚本命令。
- [cross-spawn-promise](https://github.com/zentrick/cross-spawn-promise) - Promise化的cross-spawn。
- [shell-exec](https://github.com/tiaanduplessis/shell-exec) - 通过系统Shell执行命令。

### 环境

- [dotenv](https://github.com/motdotla/dotenv) - 从 .env文件 加载用于nodejs项目的环境变量。
- [cross-env](https://github.com/kentcdodds/cross-env) - 跨平台设置环境变量。
- [envinfo](https://github.com/tabrindle/envinfo) - 生成关于您的开发环境的报告，用于调试和问题报告。
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
  - [argparse](https://github.com/nodeca/argparse) - Node.js CLI参数解析。
  - [yargs-parser](https://github.com/yargs/yargs-parser) - yargs在使用，优雅参数解析库.

- Prompt提示
  - [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - 通用可交互命令行工具集合。
  - [prompts](https://github.com/terkelg/prompts) - 轻量、美观、用户友好的交互式命令行提示。
  - [Enquirer](https://github.com/enquirer/enquirer) - 用户友好、直观且易于创建的时尚CLI提示。
  - [node-promptly](https://github.com/moxystudio/node-promptly) - 简单命令行提示实用程序。

- 进度条
  - [progress](https://github.com/visionmedia/node-progress) - Node.js的灵活ascii进度条。
  - [progress-estimator](https://github.com/bvaughn/progress-estimator) - 打印进度条并估计完成Promise所需的时间。
  - [cli-progress](https://github.com/AndiDittrich/Node.CLI-Progress) - 在命令行/终端应用中轻松的使用进度条。

- 样式
  - [chalk](https://github.com/chalk/chalk) - 命令行字符串样式美化工具。
  - [ora](https://github.com/sindresorhus/ora) - 优雅的命令行loading效果。
  - [colors.js](https://github.com/Marak/colors.js) - 获取Node.js控制台的颜色。
  - [listr](https://github.com/SamVerschueren/listr) - 命令行任务列表。
  - [figlet.js](https://github.com/patorjk/figlet.js) - 用 JavaScript 编写的 FIG，旨在完全实现 FIGfont 规范。
  - [kleur](https://github.com/lukeed/kleur) -  使用ANSI颜色格式化命令行文本的最快的Node.js库。
  - [colorette](https://github.com/jorgebucaran/colorette) - 在终端中轻松设置文本的颜色和样式。
  - [qrcode-terminal](https://github.com/gtanner/qrcode-terminal) - 命令行中显示二维码。
  - [boxen](https://github.com/sindresorhus/boxen) - 控制台中创建盒子。
  - [terminal-image](https://github.com/sindresorhus/terminal-image) - 在终端中展示图片。
  - [log-symbols](https://github.com/sindresorhus/log-symbols) - 为不同日志级别添加色彩图标。
  - [gradient-string](https://github.com/bokub/gradient-string) - 终端输出中漂亮的颜色渐变。
  - [figures](https://github.com/sindresorhus/figures) - Windows兜底的Unicode符号。
  - [terminal-link](https://github.com/sindresorhus/terminal-link) - 在终端中创建可点击的链接。
  - [snazzy](https://github.com/standard/snazzy) - 将 JavaScript 标准样式格式化为时尚（即时髦）输出。
  - [columnify](https://github.com/timoxley/columnify) - 创建适合控制台输出的基于文本的列。 支持单元格。
  - [cli-table3](https://github.com/cli-table/cli-table3) - 命令行的漂亮unicode表。
  - [easy-table](https://github.com/eldargab/easy-table) - 漂亮的文本表格。
  - [cli-highlight](https://github.com/felixfbecker/cli-highlight) - 终端的语法高亮显示💻✨
  - [treeify](https://github.com/notatestuser/treeify) - 将javascript对象漂亮地打印为树。
  - [kolorist](https://github.com/marvinhagemeister/kolorist) - 使用输入和输出色彩化的小工具。
  - [console-png](https://github.com/aantthony/console-png) - 在命令行输出中打印PNG图片。

- 编辑器
  - [slap](https://github.com/slap-editor/slap) - 基于命令行终端的类Sublime文本编辑器。

- 其他
  - [commitizen](https://github.com/commitizen/cz-cli) - Commitizen命令行实用程序。
  - [update-notifier](https://github.com/yeoman/update-notifier) - 为你的CLI应用提供的更新提示。
  - [console-stamp](https://github.com/starak/node-console-stamp) - 为NodeJS console方法添加布丁，使其按模式添加时间戳信息。
  - [didyoumean](https://github.com/dcporter/didyoumean.js) - 简单、优化的JS库 和 Node.JS模块，用于将简短的人为的输入匹配到一个可能性列表中。
  - [console-clear](https://github.com/lukeed/console-clear) - 跨平台清空控制台。

### Node.js管理工具

- [nvm](https://github.com/nvm-sh/nvm) - Node.js版本管理工具。
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) -  Node.js版本管理工具Windows版。
- [n](https://github.com/tj/n) - Node.js版本管理工具。
- [fnm](https://github.com/Schniz/fnm) - 🚀 快速、轻量的Node.js版本管理工具，由Rust构建。
- [nodenv](https://github.com/nodenv/nodenv) - 版本管理工具（类似Ruby的 rbenv ），它支持自动切换。
- [nave](https://github.com/isaacs/nave) - Node.js虚拟环境。
- [nvs](https://github.com/jasongin/nvs) - Node Version Switcher - 一个跨平台的工具，用于在 Node.js 的版本之间切换。
- [nodeenv](https://github.com/ekalinin/nodeenv) - 与Python的 virtualenv 兼容的Node.js虚拟环境。

### NPM

- NPM管理工具
  - [pnpm](https://github.com/pnpm/pnpm) - 快速、节省磁盘空间高效的包管理器。
  - [npm](https://github.com/npm/cli) - JavaScript包管理工具。
  - [yarn](https://github.com/yarnpkg/berry) - 现代包管理工具，拆分成多个不同的包。
  - [yalc](https://github.com/wclr/yalc) - 更适用的前端link工具。
  - [nrm](https://github.com/Pana/nrm) - 快速切换npm注册服务商，如npm、cnpm、nj、taobao。
  - [cnpm](https://github.com/cnpm/cnpm) - NPM中国区镜像客户端。

- package.json
  - [read-pkg-up](https://github.com/sindresorhus/read-pkg-up) - 读取最近的package.json文件。
  - [node-pkginfo](https://github.com/indexzero/node-pkginfo) - 从package.json读取属性的简单方法。
  - [pkg-dir](https://github.com/sindresorhus/pkg-dir) - 查找npm包的根目录。
  - [read-pkg](https://github.com/sindresorhus/read-pkg) - 读取package.json文件。
  - [write-pkg](https://github.com/sindresorhus/write-pkg) - 写入package.json文件。
  - [read-package-json-fast](https://github.com/npm/read-package-json-fast) - 类似 read-package-json, 但更快。

- 语义化版本
  - [semver](https://github.com/npm/node-semver) - NPM使用的JavaScript语义化版本号解析器。
  - [compare-versions](https://github.com/omichelsen/compare-versions) - 比较semver版本字符串，找出哪个更大，哪个相等，哪个更小。

- NPM私有部署
  - [verdaccio](https://github.com/verdaccio/verdaccio) - 私有轻量级的NPM镜像。
  - [cnpmjs.org](https://github.com/cnpm/cnpmjs.org) - 企业级私有NPM镜像和Web界面。

- 工具
  - [npm-check-updates](https://github.com/raineorshine/npm-check-updates) - 查找当前package.json依赖允许的更新的版本。
  - [concurrently](https://github.com/kimmobrunfeldt/concurrently) - 并行执行命令，类似 `npm run watch-js & npm run watch-less`但更优。
  - [npm-run-all](https://github.com/mysticatea/npm-run-all) - 命令行工具，同时运行多个npm脚本（并行或串行）。
  - [depcheck](https://github.com/depcheck/depcheck) - 检查你的NPM模块未使用的依赖。
  - [npminstall](https://github.com/cnpm/npminstall) - 使 `npm install` 更快更容易。
  - [validate-npm-package-name](https://github.com/npm/validate-npm-package-name) - 校验给定的字符串 是否为 可接受的 npm 包名称。
  - [npm-home](https://github.com/sindresorhus/npm-home) - 打开npm包页面。
  - [npm-name](https://github.com/sindresorhus/npm-name) - 在npm上检查软件包名称的可用性。
  - [pacote](https://github.com/npm/pacote) - 从npm注册商下载tar压缩文件，并获取包的资源信息。
  - [npm-package-arg](https://github.com/npm/npm-package-arg) - 根据包名解析信息。
  - [npm-registry-fetch](https://github.com/npm/npm-registry-fetch) - 类型fetch()函数，但用于npm仓库。
  - [npm-updater](https://github.com/node-modules/npm-updater) - 检查npm包的更新。

### Monorepo
*(你也许喜欢 [awesome-monorepo](https://github.com/korfuri/awesome-monorepo))*

- [lerna](https://github.com/lerna/lerna) - 用于管理具有多个包的JavaScript项目的工具。
- [rush](https://rushjs.io/) - 可伸缩的monorepo构建管理工具。

### 文件系统

- 通用
  - [fs-extra](https://github.com/jprichardson/node-fs-extra) - 为 `fs` 模块提供额外方法。
  - [graceful-fs](https://github.com/isaacs/node-graceful-fs) - graceful-fs可以替代fs模块，并做了各种改进。
  - [filesize.js](https://github.com/avoidwork/filesize.js) - 生成人类可读的文件大小字符串。
  - [memfs](https://github.com/streamich/memfs) - Node.js API内存文件系统。
  - [fs-jetpack](https://github.com/szwacz/fs-jetpack) - 完全重新设计的文件系统API，方便日常使用。
  - [make-dir](https://github.com/sindresorhus/make-dir) - 递归创建文件夹，类似 `mkdir -p`。
  - [find-up](https://github.com/sindresorhus/find-up) - 通过上级父目录查找文件或目录。
  - [filenamify](https://github.com/sindresorhus/filenamify) - 将字符串转换为有效的文件名。
  - [copyfiles](https://github.com/calvinmetcalf/copyfiles) - 在命令行中复制文件。
  - [filehound](https://github.com/nspragg/filehound) - 灵活流畅的文件系统搜索接口。
  - [move-file](https://github.com/sindresorhus/move-file) - 移动文件，甚至可以跨设备工作。
  - [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - 进程间和机器间文件锁实用工具。
  - [istextorbinary](https://github.com/bevry/istextorbinary) - 检查文件是文本文件还是二进制文件。
  - [mkdirp](https://github.com/isaacs/node-mkdirp) - 递归创建文件夹，类似 `mkdir -p`。
  - [dir-compare](https://github.com/gliviu/dir-compare) - Node JS文件夹对比。
  - [folder-hash](https://github.com/marc136/node-folder-hash) - 为 文件夹或文件 上创建哈希检验码。
  - [lnfs](https://github.com/kevva/lnfs) - 强制创建符号链接。类似`ln -fs`.

- 复制
  - [ncp](https://github.com/AvianFlu/ncp) - 使用Node.js进行异步递归文件复制。
  - [cpy](https://github.com/sindresorhus/cpy) - 文件拷贝。

- 删除
  - [rimraf](https://github.com/isaacs/rimraf) - 递归删除文件，类似 `rm -rf`。
  - [del](https://github.com/sindresorhus/del) - 删除文件/文件夹。

- 临时
  - [temp](https://github.com/bruce/node-temp) - Node.js临时文件、文件夹、流。
  - [tempy](https://github.com/sindresorhus/tempy) - 获取随机的临时文件或目录路径。
  - [temp-dir](https://github.com/sindresorhus/temp-dir) - 获取系统临时文件夹的真实路径。

- 监控
  - [chokidar](https://github.com/paulmillr/chokidar) - 最小且高效的跨平台Watch库。
  - [watchpack](https://github.com/webpack/watchpack) - Watch文件和文件夹。

- 遍历查找
  - [glob](https://github.com/isaacs/node-glob) - Node.js版glob功能。
  - [globby](https://github.com/sindresorhus/globby) - 基于fast-glob，但添加了很多有用的特性。
  - [fast-glob](https://github.com/mrmlnc/fast-glob) - 非常快速且高效的Node.js glob库。
  - [node-sync-glob](https://github.com/AndyOGo/node-sync-glob) - 通过glob模式在本地同步文件和文件夹，包括watch选项。

### 解析工具

- Markdown
  - [marked](https://github.com/markedjs/marked) - Markdown解析器和编译器，专为提高速度而设计。
  - [remark](https://github.com/wooorm/remark) - Markdown处理工具。
  - [markdown-it](https://github.com/markdown-it/markdown-it) - 支持100%通用Markdown标签解析的扩展&语法插件。
  - [turndown](https://github.com/mixmark-io/turndown) - 用 JavaScript 编写的 HTML 到 Markdown 转换器。
  - [remove-markdown](https://github.com/stiang/remove-markdown) - 从文本中删除Markdown内容。

- CSV
  - [PapaParse](https://github.com/mholt/PapaParse) - 快速而强大的 CSV（分隔文本）解析器，可以优雅地处理大文件和格式错误的输入。
  - [node-csv](https://github.com/adaltas/node-csv) - 具有简单api的全功能CSV解析器，并针对大型数据集进行了测试。
  - [csv-parser](https://github.com/mafintosh/csv-parser) - 旨在比其他任何人都快的流式CSV解析器。
  - [neat-csv](https://github.com/sindresorhus/neat-csv) - 快速的CSV解析器。

- YAML
  - [js-yaml](https://github.com/nodeca/js-yaml) - 快速的YAML解析器。
  - [yaml](https://github.com/eemeli/yaml) - YAML 的 JavaScript 解析器和字符串化。

- XML
  - [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - 将XML转换为JavaScript对象的转换器。
  - [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - 验证&解析 XML。
  - [xmlbuilder](https://github.com/oozcitak/xmlbuilder-js) - XML构建器。
  - [js2xmlparser](https://github.com/michaelkourlas/node-js2xmlparser) - 用于将 JavaScript 对象解析为 XML 的流行 Node.js 模块。

- HTML
  - [htmlparser2](https://github.com/fb55/htmlparser2) - 宽容的 HTML 和 XML 解析器。
  - [parse5](https://github.com/inikulin/parse5) - 用于 Node.js 的 HTML 解析/序列化工具集。 WHATWG HTML 标准（又名 HTML5）兼容。
  - [sanitize-html](https://github.com/apostrophecms/sanitize-html) - 清理用户提交的 HTML，在每个元素的基础上保留列入白名单的元素和属性。 建立在 htmlparser2 上，以提高速度和容忍度。
  - [himalaya](https://github.com/andrejewski/himalaya) - 将HTML转化为JSON的解析器。

- CSS
  - [PostCSS](https://github.com/postcss/postcss) - CSS解析工具。
  - [less](https://github.com/less/less.js) - Less动态样式表语言。

- SQL
  - [pgsql-ast-parser](https://github.com/oguimbal/pgsql-ast-parser) - 简单的Postgres SQL解析器。
  - [dt-sql-parser](https://github.com/DTStack/dt-sql-parser) - 大数据的SQL解析器，用antlr4构建。

- Plist
  - [node-bplist-parser](https://github.com/joeferner/node-bplist-parser) - 二进制plist文件解析。

- ini
  - [ini](https://github.com/npm/ini) - ini文件解析和序列化。

- 其他
  - [readability](https://github.com/mozilla/readability) - 可读内容提取库，用于Firefox Reader View的独立提取版本。

### Git

- [husky](https://github.com/typicode/husky) - 现代化的本地Git钩子使操作更加轻松！
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - 用于Node.js和浏览器的 纯 JavaScript git实现！
- [nodegit](https://github.com/nodegit/nodegit) - [libgit2](https://libgit2.org/) 的 Node.js 绑定版本。
- [js-git](https://github.com/creationix/js-git) - Git的JavaScript实现。
- [degit](https://github.com/Rich-Harris/degit) - Degit 制作 git 存储库的副本。用于构建简单的项目脚手架。
- [simple-git](https://github.com/steveukx/git-js) - 一个轻量级的接口，用于在任何 node.js 应用程序中运行 git 命令。
- [gitgraph-node](https://github.com/nicoespeon/gitgraph.js/tree/master/packages/gitgraph-node) - 在 Terminal 绘制 git 流程图（支持浏览器、React）。
- [pre-commit](https://github.com/observing/pre-commit) - 自动在您的git储存库中安装git pre-commit脚本，该脚本在pre-commit上运行您的`npm test`。
- [yorkie](https://github.com/yyx990803/yorkie) -  husky的Fork，让 Git 钩子变得简单(在 vue3 中使用)
- [git-url-parse](https://github.com/IonicaBizau/git-url-parse) - 高级别git解析。
- [git-promise](https://github.com/piuccio/git-promise) - 简单的封装，可运行任何git命令，并使用promise处理其输出。
- [gittar](https://github.com/lukeed/gittar) - 下载/提取git仓库 (GitHub, GitLab, BitBucket)，跨平台和优先离线。
- [parse-git-config](https://github.com/jonschlinkert/parse-git-config) - 将 `.git/config` 解析为 JavaScript 对象。 同步或异步。
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - 从远程仓库中获取标签。
- [giturl](https://github.com/repo-utils/giturl) - 将Git链接转化成Web链接。
- [download-git-repo](https://gitlab.com/flippidippi/download-git-repo) - 下载和提取Git仓库 (支持GitHub, GitLab, Bitbucket)。

### 日志

- [winston](https://github.com/winstonjs/winston) - 多传输异步日志记录库。
- [pino](https://github.com/pinojs/pino) - 受Bunyan启发的超快日志记录库。
- [signale](https://github.com/klauscfhq/signale) - 高度可配置的日志工具。
- [bunyan](https://github.com/trentm/node-bunyan) - 一个用于 Node.js 服务的简单快速的 JSON 日志模块。
- [log4js-node](https://github.com/log4js-node/log4js-node) - 不同于Java log4j的日志记录库。
- [consola](https://github.com/nuxt/consola) - 优雅的Node.js和浏览器日志记录库。
- [loglevel](https://github.com/pimterry/loglevel) - 小巧的轻量级日志记录，添加可靠的日志级别方法来封装任何可用的 console.log 方法。
- [storyboard](https://github.com/guigrpa/storyboard) - 一个Chrome浏览器插件，用于查看日志。
- [cabin](https://github.com/cabinjs/cabin) - 提供日志服务和NPM包。
- [fancy-log](https://github.com/gulpjs/fancy-log) - 带上时间前缀的日志记录库。
- [caterpillar](https://github.com/bevry/caterpillar) - Caterpillar 是 Deno、Node.js 和 Web 浏览器的终极日志系统。日志级别实现了RFC标准。日志条目可以过滤并通过管道传输到各种流，包括多色输出到终端、浏览器的控制台和调试文件。你甚至可以编写自己的转换。
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
- [js-beautify](https://github.com/beautify-web/js-beautify) - Javascript美化工具。
- [xo](https://github.com/xojs/xo) - 带出色默认配置的JavaScript/TypeScript代码校验 (基于ESLint封装)
- [markdownlint](https://github.com/DavidAnson/markdownlint) - Markdown/CommonMark风格检查工具。
- [textlint](https://github.com/textlint/textlint) - Text 和 Markdown 校验和格式化。
- [pretty-quick](https://github.com/azz/pretty-quick) - 快速美化。
- [dtslint](https://github.com/Microsoft/dtslint) - 基于 TSLint 构建的实用程序，用于对 TypeScript 声明 (.d.ts) 文件进行 linting。

### 配置工具

- [node-config](https://github.com/lorenwest/node-config) - Node.js 应用程序配置。
- [nconf](https://github.com/indexzero/nconf) - 可通过文件、环境变量、命令行参数和对象 合并的分层 Node.js 配置。
- [convict](https://github.com/mozilla/node-convict/tree/master/packages/convict) - Convict 扩展了配置 node.js 应用程序的标准模式，提供了更健壮且易于访问。
- [rc](https://github.com/dominictarr/rc) - 懒人的配置加载器。

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
  - [blitz](https://github.com/blitz-js/blitz) - 全栈 React 框架——建立在 Next.js 之上。
- [Meteor](https://github.com/meteor/meteor) - 超简单，无处不在的数据库，在线数据，纯Javascript Web框架。 *（你也许会喜欢 [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Vue服务端渲染框架。
- [Nest](https://github.com/nestjs/nest) -受Angular启发的框架，用于构建高效且可扩展的服务器端应用程序。*(你也许会喜欢 [awesome-nestjs](https://github.com/juliandavidmr/awesome-nestjs))*
- [Koa](https://github.com/koajs/koa) - 由Express背后的团队设计的框架，旨在为Web应用程序和API提供更小，更富表现力和更强大的基础。
- [sails](https://github.com/balderdashy/sails) - Node.js实时MVC框架。
- [Fastify](https://github.com/fastify/fastify) - 快速和低开销的Web框架。
- [Hapi](https://github.com/hapijs/hapi) - 用于创建应用和服务的框架。
- [Egg](https://github.com/eggjs/egg) - 为企业级框架和应用而生。
- [Feathers](https://github.com/feathersjs/feathers) - 基于Express精神构建的微服务框架。
- [LoopBack](https://github.com/strongloop/loopback-next) - 用于创建REST API并轻松连接到后端数据源的强大框架。
- [Restify](https://github.com/restify/node-restify) - 使你能够构建正确的REST Web服务。
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 支持ES2015 +的框架，WebSockets，REST API。
- [total.js](https://github.com/totaljs/framework) - 使用纯JavaScript编写的Node.js框架，类似PHP's Laravel或Python's Django或ASP.NET MVC
- [AdonisJs](http://adonisjs.com) - 基于依赖注入和IoC容器的坚实基础构建的Node.js的真正MVC框架。
- [Micro](https://github.com/zeit/micro) - 具有异步方法的简约微服务框架。
- [Moleculer](https://moleculer.services) - 快速而强大的微服务框架。
- [Midway](https://github.com/midwayjs/midway) - 一个面向未来的云端一体 Node.js 框架。
- [seneca](https://github.com/senecajs/seneca) - 编写微服务的工具包。
- [server](https://github.com/franciscop/server) - 简单而强大的 Node.js 服务器。
- [beidou](https://github.com/alibaba/beidou) - NodeJS & React 同构框架，基于Egg.js开发。
- [Marble.js](https://github.com/marblejs/marble) - 基于TypeScript和RxJS，用于构建服务端应用的函数响应式框架。
- [ActionHero](https://github.com/actionhero/actionhero) - 用于为TCP套接字，WebSocket和HTTP客户端制作可重用和可扩展的API的框架。
- [lad](https://github.com/ladjs/lad) - 最好的Node.js框架，由前Express和Koa团队成员创建。
- [Tinyhttp](https://github.com/talentlessguy/tinyhttp) - 类Express更现代更快的Web框架。
- [daruk](https://github.com/darukjs/daruk) - 基于 typescript 的 Node.js web 框架。
- [Hemera](https://github.com/hemerajs/hemera) - 使用以下工具编写可靠且容错的微服务 [NATS](https://nats.io)。
- [restana](https://github.com/BackendStack21/restana) - 用于构建REST微服务的超快速和简约的框架。
- [CabloyJS](https://github.com/zhennann/Cabloy) - 一款自带工作流引擎的Node.js全栈框架。
- [malagu](https://github.com/cellbang/malagu) - Malagu 是基于 TypeScript 的 Serverless First、可扩展和组件化的应用框架。
- [Zeronode](https://github.com/sfast/zeronode) - 最小的构建块，可实现可靠且容错的微服务。

### GraphQL

- *(你也许喜欢 [awesome-graphql](https://github.com/chentsulin/awesome-graphql#javascript-libraries))*

### 内容管理系统 (CMS)

- [Ghost](https://github.com/TryGhost/Ghost) - 用于专业发布的无头 Node.js CMS。
- [Strapi](https://github.com/strapi/strapi) - 用于构建强大 API 的内容管理框架 (headless-CMS)。
- [KeystoneJS](https://github.com/keystonejs/keystone) - 基于 Express 和 MongoDB 的 CMS 和 Web应用程序平台。
- [AdminBro](https://github.com/SoftwareBrothers/admin-bro) - 为您的所有模型自动生成带有 增删查改(CRUD) 的管理面板。
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - 基于 Express 和 MongoDB，拥有直观的内容编辑和管理的内容管理系统。
- [Tipe](https://github.com/tipeio/tipe) - 面向开发人员的下一代 API优先 CMS。使用离线原型和内置编辑器从 GraphQL Schema 中 生成 API优先 的 CMS。
- [Factor](https://github.com/fiction-com/factor) - Vue.js 仪表板框架 和 无头CMS。

### 静态网站生成 & 博客

- [gatsby](https://github.com/gatsbyjs/gatsby) - 使用React构建快速、现代的应用程序和网站。
- [hexo](https://github.com/hexojs/hexo) - 使用Node.js的快速，简单，强大的博客框架。
- [vuepress](https://github.com/vuejs/vuepress) - 极简的Vue静态网站生成工具。
- [netlify-cms](https://github.com/netlify/netlify-cms) - 基于Git的静态网站生成工具。
- [react-static](https://github.com/react-static/react-static) - 渐进式的React静态网站生成工具。
- [gridsome](https://github.com/gridsome/gridsome) - Vue.js静态网站生成工具。
- [vitepress](https://github.com/vuejs/vitepress) - Vite & Vue.js静态网站生成工具。
- [scully](https://github.com/scullyio/scully) - Angular 应用程序的静态站点生成器。

### 文档生成

- [Docusaurus](https://github.com/facebook/docusaurus) - 使用React和Markdown并具有翻译和版本控制功能的文档站点生成器。
- [docsify](https://github.com/docsifyjs/docsify) - API文档生成器。
- [JSDoc](https://github.com/jsdoc3/jsdoc) - API文档生成器，类似于JavaDoc或PHPDoc。
- [documentation.js](https://github.com/documentationjs/documentation) - API文档生成器，支持ES2015+和流程注释。
- [Docco](https://github.com/jashkenas/docco) - 文档生成器，该生成器生成一个HTML文档，该文档显示与代码混合的注释。
- [docute](https://github.com/egoist/docute) - 毫不费力的文档，做就对了。
- [ESDoc](https://github.com/esdoc/esdoc) - 针对ES2015的文档生成器，附加测试代码并衡量文档覆盖范围。
- [groc](https://github.com/nevir/groc) - 文档生成，本着文学编程的精神。

### 接口管理

- [yapi](https://github.com/YMFE/yapi) - YApi 是一个可本地部署的、打通前后端及QA的、可视化的接口管理平台。
- [swagger](https://github.com/swagger-api/swagger-node) - Swagger NodeJS版。将符合 Swagger规范 的 API 动态生成精美的文档。
- [rap2](https://github.com/thx/rap2-delos) - 阿里妈妈前端团队出品的开源接口管理工具RAP第二代。

### 桌面应用程序

- [Electron](https://github.com/atom/electron) - 使用Web技术构建跨平台的桌面应用程序。 *(你也许喜欢 [awesome-electron](https://github.com/sindresorhus/awesome-electron))*
- [nw.js](https://github.com/nwjs/nw.js) - 使用 Web 技术编写应用程序的新方法，并直接从 DOM/WebWorker 调用所有 Node.js 模块。

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
- [nodejs-websocket](https://github.com/sitegui/nodejs-websocket) - 一个Websocket服务端和客户端模块。
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - 通过WebSocket实现JSON-RPC 2.0。
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - 可扩展的实时通信微服务框架。
- [isomorphic-ws](https://github.com/heineiuo/isomorphic-ws) - WebSocket 的同构实现。
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

### 调试

- [node-inspector](https://github.com/node-inspector/node-inspector) - 基于Blink开发者工具的调试器。
- [ndb](https://github.com/GoogleChromeLabs/ndb) - Chrome DevTools调试体验改进工具。
- [debug](https://github.com/visionmedia/debug) - 轻量调试工具。
- [ironNode](https://github.com/s-a/iron-node) - 支持ES2015的Node.js开箱即用的调试器。
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - 当Node因不明原因继续运行时，使用的分析工具。
- [llnode](https://github.com/nodejs/llnode) - 事后分析工具，使您可以检查对象并从崩溃的Node.js进程中获取信息。
- [njsTrace](https://github.com/valyouw/njstrace) - 检测和跟踪您的代码，查看所有函数调用、参数、返回值以及在每个函数中花费的时间。
- [locus](https://github.com/alidavut/locus) - Locus 是一个调试模块，它允许您通过 REPL 在运行时执行命令。
- [stackman](https://github.com/watson/stackman) - 使用代码摘录和其他优点增强错误堆栈跟踪。
- [NiM](https://github.com/june07/nim) - 管理DevTools调试工具流。
- [ctrace](https://github.com/automation-stack/ctrace) - 将系统调用信息和信号，以更良好的格式显示和扩展。
- [vstream](https://github.com/joyent/node-vstream) - 检测流。

### 剖析/分析

- [Clinic.js](https://github.com/clinicjs/node-clinic) - Clinic.js诊断Node.js性能问题。
- [0x](https://github.com/davidmarkclements/0x) - 火焰图分析。
- [node-heapdump](https://github.com/bnoordhuis/node-heapdump) - 存储V8内存堆使用情况，以供以后诊断。
- [leakage](https://github.com/andywer/leakage) - 内存写入泄漏测试。
- [v8-profiler](https://github.com/node-inspector/v8-profiler) - V8性能探测器。
- [node-memwatch](https://github.com/marcominetti/node-memwatch) - 一个 NodeJS 库，用于监视您的内存使用情况，并发现和隔离泄漏。
- [v8-analytics](https://github.com/hyj1991/v8-analytics) - V8引擎CPU 和 堆内存分析。
- [thetool](https://github.com/sfninja/thetool) - 以Chrome DevTools友好格式为您的应用捕获不同的CPU，内存和其他配置文件。
- [flamegraph](https://github.com/thlorenz/flamegraph) - 在Node.js或浏览器中生成火焰图。
- [v8-profiler-next](https://github.com/hyj1991/v8-profiler-next) - V8性能探测器。
- [cpu-memory-monitor](https://github.com/nswbmw/cpu-memory-monitor) - CPU 和内存监视器，自动转储。

### 性能优化

- [v8-compile-cache](https://github.com/zertosh/v8-compile-cache) - 将require的V8编译的结果自动持久缓存化。

### 应用性能监控 (APM)

- 解决方案
  - [easy-monitor](https://github.com/hyj1991/easy-monitor) - 企业级 Node.js 应用性能监控和在线故障定位解决方案。
  - [webfunny_monitor](https://github.com/a597873885/webfunny_monitor) - Webfunny是一款轻量级的前端监控系统，也是一款前端性能监控系统，无埋点监控前端日志，实时分析前端健康状态。

- 中间件
  - [swagger-stats](https://github.com/slanatech/swagger-stats) - 跟踪 API 调用并监控 API 性能、运行状况和使用指标。

- 代理
  - [prom-client](https://github.com/siimon/prom-client) - Prometheus代理。
  - [apm-agent-nodejs](https://github.com/elastic/apm-agent-nodejs) - Elastic APM Node.js代理。
  - [skywalking-nodejs](https://github.com/apache/skywalking-nodejs) - Apache SkyWalking Node.js代理

### 论坛

- [NodeBB](https://github.com/NodeBB/NodeBB) - 基于Node.js的现代Web论坛。
- [nodeclub](https://github.com/cnodejs/nodeclub/) -  Nodeclub 是使用 Node.js 和 MongoDB 开发的社区系统

### 数据库

- 驱动
  - [MySQL](https://github.com/mysqljs/mysql) - MySQL 客户端。
  - [redis](https://github.com/NodeRedis/node-redis) - 高性能的 Node.js Redis客户端。
  - [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL客户端。
  - [MongoDB](https://github.com/mongodb/node-mongodb-native) - 官方MongoDB驱动。
  - [ioredis](https://github.com/luin/ioredis) - Redis客户端。
  - [LevelUP](https://github.com/Level/levelup) - LevelDB客户端。
  - [mysql2](https://github.com/sidorares/node-mysql2) - 快速 兼容mysqljs/mysql库 的 mysql 驱动程序。
  - [rethinkdbdash](https://github.com/neumino/rethinkdbdash) - RethinkDB 的高级 Node.js 驱动程序，带有连接池、支持流等。
  - [couchdb-nano](https://github.com/apache/couchdb-nano) - 官方CouchDB客户端。
  - [Couchbase](https://github.com/couchbase/couchnode) - Couchbase客户端（官方）。
  - [mariadb](https://github.com/mariadb-corporation/mariadb-connector-nodejs) - MariaDB Connector/Node.js 用于将在 Node.js 上开发的应用程序连接到 MariaDB 和 MySQL 数据库。
  - [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike客户端。

- ODM / ORM
  - [Sequelize](https://github.com/sequelize/sequelize) - 多方ORM。 支持PostgreSQL，SQLite，MySQL。
    - [sequelize-typescript](https://github.com/RobinBuschmann/sequelize-typescript) - Sequelize 装饰器和一些其他功能。
  - [TypeORM](https://github.com/typeorm/typeorm) - PostgreSQL，MariaDB，MySQL，SQLite等的ORM。
  - [Mongoose](https://github.com/Automattic/mongoose) - 优雅的MongoDB对象建模。
    - [typegoose](https://github.com/typegoose/typegoose) - Typegoose - 使用 TypeScript 类定义 Mongoose 模型。
  - [Prisma](https://github.com/prisma/prisma) - 支持PostgreSQL, MySQL & SQLite，自动生成、类型安全的query builder。
  - [Bookshelf](https://github.com/bookshelf/bookshelf) - Backbone.js风格的PostgreSQL，MySQL和SQLite3的ORM。
  - [Objection.js](https://github.com/Vincit/objection.js) - 基于SQL查询生成器Knex的轻量级ORM。
  - [Waterline](https://github.com/balderdashy/waterline) - 与数据存储区无关的工具，可大大简化与一个或多个数据库的交互。
  - [Massive](https://github.com/robconery/massive-js) - PostgreSQL数据访问工具。
  - [pg-promise](https://github.com/vitaly-t/pg-promise) - 用于使用Promise的本机SQL的PostgreSQL框架。
  - [MikroORM](https://github.com/mikro-orm/mikro-orm) - 基于数据映射器，工作单元和身份映射模式的TypeScript ORM。 支持MongoDB，PostgreSQL，MySQL和SQLite。
  - [slonik](https://github.com/gajus/slonik) - 具有严格类型，详细日志记录和断言的PostgreSQL客户端。
  - [OpenRecord](https://github.com/PhilWaldmann/openrecord) - PostgreSQL，MySQL，SQLite3和RESTful数据存储的ORM。 类似于ActiveRecord。
  - [leoric](https://github.com/cyjake/leoric) - 用于MySQL, PostgreSQL, and SQLite的ORM。

- Query builder
  - [Knex](https://github.com/tgriesser/knex) - PostgreSQL，MySQL和SQLite3的查询构建器，旨在灵活，可移植且易于使用。

- SQL
  - [sqlstring](https://github.com/mysqljs/sqlstring) - 简单 SQL 转义和格式，用于MySQL。

- 其他
  - [Lowdb](https://github.com/typicode/lowdb) - 用于小型项目的微型本地 JSON 数据库（支持 Node、Electron 和浏览器）。
  - [NeDB](https://github.com/louischatriot/nedb) - 用于 Node.js、nw.js、Electron和浏览器的嵌入式持久数据库或内存数据库。
  - [Keyv](https://github.com/lukechilds/keyv) - 支持多个后端的简单键值(KV)存储。
  - [pg-mem](https://github.com/oguimbal/pg-mem) - 内存 PostgreSQL 实例。
  - [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - 使用 JavaScript 和 JSON 文件填充 MongoDB 数据库。
  - [@databases](https://github.com/ForbesLindesay/atdatabases) - 使用普通 SQL 查询 PostgreSQL、MySQL 和 SQLite3，而不会导致 SQL注入 的风险。
  - [Finale](https://github.com/tommybananas/finale) - 基于 Sequelize 模型生成 RESTful接口。
  - [database-js](https://github.com/mlaanderson/database-js) - 类似 JDBC连接 的多个数据库连接封装。

### 缓存

- [lru-cache](https://github.com/isaacs/node-lru-cache) - 最近最少使用的缓存（LRU）实现。
- [node-cache](https://github.com/node-cache/node-cache) - Node.js内存缓存模块。
- [memcached](https://github.com/3rd-Eden/memcached) - 功能齐全的Memcached Node.js客户端库。 考虑到扩展性，因此它将支持Memcached群集和一致的哈希。
- [node-cache-manager](https://github.com/BryanDonovan/node-cache-manager) - Node.js Cache模块。
- [quick-lru](https://github.com/sindresorhus/quick-lru) - 简单的 “最近最少使用” (LRU) 缓存.
- [hashlru](https://github.com/dominictarr/hashlru) - 更轻量更快的LRU算法。
- [flat-cache](https://github.com/royriojas/flat-cache) - 一个傻瓜般简单的键/值存储使用文件来持久化数据。
- [ylru](https://github.com/node-modules/ylru) - 基于hashlru添加过期时间，允许空值。

### 搜索引擎

- [elasticsearch-js](https://github.com/elastic/elasticsearch-js) - 官方Elasticsearch客户端库。
- [elasticsearch-js-legacy](https://github.com/elastic/elasticsearch-js-legacy) -  适用于 Node.js 和浏览器的旧版 Elasticsearch 客户端库。

### Serverless

- [serverless](https://github.com/serverless/serverless) - 无服务器框架 – 使用 AWS Lambda、Azure Functions、Google CloudFunctions 等无服务器架构构建 Web、移动和 IoT 应用程序。
- [@midway/faas](https://github.com/midwayjs/midway/tree/2.x/packages/faas) - Midway FaaS 是用于构建 Node.js 云功能的 Serverless 框架。
- [malagu](https://github.com/cellbang/malagu) - Malagu 是基于 TypeScript 的 Serverless First、可扩展和组件化的应用框架。

### 自动化 & 机器人流程自动化 - RPA

- [puppeteer](https://github.com/puppeteer/puppeteer) - 无头Chrome Node.js API。
- [playwright](https://github.com/microsoft/playwright) - 使用单一API自动操作Chromium, Firefox and WebKi。
- [phantomjs](https://github.com/ariya/phantomjs) - 脚本化无头浏览器。
- [appium](https://github.com/appium/appium) - iOS, Android, and Windows Apps自动化。
- [wechaty](https://github.com/wechaty/wechaty) - 会话 RPA SDK。
- [robotjs](https://github.com/octalmage/robotjs) - Node.js桌面自动化。
- [nut.js](https://github.com/nut-tree/nut.js) - 使用Node.js进行原生 UI 测试/控制

### 测试相关

- 断言库
  - [chai](https://github.com/chaijs/chai) - 基于行为驱动开发(BDD)和测试驱动开发(TDD)理念的Node.js和浏览器断言库，可与任何 JavaScript 测试框架集成。
  - [power-assert](https://github.com/power-assert-js/power-assert) - 使用标准assert接口提供的描述型断言消息。
  - [expect.js](https://github.com/Automattic/expect.js) - 适用于Node.JS和浏览器的简约BDD风格的断言库。
  - [should.js](https://github.com/shouldjs/should.js) - Node.JS的行为驱动开发(BDD)风格断言库。
  - [unexpected](https://github.com/unexpectedjs/unexpected) - Unexpected - 可扩展的 BDD 断言工具包。
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
  - [mm](https://github.com/node-modules/mm) - 简单但灵活的 mock(或者叫stub) 包, mock伴侣。

- Mock服务
  - [json-server](https://github.com/typicode/json-server) - 在不到30秒的时间内获得具有零编码的完整伪造的REST API。
  - [easy-mock](https://github.com/easy-mock/easy-mock) - 可视化，并且能快速生成模拟数据的持久化服务。
  - [miragejs](https://github.com/miragejs/miragejs) - 用于构建、测试和共享您的 JavaScript 应用程序的客户端服务。
  - [pretender](https://github.com/pretenderjs/pretender) - 具有良好路由 DSL 的Mock服务器库。
  - [http-fake-backend](https://github.com/micromata/http-fake-backend) - 通过可配置的路由，提供JSON文件或JavaScript对象来构建伪造的后端。
  - [smoke](https://github.com/sinedied/smoke) - 具有记录功能的，简单但功能强大的基于文件的Mock服务器。

- UI录制和播放
  - [rrweb](https://github.com/rrweb-io/rrweb) - 记录和播放Web操作。
  - [uirecorder](https://github.com/alibaba/uirecorder) - UI Recorder 是一款面向多端的 UI 自动化录制工具。

- 端到端的测试(E2E)
  - [cypress](https://github.com/cypress-io/cypress) - 对浏览器中运行的任何东西进行快速、简单和可靠的测试。
  - [nightwatch](https://github.com/nightwatchjs/nightwatch) - 用 Node.js 编写，并使用 Webdriver API 的端到端测试框架。
  - [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - Node.js端到端测试框架。

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
  - [benny](https://github.com/caderek/benny) - 一个非常简单的 JS/TS 库基准测试框架。
  - [node-wrk](https://github.com/sidorares/node-wrk) - Wrk负载测试工具Node.js版封装。

- 解决方案
  - [macaca](https://github.com/alibaba/macaca) - 多端自动化解决方案。*（你也许会喜欢 [awesome-macaca](https://github.com/macacajs/awesome-macaca))*

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
  - [jsPDF](https://github.com/MrRio/jsPDF) - 使用JavaScript生成PDF文件的库。
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

### 压缩解压

- [jszip](https://github.com/Stuk/jszip) - 使用JavaScript创建、读取、编辑.zip文件。
- [pako](https://github.com/nodeca/pako) - 高速 zlib 实现，适用于浏览器和 Node.js。
- [adm-zip](https://github.com/cthackers/adm-zip) - 使用JavaScript创建、读取、编辑.zip文件。
- [node-tar](https://github.com/npm/node-tar) - 快速且功能齐全的Tar。
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Node.js unzip解压库。
- [unzipper](https://github.com/ZJONSSON/node-unzipper) - 使用流的 Node.js 跨平台解压缩。
- [tar-fs](https://github.com/mafintosh/tar-fs) - tar-fs允许您将目录打包到tar格式压缩包中，并将tar格式压缩包提取到目录中。
- [extract-zip](https://github.com/maxogden/extract-zip) - 用纯 JavaScript 编写的 Zip 提取。 将 zip 解压缩到目录中。
- [compressing](https://github.com/node-modules/compressing) - 压缩和解压缩你所需的一切。
- [yazl](https://github.com/thejoshwolfe/yazl) - Node.js zip压缩库。
- [7zip](https://github.com/fritx/win-7zip) - Windows包压缩/解压 - 7zip。

### 最小化

- [UglifyJS](https://github.com/mishoo/UglifyJS) - JavaScript压缩工具。
- [imagemin](https://github.com/imagemin/imagemin) - Image压缩工具。
- [babel-minify](https://github.com/babel/minify) - 基于Babel工具链的 ES6+ 压缩库。
- [cssnano](https://github.com/cssnano/cssnano) - 建立在PostCSS生态系统之上模块化的压缩工具。
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS压缩工具。
- [minimize](https://github.com/Swaagie/minimize) - HTML压缩工具。
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - CSS注释剔除工具。

### 邮箱

- [Nylas Mail](https://github.com/nylas/nylas-mail) - 构建在现代Web技术的高扩展性邮件客户端程序。
- [Nodemailer](https://github.com/nodemailer/nodemailer) - 使用Node.js轻松发送电子邮件。
- [Email Templates](https://github.com/forwardemail/email-templates) - 创建、预览和发送自定义电子邮件模板。
- [emailjs](https://github.com/eleith/emailjs) - 向任何SMTP服务器发送带有附件的文本/HTML电子邮件。
- [mjml](https://github.com/mjmlio/mjml) - 旨在减少创建响应电子邮件的痛苦的标记语言。

### 网络

- IP
  - [node-ip](https://github.com/indutny/node-ip) - NodeJS IP地址工具。
  - [public-ip](https://github.com/sindresorhus/public-ip) - 非常快的获取你的公网IP地址。
  - [request-ip](https://github.com/pbojinov/request-ip) - 在服务器中获取请求的IP地址。
  - [ipaddr.js](https://github.com/whitequark/ipaddr.js) - JavaScript 中的 IP 地址操作库。
  - [internal-ip](https://github.com/sindresorhus/internal-ip) - 获取您的内网IP地址。
  - [ipify](https://github.com/sindresorhus/ipify) - 获取你的公网IP地址。
  - [address](https://github.com/node-modules/address) - 获取当前机器IP地址和MAC地址。

- 端口
  - [node-portfinder](https://github.com/http-party/node-portfinder) - 在当前机器上查找开放端口 或 域套接字的简单工具。
  - [get-port](https://github.com/sindresorhus/get-port) - 获取一个可用的端口。
  - [detect-port](https://github.com/node-modules/detect-port) - 端口探测的Node.JS实现。

- 隧道代理
  - [localtunnel](https://github.com/localtunnel/localtunnel) - Localtunnel 将您的本地主机公开给全世界，以便于测试和共享！
  - [node-tunnel](https://github.com/koichik/node-tunnel) - 用于隧道代理的 HTTP/HTTPS代理。
  - [tunnel-agent](https://github.com/request/tunnel-agent) - HTTP 隧道代理。以前是 mikeal/request 的一部分，现在是一个独立的模块。

- 其他
  - [netcat](https://github.com/roccomuso/netcat) - 纯JS中的Netcat端口。
  - [getmac](https://github.com/bevry/getmac) -  获取电脑的MAC地址。
  - [DHCP](https://github.com/infusion/node-dhcp) - DHCP客户端和服务器。
  - [default-gateway](https://github.com/silverwind/default-gateway) - 获取默认网络网关(跨平台)。

### HTTP

- 请求库
  - [axios](https://github.com/mzabriskie/axios) - 基于Promise 的HTTP客户端（也可以在浏览器中工作）。
  - [superagent](https://github.com/visionmedia/superagent) - HTTP请求库。
  - [got](https://github.com/sindresorhus/got) - 更好的基于内建“http”模块接口实现。
  - [node-fetch](https://github.com/bitinn/node-fetch) - Node.js的 `window.fetch` 实现。
  - [undici](https://github.com/nodejs/undici) - 一个 HTTP/1.1 客户端，从头开始为 Node.js 编写。
  - [needle](https://github.com/tomas/needle) - 灵活，基于流的HTTP Node.js客户端请求库。支持proxy，iconv，cookie，deflate和multipart。
  - [urllib](https://github.com/node-modules/urllib) - 在复杂世界中请求HTTP/HTTPS的URL。
  - [phin](https://github.com/ethanent/phin) - Node HTTP client.
  - [gotql](https://github.com/khaosdoctor/gotql) - 基于[got](https://github.com/sindresorhus/got)构建的GraphQL请求库。
  - [wreck](https://github.com/hapijs/wreck) - HTTP 客户端工具。
  - [cacheable-request](https://github.com/lukechilds/cacheable-request) - 使用符合RFC的缓存封装的本机HTTP请求库。
  - [gh-got](https://github.com/sindresorhus/gh-got) - 基于"got"封装，与GitHub API更方便的交互。
  - [flashheart](https://github.com/bbc/flashheart) - REST 客户端。

- 服务端库
  - [http-server](https://github.com/http-party/http-server) - 零配置的命令行Http服务端。
  - [anywhere](https://github.com/JacksonTian/anywhere) - 随启随用的静态文件服务器。

- Mock服务
  - [json-server](https://github.com/typicode/json-server) - 在不到30秒的时间内获得具有零编码的完整伪造的REST API。
  - [easy-mock](https://github.com/easy-mock/easy-mock) - 可视化，并且能快速生成模拟数据的持久化服务。
  - [miragejs](https://github.com/miragejs/miragejs) - 用于构建、测试和共享您的 JavaScript 应用程序的客户端服务。
  - [http-fake-backend](https://github.com/micromata/http-fake-backend) - 通过可配置的路由，提供JSON文件或JavaScript对象来构建伪造的后端。
  - [smoke](https://github.com/sinedied/smoke) - 具有记录功能的，简单但功能强大的基于文件的Mock服务器。

- 代理
  - [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP代理。
  - [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) - ⚡用于connect，express和browser-sync的单线Node.js Http代理中间件。
  - [https-proxy-agent](https://github.com/TooTallNate/node-https-proxy-agent) - HTTP(S) 代理 `http.Agent`实现。
  - [global-agent](https://github.com/gajus/global-agent) - 可以使用环境变量配置的全局 HTTP/HTTPS 代理。
  - [fast-proxy](https://github.com/fastify/fast-proxy) - Node.js框架，使您可以将http请求转发到另一个HTTP服务器。 支持的协议：HTTP，HTTPS，HTTP2。
  - [argo](https://github.com/argo/argo) - 一个可扩展的异步 HTTP 反向代理和源服务器。

- 下载
  - [download](https://github.com/kevva/download) - 轻松下载和提取文件。
  - [nugget](https://github.com/maxogden/nugget) - 使用Node.js编写的极简主义wget clone。 HTTP GET文件并将其下载到当前目录。

### 验证

- [Passport](https://github.com/jaredhanson/passport) - 简单的身份验证。
- [Grant](https://github.com/simov/grant) - 适用于Express，Koa，Hapi，Fastify，AWS Lambda，Azure，Google Cloud，Vercel等的OAuth程序。
- [permit](https://github.com/ianstormtaylor/permit) - 用于构建Node.js API的非标准认证库。

### 授权 / 鉴权

- [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - JsonWebToken Node.JS实现
- [CASL](https://github.com/stalniy/casl) - 同构授权用于可视化界面和API。
- [node-casbin](https://github.com/casbin/node-casbin) - 支持访问控制模型（如ACL，RBAC和ABAC）的授权库。
- [jose](https://github.com/panva/jose) - 通用的“JSON Web 几乎所有东西” —— JWA、JWS、JWE、JWT、JWK，0依赖
- [basic-auth](https://github.com/jshttp/basic-auth) - 通用基础身份验证授权头字段解析器。
- [selfsigned](https://github.com/jfromaniello/selfsigned) - 使用 Node.js 生成自签名证书。

### 分布式

- [node-zookeeper-client](https://github.com/alexguan/node-zookeeper-client) - 纯JavaScript ZooKeeper客户端。

### 序列化

- [protobuf](https://github.com/protobufjs/protobuf.js) - Protocol Buffers实现。
- [hessian.js](https://github.com/node-modules/hessian.js) - JavaScript hessian 二进制web服务协议实现，支持与 java 通信。
- [snappy](https://github.com/kesla/node-snappy) - Google 的 Snappy 压缩库的原生绑定（Native bindings）。
- [compactr](https://github.com/compactr/compactr.js) - Compactr协议的实现。

### RPC

- [grpc-js](https://github.com/grpc/grpc-node/tree/master/packages/grpc-js) - 纯JavaScript gRPC客户端。
- [jayson](https://github.com/tedeh/jayson) - Jayson是用于Node.js的简单但功能强大的JSON-RPC 2.0 / 1.0客户端和服务器。
- [sofa-rpc-node](https://github.com/sofastack/sofa-rpc-node) - SOFARPC Node是高性能、高可扩展性、产品级Node.js RPC框架。

### 服务端DOM

- [cheerio](https://github.com/cheeriojs/cheerio) - 运行在服务器端，快速、灵活和精益的jQuery核心功能实现。
- [jsdom](https://github.com/jsdom/jsdom) - Node.js版Web标准实现。
- [domino](https://github.com/fgnass/domino) - 基于 Mozilla的dom.js的服务器端DOM实现。

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
  - [nearley](https://github.com/kach/nearley) - JavaScript的简单、快速、功能强大的解析工具集。
  - [espree](https://github.com/eslint/espree) - 与Esprima兼容的JavaScript解析器。
  - [csstree](https://github.com/csstree/csstree) - 基于W3C标准和浏览器标准实现，包含快速详细的解析器、遍历器、生成器、词法解析的CSS工具集。
  - [es-module-lexer](https://github.com/guybedford/es-module-lexer) - 低开销的词法分析器，专门用于ES模块快速分析解析。

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
  - [notevil](https://github.com/mmckegg/notevil) - 像内置的 javascript eval() 方法一样执行 javascript，但安全。

- 其他
  - [astexplorer](https://github.com/fkling/astexplorer) - 使用多种解析器的AST Web可视化工具。
  - [estree-walker](https://github.com/Rich-Harris/estree-walker) - 用于遍历ESTree兼容树的AST。
  - [periscopic](https://github.com/Rich-Harris/periscopic) - 用于分析符合ESTree的AST的作用域的工具。

### WebAssembly

- [webassembly](https://github.com/dcodeIO/webassembly) - 用于生成和运行 WebAssembly 模块的最小工具包和运行时。

### 设计稿转代码（D2C）
- [psd.js](https://github.com/meltingice/psd.js) - 在Node.js和浏览器中解析Photoshop PSD文件。

### 沙箱

- [vm2](https://github.com/patriksimek/vm2) - Node.js高级虚拟机/沙箱。
- [sandbox](https://github.com/gf3/sandbox) - 用于Node.js漂亮的JavaScript沙箱。
- [safeify](https://github.com/Houfeng/safeify) - Safeify 可让 Node 应用安全的隔离执行非信任的用户自定义代码。

### 硬件

- [johnny-five](https://github.com/rwaldron/johnny-five) - 基于Firmata的Arduino框架。
- [serialport](https://github.com/voodootikigod/node-serialport) - 访问串行端口以进行读写。
- [usb](https://github.com/nonolith/node-usb) - USB 库。
- [onoff](https://github.com/fivdi/onoff) - GPIO访问和中断检测.
- [pigpio](https://github.com/fivdi/pigpio) - 树莓派（Raspberry Pi）上的快速GPIO，PWM，伺服控制，状态更改通知和中断处理。
- [node-escpos](https://github.com/song940/node-escpos) - ESC/POS打印机驱动程序。
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C串行总线访问。
- [gps](https://github.com/infusion/GPS.js) - NMEA解析器，用于处理GPS接收器。
- [node-bluetooth](https://github.com/song940/node-bluetooth) - Node.js 的蓝牙串口通信。
- [spi-device](https://github.com/fivdi/spi-device) - SPI串行总线访问。

### 物联网IoT

- [zetta](https://github.com/zettajs/zetta) - 面向物联网的 API 优先的开源软件平台。
- [iot-nodejs](https://github.com/ibm-watson-iot/iot-nodejs) - 用于使用 nodejs 连接到 IBM Watson IoT 的客户端库和示例。

### 机器学习 和 神经网络

- [tfjs](https://github.com/tensorflow/tfjs) - 一个WebGL加速的JavaScript库，用于训练和部署ML模型（Tensorflow官方）。
- [netron](https://github.com/lutzroeder/netron) - 神经网络、深度学习和机器学习模型的可视化工具。
- [face-api.js](https://github.com/justadudewhohacks/face-api.js) - 可在浏览器和 nodejs 中，使用 tensorflow.js 进行人脸检测和人脸识别的 JavaScript API。
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

### OCR

- [tesseract.js](https://github.com/naptha/tesseract.js) - 100 多种语言的纯 Javascript OCR。
- [Parsr](https://github.com/axa-group/Parsr) - 将 PDF、文档和图像转换为丰富的结构化数据。

### 比特币

- [GitTorrent](https://github.com/cjb/GitTorrent) - 使用 BitTorrent 和比特币的 GitHub 去中心化。
- [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) - 一个用于 node.js 和浏览器的 javascript 比特币库。
- [bitcore](https://github.com/bitpay/bitcore) - 比特币和基于区块链的应用程序的全栈。

## 项目

### 低代码（Lowcode）
*(你也许会喜欢 [awesome-lowcode](https://github.com/taowen/awesome-lowcode))*

- H5/PC
  - [amis](https://github.com/baidu/amis) - 前端低代码框架，通过 JSON 配置就能生成各种页面。

- H5
  - [h5-Dooring](https://github.com/MrXujiang/h5-Dooring) - 让H5制作像搭积木一样简单, 轻松搭建H5页面, H5网站, PC端网站, 可视化设计,LowCode平台。
  - [luban-h5](https://github.com/ly525/luban-h5) - 类似易企秀的H5制作、建站工具、可视化搭建系统。
  - [gods-pen](https://github.com/ymm-tech/gods-pen) - 基于vue的高扩展在线网页制作平台，可自定义组件，可添加脚本，可数据统计。

- PC
  - [pc-Dooring](https://github.com/MrXujiang/pc-Dooring) - 让网页制作像搭积木一样简单, 轻松搭建PC页面, Web网站, PC端网站. lowcode(low-code)可视化搭建平台。

- 逻辑编排
  - [node-red](https://github.com/node-red/node-red) - 事件驱动应用的低代码编程。
  - [imove](https://github.com/ykfe/imove) - iMove 是一个逻辑可复用的，面向函数的，流程可视化的 JavaScript 工具库。
