# Awesome Go

[Gold]: ./docs/Gold.svg "star > 5000"
[Silver]: ./docs/Silver.svg "star > 1000"
[Bronze]: ./docs/Bronze.svg "star > 100"
[Green]: ./docs/Green.svg "最近一个周有更新"
[Yellow]: ./docs/Yellow.svg "最近三个月没有更新"

**此项目是 [awesome-go](https://awesome-go.com/) 中文版，最后一次同步时间 : 2019-07-03 09:17:24(每隔1天同步一次)**

**:star:项目地址 : [yinggaozhen/awesome-go-cn](https://github.com/yinggaozhen/awesome-go-cn):star:**

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinosource) 为Awesome Go打赏~

精选了一系列很棒的Go框架、库和软件。灵感来自于[awesome-python](https://github.com/vinta/awesome-python)。

### 贡献

你可以快速浏览贡献者名单[contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md). 感觉所有为此项目付出的同学[contributors](https://github.com/avelino/awesome-go/graphs/contributors); 你真棒!

如果您在看到一个包或项目不再维护或不适合，请往awesome-go提交[Pull Request](https://github.com/avelino/awesome-go/pulls)，本项目每隔一天与英文文档同步。感谢!

### 内容

- [Awesome Go](#awesome-go)
    - [音频和音乐](#音频和音乐)
    - [身份验证和OAuth](#身份验证和oauth)
    - [Bot建设](#bot建设)
    - [命令行](#命令行)
    - [配置](#配置)
    - [持续集成](#持续集成)
    - [CSS预处理器](#css预处理器)
    - [数据结构](#数据结构)
    - [数据库](#数据库)
    - [数据库驱动程序](#数据库驱动程序)
    - [日期和时间](#日期和时间)
    - [分布式系统](#分布式系统)
    - [电子邮件](#电子邮件)
    - [可嵌入的脚本语言](#可嵌入的脚本语言)
    - [错误处理](#错误处理)
    - [文件](#文件)
    - [金融](#金融)
    - [表单](#表单)
    - [方法](#方法)
    - [游戏开发](#游戏开发)
    - [代码生成与泛型](#代码生成与泛型)
    - [地理](#地理)
    - [Go 编译器](#go-编译器)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [硬件](#硬件)
    - [图片](#图片)
    - [物联网](#物联网)
    - [作业调度器](#作业调度器)
    - [JSON](#json)
    - [日志记录](#日志记录)
    - [机器学习](#机器学习)
    - [消息](#消息)
    - [微软办公软件](#微软办公软件)
        - [Microsoft Excel](#microsoft-excel)
    - [杂项](#杂项)
        - [依赖注入](#依赖注入)
        - [项目布局](#项目布局)
        - [字符串](#字符串)
    - [自然语言处理](#自然语言处理)
    - [网络](#网络)
        - [HTTP客户端](#http客户端)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [包管理](#包管理)
    - [查询语言](#查询语言)
    - [嵌入的资源](#嵌入的资源)
    - [科学与数据分析](#科学与数据分析)
    - [安全](#安全)
    - [序列化](#序列化)
    - [模板引擎](#模板引擎)
    - [测试](#测试)
    - [文本处理](#文本处理)
    - [Third-party APIs](#third-party-apis)
    - [公用事业公司](#公用事业公司)
    - [UUID](#uuid)
    - [验证](#验证)
    - [版本控制](#版本控制)
    - [视频](#视频)
    - [Web框架](#web框架)
        - [中间件](#中间件)
            - [仿真中间件](#仿真中间件)
            - [用于创建HTTP中间件的库](#用于创建http中间件的库)
        - [路由器](#路由器)
    - [Windows](#windows)
    - [XML](#xml)

- [工具](#工具)
    - [代码分析](#代码分析)
    - [编辑器插件](#编辑器插件)
    - [Go 生成工具](#go-生成工具)
    - [Go 工具](#go-工具)
    - [软件包](#软件包)
        - [DevOps 工具](#devops-工具)
        - [其他软件](#其他软件)

- [服务器应用程序](#服务器应用程序)

- [资源](#资源)
    - [基准](#基准)
    - [会议](#会议)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [聚会](#聚会)
    - [Twitter](#twitter)
    - [网站](#网站)
        - [教程](#教程)

## 音频和音乐

*用于操作音频的库。*

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - **Star : 20** EasyMidi是一个简单可靠的库，用于处理标准midi文件(SMF)。![最近三个月没有更新][Yellow]
* [flac](https://github.com/eaburns/flac) - **Star : 84** 原生 Go FLAC解码器，将FLAC文件解码为字节片。![最近三个月没有更新][Yellow]
* [flac](https://github.com/mewkiz/flac) - **Star : 101** 原生 Go FLAC编码器/解码器，支持FLAC流。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gaad](https://github.com/Comcast/gaad) - **Star : 55** 原生 Go AAC位流解析器。![最近三个月没有更新][Yellow]
* [go-sox](https://github.com/krig/go-sox) - **Star : 92** libsox 的 Go 语言实现接口。![最近三个月没有更新][Yellow]
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - **Star : 24** libmediainfo 的 Go 语言实现接口。![最近三个月没有更新][Yellow]
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - **Star : 8** libsamplerate 的 Go 语言实现接口。![最近三个月没有更新][Yellow]
* [id3v2](https://github.com/bogem/id3v2) - **Star : 107** 快速稳定的 ID3 解析及写入Go库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [malgo](https://github.com/gen2brain/malgo) - **Star : 68** 迷你音频库。
* [minimp3](https://github.com/tosone/minimp3) - **Star : 25** 轻量级MP3解码器库。![最近三个月没有更新][Yellow]
* [mix](https://github.com/go-mix/mix) - **Star : 95** 基于序列的 Go 原生音乐混音器。![最近三个月没有更新][Yellow]
* [mp3](https://github.com/tcolgate/mp3) - **Star : 89** 原生 Go MP3解码器。![最近三个月没有更新][Yellow]
* [music-theory](https://github.com/go-music-theory/music-theory) - **Star : 250** 基于 Go 的音乐理论模型。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Oto](https://github.com/hajimehoshi/oto) - **Star : 383** 多平台的 low-level 声音播放库。![star > 100][Bronze]![最近一个周有更新][Green]
* [PortAudio](https://github.com/gordonklaus/portaudio) - **Star : 295** 基于 Go 的PortAudio audio I/O库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [portmidi](https://github.com/rakyll/portmidi) - **Star : 203** PortMidi的 Go 语言实现接口。。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [taglib](https://github.com/wtolson/go-taglib) - **Star : 66** taglib 的 Go 语言实现接口。。![最近三个月没有更新][Yellow]
* [vorbis](https://github.com/mccoyst/vorbis) - **Star : 22** “原生” Go Vorbis解码器(使用CGO，但没有依赖关系)。![最近三个月没有更新][Yellow]
* [waveform](https://github.com/mdlayher/waveform) - **Star : 245** 通过音频流生成波形图像的包。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 身份验证和OAuth

*用于实现验证方案的库。*

* [authboss](https://github.com/volatiletech/authboss) - **Star : 1892** web模块化认证系统。它试图删除尽可能多的模板文件和硬编码，以便每次新建一个新的web项目时，您都可以插入、配置并开始构建您的应用程序，而不必每次都构建一个身份验证系统。![star > 1000][Silver]![最近一个周有更新][Green]
* [branca](https://github.com/hako/branca) - **Star : 67** 基于 Go 实现Branca令牌。![最近三个月没有更新][Yellow]
* [casbin](https://github.com/hsluoyz/casbin) - **Star : 4653** 支持ACL、RBAC、ABAC等访问控制模型的授权库。![star > 1000][Silver]![最近一个周有更新][Green]
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - **Star : 2** 提供cookie .txt文件格式的解析器。![最近三个月没有更新][Yellow]
* [go-jose](https://github.com/square/go-jose) - **Star : 1088** 相当完整地实现了JOSE工作组的JSON Web令牌、JSON Web签名和JSON Web加密规范。![star > 1000][Silver]![最近一个周有更新][Green]
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - **Star : 1247** 用 Golang 编写的独立且符合规范的OAuth2服务器。![star > 1000][Silver]
* [gologin](https://github.com/dghubble/gologin) - **Star : 1028** 用于使用OAuth1和OAuth2身份验证提供者登录的可链处理程序。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [gorbac](https://github.com/mikespook/gorbac) - **Star : 896** 轻量级的基于角色的访问控制(RBAC)实现。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goth](https://github.com/markbates/goth) - **Star : 2214** 提供了 OAuth 和 OAuth2 的简单清晰易用的方法。可开箱即用处理多个提供程序。![star > 1000][Silver]
* [httpauth](https://github.com/goji/httpauth) - **Star : 175** HTTP身份验证中间件。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [jwt](https://github.com/robbert229/jwt) - **Star : 68** 简单易用的JSON Web令牌实现(JWT)。![最近三个月没有更新][Yellow]
* [jwt](https://github.com/pascaldekloe/jwt) - **Star : 76** 轻量级JSON Web令牌库。![最近一个周有更新][Green]
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - **Star : 151** JWT中间件，可用于Golang http服务器，提供了许多配置选项。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [jwt-go](https://github.com/dgrijalva/jwt-go) - **Star : 5709** JSON Web令牌(JWT)。![star > 5000][Gold]
* [loginsrv](https://github.com/tarent/loginsrv) - **Star : 793** JWT登录微服务带有可插拔的后端服务，如OAuth2 (Github)、htpasswd、osiam。![star > 100][Bronze]
* [oauth2](https://github.com/golang/oauth2) - **Star : 2325** goauth2的继任者。通用OAuth 2.0包，附带JWT、谷歌api、计算引擎和应用程序引擎支持。![star > 1000][Silver]
* [osin](https://github.com/openshift/osin) - **Star : 1535** OAuth2服务器库。![star > 1000][Silver]
* [paseto](https://github.com/o1egl/paseto) - **Star : 220** 平台无关的安全令牌(PASETO)。![star > 100][Bronze]
* [permissions2](https://github.com/xyproto/permissions2) - **Star : 346** 用于跟踪用户、登录状态和权限的库。依赖于cookie安全和bcrypt。![star > 100][Bronze]
* [rbac](https://github.com/zpatrick/rbac) - **Star : 25** 最小的RBAC包。![最近三个月没有更新][Yellow]
* [scs](https://github.com/alexedwards/scs) - **Star : 515** HTTP服务器的会话管理器。![star > 100][Bronze]
* [securecookie](https://github.com/chmike/securecookie) - **Star : 31** 高效安全的cookie编码/解码。![最近三个月没有更新][Yellow]
* [session](https://github.com/icza/session) - **Star : 87** web服务器会话管理(包括支持谷歌应用程序引擎- GAE)。![最近一个周有更新][Green]
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - **Star : 8** 使用SessionGate Redis模块进行会话管理。![最近三个月没有更新][Yellow]
* [sessions](https://github.com/adam-hanna/sessions) - **Star : 45** 非常简单，高性能，可深度定制的会话服务，主要用于的 go http 服务器。
* [signedvalue](https://github.com/sashka/signedvalue) - **Star : 7** 与[Tornado's](https://github.com/tornado oweb/tornado) 完全兼容的签名和时间戳字符串实现. create_signed_value '， ' decode_signed_value '，因此' set_secure_cookie '和' get_secure_cookie '。![最近三个月没有更新][Yellow]

## Bot建设

*用于构建和使用机器人的库。*

* [go-chat-bot](https://github.com/go-chat-bot/bot) - **Star : 453** 用 Go 编写的IRC, Slack和电报机器人。![star > 100][Bronze]
* [go-sarah](https://github.com/oklahomer/go-sarah) - **Star : 128** 此框架提供了聊天机器人相关的服务，包括LINE、Slack、Gitter等。![star > 100][Bronze]![最近一个周有更新][Green]
* [go-tgbot](https://github.com/olebedev/go-tgbot) - **Star : 82** 由swagger文件、基于会话的路由器和中间件生成的纯Golang Telegram Bot API包装器。![最近三个月没有更新][Yellow]
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - **Star : 207** 基于控制台的，用于加密货币交易所的的交易机器人。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [govkbot](https://github.com/nikepan/govkbot) - **Star : 22** 简单的Go [VK](https://vk.com) bot库。![最近三个月没有更新][Yellow]
* [hanu](https://github.com/sbstjn/hanu) - **Star : 107** 用于编写Slack机器人的框架。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Kelp](https://github.com/stellar/kelp) - **Star : 146** 官方交易和做市机器人为[Stellar](https://www.stellar.org/) DEX。开箱即用的作品，用 Golang 编写，兼容集中交易和定制交易策略。![star > 100][Bronze]![最近一个周有更新][Green]
* [margelet](https://github.com/zhulik/margelet) - **Star : 57** 构建电报机器人的框架。![最近三个月没有更新][Yellow]
* [micha](https://github.com/onrik/micha) - **Star : 10** 基于 GO 实现的Telegram 机器人API库。![最近三个月没有更新][Yellow]
* [slacker](https://github.com/shomali11/slacker) - **Star : 298** 可简单创建Slack机器人的框架。![star > 100][Bronze]
* [slackscot](https://github.com/alexandre-normand/slackscot) - **Star : 10** 另一个构建Slack机器人的框架。![最近一个周有更新][Green]
* [tbot](https://github.com/yanzay/tbot) - **Star : 212** 带有类似于net/http API的Telegram bot服务器。![star > 100][Bronze]
* [telebot](https://github.com/tucnak/telebot) - **Star : 923** 用Go编写的Telegram bot框架。![star > 100][Bronze]
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - **Star : 1556** 简单轻量级的Telegram bot客户端。![star > 1000][Silver]
* [Tenyks](https://github.com/kyleterry/tenyks) - **Star : 167** 面向服务的IRC bot，使用Redis和JSON进行消息传递。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 命令行

### 标准CLI

*用于构建标准或基本命令行应用程序的库。*

* [argparse](https://github.com/akamensky/argparse) - **Star : 99** 命令行参数分析器，灵感来自Python的argparse模块。![最近三个月没有更新][Yellow]
* [argv](https://github.com/cosiner/argv) - **Star : 16** 基于Base 语法，用于分隔命令行字符串并将其作为参数的 Go 语言库，
* [cli](https://github.com/mkideal/cli) - **Star : 470** 基于golang结构标签，功能丰富易于使用的命令行包。![star > 100][Bronze]
* [cli](https://github.com/teris-io/cli) - **Star : 56** 为 Go 构建命令接口提供简单而完整的API。
* [cli-init](https://github.com/tcnksm/gcli) - **Star : 867** 一个简单就可开启构建Golang命令行的应用程序。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [cmdr](https://github.com/hedzr/cmdr) - **Star : 7** 一个POSIX/GNU风格的、类似getopt的命令行UI Go库。
* [cobra](https://github.com/spf13/cobra) - **Star : 12559** 现代Go CLI命令行交互工具。![star > 5000][Gold]![最近一个周有更新][Green]
* [commandeer](https://github.com/jaffee/commandeer) - **Star : 78** 开发友好的CLI应用程序。![最近一个周有更新][Green]
* [complete](https://github.com/posener/complete) - **Star : 607** 使用 Go 语言编写的 bash 命令补全工具以及 Go 命令补全工具.![star > 100][Bronze]![最近一个周有更新][Green]
* [docopt.go](https://github.com/docopt/docopt.go) - **Star : 1133** 会让你满意的命令行参数解析器。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [env](https://github.com/codingconcepts/env) - **Star : 41** 基于标记的结构化的环境配置。
* [flag](https://github.com/cosiner/flag) - **Star : 100** 简单但功能强大的命令行选项解析库，用于支持Go子命令。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [flaggy](https://github.com/integrii/flaggy) - **Star : 441** 一个健壮的、易用的标志包，具有出色的子命令支持。![star > 100][Bronze]
* [flagvar](https://github.com/sgreben/flagvar) - **Star : 31** 符合 Go 标准的“flag”标志参数类型包。
* [go-arg](https://github.com/alexflint/go-arg) - **Star : 641** 基于结构的参数解析。![star > 100][Bronze]
* [go-commander](https://github.com/yitsushi/go-commander) - **Star : 14** 用于简化CLI工作流的 Go 库。
* [go-flags](https://github.com/jessevdk/go-flags) - **Star : 1488**  Go 命令行选项解析器。![star > 1000][Silver]
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - **Star : 5**  Go 选择解析器，借鉴于Perl灵活性的GetOpt::Long。![最近一个周有更新][Green]
* [gocmd](https://github.com/devfacet/gocmd) - **Star : 33** 用于构建命令行应用程序。![最近三个月没有更新][Yellow]
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - 具有自动配置和依赖注入的cli应用程序框架。
* [job](https://github.com/liujianping/job) - **Star : 41** 工作，把你的短期指令当作长期任务。
* [kingpin](https://github.com/alecthomas/kingpin) - **Star : 2491** 支持子命令的命令行和标志解析器。![star > 1000][Silver]
* [liner](https://github.com/peterh/liner) - **Star : 569** 类似readline-like的命令行接口库。![star > 100][Bronze]
* [mitchellh/cli](https://github.com/mitchellh/cli) - **Star : 983** 用于实现命令行接口的Go库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [mow.cli](https://github.com/jawher/mow.cli) - **Star : 619** 用于构建具有复杂标志和参数解析和验证的CLI应用程序。![star > 100][Bronze]
* [ops](https://github.com/nanovms/ops) - **Star : 187** Unikernel Builder /协调器。![star > 100][Bronze]![最近一个周有更新][Green]
* [pflag](https://github.com/spf13/pflag) - **Star : 729** 基于POSIX/GNU-style --flags实现的包，主要用于替换Go的falg包。![star > 100][Bronze]![最近一个周有更新][Green]
* [readline](https://github.com/chzyer/readline) - **Star : 1362** 纯golang实现，在MIT许可下提供了GNU-Readline的大部分特性。![star > 1000][Silver]
* [sand](https://github.com/Zaba505/sand) - **Star : 5** 用于创建解释器等的简单API。![最近三个月没有更新][Yellow]
* [sflags](https://github.com/octago/sflags) - **Star : 84** 基于结构的flag生成器，用于flag、urfave/cli、pflag、cobra、kingpin和其他库。![最近三个月没有更新][Yellow]
* [strumt](https://github.com/antham/strumt) - **Star : 27** 用于创建提示链。![最近三个月没有更新][Yellow]
* [ukautz/clif](https://github.com/ukautz/clif) - **Star : 98** 简小的命令行接口框架。![最近三个月没有更新][Yellow]
* [urfave/cli](https://github.com/urfave/cli) - **Star : 11063** 可让你简单、快速和愉快的构建命令行应用(之前是codegangsta/cli)。![star > 5000][Gold]![最近一个周有更新][Green]
* [wlog](https://github.com/dixonwille/wlog) - **Star : 33** 支持跨平台和并发的简单日志记录接口。![最近三个月没有更新][Yellow]
* [wmenu](https://github.com/dixonwille/wmenu) - **Star : 80** 为cli程序提供了简单上手的菜单，可提示用户作出选择。

### 高级控制台用户界面

*用于构建控制台应用程序和控制台用户界面的库。*

* [asciigraph](https://github.com/guptarohit/asciigraph) - **Star : 1109** 在命令行中构建轻量级ASCII线图╭┈╯，应用程序中没有其他依赖项。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [aurora](https://github.com/logrusorgru/aurora) - **Star : 596** 支持fmt.Printf/Sprintf的ANSI终端颜色。![star > 100][Bronze]
* [cfmt](https://github.com/mingrammer/cfmt) - **Star : 67** 提供上下文的fmt，灵感来自于bootstrap color classes。![最近三个月没有更新][Yellow]
* [chalk](https://github.com/ttacon/chalk) - **Star : 302** 美化终端/控制台输出。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [color](https://github.com/fatih/color) - **Star : 2980** 多功能包装，彩色终端输出。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [colourize](https://github.com/TreyBastian/colourize) - **Star : 16** 在终端提供ANSI彩色文本。![最近三个月没有更新][Yellow]
* [ctc](https://github.com/wzshiming/ctc) - **Star : 9** 不需要Print方法的非侵入性跨平台终端颜色库。![最近三个月没有更新][Yellow]
* [go-ataman](https://github.com/workanator/go-ataman) - **Star : 8** 在终端提供ANSI彩色文本模板。![最近三个月没有更新][Yellow]
* [go-colorable](https://github.com/mattn/go-colorable) - **Star : 368** 适用于windows的颜色编写器。![star > 100][Bronze]
* [go-colortext](https://github.com/daviddengcn/go-colortext) - **Star : 198** 在终端中使用彩色文字。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-isatty](https://github.com/mattn/go-isatty) - **Star : 333** Go 实现的 isatty。![star > 100][Bronze]
* [go-prompt](https://github.com/c-bata/go-prompt) - **Star : 2263** 构建一个强大的交互式提示，借鉴于[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit)![star > 1000][Silver]![最近一个周有更新][Green]
* [gocui](https://github.com/jroimartin/gocui) - **Star : 4410** 旨在创建控制台用户界面的极简Go库。![star > 1000][Silver]
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - 更换终端文本样式。
* [gookit/color](https://github.com/gookit/color) - **Star : 181** 终端显色工具库，支持16种颜色，256种颜色，RGB显色输出，兼容Windows。![star > 100][Bronze]
* [mpb](https://github.com/vbauerster/mpb) - **Star : 499** 可在终端显示多进度条。![star > 100][Bronze]
* [progressbar](https://github.com/schollz/progressbar) - **Star : 550** 基本线程安全的进度条，在每个操作系统工作。![star > 100][Bronze]![最近一个周有更新][Green]
* [simpletable](https://github.com/alexeyco/simpletable) - **Star : 154** 可在终端显示简易表格。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [tabby](https://github.com/cheynewallace/tabby) - **Star : 244** 一个可在终端生成一个极简Golang表格轻量级库![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [tabular](https://github.com/InVisionApp/tabular) - **Star : 29** 不需要向API传递大量参数就可从命令行实用程序中打印ASCII表。![最近三个月没有更新][Yellow]
* [termbox-go](https://github.com/nsf/termbox-go) - **Star : 3430** 基于文本的跨平台接口库。![star > 1000][Silver]
* [termdash](https://github.com/mum4k/termdash) - **Star : 773** 此库是基于**termbox-go**实现的，借鉴于[termui](https://github.com/gizak/termui)。![star > 100][Bronze]
* [termtables](https://github.com/apcera/termtables) - **Star : 212** 使用Ruby库[terminal-tables](https://github.com/tj/terminal-table)的端口生成简单的ASCII表，并提供标记和HTML输出。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [termui](https://github.com/gizak/termui) - **Star : 8787** 此库是基于**termbox-go**实现的，借鉴于[blessed-contrib](https://github.com/yaronn/blessed-contrib)。![star > 5000][Gold]![最近一个周有更新][Green]
* [uilive](https://github.com/gosuri/uilive) - **Star : 814** 用于实时更新终端输出的库。![star > 100][Bronze]
* [uiprogress](https://github.com/gosuri/uiprogress) - **Star : 1518** 在终端呈现进度条，可灵活配置的。![star > 1000][Silver]
* [uitable](https://github.com/gosuri/uitable) - **Star : 493** 改善终端应用程序中表格数据的可读性。![star > 100][Bronze]

## 配置

*配置解析的库。*

* [config](https://github.com/JeremyLoy/config) - **Star : 184** 云本地应用程序配置。将ENV绑定到结构体仅需两行代码。![star > 100][Bronze]
* [config](https://github.com/olebedev/config) - **Star : 209** 带有环境变量和标记解析的JSON或YAML配置包装器。![star > 100][Bronze]
* [configure](https://github.com/paked/configure) - **Star : 48** 通过多个源提供配置，包括JSON、flags和环境变量。![最近三个月没有更新][Yellow]
* [confita](https://github.com/heetch/confita) - **Star : 238** 从多个后端级联加载配置到struct中。![star > 100][Bronze]
* [conflate](https://github.com/the4thamigo-uk/conflate) - **Star : 8** 合并来自任意url的多个JSON/YAML/TOML文件、针对JSON模式的验证以及模式中定义的默认值的应用程序。
* [env](https://github.com/caarlos0/env) - **Star : 832** 解析环境变量并赋值到struct中(默认值)。![star > 100][Bronze]
* [envcfg](https://github.com/tomazk/envcfg) - **Star : 90** 对环境变量进行解析，并赋值到struct。![最近三个月没有更新][Yellow]
* [envconf](https://github.com/ian-kent/envconf) - **Star : 7** 从环境配置中读取配置。![最近三个月没有更新][Yellow]
* [envconfig](https://github.com/vrischmann/envconfig) - **Star : 143** 从环境变量中读取配置。![star > 100][Bronze]![最近一个周有更新][Green]
* [envh](https://github.com/antham/envh) - **Star : 94** 协助管理环境变量的Helpers。
* [gcfg](https://github.com/go-gcfg/gcfg) - **Star : 115** 将ini的配置文件读入 Go structs中;支持用户定义的类型和子选项。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-up](https://github.com/ufoscout/go-up) - **Star : 24** 一个简单的配置库，具有递归占位符解析功能。![最近三个月没有更新][Yellow]
* [goConfig](https://github.com/crgimenes/goConfig) - **Star : 102** 将结构体解析为输入，并用来自命令行、环境变量和配置文件的参数填充该结构体的字段。![star > 100][Bronze]
* [godotenv](https://github.com/joho/godotenv) - **Star : 2045** Ruby 的 dotenv 库的 Go移植版(从.env文件加载环境变量)。![star > 1000][Silver]
* [gofigure](https://github.com/ian-kent/gofigure) - **Star : 57** 让程序配置变得简单。![最近三个月没有更新][Yellow]
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - 模块化的JSON配置。保持配置结构及其配置的代码，并将解析委托给子模块，而不牺牲配置的完整序列化。
* [gookit/config](https://github.com/gookit/config) - **Star : 71** 程序配置管理(load,get,set)。支持JSON, YAML, TOML, INI, HCL。支持多文件加载，数据覆盖合并。![最近一个周有更新][Green]
* [harvester](https://github.com/beatlabs/harvester) - **Star : 19** 一个易于使用的静态和动态配置包![最近一个周有更新][Green]
* [hjson](https://github.com/hjson/hjson-go) - **Star : 171** 更加人性化的JSON配置。轻松的语法，更少的错误，更多的注释。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [ingo](https://github.com/schachmat/ingo) - **Star : 23** flag保存在类ini的配置文件中。![最近三个月没有更新][Yellow]
* [ini](https://github.com/go-ini/ini) - **Star : 1516**  读和写INI文件。![star > 1000][Silver]
* [joshbetz/config](https://github.com/joshbetz/config) - **Star : 195** 一个可解析环境变量、JSON文件小巧的配置库，在SIGHUP时会自动重新加载。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - **Star : 2338** 管理来自环境变量的配置数据。![star > 1000][Silver]
* [koanf](https://github.com/knadh/koanf) - **Star : 67** 轻量级可扩展库，用于读取Go应用程序中的配置。内置支持JSON, TOML, YAML, env，命令行。![最近一个周有更新][Green]
* [konfig](https://github.com/lalamove/konfig) - **Star : 507** 可组合、可观察和高性能的分布式配置管理。![star > 100][Bronze]
* [mini](https://github.com/sasbury/mini) - **Star : 19** 用于解析ini类型的配置文件。![最近三个月没有更新][Yellow]
* [sprbox](https://github.com/oblq/sprbox) - **Star : 3** 支持构建环境的工具箱工厂和其他不确定的配置解析器(如YAML、TOML、JSON和环境vars)。![最近三个月没有更新][Yellow]
* [store](https://github.com/tucnak/store) - **Star : 242** 轻量级配置管理器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [viper](https://github.com/spf13/viper) - **Star : 8943** 配置管理。![star > 5000][Gold]
* [xdg](https://github.com/OpenPeeDeeP/xdg) - **Star : 32** 遵循[XDG标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html)的跨平台包。![最近三个月没有更新][Yellow]

## 持续集成

*用于帮助进行持续集成的工具。*

* [drone](https://github.com/drone/drone) - **Star : 18666** Drone 是一个基于 Docker 的持续集成平台，用 Go 编写。![star > 5000][Gold]
* [duci](https://github.com/duck8823/duci) - **Star : 40** 一个简单的 ci 服务。
* [gomason](https://github.com/nikogura/gomason) - **Star : 27** 在一个干净的工作区中对你的 Go 二进制文件进行测试、构建、签名和发布。
* [goveralls](https://github.com/mattn/goveralls) - **Star : 570** Coveralls.io 是一个用 Go 编写，可持续对代码覆盖率进行检测的系统。![star > 100][Bronze]
* [overalls](https://github.com/go-playground/overalls) - **Star : 97** 针对多package 的 Go 语言项目，可为类似 goveralls 这样的工具生成覆盖率报告。![最近三个月没有更新][Yellow]
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - **Star : 12** 递归覆盖测试工具。![最近三个月没有更新][Yellow]

## CSS预处理器

*用于预处理CSS文件的库。*

* [gcss](https://github.com/yosssi/gcss) - **Star : 421** 纯Go编写的 CSS 预处理器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-libsass](https://github.com/wellington/go-libsass) - **Star : 128**  采用 Go封装，100% 与 Sass 兼容的 libsass 项目。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 数据结构

*用 Go 实现的通用的数据结构和算法。*

* [algorithms](https://github.com/shady831213/algorithms) - **Star : 228** 算法和数据结构。来源于CLRS。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [binpacker](https://github.com/zhuangsirui/binpacker) - **Star : 120** 帮助用户构建自定义二进制流的二进制封装器和解包器![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [bit](https://github.com/yourbasic/bit) - **Star : 51** Go 语言集合数据结构。提供了额外的位操作功能。![最近三个月没有更新][Yellow]
* [bitset](https://github.com/willf/bitset) - **Star : 476** 实现了 bitsets 的 Go 包。![star > 100][Bronze]
* [bloom](https://github.com/zhenjl/bloom) - **Star : 128** 在Go中实现了Bloom过滤器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [bloom](https://github.com/yourbasic/bloom) - **Star : 38** Golang Bloom过滤器的实现。![最近三个月没有更新][Yellow]
* [boomfilters](https://github.com/tylertreat/BoomFilters) - **Star : 1121** 用于处理连续的概率数据结构。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [concurrent-writer](https://github.com/free/concurrent-writer) - **Star : 22** 具备高并发能力，可替换 bufio.Writer。![最近三个月没有更新][Yellow]
* [conjungo](https://github.com/InVisionApp/conjungo) - **Star : 75** 一个小型、强大和灵活的合并库。
* [count-min-log](https://github.com/seiflotfy/count-min-log) - **Star : 43** Go实现Count-Min-log sketch的功能 : 使用近似计数器进行近似计数(类似Count-Min sketch，但使用更少内存)。![最近三个月没有更新][Yellow]
* [crunch](https://github.com/superwhiskers/crunch) - **Star : 19** 打包实现缓冲区，以便轻松处理各种数据类型。
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - **Star : 493** 布谷鸟过滤器:一个用Go实现，可替代计数 bloom 过滤器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [deque](https://github.com/edwingeng/deque) - **Star : 4** 高度优化的双端队列。![最近三个月没有更新][Yellow]
* [deque](https://github.com/gammazero/deque) - **Star : 58** 快速环缓冲区deque(双端队列)。
* [dict](https://github.com/srfrog/dict) - **Star : 7** 实现类似 python dict的功能(dict)。
* [encoding](https://github.com/zhenjl/encoding) - **Star : 94** 整形压缩库。![最近三个月没有更新][Yellow]
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - **Star : 83** 自适应基数树。
* [go-datastructures](https://github.com/Workiva/go-datastructures) - **Star : 5040** 可靠的、高性能的和线程安全的数据结构的集合。![star > 5000][Gold]![最近三个月没有更新][Yellow]
* [go-ef](https://github.com/amallia/go-ef) - **Star : 10** 实现了 Elias-Fano 编码。![最近三个月没有更新][Yellow]
* [go-geoindex](https://github.com/hailocab/go-geoindex) - **Star : 309** 基于内存的地理索引。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - **Star : 32** 基于内存的实现了高性能的key:value存储库。指针缓存。
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - **Star : 98** 区域四叉树具有高效的点定位和邻域查找功能。![最近三个月没有更新][Yellow]
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - **Star : 23** 并行FIFO队列。
* [gods](https://github.com/emirpasic/gods) - **Star : 6022** 数据结构。容器、集合、列表、堆栈、地图、BidiMaps、树、HashSet等。![star > 5000][Gold]
* [golang-set](https://github.com/deckarep/golang-set) - **Star : 1117** 线程安全和非线程安全的高性能集。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [goset](https://github.com/zoumo/goset) - **Star : 16** 一个有用的Go集合实现。![最近三个月没有更新][Yellow]
* [goskiplist](https://github.com/ryszard/goskiplist) - **Star : 191** 基于 Go 的跳表实现。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gota](https://github.com/kniren/gota) - **Star : 850** 实现了数据帧，序列以及数据噪音。![star > 100][Bronze]
* [hide](https://github.com/emvi/hide) - **Star : 7** ID type with marshalling to/from hash to prevent sending IDs to clients.![最近三个月没有更新][Yellow]
* [hilbert](https://github.com/google/hilbert) - **Star : 178** 用于映射空间填充曲线（例如 Hilbert 曲线和 Peano 曲线）和数值。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - **Star : 657** HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.![star > 100][Bronze]
* [levenshtein](https://github.com/agext/levenshtein) - **Star : 32** Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.![最近三个月没有更新][Yellow]
* [levenshtein](https://github.com/agnivade/levenshtein) - **Star : 53** 实现在Go中计算levenshtein距离。
* [mafsa](https://github.com/smartystreets/mafsa) - **Star : 272** 实现了 MA-FSA ，包含最小完美哈希。![star > 100][Bronze]
* [merkletree](https://github.com/cbergoon/merkletree) - **Star : 142** 实现了merkle树，提供了对数据结构内容的有效和安全的验证。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [mspm](https://github.com/BlackRabbitt/mspm) - **Star : 7** 用于信息检索的多字符串模式匹配算法。![最近三个月没有更新][Yellow]
* [null](https://github.com/emvi/null) - **Star : 5** 对空的 Go 数据类型也可以进行JSON进行解析/反解析。
* [parsefields](https://github.com/MonaxGT/parsefields) - **Star : 3** 用于解析类似json的日志的工具，用于收集惟一的字段和事件。
* [pipeline](https://github.com/hyfather/pipeline) - **Star : 15** 实现了 fan-in 和 fan-out 的管道功能。![最近三个月没有更新][Yellow]
* [ring](https://github.com/TheTannerRyan/ring) - **Star : 86** 高性能、线程安全的bloom过滤器。
* [roaring](https://github.com/RoaringBitmap/roaring) - **Star : 642** 实现了压缩 bitsets 的Go包。![star > 100][Bronze]
* [set](https://github.com/StudioSol/set) - **Star : 6** 使用LinkedHashMap在Go中实现简单的set数据结构。![最近三个月没有更新][Yellow]
* [skiplist](https://github.com/MauriceGit/skiplist) - **Star : 96** 高性能的 Go 跳表实现。![最近三个月没有更新][Yellow]
* [skiplist](https://github.com/gansidui/skiplist) - **Star : 62** 在Go中实现了跳表。![最近三个月没有更新][Yellow]
* [timedmap](https://github.com/zekroTJA/timedmap) - **Star : 1** 实现了有生命周期的键值对Map。![最近三个月没有更新][Yellow]
* [treap](https://github.com/perdata/treap) - **Star : 7** 使用树堆进行持久、快速有序的映射。![最近三个月没有更新][Yellow]
* [trie](https://github.com/derekparker/trie) - **Star : 408** 在Go中实现Trie。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [ttlcache](https://github.com/diegobernardes/ttlcache) - **Star : 91** 基于内存的LRU算法实现。
* [typ](https://github.com/gurukami/typ) - **Star : 9** 从复杂结构中获取值，支持空类型、安全的类型转换。
* [willf/bloom](https://github.com/willf/bloom) - **Star : 646** 实现Bloom过滤器。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 数据库

*数据库。*

* [badger](https://github.com/dgraph-io/badger) - **Star : 6083** 快速 K/V 存储。![star > 5000][Gold]![最近一个周有更新][Green]
* [bcache](https://github.com/iwanbk/bcache) - **Star : 25** 基于内存的最终一致的分布式缓存。
* [BigCache](https://github.com/allegro/bigcache) - **Star : 2379** 高效的键/值缓存为千兆字节的数据。![star > 1000][Silver]![最近一个周有更新][Green]
* [bolt](https://github.com/boltdb/bolt) - **Star : 9859** K/V 数据库。![star > 5000][Gold]![最近三个月没有更新][Yellow]
* [buntdb](https://github.com/tidwall/buntdb) - **Star : 2417** 基于内存的K/V，快速，可嵌入的数据库，可自定义索引和空间支持。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [cache](https://github.com/akyoto/cache) - **Star : 10** 基于内存的 K/V 存储:带生命周期的值存储，0个依赖项，<100 LoC, 100%覆盖率。
* [cache2go](https://github.com/muesli/cache2go) - **Star : 926** 基于内存的 K/V 缓存，支持超时的自动失效。![star > 100][Bronze]
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - **Star : 29** BigCache 支持集群和独立且生命周期存储项。![最近三个月没有更新][Yellow]
* [cockroach](https://github.com/cockroachdb/cockroach) - **Star : 16545** 可伸缩、区域备份、事务性数据存储。![star > 5000][Gold]![最近一个周有更新][Green]
* [couchcache](https://github.com/codingsince1985/couchcache) - **Star : 40** 由 Couchbase服务 支持的RESTful缓存微服务。
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - **Star : 1421** 区块链领域的一个SQL数据库。![star > 1000][Silver]![最近一个周有更新][Green]
* [dgraph](https://github.com/dgraph-io/dgraph) - **Star : 9885** 可伸缩、分布式、低延迟、高吞吐量的图形数据库。![star > 5000][Gold]![最近一个周有更新][Green]
* [diskv](https://github.com/peterbourgon/diskv) - **Star : 736** 支持磁盘备份的可持久化 K/V 存储。![star > 100][Bronze]
* [eliasdb](https://github.com/krotik/eliasdb) - **Star : 531** 无其他依赖项，支持REST API，短语搜索和sql类似的查询语言的事务图数据库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [fastcache](https://github.com/VictoriaMetrics/fastcache) - **Star : 467** 基于内存的快速线程安全的缓存，可缓存大量的条目。最大限度地减少GC开销。![star > 100][Bronze]
* [GCache](https://github.com/bluele/gcache) - **Star : 861** 支持过期缓存、LFU、LRU和ARC的缓存库。![star > 100][Bronze]
* [go-cache](https://github.com/pmylund/go-cache) - **Star : 2785** 基于内存的 K/V 存储/缓存 : (类似于Memcached)，适用于单机应用程序。![star > 1000][Silver]
* [goleveldb](https://github.com/syndtr/goleveldb) - **Star : 3095** 在Go中实现[LevelDB](https://github.com/google/leveldb) key/value数据库。![star > 1000][Silver]
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - **Star : 7** 用 Go 对[RocksDB](https://rocksdb.org)实现了封装。![最近三个月没有更新][Yellow]
* [groupcache](https://github.com/golang/groupcache) - **Star : 7538** Groupcache是一个缓存和缓存填充库，在许多情况下，它是memcached的替代品。![star > 5000][Gold]![最近三个月没有更新][Yellow]
* [influxdb](https://github.com/influxdb/influxdb) - **Star : 16679** 可伸缩的数据存储，用于指标衡量、事件和实时分析。![star > 5000][Gold]![最近一个周有更新][Green]
* [ledisdb](https://github.com/siddontang/ledisdb) - **Star : 3037** Ledisdb是一种高性能的NoSQL，类似于基于LevelDB的Redis。![star > 1000][Silver]
* [levigo](https://github.com/jmhodges/levigo) - **Star : 363** 实现了对LevelDB封装。![star > 100][Bronze]
* [moss](https://github.com/couchbase/moss) - **Star : 714** Moss是一个用100% Go编写的简单LSM键值存储引擎。![star > 100][Bronze]
* [nutsdb](https://github.com/xujiajun/nutsdb) - **Star : 843** Nutsdb是一个用纯Go编写的简单、快速、可嵌入、持久的键/值存储。它支持完全序列化的事务和许多数据结构，如列表、集合、排序集。![star > 100][Bronze]
* [piladb](https://github.com/fern4lvarez/piladb) - **Star : 170** 基于堆栈数据结构的轻量级RESTful数据库引擎。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [prometheus](https://github.com/prometheus/prometheus) - **Star : 24851** 用于监控系统和时序的数据库。![star > 5000][Gold]![最近一个周有更新][Green]
* [pudge](https://github.com/recoilme/pudge) - **Star : 213** 使用Go的标准库编写的快速和简单的键/值存储。![star > 100][Bronze]
* [rqlite](https://github.com/rqlite/rqlite) - **Star : 4631** 基于SQLite的轻量级分布式关系数据库。![star > 1000][Silver]
* [Scribble](https://github.com/nanobox-io/golang-scribble) - **Star : 55** 小型平面文件JSON存储。![最近三个月没有更新][Yellow]
* [slowpoke](https://github.com/recoilme/slowpoke) - **Star : 84** 具有持久性的键值存储。![最近三个月没有更新][Yellow]
* [tempdb](https://github.com/rafaeljesus/tempdb) - **Star : 13** 用于临时数据存放的 K/V 存储。![最近三个月没有更新][Yellow]
* [tidb](https://github.com/pingcap/tidb) - **Star : 19467** TiDB是一个分布式SQL数据库。灵感来自谷歌F1的设计。![star > 5000][Gold]![最近一个周有更新][Green]
* [tiedot](https://github.com/HouzuoGuo/tiedot) - **Star : 2353** 属于你的NoSQL数据库。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [Vasto](https://github.com/chrislusf/vasto) - **Star : 142** 分布式高性能键值存储。可做磁盘备份。最终一致。高可用。能够在不中断服务的情况下增长或收缩。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - **Star : 862** 开源，快速，可伸缩的时间序列数据库。支持PromQL。![star > 100][Bronze]![最近一个周有更新][Green]

*数据库迁移。*

* [avro](https://github.com/khezen/avro) - **Star : 3** 发现SQL schemas并将其转换为AVRO schemas。
* [darwin](https://github.com/GuiaBolso/darwin) - **Star : 84** 用于数据库 schema 升级的库。![最近三个月没有更新][Yellow]
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - **Star : 19** 类似 Django fixture，用于 Go 建立内置数据库/sql库。![最近三个月没有更新][Yellow]
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - **Star : 24** 用Go -pg/pg编写的迁移包。![最近三个月没有更新][Yellow]
* [gondolier](https://github.com/emvi/gondolier) - **Star : 26** 使用结构修饰的数据库迁移库。
* [goose](https://github.com/steinbacher/goose) - **Star : 117** 数据库迁移工具。您可以通过创建增量SQL或Go脚本来管理数据库的升级。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - **Star : 316** 面向Gorm ORM的数据库 schema 迁移辅助程序。![star > 100][Bronze]
* [migrate](https://github.com/golang-migrate/migrate) - **Star : 2412** 基于CLI的数据库迁移库。![star > 1000][Silver]![最近一个周有更新][Green]
* [migrator](https://github.com/lopezator/migrator) - **Star : 26** 非常简单的 Go 数据库迁移库。
* [pravasan](https://github.com/pravasan/pravasan) - **Star : 24** 简易的迁移工具-目前只支持MySQL，但计划很快支持Postgres, SQLite, MongoDB等。![最近三个月没有更新][Yellow]
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) - 数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。
* [sql-migrate](https://github.com/rubenv/sql-migrate) - **Star : 1369** 数据库迁移工具。允许使用go-bindata将迁移嵌入到应用程序中。![star > 1000][Silver]

*数据库工具。*

* [chproxy](https://github.com/Vertamedia/chproxy) - **Star : 293** ClickHouse数据库的HTTP代理。![star > 100][Bronze]
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - **Star : 127** 收集小的 insterts 并向 ClickHouse 服务器发送大请求。![star > 100][Bronze]
* [datagen](https://github.com/codingconcepts/datagen) - **Star : 5** 一个快速的数据生成器，支持多表感知和多行DML。
* [dbbench](https://github.com/sj14/dbbench) - **Star : 30** 数据库基准测试工具，支持多个数据库和脚本。![最近三个月没有更新][Yellow]
* [go-mysql](https://github.com/siddontang/go-mysql) - **Star : 1799**  Go 工具集，用于处理MySQL协议和复制。![star > 1000][Silver]![最近一个周有更新][Green]
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - **Star : 2281** 自动将MySQL数据同步到Elasticsearch中。![star > 1000][Silver]
* [kingshard](https://github.com/flike/kingshard) - **Star : 4523** kingshard 是基于 Golang 的MySQL高性能代理。![star > 1000][Silver]
* [myreplication](https://github.com/2tvenom/myreplication) - **Star : 141** MySql二进制日志复制监听器。支持基于语句和行的复制。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [octillery](https://github.com/knocknote/octillery) - **Star : 46** 用于数据库分表(支持每个ORM或原生SQL)。
* [orchestrator](https://github.com/github/orchestrator) - **Star : 2944** MySQL复制拓扑管理器和可视化工具。![star > 1000][Silver]![最近一个周有更新][Green]
* [pgweb](https://github.com/sosedoff/pgweb) - **Star : 5936** 基于web的PostgreSQL数据库浏览器。![star > 5000][Gold]![最近三个月没有更新][Yellow]
* [prep](https://github.com/hexdigest/prep) - **Star : 24** 在不更改代码的情况下使用准备好的SQL语句。![最近三个月没有更新][Yellow]
* [pREST](https://github.com/nuveo/prest) - **Star : 2053** 基于PostgreSQL database的RESTful API服务。![star > 1000][Silver]
* [rwdb](https://github.com/andizzle/rwdb) - **Star : 10** rwdb为多个数据库服务器的设置提供读取副本功能。![最近三个月没有更新][Yellow]
* [vitess](https://github.com/youtube/vitess) - **Star : 8265** vitess提供了可以为大规模web服务扩展MySQL数据库提供便利的服务和工具。![star > 5000][Gold]![最近一个周有更新][Green]

*SQL查询生成器，用于构建和使用SQL的库。*

* [Dotsql](https://github.com/gchaincl/dotsql) - **Star : 433** Go library帮助您将sql文件保存在一个地方，并轻松地使用它们。![star > 100][Bronze]
* [gendry](https://github.com/didi/gendry) - **Star : 695** 非入侵的SQL构建器和强大的数据绑定器。![star > 100][Bronze]
* [godbal](https://github.com/xujiajun/godbal) - **Star : 50** 数据库抽象层(dbal)。支持SQL builder，轻松获取结果。![最近三个月没有更新][Yellow]
* [goqu](https://github.com/doug-martin/goqu) - **Star : 520** 常用的SQL生成器和查询库。![star > 100][Bronze]
* [igor](https://github.com/galeone/igor) - **Star : 77** PostgreSQL的抽象层，支持高级功能和类似gorm的语法。![最近三个月没有更新][Yellow]
* [ormlite](https://github.com/pupizoid/ormlite) - 包含一些类似orm的特性和sqlite数据库的辅助程序的轻量级包
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - **Star : 434** Powerful data retrieval methods as well as DB-agnostic query building capabilities.![star > 100][Bronze]
* [scaneo](https://github.com/variadico/scaneo) - **Star : 149** 生成用于将数据库行转换为任意结构体的 Go 代码。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [sqrl](https://github.com/elgris/sqrl) - **Star : 172** SQL查询生成器，从Squirrel fork而来，并再此基础上对性能做了优化。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Squalus](https://gitlab.com/qosenergy/squalus) - Go SQL中间层，能使得执行查询更加容易。
* [Squirrel](https://github.com/Masterminds/squirrel) - **Star : 2189** 帮助您构建SQL查询的Go库。![star > 1000][Silver]
* [xo](https://github.com/knq/xo) - **Star : 2113** 基于现有的schema定义和自定义查询生成 Go 代码，基于支持PostgreSQL、MySQL、SQLite、Oracle和Microsoft SQL Server。![star > 1000][Silver]![最近一个周有更新][Green]

## 数据库驱动程序

*用于连接和操作数据库的库。*

* Relational Databases
    * [avatica](https://github.com/apache/calcite-avatica-go) - **Star : 31** Apache Avatica/Phoenix SQL驱动程序。
    * [bgc](https://github.com/viant/bgc) - **Star : 12** BigQuery 的数据存储连接。
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - **Star : 102** Firebird RDBMS SQL驱动程序。![star > 100][Bronze]
    * [go-adodb](https://github.com/mattn/go-adodb) - **Star : 90** Microsoft ActiveX对象数据库驱动程序。
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - **Star : 991** 微软MSSQL驱动程序。![star > 100][Bronze]
    * [go-oci8](https://github.com/mattn/go-oci8) - **Star : 397** Oracle 驱动程序。![star > 100][Bronze]
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - **Star : 7851** MySQL驱动程序。![star > 5000][Gold]![最近一个周有更新][Green]
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - **Star : 3346** SQLite3驱动程序。![star > 1000][Silver]
    * [gofreetds](https://github.com/minus5/gofreetds) - **Star : 90** 基于[FreeTDS](http://www.freetds.org)封装的微软MSSQL Go 驱动。![最近三个月没有更新][Yellow]
    * [goracle](https://github.com/go-goracle/goracle) - **Star : 226** 基于 ODPI-C 的 Oracle 驱动程序![star > 100][Bronze]![最近一个周有更新][Green]
    * [pgx](https://github.com/jackc/pgx) - **Star : 1853** PostgreSQL驱动，支持比现有database/sql更多的特性。![star > 1000][Silver]![最近一个周有更新][Green]
    * [pq](https://github.com/lib/pq) - **Star : 5061** 纯 Go 的Postgres驱动。![star > 5000][Gold]

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - **Star : 301** Aerospike 客户端。![star > 100][Bronze]
    * [arangolite](https://github.com/solher/arangolite) - **Star : 65** 轻量级的 ArangoDB 驱动。
    * [asc](https://github.com/viant/asc) - **Star : 4** Aerospike 的数据存储连接器。
    * [dynago](https://github.com/underarmour/dynago) - **Star : 65** 满足 principle of least surprise 的 DynamoDB 客户端。![最近三个月没有更新][Yellow]
    * [forestdb](https://github.com/couchbase/goforestdb) - **Star : 30** 基于 Go 的 ForestDB 接口实现。![最近三个月没有更新][Yellow]
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - **Star : 291** Couchbase客户端。![star > 100][Bronze]![最近一个周有更新][Green]
    * [go-couchdb](https://github.com/fjl/go-couchdb) - **Star : 52** 基于 Go 的 Yet another CouchDB 的 Http 接口封装。![最近三个月没有更新][Yellow]
    * [go-pilosa](https://github.com/pilosa/go-pilosa) - **Star : 32**  Pilosa客户端。
    * [go-rejson](https://github.com/nitishm/go-rejson) - **Star : 81** 实现了基于 Redigo 客户端的redislabs' ReJSON 模块。可简单地将结构体存储为JSON对象并对其进行操作。
    * [gocb](https://github.com/couchbase/gocb) - **Star : 289** 官方Couchbase Go SDK。![star > 100][Bronze]![最近一个周有更新][Green]
    * [gocql](http://gocql.github.io) - Apache Cassandra 的 Go 驱动。
    * [godscache](https://github.com/defcronyke/godscache) - **Star : 6** 谷歌云平台Go Datastore包的封装，它采用了memcached添加缓存。![最近三个月没有更新][Yellow]
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache客户端库。
    * [gorethink](https://github.com/dancannon/gorethink) - **Star : 1456** RethinkDB 驱动。![star > 1000][Silver]
    * [goriak](https://github.com/zegl/goriak) - **Star : 24**  Riak KV 驱动。![最近三个月没有更新][Yellow]
    * [mgo](https://github.com/globalsign/mgo) - **Star : 1596** (已停止维护) MongoDB驱动。![star > 1000][Silver]
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - **Star : 2879** 官方的 MongoDB 驱动。![star > 1000][Silver]![最近一个周有更新][Green]
    * [neo4j](https://github.com/cihangir/neo4j) - **Star : 24** Neo4j Rest API实现。![最近三个月没有更新][Yellow]
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - **Star : 72** Neo4j REST 客户端。![最近三个月没有更新][Yellow]
    * [neoism](https://github.com/jmcvetta/neoism) - **Star : 355** Golang 的 Neo4j 客户端。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [redeo](https://github.com/bsm/redeo) - **Star : 257** 与 redis 协议兼容的 TCP 服务器/服务。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [redigo](https://github.com/gomodule/redigo) - **Star : 6111** Redigo 是基于 Go 的Redis 客户端。![star > 5000][Gold]
    * [redis](https://github.com/go-redis/redis) - **Star : 6154** 基于 Go 的 Redis 客户端。![star > 5000][Gold]![最近一个周有更新][Green]
    * [xredis](https://github.com/shomali11/xredis) - **Star : 9** 类型安全，可定制，清晰和易用的Redis客户端。

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - **Star : 5740** 基于 Go 的现代文本索引库。![star > 5000][Gold]![最近一个周有更新][Green]
    * [elastic](https://github.com/olivere/elastic) - **Star : 3990** Elasticsearch 客户端。![star > 1000][Silver]![最近一个周有更新][Green]
    * [elasticsql](https://github.com/cch123/elasticsql) - **Star : 367** 将 SQL 转换为 elasticsearch dsl。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [elastigo](https://github.com/mattbaird/elastigo) - **Star : 948** Elasticsearch 客户端。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - **Star : 1456** 官方 Elasticsearch 客户端。![star > 1000][Silver]![最近一个周有更新][Green]
    * [goes](https://github.com/OwnLocal/goes) - **Star : 24** 实现了与 Elasticsearch 交互的库。![最近三个月没有更新][Yellow]
    * [riot](https://github.com/go-ego/riot) - **Star : 4621** 基于 Go 的 开源、分布式、简单高效的搜索引擎。![star > 1000][Silver]
    * [skizze](https://github.com/seiflotfy/skizze) - **Star : 68** 面向概率数据结构的服务和存储。![最近三个月没有更新][Yellow]

* Multiple Backends.
    * [cachego](https://github.com/fabiorphp/cachego) - **Star : 109** 基于多个驱动程序的缓存组件。![star > 100][Bronze]
    * [cayley](https://github.com/google/cayley) - **Star : 12595** 图形数据库，支持多个后端。![star > 5000][Gold]![最近一个周有更新][Green]
    * [dsc](https://github.com/viant/dsc) - **Star : 12** 面向 SQL、NoSQL、结构化文件的数据存储连接。
    * [gokv](https://github.com/philippgille/gokv) - **Star : 74** 可扩展的简单的 K/V 存储(Redis、、etcd、bbolt、BadgerDB、LevelDB、Memcached、DynamoDB、S3、PostgreSQL、MongoDB、CockroachDB等等)。

## 日期和时间

*用于处理日期和时间的库。*

* [carbon](https://github.com/uniplaces/carbon) - **Star : 330** 简单的时间扩展，包含了许多使用方法，从 PHP Carbon 库移植的。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [date](https://github.com/rickb777/date) - **Star : 27** 增加处理日期、日期范围、时间跨度、时间段和time-of-day。
* [dateparse](https://github.com/araddon/dateparse) - **Star : 875** 可以解析很多格式不固定的日期字符串。![star > 100][Bronze]
* [durafmt](https://github.com/hako/durafmt) - **Star : 235** 轻量级、可让time.Duration更加易读的库。![star > 100][Bronze]
* [feiertage](https://github.com/wlbr/feiertage) - **Star : 21** 用于计算德国公共假期的函数，比如复活节、感恩节等
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - **Star : 58** 太阳历实现。![最近三个月没有更新][Yellow]
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - **Star : 13** 计算指定位置的日出和日落时间。![最近三个月没有更新][Yellow]
* [goweek](https://github.com/grsmv/goweek) - **Star : 18** 用于处理以星期实体单位的库。![最近三个月没有更新][Yellow]
* [iso8601](https://github.com/relvacode/iso8601) - **Star : 67** 不用正则表达式有效解析 ISO8601 日期时间。![最近三个月没有更新][Yellow]
* [kair](https://github.com/GuilhermeCaruso/kair) - **Star : 9** 用于处理日期和时间的 golang 库。![最近三个月没有更新][Yellow]
* [now](https://github.com/jinzhu/now) - **Star : 2126** now 是时间有关的工具类。![star > 1000][Silver]
* [NullTime](https://github.com/kirillDanshin/nulltime) - **Star : 9** 可以允许 time.Time 为null。![最近三个月没有更新][Yellow]
* [strftime](https://github.com/awoodbeck/strftime) - **Star : 5** C99-compatible strftime formatter。![最近三个月没有更新][Yellow]
* [timespan](https://github.com/SaidinWoT/timespan) - **Star : 60** 用于处理时间间隔相关的库，可定义开始时间和持续时间。![最近三个月没有更新][Yellow]
* [timeutil](https://github.com/leekchan/timeutil) - **Star : 168** 面向 Golang 的时间库，集成了很多有用的扩展(Timedelta, Strftime, ...)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [tuesday](https://github.com/osteele/tuesday) - **Star : 7** Ruby-compatible Strftime function。![最近三个月没有更新][Yellow]

## 分布式系统

*协助构建分布式系统的包。*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - **Star : 52** 用于对 Celery worker、任务、事件进行交互和监控的库。![最近三个月没有更新][Yellow]
* [consistent](https://github.com/buraksezer/consistent) - **Star : 181** Consistent hashing with bounded loads。![star > 100][Bronze]
* [dht](https://github.com/anacrolix/dht) - **Star : 121** BitTorrent Kademlia DHT的实现。![star > 100][Bronze]
* [digota](https://github.com/digota/digota) - **Star : 296** 基于 grpc 的电子商务微服务。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [dot](https://github.com/dotchain/dot/) - 基于 transformation/OT 的分布式同步。
* [doublejump](https://github.com/edwingeng/doublejump) - **Star : 37** 实现了谷歌的jump consistent hash。![最近三个月没有更新][Yellow]
* [dragonboat](https://github.com/lni/dragonboat) - **Star : 2434** 一个功能齐全，高性能的库集。![star > 1000][Silver]![最近一个周有更新][Green]
* [drmaa](https://github.com/dgruber/drmaa) - **Star : 24** 符合 DRMAA 标准的集群调度程序作业提交库。![最近三个月没有更新][Yellow]
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed 分布式锁定实现。
* [dynatomic](https://github.com/tylfin/dynatomic) - **Star : 8** 基于 DynamoDB 的 原子计数器的库。![最近三个月没有更新][Yellow]
* [emitter-io](https://github.com/emitter-io/emitter) - **Star : 1869** 高性能、分布式、安全和低延迟的发布-订阅平台，使用MQTT、Websockets和love构建。![star > 1000][Silver]![最近一个周有更新][Green]
* [flowgraph](https://github.com/vectaport/flowgraph) - **Star : 17** flow-based programming package。
* [gleam](https://github.com/chrislusf/gleam) - **Star : 2037** 使用纯Go和Luajit编写的快速、可伸缩的分布式map/reduce系统，结合了Go的高并发性和Luajit的高性能，可以独立运行或分布式运行。![star > 1000][Silver]![最近一个周有更新][Green]
* [glow](https://github.com/chrislusf/glow) - **Star : 2492** 全部用 Go 实现，易用、可伸缩，可用于分布式大数据处理，Map-Reduce, DAG执行。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [go-health](https://github.com/InVisionApp/go-health) - **Star : 474** 用于在服务中启用异步依赖项健康检查的库。![star > 100][Bronze]![最近一个周有更新][Green]
* [go-jump](https://github.com/dgryski/go-jump) - **Star : 251** 提供了谷歌的 “Jump” 一致哈希函数接口。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-kit](https://github.com/go-kit/kit) - **Star : 14082** 支持服务发现、负载平衡、插件式传输、请求跟踪等功能的Microservice toolkit。![star > 5000][Gold]![最近一个周有更新][Green]
* [gorpc](https://github.com/valyala/gorpc) - **Star : 546** 简单、快速和可伸缩的RPC库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [grpc-go](https://github.com/grpc/grpc-go) - **Star : 8715** gRPC的Go语言实现。![star > 5000][Gold]![最近一个周有更新][Green]
* [hprose](https://github.com/hprose/hprose-golang) - **Star : 990** 支持25+种语言RPC库。![star > 100][Bronze]![最近一个周有更新][Green]
* [jaeger](https://github.com/jaegertracing/jaeger) - **Star : 8371** 分布式跟踪系统。![star > 5000][Gold]![最近一个周有更新][Green]
* [jsonrpc](https://github.com/osamingo/jsonrpc) - **Star : 113** jsonrpc 包，实现了 JSON-RPC 2.0。![star > 100][Bronze]
* [jsonrpc](https://github.com/ybbus/jsonrpc) - **Star : 95** JSON-RPC 2.0 HTTP客户端。
* [KrakenD](https://github.com/devopsfaith/krakend) - **Star : 1625** 具有中间件的高性能API网关框架。![star > 1000][Silver]
* [micro](https://github.com/micro/micro) - **Star : 6405** 可插拔的微服务 toolkit 和分布式系统平台。![star > 5000][Gold]![最近一个周有更新][Green]
* [NATS](https://github.com/nats-io/gnatsd) - **Star : 5906** 轻量级、高性能消息传递系统，可用于微服务、物联网(IoT)和云。![star > 5000][Gold]![最近一个周有更新][Green]
* [outboxer](https://github.com/italolelis/outboxer) - **Star : 1** 实现了 outbox pattern Go 库。![最近三个月没有更新][Yellow]
* [pglock](https://cirello.io/pglock) - postgresql 的分布式锁定实现。
* [raft](https://github.com/hashicorp/raft) - **Star : 2767** Raft consensus协议的实现。 by HashiCorp。![star > 1000][Silver]![最近一个周有更新][Green]
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Raft consensus协议的实现。 by CoreOS。
* [redis-lock](https://github.com/bsm/redis-lock) - **Star : 145** 基于redis的分布式锁简易实现。![star > 100][Bronze]
* [resgate](https://resgate.io/) - 用于构建REST、实时和RPC API的实时API网关，其中所有客户端都是无缝同步的。
* [ringpop-go](https://github.com/uber/ringpop-go) - **Star : 563** 可伸缩的，容错、应用分层的的Go应用程序。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [rpcx](https://github.com/smallnest/rpcx) - **Star : 3664** 分布式可插拔的RPC服务框架，如阿里巴巴Dubbo。![star > 1000][Silver]![最近一个周有更新][Green]
* [sleuth](https://github.com/ursiform/sleuth) - **Star : 298** 用于HTTP服务之间进行无中心p2p自动发现和RPC通信的库(使用[ZeroMQ](https://github.com/zeromq/libzmq))。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [tendermint](https://github.com/tendermint/tendermint) - **Star : 3057** 一个高性能中间件，可将任何语言的状态机转换为 Byzantine Fault 状态机。使用 Tendermint 一致性及区块链协议。![star > 1000][Silver]![最近一个周有更新][Green]
* [torrent](https://github.com/anacrolix/torrent) - **Star : 2763** BitTorrent 客户端。![star > 1000][Silver]

## 电子邮件

*实现了电子邮件创建和发送。*

* [chasquid](https://blitiri.com.ar/p/chasquid) - 用Go编写的SMTP服务器。
* [douceur](https://github.com/aymerick/douceur) - **Star : 157** 在HTML邮件中支持CSS内联。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [email](https://github.com/jordan-wright/email) - **Star : 1073** 一个强大和灵活的电子邮件库。![star > 1000][Silver]
* [go-dkim](https://github.com/toorop/go-dkim) - **Star : 46** DKIM库，用于签署 & 验证电子邮件。
* [go-imap](https://github.com/emersion/go-imap) - **Star : 703** 用于客户端和服务器的IMAP库。![star > 100][Bronze]![最近一个周有更新][Green]
* [go-message](https://github.com/emersion/go-message) - **Star : 101** 用于Internet消息格式化和邮件消息的流媒体库。![star > 100][Bronze]
* [go-premailer](https://github.com/vanng822/go-premailer) - **Star : 34** 在HTML邮件中支持CSS内联。
* [Gomail](https://github.com/go-gomail/gomail/) - 一个非常简单和强大的邮件发送库。
* [Hectane](https://github.com/hectane/hectane) - **Star : 168** 轻量级的SMTP客户机，提供了HTTP API。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [hermes](https://github.com/matcornic/hermes) - **Star : 1591** 可生成干净的、响应式的HTML电子邮件。![star > 1000][Silver]
* [MailHog](https://github.com/mailhog/MailHog) - **Star : 5016** 电子邮件和SMTP测试工具，对外提供了 web 和 API 接口。![star > 5000][Gold]
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - **Star : 513** SendGrid 的 Go语言库，用于发送电子邮件。![star > 100][Bronze]
* [smtp](https://github.com/mailhog/smtp) - **Star : 49** SMTP服务器协议状态机。![最近三个月没有更新][Yellow]

## 可嵌入的脚本语言

*在go代码中嵌入其他语言。*

* [agora](https://github.com/PuerkitoBio/agora) - **Star : 322** 基于 Go 的动态类型，可嵌入的编程语言。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [anko](https://github.com/mattn/anko) - **Star : 901** 用Go编写的解释器。![star > 100][Bronze]![最近一个周有更新][Green]
* [binder](https://github.com/alexeyco/binder) - **Star : 29** Lua接口，基于[gopher-lua](https://github.com/yuin/gopher-lua)。![最近三个月没有更新][Yellow]
* [expr](https://github.com/antonmedv/expr) - **Star : 556** 一个可以计算表达式的引擎。![star > 100][Bronze]![最近一个周有更新][Green]
* [gentee](https://github.com/gentee/gentee) - **Star : 24** 嵌入式脚本编程语言。![最近一个周有更新][Green]
* [gisp](https://github.com/jcla1/gisp) - **Star : 428** LISP 的 Go 接口。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-duktape](https://github.com/olebedev/go-duktape) - **Star : 647** 支持 Duktape JavaScript 引擎。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-lua](https://github.com/Shopify/go-lua) - **Star : 1637** 用 Go 实现的 Lua 5.2 VM接口。![star > 1000][Silver]
* [go-php](https://github.com/deuill/go-php) - **Star : 669** PHP 的 Go 接口。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-python](https://github.com/sbinet/go-python) - **Star : 889** CPython C-API 的 Go 接口。![star > 100][Bronze]
* [golua](https://github.com/aarzilli/golua) - **Star : 434** Lua C 的 Go 接口。![star > 100][Bronze]
* [gopher-lua](https://github.com/yuin/gopher-lua) - **Star : 2903** 用 Go 实现的 Lua 5.1 虚拟机和编译器。![star > 1000][Silver]
* [gval](https://github.com/PaesslerAG/gval) - **Star : 131** 一种用Go编写的高度可定制的表达式语言。![star > 100][Bronze]
* [ngaro](https://github.com/db47h/ngaro) - **Star : 18** 嵌入式 Ngaro VM实现，支持在 Retro 中运行脚本。![最近三个月没有更新][Yellow]
* [otto](https://github.com/robertkrimen/otto) - **Star : 4648** 用 Go 编写的 JavaScript 解释器。![star > 1000][Silver]
* [purl](https://github.com/ian-kent/purl) - **Star : 27** 嵌入 Go 的 Perl 5.18.2。![最近三个月没有更新][Yellow]
* [tengo](https://github.com/d5/tengo) - **Star : 1264** 字节码编译的脚本语言。![star > 1000][Silver]

## 错误处理

*处理错误的库。*

* [errlog](https://github.com/snwfdhmp/errlog) - **Star : 142** 用于定位抛出错误的源代码(以及一些其他快速调试特性)。可插入到任何 logger 的位置。![star > 100][Bronze]
* [errors](https://github.com/pkg/errors) - **Star : 4688** 可让你很简单的进行错误处理。![star > 1000][Silver]
* [errorx](https://github.com/joomcode/errorx) - **Star : 546** 一个功能丰富的错误包，可进行堆栈跟踪、组装异常信息以及其他。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-multierror](https://github.com/hashicorp/go-multierror) - **Star : 703** 可将一系列的错误作为一个整体来显示。![star > 100][Bronze]
* [tracerr](https://github.com/ztrue/tracerr) - **Star : 485** 可展示错误的堆栈跟踪信息和源码片段。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [werr](https://github.com/txgruppi/werr) - **Star : 10** 对错误异常进行了捕获封装，封装信息包含了调用它的文件、行和堆栈。![最近三个月没有更新][Yellow]

## 文件

*处理文件和文件系统的库。*

* [afero](https://github.com/spf13/afero) - **Star : 2169** 文件系统的抽象系统。![star > 1000][Silver]
* [checksum](https://github.com/codingsince1985/checksum) - **Star : 6** 生成大型文件的消息摘要(如 MD5 和 SHA256)。
* [flop](https://github.com/homedepot/flop) - **Star : 8** 文件操作库，是[GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp- invoc.html)的镜像。
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - **Star : 44** 使用 tag 加载 csv 文件。![最近三个月没有更新][Yellow]
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - **Star : 11** 拷贝文件。![最近三个月没有更新][Yellow]
* [go-exiftool](https://github.com/barasher/go-exiftool) - ExifTool 的 Go 实现，这个著名的库用于从文件(图片、PDF、office，…)中提取尽可能多的元数据(EXIF、IPTC，…)。
* [go-gtfs](https://github.com/artonge/go-gtfs) - **Star : 15** 加载gtfs文件。![最近三个月没有更新][Yellow]
* [notify](https://github.com/rjeczalik/notify) - **Star : 483** 文件系统事件通知库，具有类似于os/signal的简单API，。![star > 100][Bronze]
* [opc](https://github.com/qmuntal/opc) - **Star : 57** 加载Open Packaging Conventions (OPC)文件。
* [pdfcpu](https://github.com/hhrutter/pdfcpu) - **Star : 918** PDF处理器。![star > 100][Bronze]
* [skywalker](https://github.com/dixonwille/skywalker) - **Star : 46** 可以轻松地并发地遍历文件系统。![最近三个月没有更新][Yellow]
* [stl](https://gitlab.com/russoj88/stl) - 采用并行读取算法的进行读取和写入STL(立体光刻)文件的模块。
* [tarfs](https://github.com/posener/tarfs) - **Star : 34** tar文件的实现[ FileSystem 接口](https://godoc.org/github.com/kr/fs#FileSystem)。![最近三个月没有更新][Yellow]
* [vfs](https://github.com/C2FO/vfs) - **Star : 18** 一组可插拔的、可扩展的和自定义的文件系统功能，用于跨越许多文件系统类型，如os、S3和GCS。![最近一个周有更新][Green]

## 金融

*会计和财务软件包。*

* [accounting](https://github.com/leekchan/accounting) - **Star : 476** 货币和货币格式。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [currency](https://github.com/bnkamalesh/currency) - **Star : 8** 高性能、准确的货币计算软件包。
* [decimal](https://github.com/shopspring/decimal) - **Star : 1537** 任意精度定点的十进制数。![star > 1000][Silver]
* [go-finance](https://github.com/FlashBoys/go-finance) - **Star : 538** 综合金融市场数据。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-finance](https://github.com/alpeb/go-finance) - **Star : 39** 用于货币时间价值(年金)、现金流、利率转换、债券和折旧计算的金融函数库。![最近三个月没有更新][Yellow]
* [go-money](https://github.com/rhymond/go-money) - **Star : 604** Fowler 货币模式的实现。![star > 100][Bronze]
* [ofxgo](https://github.com/aclindsa/ofxgo) - **Star : 59** 查询 OFX 服务器和/或解析响应。![最近一个周有更新][Green]
* [orderbook](https://github.com/i25959341/orderbook) - **Star : 62** 限购单匹配引擎。
* [techan](https://github.com/sdcoffey/techan) - **Star : 140** 拥有先进的市场分析和交易策略的技术分析库。![star > 100][Bronze]
* [transaction](https://github.com/claygod/transaction) - **Star : 52** 嵌入式事务数据库，可多线程模式运行。
* [vat](https://github.com/dannyvankooten/vat) - **Star : 60** 增值税编号验证 & 欧盟增值税税率。![最近三个月没有更新][Yellow]

## 表单

*用于处理表单的库。*

* [bind](https://github.com/robfig/bind) - **Star : 23** 将表单数据与任意 Go 变量进行绑定。![最近三个月没有更新][Yellow]
* [binding](https://github.com/mholt/binding) - **Star : 752** 将来自 net/HTTP 请求的表单、JSON 数据绑定到结构体。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [conform](https://github.com/leebenson/conform) - **Star : 171** 控制用户输入。基于struct tags可对数据进行修剪、清理和擦除。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [form](https://github.com/go-playground/form) - **Star : 347**  将 url 中的数据解析到 Go 变量中，以及将 Go 语言变量编码进 url。支持 Dual Array 及 Full map。![star > 100][Bronze]
* [formam](https://github.com/monoculum/formam) - **Star : 123** 将表单的值解码为 struct。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [forms](https://github.com/albrow/forms) - **Star : 103** 与框架无关的库，用于解析和验证支持多部分表单和文件的表单/JSON数据。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gorilla/csrf](https://github.com/gorilla/csrf) - **Star : 421** 用于Go web应用程序和服务的CSRF保护。![star > 100][Bronze]![最近一个周有更新][Green]
* [nosurf](https://github.com/justinas/nosurf) - **Star : 957** CSRF保护中间件。![star > 100][Bronze]

## 方法

*在Go中支持函数式编程的包。*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - **Star : 99** 提供函数式编程功能。![最近三个月没有更新][Yellow]
* [fuego](https://github.com/seborama/fuego) - **Star : 34** Functional Experiment in Go。
* [go-underscore](https://github.com/tobyhede/go-underscore) - **Star : 1058** 常用辅助方法集合。![star > 1000][Silver]![最近三个月没有更新][Yellow]

## 游戏开发

*很棒的游戏开发库。*

* [Azul3D](https://github.com/azul3d/engine) - **Star : 421** 用Go编写的 3D 游戏引擎。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Ebiten](https://github.com/hajimehoshi/ebiten) - **Star : 1775** 很简单的 2D 游戏库。![star > 1000][Silver]![最近一个周有更新][Green]
* [engo](https://github.com/EngoEngine/engo) - **Star : 1071** 开源 2D 游戏引擎。它遵循 Entity-Component-System 范式。![star > 1000][Silver]
* [g3n](https://github.com/g3n/engine) - **Star : 721**  3D游戏引擎。![star > 100][Bronze]
* [GarageEngine](https://github.com/vova616/GarageEngine) - **Star : 308** 用 OpenGL 编写的 2D 游戏引擎。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [glop](https://github.com/runningwild/glop) - **Star : 77** Glop (Game Library Of Power) 是一个相当简单的跨平台游戏库。![最近三个月没有更新][Yellow]
* [go-astar](https://github.com/beefsack/go-astar) - **Star : 322** 实现了A\*路径查找算法。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-collada](https://github.com/GlenKelley/go-collada) - **Star : 12** 处理Collada文件。![最近三个月没有更新][Yellow]
* [go-sdl2](https://github.com/veandco/go-sdl2) - **Star : 1132** 实现了[Simple DirectMedia Layer](https://www.libsdl.org/)。![star > 1000][Silver]
* [go3d](https://github.com/ungerik/go3d) - **Star : 162** 以性能为主的2D/3D数学相关包。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gonet](https://github.com/xtaci/gonet) - **Star : 1042** 实现了游戏服务器骨架。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [goworld](https://github.com/xiaonanln/goworld) - **Star : 1132** 可伸缩的游戏服务器引擎，具有 space-entity 框架和 hot-swapping 功能。![star > 1000][Silver]
* [Leaf](https://github.com/name5566/leaf) - **Star : 2989** 轻量级游戏服务器框架。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [nano](https://github.com/lonng/nano) - **Star : 956** 轻量级、方便、高性能的基于golang的游戏服务器框架。![star > 100][Bronze]![最近一个周有更新][Green]
* [Oak](https://github.com/oakmound/oak) - **Star : 622** 纯 Go 实现的游戏引擎。![star > 100][Bronze]
* [Pitaya](https://github.com/topfreegames/pitaya) - **Star : 283** 可伸缩的游戏服务器框架，支持集群和客户端库的iOS, Android, Unity。![star > 100][Bronze]
* [Pixel](https://github.com/faiface/pixel) - **Star : 2371** 手工制作的 2D 游戏库。![star > 1000][Silver]![最近一个周有更新][Green]
* [raylib-go](https://github.com/gen2brain/raylib-go) - **Star : 377** 实现了 [raylib](http://www.raylib.com/)，一个简单易用的库，用于学习视频游戏编程。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [termloop](https://github.com/JoelOtter/termloop) - **Star : 1017** 基于终端的 Go 游戏引擎，建立在 Termbox 之上。![star > 1000][Silver]

## 代码生成与泛型

*增强语言的工具，例如通过代码生成支持泛型。*

* [efaceconv](https://github.com/t0pep0/efaceconv) - **Star : 42** 代码生成工具，可以不通过内存分配就可以高效的将interface{}转换为不可变类型，。![最近三个月没有更新][Yellow]
* [gen](https://github.com/clipperhouse/gen) - **Star : 1016** 用于生成泛型等类似方法的功能代码生成工具。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [generis](https://github.com/senselogic/GENERIS) - **Star : 18** 提供泛型、free-form 宏、条件编译和HTML模板的代码生成工具。
* [go-enum](https://github.com/abice/go-enum) - **Star : 80** 从代码注释中生成枚举。
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - **Star : 1759** 提供类似 .NET LINQ 的查询方法。![star > 1000][Silver]
* [goderive](https://github.com/awalterschulze/goderive) - **Star : 717** 从输入类型来派生函数。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gotype](https://github.com/wzshiming/gotype) - **Star : 19** Golang 源码解析，用法类似reflect(反射)。
* [GoWrap](https://github.com/hexdigest/gowrap) - **Star : 258** 使用简单模板为 Go 接口生成装饰器。![star > 100][Bronze]
* [interfaces](https://github.com/rjeczalik/interfaces) - **Star : 184** 用于生成接口定义的命令行工具。![star > 100][Bronze]
* [jennifer](https://github.com/dave/jennifer) - **Star : 1248** 不使用模板生成任意 Go 代码。![star > 1000][Silver]
* [pkgreflect](https://github.com/ungerik/pkgreflect) - **Star : 84** 用于包作用域反射的 Go 预处理器。![最近三个月没有更新][Yellow]

## 地理

*地理工具和服务器*

* [geocache](https://github.com/melihmucuk/geocache) - **Star : 106** 基于内存缓存的的地理位置的应用程序。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [geoserver](https://github.com/hishamkaram/geoserver) - **Star : 24** 基于geoserver REST API的 geoserver 实例。![最近三个月没有更新][Yellow]
* [gismanager](https://github.com/hishamkaram/gismanager) - **Star : 17** 将你的 GIS 数据(矢量数据)发布到 PostGIS 和 Geoserver。![最近三个月没有更新][Yellow]
* [osm](https://github.com/paulmach/osm) - **Star : 58** 用于读取、写入和处理 OpenStreetMap 数据和 APIs。![最近三个月没有更新][Yellow]
* [pbf](https://github.com/maguro/pbf) - **Star : 15** 基于Golang 的 OpenStreetMap PBF 编码器/解码器。![最近三个月没有更新][Yellow]
* [S2 geometry](https://github.com/golang/geo) - **Star : 870** S2 geometry 库。![star > 100][Bronze]
* [Tile38](https://github.com/tidwall/tile38) - **Star : 6260** 具有空间索引和实时地理定位功能的地理定位数据库。![star > 5000][Gold]![最近一个周有更新][Green]

## Go 编译器

*可将 Go 转换为其他语言的编译工具。*

* [c4go](https://github.com/Konstantin8105/c4go) - **Star : 142** 将 C 代码转换为 Go 代码。![star > 100][Bronze]
* [f4go](https://github.com/Konstantin8105/f4go) - **Star : 11** 将 FORTRAN 77 转换为 Go代码。![最近三个月没有更新][Yellow]
* [gopherjs](https://github.com/gopherjs/gopherjs) - **Star : 8420** 将 Go 编译成 JavaScript。![star > 5000][Gold]
* [llgo](https://github.com/go-llvm/llgo) - **Star : 986** 基于 llvm 的编译器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [tardisgo](https://github.com/tardisgo/tardisgo) - **Star : 391** Golang 转换为 Haxe，再转换为 CPP/CSharp/Java/JavaScript 的编译器.![star > 100][Bronze]![最近三个月没有更新][Yellow]

## Goroutines

*管理和处理 Goroutines 的工具。*

* [ants](https://github.com/panjf2000/ants) - **Star : 1740** 一个高性能的协程池。![star > 1000][Silver]![最近一个周有更新][Green]
* [artifex](https://github.com/borderstech/artifex) - **Star : 12** 简单的内存作业队列。![最近三个月没有更新][Yellow]
* [async](https://github.com/studiosol/async) - **Star : 18** 一种异步执行函数的安全方法，在出现 panic 时恢复它们。![最近三个月没有更新][Yellow]
* [breaker](https://github.com/kamilsk/breaker) - **Star : 24** 灵活的机制，可以使执行流可中断。![最近一个周有更新][Green]
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - **Star : 27** 基于 Go 的 CyclicBarrier 实现。![最近三个月没有更新][Yellow]
* [go-floc](https://github.com/workanator/go-floc) - **Star : 167** 轻松编排 goroutines。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - **Star : 103** 控制 goroutines 的执行顺序。![star > 100][Bronze]
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - **Star : 5** 轻量级的协程池库，可以通过简单的API来管理。![最近三个月没有更新][Yellow]
* [go-trylock](https://github.com/subchen/go-trylock) - **Star : 4** 支持 read-write 锁。![最近三个月没有更新][Yellow]
* [gollback](https://github.com/vardius/gollback) - **Star : 25** 异步简单的函数实用程序，用于管理闭包和回调的执行。
* [GoSlaves](https://github.com/themester/GoSlaves) - **Star : 74** 简单异步的协程池。
* [goworker](https://github.com/benmanns/goworker) - **Star : 2220** 基于 go 的后台 worker。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [gpool](https://github.com/Sherifabdlnaby/gpool) - **Star : 58** manages a resizeable pool of context-aware goroutines to bound concurrency
* [grpool](https://github.com/ivpusic/grpool) - **Star : 487** 轻量级协程池。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Hunch](https://github.com/AaronJan/Hunch) - **Star : 8** Hunch 提供了诸如 All、First、Retry、Waterfall 等功能，这使得异步流控制更加直观。![最近一个周有更新][Green]
* [oversight](https://cirello.io/oversight) - 完整的实现了Erlang supervision trees。
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - **Star : 24** 并行运行函数。![最近三个月没有更新][Yellow]
* [pool](https://github.com/go-playground/pool) - **Star : 471** 有限消费者协程或无限协程池，可用于更加简单的处理和取消协程![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [queue](https://github.com/AnikHasibul/queue) - **Star : 1** 提供类似队列组可访问性 sync.WaitGroup 的功能。帮助你节流和限制协程、等待所有协程结束以及更多功能。
* [routine](https://github.com/x-mod/routine) - **Star : 1** go routine control with context, support: Main, Go, Pool and some useful Executors.
* [semaphore](https://github.com/kamilsk/semaphore) - **Star : 74** 信号量模式实现，可根据通道和上下文进行具备超时功能的锁定/解锁操作。
* [semaphore](https://github.com/marusama/semaphore) - **Star : 69** 基于 CAS 的可快速调整的信号量实现(比基于通道的信号量实现更快)。![最近三个月没有更新][Yellow]
* [stl](https://github.com/ssgreg/stl) - **Star : 7** 基于软件事务内存(STM)并发控制机制的软件事务锁。
* [threadpool](https://github.com/shettyh/threadpool) - **Star : 17** Golang 的 threadpool 实现。![最近三个月没有更新][Yellow]
* [tunny](https://github.com/Jeffail/tunny) - **Star : 1293** golang 的协程池。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [worker-pool](https://github.com/vardius/worker-pool) - **Star : 43** 一个简单的 Go 异步工作池。
* [workerpool](https://github.com/gammazero/workerpool) - **Star : 118** 限制任务执行并发数，而不是队列中的任务数量的协程池，。![star > 100][Bronze]

## GUI

*用于构建GUI应用程序的库。*

*工具包*

* [app](https://github.com/murlokswarm/app) - **Star : 2912** 用于创建包含了 GO, HTML 和 CSS 的应用程序。支持 MacOS, Windows 正在开发中。![star > 1000][Silver]
* [fyne](https://github.com/fyne-io/fyne) - **Star : 6004** 为 Go 而设计的跨平台的本地GUIs，使用EFL呈现。支持 : Linux, macOS, Windows。![star > 5000][Gold]![最近一个周有更新][Green]
* [go-astilectron](https://github.com/asticode/go-astilectron) - **Star : 2591** 使用 GO 和 HTML/JS/CSS (电子驱动)进行构建跨平台 GUI 应用程序。![star > 1000][Silver]
* [go-gtk](http://mattn.github.io/go-gtk/) - 实现了 GTK 的 Go接口。
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - **Star : 1415** 实现了 Sciter 的 Go 接口 : 用于现代桌面 UI 开发的可嵌入HTML/CSS/脚本引擎。可跨平台。![star > 1000][Silver]
* [gotk3](https://github.com/gotk3/gotk3) - **Star : 728** 实现了 GTK3 的 Go接口。![star > 100][Bronze]
* [gowd](https://github.com/dtylman/gowd) - **Star : 201** 跨平台、快速、简单的桌面UI开发，采用了GO, HTML, CSS和NW.js实现。![star > 100][Bronze]
* [qt](https://github.com/therecipe/qt) - **Star : 5797** 实现了 Qt 的 Go接口(支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi)。![star > 5000][Gold]![最近一个周有更新][Green]
* [ui](https://github.com/andlabs/ui) - **Star : 6821** 跨平台的 Platform-native GUI 库。![star > 5000][Gold]![最近三个月没有更新][Yellow]
* [Wails](https://wails.app) - Mac, Windows, Linux桌面应用程序，主要基于含有内置的OS HTML渲染器的HTML UI。
* [walk](https://github.com/lxn/walk) - **Star : 3626** Windows应用程序库。![star > 1000][Silver]
* [webview](https://github.com/zserge/webview) - **Star : 4508** 跨平台webview窗口，具有简单的双向JavaScript绑定(Windows / macOS / Linux)。![star > 1000][Silver]![最近一个周有更新][Green]

*交互*

* [go-appindicator](https://github.com/dawidd6/go-appindicator) - **Star : 1** 实现了 libappindicator3 C库 的 Go接口。
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - **Star : 492** OSX 桌面通知库。![star > 100][Bronze]
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) - **Star : 1** 用于通知计算机上的任何(可插入的)活动的 OSX 库。
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX 睡眠/唤醒通知。
* [robotgo](https://github.com/go-vgo/robotgo) - **Star : 4344** 实现跨平台的GUI系统自动化。包含了控制鼠标、键盘等功能。![star > 1000][Silver]![最近一个周有更新][Green]
* [systray](https://github.com/getlantern/systray) - **Star : 751** 跨平台 Go 库，可在通知区放置图标和菜单。![star > 100][Bronze]![最近一个周有更新][Green]
* [trayhost](https://github.com/shurcooL/trayhost) - **Star : 158** 跨平台 Go 库，可用于在主机操作系统的任务栏中放置图标。![star > 100][Bronze]![最近三个月没有更新][Yellow]


## 硬件

*硬件交互相关的库、工具和教程。*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## 图片

*图像处理相关的库。*

* [bild](https://github.com/anthonynsimon/bild) - **Star : 2016** 纯Go语言实现的图像处理算法合集。![star > 1000][Silver]
* [bimg](https://github.com/h2non/bimg) - **Star : 767** 使用libvips实现的快速高效的图像处理包。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [cameron](https://github.com/aofei/cameron) - **Star : 30** 一个Go语言的头像生成器。
* [geopattern](https://github.com/pravj/geopattern) - **Star : 1008** 由字符串创建漂亮图案的图片生成器。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [gg](https://github.com/fogleman/gg) - **Star : 1867** 纯Go语言实现的2D渲染。![star > 1000][Silver]
* [gift](https://github.com/disintegration/gift) - **Star : 1203** 图像处理包。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [gltf](https://github.com/qmuntal/gltf) - **Star : 34** 一个高效、健壮的glTF 2.0文件读取、写入和验证器。
* [go-cairo](https://github.com/ungerik/go-cairo) - **Star : 85**  cairo图形库的Go binding。![最近三个月没有更新][Yellow]
* [go-gd](https://github.com/bolknote/go-gd) - **Star : 48**  GD库的Go binding。![最近三个月没有更新][Yellow]
* [go-nude](https://github.com/koyachi/go-nude) - **Star : 279** Go语言实现的裸照检测工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-opencv](https://github.com/lazywei/go-opencv) - **Star : 1079** OpenCV库的Go bindings。![star > 1000][Silver]
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - **Star : 24** Python下webcolors库的Go语言调用。![最近三个月没有更新][Yellow]
* [gocv](https://github.com/hybridgroup/gocv) - **Star : 2353** 使用OpenCV 3.3+实现的计算机视觉(ComputerVision)的Go语言包。![star > 1000][Silver]
* [goimagehash](https://github.com/corona10/goimagehash) - **Star : 206**  图像哈希处理的Go语言包。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goimghdr](https://github.com/corona10/goimghdr) - **Star : 26** Go语言实现的imghdr模块用于确定文件的图像类型。
* [govatar](https://github.com/o1egl/govatar) - **Star : 307** 生成有趣头像的库和CMD工具。![star > 100][Bronze]
* [image2ascii](https://github.com/qeesung/image2ascii) - **Star : 282** 将图像转换为ASCII码。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [imagick](https://github.com/gographics/imagick) - **Star : 951**  ImageMagick下MagickWand的C API的Go binding。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [imaginary](https://github.com/h2non/imaginary) - **Star : 2541** 用于图像大小调整的快速、简单的HTTP微服务。![star > 1000][Silver]![最近一个周有更新][Green]
* [imaging](https://github.com/disintegration/imaging) - **Star : 2459** 简单的Go图像处理包。![star > 1000][Silver]
* [img](https://github.com/hawx/img) - **Star : 128** 图像处理工具的集合。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [ln](https://github.com/fogleman/ln) - **Star : 2439** Go实现的3D线艺术（3D Line Art）渲染。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [mergi](https://github.com/noelyahan/mergi) - **Star : 68** 用于图像处理(合并、裁剪、调整大小、水印、动画)的工具和Go库。
* [mort](https://github.com/aldor007/mort) - **Star : 362** Go语言实现的图像存储和处理服务器。![star > 100][Bronze]
* [mpo](https://github.com/donatj/mpo) - **Star : 6** MPO三维照片的解码和转换工具。![最近三个月没有更新][Yellow]
* [picfit](https://github.com/thoas/picfit) - **Star : 1049** Go实现的图像调整服务器。![star > 1000][Silver]
* [pt](https://github.com/fogleman/pt) - **Star : 1750** Go实现的路径跟踪（path tracing）引擎。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [resize](https://github.com/nfnt/resize) - **Star : 2107** Go实现的使用常用的插值法（interpolation methods）调整图像大小的库。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [rez](https://github.com/bamiaux/rez) - **Star : 181** 纯Go语言和SIMD实现的图像大小调整。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [smartcrop](https://github.com/muesli/smartcrop) - **Star : 1239** 为任意图片寻找合适的位置进行图片裁剪。![star > 1000][Silver]
* [steganography](https://github.com/auyer/steganography) - **Star : 25** 纯Go实现的LSB隐写（LSB steganography）的库。
* [stegify](https://github.com/DimitarPetrov/stegify) - **Star : 480**  Go实现的LSB隐写（LSB steganography），能够隐藏任何文件到一个图像中。![star > 100][Bronze]
* [svgo](https://github.com/ajstarks/svgo) - **Star : 1307**  Go实现的SVG生成库。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [tga](https://github.com/ftrvxmtrx/tga) - **Star : 23** tga包是一个TARGA图像的解码、编码器。![最近三个月没有更新][Yellow]

## 物联网

*物联网设备编程库。*

* [connectordb](https://github.com/connectordb/connectordb) - **Star : 166** 自我量化和物联网的开源平台。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [devices](https://github.com/goiot/devices) - **Star : 224** 一套用于物联网设备的库，实验性地用于x/exp/io。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [eywa](https://github.com/xcodersun/eywa) - **Star : 35** Eywa是一个用于跟踪连接的设备连接管理器。![最近三个月没有更新][Yellow]
* [flogo](https://github.com/tibcosoftware/flogo) - **Star : 1089** Flogo是一个面向物联网边缘应用和集成的开源框架。![star > 1000][Silver]
* [gatt](https://github.com/paypal/gatt) - **Star : 806** Gatt是一个用于构建低能耗蓝牙外围设备的Go语言包。![star > 100][Bronze]
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot是一个用于机器人、物理计算和物联网的框架。
* [huego](https://github.com/amimof/huego) - **Star : 107** 一个包含广泛的Philips Hue客户端的Go语言库。![star > 100][Bronze]
* [iot](https://github.com/vaelen/iot/) - IoT是一个实现谷歌物联网核心设备的简单框架。
* [mainflux](https://github.com/Mainflux/mainflux) - **Star : 551** 工业物联网消息和设备管理服务器。![star > 100][Bronze]![最近一个周有更新][Green]
* [periph](https://periph.io/) - 外围设备I/O与低级板(low-level board)设备接口。
* [sensorbee](https://github.com/sensorbee/sensorbee) - **Star : 175** 轻量级物联网流处理引擎。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 作业调度器

*用于作业调度的库。*

* [clockwerk](http://github.com/onatm/clockwerk) - 使用简单、流畅的语法调度作业的Go语言库。
* [clockwork](https://github.com/whiteShtef/clockwork) - **Star : 74** Go实现的简单直观的作业调度库。
* [go-cron](https://github.com/rk/go-cron) - **Star : 177** 一个Go实现的简单的定时任务库。可以在不同的时间间隔（每秒一次到在每年在特定的日期执行）执行闭包或函数。主要用于web应用和长时间运行的守护进程。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gron](https://github.com/roylee0704/gron) - **Star : 622** 使用简单的Go API定义基于时间的任务。 之后Gron的调度程序将运行它们。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [JobRunner](https://github.com/bamzi/jobrunner) - **Star : 559** 智能和功能丰富的cron作业调度程序（包含任务队列和实时监控）。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [jobs](https://github.com/albrow/jobs) - **Star : 449** 持久和灵活的后台作业库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [leprechaun](https://github.com/kilgaloon/leprechaun) - **Star : 36** 支持webhook、crons和经典调度的作业调度程序。
* [scheduler](https://github.com/carlescere/scheduler) - **Star : 290** Cronjobs让调度变得很简单。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## JSON

*用于JSON处理的库。*

* [ajson](https://github.com/spyzhov/ajson) - **Star : 10** 为Go语言开发的包含JSONPath支持的抽象JSON。
* [gjo](https://github.com/skanehira/gjo) - **Star : 57** 用于创建JSON对象的小工具。
* [GJSON](https://github.com/tidwall/gjson) - **Star : 4701** 使用一行代码获取JSON的值。![star > 1000][Silver]![最近一个周有更新][Green]
* [go-respond](https://github.com/nicklaw5/go-respond) - **Star : 20** 用于处理常见的HTTP JSON响应的Go语言库。![最近一个周有更新][Green]
* [gojq](https://github.com/elgs/gojq) - **Star : 139** Go语言实现的JSON请求。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gojson](https://github.com/ChimeraCoder/gojson) - **Star : 2016** 从JSON自动生成Go的结构（struct）定义。![star > 1000][Silver]
* [JayDiff](https://github.com/yazgazan/jaydiff) - **Star : 37** 用Go编写的JSON比对工具。
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - 将JSON转换为Go的结构（struct）。
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - **Star : 5** 基于JSON API错误引用的Go bindings。![最近三个月没有更新][Yellow]
* [jsonf](https://github.com/miolini/jsonf) - **Star : 55** 用于高亮展示和查询JSON的控制台工具。![最近三个月没有更新][Yellow]
* [jsongo](https://github.com/ricardolonga/jsongo) - **Star : 93** 使用Fluent API来更容易地创建Json对象。![最近三个月没有更新][Yellow]
* [jsonhal](https://github.com/RichardKnop/jsonhal) - **Star : 9** 让自定义结构（struct）转化为JSON兼容的HAL（Hypertext Application Language）返回数据的简单Go包。![最近三个月没有更新][Yellow]
* [kazaam](https://github.com/Qntfy/kazaam) - **Star : 123** 用于任意JSON文档转换的API。![star > 100][Bronze]
* [mp](https://github.com/sanbornm/mp) - **Star : 32** 简单的cli电子邮件解析器。它目前接受stdin并输出JSON。![最近三个月没有更新][Yellow]

## 日志记录

*用于生成和处理日志文件的库。*

* [distillog](https://github.com/amoghe/distillog) - **Star : 18** 经过蒸馏的水平日志记录(可以将其视为stdlib +日志级别)。![最近三个月没有更新][Yellow]
* [glg](https://github.com/kpango/glg) - **Star : 51** glg是一个简单而快速的Go日志库。
* [glo](https://github.com/lajosbencz/glo) - **Star : 7** PHP独白激发了具有相同严重性级别的日志记录功能。![最近三个月没有更新][Yellow]
* [glog](https://github.com/golang/glog) - **Star : 2260** 为Go提供了水平的执行日志。![star > 1000][Silver]
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - **Star : 19** 基于当前日期和时间自动旋转日志文件的简单编写器，如cronolog。![最近三个月没有更新][Yellow]
* [go-log](https://github.com/subchen/go-log) - **Star : 10** 简单且可配置的登录Go，带有level、格式化程序和编写器。![最近三个月没有更新][Yellow]
* [go-log](https://github.com/siddontang/go-log) - **Star : 23** 日志库支持级别和多处理程序。![最近三个月没有更新][Yellow]
* [go-log](https://github.com/ian-kent/go-log) - **Star : 34** 在Go中实现Log4j。![最近三个月没有更新][Yellow]
* [go-logger](https://github.com/apsdehal/go-logger) - **Star : 229** 简单的日志程序的 Go 程序，与级别处理程序。![star > 100][Bronze]
* [gologger](https://github.com/sadlil/gologger) - **Star : 40** 简单易用的日志库，日志在彩色控制台，简单控制台，文件或弹性搜索。![最近三个月没有更新][Yellow]
* [gomol](https://github.com/aphistic/gomol) - **Star : 16** 具有可扩展日志输出的多输出、结构化日志记录。![最近三个月没有更新][Yellow]
* [gone/log](https://github.com/One-com/gone/tree/master/log) - 快速、可扩展、功能齐全、std-lib源代码兼容的日志库。
* [journald](https://github.com/ssgreg/journald) - **Star : 18**  Go 实现systemd Journal的本地日志API。![最近三个月没有更新][Yellow]
* [log](https://github.com/aerogo/log) - **Star : 4** 一个O(1)日志系统，允许您将一个日志连接到多个写入器(例如stdout、文件和TCP连接)。
* [log](https://github.com/apex/log) - **Star : 720** Go的结构化日志包。![star > 100][Bronze]
* [log](https://github.com/go-playground/log) - **Star : 265** 简单、可配置和可伸缩的Go结构化日志。![star > 100][Bronze]
* [log](https://github.com/teris-io/log) - **Star : 22** Go的结构化日志接口清晰地将日志外观与其实现分离开来。![最近三个月没有更新][Yellow]
* [log-voyage](https://github.com/firstrow/logvoyage) - **Star : 83** 用golang编写的功能齐全的日志saas。![最近三个月没有更新][Yellow]
* [log15](https://github.com/inconshreveable/log15) - **Star : 877** 简单、强大的Go日志。![star > 100][Bronze]
* [logdump](https://github.com/ewwwwwqm/logdump) - **Star : 8** 用于多级日志记录的包。![最近三个月没有更新][Yellow]
* [logex](https://github.com/chzyer/logex) - **Star : 32** Golang日志库，支持跟踪和水平，包装由标准日志库。![最近三个月没有更新][Yellow]
* [logger](https://github.com/azer/logger) - **Star : 135** Go的最小化日志库。![star > 100][Bronze]![最近一个周有更新][Green]
* [logmatic](https://github.com/borderstech/logmatic) - **Star : 7** 带有动态日志级别配置的Golang彩色日志记录器。![最近三个月没有更新][Yellow]
* [logo](https://github.com/mbndr/logo) - **Star : 4** Golang日志程序到不同的可配置作家。![最近三个月没有更新][Yellow]
* [logrus](https://github.com/Sirupsen/logrus) - **Star : 11424** 结构化的日志 Go 。![star > 5000][Gold]![最近一个周有更新][Green]
* [logrusly](https://github.com/sebest/logrusly) - **Star : 26** [logrus](https://github.com/sirupsen/logrus)插件将错误发送到[Loggly](https://www.loggly.com/)。![最近三个月没有更新][Yellow]
* [logutils](https://github.com/hashicorp/logutils) - **Star : 247** 用于稍微更好地登录的实用程序Go (Golang)扩展了标准日志记录器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [logxi](https://github.com/mgutz/logxi) - **Star : 332** 12因素的应用程序日志程序是快速的，让你快乐。![star > 100][Bronze]
* [lumberjack](https://github.com/natefinch/lumberjack) - **Star : 1379** 简单的滚动日志程序，实现io.WriteCloser。![star > 1000][Silver]![最近一个周有更新][Green]
* [mlog](https://github.com/jbrodriguez/mlog) - **Star : 17** 简单的go日志模块，有5个级别，可选的旋转日志文件功能和stdout/stderr输出。![最近三个月没有更新][Yellow]
* [onelog](https://github.com/francoispqt/onelog) - **Star : 325** Onelog是一个非常简单但非常高效的JSON日志程序。它是所有场景中速度最快的JSON日志程序。而且，它是配置最低的日志记录器之一。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - **Star : 108** 支持日志严重性、分类和过滤的高性能日志记录。可以发送过滤日志消息到各种目标(如控制台，网络，邮件)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) - **Star : 94** RollingWriter是一个自动旋转的io。作者的实现与多个策略，以提供日志文件旋转。
* [seelog](https://github.com/cihub/seelog) - **Star : 1335** 具有灵活调度、过滤和格式化的日志功能。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [spew](https://github.com/davecgh/go-spew) - **Star : 3231** 为Go数据结构实现一个漂亮的深层打印机，以帮助调试。![star > 1000][Silver]
* [stdlog](https://github.com/alexcesaro/log) - **Star : 43** Stdlog是一个面向对象的库，提供水平日志记录。它对cron作业非常有用。![最近三个月没有更新][Yellow]
* [tail](https://github.com/hpcloud/tail) - **Star : 1494** Go软件包努力模拟BSD tail程序的特性。![star > 1000][Silver]
* [xlog](https://github.com/xfxdev/xlog) - **Star : 7** 插件架构和灵活的日志系统的Go，与级别ctrl，多日志目标和自定义日志格式。![最近三个月没有更新][Yellow]
* [xlog](https://github.com/rs/xlog) - **Star : 130** 结构化记录器'net/context`意识到HTTP处理程序的灵活调度。![star > 100][Bronze]
* [zap](https://github.com/uber-go/zap) - **Star : 7171** 快速、结构化、水平登录Go。![star > 5000][Gold]
* [zerolog](https://github.com/rs/zerolog) - **Star : 2092** 零JSON记录器。![star > 1000][Silver]![最近一个周有更新][Green]

## 机器学习

*机器学习库。*

* [bayesian](https://github.com/jbrukh/bayesian) - **Star : 625** Golang的朴素贝叶斯分类。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [CloudForest](https://github.com/ryanbressler/CloudForest) - **Star : 642** 快速、灵活、多线程的决策树集成，用于纯Go中的机器学习。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [eaopt](https://github.com/MaxHalford/eaopt) - **Star : 615** 一个进化优化库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [evoli](https://github.com/khezen/evoli) - **Star : 8** 遗传算法和粒子群优化库。
* [fonet](https://github.com/Fontinalis/fonet) - **Star : 31** 一个用Go编写的深度神经网络库。![最近三个月没有更新][Yellow]
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - **Star : 21** Go实现了k模式和k原型聚类算法。![最近三个月没有更新][Yellow]
* [go-deep](https://github.com/patrikeh/go-deep) - **Star : 213** 一个功能丰富的神经网络库在 Go 。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-fann](https://github.com/white-pony/go-fann) - **Star : 99** 快速人工神经网络(FANN)库的Go绑定。![最近三个月没有更新][Yellow]
* [go-galib](https://github.com/thoj/go-galib) - **Star : 170** 用Go / golang编写的遗传算法库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-pr](https://github.com/daviddengcn/go-pr) - **Star : 57** 模式识别包在Go lang。![最近三个月没有更新][Yellow]
* [gobrain](https://github.com/goml/gobrain) - **Star : 365** 用 Go 编写的神经网络。![star > 100][Bronze]![最近一个周有更新][Green]
* [godist](https://github.com/e-dard/godist) - **Star : 24** 各种概率分布，以及相关的方法。![最近三个月没有更新][Yellow]
* [goga](https://github.com/tomcraven/goga) - **Star : 79** Go的遗传算法库。![最近三个月没有更新][Yellow]
* [GoLearn](https://github.com/sjwhitworth/golearn) - **Star : 6593** 通用机器学习库。![star > 5000][Gold]
* [golinear](https://github.com/danieldk/golinear) - **Star : 39**  Go 的线性绑定。![最近三个月没有更新][Yellow]
* [GoMind](https://github.com/surenderthakran/gomind) - **Star : 6** 一个简单的神经网络库在 Go 。![最近三个月没有更新][Yellow]
* [goml](https://github.com/cdipaolo/goml) - **Star : 1001** 在线机器学习在 Go 。![star > 1000][Silver]
* [goRecommend](https://github.com/timkaye11/goRecommend) - **Star : 141** 推荐算法库用Go编写。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gorgonia](https://github.com/chewxy/gorgonia) - **Star : 2643** 基于图形的计算库，如Theano for Go，它为构建各种机器学习和神经网络算法提供了基本框架。![star > 1000][Silver]![最近一个周有更新][Green]
* [gorse](https://github.com/zhenghaoz/gorse) - **Star : 508** 基于协同过滤的Go高性能推荐系统包。![star > 100][Bronze]
* [goscore](https://github.com/asafschers/goscore) - **Star : 34**  Go 为PMML评分API。
* [gosseract](https://github.com/otiai10/gosseract) - **Star : 841** 使用Tesseract c++库为OCR(光学字符识别)打包。![star > 100][Bronze]
* [libsvm](https://github.com/datastream/libsvm) - **Star : 63** 基于libsvm的golang版本派生工作。![最近三个月没有更新][Yellow]
* [mlgo](https://github.com/NullHypothesis/mlgo) - **Star : 5** 这个项目的目的是在 Go 中提供最小化的机器学习算法。![最近三个月没有更新][Yellow]
* [neat](https://github.com/jinyeom/neat) - **Star : 55** 即插即用的并行Go框架，用于增强拓扑的神经进化(整洁)。![最近三个月没有更新][Yellow]
* [neural-go](https://github.com/schuyler/neural-go) - **Star : 61** 多层感知器网络在Go中实现，通过反向传播进行训练。![最近三个月没有更新][Yellow]
* [ocrserver](https://github.com/otiai10/ocrserver) - **Star : 216** 一个简单的OCR API服务器，非常容易被Docker和Heroku部署。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [onnx-go](https://github.com/owulveryck/onnx-go) - **Star : 137** Go接口打开神经网络交换(ONNX)。![star > 100][Bronze]![最近一个周有更新][Green]
* [probab](https://github.com/ThePaw/probab) - **Star : 10** 概率分布函数。贝叶斯推理。用纯 Go 写的。![最近三个月没有更新][Yellow]
* [regommend](https://github.com/muesli/regommend) - **Star : 243** 推荐&协同过滤引擎。![star > 100][Bronze]
* [shield](https://github.com/eaigner/shield) - **Star : 124** 贝叶斯文本分类器，具有灵活的令牌器和存储后端。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [tfgo](https://github.com/galeone/tfgo) - **Star : 1156** 易于使用的Tensorflow绑定:简化了官方Tensorflow Go绑定的使用。在Go中定义计算图形，加载和执行Python中训练的模型。![star > 1000][Silver]
* [Varis](https://github.com/Xamber/Varis) - **Star : 24** Golang神经网络。![最近三个月没有更新][Yellow]

## 消息

*实现消息传递系统的库。*

* [APNs2](https://github.com/sideshow/apns2) - **Star : 2021** HTTP / 2苹果推送通知供应商——发送推送通知到iOS, tvo, Safari和OSX的应用。![star > 1000][Silver]
* [Beaver](https://github.com/Clivern/Beaver) - **Star : 711** 一个实时消息服务器，可构建一个可伸缩的应用程序内通知，多人游戏，聊天应用程序在web和移动应用程序。![star > 100][Bronze]
* [Benthos](https://github.com/Jeffail/benthos) - **Star : 1899** 一系列协议之间的消息流桥。![star > 1000][Silver]![最近一个周有更新][Green]
* [Bus](https://github.com/mustafaturan/bus) - **Star : 110** 内部通信的最小消息总线实现。![star > 100][Bronze]
* [Centrifugo](https://github.com/centrifugal/centrifugo) - **Star : 3611** 实时消息(Websockets或SockJS)服务器。![star > 1000][Silver]![最近一个周有更新][Green]
* [Commander](https://github.com/jeroenrinzema/commander) - **Star : 19** 高级事件驱动的消费者/生产者，支持各种“方言”，如Apache Kafka。
* [dbus](https://github.com/godbus/dbus) - **Star : 350** D-Bus的本地Go绑定。![star > 100][Bronze]
* [drone-line](https://github.com/appleboy/drone-line) - **Star : 58** 使用二进制、docker或从属CI发送[Line](https://at.line.me/en)通知。![最近三个月没有更新][Yellow]
* [emitter](https://github.com/olebedev/emitter) - **Star : 307** 使用通配符、谓词、取消可能性和许多其他优点，使用Go way发出事件。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [event](https://github.com/agoalofalife/event) - **Star : 27** 模式观察者的实现。![最近三个月没有更新][Yellow]
* [EventBus](https://github.com/asaskevich/EventBus) - **Star : 539** 具有异步兼容性的轻量级事件总线。![star > 100][Bronze]
* [gaurun-client](https://github.com/osamingo/gaurun-client) - **Star : 8** 用Go编写的Gaurun客户端。
* [Glue](https://github.com/desertbit/glue) - **Star : 312** 健壮的Go和Javascript套接字库(替代Socket.io)。![star > 100][Bronze]![最近一个周有更新][Green]
* [go-notify](https://github.com/TheCreeper/go-notify) - **Star : 47** 本地实现的freedesktop通知规范。![最近三个月没有更新][Yellow]
* [go-nsq](https://github.com/nsqio/go-nsq) - **Star : 1435** NSQ的官方Go包。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [go-socket.io](https://github.com/googollee/go-socket.io) - **Star : 2827** 套接字。面向golang的io库，一个实时应用程序框架。![star > 1000][Silver]
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - **Star : 11** 客户端库到Viessmann Vitotrol web服务。
* [Gollum](https://github.com/trivago/gollum) - **Star : 761** n:m多路复用器，它收集来自不同来源的消息并将其广播到一组目的地。![star > 100][Bronze]
* [golongpoll](https://github.com/jcuga/golongpoll) - **Star : 418** HTTP longpoll服务器库，使web发布-订阅变得简单。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goose](https://github.com/ian-kent/goose) - **Star : 37** 服务器在Go中发送事件。![最近三个月没有更新][Yellow]
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - **Star : 1820** gopush-cluster是一个gopush服务器集群。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [gorush](https://github.com/appleboy/gorush) - **Star : 3623** 使用[APNs2](https://github.com/sideshow/apns2)和谷歌[GCM](https://github.com/google/go-gcm)推送通知服务器。![star > 1000][Silver]![最近一个周有更新][Green]
* [guble](https://github.com/smancke/guble) - **Star : 138** 消息服务器使用推送通知(谷歌Firebase云消息、苹果推送通知服务、SMS)以及websockets，一个REST API，具有分布式操作和消息持久性。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [hub](https://github.com/leandro-lugaresi/hub) - **Star : 24** 用于Go应用程序的消息/事件中心，使用发布/订阅模式，并支持别名(如rabbitMQ交换)。![最近三个月没有更新][Yellow]
* [jazz](https://github.com/socifi/jazz) - **Star : 6** 一个简单的RabbitMQ抽象层，用于队列管理和消息的发布和消费。![最近三个月没有更新][Yellow]
* [machinery](https://github.com/RichardKnop/machinery) - **Star : 3298** 基于分布式消息传递的异步任务队列/作业队列。![star > 1000][Silver]![最近一个周有更新][Green]
* [mangos](https://github.com/go-mangos/mangos) - **Star : 1531** 具有传输互操作性的Nanomsg(“可伸缩协议”)的纯go实现。![star > 1000][Silver]![最近一个周有更新][Green]
* [melody](https://github.com/olahol/melody) - **Star : 1509** 处理websocket会话的极简框架，包括广播和自动乒乓球处理。![star > 1000][Silver]![最近一个周有更新][Green]
* [Mercure](https://github.com/dunglas/mercure) - **Star : 1432** 使用Mercure协议(构建在服务器发送事件之上)分派服务器发送的更新的服务器和库。![star > 1000][Silver]![最近一个周有更新][Green]
* [messagebus](https://github.com/vardius/message-bus) - **Star : 62** messagebus是一种Go简单异步消息总线，非常适合在执行事件源、CQRS和DDD时用作事件总线。
* [NATS Go Client](https://github.com/nats-io/nats) - **Star : 2336** 轻量级和高性能的发布-订阅和分布式队列消息传递系统——这是Go库。![star > 1000][Silver]
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - **Star : 49** 一个围绕NSQ主题和通道的小包装。![最近三个月没有更新][Yellow]
* [oplog](https://github.com/dailymotion/oplog) - **Star : 94** 用于REST api的通用oplog/复制系统。![最近三个月没有更新][Yellow]
* [pubsub](https://github.com/tuxychandru/pubsub) - **Star : 270** 简单的pubsubpackage for go。![star > 100][Bronze]
* [rabbus](https://github.com/rafaeljesus/rabbus) - **Star : 61** amqp交换器和队列上的一个小包装。![最近三个月没有更新][Yellow]
* [rabtap](https://github.com/jandelgado/rabtap) - **Star : 66** RabbitMQ瑞士军刀cli应用。
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - **Star : 55** RapidMQ是用于管理本地消息队列的轻量级可靠库。![最近三个月没有更新][Yellow]
* [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ重新连接。amqp包装器。连接和amqp.Dial。在强制关闭对Close()方法的调用之前，允许在连接断开时重新连接。
* [sarama](https://github.com/Shopify/sarama) - **Star : 4446**  Go Apache Kafka的库。![star > 1000][Silver]![最近一个周有更新][Green]
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - **Star : 1092** Redis支持面向移动设备的服务器端通知的统一推送服务。![star > 1000][Silver]
* [zmq4](https://github.com/pebbe/zmq4) - **Star : 770** 转接口到ZeroMQ版本4。也可用于[版本3](https://github.com/pebbe/zmq3)和[版本2](https://github.com/pebbe/zmq2)。![star > 100][Bronze]![最近一个周有更新][Green]

## 微软办公软件

### Microsoft Excel

*用于使用Microsoft Excel的库。*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - **Star : 4249** Golang库读写Microsoft Excel™(XLSX)文件。![star > 1000][Silver]![最近一个周有更新][Green]
* [go-excel](https://github.com/szyhf/go-excel) - **Star : 46** 一个简单而轻便的阅读器，可以将类似于关系数据库的excel作为表来读取。![最近三个月没有更新][Yellow]
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - **Star : 12** 用于编写XLSX (Microsoft Excel)文件的libxlsxwriter的Golang绑定。![最近三个月没有更新][Yellow]
* [xlsx](https://github.com/tealeg/xlsx) - **Star : 3268** 库，以简化在Go程序中读取Microsoft Excel最新版本使用的XML格式。![star > 1000][Silver]
* [xlsx](https://github.com/plandem/xlsx) - **Star : 58** 快速和安全的方式读取/更新您现有的Microsoft Excel文件在 Go 程序。

## 杂项

### 依赖注入

*用于处理依赖项注入的库。*

* [alice](https://github.com/magic003/alice) - **Star : 34** Golang的添加依赖注入容器。![最近三个月没有更新][Yellow]
* [dig](https://github.com/uber-go/dig) - **Star : 859** 一个基于反射的Go依赖注入工具包。![star > 100][Bronze]
* [fx](https://github.com/uber-go/fx) - **Star : 635** 基于依赖注入的Go应用程序框架(构建在dig之上)。![star > 100][Bronze]
* [gocontainer](https://github.com/vardius/gocontainer) - **Star : 3** 简单的依赖注入容器。
* [inject](https://github.com/defval/inject) - **Star : 17** 一个基于反射的依赖注入容器，具有简单的接口。![最近一个周有更新][Green]
* [wire](https://github.com/Fs02/wire) - **Star : 20** Golang严格的运行时依赖注入。![最近三个月没有更新][Yellow]

### 项目布局

*用于组织项目的非正式模式集。*

* [go-sample](https://github.com/zitryss/go-sample) - **Star : 17** 使用实际代码的Go应用程序项目的示例布局。![最近三个月没有更新][Yellow]
* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - **Star : 8394** Go生态系统中常见的历史和新兴的项目布局模式。![star > 5000][Gold]
* [scaffold](https://github.com/catchplay/scaffold) - **Star : 21** 脚手架生成starter Go项目布局。让您专注于已实现的业务逻辑。![最近三个月没有更新][Yellow]

### 字符串

*处理字符串的库。*

* [strutil](https://github.com/ozgio/strutil) - **Star : 61** 字符串工具。![最近三个月没有更新][Yellow]
* [xstrings](https://github.com/huandu/xstrings) - **Star : 605** 从其他语言移植的有用字符串函数的集合。![star > 100][Bronze]![最近三个月没有更新][Yellow]

*这些库之所以放在这里，是因为其他类别似乎都不适合。*

* [anagent](https://github.com/mudler/anagent) - **Star : 11** 最小化，可插入的Golang evloop/计时器处理程序与依赖注入。![最近三个月没有更新][Yellow]
* [antch](https://github.com/antchfx/antch) - **Star : 137** 一个快速、强大和可扩展的web爬行和抓取框架。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [archiver](https://github.com/mholt/archiver) - **Star : 2396** 用于生成和提取.zip和.tar.gz存档的库和命令。![star > 1000][Silver]![最近一个周有更新][Green]
* [autoflags](https://github.com/artyom/autoflags) - **Star : 24** Go package从struct字段自动定义命令行标志。![最近三个月没有更新][Yellow]
* [avgRating](https://github.com/kirillDanshin/avgRating) - **Star : 9** 根据Wilson评分方程计算平均分和评分。![最近三个月没有更新][Yellow]
* [banner](https://github.com/dimiro1/banner) - **Star : 229** 在Go应用程序中添加漂亮的横幅。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [base64Captcha](https://github.com/mojocn/base64Captcha) - **Star : 604** Base64captch支持数字，数字，字母，算术，音频和数字-字母验证码。![star > 100][Bronze]
* [battery](https://github.com/distatus/battery) - **Star : 134** 跨平台、标准化的电池信息库。![star > 100][Bronze]
* [bitio](https://github.com/icza/bitio) - **Star : 91** 高度优化的位级读写器。![最近三个月没有更新][Yellow]
* [browscap_go](https://github.com/digitalcrab/browscap_go) - **Star : 29** 用于[浏览器功能项目]的GoLang库(http://browscap.org/)。![最近三个月没有更新][Yellow]
* [captcha](https://github.com/steambap/captcha) - **Star : 41** 软件包captcha为captcha的生成提供了一个易于使用的、未绑定的API。
* [conv](https://github.com/cstockton/go-conv) - **Star : 341** 包conv提供了跨Go类型的快速和直观的转换。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [datacounter](https://github.com/miolini/datacounter) - **Star : 27** 读取器/写入器/http.ResponseWriter的计数器。![最近三个月没有更新][Yellow]
* [ffmt](https://github.com/go-ffmt/ffmt) - **Star : 126** 美化数据显示为人类。![star > 100][Bronze]
* [ghorg](https://github.com/gabrie30/ghorg) - **Star : 22** 将所有repos从GitHub org复制到一个目录中。![最近三个月没有更新][Yellow]
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - **Star : 649** Golang的通用对象池。![star > 100][Bronze]
* [go-openapi](https://github.com/go-openapi) - 用于解析和利用开放api模式的包的集合。
* [go-resiliency](https://github.com/eapache/go-resiliency) - **Star : 831**  Go 的弹性模式。![star > 100][Bronze]
* [go-unarr](https://github.com/gen2brain/go-unarr) - **Star : 66** 用于RAR、TAR、ZIP和7z存档的解压缩库。![最近三个月没有更新][Yellow]
* [gofakeit](https://github.com/brianvoe/gofakeit) - **Star : 403** 用go编写的随机数据生成器。![star > 100][Bronze]
* [gommit](https://github.com/antham/gommit) - **Star : 65** 分析git提交消息，确保它们遵循已定义的模式。
* [gopsutil](https://github.com/shirou/gopsutil) - **Star : 3791** 用于检索进程和系统利用率(CPU、内存、磁盘等)的跨平台库。![star > 1000][Silver]![最近一个周有更新][Green]
* [gosh](https://github.com/osamingo/gosh) - **Star : 16** 提供Go统计处理程序，结构，测量方法。
* [gosms](https://github.com/haxpax/gosms) - **Star : 1220** 您自己的本地短信网关在Go，可以用来发送短信。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [gotoprom](https://github.com/cabify/gotoprom) - **Star : 15** 为Prometheus客户端提供类型安全的度量构建器包装库。
* [gountries](https://github.com/pariz/gountries) - **Star : 205** 公开国家和细分数据的包。![star > 100][Bronze]
* [health](https://github.com/dimiro1/health) - **Star : 359** 易于使用，可扩展的健康检查库。![star > 100][Bronze]
* [healthcheck](https://github.com/etherlabsio/healthcheck) - **Star : 78** 用于RESTful服务的自以为是的并发健康检查HTTP处理程序。
* [hostutils](https://github.com/Wing924/hostutils) - **Star : 7** 一个用于打包和解包FQDNs列表的golang库。![最近三个月没有更新][Yellow]
* [indigo](https://github.com/osamingo/indigo) - **Star : 51** 分布式唯一ID生成器使用Sonyflake，并由Base58编码。
* [lk](https://github.com/hyperboloide/lk) - **Star : 111** 一个简单的golang授权库。![star > 100][Bronze]
* [llvm](https://github.com/llir/llvm) - **Star : 403** 用于在纯Go中与LLVM IR交互的库。![star > 100][Bronze]![最近一个周有更新][Green]
* [metrics](https://github.com/pascaldekloe/metrics) - **Star : 4** 用于度量仪器和普罗米修斯博览会的库。
* [morse](https://github.com/alwindoss/morse) - **Star : 48** 转换成莫尔斯电码和从莫尔斯电码转换成莫尔斯电码的程序库。![最近三个月没有更新][Yellow]
* [numa](https://github.com/lrita/numa) - **Star : 2** NUMA是一个用go编写的实用程序库。它帮助我们编写一些NUMA-AWARED代码。
* [pdfgen](https://github.com/hyperboloide/pdfgen) - **Star : 32** HTTP服务从Json请求生成PDF。![最近三个月没有更新][Yellow]
* [persian](https://github.com/mavihq/persian) - **Star : 33** 一些实用的波斯语在 Go 。![最近三个月没有更新][Yellow]
* [sandid](https://github.com/aofei/sandid) - **Star : 12** 地球上的每一粒沙子都有自己的身份。
* [shellwords](https://github.com/Wing924/shellwords) - **Star : 7** 一个Golang库，根据UNIX Bourne shell的单词解析规则操纵字符串。![最近三个月没有更新][Yellow]
* [shortid](https://github.com/teris-io/shortid) - **Star : 442** 分布式生成超短、唯一、非顺序、URL友好的id。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [stats](https://github.com/go-playground/stats) - **Star : 120** 显示器 Go MemStats +系统统计，如内存，交换和CPU，并通过UDP发送到任何地方，你想记录等…![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [turtle](https://github.com/hackebrot/turtle) - **Star : 73** Emojis Go 。![最近三个月没有更新][Yellow]
* [url-shortener](https://github.com/pantrif/url-shortener) - **Star : 17** 一个现代的、强大的、健壮的URL缩短器微服务，支持mysql。![最近三个月没有更新][Yellow]
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - 生成样板http输入和输出处理。
* [xdg](https://github.com/rkoesters/xdg) - **Star : 20** FreeDesktop.org (xdg)规范在Go中实现。![最近三个月没有更新][Yellow]
* [xkg](https://github.com/go-xkg/xkg) - **Star : 39** X键盘打捞工具。![最近三个月没有更新][Yellow]

## 自然语言处理

*用于处理人类语言的库。*

* [getlang](https://github.com/rylans/getlang) - **Star : 71** 快速自然语言检测包。
* [go-eco](https://github.com/ThePaw/go-eco) - **Star : 4** 相似、不相似和距离矩阵;多样性、公平性和不平等度量;物种丰富度估计;coenocline模型。![最近三个月没有更新][Yellow]
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - 软件包和用于处理本地化文本的附带工具。
* [go-mystem](https://github.com/dveselov/mystem) - **Star : 23** CGo绑定到Yandex。Mystem -俄罗斯形态学分析仪。![最近三个月没有更新][Yellow]
* [go-nlp](https://github.com/nuance/go-nlp) - **Star : 79** 用于处理离散概率分布的实用程序和用于进行NLP工作的其他工具。![最近三个月没有更新][Yellow]
* [go-pinyin](https://github.com/mozillazg/go-pinyin) - **Star : 512** 中文汉字到汉语拼音的转换。![star > 100][Bronze]
* [go-stem](https://github.com/agonopol/go-stem) - **Star : 51** 波特词干算法的实现。![最近三个月没有更新][Yellow]
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - **Star : 54** Unicode文本的ASCII音译。
* [go2vec](https://github.com/danieldk/go2vec) - **Star : 30** 用于word2vec嵌入式的阅读器和实用程序函数。![最近三个月没有更新][Yellow]
* [gojieba](https://github.com/yanyiwu/gojieba) - **Star : 788** 这是一个Go实现的[jieba](https://github.com/fxsjy/jieba)，这是一个中文分词算法。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - **Star : 15**  Go 绑定斯诺鲍libstemmer库，包括波特2。![最近三个月没有更新][Yellow]
* [gotokenizer](https://github.com/xujiajun/gotokenizer) - **Star : 6** 一种基于字典和双字母格朗语言模型的记号赋予器。(现在只支持中文分割)
* [gounidecode](https://github.com/fiam/gounidecode) - **Star : 67** 用于Go的Unicode音译器(也称为unidecode)。![最近三个月没有更新][Yellow]
* [gse](https://github.com/go-ego/gse) - **Star : 1036** 高效的文本分割;支持英语、汉语、日语等。![star > 1000][Silver]![最近一个周有更新][Green]
* [icu](https://github.com/goodsign/icu) - **Star : 19** Cgo绑定用于icu4c C库的检测和转换功能。保证与版本50.1兼容。![最近三个月没有更新][Yellow]
* [kagome](https://github.com/ikawaha/kagome) - **Star : 411** JP形态学分析仪编写的纯Go。![star > 100][Bronze]
* [libtextcat](https://github.com/goodsign/libtextcat) - **Star : 10** 用于libtextcat C库的Cgo绑定。保证与版本2.2兼容。![最近三个月没有更新][Yellow]
* [MMSEGO](https://github.com/awsong/MMSEGO) - **Star : 59** 这是一个 Go 实现的[MMSEG](http://technology.chtsai.org/mmseg/)，这是一个中文分词算法。![最近三个月没有更新][Yellow]
* [nlp](https://github.com/Shixzie/nlp) - **Star : 354** 从字符串中提取值并用nlp填充结构。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [nlp](https://github.com/james-bowman/nlp) - **Star : 212** 支持LSA(潜在语义分析)的Go自然语言处理库。![star > 100][Bronze]
* [paicehusk](https://github.com/rookii/paicehusk) - **Star : 25** Golang实现了Paice/外壳阻塞算法。![最近三个月没有更新][Yellow]
* [petrovich](https://github.com/striker2000/petrovich) - **Star : 22** 彼得罗维奇是一个图书馆，它把俄语名字的词形变化成特定的语法格。![最近三个月没有更新][Yellow]
* [porter](https://github.com/a2800276/porter) - **Star : 8** 这是Martin Porter在C语言中实现的Porter词干分析算法的一个相当简单的移植。![最近三个月没有更新][Yellow]
* [porter2](https://github.com/zhenjl/porter2) - **Star : 33** 非常快的波特2史坦默。![最近三个月没有更新][Yellow]
* [prose](https://github.com/jdkato/prose) - **Star : 2018** 用于支持标记化、词性标记、名称实体提取等文本处理的库。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [RAKE.go](https://github.com/Obaied/RAKE.go) - **Star : 42** 快速自动关键字提取算法(RAKE)的Go端口。![最近三个月没有更新][Yellow]
* [segment](https://github.com/blevesearch/segment) - **Star : 47** 如[Unicode标准附件#29]所述，执行Unicode文本分割的Go库(http://www.unicode.org/reports/tr29/)![最近三个月没有更新][Yellow]
* [sentences](https://github.com/neurosnap/sentences) - **Star : 261** 句子标记器:将文本转换为句子列表。![star > 100][Bronze]
* [shamoji](https://github.com/osamingo/shamoji) - **Star : 10** shamoji是用Go编写的word过滤包。
* [snowball](https://github.com/goodsign/snowball) - **Star : 24** 滚雪球柄端口(cgo包装)为 Go 。提供词干提取功能[Snowball native](http://snowball.tartarus.org/)。![最近三个月没有更新][Yellow]
* [stemmer](https://github.com/dchest/stemmer) - **Star : 47** 用于Go编程语言的Stemmer包。包括英语和德语词根。![最近三个月没有更新][Yellow]
* [textcat](https://github.com/pebbe/textcat) - **Star : 60** Go package支持基于n-gram的文本分类，支持utf-8和原始文本。![最近三个月没有更新][Yellow]
* [whatlanggo](https://github.com/abadojack/whatlanggo) - **Star : 342** Go的自然语言检测包。支持84种语言和24种脚本(书写系统，如拉丁语、西里尔语等)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [when](https://github.com/olebedev/when) - **Star : 923** 带有可插入规则的自然EN和RU语言日期/时间解析器。![star > 100][Bronze]

## 网络

*用于处理网络各层的库。*

* [arp](https://github.com/mdlayher/arp) - **Star : 191** 包arp实现了arp协议，如RFC 826中所述。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - **Star : 229** 通过TCP传输协议缓冲区数据变得很容易。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [canopus](https://github.com/zubairhamed/canopus) - **Star : 134** CoAP客户机/服务器实现(RFC 7252)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [cidranger](https://github.com/yl2chen/cidranger) - **Star : 376** 快速IP到CIDR查找 Go 。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [dhcp6](https://github.com/mdlayher/dhcp6) - **Star : 60** 包dhcp6实现了一个DHCPv6服务器，如RFC 3315所述。![最近三个月没有更新][Yellow]
* [dns](https://github.com/miekg/dns) - **Star : 3712** 使用DNS的库。![star > 1000][Silver]![最近一个周有更新][Green]
* [ether](https://github.com/songgao/ether) - **Star : 62** 用于发送和接收以太网帧的跨平台Go包。![最近三个月没有更新][Yellow]
* [ethernet](https://github.com/mdlayher/ethernet) - **Star : 182** 包以太网实现了对IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的编组和解组。![star > 100][Bronze]
* [fasthttp](https://github.com/valyala/fasthttp) - **Star : 9015** 软件包fasthttp是Go的一个快速HTTP实现，比net/http快10倍。![star > 5000][Gold]![最近一个周有更新][Green]
* [fortio](https://github.com/fortio/fortio) - **Star : 828** 负载测试库和命令行工具，先进的echo服务器和web UI。允许指定一组每秒查询的负载，并记录延迟直方图和其他有用的统计数据，并将它们作图。Tcp、Http、gRPC。![star > 100][Bronze]
* [ftp](https://github.com/jlaffaye/ftp) - **Star : 500** 包ftp实现了[RFC 959](http://tools.ietf.org/html/rfc959)中描述的ftp客户机。![star > 100][Bronze]
* [gmqtt](https://github.com/DrmagicE/gmqtt) - **Star : 63** Gmqtt是一个灵活、高性能的MQTT代理库，它完全实现了MQTT协议V3.1.1。
* [gNxI](https://github.com/google/gnxi) - **Star : 99** 一组使用gNMI和gNOI协议的网络管理工具。
* [go-getter](https://github.com/hashicorp/go-getter) - **Star : 686**  Go 图书馆下载文件或目录从各种来源使用一个URL。![star > 100][Bronze]![最近一个周有更新][Green]
* [go-stun](https://github.com/ccding/go-stun) - **Star : 321** Go实现了STUN客户机(RFC 3489和RFC 5389)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gobgp](https://github.com/osrg/gobgp) - **Star : 1647** 用 Go 编程语言实现的BGP。![star > 1000][Silver]![最近一个周有更新][Green]
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - **Star : 14** golibwireshark包使用libwireshark库解码pcap文件并分析解剖数据。![最近三个月没有更新][Yellow]
* [gopacket](https://github.com/google/gopacket) - **Star : 2776** 使用libpcap绑定访问包处理库。![star > 1000][Silver]![最近一个周有更新][Green]
* [gopcap](https://github.com/akrennmair/gopcap) - **Star : 347**  Go 包装libpcap。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goshark](https://github.com/sunwxg/goshark) - **Star : 9** goshark包使用tshark来解码IP包，并创建数据结构来分析包。![最近三个月没有更新][Yellow]
* [gosnmp](https://github.com/soniah/gosnmp) - **Star : 424** 用于执行SNMP操作的本机Go库。![star > 100][Bronze]
* [gotcp](https://github.com/gansidui/gotcp) - **Star : 406**  Go 包快速编写tcp应用程序。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [grab](https://github.com/cavaliercoder/grab) - **Star : 539**  Go 软件包管理文件下载。![star > 100][Bronze]
* [graval](https://github.com/koofr/graval) - **Star : 25** 实验FTP服务器框架。![最近三个月没有更新][Yellow]
* [HTTPLab](https://github.com/gchaincl/httplab) - **Star : 3369** HTTPLabs允许您检查HTTP请求并伪造响应。![star > 1000][Silver]
* [iplib](https://github.com/c-robinson/iplib) - **Star : 24** 用于处理IP地址的库(net)。受python [ipaddress](https://docy-doc.org/3/library/ipaddress.html)和ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)的启发
* [jazigo](https://github.com/udhos/jazigo) - **Star : 122** Jazigo是一个用Go编写的工具，用于检索多个网络设备的配置。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [kcp-go](https://github.com/xtaci/kcp-go) - **Star : 2193** 快速可靠的ARQ协议。![star > 1000][Silver]![最近一个周有更新][Green]
* [kcptun](https://github.com/xtaci/kcptun) - **Star : 10515** 非常简单和快速udp隧道基于KCP协议。![star > 5000][Gold]![最近一个周有更新][Green]
* [lhttp](https://github.com/fanux/lhttp) - **Star : 506** 强大的websocket框架，使您的IM服务器更容易构建。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [linkio](https://github.com/ian-kent/linkio) - **Star : 45** 用于读写器接口的网络链路速度模拟。![最近三个月没有更新][Yellow]
* [llb](https://github.com/kirillDanshin/llb) - **Star : 8** 这是一个非常简单但快速的代理服务器后端。可用于快速重定向到预定义域，具有零内存分配和快速响应。![最近三个月没有更新][Yellow]
* [mdns](https://github.com/hashicorp/mdns) - **Star : 541** Golang中的简单mDNS(多播DNS)客户机/服务器库。![star > 100][Bronze]
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - Paho Go客户机提供一个MQTT客户机库，用于通过TCP、TLS或WebSockets连接到MQTT代理。
* [NFF-Go](https://github.com/intel-go/nff-go) - **Star : 643** 快速开发云计算和裸机网络功能的框架(原YANFF)。![star > 100][Bronze]![最近一个周有更新][Green]
* [packet](https://github.com/aerogo/packet) - **Star : 26** 通过TCP和UDP发送数据包。如果需要，它可以缓冲消息和热交换连接。
* [peerdiscovery](https://github.com/schollz/peerdiscovery) - **Star : 356** 使用UDP组播进行跨平台本地对等点发现的纯Go库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [portproxy](https://github.com/aybabtme/portproxy) - **Star : 42** 简单的TCP代理将CORS支持添加到不支持它的API中。![最近三个月没有更新][Yellow]
* [publicip](https://github.com/polera/publicip) - **Star : 18** 包publicip返回面向公共的IPv4地址(internet出口)。![最近三个月没有更新][Yellow]
* [quic-go](https://github.com/lucas-clemente/quic-go) - **Star : 2796** 在纯Go中实现了QUIC协议。![star > 1000][Silver]![最近一个周有更新][Green]
* [raw](https://github.com/mdlayher/raw) - **Star : 298** Package raw支持在设备驱动程序级别读取和写入网络接口的数据。![star > 100][Bronze]
* [sftp](https://github.com/pkg/sftp) - **Star : 711** 包sftp实现了SSH文件传输协议，如https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt所述。![star > 100][Bronze]
* [ssh](https://github.com/gliderlabs/ssh) - **Star : 1087** 用于构建SSH服务器的高级API(封装密码/ SSH)。![star > 1000][Silver]
* [sslb](https://github.com/eduardonunesp/sslb) - **Star : 113** 它是一个超级简单的负载平衡器，只是一个实现某种性能的小项目。![star > 100][Bronze]
* [stun](https://github.com/go-rtc/stun) - **Star : 255** Go实现的RFC 5389 STUN协议。![star > 100][Bronze]
* [tcp_server](https://github.com/firstrow/tcp_server) - **Star : 275**  Go 图书馆建设tcp服务器更快。![star > 100][Bronze]
* [tspool](https://github.com/two/tspool) - **Star : 5** TCP库使用工作池来提高性能并保护服务器。![最近三个月没有更新][Yellow]
* [utp](https://github.com/anacrolix/utp) - **Star : 150** Go uTP微传输协议的实现。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [water](https://github.com/songgao/water) - **Star : 826** 简单TUN / TAP图书馆。![star > 100][Bronze]
* [webrtc](https://github.com/pions/webrtc) - **Star : 2032** WebRTC API的纯Go实现。![star > 1000][Silver]![最近一个周有更新][Green]
* [winrm](https://github.com/masterzen/winrm) - **Star : 207**  Go WinRM客户端远程执行Windows机器上的命令。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [xtcp](https://github.com/xfxdev/xtcp) - **Star : 80** TCP服务器框架具有同时全双工通信，优雅关机，自定义协议。![最近三个月没有更新][Yellow]

### HTTP客户端

*用于发出HTTP请求的库。*

* [gentleman](https://github.com/h2non/gentleman) - **Star : 669** 功能齐全的插件驱动HTTP客户端库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goreq](https://github.com/smallnest/goreq) - **Star : 98** 基于gorequest的增强简化HTTP客户机。![最近三个月没有更新][Yellow]
* [grequests](https://github.com/levigross/grequests) - **Star : 1391** 一个 Go “克隆”的伟大和著名的请求库。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [heimdall](https://github.com/gojektech/heimdall) - **Star : 1047** 具有重试和hystrix功能的增强http客户机。![star > 1000][Silver]
* [pester](https://github.com/sethgrid/pester) - **Star : 319** 使用重试、后退和并发执行HTTP客户机调用。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [rq](https://github.com/ddo/rq) - **Star : 25** golang stdlib HTTP客户端更好的接口。![最近三个月没有更新][Yellow]
* [sling](https://github.com/dghubble/sling) - **Star : 845** Sling是一个用于创建和发送API请求的Go HTTP客户端库。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## OpenGL

*用于在Go中使用OpenGL的库。*

* [gl](https://github.com/go-gl/gl) - **Star : 627** OpenGL的Go绑定(通过glow生成)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [glfw](https://github.com/go-gl/glfw) - **Star : 709** Go绑定用于glfw3。![star > 100][Bronze]
* [goxjs/gl](https://github.com/goxjs/gl) - **Star : 131** 跨平台的OpenGL绑定(OS X, Linux, Windows，浏览器，iOS, Android)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goxjs/glfw](https://github.com/goxjs/glfw) - **Star : 58** 使用跨平台glfw库创建OpenGL上下文并接收事件。![最近三个月没有更新][Yellow]
* [mathgl](https://github.com/go-gl/mathgl) - **Star : 286** 纯Go数学软件包专门为三维数学，与灵感来自GLM。![star > 100][Bronze]

## ORM

*实现对象关系映射或数据映射技术的库。*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - 强大的orm框架。支持:pq / mysql / sqlite3。
* [go-firestorm](https://github.com/jschoedt/go-firestorm) - 一个用于谷歌/Firebase云Firestore的简单ORM。
* [go-pg](https://github.com/go-pg/pg) - **Star : 2871** 关注PostgreSQL的特性和性能。![star > 1000][Silver]![最近一个周有更新][Green]
* [go-queryset](https://github.com/jirfag/go-queryset) - **Star : 443** 100%类型安全ORM与代码生成和MySQL, PostgreSQL, Sqlite3, SQL Server支持基于GORM。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - **Star : 219** 一个灵活而强大的SQL字符串构建器库加上一个零配置ORM。![star > 100][Bronze]
* [go-store](https://github.com/gosuri/go-store) - **Star : 92** 简单而快速的Redis支持的键值存储库。![最近三个月没有更新][Yellow]
* [GORM](https://github.com/jinzhu/gorm) - **Star : 14113** Golang出色的ORM库的目标是对开发人员友好。![star > 5000][Gold]![最近一个周有更新][Green]
* [gorp](https://github.com/go-gorp/gorp) - **Star : 3059** Go的关系持久性，ORM-ish库。![star > 1000][Silver]
* [grimoire](https://github.com/Fs02/grimoire) - **Star : 110** Grimoire是golang的数据库访问层和验证。(支持:MySQL, PostgreSQL和SQLite3)。![star > 100][Bronze]
* [lore](https://github.com/abrahambotros/lore) - **Star : 4** 用于Go的简单轻量级伪orm /伪结构映射环境。![最近三个月没有更新][Yellow]
* [Marlow](https://github.com/dadleyy/marlow) - **Star : 60** 从项目结构生成ORM，用于编译时安全保证。![最近三个月没有更新][Yellow]
* [pop/soda](https://github.com/gobuffalo/pop) - **Star : 655** 数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。![star > 100][Bronze]![最近一个周有更新][Green]
* [QBS](https://github.com/coocood/qbs) - **Star : 536** 表示结构查询。一个ORM。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [reform](https://github.com/go-reform/reform) - **Star : 786** 更好的ORM for Go，基于非空接口和代码生成。![star > 100][Bronze]![最近一个周有更新][Green]
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - **Star : 2200** ORM生成器。根据您的数据库模式生成一个功能强大且运行速度快的ORM。![star > 1000][Silver]![最近一个周有更新][Green]
* [upper.io/db](https://github.com/upper/db) - **Star : 1814** 通过使用封装成熟数据库驱动程序的适配器与不同数据源交互的单一接口。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [Xorm](https://github.com/go-xorm/xorm) - **Star : 4998** 简单而强大的ORM for Go。![star > 1000][Silver]![最近一个周有更新][Green]
* [Zoom](https://github.com/albrow/zoom) - **Star : 237** 基于Redis的快速数据存储和查询引擎。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 包管理

*用于管理依赖和包的官方工具*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules 是源码的版本控制和交换的单位。go命令直接支持处理模块，包括记录和解决对其他模块的依赖关系。

*包管理的官方实验工具*

* [dep](https://github.com/golang/dep) - **Star : 12382**  Go 的依赖管理工具，需要 Go 1.9+![star > 5000][Gold]
* [vgo](https://go.googlesource.com/vgo/) - Go 命令版本管理

*用于包和依赖项管理的非官方库。*

* [gigo](https://github.com/LyricalSecurity/gigo) - **Star : 196** 类似pip的golang依赖工具，支持私有存储库和散列。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [glide](https://github.com/Masterminds/glide) - **Star : 7737** 轻松管理您的 golang 第三方包。受Maven、Bundler和Pip等工具的启发。![star > 5000][Gold]
* [godep](https://github.com/tools/godep) - **Star : 5652** godep是go的依赖工具，它通过修复包的依赖关系来帮助构建可重复的包。![star > 5000][Gold]![最近三个月没有更新][Yellow]
* [gom](https://github.com/mattn/gom) - **Star : 1353** Go Manager - bundle for Go。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [goop](https://github.com/nitrous-io/goop) - **Star : 779** Go 的简单依赖管理器，灵感来自Bundler。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gop](https://github.com/lunny/gop) - **Star : 50** 在GOPATH之外构建和管理Go应用程序。![最近三个月没有更新][Yellow]
* [gopm](https://github.com/gpmgo/gopm) - **Star : 2327** 包管理器。![star > 1000][Silver]
* [govendor](https://github.com/kardianos/govendor) - **Star : 4659** 包管理器。使用 vendor 文件的 Go vendor 工具。![star > 1000][Silver]
* [gpm](https://github.com/pote/gpm) - **Star : 1204** 基本的 Go 依赖管理器。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - **Star : 213** 使用Git的最小依赖版本。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [mvn-golang](https://github.com/raydac/mvn-golang) - **Star : 87** 插件，为自动加载Golang SDK，依赖关系管理和启动Maven项目基础设施中的构建环境提供了方法。
* [nut](https://github.com/jingweno/nut) - **Star : 246** vendor 依赖。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [VenGO](https://github.com/DamnWidget/VenGO) - **Star : 116** 创建和管理可导出的隔离go虚拟环境。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 查询语言

* [gojsonq](https://github.com/thedevsaddam/gojsonq) - **Star : 832** 一个用来查询JSON数据的Go包。![star > 100][Bronze]
* [graphql](https://github.com/tmc/graphql) - **Star : 51** graphql解析器+工具集![最近三个月没有更新][Yellow]
* [graphql](https://github.com/neelance/graphql-go) - **Star : 2694** 关注易用性的GraphQL服务器。![star > 1000][Silver]
* [graphql-go](https://github.com/graphql-go/graphql) - **Star : 5043** 为Go实现GraphQL。![star > 5000][Gold]
* [jsonql](https://github.com/elgs/jsonql) - **Star : 201** Golang中的JSON查询表达式库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [jsonslice](https://github.com/bhmj/jsonslice) - **Star : 22** 使用高级过滤器查询Jsonpath。
* [rql](https://github.com/a8m/rql) - **Star : 109** 用于REST API的资源查询语言。![star > 100][Bronze]

## 嵌入的资源

* [esc](https://github.com/mjibson/esc) - **Star : 456** 将文件嵌入到Go程序中并提供http文件系统接口。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [fileb0x](https://github.com/UnnoTed/fileb0x) - **Star : 416** 一个可定制的工具用来在Go中嵌入文件![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-embed](https://github.com/pyros2097/go-embed) - **Star : 14** 生成go代码，将资源文件嵌入到库或可执行文件中。![最近三个月没有更新][Yellow]
* [go-resources](https://github.com/omeid/go-resources) - **Star : 155** 嵌入到Go中的普通资源。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go.rice](https://github.com/GeertJohan/go.rice) - **Star : 1617** go.rice 是一个Go包，它使处理html、js、css、图像和模板等资源变得非常容易。![star > 1000][Silver]
* [packr](https://github.com/gobuffalo/packr) - **Star : 2009** 将静态文件嵌入到Go二进制文件中的简单方法。![star > 1000][Silver]![最近一个周有更新][Green]
* [statics](https://github.com/go-playground/statics) - **Star : 53** 将静态资源嵌入到go文件中，用于单个二进制编译+使用http。文件系统+符号链接。![最近三个月没有更新][Yellow]
* [statik](https://github.com/rakyll/statik) - **Star : 2020** 将静态文件嵌入到Go可执行文件中。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [templify](https://github.com/wlbr/templify) - **Star : 19** 将外部模板文件嵌入到Go代码中，以创建单个文件二进制文件。
* [vfsgen](https://github.com/shurcooL/vfsgen) - **Star : 632** 生成一个vfsdata。静态实现给定虚拟文件系统的go文件。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 科学与数据分析

*用于科学计算和数据分析的库。*

* [assocentity](https://github.com/ndabAP/assocentity) - **Star : 3** assocentity 返回单词到给定实体的平均距离。
* [bradleyterry](https://github.com/seanhagen/bradleyterry) - 为成对比较提供了一个 Bradley-Terry 模型。
* [chart](https://github.com/vdobler/chart) - **Star : 573** 简单的图表绘制库。支持多种图形类型。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - **Star : 59** 用于机器学习和统计的数据模型(类似于 pandas)。![最近一个周有更新][Green]
* [evaler](https://github.com/soniah/evaler) - **Star : 40** 简单的浮点算术表达式求值器。![最近三个月没有更新][Yellow]
* [ewma](https://github.com/VividCortex/ewma) - **Star : 264** 提供指数加权移动平均算法。![star > 100][Bronze]
* [geom](https://github.com/skelterjohn/geom) - **Star : 40**  Go 的二维几何。![最近三个月没有更新][Yellow]
* [go-dsp](https://github.com/mjibson/go-dsp) - **Star : 623** Go数字信号处理。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-fn](https://github.com/ematvey/go-fn) - **Star : 11** 用Go语言编写的数学函数，不包括在math pkg中。![最近三个月没有更新][Yellow]
* [go-gt](https://github.com/ThePaw/go-gt) - **Star : 5** 用“Go”语言编写的图论算法。![最近三个月没有更新][Yellow]
* [gocomplex](https://github.com/varver/gocomplex) - **Star : 5** 用于 Go 编程语言的复数库。![最近三个月没有更新][Yellow]
* [goent](https://github.com/kzahedi/goent) - **Star : 13**  Go 实现熵度量。![最近三个月没有更新][Yellow]
* [gohistogram](https://github.com/VividCortex/gohistogram) - **Star : 126** 数据流的近似直方图。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gonum](https://github.com/gonum/gonum) - **Star : 2843** Gonum是一组用于Go编程语言的数字库。它包含用于矩阵、统计、优化等的库。![star > 1000][Silver]![最近一个周有更新][Green]
* [gonum/plot](https://github.com/gonum/plot) - **Star : 1180** gonum/plot提供了一个API，用于在Go中构建和绘制绘图。![star > 1000][Silver]
* [goraph](https://github.com/gyuho/goraph) - **Star : 597** 纯Go图论库(数据结构，算法可视化)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gosl](https://github.com/cpmech/gosl) - **Star : 1289** 提供线性代数，FFT，几何，NURBS，数值方法，概率，优化，微分方程，等等。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [GoStats](https://github.com/OGFris/GoStats) - **Star : 9** GoStats是一个开放源码的GoLang库，主要用于机器学习领域的数学统计，它涵盖了大多数统计度量函数。![最近三个月没有更新][Yellow]
* [graph](https://github.com/yourbasic/graph) - **Star : 225** 基本图形算法库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [ode](https://github.com/ChristopherRabotin/ode) - **Star : 10** 常微分方程(ODE)求解器，支持扩展状态和基于信道的迭代停止条件。![最近三个月没有更新][Yellow]
* [orb](https://github.com/paulmach/orb) - **Star : 184** 2D几何类型，支持剪切、GeoJSON和Mapbox矢量平铺。![star > 100][Bronze]
* [pagerank](https://github.com/alixaxel/pagerank) - **Star : 48** 加权 PageRank 算法在Go中的实现。
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - **Star : 5** 微型线性插值库。![最近三个月没有更新][Yellow]
* [PiHex](https://github.com/claygod/PiHex) - **Star : 9** 实现了针对16进制数 Pi 的“bailee - borwein - plouffe”算法。
* [rootfinding](https://github.com/khezen/rootfinding) - **Star : 3** 二次函数求根算法库。![最近三个月没有更新][Yellow]
* [sparse](https://github.com/james-bowman/sparse) - **Star : 65**  Go 稀疏矩阵格式的线性代数支持科学和机器学习应用程序，兼容gonum矩阵库。
* [stats](https://github.com/montanaflynn/stats) - **Star : 1330** 包含Golang标准库中缺少的公共函数的统计软件包。![star > 1000][Silver]
* [streamtools](https://github.com/nytlabs/streamtools) - **Star : 1315** 通用图形工具，用于处理数据流。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [TextRank](https://github.com/DavidBelicza/TextRank) - **Star : 65** TextRank在Golang中的实现，支持扩展特性(摘要、加权、短语提取)和多线程(goroutine)。![最近三个月没有更新][Yellow]
* [triangolatte](https://github.com/tchayen/triangolatte) - **Star : 11** 二维三角库。允许将线和多边形(都基于点)转换为gpu语言。

## 安全

*用于帮助您的应用程序更安全的库。*

* [acmetool](https://github.com/hlandau/acme) - **Star : 1690** ACME(让我们用自动更新加密)客户端工具。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [acra](https://github.com/cossacklabs/acra) - **Star : 441** 网络加密代理保护基于数据库的应用程序免受数据泄漏:强选择性加密，SQL注入预防，入侵检测系统。![star > 100][Bronze]
* [argon2pw](https://github.com/raja/argon2pw) - **Star : 72** 使用常量时间密码比较生成Argon2密码散列。![最近三个月没有更新][Yellow]
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - 让我们加密证书并启动TLS服务器。
* [BadActor](https://github.com/jaredfolkins/badactor) - **Star : 241** 一个驻留在内存中的，应用驱动的监控程序，受 fail2ban 的启发![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Cameradar](https://github.com/Ullaakut/cameradar) - **Star : 1772** 工具和库，以远程入侵RTSP流从监控摄像头。![star > 1000][Silver]![最近一个周有更新][Green]
* [certificates](https://github.com/mvmaasakkers/certificates) - **Star : 6** 用于生成tls证书的自定义工具。
* [go-yara](https://github.com/hillu/go-yara) - **Star : 132** YARA的 Go 语言接口，号称是 “对于恶意软件研究者（以及其他人）来说是模式匹配的瑞士军刀”![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goArgonPass](https://github.com/dwin/goArgonPass) - **Star : 10** Argon2密码散列和验证设计为与现有Python和PHP实现兼容。![最近三个月没有更新][Yellow]
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - **Star : 28** 一个安全哈希和加密密码的偏执包。![最近三个月没有更新][Yellow]
* [Interpol](https://bitbucket.org/vahidi/interpol) - 基于规则的数据生成器，用于模糊和渗透测试。
* [jwc](https://github.com/khezen/jwc) - **Star : 5** JSON Web加密库。![最近一个周有更新][Green]
* [lego](https://github.com/xenolf/lego) - **Star : 3418** 纯 Go ACME 客户端库及命令行工具![star > 1000][Silver]![最近一个周有更新][Green]
* [memguard](https://github.com/awnumar/memguard) - **Star : 995** 一个用于处理内存中敏感值的纯Go库。![star > 100][Bronze]![最近一个周有更新][Green]
* [nacl](https://github.com/kevinburke/nacl) - **Star : 450**  Go 实现NaCL API的集合。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [passlib](https://github.com/hlandau/passlib) - **Star : 224** 不过时的密码哈希库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [secure](https://github.com/unrolled/secure) - **Star : 1184** Go 语言 HTTP 中间件，为 Go 提供了一些安全功能![star > 1000][Silver]
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - **Star : 154** Scrypt 库，具有简单、易懂的 API，同时具有内置的自动校准功能![star > 100][Bronze]![最近一个周有更新][Green]
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - **Star : 194** 使用ssh密钥加密/解密。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [sslmgr](https://github.com/adrianosela/sslmgr) - **Star : 7** 使用围绕acme/autocert的高级包装器，SSL证书变得很容易。

## 序列化

*用于二进制序列化的库和工具。*

* [asn1](https://github.com/PromonLogicalis/asn1) - **Star : 39** 面向golang的BER和DER编码库。![最近三个月没有更新][Yellow]
* [bambam](https://github.com/glycerine/bambam) - **Star : 61** 用于 Go 语言生成 Cap'n Proto schemas 的生成器![最近三个月没有更新][Yellow]
* [bel](https://github.com/32leaves/bel) - **Star : 4** 从Go structs/interface生成TypeScript接口。对JSON RPC很有用。
* [binstruct](https://github.com/ghostiam/binstruct) - **Star : 7** 用于将数据映射到结构中的Golang二进制解码器。![最近三个月没有更新][Yellow]
* [colfer](https://github.com/pascaldekloe/colfer) - **Star : 469** 为Colfer二进制格式生成代码。![star > 100][Bronze]
* [csvutil](https://github.com/jszwec/csvutil) - **Star : 299** 高性能、惯用的CSV记录编码和解码到本机Go结构。![star > 100][Bronze]
* [fwencoder](https://github.com/o1egl/fwencoder) - **Star : 6** 用于Go的固定宽度文件解析器(编码和解码库)。![最近三个月没有更新][Yellow]
* [go-capnproto](https://github.com/glycerine/go-capnproto) - **Star : 273** Go 语言用的 Cap'n Proto 库及解析器![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-codec](https://github.com/ugorji/go) - **Star : 1206** 高性能、多功能、规范化编码解码以及 rpc 库， 用于 msgpack, cbor 和 json，支持基于运行时的 OR 码生成![star > 1000][Silver]![最近一个周有更新][Green]
* [gogoprotobuf](https://github.com/gogo/protobuf) - **Star : 2828** Go 语言的 Protocol Buffer 库。![star > 1000][Silver]
* [goprotobuf](https://github.com/golang/protobuf) - **Star : 4847** 通过库和协议编译器插件使 Go 语言支持 Google的 protocol buffers.![star > 1000][Silver]![最近一个周有更新][Green]
* [jsoniter](https://github.com/json-iterator/go) - **Star : 5255** 高性能，100% 兼容的“encoding/json” 替代品![star > 5000][Gold]
* [mapstructure](https://github.com/mitchellh/mapstructure) - **Star : 2315** 用于对原生键值对进行解码生成 Go 语言结构体![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - **Star : 118** 用于协同 PHP session 格式数据和 PHP 序列化／反序列化函数工作的go语言库![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [structomap](https://github.com/tuvistavie/structomap) - **Star : 91** 用于从静态结构体简单、动态的生成键值对的库

## 服务器应用程序

* [algernon](https://github.com/xyproto/algernon) - **Star : 1572** 内置支持Lua、Markdown、GCSS和Amber的HTTP/2 web服务器。![star > 1000][Silver]
* [Caddy](https://github.com/mholt/caddy) - **Star : 22470** Caddy是另一种HTTP/2 web服务器，易于配置和使用。![star > 5000][Gold]![最近一个周有更新][Green]
* [consul](https://www.consul.io/) - Consul 是一个用于服务发现、监控和配置的工具
* [devd](https://github.com/cortesi/devd) - **Star : 2781** 为开发人员提供本地web服务器。![star > 1000][Silver]![最近一个周有更新][Green]
* [discovery](https://github.com/Bilibili/discovery) - **Star : 624** 用于弹性中间层负载平衡和故障转移的注册表。![star > 100][Bronze]
* [etcd](https://github.com/coreos/etcd) - **Star : 25734** 为共享配置和服务发现提供高可用的键值存储。![star > 5000][Gold]![最近一个周有更新][Green]
* [Fider](https://github.com/getfider/fider) - **Star : 767** Fider是一个收集和组织客户反馈的开放平台。![star > 100][Bronze]
* [Flagr](https://github.com/checkr/flagr) - **Star : 779** Flagr是一个开源特性标记和A/B测试服务。![star > 100][Bronze]![最近一个周有更新][Green]
* [flipt](https://github.com/markphelps/flipt) - **Star : 974** 一个用Go和Vue.js编写的自包含特性标志解决方案![star > 100][Bronze]![最近一个周有更新][Green]
* [jackal](https://github.com/ortuman/jackal) - **Star : 704** 用Go编写的XMPP服务器。![star > 100][Bronze]
* [minio](https://github.com/minio/minio) - **Star : 16807** Minio是一个分布式对象存储服务器。![star > 5000][Gold]![最近一个周有更新][Green]
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - **Star : 5** Nginx日志解析器和Prometheus 导出。
* [nsq](http://nsq.io/) - 一个实时分布式消息平台。
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) - **Star : 4** 从PostgreSQL到Kafka的流数据库事件。
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) - 传递到负载平衡Riemann事件并/或将其转换为 Carbon。
* [RoadRunner](https://github.com/spiral/roadrunner) - **Star : 3128** 高性能PHP应用服务器，负载平衡器和进程管理器。![star > 1000][Silver]![最近一个周有更新][Green]
* [yakvs](https://git.sci4me.com/sci4me/yakvs) - 小型化、网络化、基于内存的键值存储

## 模板引擎

*用于模板和词法分析的库和工具。*

* [ace](https://github.com/yosssi/ace) - **Star : 761** Ace 是一个 Go 语言的 HTML 模板引擎，受到了 Slim 和 Jade 的启发。 Ace 是对Gold的一种改进。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [amber](https://github.com/eknkc/amber) - **Star : 821** Amber是一个优雅的Go编程语言模板引擎，它的灵感来自HAML和Jade。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [damsel](https://github.com/dskinner/damsel) - **Star : 20** 标记语言，通过css选择器实现了 html 框架 ，并可以通过 pkg html/template 等进行扩展![最近三个月没有更新][Yellow]
* [ego](https://github.com/benbjohnson/ego) - **Star : 409** 轻量级模板语言，允许您在Go中编写模板。模板被翻译成Go并编译。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [extemplate](https://github.com/dannyvankooten/extemplate) - **Star : 12**  对 html/template 进行了简单的封装，支持基于文件的模板可以利用其他模板文件进行扩展![最近三个月没有更新][Yellow]
* [fasttemplate](https://github.com/valyala/fasttemplate) - **Star : 287** 简单快速的模板引擎。进行模板元素替换时，速度是比[text/template](http://golang.org/pkg/text/template/)快10倍。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gofpdf](https://github.com/jung-kurt/gofpdf) - **Star : 2996** PDF 文档生成器，支持文本，绘图和图片![star > 1000][Silver]
* [goview](https://github.com/foolin/goview) - **Star : 38** Goview是一个轻量级、极简的模板库，基于golang html/template构建Go web应用程序。
* [hero](https://github.com/shiyanhui/hero) - **Star : 1192** Hero是一个方便、快速和强大的go模板引擎。![star > 1000][Silver]
* [jet](https://github.com/CloudyKit/jet) - **Star : 576** Jet模板引擎。![star > 100][Bronze]
* [kasia.go](https://github.com/ziutek/kasia.go) - **Star : 70** 一个用于HTML 和其他文本文件的模板系统，使用go语言实现![最近三个月没有更新][Yellow]
* [liquid](https://github.com/osteele/liquid) - **Star : 80** Go 语言实现的 Shopify Liquid 模板.
* [mustache](https://github.com/hoisie/mustache) - **Star : 964** Go 语言实现的 Mustache 模板语言![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [pongo2](https://github.com/flosch/pongo2) - **Star : 1478** 类似 DjanGo 的模板引擎![star > 1000][Silver]
* [quicktemplate](https://github.com/valyala/quicktemplate) - **Star : 1357** 快速、强大且易用的模板引擎。将模板转化为 Go 语言并进行编译![star > 1000][Silver]
* [raymond](https://github.com/aymerick/raymond) - **Star : 335** 使用 Go 语言实现的完整的 handlebars![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Razor](https://github.com/sipin/gorazor) - **Star : 670** Go 语言的 Razor 视图引擎![star > 100][Bronze]
* [Soy](https://github.com/robfig/soy) - **Star : 143** Go 语言实现的谷歌闭包模板(也就是 Soy templates) ,遵循[官方规范](https://developer.google.com/closure/templates/)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [velvet](https://github.com/gobuffalo/velvet) - **Star : 65** 使用 Go 语言实现的完整的 handlebars![最近三个月没有更新][Yellow]

## 测试

*用于测试代码库和生成测试数据的库。*

* Testing Frameworks
    * [assert](https://github.com/go-playground/assert) - **Star : 13** 基础断言库，用于对 Go 语言程序进行测试，提供了一些用于自定义断言的代码块![最近三个月没有更新][Yellow]
    * [badio](https://github.com/cavaliercoder/badio) - **Star : 8** Go 语言 testing/iotest 包的扩展。![最近三个月没有更新][Yellow]
    * [baloo](https://github.com/h2non/baloo) - **Star : 634** 表达性强、多功能的、端到端的HTTP API 测试工具![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [biff](https://github.com/fulldump/biff) - **Star : 6** 分支测试框架，BDD兼容。![最近三个月没有更新][Yellow]
    * [bro](https://github.com/marioidival/bro) - **Star : 26** 监控目录中的文件并对其进行测试![最近三个月没有更新][Yellow]
    * [charlatan](https://github.com/percolate/charlatan) - **Star : 188** 为测试生成假接口实现的工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [commander](https://github.com/SimonBaeumer/commander) - **Star : 31** 用于在windows、linux和osx上测试cli应用程序的工具。
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - **Star : 77** 测试框架的简单快照测试插件。![最近三个月没有更新][Yellow]
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - **Star : 79** 清空数据库用于测试，受到database_cleaner 的启发
    * [dsunit](https://github.com/viant/dsunit) - **Star : 24** 用于SQL、NoSQL、结构化文件的数据存储测试。![最近一个周有更新][Green]
    * [endly](https://github.com/viant/endly) - **Star : 83** 声明性端到端功能测试。
    * [frisby](https://github.com/verdverm/frisby) - **Star : 246** REST API测试框架。![star > 100][Bronze]
    * [ginkgo](http://onsi.github.io/ginkgo/) - Go的BDD测试框架。
    * [go-carpet](https://github.com/msoap/go-carpet) - **Star : 195** 在终端中查看测试覆盖率的工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [go-cmp](https://github.com/google/go-cmp) - **Star : 1084** 用于比较测试中的Go值的包。![star > 1000][Silver]
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - **Star : 244** 变异测试的Go源代码。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [go-testdeep](https://github.com/maxatome/go-testdeep) - **Star : 49** 极具灵活性的golang深度比较，扩展了go测试包。
    * [go-vcr](https://github.com/dnaeon/go-vcr) - **Star : 325** 记录并回放HTTP交互，以便进行快速、确定和准确的测试。![star > 100][Bronze]![最近一个周有更新][Green]
    * [goblin](https://github.com/franela/goblin) - **Star : 613** 类似Mocha的测试框架。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [gocheck](http://labix.org/gocheck) - 更加高级的测试框架，用于替换 Gotest
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD 风格的测试框架，具有 web 界面和计时刷新功能
    * [gocrest](https://github.com/corbym/gocrest) - **Star : 8** 用于 Go 断言的可组合的类似 hamcrest 的 matchers。![最近三个月没有更新][Yellow]
    * [godog](https://github.com/DATA-DOG/godog) - **Star : 716** 类似 Cucumber 或 Behat 的 BDD 框架![star > 100][Bronze]
    * [gofight](https://github.com/appleboy/gofight) - **Star : 252** 对 Go 语言的路由框架进行 API 测试![star > 100][Bronze]
    * [gogiven](https://github.com/corbym/gogiven) - **Star : 7** 类似于 YATSPEC 的Go BDD测试框架。![最近三个月没有更新][Yellow]
    * [gomatch](https://github.com/jfilipczyk/gomatch) - **Star : 29** 为针对模式测试JSON而创建的库。![最近三个月没有更新][Yellow]
    * [gomega](http://onsi.github.io/gomega/) - 类似 Rspec 的 matcher/assertion 库
    * [GoSpec](https://github.com/orfjackal/gospec) - **Star : 111** 用于 Go 编程语言的bdd风格的测试框架。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [gospecify](https://github.com/stesla/gospecify) - **Star : 51** 支持 BDD 语法 。对于任何使用过 rspec 等库的人来说应该非常熟悉。![最近三个月没有更新][Yellow]
    * [gosuite](https://github.com/pavlo/gosuite) - **Star : 9** 轻量级测试套，为 Go1.7's Subtests 带来了setup/teardown 功能![最近三个月没有更新][Yellow]
    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) - **Star : 112** 一组包，用于增强go测试包并支持公共模式。![star > 100][Bronze]![最近一个周有更新][Green]
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - **Star : 26** 用于声明性 Matcher 对象的连贯框架，当将其应用于输入值时，将产生自描述结果。![最近三个月没有更新][Yellow]
    * [httpexpect](https://github.com/gavv/httpexpect) - **Star : 1103** 简洁的、声明式的、易用的端到端HTTP 及 REST API 测试![star > 1000][Silver]
    * [jsonassert](https://github.com/kinbiko/jsonassert) - **Star : 20** 用于验证JSON有效负载已正确序列化的包。![最近一个周有更新][Green]
    * [restit](https://github.com/yookoala/restit) - **Star : 48** 帮助编写 RESTful API 集成测试的 Go 语言微型框架.。![最近三个月没有更新][Yellow]
    * [testcase](https://github.com/adamluzsi/testcase) - **Star : 9** 行为驱动开发的惯用测试框架。
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - **Star : 314** 类似 Rails 的测试工具，用于测试数据库应用![star > 100][Bronze]
    * [Testify](https://github.com/stretchr/testify) - **Star : 7771** 对标准测试包的扩展。![star > 5000][Gold]
    * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - 将markdown代码段转换为可测试的go代码。
    * [testsql](https://github.com/zhulongcheng/testsql) - **Star : 7** 在测试前从SQL文件生成测试数据，并在测试完成后清除数据。
    * [Tt](https://github.com/vcaesar/tt) - **Star : 5** 简单而丰富多彩的测试工具。
    * [wstest](https://github.com/posener/wstest) - **Star : 62** 用于单元测试Websocket http.Handler的Websocket客户机。![最近三个月没有更新][Yellow]

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - **Star : 353** 用于生成自包含 mock 对象的工具![star > 100][Bronze]![最近一个周有更新][Green]
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - **Star : 1623** Mock SQL ，用于测试数据库交互![star > 1000][Silver]
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - **Star : 154** 基于单事务的数据库驱动，主要用于测试目的![star > 100][Bronze]
    * [gock](https://github.com/h2non/gock) - **Star : 786** 多功能、易用 HTTP mock![star > 100][Bronze]
    * [gomock](https://github.com/golang/mock) - **Star : 2668** 用于Go编程语言的mock框架。![star > 1000][Silver]
    * [govcr](https://github.com/seborama/govcr) - **Star : 78** HTTP mock : 离线测试时记录和重放浏览器的动作
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - **Star : 1407** 使用可扩展中间件和易于使用的CLI记录和模拟REST/SOAP api的HTTP(S)代理。![star > 1000][Silver]![最近一个周有更新][Green]
    * [httpmock](https://github.com/jarcoal/httpmock) - **Star : 555** 轻松模拟来自外部资源的HTTP响应。![star > 100][Bronze]
    * [minimock](https://github.com/gojuno/minimock) - **Star : 193** Go接口的模拟生成器。![star > 100][Bronze]
    * [mockhttp](https://github.com/tv42/mockhttp) - **Star : 22** Go http.ResponseWriter的模拟对象。![最近三个月没有更新][Yellow]

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - **Star : 2836** 随机测试系统。![star > 1000][Silver]
    * [gofuzz](https://github.com/google/gofuzz) - **Star : 518** 用于生成随机值来初始化 Go 语言对象的库![star > 100][Bronze]
    * [Tavor](https://github.com/zimmski/tavor) - **Star : 208** 通用模糊测试框架![star > 100][Bronze]![最近三个月没有更新][Yellow]

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - **Star : 343** 用于Chrome调试协议的类型安全绑定，可与实现该协议的浏览器或其他调试目标一起使用。![star > 100][Bronze]
    * [chromedp](https://github.com/knq/chromedp) - **Star : 3384** 用于驱动和测试 Chrome, Safari, Edge, Android Webviews, 以及其他支持 Chrome 调试协议的产品![star > 1000][Silver]![最近一个周有更新][Green]
    * [ggr](https://github.com/aerokube/ggr) - **Star : 208** 一个轻量级服务器，可以将 Selenium Wedriver 的请求路由或代理到多个 Selenium hubs![star > 100][Bronze]
    * [selenoid](https://github.com/aerokube/selenoid) - **Star : 1174** Selenium hub 服务器的替代品，在容器中启动浏览器![star > 1000][Silver]

* Fail injection
    * [failpoint](https://github.com/pingcap/failpoint) - **Star : 365** 为Golang实现[failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail)。![star > 100][Bronze]![最近一个周有更新][Green]

## 文本处理

*用于解析和操作文本的库。*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - **Star : 57** 对文本进行对齐的通用应用程序。![最近三个月没有更新][Yellow]
    * [allot](https://github.com/sbstjn/allot) - **Star : 33** 用于CLI工具和机器人的占位符和通配符文本解析。
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - **Star : 5** 将bbCode转换为HTML，使您可以添加对自定义bbCode标记的支持。![最近三个月没有更新][Yellow]
    * [blackfriday](https://github.com/russross/blackfriday) - **Star : 3795** Markdown 解析器![star > 1000][Silver]![最近一个周有更新][Green]
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - **Star : 1212** HTML 清理工具![star > 1000][Silver]![最近三个月没有更新][Yellow]
    * [codetree](https://github.com/aerogo/codetree) - **Star : 6** 解析缩进代码(python、pixy、scarlet等)并返回树结构。
    * [colly](https://github.com/asciimoo/colly) - **Star : 8050** 快速和优雅的 Scraping 框架。![star > 5000][Gold]
    * [commonregex](https://github.com/mingrammer/commonregex) - **Star : 545** 一组用于Go的公共正则表达式。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [dataflowkit](https://github.com/slotix/dataflowkit) - **Star : 276** Web抓取框架将网站转换为结构化数据。![star > 100][Bronze]
    * [did](https://github.com/ockam-network/did) - **Star : 21** DID(分散标识符)解析器和Stringer。
    * [doi](https://github.com/hscells/doi) - **Star : 4** 文档对象标识符(doi)解析器。![最近三个月没有更新][Yellow]
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - **Star : 37** Editorconfig文件解析器和Go操作器。
    * [enca](https://github.com/endeveit/enca) - **Star : 7** [libenca](http://cihar.com/software/enca/)的最小cgo绑定。![最近三个月没有更新][Yellow]
    * [encdec](https://github.com/mickep76/encdec) - **Star : 3** 软件包为编码器和解码器提供了通用接口。![最近三个月没有更新][Yellow]
    * [genex](https://github.com/alixaxel/genex) - **Star : 50** 将正则表达式计数并展开为所有匹配的字符串。
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub 风格的 Markdown 渲染器 (使用 blackfriday) ，支持代码块高亮以及可点击的锚点
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - **Star : 21** 固定宽度的文本格式(带反射的编码器/解码器)。![最近一个周有更新][Green]
    * [go-humanize](https://github.com/dustin/go-humanize) - **Star : 1847** 格式化程序，用于将时间、数字和内存大小转换为可读格式。![star > 1000][Silver]![最近三个月没有更新][Yellow]
    * [go-nmea](https://github.com/adrianmo/go-nmea) - **Star : 90** 用于Go语言的NMEA解析器库。
    * [go-runewidth](https://github.com/mattn/go-runewidth) - **Star : 207** 函数获取字符或字符串的固定宽度。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [go-slugify](https://github.com/mozillazg/go-slugify) - **Star : 27** 生成漂亮的固定链接地址（slug），支持多种语言![最近三个月没有更新][Yellow]
    * [go-toml](https://github.com/pelletier/go-toml) - **Star : 588** 使用带有查询支持和方便的cli工具的TOML格式库。![star > 100][Bronze]
    * [go-vcard](https://github.com/emersion/go-vcard) - **Star : 23** 解析和格式化vCard。
    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) - **Star : 41** 用于Go的零宽度字符检测和删除。
    * [gofeed](https://github.com/mmcdole/gofeed) - **Star : 1077** 在Go中解析RSS和Atom feeds。![star > 1000][Silver]
    * [gographviz](https://github.com/awalterschulze/gographviz) - **Star : 284** 解析Graphviz DOT语言。![star > 100][Bronze]
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - 格式化二进制为字符串。
    * [gonameparts](https://github.com/polera/gonameparts) - **Star : 30** 将人名解析为单独的名称部分。![最近三个月没有更新][Yellow]
    * [goq](https://github.com/andrewstuart/goq) - **Star : 141**  声明式 HTML 编组，使用结构标签和 jQuery 语法 (使用 GoQuery).![star > 100][Bronze]
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - **Star : 7412** GoQuery 为 Go 语言带来了一组类似 jQuery 的语法和功能![star > 5000][Gold]
    * [goregen](https://github.com/zach-klippenstein/goregen) - **Star : 35** 根据正则表达式生成随机字符串![最近三个月没有更新][Yellow]
    * [gotext](https://github.com/leonelquinteros/gotext) - **Star : 228** GNU gettext 工具![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - **Star : 44** 通过一个 unicode 文本来猜测该文本使用的语言![最近三个月没有更新][Yellow]
    * [htmlquery](https://github.com/antchfx/htmlquery) - **Star : 115** 用于HTML的XPath查询包，允许您通过XPath表达式从HTML文档中提取数据或求值。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [inject](https://github.com/facebookgo/inject) - **Star : 1129** 包注入提供了一个基于反射的注入器。![star > 1000][Silver]![最近三个月没有更新][Yellow]
    * [ltsv](https://github.com/Wing924/ltsv) - **Star : 2** 用于Go的高性能[LTSV(标签为Tab Separeted Value)](http://ltsv.org/)阅读器。
    * [mxj](https://github.com/clbanning/mxj) - **Star : 323** 将XML编码/解码为JSON或map[string]接口{};使用点符号路径和通配符提取值。替换x2j和j2x包。![star > 100][Bronze]
    * [sdp](https://github.com/gortc/sdp) - **Star : 66** SDP:会话描述协议[[RFC 4566](https://tools.ietf.org/html/rfc4566)]。![最近三个月没有更新][Yellow]
    * [sh](https://github.com/mvdan/sh) - **Star : 1915** Shell解析器和格式化工具。![star > 1000][Silver]![最近一个周有更新][Green]
    * [slug](https://github.com/gosimple/slug) - **Star : 365** URL 友好的 slug 化工具，支持多种语言![star > 100][Bronze]
    * [Slugify](https://github.com/avelino/slugify) - **Star : 26** 字符串 slug 化的工具。![最近三个月没有更新][Yellow]
    * [syndfeed](https://github.com/zhengchun/syndfeed) - **Star : 4** Atom 1.0和RSS 2.0的联合提要。![最近三个月没有更新][Yellow]
    * [toml](https://github.com/BurntSushi/toml) - **Star : 2707** TOML配置格式(带反射的编码器/解码器)。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* Utility
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - **Star : 15** 一个基于 sanitization 的 Go 敏感词过滤器。![最近三个月没有更新][Yellow]
    * [gotabulate](https://github.com/bndr/gotabulate) - **Star : 198** 使用 Go 语言简单、美观的打印表格数据![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [kace](https://github.com/codemodus/kace) - **Star : 12** 通用大小写转换工具![最近三个月没有更新][Yellow]
    * [parseargs-go](https://github.com/nproc/parseargs-go) - **Star : 5** 字符串参数解析器，能够理解引用及反斜杠。![最近三个月没有更新][Yellow]
    * [parth](https://github.com/codemodus/parth) - **Star : 31** URL路径分割解析。![最近三个月没有更新][Yellow]
    * [radix](https://github.com/yourbasic/radix) - **Star : 141** 快速字符串排序算法。![star > 100][Bronze]![最近三个月没有更新][Yellow]
    * [Tagify](https://github.com/zoomio/tagify) - 从给定源生成一组标记。
    * [TySug](https://github.com/Dynom/TySug) - **Star : 3** 关于键盘布局的其他建议。
    * [xj2go](https://github.com/stackerzzq/xj2go) - **Star : 17** 将xml或json转换为struct。![最近三个月没有更新][Yellow]
    * [xurls](https://github.com/mvdan/xurls) - **Star : 454** 从文本中提取url。![star > 100][Bronze]

## 第三方api

*用于访问第三方api的库。*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - **Star : 39** 使用[Amazon Product Advertising API]的客户端库(https://program.amazon.com/gp/advertising /api/detail/main.html)。![最近三个月没有更新][Yellow]
* [anaconda](https://github.com/ChimeraCoder/anaconda) - **Star : 983**  Twitter 1.1 API 的 go 语言客户端![star > 100][Bronze]
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - **Star : 4917** AWS 提供的官方go语言 SDK![star > 1000][Silver]![最近一个周有更新][Green]
* [brewerydb](https://github.com/naegelejd/brewerydb) - **Star : 16** 用于访问 BreweryDB API的 Go 语言库![最近三个月没有更新][Yellow]
* [cachet](https://github.com/andygrunwald/cachet) - **Star : 65** 使用客户端库[Cachet(开源状态页系统)](https://cachethq.io/)。![最近三个月没有更新][Yellow]
* [circleci](https://github.com/jszwedko/go-circleci) - **Star : 41** CircleCI的API的客户端![最近一个周有更新][Green]
* [clarifai](https://github.com/samuelcouch/clarifai) - **Star : 57** Clarifai API的客户端。![最近三个月没有更新][Yellow]
* [codeship-go](https://github.com/codeship/codeship-go) - **Star : 14**  Codeship API v2的客户端。
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - **Star : 10** Coinpaprika API的客户端。![最近三个月没有更新][Yellow]
* [discordgo](https://github.com/bwmarrin/discordgo) - **Star : 930**  Discord Chat API的客户端。![star > 100][Bronze]![最近一个周有更新][Green]
* [ethrpc](https://github.com/onrik/ethrpc) - **Star : 164**  Ethereum JSON RPC API的客户端。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [facebook](https://github.com/huandu/facebook) - **Star : 764** 支持 Facebook Graph API 的库![star > 100][Bronze]
* [fcm](https://github.com/maddevsio/fcm) - **Star : 33**  Firebase Cloud Messaging 的 Go 语言库![最近三个月没有更新][Yellow]
* [gads](https://github.com/emiddleton/gads) - **Star : 44**  Google Adwords 非官方 API
* [gami](https://github.com/bit4bit/gami) - **Star : 26**  Asterisk Manager Interface 的 Go 语言库![最近三个月没有更新][Yellow]
* [gcm](https://github.com/Aorioli/gcm) - **Star : 30**  Google Cloud Messaging 库![最近三个月没有更新][Yellow]
* [geo-golang](https://github.com/codingsince1985/geo-golang) - **Star : 300** 访问谷歌地图(https://developers.google.com/maps/documentation/geocoding/intro), (MapQuest) (http://open.mapquestapi.com/geocoding/), (Nominatim) (https://developer.mapquest.com/documentation/open/nominatim-search), (OpenCage) (http://geocoder.opencagedata.com/api.html), (Bing) (https://msdn.microsoft.com/en-us/library/ff701715.aspx), (Mapbox) (https://www.mapbox.com/developers/api/geocoding/),以及[OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding api 的库![star > 100][Bronze]
* [github](https://github.com/google/go-github) - **Star : 4676** 访问GitHub REST API v3的库。![star > 1000][Silver]![最近一个周有更新][Green]
* [githubql](https://github.com/shurcooL/githubql) - **Star : 479** 访问GitHub GraphQL API v4的库。![star > 100][Bronze]
* [go-chronos](https://github.com/axelspringer/go-chronos) - **Star : 3** 用于与[Chronos](https://mesos.github.io/chronos/)作业调度程序进行交互的Go库![最近三个月没有更新][Yellow]
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - **Star : 9** HackerNews API的小型Go客户端。![最近三个月没有更新][Yellow]
* [go-imgur](https://github.com/koffeinsource/go-imgur) - **Star : 12**  Go [imgur]的客户端库(https://imgur.com)![最近三个月没有更新][Yellow]
* [go-jira](https://github.com/andygrunwald/go-jira) - **Star : 549**  Go [Atlassian JIRA]的客户端库(https://www.atlassian.com/software/jira)![star > 100][Bronze]
* [go-marathon](https://github.com/gambol99/go-marathon) - **Star : 188**  用于和 Mesosphere's Marathon PAAS 交互的 Go 语言库![star > 100][Bronze]
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - **Star : 16** 访问[MyAnimeList API]的客户端库(http://myanimelist.net/modules.php?go=api)。![最近三个月没有更新][Yellow]
* [go-sophos](https://github.com/esurdam/go-sophos) - **Star : 5** 为[Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/pdfs/documentation/utmonaws/sophos-ut-restful-api.pdf?![最近三个月没有更新][Yellow]
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - **Star : 8**  SPTrans Olho Vivo API 的客户端。![最近三个月没有更新][Yellow]
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph 发布平台 API 客户端。
* [go-trending](https://github.com/andygrunwald/go-trending) - **Star : 99** 在Github上访问[trends repository](https://github.com/trends)和[developers](https://github.com/trending/developers)的库。
* [go-twitch](https://github.com/knspriggs/go-twitch) - **Star : 16**  Twitch v3 API 的客户端。![最近三个月没有更新][Yellow]
* [go-twitter](https://github.com/dghubble/go-twitter) - **Star : 688**  Twitter v1.1 api 的客户端。。![star > 100][Bronze]
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - **Star : 20** 使用[Unsplash.com](https://unsplash.com) API的客户端库。![最近三个月没有更新][Yellow]
* [go-xkcd](https://github.com/nishanths/go-xkcd) - **Star : 37**  xkcd API 的客户端。![最近三个月没有更新][Yellow]
* [golyrics](https://github.com/mamal72/golyrics) - **Star : 29** Golyrics是一个从Wikia网站获取音乐歌词数据的Go库。![最近三个月没有更新][Yellow]
* [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](http://www.malshare.com/)
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - **Star : 36**  Go MusicBrainz WS2客户端库。![最近三个月没有更新][Yellow]
* [google](https://github.com/google/google-api-go-client) - **Star : 1890** 为Go自动生成谷歌api。![star > 1000][Silver]![最近一个周有更新][Green]
* [google-analytics](https://github.com/chonthu/go-google-analytics) - **Star : 12** 简单的包装，方便的谷歌分析报告。![最近三个月没有更新][Yellow]
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - **Star : 1722** 谷歌云api Go 客户端库。![star > 1000][Silver]![最近一个周有更新][Green]
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - **Star : 6** [谷歌G Suite Email Audit API](https://developer.google.com/admin-sdk/email-audit/) 的客户端。![最近三个月没有更新][Yellow]
* [gostorm](https://github.com/jsgilmore/gostorm) - **Star : 119** GoStorm是一个Go库，它实现了编写Storm spout和bolt所需的通信协议，这些协议用于与Storm shell通信。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [hipchat](https://github.com/andybons/hipchat) - **Star : 109** 这个项目为Hipchat API实现了一个golang客户端库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - **Star : 114** 一个用于通过XMPP与HipChat通信的golang包。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [igdb](https://github.com/Henry-Sarabia/igdb) - **Star : 52** [Internet Game Database API](https://api.igdb.com/) 客户端。
* [Medium](https://github.com/Medium/medium-sdk-go) - **Star : 116** Medium的OAuth2 API 客户端。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [megos](https://github.com/andygrunwald/megos) - **Star : 57** 用于访问[Apache Mesos](http://mesos.apache.org/)集群的客户端库。![最近三个月没有更新][Yellow]
* [minio-go](https://github.com/minio/minio-go) - **Star : 704** 用于Amazon S3兼容云存储的Minio Go库。![star > 100][Bronze]![最近一个周有更新][Green]
* [mixpanel](https://github.com/dukex/mixpanel) - **Star : 28** Mixpanel是一个库，用于跟踪事件并将Mixpanel概要文件更新从go应用程序发送到Mixpanel。![最近三个月没有更新][Yellow]
* [patreon-go](https://github.com/mxpv/patreon-go) - **Star : 16**  Go Patreon API库。![最近三个月没有更新][Yellow]
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) - **Star : 296** PayPal支付API的包装器。![star > 100][Bronze]![最近一个周有更新][Green]
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - **Star : 1** Playlyfe Rest API Go SDK。![最近三个月没有更新][Yellow]
* [pushover](https://github.com/gregdel/pushover) - **Star : 57**  Go 包装的 Pushover API。![最近三个月没有更新][Yellow]
* [rrdaclient](https://github.com/Omie/rrdaclient) - **Star : 8** 用于接入 statdns.com API 的库——RRDA API。通过HTTP协议进行 DNS查询。![最近三个月没有更新][Yellow]
* [shopify](https://github.com/rapito/go-shopify) - **Star : 20** 一个用于通过 Shopify API 进行增删改查的 Go 语言库。![最近三个月没有更新][Yellow]
* [simples3](https://github.com/rhnvrm/simples3) - **Star : 9** 使用REST和用Go编写的V4签名的AWS S3库非常简单。![最近三个月没有更新][Yellow]
* [slack](https://github.com/nlopes/slack) - **Star : 2338** Slack API。![star > 1000][Silver]
* [smite](https://github.com/sergiotapia/smitego) - **Star : 10** 对 Smite game API 的封装。![最近三个月没有更新][Yellow]
* [spotify](https://github.com/rapito/go-spotify) - **Star : 16**  用于接入 Spotify WEB API 的 Go 语言库![最近三个月没有更新][Yellow]
* [steam](https://github.com/sostronk/go-steam) - **Star : 14**  用于与Steam服务器进行交互的库。![最近三个月没有更新][Yellow]
* [stripe](https://github.com/stripe/stripe-go) - **Star : 912**  Stripe API 的 Go 语言客户端![star > 100][Bronze]![最近一个周有更新][Green]
* [textbelt](https://github.com/dietsche/textbelt) - **Star : 14** textbelt.com txt messaging API 的go语言客户端。![最近三个月没有更新][Yellow]
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - **Star : 13** 简单的golang包与[themoviedb.org]通信(https://themoviedb.org)。![最近三个月没有更新][Yellow]
* [translate](https://github.com/poorny/translate) - **Star : 27**  Go 在线翻译包。![最近三个月没有更新][Yellow]
* [Trello](https://github.com/adlio/trello) - **Star : 97**  Trello API的 Go 语言封装。
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) -  TripAdvisor API 的 Go 语言封装。
* [tumblr](https://github.com/mattcunningham/gumblr) - **Star : 6**  Tumblr v2 API 的 Go 语言封装。![最近三个月没有更新][Yellow]
* [uptimerobot](https://github.com/bitfield/uptimerobot) - **Star : 34** 运行时Robot v2 API 的 Go 语言封装和命令行客户端。
* [webhooks](https://github.com/go-playground/webhooks) - **Star : 335** GitHub 和 Bitbucket 的Webhook接收器。![star > 100][Bronze]
* [wit-go](https://github.com/wit-ai/wit-go) - **Star : 44** wit.ai HTTP API 客户端。![最近一个周有更新][Green]
* [ynab](https://github.com/brunomvsouza/ynab.go) - **Star : 10**  YNAB API 的 Go 语言封装。![最近三个月没有更新][Yellow]
* [zooz](https://github.com/gojuno/go-zooz) - **Star : 5**  Zooz API 的 Go 语言客户端。![最近三个月没有更新][Yellow]

## 公用事业公司

*可以让你的生活变得更简单的实用工具.。*

* [abutil](https://github.com/bahlo/abutil) - **Star : 52** 常用 Go 语言工具的集合。![最近三个月没有更新][Yellow]
* [apm](https://github.com/topfreegames/apm) - **Star : 127** Go 语言进程管理工具具有HTTP API.。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [backscanner](https://github.com/icza/backscanner) - **Star : 8** 类似 bufio 的扫描器，但它以相反的顺序读取和返回行，从给定的位置开始，然后返回。![最近三个月没有更新][Yellow]
* [blank](https://github.com/Henry-Sarabia/blank) - **Star : 1** 验证或删除字符串中的空白。![最近三个月没有更新][Yellow]
* [boilr](https://github.com/tmrts/boilr) - **Star : 921** 非常快的CLI工具，用于从样板模板创建项目。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [chyle](https://github.com/antham/chyle) - **Star : 107** 使用具有多种配置可能性的git存储库生成变更日志。![star > 100][Bronze]![最近一个周有更新][Green]
* [circuit](https://github.com/cep21/circuit) - **Star : 315** 一个高效和功能齐全的 类似 Hystrix Go 实现断路器模式。![star > 100][Bronze]![最近一个周有更新][Green]
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - **Star : 776** 接通断路器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [clockwork](https://github.com/jonboulle/clockwork) - **Star : 217** 一个简单的假 clock 。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [command](https://github.com/txgruppi/command) - **Star : 9** 命令模式，支持线程安全的串行、并行调度。![最近三个月没有更新][Yellow]
* [copy-pasta](https://github.com/jutkko/copy-pasta) - **Star : 37** 通用多工作站剪切板，使用类似 S3 的后端作为存储。![最近三个月没有更新][Yellow]
* [ctop](https://github.com/bcicen/ctop) - **Star : 8626** [Top-like](http://ctop.sh)接口(例如htop)， 用于容器数据收集。![star > 5000][Gold]![最近一个周有更新][Green]
* [ctxutil](https://github.com/posener/ctxutil) - **Star : 6** 上下文工具。![最近三个月没有更新][Yellow]
* [dbt](https://github.com/nikogura/dbt) - **Star : 10** 用于从中心可信存储库运行自更新签名二进制文件的框架。
* [Death](https://github.com/vrecan/death) - **Star : 132** 利用信号管理应用程序的关闭。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Deepcopier](https://github.com/ulule/deepcopier) - **Star : 201** 结构体拷贝![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [delve](https://github.com/derekparker/delve) - **Star : 11684** Go 语言调试器![star > 5000][Gold]![最近一个周有更新][Green]
* [dlog](https://github.com/kirillDanshin/dlog) - **Star : 15** 编译时控制的日志，让你的 release 包变得更小而不需移除 debug 调用。![最近三个月没有更新][Yellow]
* [ergo](https://github.com/cristianoliveira/ergo) - **Star : 307** 管理运行在不同端口上的多个本地服务变得很容易。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [evaluator](https://github.com/nullne/evaluator) - **Star : 14** 基于 s-expression。它很简单，很容易扩展。![最近三个月没有更新][Yellow]
* [fastlz](https://github.com/digitalcrab/fastlz) - **Star : 11** [FastLz](http://fastlz.org/)(免费，开源，可移植实时压缩库) 的一个封装![最近三个月没有更新][Yellow]
* [filetype](https://github.com/h2non/filetype) - **Star : 923** 通过数字签名来推测文件类型。![star > 100][Bronze]
* [filler](https://github.com/yaronsumel/filler) - **Star : 14** 使用“fill”标签填充结构的小工具。![最近三个月没有更新][Yellow]
* [filter](https://github.com/gookit/filter) - **Star : 11** 提供Go数据的过滤、清理和转换。
* [fzf](https://github.com/junegunn/fzf) - **Star : 22371** 用Go编写的命令行模糊查找器。![star > 5000][Gold]
* [gaper](https://github.com/maxcnunes/gaper) - **Star : 37** 当Go项目崩溃或一些人看到文件更改时，构建并重新启动该项目。![最近三个月没有更新][Yellow]
* [generate](https://github.com/go-playground/generate) - **Star : 19** 针对一个路径或环境变量，递归的执行 Go generate，可以通过正则表达式来进行过滤。![最近三个月没有更新][Yellow]
* [ghokin](https://github.com/antham/ghokin) - **Star : 12** 没有外部依赖的gherkin (cucumber, behat…)并行格式化程序。
* [git-time-metric](https://github.com/git-time-metric/gtm) - **Star : 709** git-time-metric - 。![star > 100][Bronze]![最近一个周有更新][Green]
* [go-astitodo](https://github.com/asticode/go-astitodo) - **Star : 46** 解析你 Go 语言代码中的 TODOs（待办事项）。![最近三个月没有更新][Yellow]
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - **Star : 159** Go:generate 工具，用于构建 Go 语言插件(1.8 only)，并对导出的符号进行包装。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) - **Star : 79** 纯Go bsdiff和bspatch库和CLI工具。![最近三个月没有更新][Yellow]
* [go-dry](https://github.com/ungerik/go-dry) - **Star : 432** DRY(don't repeat yourself)库。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-funk](https://github.com/thoas/go-funk) - **Star : 997** 现代 Go 语言工具库，提供了很多有用的工具 (map, find, contains, filter, chunk, reverse, ...)![star > 100][Bronze]
* [go-health](https://github.com/Talento90/go-health) - **Star : 63** 健康包简化了向服务中添加健康检查的方式。![最近三个月没有更新][Yellow]
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - **Star : 14**  用于将结构体编码进 http 头的 Go 语言库![最近三个月没有更新][Yellow]
* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - **Star : 2** 打包处理问题细节。
* [go-rate](https://github.com/beefsack/go-rate) - **Star : 292**  Go 限速器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - **Star : 103** 用Go编写的XML站点地图生成器。![star > 100][Bronze]
* [go-torch](https://github.com/uber/go-torch) - **Star : 3624** 为 Go 语言程序生成火焰图。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [go-trigger](https://github.com/sadlil/go-trigger) - **Star : 181** Go 语言全局事件触发器，通过 id 和触发器，在程序的任何地方注册事件。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goback](https://github.com/carlescere/goback) - **Star : 39**  一个 Go 语言的简单的指数补偿包。![最近三个月没有更新][Yellow]
* [godaemon](https://github.com/VividCortex/godaemon) - **Star : 401** 用于编写守护进程的工具![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [godropbox](https://github.com/dropbox/godropbox) - **Star : 3730** 用于编写 Go 语言服务／应用的库，来自 Dropbox.。![star > 1000][Silver]
* [gohper](https://github.com/cosiner/gohper) - **Star : 248** 多种能够帮助你进行软件开发的工具和模块。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [golarm](https://github.com/msempere/golarm) - **Star : 34** 告警（支持系统事件）。![最近三个月没有更新][Yellow]
* [golog](https://github.com/mlimaloureiro/golog) - **Star : 43** 简单、轻量级的命令后工具，用于对你的计划任务进行跟踪。![最近三个月没有更新][Yellow]
* [gopencils](https://github.com/bndr/gopencils) - **Star : 423** 小而简单的包，可以轻松地使用REST api。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [goplaceholder](https://github.com/michiwend/goplaceholder) - **Star : 22** 一个小巧的 Go 语言库用于生成占位图片。![最近三个月没有更新][Yellow]
* [goreadability](https://github.com/philipjkim/goreadability) - **Star : 28** 网页摘要提取器使用Facebook开放图形和arc90的可读性。
* [goreleaser](https://github.com/goreleaser/goreleaser) - **Star : 4331** 尽可能快速的发布 Go 语言二进制文件。![star > 1000][Silver]![最近一个周有更新][Green]
* [goreporter](https://github.com/wgliang/goreporter) - **Star : 2457** 进行代码静态分析，单元测试，代码检视并生成代码质量报告的工具![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - **Star : 25** conseilSeaweedFS 客户端，几乎具有全部的特性。![最近三个月没有更新][Yellow]
* [gostrutils](https://github.com/ik5/gostrutils) - **Star : 14** 字符串操作和转换函数的集合。![最近三个月没有更新][Yellow]
* [gotenv](https://github.com/subosito/gotenv) - **Star : 136** 从 `.env` 或者任何 `io.Reader`。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gpath](https://github.com/tenntenn/gpath) - **Star : 25**  用于简化结构体域访问的库。![最近三个月没有更新][Yellow]
* [gubrak](https://github.com/novalagung/gubrak) - **Star : 127** 带有语法糖的Golang实用工具，就像lodash。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [handy](https://github.com/miguelpragier/handy) - **Star : 43** 许多实用程序和帮助程序，如字符串处理程序/格式化程序和验证器。
* [htcat](https://github.com/htcat/htcat) - **Star : 480** 并行及流水线的 HTTP GET 工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [hub](https://github.com/github/hub) - **Star : 16548** 封装了 git 命令，提供了额外的功能用于在终端中和 Github 进行交互。![star > 5000][Gold]![最近一个周有更新][Green]
* [hystrix-go](https://github.com/afex/hystrix-go) - **Star : 1943** 实现 Hystrix 风格的、程序员预定义的 fallback 机制（熔断。![star > 1000][Silver]
* [immortal](https://github.com/immortal/immortal) - **Star : 598** \*nix 跨平台 (与操作系统无关的)监控程序。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [intrinsic](https://github.com/mengzhuo/intrinsic) - **Star : 39** 不需要编写任何汇编代码就能使用 x86 SIMD。![最近三个月没有更新][Yellow]
* [jump](https://github.com/gsamokovarov/jump) - **Star : 639** 通过学习你的习惯，可以帮助你更快地导航。![star > 100][Bronze]
* [koazee](https://github.com/wesovilabs/koazee) - **Star : 276** 库的灵感来自于延迟计算和函数式编程，从而减少了使用数组的麻烦。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [lrserver](https://github.com/jaschaephraim/lrserver) - **Star : 99** LiveReload 服务器。![最近三个月没有更新][Yellow]
* [mc](https://github.com/minio/mc) - **Star : 1064** Minio Client 提供了一组工具，用于操作 Amazon S3 兼容云存储和文件系统。![star > 1000][Silver]![最近一个周有更新][Green]
* [mergo](https://github.com/imdario/mergo) - **Star : 821** 用于将结构体和map合并进 Go 语言的工具。对于配置默认值，避免杂乱的if语句很有帮助。![star > 100][Bronze]
* [mimemagic](https://github.com/zRedShift/mimemagic) - **Star : 43** 纯粹 Go 超性能MIME嗅探库/实用程序。![最近三个月没有更新][Yellow]
* [mimesniffer](https://github.com/aofei/mimesniffer) - **Star : 6** 一个用于Go的MIME类型嗅探器。
* [mimetype](https://github.com/gabriel-vasile/mimetype) - **Star : 98** 用于基于神奇数字的MIME类型检测的包。
* [minify](https://github.com/tdewolff/minify) - **Star : 1833** 用于HTML、CSS、JS、XML、JSON和SVG文件格式的快速缩小器。![star > 1000][Silver]
* [minquery](https://github.com/icza/minquery) - **Star : 50** MongoDB / mgo.v2, 支持高效分页查询(用于继续列出我们停止的文档的游标)。![最近三个月没有更新][Yellow]
* [mmake](https://github.com/tj/mmake) - **Star : 1450** 现代 Make 工具![star > 1000][Silver]
* [moldova](https://github.com/StabbyCutyou/moldova) - **Star : 148** 基于输入目标生成随机数据的工具![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [mole](https://github.com/davrodpin/mole) - **Star : 1290** cli应用程序可以轻松创建ssh隧道。![star > 1000][Silver]![最近一个周有更新][Green]
* [mssqlx](https://github.com/linxGnu/mssqlx) - **Star : 57** 数据库客户端，用于主-从 (或主-主) 数据库，集成了简单的、轻量级的轮询调度负载均衡。![最近三个月没有更新][Yellow]
* [multitick](https://github.com/VividCortex/multitick) - **Star : 58** 用于 aligned tickers 的多路复用![最近三个月没有更新][Yellow]
* [myhttp](https://github.com/inancgumus/myhttp) - **Star : 34** 简单的API，使HTTP GET请求与超时支持。![最近三个月没有更新][Yellow]
* [netbug](https://github.com/e-dard/netbug) - **Star : 65** 远程对你的服务进行性能分析![最近三个月没有更新][Yellow]
* [okrun](https://github.com/xta/okrun) - **Star : 14**  Go 运行错误 steamroller。![最近三个月没有更新][Yellow]
* [olaf](https://github.com/btnguyen2k/olaf) - **Star : 1** Twitter Snowflake 在Go中实现。
* [onecache](https://github.com/adelowo/onecache) - **Star : 98** 支持多个后端存储(Redis、Memcached、文件系统等)的缓存库。
* [panicparse](https://github.com/maruel/panicparse) - **Star : 2073** 将类似的协程分组并对调用栈进行着色![star > 1000][Silver]![最近一个周有更新][Green]
* [peco](https://github.com/peco/peco) - **Star : 5404** 简单的交互过滤工具。![star > 5000][Gold]
* [pgo](https://github.com/arthurkushman/pgo) - **Star : 23** 用于PHP社区的 Convenient 函数。
* [pm](https://github.com/VividCortex/pm) - **Star : 72** 进程(即goroutine)管理器与HTTP API。
* [profile](https://github.com/pkg/profile) - **Star : 977** Go的简单分析支持包。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [rclient](https://github.com/zpatrick/rclient) - **Star : 26** 可读、灵活、易于使用的REST api客户端。![最近三个月没有更新][Yellow]
* [realize](https://github.com/tockins/realize) - **Star : 3082** Go 语言构建系统，可以监控文件变化并重新加载。运行，构建，监控文件并支持自定义路径。![star > 1000][Silver]
* [repeat](https://github.com/ssgreg/repeat) - **Star : 56** 执行不同的后 backoff 策略，这对重新尝试操作和心跳非常有用。![最近三个月没有更新][Yellow]
* [request](https://github.com/mozillazg/request) - **Star : 353** Go 语言版的 HTTP Requests for Humans™.。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [rerate](https://github.com/abo/rerate) - **Star : 12** 基于 Redis 的速率计数器和限速器![最近三个月没有更新][Yellow]
* [rerun](https://github.com/ivpusic/rerun) - **Star : 153** 当源代码发生更改时，重新编译和重新运行go应用程序。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [resty](https://github.com/go-resty/resty) - **Star : 1811** 简单的 HTTP 和 REST 客户端，受到 Ruby rest-client 的启发。![star > 1000][Silver]
* [retry](https://github.com/kamilsk/retry) - **Star : 139** 基于上下文的功能机制，反复执行命令直到成功。![star > 100][Bronze]
* [retry](https://github.com/percolate/retry) - **Star : 2** 一个简单但高度可配置的Go重试包。![最近三个月没有更新][Yellow]
* [retry](https://github.com/thedevsaddam/retry) - **Star : 34** 简单易用的重试机制包，为 Go 。![最近三个月没有更新][Yellow]
* [retry](https://github.com/shafreeck/retry) - **Star : 9** 一个相当简单的库，以确保您的工作可以完成。![最近三个月没有更新][Yellow]
* [retry-go](https://github.com/rafaeljesus/retry-go) - **Star : 26** 对 Go 来说，重试变得简单而容易。![最近三个月没有更新][Yellow]
* [robustly](https://github.com/VividCortex/robustly) - **Star : 133** 有弹性的执行函数，遇到错误时捕获并重新运行。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [scan](https://github.com/blockloop/scan) - **Star : 11** 扫描golang的sql。行直接指向结构、片或基本类型。
* [serve](https://github.com/syntaqx/serve) - **Star : 190** 任何您需要的静态http服务器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [silk](https://github.com/chrispassas/silk) - **Star : 4** 阅读silk netflow文件。
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - **Star : 2** 基本类型之间的片转换。![最近三个月没有更新][Yellow]
* [slicer](https://github.com/leaanthony/slicer) - **Star : 3** 使处理切片更容易。![最近一个周有更新][Green]
* [spinner](https://github.com/briandowns/spinner) - **Star : 763**  一个 Go 语言软件包，提供多种选项，方便在终端中创建加载动画。![star > 100][Bronze]
* [sqlx](https://github.com/jmoiron/sqlx) - **Star : 6558** 为内建的数据库/sql 软件包提供一组扩展。![star > 5000][Gold]
* [sslice](https://github.com/yaa110/sslice) - **Star : 2** 创建一个总是排序的切片。![最近三个月没有更新][Yellow]
* [Storm](https://github.com/asdine/storm) - **Star : 1332** 一个简单又强大的用于 BoltDB 的工具![star > 1000][Silver]
* [structs](https://github.com/PumpkinSeed/structs) - **Star : 12** 简单来讲就是 "Make" 的替代品。![最近三个月没有更新][Yellow]
* [Task](https://github.com/go-task/task) - **Star : 1856** 简单的“Go”的选择。![star > 1000][Silver]![最近一个周有更新][Green]
* [toolbox](https://github.com/viant/toolbox) - **Star : 86** 切片, map, multimap, 结构体, 函数,数据转换工具。服务路由，宏求值和标记器。![最近一个周有更新][Green]
* [tracer](https://github.com/kamilsk/tracer) - **Star : 2** 简单、轻量级的跟踪。![最近一个周有更新][Green]
* [ugo](https://github.com/alxrm/ugo) - **Star : 20** uGo 是一个切片工具箱，有着和 Go 语言一致的语法法。![最近三个月没有更新][Yellow]
* [UNIS](https://github.com/esemplastic/unis) - **Star : 70** Go 语言字符串处理函数的通用架构 。![最近三个月没有更新][Yellow]
* [usql](https://github.com/knq/usql) - **Star : 4649** usql 是一个通用的命令行接口，用于操作 sql 数据库。![star > 1000][Silver]
* [util](https://github.com/shomali11/util) - **Star : 131** 有用实用函数的集合。(字符串，并发，操作，…)![star > 100][Bronze]
* [wuzz](https://github.com/asciimoo/wuzz) - **Star : 8190** 用于HTTP检查的交互式cli工具。![star > 5000][Gold]![最近三个月没有更新][Yellow]
* [xferspdy](https://github.com/monmohan/xferspdy) - **Star : 68** Xferspdy在golang中提供二进制diff和补丁库。![最近三个月没有更新][Yellow]

## UUID

*用于处理uuid的库。*

* [goid](https://github.com/jakehl/goid) - **Star : 20** 生成和解析RFC4122兼容的V4 uuid。![最近三个月没有更新][Yellow]
* [sno](https://github.com/muyo/sno) - **Star : 12** 使用嵌入元数据的紧凑、可排序和快速的惟一id。
* [ulid](https://github.com/oklog/ulid) - **Star : 1652** 实现了ULID(普遍唯一的词典分类标识符)。![star > 1000][Silver]
* [uuid](https://github.com/agext/uuid) - **Star : 10** 使用快速或加密质量的随机节点标识符生成、编码和解码UUIDs v1。![最近三个月没有更新][Yellow]
* [uuid](https://github.com/gofrs/uuid) - **Star : 547** 通用唯一标识符(UUID)的实现。支持uuid的创建和解析。积极维护satori uuid的fork。![star > 100][Bronze]
* [wuid](https://github.com/edwingeng/wuid) - **Star : 266** 一个非常快的唯一数字生成器，比UUID快10-135倍。![star > 100][Bronze]

## 验证

*库进行验证。*

* [checkdigit](https://github.com/osamingo/checkdigit) - **Star : 43** 提供校验数字算法(Luhn, Verhoeff, Damm)和计算器(ISBN, EAN, JAN, UPC等)。
* [govalidator](https://github.com/asaskevich/govalidator) - **Star : 3472** 用于字符串，数字，切片和结构的验证器和sanitizers。![star > 1000][Silver]
* [govalidator](https://github.com/thedevsaddam/govalidator) - **Star : 687** 用简单的规则验证Golang请求数据。深受Laravel请求验证的启发。![star > 100][Bronze]
* [jio](https://github.com/faceair/jio) - **Star : 21** jio是一个json模式验证器，类似于[joi](https://github.com/hapijs/joi)。
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - **Star : 1006** 支持各种数据类型(结构、字符串、映射、片等)的验证，使用可配置和可扩展的验证规则，这些规则在通常的代码构造中指定，而不是在结构标签中指定。![star > 1000][Silver]
* [validate](https://github.com/gookit/validate) - **Star : 83**  Go 封装数据验证和过滤。支持验证映射、结构、请求(表单、JSON、url)。值，上载文件)数据和更多特性。
* [validate](https://github.com/gobuffalo/validate) - **Star : 19** 这个包提供了一个框架，用于为Go应用程序编写验证。![最近三个月没有更新][Yellow]
* [validator](https://github.com/go-playground/validator) - **Star : 3282**  Go 结构体及域验证，包括：跨域、跨结构体, Map, 切片和数组。![star > 1000][Silver]

## 版本控制

*用于版本控制的库。*

* [gh](https://github.com/rjeczalik/gh) - **Star : 68** 用于GitHub webhook的可编写脚本的服务器和net/http中间件。![最近三个月没有更新][Yellow]
* [git2go](https://github.com/libgit2/git2go) - **Star : 1338**  libgit2 的 Go 语言接口。![star > 1000][Silver]
* [go-git](https://github.com/src-d/go-git) - **Star : 4098** 纯Go中高度可扩展的Git实现。![star > 1000][Silver]![最近一个周有更新][Green]
* [go-vcs](https://github.com/sourcegraph/go-vcs) - **Star : 69** 在Go中操作和检查VCS存储库。
* [hercules](https://github.com/src-d/hercules) - **Star : 492** 从Git存储库历史中获得高级见解。![star > 100][Bronze]
* [hgo](https://github.com/beyang/hgo) - **Star : 12** Hgo是一组Go包的集合，提供对本地Mercurial存储库的读取访问。![最近三个月没有更新][Yellow]

## 视频

*用于操作视频的库。*

* [gmf](https://github.com/3d0c/gmf) - **Star : 508**  FFmpeg av\* 库的 Go 语言接口。![star > 100][Bronze]
* [go-astisub](https://github.com/asticode/go-astisub) - **Star : 162** 使用 Go 语言操作字幕(.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.)。![star > 100][Bronze]
* [go-astits](https://github.com/asticode/go-astits) - **Star : 256** 在GO中解析和演示MPEG传输流(.ts)。![star > 100][Bronze]
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) - **Star : 36** 苹果m3u8播放列表的解析器和生成器库。
* [goav](https://github.com/giorgisio/goav) - **Star : 748** FFmpeg的Comphrensive。![star > 100][Bronze]
* [gst](https://github.com/ziutek/gst) - **Star : 153**  GStreamer的Go工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - **Star : 11** 字幕格式支持 .srt、.ttml和.ass。![最近三个月没有更新][Yellow]
* [libvlc-go](https://github.com/adrg/libvlc-go) - **Star : 60** Go绑定libvlc 2.X/3.X/4。X(由VLC媒体播放器使用)。
* [v4l](https://github.com/korandiz/v4l) - **Star : 26** 用于Linux的视频捕捉库，用Go编写。![最近三个月没有更新][Yellow]

## Web框架

*全栈 web 框架。*

* [aah](https://aahframework.org) - 可伸缩、高性能、快速开发的Go Web框架。
* [Aero](https://github.com/aerogo/aero) - **Star : 152** 高性能的Go web框架，在Lighthouse中达到最高分。![star > 100][Bronze]
* [Air](https://github.com/aofei/air) - **Star : 512** 一个理想的精细化的Go web框架。![star > 100][Bronze]
* [Banjo](https://github.com/nsheremet/banjo) - **Star : 7** 非常简单和快速的网络框架 Go 。![最近三个月没有更新][Yellow]
* [Beego](https://github.com/astaxie/beego) - **Star : 21008** beego是一种用于 Go 编程语言的开源高性能web框架。![star > 5000][Gold]![最近一个周有更新][Green]
* [Buffalo](http://gobuffalo.io) - 为 Go 语言带来堪比 Rails 的高生产效率!
* [Echo](https://github.com/labstack/echo) - **Star : 14331** 高性能、极简的Go web框架。![star > 5000][Gold]![最近一个周有更新][Green]
* [Fireball](https://github.com/zpatrick/fireball) - **Star : 48** 感觉更加自然的 web 框架。![最近三个月没有更新][Yellow]
* [Gem](https://github.com/go-gem/gem) - **Star : 153** 简单快速的web框架，对REST API友好。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Gin](https://github.com/gin-gonic/gin) - **Star : 28677** Gin是一个用Go编写的web框架!它具有一个类似于martini的API，性能更好，速度快40倍。![star > 5000][Gold]![最近一个周有更新][Green]
* [Gizmo](https://github.com/NYTimes/gizmo) - **Star : 2811** 《纽约时报》使用的微服务工具包。![star > 1000][Silver]
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - **Star : 3317** 设置RESTful JSON API的快速简便方法。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [go-rest](https://github.com/ungerik/go-rest) - **Star : 115** 小型的 REST 框架。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Goa](https://github.com/goadesign/goa) - **Star : 3457** Goa为在Go中开发远程api和微服务提供了一种全面的方法。![star > 1000][Silver]![最近一个周有更新][Green]
* [Golax](https://github.com/fulldump/golax) - **Star : 71** 一个非Sinatra快速HTTP框架，支持谷歌自定义方法、深度拦截器、递归等。![最近三个月没有更新][Yellow]
* [Golf](https://github.com/dinever/golf) - **Star : 235** Golf 是一个快速、简单、轻量级的 Go 语言微型 web 框架。具有强大的功能且没有标准库以外的依赖。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Gondola](https://github.com/rainycape/gondola) - **Star : 315** web框架写的网站越快越好。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gongular](https://github.com/mustafaakin/gongular) - **Star : 415**  快速 Go web 框架，支持输入映射／验证以及依赖注入。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [hiboot](https://github.com/hidevopsio/hiboot) - **Star : 80** hiboot是一个高性能的web应用程序框架，支持自动配置和依赖注入。
* [Macaron](https://github.com/go-macaron/macaron) - **Star : 2782** Macaron 是一个高效的模块化设计的web框架![star > 1000][Silver]
* [mango](https://github.com/paulbellamy/mango) - **Star : 339** ManGo 是一个模块化 web 应用框架，受到 Rack 和 PEP333 的启发。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Microservice](https://github.com/claygod/microservice) - **Star : 56** 创建微服务的框架，用Golang编写。
* [neo](https://github.com/ivpusic/neo) - **Star : 392** Neo是一个非常简单且快速的Web框架API。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [nio](https://github.com/go-nio/nio) - **Star : 21** 现代的、最小的和高效的Go HTTP框架。![最近三个月没有更新][Yellow]
* [patron](https://github.com/beatlabs/patron) - **Star : 20** Patron是一个遵循最佳云实践的微服务框架，专注于提升开发效率。![最近一个周有更新][Green]
* [Resoursea](https://github.com/resoursea/api) - **Star : 29** 用于快速编写基于资源的服务的REST框架。![最近三个月没有更新][Yellow]
* [REST Layer](http://rest-layer.io) - 框架，用于在数据库之上构建REST/GraphQL API，主要是通过代码进行配置。
* [Revel](https://github.com/revel/revel) - **Star : 11167** 用于Go语言的高效web框架。![star > 5000][Gold]
* [rex](https://github.com/goanywhere/rex) - **Star : 25**  Rex 是一个用于进行模块化开发的库，基于Gorilla/mux 完全兼容大多数的 net/HTTP.![最近三个月没有更新][Yellow]
* [sawsij](https://github.com/jaybill/sawsij) - **Star : 2** 轻量级、开源的web框架，用于构建高性能、数据驱动的web应用程序。![最近三个月没有更新][Yellow]
* [tango](https://github.com/lunny/tango) - **Star : 814** 微型的、支持插件的 web 框架。![star > 100][Bronze]
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - **Star : 998** 用于构建 JSON web 服务的 Go 语言框架，受到 Dropwizard 的启发。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [traffic](https://github.com/pilu/traffic) - **Star : 518** Sinatra启发了regexp/pattern mux和用于Go的web框架。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [uAdmin](https://github.com/uadmin/uadmin) - **Star : 46** 受到 Sinatra 启发的 Go 语言 web 框架。
* [utron](https://github.com/gernest/utron) - **Star : 2139** Go(Golang)的轻量级MVC框架。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [vox](https://github.com/aisk/vox) - **Star : 27** 一个面向人类的golang web框架，深受Koa的启发。![最近一个周有更新][Green]
* [WebGo](https://github.com/bnkamalesh/webgo) - **Star : 70** 构建web应用程序的微框架;处理程序链接、中间件和上下文注入。与标准库兼容的HTTP处理程序(即http.HandlerFunc)。
* [YARF](https://github.com/yarf-framework/yarf) - **Star : 49** 快速微框架，旨在以快速和简单的方式构建REST api和web服务。![最近三个月没有更新][Yellow]
* [Zerver](https://github.com/cosiner/zerver) - Zerver是一个表现力强、模块化、功能完备的RESTful框架。

### 中间件

#### 仿真中间件

* [client-timing](https://github.com/posener/client-timing) - **Star : 11** 用于服务器定时报头的HTTP客户机。![最近三个月没有更新][Yellow]
* [CORS](https://github.com/rs/cors) - **Star : 1175** 轻松地向API添加CORS功能。![star > 1000][Silver]
* [formjson](https://github.com/rs/formjson) - **Star : 33** 透明地将JSON输入作为标准表单POST处理。![最近三个月没有更新][Yellow]
* [go-server-timing](https://github.com/mitchellh/go-server-timing) - **Star : 743** 添加/解析Server-Timing头。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Limiter](https://github.com/ulule/limiter) - **Star : 760** 简单的速度限制中间件。![star > 100][Bronze]
* [ln-paywall](https://github.com/philippgille/ln-paywall) - **Star : 86** 使用Lightning Network(比特币)实现基于每个请求的api货币化中间件。![最近三个月没有更新][Yellow]
* [Tollbooth](https://github.com/didip/tollbooth) - **Star : 1208** 限制速率的 HTTP 请求处理程序。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [XFF](https://github.com/sebest/xff) - **Star : 71** 处理 X-Forwarded-For 头的中间件。

#### 用于创建HTTP中间件的库

* [alice](https://github.com/justinas/alice) - **Star : 1805** 用于连接中间件的库，简单无痛苦。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [catena](https://github.com/codemodus/catena) - **Star : 7** HTTP.Handler wrapper catenation (和chain具有相同的 API ).。![最近三个月没有更新][Yellow]
* [chain](https://github.com/codemodus/chain) - **Star : 63** 带有范围数据的处理程序包装器链接(基于网络/上下文的“中间件”)。![最近三个月没有更新][Yellow]
* [go-wrap](https://github.com/go-on/wrap) - **Star : 56** net/http的小型中间件包。![最近三个月没有更新][Yellow]
* [gores](https://github.com/alioygur/gores) - **Star : 82** 处理HTML、JSON、XML等响应的Go包。对于RESTful api非常有用。![最近三个月没有更新][Yellow]
* [interpose](https://github.com/carbocation/interpose) - **Star : 290** golang的极简网络/http中间件。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [muxchain](https://github.com/stephens2424/muxchain) - **Star : 208** 用于net/http的轻量级中间件。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [negroni](https://github.com/urfave/negroni) - **Star : 6276** 符合语言习惯的 HTTP 中间件库。![star > 5000][Gold]
* [render](https://github.com/unrolled/render) - **Star : 1259** Go package用于方便地呈现JSON、XML和HTML模板响应。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [renderer](https://github.com/thedevsaddam/renderer) - **Star : 166** 简单、轻量级和更快的响应(JSON、JSONP、XML、YAML、HTML、文件)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [rye](https://github.com/InVisionApp/rye) - **Star : 92** 支持JWT、CORS、Statsd和Go 1.7上下文的小型Go中间件库(带有罐装中间件)。![最近三个月没有更新][Yellow]
* [stats](https://github.com/thoas/stats) - **Star : 536** 使用中间件来存储关于web应用程序的各种信息。![star > 100][Bronze]

### 路由器

* [alien](https://github.com/gernest/alien) - **Star : 105** 轻量级和快速http路由器从外层空间。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [bellt](https://github.com/GuilhermeCaruso/bellt) - **Star : 37** 一个简单的Go HTTP路由器。
* [Bone](https://github.com/go-zoo/bone) - **Star : 1219** 闪电快速HTTP多路复用器。![star > 1000][Silver]
* [Bxog](https://github.com/claygod/Bxog) - **Star : 93** 简单和快速的HTTP路由器 Go 。它可以处理不同难度、长度和嵌套的路径。他还知道如何根据接收到的参数创建URL。![最近三个月没有更新][Yellow]
* [chi](https://github.com/go-chi/chi) - **Star : 5849** 小巧、快速、具有丰富表达力的 HTTP 路由，基于net/context.。![star > 5000][Gold]
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - **Star : 734** 高性能路由器分叉从`httprouter`。第一个路由器适合`fasthttp`。![star > 100][Bronze]
* [FastRouter](https://github.com/razonyang/fastrouter) - **Star : 18** 一个快速，灵活的HTTP路由器写在Go。![最近三个月没有更新][Yellow]
* [gocraft/web](https://github.com/gocraft/web) - **Star : 1390** Mux和中间件包在Go中。![star > 1000][Silver]![最近一个周有更新][Green]
* [Goji](https://github.com/goji/goji) - **Star : 761** 枸杞是一种简约的和灵活的与支持'net/context` HTTP请求多路复用器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [GoRouter](https://github.com/vardius/gorouter) - **Star : 47** GoRouter 是一个服务器/API 微型框架、HTTP 请求路由 router, 数据分选器，提供了支持net/context的中间件。
* [gowww/router](https://github.com/gowww/router) - **Star : 158** 超快的HTTP 路由，完全兼容 net/HTTP.Handler 接口.。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [httprouter](https://github.com/julienschmidt/httprouter) - **Star : 9482** 高性能路由。使用这个库和标准http处理工具可以构建一个非常高性能大web框架。![star > 5000][Gold]
* [httptreemux](https://github.com/dimfeld/httptreemux) - **Star : 386** 高速，灵活，基于树的 HTTP 路由。受到了 httprouter 的启发。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [lars](https://github.com/go-playground/lars) - **Star : 375** 是一个轻量级、快速、可扩展、零分配的HTTP路由，用于创建定制化的框架。![star > 100][Bronze]
* [mux](https://github.com/gorilla/mux) - **Star : 9304** 强大的URL路由器和调度器为golang。![star > 5000][Gold]![最近一个周有更新][Green]
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - **Star : 358** 一个非常快的Go (golang) HTTP路由器，支持正则表达式路由匹配。完全支持构建RESTful api。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [pure](https://github.com/go-playground/pure) - **Star : 83** 是一个轻量级HTTP路由器，它坚持net/ HTTP“实现”的std。
* [Siesta](https://github.com/VividCortex/siesta) - **Star : 349** 编写中间件和处理程序的可组合框架。![star > 100][Bronze]
* [vestigo](https://github.com/husobee/vestigo) - **Star : 250** 高性能，独立，HTTP兼容的URL路由器的go web应用程序。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [violetear](https://github.com/nbari/violetear) - **Star : 95** HTTP路由器。![最近三个月没有更新][Yellow]
* [xmux](https://github.com/rs/xmux) - **Star : 87** 高性能mux基于httprouter 'net/context`支持。![最近三个月没有更新][Yellow]
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - **Star : 444** 一个简单和快速的HTTP路由器 Go 。![star > 100][Bronze]![最近一个周有更新][Green]

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - **Star : 86**  Direct3D9 的 Go 语言接口。![最近三个月没有更新][Yellow]
* [go-ole](https://github.com/go-ole/go-ole) - **Star : 540** 为 Go 语言实现的 Win32 OLE。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gosddl](https://github.com/MonaxGT/gosddl) - **Star : 1** 从SDDL-string到用户友好的JSON的转换器。SDDL由四个部分组成:所有者、主群、DACL、SACL。

## XML

*用于操作XML的库和工具。*

* [XML-Comp](https://github.com/xml-comp/xml-comp) - **Star : 15** 简单的命令行XML比较器，生成文件夹、文件和标记的差异。![最近三个月没有更新][Yellow]
* [xml2map](https://github.com/sbabiv/xml2map) - **Star : 15** XML来映射转换器编写的Golang。
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - **Star : 6** 基于libxml2的xmlwriter模块的过程性XML生成API。![最近三个月没有更新][Yellow]
* [xpath](https://github.com/antchfx/xpath) - **Star : 149** Go的XPath包。![star > 100][Bronze]
* [xquery](https://github.com/antchfx/xquery) - **Star : 145** XQuery允许您使用XPath表达式从HTML/XML文档中提取数据。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [zek](https://github.com/miku/zek) - **Star : 242** 从XML生成Go结构。![star > 100][Bronze]

# 工具

* Go 软件和插件。*

## 代码分析

* [apicompat](https://github.com/bradleyfalzon/apicompat) - **Star : 165** 检查 Go 项目最近的向下不兼容修改。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [dupl](https://github.com/mibk/dupl) - **Star : 167** 用于代码克隆检测的工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [errcheck](https://github.com/kisielk/errcheck) - **Star : 1307** Errcheck是一个用于检查Go程序中未检查错误的程序。![star > 1000][Silver]![最近一个周有更新][Green]
* [gcvis](https://github.com/davecheney/gcvis) - **Star : 912** 实时可视化跟踪 GC 数据。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-checkstyle](https://github.com/qiniu/checkstyle) - **Star : 95** checkstyle是一个类似于java checkstyle的样式检查工具![最近三个月没有更新][Yellow]
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - **Star : 277** go-cleanarch 的创建是为了验证 Clean 体系结构规则，比如 Go 项目中的依赖关系。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-critic](https://github.com/go-critic/go-critic) - **Star : 551** 源代码检查工具。![star > 100][Bronze]
* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - **Star : 176** 找出项目中过期的依赖项。![star > 100][Bronze]
* [go-outdated](https://github.com/firstrow/go-outdated) - **Star : 45** 显示过期包的终端应用。![最近三个月没有更新][Yellow]
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - **Star : 367** 基于 Web 的 Golang AST 可视化工具。![star > 100][Bronze]
* [GoCover.io](http://gocover.io/) - GoCover.io 提供了任意 golang 包的代码覆盖率服务。
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - 来修复(添加，删除) Go 中自动导入的工具。
* [GolangCI](https://golangci.com/) - GolangCI 是一个针对 GitHub pull 请求的自动代码审查服务。服务是开源的，对开源项目是免费的。
* [GoLint](https://github.com/golang/lint) - **Star : 3096** Go 源码的 linter。![star > 1000][Silver]
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - 添加 zero 返回声明，以匹配 func 返回类型。
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple 是 Go 源代码的linter，专门用于简化代码。
* [gostatus](https://github.com/shurcooL/gostatus) - **Star : 241** 用于显示包含 Go 包的存储库的状态的命令行工具，。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [lint](https://github.com/surullabs/lint) - **Star : 62** 将 linters 作为测试的一部分。![最近三个月没有更新][Yellow]
* [php-parser](https://github.com/z7zmey/php-parser) - **Star : 614** 用 Go 编写的 PHP 解析器。![star > 100][Bronze]
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - 用于大量静态分析检查，您可能已经从 c# 的 ReSharper 等工具中习惯了这些检查。
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - **Star : 14** 在源码中寻找没有直接单元测试的函数和方法。![最近三个月没有更新][Yellow]
* [unconvert](https://github.com/mdempsky/unconvert) - **Star : 257** 在源码中删除不必要的类型转换。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - 对未使用的常量、变量、函数和类型的代码进行检查。
* [validate](https://github.com/mccoyst/validate) - **Star : 62** 使用 tags 自动验证结构体字段。![最近三个月没有更新][Yellow]

## 编辑器插件

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - JetBrains IDEs 的 Go 插件。
* [go-language-server](https://github.com/theia-ide/go-language-server) - **Star : 28** A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.![最近三个月没有更新][Yellow]
* [go-mode](https://github.com/dominikh/go-mode.el) - **Star : 940** 在 GNU/Emacs 支持 GO。![star > 100][Bronze]
* [go-plus](https://github.com/joefitzgerald/go-plus) - **Star : 1479** 在 Atom 中添加自动完成，格式化，语法检查，高亮和审查。![star > 1000][Silver]![最近一个周有更新][Green]
* [gocode](https://github.com/nsf/gocode) - **Star : 4713** Autocompletion daemon for the Go programming language.![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - 在 VS Code 中支持 Go 的基准分析。
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - **Star : 3215** 包含了可为文本编辑器 SublimeText 3 提供代码自动填充和其他类似IDE的功能的 Golang IDE 插件集合。![star > 1000][Silver]![最近一个周有更新][Green]
* [gounit-vim](https://github.com/hexdigest/gounit-vim) - **Star : 17** 基于函数或方法的签名生成Go测试的Vim插件。![最近三个月没有更新][Yellow]
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - **Star : 12** 在 Theia IDE中支持 Go。![最近三个月没有更新][Yellow]
* [velour](https://github.com/velour/velour) - **Star : 16** acme编辑器的IRC客户端。![最近三个月没有更新][Yellow]
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - **Star : 80** 在保存时突出显示语法错误的 Vim 插件。![最近三个月没有更新][Yellow]
* [vim-go](https://github.com/fatih/vim-go) - **Star : 10658** Go 开发会用到的 Vim 插件。![star > 5000][Gold]![最近一个周有更新][Green]
* [vscode-go](https://github.com/Microsoft/vscode-go) - **Star : 5006** Visual Studio代码的扩展(VS代码)，它提供了对Go语言的支持。![star > 5000][Gold]![最近一个周有更新][Green]
* [Watch](https://github.com/eaburns/Watch) - **Star : 166** Runs a command in an acme win on file changes.![star > 100][Bronze]![最近三个月没有更新][Yellow]

## Go 生成工具

* [generic](https://github.com/usk81/generic) - **Star : 28** 灵活的 Go 数据类型。![最近三个月没有更新][Yellow]
* [genny](https://github.com/cheekybits/genny) - **Star : 919** 优雅的 Go 泛型。![star > 100][Bronze]
* [gocontracts](https://github.com/Parquery/gocontracts) - **Star : 52** 通过同步代码和文档来实现 design-by-contract 设计。![最近三个月没有更新][Yellow]
* [gonerics](http://github.com/bouk/gonerics) - Go中的易用的泛型。
* [gotests](https://github.com/cweill/gotests) - **Star : 2122** 从源代码生成测试用例。![star > 1000][Silver]![最近一个周有更新][Green]
* [gounit](https://github.com/hexdigest/gounit) - **Star : 28** 使用您自己的模板生成Go测试用例。![最近三个月没有更新][Yellow]
* [hasgo](https://github.com/DylanMeeus/hasgo) - **Star : 11** 可生成用于切片的 Haskell。
* [re2dfa](https://github.com/opennota/re2dfa) - **Star : 169** 将正则表达式转换为有限状态机，并输出 Go 源代码。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [TOML-to-Go](https://xuri.me/toml-to-go) - 在浏览器中将 TOML 转换为 Go 类型。

## Go 工具

* [colorgo](https://github.com/songgao/colorgo) - **Star : 95** 将 go 命令包装成彩色的 go build 输出。![最近三个月没有更新][Yellow]
* [depth](https://github.com/KyleBanks/depth) - **Star : 369** 通过分析导入，将包依赖关系树可视化输出。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gb](https://getgb.io/) - 一个基于项目的易用的构建工具。
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - **Star : 13** 一个[Yeoman](http://yeoman.io)生成器，用于启动新的 Go 项目。
* [gilbert](https://go-gilbert.github.io) - 一个为 Go 项目而生的构建系统和任务运行器。
* [go-callvis](https://github.com/TrueFurby/go-callvis) - **Star : 1917** 使用 dot format 可视化 Go 程序的调用图。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - **Star : 37** Bash completion for go and wgo。![最近三个月没有更新][Yellow]
* [go-swagger](https://github.com/go-swagger/go-swagger) - **Star : 3809** 基于 Go 的Swagger 2.0实现。![star > 1000][Silver]![最近一个周有更新][Green]
* [godbg](https://github.com/tylerwince/godbg) - **Star : 157** 实现了 Rusts 的 dbg! 宏，可以方便的在开发过程中快速、容易地调试。![star > 100][Bronze]
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - **Star : 3681** 借助的 OctoLinker 浏览器扩展，可以高效的地浏览  GitHub go文件。![star > 1000][Silver]![最近一个周有更新][Green]
* [richgo](https://github.com/kyoh86/richgo) - **Star : 374** 用文本装饰丰富 go test 的输出。![star > 100][Bronze]
* [rts](https://github.com/galeone/rts) - **Star : 184** 从服务器响应生成Go结构。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 软件包

*用Go编写的软件。*

### DevOps 工具

* [aptly](https://github.com/smira/aptly) - **Star : 1723** Debian存储库管理工具。![star > 1000][Silver]![最近一个周有更新][Green]
* [aurora](https://github.com/xuri/aurora) - **Star : 390** 基于web的跨平台 Beanstalkd 队列服务器控制台。![star > 100][Bronze]
* [awsenv](https://github.com/soniah/awsenv) - **Star : 20** 可以为 profile 加载Amazon (AWS)环境变量的轻量二进制文件。![最近三个月没有更新][Yellow]
* [Blast](https://github.com/dave/blast) - **Star : 168** 一个用于API负载测试和批处理作业的简单工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [bombardier](https://github.com/codesenberg/bombardier) - **Star : 1674** 快速跨平台 HTTP 基准测试工具。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [bosun](https://github.com/bosun-monitor/bosun) - **Star : 2841** 按照时间轴发出告警的框架。![star > 1000][Silver]
* [DepCharge](https://github.com/centerorbit/depcharge) - **Star : 9** Helps orchestrating the execution of commands across the many dependencies in larger projects.![最近三个月没有更新][Yellow]
* [dogo](https://github.com/liudng/dogo) - **Star : 215** 监视源文件中的更改并自动编译和运行(restart)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - **Star : 22** 使用二进制文件、docker或 Drone CI 来触发下游Jenkins作业。
* [drone-scp](https://github.com/appleboy/drone-scp) - **Star : 54** 通过 SSH 进行文件拷贝。其中 SSH 通过二进制文件、docker 或 Drone CI触发。
* [Dropship](https://github.com/chrismckenzie/dropship) - **Star : 46** 通过 cdn 部署代码的工具。![最近三个月没有更新][Yellow]
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - **Star : 96** Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* [fac](https://github.com/mkchoi212/fac) - **Star : 1584** 修复 git 合并冲突。![star > 1000][Silver]
* [gaia](https://github.com/gaia-pipeline/gaia) - **Star : 3686** 可用于任何编程语言来构建强大的管道。![star > 1000][Silver]![最近一个周有更新][Green]
* [Gitea](https://github.com/go-gitea/gitea) - **Star : 14560** 从 Gogs fork，完全由社区驱动。![star > 5000][Gold]![最近一个周有更新][Green]
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - 将所有GitHub repositories、issues、milestones 和 labels 都迁移到 Gitea。
* [go-furnace](https://github.com/go-furnace/go-furnace) - **Star : 62** 用Go编写的托管解决方案，可轻松地在AWS、GCP或DigitalOcean上部署应用程序。
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - **Star : 658** 允许你的 Go应用程序 进行自我更新。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gobrew](https://github.com/cryptojuice/gobrew) - **Star : 175** gobrew 允许您轻松地在 go 的多个版本之间切换。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [godbg](https://github.com/sirnewton01/godbg) - **Star : 219** 基于 web 的 gdb 前端应用程序。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Gogs](https://gogs.io/) - 自托管的Git服务。
* [gonative](https://github.com/inconshreveable/gonative) - **Star : 312** 用原生 Go 创建一个跨平台的 Go 工具链。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [govvv](https://github.com/ahmetalpbalkan/govvv) - **Star : 372** 可轻松地添加版本信息到 Go 二进制文件。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gox](https://github.com/mitchellh/gox) - **Star : 3321** 非常简单，没有多余的跨平台编译工具。![star > 1000][Silver]
* [goxc](https://github.com/laher/goxc) - **Star : 1627** 专注于跨平台编译和打包的 Go 构建工具。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [grapes](https://github.com/yaronsumel/grapes) - **Star : 133** 旨在轻松地通过ssh分发命令的轻量级工具。![star > 100][Bronze]
* [GVM](https://github.com/moovweb/gvm) - **Star : 4405** GVM 提供了一个接口来管理 Go 版本。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [Hey](https://github.com/rakyll/hey) - **Star : 6046** 压力测试工具，可用来代替 ApacheBench (ab)。![star > 5000][Gold]
* [kala](https://github.com/ajvb/kala) - **Star : 1345** 简单、现代和高性能的作业调度程序。![star > 1000][Silver]
* [kcli](https://github.com/cswank/kcli) - **Star : 65** 用于检查kafka主题/分区/消息的命令行工具。![最近三个月没有更新][Yellow]
* [kubernetes](https://github.com/kubernetes/kubernetes) - **Star : 54655** 来自谷歌的容器集群管理器。![star > 5000][Gold]![最近一个周有更新][Green]
* [lstags](https://github.com/ivanilves/lstags) - **Star : 219** 提供了工具和API，可用来同步不同注册中心的Docker图像。![star > 100][Bronze]![最近一个周有更新][Green]
* [lwc](https://github.com/timdp/lwc) - **Star : 8** UNIX wc命令的实时更新版本。![最近三个月没有更新][Yellow]
* [manssh](https://github.com/xwjdsh/manssh) - **Star : 202** manssh是一个命令行工具，可以方便地管理ssh别名配置。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Moby](https://github.com/moby/moby) - **Star : 53932** Collaborative project for the container ecosystem to assemble container-based systems.![star > 5000][Gold]![最近一个周有更新][Green]
* [Mora](https://github.com/emicklei/mora) - **Star : 263** 用于访问 MongoDB 文档和元数据的 REST 服务器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [ostent](https://github.com/ostrost/ostent) - **Star : 164** 收集和显示系统指标，并可选 Graphite and/or fluxdb作为依赖。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Packer](https://github.com/mitchellh/packer) - **Star : 9065** 用于从一个源配置为多个平台创建相同的机器图像。![star > 5000][Gold]![最近一个周有更新][Green]
* [Pewpew](https://github.com/bengadbois/pewpew) - **Star : 199** 灵活的 HTTP 命令行压测工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Pomerium](https://github.com/pomerium/pomerium) - **Star : 463** Pomerium是一个可识别身份的访问代理。![star > 100][Bronze]![最近一个周有更新][Green]
* [Rodent](https://github.com/alouche/rodent) - **Star : 30** 管理Go版本、项目和跟踪依赖项。![最近三个月没有更新][Yellow]
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - **Star : 988** 小型实用程序/库，针对大型对象在Amazon S3中的高速传输进行了优化。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - **Star : 533** 从命令行管理 BareMetal 服务器(与使用Docker一样容易)。![star > 100][Bronze]
* [script](https://github.com/bitfield/script) - **Star : 625** 让DevOps编写类shell和系统管理任务变得更加容易。![star > 100][Bronze]![最近一个周有更新][Green]
* [sg](https://github.com/ChristopherRabotin/sg) - **Star : 5** 可测试一组HTTP极限(如ab)，可以在每个调用之间使用响应代码和数据，根据之前的响应来确定特定的服务器压力。![最近三个月没有更新][Yellow]
* [skm](https://github.com/TimothyYe/skm) - **Star : 544** SKM是一个简单而强大的SSH密钥管理器，它可以帮助您轻松地管理多个SSH密钥!![star > 100][Bronze]
* [StatusOK](https://github.com/sanathp/statusok) - **Star : 1141** 监视您的网站和REST api。当服务器宕机或响应时间超过预期时，通过Slack、电子邮件获得通知。![star > 1000][Silver]
* [traefik](https://github.com/containous/traefik) - **Star : 23125** 反向代理和负载均衡器，支持多个后端。![star > 5000][Gold]![最近一个周有更新][Green]
* [Vegeta](https://github.com/tsenart/vegeta) - **Star : 11860** HTTP负载测试工具和库。超过9000 !![star > 5000][Gold]![最近一个周有更新][Green]
* [webhook](https://github.com/adnanh/webhook) - **Star : 3982** 允许用户创建在服务器上执行命令的 HTTP hooks。![star > 1000][Silver]![最近一个周有更新][Green]
* [Wide](https://wide.b3log.org/login) - 为使用 Golang 的团队提供基于 web 的 IDE。
* [winrm-cli](https://github.com/masterzen/winrm-cli) - **Star : 64** 在Windows机器上远程执行命令的Cli工具。

### 其他软件

* [borg](https://github.com/crufter/borg) - **Star : 1416** 基于终端的bash代码段搜索引擎。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [boxed](https://github.com/tejo/boxed) - **Star : 72** 基于Dropbox的博客引擎。![最近三个月没有更新][Yellow]
* [Cherry](https://github.com/rafael-santiago/cherry) - **Star : 192** 微型网络聊天服务器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Circuit](https://github.com/gocircuit/circuit) - **Star : 1775** Circuit 是一个可编程平台即服务(PaaS)和/或基础设施即服务(IaaS)，用于管理、发现、同步和编排包含云应用程序的服务和主机。![star > 1000][Silver]
* [Comcast](https://github.com/tylertreat/Comcast) - **Star : 6122** 模拟坏的网络连接。![star > 5000][Gold]![最近一个周有更新][Green]
* [confd](https://github.com/kelseyhightower/confd) - **Star : 6309** 使用 etcd 或 consul 的模板和数据管理本地应用程序配置文件。![star > 5000][Gold]
* [DDNS](https://github.com/skibish/ddns) - **Star : 97** 个人 DDNS 客户端。
* [Docker](http://www.docker.com/) - 面向开发人员和系统管理员的分布式应用程序的开放平台。
* [Documize](https://github.com/documize/community) - **Star : 786** 集成了SaaS工具数据的现代wiki软件。![star > 100][Bronze]![最近一个周有更新][Green]
* [drive](https://github.com/odeke-em/drive) - **Star : 4909** 基于命令行的谷歌驱动器客户端。![star > 1000][Silver]
* [Duplicacy](https://github.com/gilbertchen/duplicacy) - **Star : 2659** 跨平台网络和云备份工具。![star > 1000][Silver]![最近一个周有更新][Green]
* [gfile](https://github.com/Antonito/gfile) - **Star : 486** 通过WebRTC在两台计算机之间安全地传输文件，不需要任何第三方依赖。![star > 100][Bronze]
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - **Star : 879** App that displays updates for the Go packages in your GOPATH.![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - **Star : 373** 视频流 torrent 客户端。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [GoBoy](https://github.com/Humpheh/goboy) - **Star : 2092** 用 Go 编写的任天堂Game Boy彩色模拟器。![star > 1000][Silver]
* [gocc](https://github.com/goccmack/gocc) - **Star : 336** Gocc是一个用Go编写的编译器工具包。![star > 100][Bronze]
* [GoDNS](https://github.com/timothyye/godns) - **Star : 417** 一个动态DNS客户端工具，支持DNSPod & HE.net。![star > 100][Bronze]
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - **Star : 12** 包含了 Go 使用手册文档的 Chrome 扩展。![最近三个月没有更新][Yellow]
* [GoLand](https://jetbrains.com/go) - 功能齐全的跨平台 Go IDE。
* [Gor](https://github.com/buger/gor) - **Star : 11190** Http 流量复制工具，用于实时回放从生产环境到阶段/开发环境的流量。![star > 5000][Gold]![最近一个周有更新][Green]
* [hugo](http://gohugo.io/) - 快速、现代的静态网站引擎。
* [ide](https://github.com/thestrukture/ide) - **Star : 249** 基于浏览器的IDE![star > 100][Bronze]
* [ipe](https://github.com/dimiro1/ipe) - **Star : 274** Open source Pusher server implementation compatible with Pusher client libraries written in GO.![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [joincap](https://github.com/assafmo/joincap) - **Star : 121** 用于合并多个pcap文件的命令行实用程序。![star > 100][Bronze]
* [Juju](https://jujucharms.com/) - Cloud-agnostic的服务部署和编制 —— 支持EC2、Azure、Openstack、MAAS等。
* [Leaps](https://github.com/jeffail/leaps) - **Star : 641** 使用操作转换的成对编程服务。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [lgo](https://github.com/yunabe/lgo) - **Star : 1765** 与 Jupyter 可进行交互 Go 程序。它支持代码完成、代码检查以及与Go 100% 兼容性。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [limetext](http://limetext.org/) - 一个强大而优雅的文本编辑器。
* [LiteIDE](https://github.com/visualfc/liteide) - **Star : 5408** 简单的、开源的、跨平台的Go IDE。![star > 5000][Gold]
* [mockingjay](https://github.com/quii/mockingjay-server) - **Star : 407** 一份配置文件中便可伪造HTTP服务器与用户之间的行为。您还可以使服务器随机宕机，以帮助进行更实际的性能测试。![star > 100][Bronze]
* [myLG](https://github.com/mehrdadrad/mylg) - **Star : 2183** 命令行网络诊断工具。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [naclpipe](https://github.com/unix4fun/naclpipe) - **Star : 20** 基于加密管的简单的NaCL EC25519工具。![最近三个月没有更新][Yellow]
* [nes](https://github.com/fogleman/nes) - **Star : 4097** 任天堂娱乐系统(NES)模拟器。![star > 1000][Silver]
* [orange-cat](https://github.com/noraesae/orange-cat) - **Star : 178** 用Go编写的Markdown预览器。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [Orbit](https://github.com/gulien/orbit) - **Star : 128** 一个根据模板来运行命令和生成文件的简单小工具。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [peg](https://github.com/pointlander/peg) - **Star : 588** 解析表达式语法，是Packrat解析器生成器的实现。![star > 100][Bronze]
* [Pipe](https://github.com/b3log/pipe) - **Star : 2598** 一个小巧漂亮的博客平台。![star > 1000][Silver]
* [restic](https://github.com/restic/restic) - **Star : 7188** 消除重复项备份程序。![star > 5000][Gold]![最近一个周有更新][Green]
* [rkt](https://github.com/coreos/rkt) - **Star : 8698** 一个应用容器，与其他容器格式(如Docker)兼容，并支持其他执行引擎(如KVM)。![star > 5000][Gold]![最近一个周有更新][Green]
* [scc](https://github.com/boyter/scc) - **Star : 761** 一个非常快速准确的代码计数器，采用了复杂的计算和 COCOMO 预估。![star > 100][Bronze]![最近一个周有更新][Green]
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - **Star : 8025** 快速、简单、可伸缩的分布式文件系统，采用了O(1)磁盘查找。![star > 5000][Gold]![最近一个周有更新][Green]
* [shell2http](https://github.com/msoap/shell2http) - **Star : 396** 通过http服务器执行shell命令(用于原型或远程控制)。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [snap](https://github.com/intelsdi-x/snap) - **Star : 1801** 强大的遥测框架。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [Snitch](https://github.com/lucasgomide/snitch) - **Star : 15** 当有人通过 Tsuru 部署任何应用程序时，会通知您的团队以及其他工具。![最近三个月没有更新][Yellow]
* [Stack Up](https://github.com/pressly/sup) - **Star : 1968** Stack Up 是一个超级简单的部署工具 — 只面向Unix。![star > 1000][Silver]
* [syncthing](https://syncthing.net/) - 开放，分散的文件同步工具和协议。
* [term-quiz](https://github.com/crazcalm/term-quiz) - **Star : 17** 测试你的终端。![最近三个月没有更新][Yellow]
* [toxiproxy](https://github.com/shopify/toxiproxy) - **Star : 3772** 为自动化测试模拟网络和系统条件的代理。![star > 1000][Silver]![最近一个周有更新][Green]
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - **Star : 586** 高性能、可伸缩和可靠的 IPFIX、sFlow和 Netflow 收集器。![star > 100][Bronze]
* [wellington](https://github.com/wellington/wellington) - **Star : 288** Sass 项目管理工具，使用sprite函数(如Compass)扩展语言。![star > 100][Bronze]![最近三个月没有更新][Yellow]

# 资源

*在哪里可以找到新的Go库。*

## 基准

* [autobench](https://github.com/davecheney/autobench) - **Star : 89** 用来来比较不同Go版本之间的性能的框架。![最近三个月没有更新][Yellow]
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - **Star : 19** 强大的HTTP基准测试工具，包含了Аb，Wrk，Siege工具。收集统计和各种参数指标，并比较相关结果。![最近三个月没有更新][Yellow]
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - **Star : 119** Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - **Star : 1253** HTTP请求路由器基准测试和比较。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - **Star : 974** web框架基准测试。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - **Star : 841** Go序列化方法的基准测试。![star > 100][Bronze]
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - **Star : 52** Go语言常用基本操作的基准测试。![最近三个月没有更新][Yellow]
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - **Star : 17** Go 基础操作的基准测试集合。其目的是将一些语言特性与其他特性进行比较。![最近三个月没有更新][Yellow]
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - **Star : 49** 为流行的 Go 数据库/SQL实用程序收集基准测试。![最近三个月没有更新][Yellow]
* [gospeed](https://github.com/feyeleanor/GoSpeed) - **Star : 93** 计算语言结构的速度的微观基准测试。![最近三个月没有更新][Yellow]
* [kvbench](https://github.com/jimrobinson/kvbench) - **Star : 14** K / V 类型数据库基准测试。![最近三个月没有更新][Yellow]
* [skynet](https://github.com/atemerev/skynet) - **Star : 908** 天网 1M 线程微基准测试。![star > 100][Bronze]
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - **Star : 172** 对比各种图像大小调整算法性能。![star > 100][Bronze]![最近三个月没有更新][Yellow]

## 会议

* [Capital Go](http://www.capitalgolang.com) - 华盛顿特区。,美国。
* [dotGo](http://www.dotgo.eu) - 巴黎,法国。
* [GoCon](http://gocon.connpass.com/) - 东京,日本。
* [GoDays](https://www.godays.io/) - 德国柏林。
* [GoLab](http://golab.io/) - 佛罗伦萨,意大利。
* [GolangUK](http://golanguk.com/) - 伦敦,英国。
* [GopherChina](http://gopherchina.org) - 上海,中国。
* [GopherCon](http://www.gophercon.com/) - 美国丹佛。
* [GopherCon Australia](https://gophercon.com.au/) - 澳大利亚悉尼。
* [GopherCon Brazil](https://gopherconbr.org) - 弗洛,BR。
* [GopherCon Europe](https://gophercon.is/) - 雷克雅未克,冰岛。
* [GopherCon India](https://www.gophercon.in/) - 印度浦那。
* [GopherCon Israel](https://www.gophercon.org.il/) - 特拉维夫,以色列。
* [GopherCon Russia](https://www.gophercon-russia.ru) - 莫斯科,俄罗斯。
* [GopherCon Singapore](https://gophercon.sg) - 新加坡枫树商贸城。
* [GopherCon Vietnam](https://gophercon.vn/) - 越南胡志明市。
* [GothamGo](http://gothamgo.com/) - 美国纽约市。
* [GoWayFest](https://goway.io/) - 白俄罗斯明斯克。

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - 一本关注 Go 语法/语义和各种细节的书。
* [Go Bootcamp](http://golangbootcamp.com)
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - **Star : 10** in Persian.![最近三个月没有更新][Yellow]
* [GoBooks](https://github.com/dariubs/GoBooks) - **Star : 6668** 一份精选的 Go 书籍清单。![star > 5000][Gold]
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - **Star : 1457** 由 Maria Letta 提供的与 Gopher 有关的图片包，其中包含了插图,表情文字。![star > 1000][Silver]
* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - **Star : 32** 与 Go gopher 相关的媒介数据[。ai . svg)。![最近三个月没有更新][Yellow]
* [gopher-logos](https://github.com/GolangUA/gopher-logos) - **Star : 62** 可爱的 gopher 标识。![最近三个月没有更新][Yellow]
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector](https://github.com/golang-samples/gopher-vector)
* [gophericons](https://github.com/shalakhin/gophericons)
* [gopherize.me](https://github.com/matryer/gopherize.me) - **Star : 312** Gopherize自己。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [gophers](https://github.com/ashleymcnamara/gophers) - **Star : 1809** 阿什莉·麦克纳马拉的歌斐艺术品。![star > 1000][Silver]
* [gophers](https://github.com/egonelbre/gophers) - **Star : 1546** Free gophers.![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [gophers](https://github.com/rogeralsing/gophers) - **Star : 49** 随机gopher图形。![最近三个月没有更新][Yellow]
* [gophers](https://github.com/sillecelik/go-gopher) - **Star : 41** Gopher amigurumi玩具图案。![最近三个月没有更新][Yellow]

## 聚会

* [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Canberra Gophers](https://www.meetup.com/Canberra-Gophers/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Казань](https://www.meetup.com/GolangKazan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*在这里添加您所在城市/国家的群组(发送**PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## 网站

* [Awesome Go @LibHunt](https://go.libhunt.com) - 属于你的 Go 工具箱。
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - **Star : 14363** Curated list of awesome remote jobs. A lot of them are looking for Go hackers.![star > 5000][Gold]![最近一个周有更新][Green]
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - **Star : 24467** 其他 awesome 系列的列表。![star > 5000][Gold]![最近一个周有更新][Green]
* [CodinGame](https://www.codingame.com/) - 以小游戏互动完成任务的形式来学习 Go。
* [Go Blog](http://blog.golang.org) - 官方 Go 博客。
* [Go Challenge](http://golang-challenge.org/) - 通过解决问题并从 Go 专家那里得到反馈来学习 Go。
* [Go Community on Hashnode](https://hashnode.com/n/go) - Hashnode上的Go社区。
* [Go Forum](https://forum.golangbridge.org) - 讨论 Go 的论坛。
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - wiki上的 Go 社区项目列表。
* [Go Report Card](https://goreportcard.com) - 为你的 Go 包生成一份报告单。
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - **Star : 35** 专门收集需要帮助的Go项目，这是你开启开源之路的好去处。![最近三个月没有更新][Yellow]
* [godoc.org](https://godoc.org/) - 开源 Go 包的文档。
* [Golang Flow](https://golangflow.io) - 发布更新、新闻、包等等。
* [Golang News](https://golangnews.com) - 关于 Go 编程的链接和新闻。
* [golang-graphics](https://github.com/mholt/golang-graphics) - **Star : 141** 收藏的 Go 图像，图形和艺术作品。![star > 100][Bronze]![最近三个月没有更新][Yellow]
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go 邮件列表。
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - Google+社区 golang爱好者聚集地。
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - 加入我们为Gophers设立的全新Slack社区([了解它是如何产生的](https://blog.gopheracademy.com/gophers-slack-community/))。
* [Gophercises](https://gophercises.com/) - 为 Go 初学者提供免费的代码训练。
* [gowalker.org](https://gowalker.org) -  Go API 文档。
* [justforfunc](https://www.youtube.com/c/justforfunc) - 致力于传授 Go 编程语言技巧和技巧的Youtube 频道，由Francesc Campoy [@francesc](https://twitter.com/francesc)主办。
* [r/Golang](https://www.reddit.com/r/golang) - 与 Go 有关的新闻。
* [studygolang](https://studygolang.com) - Go语言中文网
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - 寻找最新的 Go库 的好地方。
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### 教程

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Go 初学者经常遇到的陷阱、误区、错误
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - 教你如何用 Go 搭建一个电商平台 (包括demo)。
* [A Tour of Go](http://tour.golang.org/) - 互动的 Go 之旅。
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - **Star : 30904** Golang电子书，主要讲述如何用 Golang 建立一个web应用程序。![star > 5000][Gold]
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - 如何缓存数据库的慢查询。
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - 如何取消MySQL查询。
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - **Star : 436** 一本讲述如何用 Go 进行以太开发的小册。![star > 100][Bronze]
* [Games With Go](http://gameswithgo.org/) - 关于编程和游戏开发系列教学视频。
* [Go By Example](https://gobyexample.com/) - 手把手教你 如何在 Go 应用程序中使用注释。
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - **Star : 3968**  Go's reference card。![star > 1000][Silver]![最近三个月没有更新][Yellow]
* [Go database/sql tutorial](http://go-database-sql.org/) - 数据库概论/ sql。
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - 在你的移动设备上编辑你编辑和运行你的 Go 代码。
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - **Star : 661** 引入示例讲述 Golang 与Node.js在学习上的差异。![star > 100][Bronze]
* [Golangbot](https://golangbot.com/learn-golang-series/) - Go 编程教程。
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Go社区投票选举出来的最好的在线 Go 教程。
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - 快速使用Godog —— 一个行为驱动开发的构建和测试应用程序框架。
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - **Star : 3840** 学习使用测试驱动开发。![star > 1000][Silver]![最近一个周有更新][Green]
* [package main](https://www.youtube.com/packagemain) - 关于 Go 编程的YouTube频道。
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Working with Go](https://github.com/mkaz/working-with-go) - **Star : 1127** 由一个经验丰富的Go程序员群体编写的一系列Go学习范例。![star > 1000][Silver]
* [Your basic Go](http://yourbasic.org/golang) - 如何收集大量的教程。

