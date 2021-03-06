---
title: awesome-go(GO相关资料的收集汇总)
date: 2017-11-20 18:15:20
category:
tags: go
---

# awesome-go
一个GO资源列表,包括第三方库、框架和软件清单

## 目录
- [awesome-go](#awesome-go)
    - [音频和音乐 Audio and Music](#音频和音乐-audio-and-music)
    - [身份验证和OAuth Authentication and Auth](#身份验证和oauth-authentication-and-auth)
    - [命令行 Command Line](#命令行-command-line)
    - [高级控制台用户界面 Advanced Console UIs](#高级控制台用户界面-advanced-console-uis)
    - [组态 Configuration](#组态-configuration)
    - [持续集成 Continuous Integration](#持续集成-continuous-integration)
    - [CSS预处理器 Css Preprocessors](#css预处理器-css-preprocessors)
    - [数据结构 Data Structures](#数据结构-data-structures)
    - [数据库 Database](#数据库-database)
    - [数据库驱动 Database Drivers](#数据库驱动-database-drivers)
    - [日期和时间 Date and Time](#日期和时间-date-and-time)
    - [分布式系统 Distributed Systems](#分布式系统-distributed-systems)
    - [电子邮件 Email](#电子邮件-email)
    - [嵌入式脚本语言 Embeddable Scripting Languages](#嵌入式脚本语言-embeddable-scripting-languages)
    - [文件 Files](#文件-files)
    - [金融 Financial](#金融-financial)
    - [表单 Forms](#表单-forms)
    - [游戏开发 Game Development](#游戏开发-game-development)
    - [代和泛型 Generation and Generics](#代和泛型-generation-and-generics)
    - [GO编译器 Go Compilers](#go编译器-go-compilers)
    - [协程 Coroutines](#协程-coroutines)
    - [GUI](#gui)
    - [硬件 Hardware](#硬件-hardware)
    - [图片 Images](#图片-images)
    - [物联网 Iot (Internet of Things)](##物联网-iot-internet-of-things)
    - [日志 Logging](#日志-logging)
    - [机器学习 Machine Learning](#机器学习-machine-learning)
    - [消息 Messaging](#消息-messaging)
    - [其他 Miscellaneous](#其他-miscellaneous)
    - [自然语言处理 Natural Language Processing](#自然语言处理-natural-language-processing)
    - [网络 Networking](#网络-networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [包管理 Package Management](#包管理-package-management)
    - [查询语言 Query Language](#查询语言-query-language)
    - [资源嵌入 Resource Embedding](#资源嵌入-resource-embedding)
    - [科学和数据分析 Science and Data Analysis](#科学和数据分析-science-and-data-analysis)
    - [安全 Security](#安全-security)
    - [序列化 Serialization](#序列化-serialization)
    - [服务器应用程序 Server Applications](#服务器应用程序-server-applications)
    - [模板引擎 Template Engines](#模板引擎-template-engines)
    - [测试 Testing](#测试-testing)
    - [文字处理 Text Processing](#文字处理-text-processing)
    - [第三方API Third-party APIs](#第三方API-third-party-apis)
    - [公用事业 Utilities](#公用事业-utilities)
    - [验证 Validation](#验证-validation)
    - [版本控制 Version Control](#版本控制-version-control)
    - [视频 Video](#视频-video)
    - [Web框架 Web Frameworks](#web框架-web-frameworks)
        - [中间件 Middlewares](#中间件-middlewares)
            - [实际的中间件 Actual Middlewares](#实际的中间件-actual-middlewares)
            - [用于创建HTTP中间件的库 Libraries For Creating HTTP Middlewares](#用于创建HTTP中间件的库-libraries-for-creating-HTTP-middlewares)
        - [路由 Routers](#路由-routers)
    - [视窗 Windows](#视窗-windows)
    - [XML](#xml)

- [工具 Tools](#工具-tools)
    - [代码分析 Code Analysis](#代码分析-code-analysis)
    - [编辑插件 Editor Plugins](#编辑插件-editor-plugins)
    - [GO生成工具 Go Generate Tools](#go生成工具-go-generate-tools)
    - [GO工具 Go Tools](#go工具-go-tools)
    - [软件包 Software Packages](#软件包-software-packages)
        - [DevOps工具 DevOps Tools](#devops工具-devOps-tools)
        - [其他软件 Other Software](#其他软件-other-software)

- [服务器应用 Server Applications](#服务器应用-server-applications)

- [资源 Resources](#资源-resources)
    - [基准 Benchmarks](#基准-benchmarks)
    - [会议 Conferences](#会议-conferences)
    - [电子书 E-Books](#电子书-e-books)
    - [聚会 Meetups](#聚会-meetups)
    - [推特 Twitter](#推特-twitter)
    - [网站 Websites](#网站-websites)
        -[教程 Tutorials](#教程-tutorials)

## <span id="音频和音乐-audio-and-music">音频和音乐 Audio and Music</span>

*操作音频的库。*

* [flac](https://github.com/eaburns/flac) - 一款GO语言实现的本地FLAC解码器。
* [flac](https://github.com/mewkiz/flac) - 另一款GO语言实现的本地FLAC解码器。
* [gaad](https://github.com/Comcast/gaad) - 本地AAC码比特流分析器。
* [go-sox](https://github.com/krig/go-sox) - libsox绑定GO libsox bindings for go.
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go.
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
* [id3v2](https://github.com/bogem/id3v2) - 一个GO语言是写的快速稳定读写ID3库。
* [malgo](https://github.com/gen2brain/malgo) - 一个用GO语言实现的迷你音频库。
* [mix](https://github.com/go-mix/mix) - 以序列为基础的GO语言实现的本地音频混合器音乐应用程序。
* [mp3](https://github.com/tcolgate/mp3) - GO语言实现本地MP3解码器。
* [music-theory](https://github.com/go-music-theory/music-theory) - GO语言的一个音乐理论模型。
* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.
* [taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib.
* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).
* [waveform](https://github.com/mdlayher/waveform) - 一个Go语言包，能够从音频流生成波形图像。

## <span id="身份验证和oauth-authentication-and-auth">身份验证和OAuth Authentication and Auth</span>

*用于实现认证方案的库。*

* [authboss](https://github.com/volatiletech/authboss) - 网络的模块化认证系统。它试图去除尽可能多的样板和“困难的事情”，以便每次在Go中启动一个新的Web项目时，都可以插入，配置并开始构建应用程序，而无需每次都构建一个身份验证系统。
* [casbin](https://github.com/hsluoyz/casbin) - 支持访问控制模型（如ACL，RBAC，ABAC）的授权库。
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - 提供解析cookie文件格式。
* [Go-AWS-Auth](https://github.com/smartystreets/go-aws-auth) - AWS（Amazon Web Services）请求签名库。
* [go-jose](https://github.com/square/go-jose) - 相当完整地实现了JOSE工作组的JSON Web令牌、JSON Web签名和JSON网络加密规范。
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - GO语言实现的独立的，符合规范的，oauth2服务。
* [gologin](https://github.com/dghubble/gologin) - 可以使用OAuth1或者OAuth2进行登录认证。
* [gorbac](https://github.com/mikespook/gorbac) - 提供了一个轻量级的基于角色的访问控制（RBAC）。
* [goth](https://github.com/markbates/goth) - 提供了一个简单，干净，和习惯的方式来使用OAuth和oauth2。提供非常好的处理复杂的操作。
* [httpauth](https://github.com/goji/httpauth) - 一个HTTP身份验证中间件。
* [jwt](https://github.com/robbert229/jwt) - 简洁易用实现json web的令牌 (JWT)。
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - 具有许多配置选项的Golang http服务器的JWT中间件。
* [jwt-go](https://github.com/dgrijalva/jwt-go) - GO语言实现Json Web Tokens(JWT)。
* [loginsrv](https://github.com/tarent/loginsrv) - 带有可插入后端的JWT登录微服务，如OAuth2（Github），htpasswd，osiam。
* [oauth2](https://github.com/golang/oauth2) - 继承goauth2。通用OAuth 2包来自JWT，谷歌计算引擎和API，应用程序引擎支持。
* [osin](https://github.com/RangelReale/osin) - Golang OAuth2服务 库.
* [permissions2](https://github.com/xyproto/permissions2) - 跟踪用户、登录状态和权限的库。使用安全的Cookie和BCrypt。
* [securecookie](https://github.com/chmike/securecookie) - 高效安全cookie编码/解码。
* [session](https://github.com/icza/session) - 通过web servers 管理会话(包含支持goole App 引擎 - GAE)。
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - GO语言通过使用sessiongate Redis模块管理会话。
* [sessions](https://github.com/adam-hanna/sessions) - 简单，高性能，高度可定制的会话服务去http服务器。
* [traefik](https://github.com/containous/traefik) - 支持多个后端的反向代理和负载均衡器
* [yubigo](https://github.com/GeertJohan/yubigo) - Yubikey客户端软件包，提供了一个简单的API来将Yubico Yubikey集成到一个应用程序中。

## <span id="命令行-command-line">命令行 Command Line</span>

### 标准CLI

*用于构建标准或基本命令行应用程序的库。*

* [argv](https://github.com/cosiner/argv) - 一个GO语言库，用于将将bash语法中的命令行字符串拆分为参数数组。
* [cli](https://github.com/mkideal/cli) - 一个功能丰富且简单易用的基于golang结构标签的命令行包。
* [cli](https://github.com/teris-io/cli) - 在Go中构建命令行界面的简单而完整的API.
* [cli-init](https://github.com/tcnksm/gcli) - 开始构建Golang命令行应用程序的简单方法。
* [climax](http://github.com/tucnak/climax) - 在Go命令的精神下，用“人脸”替代CLI.
* [cobra](https://github.com/spf13/cobra) - 现代Go CLI交互的指挥官.
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* [docopt.go](https://github.com/docopt/docopt.go) - 命令行参数解析器，会让你微笑。
* [drive](https://github.com/odeke-em/drive) - 命令行的Google Drive客户端。
* [env](https://github.com/codingconcepts/env) - 针对结构的基于标记的环境配置。
* [flag](https://github.com/cosiner/flag) - 一个Go支持子命令的简单但强大的命令行选项解析库。
* [go-arg](https://github.com/alexflint/go-arg) - 一个在Go中基于结构的参数解析。
* [go-flags](https://github.com/jessevdk/go-flags) - 一个命令行选项分析器。
* [kingpin](https://github.com/alecthomas/kingpin) - 一个支持子命令的命令行和标志分析器。
* [liner](https://github.com/peterh/liner) - 一个GO命令行界面的类似readline的库。
* [mitchellh/cli](https://github.com/mitchellh/cli) - 一个用GO的实现命令行接口的库。
* [mow.cli](https://github.com/jawher/mow.cli) - 一个用GO语言实现通过复杂的标签和参数分析和验证构建CLI应用程序的库。
* [pflag](https://github.com/spf13/pflag) - Go的标志包的替代品，实现POSIX / GNU风格的标志。
* [readline](https://github.com/chzyer/readline) - 纯粹的golang实现，提供GNU-Readline在MIT许可下的大部分功能。
* [sflags](https://github.com/octago/sflags) - 用于标志，urfave / cli，pflag，cobra，kingpin和其他库的基于结构的标志生成器。
* [ukautz/clif](https://github.com/ukautz/clif) - 小命令行界面框架。
* [urfave/cli](https://github.com/urfave/cli) - 用于在Go（以前的codegangsta / cli）中构建命令行应用程序的简单，快速和有趣的软件包。
* [wlog](https://github.com/dixonwille/wlog) - 支持跨平台颜色和并发性的简单日志记录界面。
* [wmenu](https://github.com/dixonwille/wmenu) - 易于使用的菜单结构的cli应用程序，提示用户作出选择。

### <span id="高级控制台用户界面-advanced-console-uis">高级控制台用户界面 Advanced Console UIs</span>

*用于构建控制台应用程序和控制台用户界面的库。*

* [aurora](https://github.com/logrusorgru/aurora) - 支持fmt.Printf / Sprintf的ANSI终端颜色。
* [chalk](https://github.com/ttacon/chalk) - 美化终端/控制台输出的直观包装。
* [color](https://github.com/fatih/color) - 彩色终端输出的多功能包装。
* [colourize](https://github.com/TreyBastian/colourize) - GO语言实现的一个终端的ANSI颜色文本库。
* [go-ataman](https://github.com/workanator/go-ataman) - 一个GO语言库用于渲染ANSI彩色文本模板的终端。
* [go-colorable](https://github.com/mattn/go-colorable) - 针对windows，GO语言实现的可着色的工具。
* [go-colortext](https://github.com/daviddengcn/go-colortext) - 一个GO语言库用于终端的颜色输出库。
* [go-isatty](https://github.com/mattn/go-isatty) - GO语言的isatty。
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go库旨在创建控制台用户界面。
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - 样式终端文本。
* [mpb](https://github.com/vbauerster/mpb) - 终端应用程序的多进度条。
* [progressbar](https://github.com/schollz/progressbar) - 在每个操作系统中工作的基本线程安全进度条。
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox是一个用于创建跨平台文本界面的库。
* [termtables](https://github.com/apcera/termtables) - 用于简单的ASCII表生成的Ruby库[终端表](https://github.com/tj/terminal-table)的端口，以及提供降价和HTML输出。
* [termui](https://github.com/gizak/termui) - 基于转到终端仪表板**termbox-go** 和灵感祝福-的contrib。
Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* [tui-go](https://github.com/marcusolsson/tui-go) - 用于构建丰富的终端应用程序的用户界面库。
* [uilive](https://github.com/gosuri/uilive) - 实时更新终端输出的库。
* [uiprogress](https://github.com/gosuri/uiprogress) - 灵活的库在终端应用程序中呈现进度条。Flexible library to render progress bars in terminal applications.
* [uitable](https://github.com/gosuri/uitable) - 一个使用表格数据提高终端应用程序可读性的库。

## <span id="组态-configuration">组态 Configuration</span>

*用于配置解析的库.*

* [config](https://github.com/olebedev/config) -  环境变量和标志解析的JSON或YAML配置包装。
* [configure](https://github.com/paked/configure) - 通过多种来源提供配置，包括JSON，标志和环境变量。
* [env](https://github.com/caarlos0/env) - 将环境变量解析为Go结构（使用默认值）。
* [envcfg](https://github.com/tomazk/envcfg) -  取消编组环境变量到Go结构。 Un-marshaling environment variables to Go structs.
* [envconf](https://github.com/ian-kent/envconf) - 环境配置
* [envconfig](https://github.com/vrischmann/envconfig) - 从环境变量中读取配置。
* [envh](https://github.com/antham/envh) - 帮助者管理环境变量。
* [gcfg](https://github.com/go-gcfg/gcfg) - 将INI文件格式的配置文件读入Go结构中; 支持用户定义的类型和子部分。
* [goConfig](https://github.com/crgimenes/goConfig) - 解析一个结构作为输入，并使用来自命令行，环境变量和配置文件的参数填充此结构的字段。
* [godotenv](https://github.com/joho/godotenv) - Ruby的dotenv库的端口（加载环境变量.env）。
* [gofigure](https://github.com/ian-kent/gofigure) - 让GO语言应用程序配置变得简单。
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - 模块化JSON配置。保持配置结构以及它们配置的代码，并将解析委派给子模块，
而不会牺牲完整的配置序列化。
* [hjson](https://github.com/hjson/hjson-go) - 人类JSON，一种人类的配置文件格式。轻松的语法，更少的错误，更多的评论。
* [ingo](https://github.com/schachmat/ingo) - 标签保存在一个INI配置文件中。 
* [ini](https://github.com/go-ini/ini) - 一个Go语言包用于读取和写入INI文件。
* [joshbetz/config](https://github.com/joshbetz/config) - 一个用于解析环境变量，JSON文件并在SIGHUP上自动重新加载的Go的小型配置库。
* [mini](https://github.com/sasbury/mini) - 一个用于解析ini样式配置文件的Go语言包。
* [store](https://github.com/tucnak/store) -  Go的轻量级配置管理器。
* [viper](https://github.com/spf13/viper) - Go configuration with fangs.
* [xdg](https://github.com/OpenPeeDeeP/xdg) - 遵循[XDG标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html)的跨平台软件包。

## <span id="持续集成-continuous-integration">持续集成 Continuous Integration</span>     

*帮助持续集成的工具。*

* [drone](https://github.com/drone/drone) - Drone是一个持续集成的平台，建立在Docker上，用Go编写。
* [goveralls](https://github.com/mattn/goveralls) - 与Coveralls.io连续代码覆盖率跟踪系统集成。 
* [overalls](https://github.com/go-playground/overalls) - 多包装GO项目goveralls工具项目coverprofile。
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - 递归覆盖测试工具。

## <span id="css预处理器-css-preprocessors">CSS预处理器 CSS Preprocessors</span>

*用于预处理CSS文件的库。*

* [c6](https://github.com/c9s/c6) - 用Go编写的高性能SASS兼容实现编译器。
* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS预处理器。
* [go-libsass](https://github.com/wellington/go-libsass) - 打包到100％Sass兼容的libsass项目。

## <span id="数据结构-data-structures">数据结构 Data Structures</span>

*Go中的通用数据结构和算法*

* [binpacker](https://github.com/zhuangsirui/binpacker) - 二进制打包器和解包器可以帮助用户构建自定义二进制流。
* [bit](https://github.com/yourbasic/bit) - Golang设置数据结构与奖金位拨弄功能。 set data structure with bonus bit-twiddling functions.
* [bitset](https://github.com/willf/bitset) - 执行包的实现位集。
* [bloom](https://github.com/zhenjl/bloom) - Go实现的Bloom过滤器。
* [bloom](https://github.com/yourbasic/bloom) - Bloom过滤器的实现。
* [boomfilters](https://github.com/tylertreat/BoomFilters) - 用于处理连续，无界流的概率数据结构。
* [concurrent-writer](https://github.com/free/concurrent-writer) - 高度并发的插入式替换 `bufio.Writer`。
* [count-min-log](https://github.com/seiflotfy/count-min-log) - 执行Count-Min-Log草图：用近似计数器近似计数（与Count-Min草图类似，但使用较少的内存）。
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo 过滤器: 在GO中实现的一个计数bloom过滤器的好替代方案。
* [encoding](https://github.com/zhenjl/encoding) - Go语言的整型压缩库
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - GO语言实现Adaptive Radix Tree算法。
* [go-datastructures](https://github.com/Workiva/go-datastructures) - 有用，高性能和线程安全的数据结构的集合。
* [go-ef](https://github.com/amallia/go-ef) - GO语言实现Elias-Fano编码。
* [go-geoindex](https://github.com/hailocab/go-geoindex) - 内存中的地理位置索引。
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - 具有有效的点位置和邻居发现的区域四叉树。
* [gods](https://github.com/emirpasic/gods) - Go 数据结构。容器，集合，列表，堆栈，地图，BidiMaps，树，HashSet等数据结构。容器，集合，列表，堆栈，地图，BidiMaps，树，HashSet等。
* [golang-set](https://github.com/deckarep/golang-set) - 用于高性能设置Go的线程安全和非线程安全。
* [goset](https://github.com/zoumo/goset) - 一个有用的Go的Set集合实现。
* [goskiplist](https://github.com/ryszard/goskiplist) - 在Go中跳过列表实现。
* [gota](https://github.com/kniren/gota) - Go的数据框架，系列和数据处理方法。 
* [hilbert](https://github.com/google/hilbert) - 一个Go软件包，用于映射空间填充曲线的值，例如Hilbert和Peano曲线。
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - 具有Sparse，LogLog-Beta偏差校正和TailCut空间缩减的HyperLogLog实施。
* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein距离和相似性指标与可定制的编辑成本和Winkler般的奖金为通用前缀。
* [levenshtein](https://github.com/agnivade/levenshtein) - GO语言实现计算Levenshtein距离。
* [mafsa](https://github.com/smartystreets/mafsa) - 使用最小完美散列的MA-FSA实现。
* [merkletree](https://github.com/cbergoon/merkletree) - 实现一个merkle树，提供数据结构内容的有效和安全的验证。
* [roaring](https://github.com/RoaringBitmap/roaring) - Go包实现压缩位集。
* [skiplist](https://github.com/gansidui/skiplist) - Go中的跳过列表实现。
* [trie](https://github.com/derekparker/trie) - GO语言实现Trie。
* [ttlcache](https://github.com/diegobernardes/ttlcache) - 内存LRU字符串接口{}映射与golang到期。
* [willf/bloom](https://github.com/willf/bloom) - GO语言实现Bloom过滤器

##  <span id="数据库-database">数据库 Database</span>

*GO语言中实现的对数据库操作*

* [badger](https://github.com/dgraph-io/badger) - Go中的快速键值存储。
* [BigCache](https://github.com/allegro/bigcache) - 千兆字节数据的高效密钥/值缓存。
* [bolt](https://github.com/boltdb/bolt) - Go的低级密钥/值数据库。
* [buntdb](https://github.com/tidwall/buntdb) - 快速，可嵌入的内存键/值数据库的自定义索引和空间支持。
* [cache2go](https://github.com/muesli/cache2go) - 内存中的 `key:value` 超速缓存支持基于超时的自动失效。
* [cockroach](https://github.com/cockroachdb/cockroach) - 可扩展，地理复制，交易数据存储。
* [couchcache](https://github.com/codingsince1985/couchcache) - 由Couchbase服务器支持的RESTful缓存微服务。
* [dgraph](https://github.com/dgraph-io/dgraph) - 可扩展，分布式，低延迟，高吞吐量图形数据库。
* [diskv](https://github.com/peterbourgon/diskv) - 自行开发的磁盘备份键值存储。 
* [eliasdb](https://github.com/krotik/eliasdb) - 无依赖关系的事务图形数据库，具有REST API，短语搜索和类似于SQL的查询语言。
* [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
* [GCache](https://github.com/bluele/gcache) - 缓存库，支持可用的Cache，LFU，LRU和ARC。
* [geocache](https://github.com/melihmucuk/geocache) - 适用于基于地理位置的应用程序的内存缓存。
* [go-cache](https://github.com/pmylund/go-cache) - 用于存储/缓存以`key:value`形式到内存中的（类似于Memcached）库，适用于单机应用程序。
* [goleveldb](https://github.com/syndtr/goleveldb) - 在Go中实现[LevelDB](https://github.com/google/leveldb) key / value数据库。
* [groupcache](https://github.com/golang/groupcache) - Groupcache是​​一个缓存和缓存填充库，在许多情况下用作memcached的替代品。
* [influxdb](https://github.com/influxdb/influxdb) - 可扩展的数据存储的度量方法，事件，和实时分析。
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb是基于LevelDB的Redis之类的高性能NoSQL。
* [levigo](https://github.com/jmhodges/levigo) - Levigo是LevelDB的Go包装器。
* [moss](https://github.com/couchbase/moss) - Moss是一个简单的LSM键值存储引擎，用100％Go编写。
* [piladb](https://github.com/fern4lvarez/piladb) - 基于堆栈数据结构的轻量级RESTful数据库引擎。
* [prometheus](https://github.com/prometheus/prometheus) - 监控系统和时间序列数据库。
* [rqlite](https://github.com/rqlite/rqlite) - 构建在SQLite上的轻量级，分布式的关系数据库。
* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.
* [tempdb](https://github.com/rafaeljesus/tempdb) - 临时项目的键值存储。
* [tidb](https://github.com/pingcap/tidb) - TiDB是一个分布式的SQL数据库。受到Google F1设计的启发。
* [tiedot](https://github.com/HouzuoGuo/tiedot) - 由Golang提供支持的NoSQL数据库。
* [Tile38](https://github.com/tidwall/tile38) - 具有空间索引和实时geofencing的地理位置数据库。

*数据库模式迁移*

* [darwin](https://github.com/GuiaBolso/darwin) - Go的数据库模式进化库。
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Golang出色的内置数据库/ sql库的Django风格的库。
* [goose](https://github.com/steinbacher/goose) - 数据库迁移工具。您可以通过创建增量SQL或Go脚本来管理数据库的演变。
* [gondolier](https://github.com/emvicom/gondolier) - Gondolier是Go的数据库迁移库。
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Gorm ORM的数据库模式迁移助手。
* [migrate](https://github.com/mattes/migrate) - 数据库迁移。GO语言命令操作数据库迁移库。
* [pravasan](https://github.com/pravasan/pravasan) - 简单的迁移工具 - 目前用于MySQL，但计划很快支持Postgres，SQLite，MongoDB等。
* [soda](https://github.com/markbates/pop/tree/master/soda) - 数据库迁移，创建，ORM等等，用于MySQL，PostgreSQL和SQLite。
* [sql-migrate](https://github.com/rubenv/sql-migrate) - 数据库迁移工具。允许使用go-bindata将迁移嵌入到应用程序中。

*数据库工具*

* [chproxy](https://github.com/Vertamedia/chproxy) - ClickHouse是数据库的HTTP代理。
* [go-mysql](https://github.com/siddontang/go-mysql) - 转到工具集来处理MySQL协议和复制。
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - 自动将你的MySQL数据同步到Elasticsearch。
* [kingshard](https://github.com/flike/kingshard) - kingshard是由Golang提供支持的MySQL的高性能代理。
* [myreplication](https://github.com/2tvenom/myreplication) - MySql二进制日志复制监听器。支持基于语句和行的复制。
* [orchestrator](https://github.com/github/orchestrator) - MySQL复制拓扑管理器和可视化器。
* [pgweb](https://github.com/sosedoff/pgweb) - 基于Web的PostgreSQL数据库浏览器。
* [pREST](https://github.com/nuveo/prest) - 从任何PostgreSQL数据库提供RESTful API。
* [rwdb](https://github.com/andizzle/rwdb) - rwdb为多个数据库服务器设置提供了只读副本功能。
* [vitess](https://github.com/youtube/vitess) - vitess提供的服务器和工具可以方便地扩展大型Web服务的MySQL数据库。

*SQL查询生成器，用于构建和使用SQL的库*

* [dat](https://github.com/mgutz/dat) - GO语言的Postgres数据访问工具包。
* [Dotsql](https://github.com/gchaincl/dotsql) - Go库，帮助您将sql文件保存在一个地方并轻松使用它们。
* [goqu](https://github.com/doug-martin/goqu) - 惯用sql生成器和查询库。
* [igor](https://github.com/galeone/igor) - PostgreSQL的抽象层，支持高级功能并使用类似gorm的语法。
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - 功能强大的数据检索方法，以及与DB无关的查询构建功能。
* [scaneo](https://github.com/variadico/scaneo) - 生成Go代码将数据库行转换为任意结构。
* [sqrl](https://github.com/elgris/sqrl) - SQL查询生成器。
* [Squirrel](https://github.com/Masterminds/squirrel) - 一个GO语言库帮助构建SQL查询。
* [xo](https://github.com/knq/xo) - 根据现有模式定义或支持PostgreSQL，MySQL，SQLite，Oracle和Microsoft SQL Server的自定义查询为数据库生成惯用的Go语言代码。

## <span id="数据库驱动-database-drivers">数据库驱动 Database Drivers</span> 

*用于连接和操作数据库的库*

* 关系数据库
    * [avatica](https://github.com/Boostport/avatica) - Apache的凤凰/数据库/ SQL的Avatica SQL驱动程序。
    * [bgc](https://github.com/viant/bgc) - 用于BigQuery的数据存储连接。
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - 用于Go的Firebird RDBMS SQL驱动程序。
    * [go-adodb](https://github.com/mattn/go-adodb) - 使用数据库/sql的Microsoft ActiveX Object DataBase驱动程序。
    * [go-bqstreamer](https://github.com/rounds/go-bqstreamer) - BigQuery快速并发流插入。
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Go的Microsoft MSSQL驱动程序。
    * [go-oci8](https://github.com/mattn/go-oci8) - 使用数据库/sql的Oracle驱动程序。
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) -GO语言的MySQL驱动。
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3驱动程序。
    * [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL驱动程序。
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL驱动程序，支持超出数据库/ sql公开的功能。
    * [pq](https://github.com/lib/pq) - 数据库/sql的Pure Go Postgres驱动程序。

* NoSQL数据库
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Go语言的Aerospike客户端。
    * [arangolite](https://github.com/solher/arangolite) - ArangoDB的轻量级golang驱动程序。
    * [asc](https://github.com/viant/asc) - Aerospike的数据存储连接。
    * [cayley](https://github.com/google/cayley) - 支持多个后端的图形数据库。
    * [dsc](https://github.com/viant/dsc) - SQL，NoSQL，结构化文件的数据存储连接。
    * [dynago](https://github.com/underarmour/dynago) - Dynago是DynamoDB最不惊奇的客户端原则。
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Go中的Couchbase客户端。
    * [go-couchdb](https://github.com/fjl/go-couchdb) - Go的另一个CouchDB HTTP API包装器。
    * [gocb](https://github.com/couchbase/gocb) - 官方Couchbase Go SDK。
    * [gocql](http://gocql.github.io) - 去Apache Cassandra的语言驱动程序。
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - Go编程语言的memcache客户端库。
    * [gorethink](https://github.com/dancannon/gorethink) - Go语言的RethinkDB的驱动程序。
    * [goriak](https://github.com/zegl/goriak) - GO的语言为Riak KV开发驱动程序。GO的语言。
    * [mgo](https://godoc.org/labix.org/v2/mgo) - Go语言的MongoDB驱动程序，它在一个非常简单的API下实现了丰富且经过测试的功能选择，遵循标准的Go语言。
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - golang中的Neo4j REST客户端。
    * [neoism](https://github.com/jmcvetta/neoism) - Golang的 Neo4j客户端。
    * [redigo](https://github.com/garyburd/redigo) - Redigo是Redis数据库的Go客户端。
    * [redis](https://github.com/go-redis/redis) -  Golang的Redis客户端。
    * [redis](https://github.com/hoisie/redis) -  Go语言实现的简单，功能强大的Redis客户端。
    * [redis](https://github.com/bsm/redeo) - Redis协议兼容的TCP服务器/服务。
    * [xredis](https://github.com/shomali11/xredis) - 类型安全，可定制，清洁和易于使用的Redis客户端。

* 搜索和分析数据库
    * [bleve](https://github.com/blevesearch/bleve) -  GO语言的现代文本索引库
    * [elastic](https://github.com/olivere/elastic) -  Go的Elasticsearch客户端。
    * [elasticsql](https://github.com/cch123/elasticsql) - 将SQL转换为Go中的elasticsearch dsl。
    * [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch客户端库。
    * [goes](https://github.com/belogik/goes) - 在Go中与Elasticsearch交互的一个库。
    * [riot](https://github.com/go-ego/riot) - GO语言实现的开源，分布式，简单，高效的搜索引擎。
    * [skizze](https://github.com/seiflotfy/skizze) - 概率数据结构服务和存储。

## <span id="日期和时间-date-and-time">日期和时间 Date and Time</span> 

*用于处理日期和时间的库*

* [carbon](https://github.com/uniplaces/carbon) - 简单的时间延长与许多实用的方法，从PHP碳库移植。
* [date](https://github.com/rickb777/date) - 增加处理日期，日期范围，时间跨度，时间段和时间的时间。
* [dateparse](https://github.com/araddon/dateparse) - 不预先知道日期格式的解析日期。
* [durafmt](https://github.com/hako/durafmt) - Go的持续时间格式化库。
* [feiertage](https://github.com/wlbr/feiertage) - 一组函数来计算德国的公共假期，包括。专攻德国（Bundesländer）。像复活节，五旬节，感恩节...
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - Go（Golang）中波斯语（Solar Hijri）日历的实现。 
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - 计算给定位置的日出和日落时间。
* [goweek](https://github.com/grsmv/goweek) - 与golang的周实体一起工作的图书馆。
* [now](https://github.com/jinzhu/now) - Now是一个时间工具包的。
* [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.
* [timeutil](https://github.com/leekchan/timeutil) - 有用的扩展（Timedelta，Strftime，...）到golang的时间包。
* [tuesday](https://github.com/osteele/tuesday) - 兼容Ruby的Strftime函数。

## <span id="分布式系统-distributed-systems">分布式系统 Distributed Systems</span> 

*有助于构建分布式系统的软件包*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - 一个GO语言中运用的增加支持互动和监测芹菜工人，任务和事件。
* [digota](https://github.com/digota/digota) - grpc电子商务微服务。
* [drmaa](https://github.com/dgruber/drmaa) - 基于DRMAA标准的集群调度程序的作业提交库。
* [emitter-io](https://github.com/emitter-io/emitter) -  高性能，分布式，安全且低延迟的发布 - 订阅平台，由MQTT，Websockets和爱构建。
* [flowgraph](https://github.com/vectaport/flowgraph) - MPI风格的即时发送协调层。
* [gleam](https://github.com/chrislusf/gleam) - 用Go和Luajit编写的快速和可扩展的分布式映射/缩减系统，将Go的高并发性与Luajit的高性能相结合，可以独立运行或分布式运行。
* [glow](https://github.com/chrislusf/glow) - 易于使用的可扩展分布式大数据处理，Map-Reduce，DAG执行，全部采用纯Go。
* [go-jump](https://github.com/dgryski/go-jump) - Google的"Jump"一致哈希函数的端口。
* [go-kit](https://github.com/go-kit/kit) - 支持服务发现，负载均衡，可插拔传输，请求跟踪等的微服务工具包。
* [gorpc](https://github.com/valyala/gorpc) - 高负载的简单，快速和可扩展的RPC库。
* [grpc-go](https://github.com/grpc/grpc-go) - Go语言实现的gRPC。基于HTTP / 2的RPC。
* [hprose](https://github.com/hprose/hprose-golang) - 非常新的RPC库，现在支持25种以上的语言。
* [jsonrpc](https://github.com/osamingo/jsonrpc) -  jsonrpc包帮助实现了JSON-RPC 2.0。
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP客户端实现。
* [KrakenD](https://github.com/devopsfaith/krakend) - 具有中间件的超高性能API网关框架。
* [micro](https://github.com/micro/micro) - 可插拔微型服务工具包和分布式系统平台。
* [NATS](https://github.com/nats-io/gnatsd) - 针对微服务，物联网和云本机系统的轻量级高性能消息传递系统。
* [raft](https://github.com/hashicorp/raft) - 由HashiCorp公司实施的Raft共识协议。
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Golang实现了Raft共识协议。
* [ringpop-go](https://github.com/uber/ringpop-go) -  Go应用程序的可扩展，容错应用程序层分片。
* [rpcx](https://github.com/smallnest/rpcx) - 像阿里巴巴Dubbo这样的分布式可插入RPC服务框架。
* [sleuth](https://github.com/ursiform/sleuth) - 用于无主p2p自动发现的库和HTTP服务之间的RPC (使用 [ZeroMQ](https://github.com/zeromq/libzmq))。
* [tendermint](https://github.com/tendermint/tendermint) - 高性能中间件，用于将使用任何编程语言编写的状态机转换为使用Tendermint共识和区块链协议的Byzantine Fault Tolerant复制状态机。
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent客户端软件包。
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent的Kademlia的DHT的实现。
    * [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - 视频流媒体客户端。

##  <span id="电子邮件-email">电子邮件 Email</span>

*实现电子邮件创建和发送的库*

* [douceur](https://github.com/aymerick/douceur) - Golang中一个简单的CSS解析器和内联器，HTML电子邮件。
* [email](https://github.com/jordan-wright/email) - 用于Go的健壮而灵活的电子邮件库。
* [go-dkim](https://github.com/toorop/go-dkim) - DKIM库，签署和验证电子邮件。
* [go-imap](https://github.com/emersion/go-imap) - 用于客户端和服务器的IMAP库。
* [go-message](https://github.com/emersion/go-message) - 用于Internet消息格式和邮件消息的流式库。
* [Gomail](https://github.com/go-gomail/gomail/) - Gomail是一个非常简单而强大的发送邮件的软件包。
* [Hectane](https://github.com/hectane/hectane) - 提供HTTP API的轻量级SMTP客户端。
* [hermes](https://github.com/matcornic/hermes) - 生成清晰，响应式HTML电子邮件的Golang软件包。
* [MailHog](https://github.com/mailhog/MailHog) - 通过Web和API接口进行电子邮件和SMTP测试。
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid的Go库用于发送电子邮件。
* [smtp](https://github.com/mailhog/smtp) - SMTP服务器协议状态机。

## <span id="嵌入式脚本语言-embeddable-scripting-languages">嵌入式脚本语言 Embeddable Scripting Languages</span>

*在代码中嵌入其他语言*

* [agora](https://github.com/PuerkitoBio/agora) - 在Go中动态输入，嵌入式编程语言。
* [anko](https://github.com/mattn/anko) - 用Go编写的脚本化的解释器。
* [binder](https://github.com/alexeyco/binder) - 转到基于[gopher-lua](https://github.com/yuin/gopher-lua)的 Lua绑定库。
* [gisp](https://github.com/jcla1/gisp) - Go中的简单LISP。
* [go-duktape](https://github.com/olebedev/go-duktape) - Go的Duktape JavaScript引擎绑定。
* [go-lua](https://github.com/Shopify/go-lua) - Lua 5.2 VM到Pure Go的端口。
* [go-php](https://github.com/deuill/go-php) - PHP bindings for Go.
* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* [ngaro](https://github.com/db47h/ngaro) - 可嵌入的Ngaro虚拟机实现在Retro中启用脚本。
* [otto](https://github.com/robertkrimen/otto) - 用Go编写的JavaScript解释器。
* [purl](https://github.com/ian-kent/purl) - 嵌入在Go中的Perl 5.18.2。

## <span id="文件-files">文件 Files</span>

*用于处理文件和文件系统的库*

* [afero](https://github.com/spf13/afero) - Go的FileSystem抽象系统。
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - 使用标签从go中读取csv文件。
* [go-gtfs](https://github.com/artonge/go-gtfs) - 加载gtfs文件。
* [notify](https://github.com/rjeczalik/notify) - 文件系统事件通知库与简单的API，类似于操作系统/信号。
* [skywalker](https://github.com/dixonwille/skywalker) - 允许一个轻松地同时通过一个文件系统的软件包。
* [tarfs](https://github.com/posener/tarfs) - 用于tar文件的[`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) 接口的实现。

## <span id="金融-financial">金融 Financial</span>

*会计和财务软件包*

* [accounting](https://github.com/leekchan/accounting) - golang的货币和货币格式。
* [decimal](https://github.com/shopspring/decimal) - 任意精度定点十进制数。
* [go-finance](https://github.com/FlashBoys/go-finance) - Go中全面的金融市场数据。
* [go-money](https://github.com/rhymond/go-money) - 实施Fowler的Money模式。
* [ofxgo](https://github.com/aclindsa/ofxgo) - Golang库用于查询和解析（使用示例命令行客户端）。
* [vat](https://github.com/dannyvankooten/vat) - 增值税号码验证和欧盟增值税税率。

## <span id="表单-forms">表单 Forms</span>

*用于处理表单的库*

* [bind](https://github.com/robfig/bind) - 将表单数据绑定到任何Go类型值。
* [binding](https://github.com/mholt/binding) - 将表单和JSON数据从net/http请求绑定到struct。
* [conform](https://github.com/leebenson/conform) - 保持用户输入检查。修剪，清理和清理基于结构标签的数据。
* [form](https://github.com/go-playground/form) - 将url.Values解码为Go值（s）和Encoding Go值（s）到url.Values。双阵列和全地图支持。
* [formam](https://github.com/monoculum/formam) - 将表单的值解码为结构体。
* [forms](https://github.com/albrow/forms) - 框架不可知的库，用于解析和验证支持多部分表单和文件的表单 / JSON数据。
* [gorilla/csrf](https://github.com/gorilla/csrf) - 用于Go web应用程序和服务的CSRF保护。
* [nosurf](https://github.com/justinas/nosurf) - 用于Go的CSRF保护中间件。

## <span id="游戏开发-game-development">游戏开发 Game Development</span> 

*游戏开发库*

* [Azul3D](https://github.com/azul3d/engine) - 用Go编写的3D游戏引擎。
* [Ebiten](https://github.com/hajimehoshi/ebiten) - Go中简单的2D游戏库。
* [engo](https://github.com/EngoEngine/engo) - Engo是一个用Go编写的开源2D游戏引擎。它遵循实体 - 组件系统范例。
* [GarageEngine](https://github.com/vova616/GarageEngine) - 用Go编写的2D游戏引擎，用于OpenGL。
* [glop](https://github.com/runningwild/glop) - Glop（Game Library Of Power）是一个相当简单的跨平台游戏库。
* [go-astar](https://github.com/beefsack/go-astar) - 执行A *路径查找算法。
* [go-collada](https://github.com/GlenKelley/go-collada) - Go包使用Collada文件格式。
* [go-sdl2](https://github.com/veandco/go-sdl2) - 为[Simple DirectMedia Layer](https://www.libsdl.org/)绑定。 
* [go3d](https://github.com/ungerik/go3d) - 面向Go的面向性能的2D / 3D数学包。
* [gonet](https://github.com/xtaci/gonet) - 用golang实现的游戏服务器框架。
* [goworld](https://github.com/xiaonanln/goworld) - 可扩展游戏服务器引擎，具有空间实体框架和热插拔功能。
* [Leaf](https://github.com/name5566/leaf) - 轻量级游戏服务器框架。
* [nano](https://github.com/lonnng/nano) -  轻量级，设施，高性能golang基于游戏服务器框架。
* [Oak](https://github.com/oakmound/oak) - Pure Go游戏引擎。
* [Pixel](https://github.com/faiface/pixel) - 手工制作的2D游戏库。
* [raylib-go](https://github.com/gen2brain/raylib-go) - 用于[raylib](http://www.raylib.com/)的绑定，一个简单易用的库，用于学习电子游戏编程。
* [termloop](https://github.com/JoelOtter/termloop) - 基于终端的Go游戏引擎，建立在Termbox之上。

## <span id="代和泛型-generation-and-generics">代和泛型 Generation and Generics</span>

*通过代码生成来增强泛型等功能的工具*

* [efaceconv](https://github.com/t0pep0/efaceconv) - 代码生成工具，用于从接口{}高性能转换为不分配的不可变类型。
* [gen](https://github.com/clipperhouse/gen) - “泛型”功能的代码生成工具。
* [go-enum](https://github.com/abice/go-enum) - 从代码注释代码生成枚举。
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - 用于Go的.NET类似LINQ的查询方法。
* [goderive](https://github.com/awalterschulze/goderive) - 从输入类型派生函数。
* [interfaces](https://github.com/rjeczalik/interfaces) - 用于生成接口定义的命令行工具。
* [jennifer](https://github.com/dave/jennifer) - 生成任意的没有模板的Go代码。
* [pkgreflect](https://github.com/ungerik/pkgreflect) - 执行软件包作用域反射的预处理器。

## <span id="go编译器-go-compilers">GO编译器 Go Compilers</span>

*编译转到其他语言工具*

* [gopherjs](https://github.com/gopherjs/gopherjs) - 编译从GO语言转到JavaScript。
* [llgo](https://github.com/go-llvm/llgo) - 基于LLVM的Go编译器。
* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang到Haxe到CPP / CSharp / Java / JavaScript transpiler。

## <span id="协程-Coroutines">协程 Coroutines</span>
    
*管理和使用协程工具。*

* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - 控制协程执行顺序。
* [GoSlaves](https://github.com/themester/GoSlaves) - 一个GO语言实现的简单和异步协程池库。
* [goworker](https://github.com/benmanns/goworker) - goworker是一个基于Go的后台work，比基于Ruby的work快10到10万倍。
* [grpool](https://github.com/ivpusic/grpool) - 轻量级协程池.
* [pool](https://github.com/go-playground/pool) - 有限的消费者会议室或无限的协程池，以便于处理和取消。
* [semaphore](https://github.com/kamilsk/semaphore) - 基于信道和上下文的超时锁定/解锁操作的信号量模式实现。
* [tunny](https://github.com/Jeffail/tunny) - 一个golang的协程池
* [worker-pool](https://github.com/vardius/worker-pool) - goworker是Go简单的异步工作池。
* [workerpool](https://github.com/gammazero/workerpool) - 协程池，限制任务执行的并发性，而不是排队的任务数。

## <span id="gui">GUI</span>

*用于构建GUI应用程序的库*

*工具包*

* [app](https://github.com/murlokswarm/app) - 使用GO，HTML和CSS创建应用程序的包。支持：MacOS，Windows正在进行。
* [go-astilectron](https://github.com/asticode/go-astilectron) - 使用GO和HTML / JS / CSS（由Electron提供支持）构建跨平台GUI应用程序。
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-qml](https://github.com/go-qml/qml) - Go语言的QML支持。
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML / CSS / script engine for modern desktop UI development. Cross platform.
* [goqt](https://github.com/visualfc/goqt) - Golang绑定到Qt跨平台应用程序框架。
* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* [gowd](https://github.com/dtylman/gowd) - 使用GO，HTML，CSS和NW.js进行快速简单的桌面用户界面开发 跨平台。
* [qt](https://github.com/therecipe/qt) - Go的Qt绑定（支持Windows / macOS / Linux / Android / iOS / Sailfish OS/Raspberry Pi）。
* [ui](https://github.com/andlabs/ui) - 用于Go的平台本地GUI库。跨平台。
* [walk](https://github.com/lxn/walk) - Windows的应用程序库工具包。
* [webview](https://github.com/zserge/webview) - 具有简单的双向JavaScript绑定（Windows / macOS / Linux）的跨平台webview窗口。

*相互作用*

* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - 用于Go的OSX桌面通知库。
* [robotgo](https://github.com/go-vgo/robotgo) - Go Native跨平台GUI系统自动化。控制鼠标，键盘和其他。
* [systray](https://github.com/getlantern/systray) - 跨平台去图书馆在通知区域放置一个图标和菜单。
* [trayhost](https://github.com/shurcooL/trayhost) - 跨平台的Go库在主机操作系统的任务栏中放置一个图标。

## <span id="硬件-hardware">硬件 Hardware</span>

*用于与硬件交互的库，工具和教程*

请参阅[硬件](https://github.com/rakyll/go-hardware)硬件了解全面的列表。

## <span id="图片-images">图片 Images</span>

*用于处理图像的库*

* [bild](https://github.com/anthonynsimon/bild) - 纯Go中的图像处理算法集合。
* [bimg](https://github.com/h2non/bimg) - 使用libvips进行快速高效的图像处理的小型软件包。
* [geopattern](https://github.com/pravj/geopattern) - 从字符串中创建美的生成图像模式。
* [gg](https://github.com/fogleman/gg) - GO语言原生实现绘制二维图。
* [gift](https://github.com/disintegration/gift) - 图像处理过滤软件包。
* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library.
* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go.
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
* [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.
* [img](https://github.com/hawx/img) - Selection of image manipulation tools.
* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go.
* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go.
* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.

## <span id="物联网-iot-internet-of-things">物联网 IoT (Internet of Things)</span>

*用于编程物联网设备的库*

* [connectordb](https://github.com/connectordb/connectordb) - 开源的物联网量化平台。
* [devices](https://github.com/goiot/devices) - 用于物联网设备的库套件，用于x / exp / io的实验。
* [eywa](https://github.com/xcodersun/eywa) - Project Eywa本质上是一个连接管理器，用于跟踪连接的设备。
* [flogo](https://github.com/tibcosoftware/flogo) - Flogo项目是IoT Edge应用程序和集成的开源框架。
* [gatt](https://github.com/paypal/gatt) - Gatt是构建蓝牙低功耗外设的Go包。
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot是机器人，物理计算和物联网的框架。
* [mainflux](https://github.com/Mainflux/mainflux) - 业物联网消息和设备管理服务器。
* [sensorbee](https://github.com/sensorbee/sensorbee) - 用于物联网的轻量级流处理引擎。

## <span id="日志-logging">日志 Logging</span>

*Libraries for generating and working with log files.*

* [distillog ](https://github.com/amoghe/distillog) - 提供还支持日志级别的简约日志记录界面。
* [glg](https://github.com/kpango/glg) - GLG是简单和快速的级别GO语言日志库。
* [glog](https://github.com/golang/glog) - Go的平台执行日志。
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* [log](https://github.com/apex/log) - Structured logging package for Go.
* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
* [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go.
* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.

## <span id="机器学习-machine-learning">机器学习 Machine Learning</span>

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
* [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
* [gago](https://github.com/MaxHalford/gago) - Multi-population, flexible, parallel genetic algorithm.
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go.
* [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
* [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
* [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go.
* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
* [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
* [gorgonia](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
* [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
* [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
* [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
* [mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go.
* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
* [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
* [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
* [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
* [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.

## <span id="消息-messaging">消息 Messaging</span>

*Libraries that implement messaging systems.*

* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://business.line.me/en/services/bot) notifications using a binary, docker or Drone CI.
* [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
* [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
* [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
* [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
* [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
* [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
* [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
* [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
* [goose](https://github.com/ian-kent/goose) - Server Sent Events in Go.
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm).
* [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
* [mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability.
* [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
* [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
* [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2).

## <span id="其他-miscellaneous">其他 Miscellaneous</span>

*These libraries were placed here because none of the other categories seemed to fit.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).
* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.
* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
* [go.uuid](https://github.com/satori/go.uuid) - Implementation of Universally Unique Identifier (UUID). Supported both creation and parsing of UUIDs.
* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
* [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
* [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
* [secdl](https://github.com/xor-gate/secdl) - Lighttpd ModSecDownload algorithm ported to go to secure download urls.
* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go.
* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and ouput handling.
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.
* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

## <span id="自然语言处理-natural-language-processing">自然语言处理 Natural Language Processing</span>

*Libraries for working with human languages.*

* [dpar](https://github.com/danieldk/dpar/) - Transition-based statistical dependency parser.
* [go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
* [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
* [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.
* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more.
* [RAKE.go](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences.
* [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
* [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.
* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).
* [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.

## <span id="网络-networking">网络 Networking</span>
    
*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* [dns](https://github.com/miekg/dns) - Go library for working with DNS.
* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).
* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
* [graval](https://github.com/koofr/graval) - Experimental FTP server framework.
* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
* [water](https://github.com/songgao/water) - Simple TUN/TAP library.
* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol.
* [YANNFF](https://github.com/intel-go/yanff) - Framework for rapid development of performant network functions for cloud and bare-metal.

## <span id="opengl">OpenGL</span>

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

## <span id="orm">ORM</span>

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.
* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* [gomodel](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database.
* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
* [Marlow](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances.
* [pop/soda](https://github.com/markbates/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM.
* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go.
* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

## <span id="包管理-package-management">包管理 Package Management</span>

*Libraries for package and dependency management.*

* [dep](https://github.com/golang/dep) - Go dependency tool.
* [gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes.
* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go.
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
* [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH
* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager.
* [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* [gvt](https://github.com/FiloSottile/gvt) - `gvt` is a simple vendoring tool made for Go native vendoring (aka GO15VENDOREXPERIMENT), based on gb-vendor.
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies.
* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.

## <span id="查询语言-query-language">查询语言 Query Language</span> 

* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities.
* [graphql](https://github.com/sevki/graphql) - GraphQL implementation in go.
* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang.

## <span id="资源嵌入-resource-embedding">资源嵌入 Resource Embedding</span>

* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable.
* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.
* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

## <span id="科学和数据分析-science-and-data-analysis">科学和数据分析 Science and Data Analysis</span>

*Libraries for scientific computing and data analyzing.*

* [blas](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms).
* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang.
* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* [go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg.
* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
* [go.matrix](https://github.com/skelterjohn/go.matrix) - linear algebra for go (has been stalled).
* [gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language.
* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures
* [gofrac](https://github.com/anschelsc/gofrac) - (goinstallable) fractions library for go with support for basic arithmetic.
* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
* [gonum/mat64](https://github.com/gonum/matrix) - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices.
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).
* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* [gostat](https://github.com/ematvey/gostat) - Statistics library for the go language.
* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* [vectormath](https://github.com/spate/vectormath) - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code (currently inactive).

## <span id="安全-security">安全 Security</span>

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
* [lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
* [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library.
* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.

## <span id="序列化-serialization">序列化 Serialization</span>

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.

## <span id="服务器应用程序-server-applications">服务器应用程序 Server Applications</span> 

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers.
* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
* [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [yakvs](https://github.com/sci4me/yakvs) - Small, networked, in-memory key-value store.

## <span id="模板引擎-template-engines">模板引擎 Template Engines</span> 

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.
* [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).
* [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.
* [grender](https://github.com/dannyvankooten/grender) - small wrapper around html/template for file-based templates that support extending other template files.
* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* [jet](https://github.com/CloudyKit/jet) - Jet template engine.
* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.
* [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
* [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.
* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
* [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang.
* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.

## <span id="测试-testing">测试 Testing</span>

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
    * [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
    * [bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them.
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
    * [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
    * [frisby](https://github.com/verdverm/frisby) - REST API testing framework.
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
    * [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
    * [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
    * [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go.
    * [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
    * [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
    * [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
    * [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
    * [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    * [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
    * [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
    * [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.
    * [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
    * [chromedp](https://github.com/knq/chromedp) - Way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
    * [ggr](https://github.com/aandryashin/ggr) - Lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs.
    * [selenoid](https://github.com/aandryashin/selenoid) - alternative Selenium hub server that launches browsers within containers.

## <span id="文字处理-text-processing">文字处理 Text Processing</span> 

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
    * [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers
    * [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
    * [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).
    * [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
    * [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
    * [go-pkg-rss](https://github.com/jteeuwen/go-pkg-rss) - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs.
    * [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
    * [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
    * [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.
    * [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
    * [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
    * [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
    * [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
    * [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
    * [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
    * [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
    * [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
    * [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
    * [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
* Utility
    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
    * [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
    * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.
    * [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm.
    * [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.
    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text.

## <span id="第三方api-third-party-apis">第三方API Third-party APIs</span> 

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* [ghost](https://github.com/neuegram/ghost) - Go Library for accessing the Snapchat API.
* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* [go-telegraph](https://github.com/toby3d/go-telegraph) - Telegraph publishing platform API client.
* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* [goamz](https://github.com/mitchellh/goamz) - Popular fork of [goamz](https://launchpad.net/goamz) which adds some missing API calls to certain packages.
* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* [paypal](https://github.com/logpacker/paypalsdk) - Wrapper for PayPal payment API.
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* [slack](https://github.com/nlopes/slack) - Slack API in Go.
* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org).
* [translate](https://github.com/poorny/translate) - Go online translation package.
* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

## Utilities

*General utilities and tools to make your life easier.*

* [abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers.
* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* [coop](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go.
* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* [delve](https://github.com/derekparker/delve) - Go debugger.
* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang.
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* [go-debug](https://github.com/tj/go-debug) - Conditional debug logging for Golang libraries & applications.
* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs.
* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* [gojq](https://github.com/elgs/gojq) - JSON query in Golang.
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events.
* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [goreq](https://github.com/franela/goreq) - Minimal and simple request library for Go language.
* [goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest.
* [gorequest](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with rich features for Go.
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* [grequests](https://github.com/levigross/grequests) - Elegant and simple `net/http` wrapper that follows Python's requests library.
* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* [httpcontrol](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries.
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [immortal](https://github.com/immortal/immortal) - *nix cross-platform (OS agnostic) supervisor.
* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* [mmake](https://github.com/tj/mmake) - Modern Make.
* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* [ngrok](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost.
* [okrun](https://github.com/xta/okrun) - go run error steamroller.
* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [retry](https://github.com/kamilsk/retry) - Functional mechanism based on context to perform actions repetitively until successful.
* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
* [sling](https://github.com/dghubble/sling) - Go HTTP requests builder for API clients.
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
* [Task](https://github.com/go-task/task) - simple "Make" alternative.
* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.

## Validation

*Libraries for validation.*

* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* [validate](https://github.com/markbates/validate) - This package provides a framework for writing validations for Go applications.
* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.

## Version Control

*Libraries for version control.*

* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
* [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg.
* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer.
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Air](https://github.com/sheng/air) - Ideal RESTful web framework for Go.
* [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
* [Florest](https://github.com/jabong/florest-core) - High-performance workflow based REST API framework.
* [Gem](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API.
* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* [go-relax](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* [goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis.
* [Goat](https://github.com/bahlo/goat) - Minimalistic REST API server in Go.
* [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
* [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
* [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
* [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
* [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
* [sawsij](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go.
* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
* [violetear](https://github.com/nbari/violetear) - Go HTTP router.
* [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.
* [Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework.

### Middlewares

#### Actual middlewares

* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
* [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http.
* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
* [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.
* [Volatile](https://github.com/volatile/core) - Minimalist middleware stack promoting flexibility, good practices and clean code.

### Routers

* [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.
* [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* [medeina](https://github.com/imdario/medeina) - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba.
* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* [pat](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra.
* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
* [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
* [zeus](https://github.com/daryl/zeus) - Very simple and fast HTTP router for Go.

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.

## XML

*Libraries and tools for manipulating XML.*

* [go-pkg-xmlx](https://github.com/jteeuwen/go-pkg-xmlx) - Extension to the standard Go XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions.
* [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
* [xpath](https://github.com/antchfx/xpath) - XPath package for Go.
* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.

# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
* [dupl](https://github.com/mibk/dupl) - Tool for code clone detection.
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* [Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form.
* [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments.
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
* [interfacer](https://github.com/mvdan/interfacer) - Linter that suggests interface types.
* [lint](https://github.com/surullabs/lint) - Run linters as part of go test.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.
* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [Goclipse](https://github.com/GoClipse/goclipse) - Eclipse plugin for Go.
* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features.
* [velour](https://github.com/velour/velour) - IRC client for the acme editor.
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* [vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

## Go Generate Tools

* [generic](https://github.com/usk81/generic) - flexible data type for Go.
* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go.
* [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go.
* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.
* [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
* [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
* [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.

## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
* [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
* [Banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics.
* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* [Go Metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics.
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
* [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the reponse code and data between each call for specific server stress based on its previous response.
* [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

### Other Software
* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine.
* [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* [fleet](https://github.com/coreos/fleet) - Distributed init System.
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at funciton list.
* [Gogland](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
* [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* [orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go.
* [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* [Postman](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email.
* [restic](https://github.com/restic/restic) - De-duplicating backup program.
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
* [toto](https://github.com/blogcin/ToTo) - Simple proxy server written in Go language, can be used together with browser.
* [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* [websysd](https://github.com/ian-kent/websysd) - Web based process manager (like Marathon or Upstart).
* [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* [go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go.
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others.
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA
* [dotGo](http://www.dotgo.eu) - Paris, France
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan
* [GolangUK](http://golanguk.com/) - London, UK
* [GopherChina](http://gopherchina.org) - Shanghai, China
* [GopherCon](http://www.gophercon.com/) - Denver, USA
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR
* [GopherCon Dubai](http://www.gophercon.ae/) - Dubai, UAE
* [GopherCon India](http://www.gophercon.in/) - Pune, India
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore
* [GothamGo](http://gothamgo.com/) - New York City, USA

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go Bootcamp](http://golangbootcamp.com)
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)

## Meetups

* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* [Flipboard - Go Magazine](https://flipboard.com/section/the-golang-magazine-bVP7nS) - Collection of Go articles and tutorials.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](http://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.

### Tutorials

* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.




