# Awesome Go

[Gold]: ./docs/Gold.svg "金牌"
[Silver]: ./docs/Silver.svg "银牌"
[Bronze]: ./docs/Bronze.svg "铜牌"

**此项目是 [awesome-go](https://awesome-go.com/) 中文版，最后一次同步时间 : 2019-07-02 17:41:24(每隔1天同步一次)**

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

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - **Star : 20** **最近提交 : 2018-03-22**  EasyMidi是一个简单可靠的库，用于处理标准midi文件(SMF)。
* [flac](https://github.com/eaburns/flac) - **Star : 84** **最近提交 : 2017-10-04**  原生 Go FLAC解码器，将FLAC文件解码为字节片。
* [flac](https://github.com/mewkiz/flac) - **Star : 101** **最近提交 : 2019-02-22**  原生 Go FLAC编码器/解码器，支持FLAC流。![star > 100][Bronze]
* [gaad](https://github.com/Comcast/gaad) - **Star : 55** **最近提交 : 2018-02-21**  原生 Go AAC位流解析器。
* [go-sox](https://github.com/krig/go-sox) - **Star : 92** **最近提交 : 2018-06-21**  libsox 的 Go 语言实现接口。
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - **Star : 24** **最近提交 : 2015-12-25**  libmediainfo 的 Go 语言实现接口。
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - **Star : 8** **最近提交 : 2018-06-04**  libsamplerate 的 Go 语言实现接口。
* [id3v2](https://github.com/bogem/id3v2) - **Star : 107** **最近提交 : 2019-02-08**  快速稳定的 ID3 解析及写入Go库。![star > 100][Bronze]
* [malgo](https://github.com/gen2brain/malgo) - **Star : 68** **最近提交 : 2019-04-16**  迷你音频库。
* [minimp3](https://github.com/tosone/minimp3) - **Star : 25** **最近提交 : 2019-03-19**  轻量级MP3解码器库。
* [mix](https://github.com/go-mix/mix) - **Star : 95** **最近提交 : 2017-06-25**  基于序列的 Go 原生音乐混音器。
* [mp3](https://github.com/tcolgate/mp3) - **Star : 89** **最近提交 : 2017-04-27**  原生 Go MP3解码器。
* [music-theory](https://github.com/go-music-theory/music-theory) - **Star : 250** **最近提交 : 2018-06-13**  基于 Go 的音乐理论模型。![star > 100][Bronze]
* [Oto](https://github.com/hajimehoshi/oto) - **Star : 383** **最近提交 : 2019-06-27**  多平台的 low-level 声音播放库。![star > 100][Bronze]
* [PortAudio](https://github.com/gordonklaus/portaudio) - **Star : 295** **最近提交 : 2018-08-20**  基于 Go 的PortAudio audio I/O库。![star > 100][Bronze]
* [portmidi](https://github.com/rakyll/portmidi) - **Star : 203** **最近提交 : 2017-07-16**  PortMidi的 Go 语言实现接口。。![star > 100][Bronze]
* [taglib](https://github.com/wtolson/go-taglib) - **Star : 66** **最近提交 : 2018-07-18**  taglib 的 Go 语言实现接口。。
* [vorbis](https://github.com/mccoyst/vorbis) - **Star : 22** **最近提交 : 2019-03-31**  “原生” Go Vorbis解码器(使用CGO，但没有依赖关系)。
* [waveform](https://github.com/mdlayher/waveform) - **Star : 245** **最近提交 : 2016-07-07**  通过音频流生成波形图像的包。![star > 100][Bronze]

## 身份验证和OAuth

*用于实现验证方案的库。*

* [authboss](https://github.com/volatiletech/authboss) - **Star : 1892** **最近提交 : 2019-06-29**  web模块化认证系统。它试图删除尽可能多的模板文件和硬编码，以便每次新建一个新的web项目时，您都可以插入、配置并开始构建您的应用程序，而不必每次都构建一个身份验证系统。![star > 1000][Silver]
* [branca](https://github.com/hako/branca) - **Star : 67** **最近提交 : 2018-08-08**  基于 Go 实现Branca令牌。
* [casbin](https://github.com/hsluoyz/casbin) - **Star : 4653** **最近提交 : 2019-07-01**  支持ACL、RBAC、ABAC等访问控制模型的授权库。![star > 1000][Silver]
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - **Star : 2** **最近提交 : 2017-10-09**  提供cookie .txt文件格式的解析器。
* [go-jose](https://github.com/square/go-jose) - **Star : 1088** **最近提交 : 2019-06-27**  相当完整地实现了JOSE工作组的JSON Web令牌、JSON Web签名和JSON Web加密规范。![star > 1000][Silver]
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - **Star : 1247** **最近提交 : 2019-06-21**  用 Golang 编写的独立且符合规范的OAuth2服务器。![star > 1000][Silver]
* [gologin](https://github.com/dghubble/gologin) - **Star : 1028** **最近提交 : 2019-03-05**  用于使用OAuth1和OAuth2身份验证提供者登录的可链处理程序。![star > 1000][Silver]
* [gorbac](https://github.com/mikespook/gorbac) - **Star : 896** **最近提交 : 2019-03-21**  轻量级的基于角色的访问控制(RBAC)实现。![star > 100][Bronze]
* [goth](https://github.com/markbates/goth) - **Star : 2214** **最近提交 : 2019-06-18**  提供了 OAuth 和 OAuth2 的简单清晰易用的方法。可开箱即用处理多个提供程序。![star > 1000][Silver]
* [httpauth](https://github.com/goji/httpauth) - **Star : 175** **最近提交 : 2016-06-01**  HTTP身份验证中间件。![star > 100][Bronze]
* [jwt](https://github.com/robbert229/jwt) - **Star : 68** **最近提交 : 2018-11-09**  简单易用的JSON Web令牌实现(JWT)。
* [jwt](https://github.com/pascaldekloe/jwt) - **Star : 76** **最近提交 : 2019-07-01**  轻量级JSON Web令牌库。
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - **Star : 151** **最近提交 : 2019-01-30**  JWT中间件，可用于Golang http服务器，提供了许多配置选项。![star > 100][Bronze]
* [jwt-go](https://github.com/dgrijalva/jwt-go) - **Star : 5709** **最近提交 : 2019-06-25**  JSON Web令牌(JWT)。![star > 5000][Gold]
* [loginsrv](https://github.com/tarent/loginsrv) - **Star : 793** **最近提交 : 2019-06-03**  JWT登录微服务带有可插拔的后端服务，如OAuth2 (Github)、htpasswd、osiam。![star > 100][Bronze]
* [oauth2](https://github.com/golang/oauth2) - **Star : 2325** **最近提交 : 2019-06-18**  goauth2的继任者。通用OAuth 2.0包，附带JWT、谷歌api、计算引擎和应用程序引擎支持。![star > 1000][Silver]
* [osin](https://github.com/openshift/osin) - **Star : 1535** **最近提交 : 2019-05-14**  OAuth2服务器库。![star > 1000][Silver]
* [paseto](https://github.com/o1egl/paseto) - **Star : 220** **最近提交 : 2019-05-06**  平台无关的安全令牌(PASETO)。![star > 100][Bronze]
* [permissions2](https://github.com/xyproto/permissions2) - **Star : 346** **最近提交 : 2019-06-13**  用于跟踪用户、登录状态和权限的库。依赖于cookie安全和bcrypt。![star > 100][Bronze]
* [rbac](https://github.com/zpatrick/rbac) - **Star : 25** **最近提交 : 2018-08-30**  最小的RBAC包。
* [scs](https://github.com/alexedwards/scs) - **Star : 515** **最近提交 : 2019-06-21**  HTTP服务器的会话管理器。![star > 100][Bronze]
* [securecookie](https://github.com/chmike/securecookie) - **Star : 31** **最近提交 : 2018-08-31**  高效安全的cookie编码/解码。
* [session](https://github.com/icza/session) - **Star : 87** **最近提交 : 2019-06-29**  web服务器会话管理(包括支持谷歌应用程序引擎- GAE)。
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - **Star : 8** **最近提交 : 2018-11-10**  使用SessionGate Redis模块进行会话管理。
* [sessions](https://github.com/adam-hanna/sessions) - **Star : 45** **最近提交 : 2019-05-14**  非常简单，高性能，可深度定制的会话服务，主要用于的 go http 服务器。
* [signedvalue](https://github.com/sashka/signedvalue) - **Star : 7** **最近提交 : 2019-01-28**  与[Tornado's](https://github.com/tornado oweb/tornado) 完全兼容的签名和时间戳字符串实现. create_signed_value '， ' decode_signed_value '，因此' set_secure_cookie '和' get_secure_cookie '。

## Bot建设

*用于构建和使用机器人的库。*

* [go-chat-bot](https://github.com/go-chat-bot/bot) - **Star : 453** **最近提交 : 2019-06-12**  用 Go 编写的IRC, Slack和电报机器人。![star > 100][Bronze]
* [go-sarah](https://github.com/oklahomer/go-sarah) - **Star : 128** **最近提交 : 2019-06-30**  此框架提供了聊天机器人相关的服务，包括LINE、Slack、Gitter等。![star > 100][Bronze]
* [go-tgbot](https://github.com/olebedev/go-tgbot) - **Star : 82** **最近提交 : 2018-06-25**  由swagger文件、基于会话的路由器和中间件生成的纯Golang Telegram Bot API包装器。
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - **Star : 207** **最近提交 : 2019-02-11**  基于控制台的，用于加密货币交易所的的交易机器人。![star > 100][Bronze]
* [govkbot](https://github.com/nikepan/govkbot) - **Star : 22** **最近提交 : 2019-03-07**  简单的Go [VK](https://vk.com) bot库。
* [hanu](https://github.com/sbstjn/hanu) - **Star : 107** **最近提交 : 2018-09-04**  用于编写Slack机器人的框架。![star > 100][Bronze]
* [Kelp](https://github.com/stellar/kelp) - **Star : 146** **最近提交 : 2019-06-28**  官方交易和做市机器人为[Stellar](https://www.stellar.org/) DEX。开箱即用的作品，用 Golang 编写，兼容集中交易和定制交易策略。![star > 100][Bronze]
* [margelet](https://github.com/zhulik/margelet) - **Star : 57** **最近提交 : 2016-09-18**  构建电报机器人的框架。
* [micha](https://github.com/onrik/micha) - **Star : 10** **最近提交 : 2018-02-15**  基于 GO 实现的Telegram 机器人API库。
* [slacker](https://github.com/shomali11/slacker) - **Star : 298** **最近提交 : 2019-06-08**  可简单创建Slack机器人的框架。![star > 100][Bronze]
* [slackscot](https://github.com/alexandre-normand/slackscot) - **Star : 10** **最近提交 : 2019-07-02**  另一个构建Slack机器人的框架。
* [tbot](https://github.com/yanzay/tbot) - **Star : 212** **最近提交 : 2019-06-15**  带有类似于net/http API的Telegram bot服务器。![star > 100][Bronze]
* [telebot](https://github.com/tucnak/telebot) - **Star : 923** **最近提交 : 2019-05-20**  用Go编写的Telegram bot框架。![star > 100][Bronze]
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - **Star : 1556** **最近提交 : 2019-06-19**  简单轻量级的Telegram bot客户端。![star > 1000][Silver]
* [Tenyks](https://github.com/kyleterry/tenyks) - **Star : 167** **最近提交 : 2017-03-05**  面向服务的IRC bot，使用Redis和JSON进行消息传递。![star > 100][Bronze]

## 命令行

### 标准CLI

*用于构建标准或基本命令行应用程序的库。*

* [argparse](https://github.com/akamensky/argparse) - **Star : 99** **最近提交 : 2019-03-09**  命令行参数分析器，灵感来自Python的argparse模块。
* [argv](https://github.com/cosiner/argv) - **Star : 16** **最近提交 : 2019-06-13**  基于Base 语法，用于分隔命令行字符串并将其作为参数的 Go 语言库，
* [cli](https://github.com/mkideal/cli) - **Star : 470** **最近提交 : 2019-06-01**  基于golang结构标签，功能丰富易于使用的命令行包。![star > 100][Bronze]
* [cli](https://github.com/teris-io/cli) - **Star : 56** **最近提交 : 2019-05-24**  为 Go 构建命令接口提供简单而完整的API。
* [cli-init](https://github.com/tcnksm/gcli) - **Star : 867** **最近提交 : 2017-11-20**  一个简单就可开启构建Golang命令行的应用程序。![star > 100][Bronze]
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [cmdr](https://github.com/hedzr/cmdr) - **Star : 7** **最近提交 : 2019-06-24**  一个POSIX/GNU风格的、类似getopt的命令行UI Go库。
* [cobra](https://github.com/spf13/cobra) - **Star : 12559** **最近提交 : 2019-06-29**  现代Go CLI命令行交互工具。![star > 5000][Gold]
* [commandeer](https://github.com/jaffee/commandeer) - **Star : 78** **最近提交 : 2019-06-29**  开发友好的CLI应用程序。
* [complete](https://github.com/posener/complete) - **Star : 607** **最近提交 : 2019-07-01**  使用 Go 语言编写的 bash 命令补全工具以及 Go 命令补全工具.![star > 100][Bronze]
* [docopt.go](https://github.com/docopt/docopt.go) - **Star : 1133** **最近提交 : 2018-09-25**  会让你满意的命令行参数解析器。![star > 1000][Silver]
* [env](https://github.com/codingconcepts/env) - **Star : 41** **最近提交 : 2019-06-14**  基于标记的结构化的环境配置。
* [flag](https://github.com/cosiner/flag) - **Star : 100** **最近提交 : 2019-03-13**  简单但功能强大的命令行选项解析库，用于支持Go子命令。![star > 100][Bronze]
* [flaggy](https://github.com/integrii/flaggy) - **Star : 441** **最近提交 : 2019-05-23**  一个健壮的、易用的标志包，具有出色的子命令支持。![star > 100][Bronze]
* [flagvar](https://github.com/sgreben/flagvar) - **Star : 31** **最近提交 : 2019-06-01**  符合 Go 标准的“flag”标志参数类型包。
* [go-arg](https://github.com/alexflint/go-arg) - **Star : 641** **最近提交 : 2019-05-04**  基于结构的参数解析。![star > 100][Bronze]
* [go-commander](https://github.com/yitsushi/go-commander) - **Star : 14** **最近提交 : 2019-05-16**  用于简化CLI工作流的 Go 库。
* [go-flags](https://github.com/jessevdk/go-flags) - **Star : 1488** **最近提交 : 2019-06-17**   Go 命令行选项解析器。![star > 1000][Silver]
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - **Star : 5** **最近提交 : 2019-07-02**   Go 选择解析器，借鉴于Perl灵活性的GetOpt::Long。
* [gocmd](https://github.com/devfacet/gocmd) - **Star : 33** **最近提交 : 2018-09-05**  用于构建命令行应用程序。
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - 具有自动配置和依赖注入的cli应用程序框架。
* [job](https://github.com/liujianping/job) - **Star : 41** **最近提交 : 2019-05-23**  工作，把你的短期指令当作长期任务。
* [kingpin](https://github.com/alecthomas/kingpin) - **Star : 2491** **最近提交 : 2019-06-08**  支持子命令的命令行和标志解析器。![star > 1000][Silver]
* [liner](https://github.com/peterh/liner) - **Star : 569** **最近提交 : 2019-05-28**  类似readline-like的命令行接口库。![star > 100][Bronze]
* [mitchellh/cli](https://github.com/mitchellh/cli) - **Star : 983** **最近提交 : 2018-11-25**  用于实现命令行接口的Go库。![star > 100][Bronze]
* [mow.cli](https://github.com/jawher/mow.cli) - **Star : 619** **最近提交 : 2019-05-10**  用于构建具有复杂标志和参数解析和验证的CLI应用程序。![star > 100][Bronze]
* [ops](https://github.com/nanovms/ops) - **Star : 186** **最近提交 : 2019-07-02**  Unikernel Builder /协调器。![star > 100][Bronze]
* [pflag](https://github.com/spf13/pflag) - **Star : 729** **最近提交 : 2019-06-28**  基于POSIX/GNU-style --flags实现的包，主要用于替换Go的falg包。![star > 100][Bronze]
* [readline](https://github.com/chzyer/readline) - **Star : 1362** **最近提交 : 2019-05-27**  纯golang实现，在MIT许可下提供了GNU-Readline的大部分特性。![star > 1000][Silver]
* [sand](https://github.com/Zaba505/sand) - **Star : 5** **最近提交 : 2018-11-22**  用于创建解释器等的简单API。
* [sflags](https://github.com/octago/sflags) - **Star : 84** **最近提交 : 2019-02-03**  基于结构的flag生成器，用于flag、urfave/cli、pflag、cobra、kingpin和其他库。
* [strumt](https://github.com/antham/strumt) - **Star : 27** **最近提交 : 2019-03-02**  用于创建提示链。
* [ukautz/clif](https://github.com/ukautz/clif) - **Star : 98** **最近提交 : 2019-02-18**  简小的命令行接口框架。
* [urfave/cli](https://github.com/urfave/cli) - **Star : 11063** **最近提交 : 2019-06-28**  可让你简单、快速和愉快的构建命令行应用(之前是codegangsta/cli)。![star > 5000][Gold]
* [wlog](https://github.com/dixonwille/wlog) - **Star : 33** **最近提交 : 2017-07-21**  支持跨平台和并发的简单日志记录接口。
* [wmenu](https://github.com/dixonwille/wmenu) - **Star : 80** **最近提交 : 2019-05-08**  为cli程序提供了简单上手的菜单，可提示用户作出选择。

### 高级控制台用户界面

*用于构建控制台应用程序和控制台用户界面的库。*

* [asciigraph](https://github.com/guptarohit/asciigraph) - **Star : 1109** **最近提交 : 2019-04-01**  在命令行中构建轻量级ASCII线图╭┈╯，应用程序中没有其他依赖项。![star > 1000][Silver]
* [aurora](https://github.com/logrusorgru/aurora) - **Star : 596** **最近提交 : 2019-04-28**  支持fmt.Printf/Sprintf的ANSI终端颜色。![star > 100][Bronze]
* [cfmt](https://github.com/mingrammer/cfmt) - **Star : 67** **最近提交 : 2018-12-08**  提供上下文的fmt，灵感来自于bootstrap color classes。
* [chalk](https://github.com/ttacon/chalk) - **Star : 302** **最近提交 : 2016-06-27**  美化终端/控制台输出。![star > 100][Bronze]
* [color](https://github.com/fatih/color) - **Star : 2980** **最近提交 : 2018-10-11**  多功能包装，彩色终端输出。![star > 1000][Silver]
* [colourize](https://github.com/TreyBastian/colourize) - **Star : 16** **最近提交 : 2016-05-10**  在终端提供ANSI彩色文本。
* [ctc](https://github.com/wzshiming/ctc) - **Star : 9** **最近提交 : 2018-10-31**  不需要Print方法的非侵入性跨平台终端颜色库。
* [go-ataman](https://github.com/workanator/go-ataman) - **Star : 8** **最近提交 : 2017-09-25**  在终端提供ANSI彩色文本模板。
* [go-colorable](https://github.com/mattn/go-colorable) - **Star : 368** **最近提交 : 2019-05-24**  适用于windows的颜色编写器。![star > 100][Bronze]
* [go-colortext](https://github.com/daviddengcn/go-colortext) - **Star : 198** **最近提交 : 2018-04-10**  在终端中使用彩色文字。![star > 100][Bronze]
* [go-isatty](https://github.com/mattn/go-isatty) - **Star : 333** **最近提交 : 2019-05-22**  Go 实现的 isatty。![star > 100][Bronze]
* [go-prompt](https://github.com/c-bata/go-prompt) - **Star : 2263** **最近提交 : 2019-06-29**  构建一个强大的交互式提示，借鉴于[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit)![star > 1000][Silver]
* [gocui](https://github.com/jroimartin/gocui) - **Star : 4410** **最近提交 : 2019-06-16**  旨在创建控制台用户界面的极简Go库。![star > 1000][Silver]
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - 更换终端文本样式。
* [gookit/color](https://github.com/gookit/color) - **Star : 181** **最近提交 : 2019-04-30**  终端显色工具库，支持16种颜色，256种颜色，RGB显色输出，兼容Windows。![star > 100][Bronze]
* [mpb](https://github.com/vbauerster/mpb) - **Star : 499** **最近提交 : 2019-06-01**  可在终端显示多进度条。![star > 100][Bronze]
* [progressbar](https://github.com/schollz/progressbar) - **Star : 550** **最近提交 : 2019-06-28**  基本线程安全的进度条，在每个操作系统工作。![star > 100][Bronze]
* [simpletable](https://github.com/alexeyco/simpletable) - **Star : 154** **最近提交 : 2019-02-23**  可在终端显示简易表格。![star > 100][Bronze]
* [tabby](https://github.com/cheynewallace/tabby) - **Star : 244** **最近提交 : 2019-03-27**  一个可在终端生成一个极简Golang表格轻量级库![star > 100][Bronze]
* [tabular](https://github.com/InVisionApp/tabular) - **Star : 29** **最近提交 : 2018-05-15**  不需要向API传递大量参数就可从命令行实用程序中打印ASCII表。
* [termbox-go](https://github.com/nsf/termbox-go) - **Star : 3430** **最近提交 : 2019-06-24**  基于文本的跨平台接口库。![star > 1000][Silver]
* [termdash](https://github.com/mum4k/termdash) - **Star : 773** **最近提交 : 2019-06-07**  此库是基于**termbox-go**实现的，借鉴于[termui](https://github.com/gizak/termui)。![star > 100][Bronze]
* [termtables](https://github.com/apcera/termtables) - **Star : 212** **最近提交 : 2017-10-30**  使用Ruby库[terminal-tables](https://github.com/tj/terminal-table)的端口生成简单的ASCII表，并提供标记和HTML输出。![star > 100][Bronze]
* [termui](https://github.com/gizak/termui) - **Star : 8787** **最近提交 : 2019-07-01**  此库是基于**termbox-go**实现的，借鉴于[blessed-contrib](https://github.com/yaronn/blessed-contrib)。![star > 5000][Gold]
* [uilive](https://github.com/gosuri/uilive) - **Star : 814** **最近提交 : 2019-05-17**  用于实时更新终端输出的库。![star > 100][Bronze]
* [uiprogress](https://github.com/gosuri/uiprogress) - **Star : 1518** **最近提交 : 2019-05-22**  在终端呈现进度条，可灵活配置的。![star > 1000][Silver]
* [uitable](https://github.com/gosuri/uitable) - **Star : 493** **最近提交 : 2019-05-14**  改善终端应用程序中表格数据的可读性。![star > 100][Bronze]

## 配置

*配置解析的库。*

* [config](https://github.com/JeremyLoy/config) - **Star : 184** **最近提交 : 2019-05-24**  云本地应用程序配置。将ENV绑定到结构体仅需两行代码。![star > 100][Bronze]
* [config](https://github.com/olebedev/config) - **Star : 209** **最近提交 : 2019-05-29**  带有环境变量和标记解析的JSON或YAML配置包装器。![star > 100][Bronze]
* [configure](https://github.com/paked/configure) - **Star : 48** **最近提交 : 2019-02-18**  通过多个源提供配置，包括JSON、flags和环境变量。
* [confita](https://github.com/heetch/confita) - **Star : 238** **最近提交 : 2019-06-14**  从多个后端级联加载配置到struct中。![star > 100][Bronze]
* [conflate](https://github.com/the4thamigo-uk/conflate) - **Star : 8** **最近提交 : 2019-04-10**  合并来自任意url的多个JSON/YAML/TOML文件、针对JSON模式的验证以及模式中定义的默认值的应用程序。
* [env](https://github.com/caarlos0/env) - **Star : 832** **最近提交 : 2019-05-15**  解析环境变量并赋值到struct中(默认值)。![star > 100][Bronze]
* [envcfg](https://github.com/tomazk/envcfg) - **Star : 90** **最近提交 : 2017-06-19**  对环境变量进行解析，并赋值到struct。
* [envconf](https://github.com/ian-kent/envconf) - **Star : 7** **最近提交 : 2014-10-26**  从环境配置中读取配置。
* [envconfig](https://github.com/vrischmann/envconfig) - **Star : 143** **最近提交 : 2019-07-01**  从环境变量中读取配置。![star > 100][Bronze]
* [envh](https://github.com/antham/envh) - **Star : 94** **最近提交 : 2019-05-20**  协助管理环境变量的Helpers。
* [gcfg](https://github.com/go-gcfg/gcfg) - **Star : 115** **最近提交 : 2018-05-18**  将ini的配置文件读入 Go structs中;支持用户定义的类型和子选项。![star > 100][Bronze]
* [go-up](https://github.com/ufoscout/go-up) - **Star : 24** **最近提交 : 2019-03-04**  一个简单的配置库，具有递归占位符解析功能。
* [goConfig](https://github.com/crgimenes/goConfig) - **Star : 102** **最近提交 : 2019-05-15**  将结构体解析为输入，并用来自命令行、环境变量和配置文件的参数填充该结构体的字段。![star > 100][Bronze]
* [godotenv](https://github.com/joho/godotenv) - **Star : 2045** **最近提交 : 2019-06-17**  Ruby 的 dotenv 库的 Go移植版(从.env文件加载环境变量)。![star > 1000][Silver]
* [gofigure](https://github.com/ian-kent/gofigure) - **Star : 57** **最近提交 : 2017-05-03**  让程序配置变得简单。
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - 模块化的JSON配置。保持配置结构及其配置的代码，并将解析委托给子模块，而不牺牲配置的完整序列化。
* [gookit/config](https://github.com/gookit/config) - **Star : 71** **最近提交 : 2019-07-01**  程序配置管理(load,get,set)。支持JSON, YAML, TOML, INI, HCL。支持多文件加载，数据覆盖合并。
* [harvester](https://github.com/beatlabs/harvester) - **Star : 19** **最近提交 : 2019-06-26**  一个易于使用的静态和动态配置包
* [hjson](https://github.com/hjson/hjson-go) - **Star : 171** **最近提交 : 2019-02-09**  更加人性化的JSON配置。轻松的语法，更少的错误，更多的注释。![star > 100][Bronze]
* [ingo](https://github.com/schachmat/ingo) - **Star : 23** **最近提交 : 2017-04-03**  flag保存在类ini的配置文件中。
* [ini](https://github.com/go-ini/ini) - **Star : 1516** **最近提交 : 2019-05-23**   读和写INI文件。![star > 1000][Silver]
* [joshbetz/config](https://github.com/joshbetz/config) - **Star : 195** **最近提交 : 2017-08-11**  一个可解析环境变量、JSON文件小巧的配置库，在SIGHUP时会自动重新加载。![star > 100][Bronze]
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - **Star : 2338** **最近提交 : 2019-06-17**  管理来自环境变量的配置数据。![star > 1000][Silver]
* [koanf](https://github.com/knadh/koanf) - **Star : 67** **最近提交 : 2019-06-27**  轻量级可扩展库，用于读取Go应用程序中的配置。内置支持JSON, TOML, YAML, env，命令行。
* [konfig](https://github.com/lalamove/konfig) - **Star : 507** **最近提交 : 2019-06-18**  可组合、可观察和高性能的分布式配置管理。![star > 100][Bronze]
* [mini](https://github.com/sasbury/mini) - **Star : 19** **最近提交 : 2018-12-27**  用于解析ini类型的配置文件。
* [sprbox](https://github.com/oblq/sprbox) - **Star : 3** **最近提交 : 2018-10-31**  支持构建环境的工具箱工厂和其他不确定的配置解析器(如YAML、TOML、JSON和环境vars)。
* [store](https://github.com/tucnak/store) - **Star : 242** **最近提交 : 2017-09-05**  轻量级配置管理器。![star > 100][Bronze]
* [viper](https://github.com/spf13/viper) - **Star : 8943** **最近提交 : 2019-06-23**  配置管理。![star > 5000][Gold]
* [xdg](https://github.com/OpenPeeDeeP/xdg) - **Star : 32** **最近提交 : 2019-03-12**  遵循[XDG标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html)的跨平台包。

## 持续集成

*用于帮助进行持续集成的工具。*

* [drone](https://github.com/drone/drone) - **Star : 18666** **最近提交 : 2019-06-25**  Drone 是一个基于 Docker 的持续集成平台，用 Go 编写。![star > 5000][Gold]
* [duci](https://github.com/duck8823/duci) - **Star : 40** **最近提交 : 2019-06-22**  一个简单的 ci 服务。
* [gomason](https://github.com/nikogura/gomason) - **Star : 27** **最近提交 : 2019-06-13**  在一个干净的工作区中对你的 Go 二进制文件进行测试、构建、签名和发布。
* [goveralls](https://github.com/mattn/goveralls) - **Star : 570** **最近提交 : 2019-06-05**  Coveralls.io 是一个用 Go 编写，可持续对代码覆盖率进行检测的系统。![star > 100][Bronze]
* [overalls](https://github.com/go-playground/overalls) - **Star : 97** **最近提交 : 2018-08-26**  针对多package 的 Go 语言项目，可为类似 goveralls 这样的工具生成覆盖率报告。
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - **Star : 12** **最近提交 : 2017-11-20**  递归覆盖测试工具。

## CSS预处理器

*用于预处理CSS文件的库。*

* [gcss](https://github.com/yosssi/gcss) - **Star : 421** **最近提交 : 2014-10-12**  纯Go编写的 CSS 预处理器。![star > 100][Bronze]
* [go-libsass](https://github.com/wellington/go-libsass) - **Star : 128** **最近提交 : 2019-02-12**   采用 Go封装，100% 与 Sass 兼容的 libsass 项目。![star > 100][Bronze]

## 数据结构

*用 Go 实现的通用的数据结构和算法。*

* [algorithms](https://github.com/shady831213/algorithms) - **Star : 228** **最近提交 : 2019-04-03**  算法和数据结构。来源于CLRS。![star > 100][Bronze]
* [binpacker](https://github.com/zhuangsirui/binpacker) - **Star : 120** **最近提交 : 2018-06-17**  帮助用户构建自定义二进制流的二进制封装器和解包器![star > 100][Bronze]
* [bit](https://github.com/yourbasic/bit) - **Star : 51** **最近提交 : 2018-03-13**  Go 语言集合数据结构。提供了额外的位操作功能。
* [bitset](https://github.com/willf/bitset) - **Star : 476** **最近提交 : 2019-04-04**  实现了 bitsets 的 Go 包。![star > 100][Bronze]
* [bloom](https://github.com/zhenjl/bloom) - **Star : 128** **最近提交 : 2018-04-16**  在Go中实现了Bloom过滤器。![star > 100][Bronze]
* [bloom](https://github.com/yourbasic/bloom) - **Star : 38** **最近提交 : 2017-06-20**  Golang Bloom过滤器的实现。
* [boomfilters](https://github.com/tylertreat/BoomFilters) - **Star : 1121** **最近提交 : 2018-10-29**  用于处理连续的概率数据结构。![star > 1000][Silver]
* [concurrent-writer](https://github.com/free/concurrent-writer) - **Star : 22** **最近提交 : 2017-11-18**  具备高并发能力，可替换 bufio.Writer。
* [conjungo](https://github.com/InVisionApp/conjungo) - **Star : 75** **最近提交 : 2019-05-22**  一个小型、强大和灵活的合并库。
* [count-min-log](https://github.com/seiflotfy/count-min-log) - **Star : 43** **最近提交 : 2017-02-12**  Go实现Count-Min-log sketch的功能 : 使用近似计数器进行近似计数(类似Count-Min sketch，但使用更少内存)。
* [crunch](https://github.com/superwhiskers/crunch) - **Star : 19** **最近提交 : 2019-06-20**  打包实现缓冲区，以便轻松处理各种数据类型。
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - **Star : 493** **最近提交 : 2019-03-03**  布谷鸟过滤器:一个用Go实现，可替代计数 bloom 过滤器。![star > 100][Bronze]
* [deque](https://github.com/edwingeng/deque) - **Star : 4** **最近提交 : 2019-02-13**  高度优化的双端队列。
* [deque](https://github.com/gammazero/deque) - **Star : 58** **最近提交 : 2019-05-21**  快速环缓冲区deque(双端队列)。
* [dict](https://github.com/srfrog/dict) - **Star : 7** **最近提交 : 2019-06-17**  实现类似 python dict的功能(dict)。
* [encoding](https://github.com/zhenjl/encoding) - **Star : 94** **最近提交 : 2017-12-24**  整形压缩库。
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - **Star : 83** **最近提交 : 2019-05-30**  自适应基数树。
* [go-datastructures](https://github.com/Workiva/go-datastructures) - **Star : 5040** **最近提交 : 2019-03-06**  可靠的、高性能的和线程安全的数据结构的集合。![star > 5000][Gold]
* [go-ef](https://github.com/amallia/go-ef) - **Star : 10** **最近提交 : 2017-09-26**  实现了 Elias-Fano 编码。
* [go-geoindex](https://github.com/hailocab/go-geoindex) - **Star : 309** **最近提交 : 2018-02-21**  基于内存的地理索引。![star > 100][Bronze]
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - **Star : 32** **最近提交 : 2019-05-20**  基于内存的实现了高性能的key:value存储库。指针缓存。
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - **Star : 98** **最近提交 : 2018-06-18**  区域四叉树具有高效的点定位和邻域查找功能。
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - **Star : 23** **最近提交 : 2019-06-05**  并行FIFO队列。
* [gods](https://github.com/emirpasic/gods) - **Star : 6022** **最近提交 : 2019-06-24**  数据结构。容器、集合、列表、堆栈、地图、BidiMaps、树、HashSet等。![star > 5000][Gold]
* [golang-set](https://github.com/deckarep/golang-set) - **Star : 1117** **最近提交 : 2018-09-27**  线程安全和非线程安全的高性能集。![star > 1000][Silver]
* [goset](https://github.com/zoumo/goset) - **Star : 16** **最近提交 : 2017-08-25**  一个有用的Go集合实现。
* [goskiplist](https://github.com/ryszard/goskiplist) - **Star : 191** **最近提交 : 2017-02-24**  基于 Go 的跳表实现。![star > 100][Bronze]
* [gota](https://github.com/kniren/gota) - **Star : 850** **最近提交 : 2019-06-14**  实现了数据帧，序列以及数据噪音。![star > 100][Bronze]
* [hide](https://github.com/emvi/hide) - **Star : 7** **最近提交 : 2019-03-08**  ID type with marshalling to/from hash to prevent sending IDs to clients.
* [hilbert](https://github.com/google/hilbert) - **Star : 178** **最近提交 : 2018-11-22**  用于映射空间填充曲线（例如 Hilbert 曲线和 Peano 曲线）和数值。![star > 100][Bronze]
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - **Star : 657** **最近提交 : 2019-06-07**  HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.![star > 100][Bronze]
* [levenshtein](https://github.com/agext/levenshtein) - **Star : 32** **最近提交 : 2019-02-23**  Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* [levenshtein](https://github.com/agnivade/levenshtein) - **Star : 53** **最近提交 : 2019-06-14**  实现在Go中计算levenshtein距离。
* [mafsa](https://github.com/smartystreets/mafsa) - **Star : 272** **最近提交 : 2019-06-04**  实现了 MA-FSA ，包含最小完美哈希。![star > 100][Bronze]
* [merkletree](https://github.com/cbergoon/merkletree) - **Star : 142** **最近提交 : 2019-03-08**  实现了merkle树，提供了对数据结构内容的有效和安全的验证。![star > 100][Bronze]
* [mspm](https://github.com/BlackRabbitt/mspm) - **Star : 7** **最近提交 : 2018-05-19**  用于信息检索的多字符串模式匹配算法。
* [null](https://github.com/emvi/null) - **Star : 5** **最近提交 : 2019-04-23**  对空的 Go 数据类型也可以进行JSON进行解析/反解析。
* [parsefields](https://github.com/MonaxGT/parsefields) - **Star : 3** **最近提交 : 2019-05-06**  用于解析类似json的日志的工具，用于收集惟一的字段和事件。
* [pipeline](https://github.com/hyfather/pipeline) - **Star : 15** **最近提交 : 2018-08-31**  实现了 fan-in 和 fan-out 的管道功能。
* [ring](https://github.com/TheTannerRyan/ring) - **Star : 86** **最近提交 : 2019-06-02**  高性能、线程安全的bloom过滤器。
* [roaring](https://github.com/RoaringBitmap/roaring) - **Star : 642** **最近提交 : 2019-06-24**  实现了压缩 bitsets 的Go包。![star > 100][Bronze]
* [set](https://github.com/StudioSol/set) - **Star : 6** **最近提交 : 2018-10-10**  使用LinkedHashMap在Go中实现简单的set数据结构。
* [skiplist](https://github.com/MauriceGit/skiplist) - **Star : 96** **最近提交 : 2018-12-08**  高性能的 Go 跳表实现。
* [skiplist](https://github.com/gansidui/skiplist) - **Star : 62** **最近提交 : 2014-11-21**  在Go中实现了跳表。
* [timedmap](https://github.com/zekroTJA/timedmap) - **Star : 1** **最近提交 : 2019-02-20**  实现了有生命周期的键值对Map。
* [treap](https://github.com/perdata/treap) - **Star : 7** **最近提交 : 2018-09-17**  使用树堆进行持久、快速有序的映射。
* [trie](https://github.com/derekparker/trie) - **Star : 408** **最近提交 : 2019-03-23**  在Go中实现Trie。![star > 100][Bronze]
* [ttlcache](https://github.com/diegobernardes/ttlcache) - **Star : 91** **最近提交 : 2019-06-17**  基于内存的LRU算法实现。
* [typ](https://github.com/gurukami/typ) - **Star : 9** **最近提交 : 2019-05-21**  从复杂结构中获取值，支持空类型、安全的类型转换。
* [willf/bloom](https://github.com/willf/bloom) - **Star : 646** **最近提交 : 2019-03-01**  实现Bloom过滤器。![star > 100][Bronze]

## 数据库

*数据库。*

* [badger](https://github.com/dgraph-io/badger) - **Star : 6083** **最近提交 : 2019-07-01**  快速 K/V 存储。![star > 5000][Gold]
* [bcache](https://github.com/iwanbk/bcache) - **Star : 25** **最近提交 : 2019-05-01**  基于内存的最终一致的分布式缓存。
* [BigCache](https://github.com/allegro/bigcache) - **Star : 2379** **最近提交 : 2019-06-26**  高效的键/值缓存为千兆字节的数据。![star > 1000][Silver]
* [bolt](https://github.com/boltdb/bolt) - **Star : 9859** **最近提交 : 2018-03-03**  K/V 数据库。![star > 5000][Gold]
* [buntdb](https://github.com/tidwall/buntdb) - **Star : 2417** **最近提交 : 2019-03-15**  基于内存的K/V，快速，可嵌入的数据库，可自定义索引和空间支持。![star > 1000][Silver]
* [cache](https://github.com/akyoto/cache) - **Star : 10** **最近提交 : 2019-05-24**  基于内存的 K/V 存储:带生命周期的值存储，0个依赖项，<100 LoC, 100%覆盖率。
* [cache2go](https://github.com/muesli/cache2go) - **Star : 926** **最近提交 : 2019-06-09**  基于内存的 K/V 缓存，支持超时的自动失效。![star > 100][Bronze]
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - **Star : 29** **最近提交 : 2018-01-23**  BigCache 支持集群和独立且生命周期存储项。
* [cockroach](https://github.com/cockroachdb/cockroach) - **Star : 16545** **最近提交 : 2019-07-01**  可伸缩、区域备份、事务性数据存储。![star > 5000][Gold]
* [couchcache](https://github.com/codingsince1985/couchcache) - **Star : 40** **最近提交 : 2019-04-23**  由 Couchbase服务 支持的RESTful缓存微服务。
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - **Star : 1421** **最近提交 : 2019-07-01**  区块链领域的一个SQL数据库。![star > 1000][Silver]
* [dgraph](https://github.com/dgraph-io/dgraph) - **Star : 9885** **最近提交 : 2019-06-30**  可伸缩、分布式、低延迟、高吞吐量的图形数据库。![star > 5000][Gold]
* [diskv](https://github.com/peterbourgon/diskv) - **Star : 736** **最近提交 : 2019-04-25**  支持磁盘备份的可持久化 K/V 存储。![star > 100][Bronze]
* [eliasdb](https://github.com/krotik/eliasdb) - **Star : 531** **最近提交 : 2019-03-13**  无其他依赖项，支持REST API，短语搜索和sql类似的查询语言的事务图数据库。![star > 100][Bronze]
* [fastcache](https://github.com/VictoriaMetrics/fastcache) - **Star : 467** **最近提交 : 2019-06-12**  基于内存的快速线程安全的缓存，可缓存大量的条目。最大限度地减少GC开销。![star > 100][Bronze]
* [GCache](https://github.com/bluele/gcache) - **Star : 861** **最近提交 : 2019-06-19**  支持过期缓存、LFU、LRU和ARC的缓存库。![star > 100][Bronze]
* [go-cache](https://github.com/pmylund/go-cache) - **Star : 2785** **最近提交 : 2019-06-24**  基于内存的 K/V 存储/缓存 : (类似于Memcached)，适用于单机应用程序。![star > 1000][Silver]
* [goleveldb](https://github.com/syndtr/goleveldb) - **Star : 3095** **最近提交 : 2019-06-25**  在Go中实现[LevelDB](https://github.com/google/leveldb) key/value数据库。![star > 1000][Silver]
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - **Star : 7** **最近提交 : 2018-01-11**  用 Go 对[RocksDB](https://rocksdb.org)实现了封装。
* [groupcache](https://github.com/golang/groupcache) - **Star : 7538** **最近提交 : 2019-02-13**  Groupcache是一个缓存和缓存填充库，在许多情况下，它是memcached的替代品。![star > 5000][Gold]
* [influxdb](https://github.com/influxdb/influxdb) - **Star : 16679** **最近提交 : 2019-06-29**  可伸缩的数据存储，用于指标衡量、事件和实时分析。![star > 5000][Gold]
* [ledisdb](https://github.com/siddontang/ledisdb) - **Star : 3037** **最近提交 : 2019-05-24**  Ledisdb是一种高性能的NoSQL，类似于基于LevelDB的Redis。![star > 1000][Silver]
* [levigo](https://github.com/jmhodges/levigo) - **Star : 363** **最近提交 : 2019-06-24**  实现了对LevelDB封装。![star > 100][Bronze]
* [moss](https://github.com/couchbase/moss) - **Star : 714** **最近提交 : 2019-06-13**  Moss是一个用100% Go编写的简单LSM键值存储引擎。![star > 100][Bronze]
* [nutsdb](https://github.com/xujiajun/nutsdb) - **Star : 843** **最近提交 : 2019-05-06**  Nutsdb是一个用纯Go编写的简单、快速、可嵌入、持久的键/值存储。它支持完全序列化的事务和许多数据结构，如列表、集合、排序集。![star > 100][Bronze]
* [piladb](https://github.com/fern4lvarez/piladb) - **Star : 170** **最近提交 : 2018-04-08**  基于堆栈数据结构的轻量级RESTful数据库引擎。![star > 100][Bronze]
* [prometheus](https://github.com/prometheus/prometheus) - **Star : 24851** **最近提交 : 2019-06-30**  用于监控系统和时序的数据库。![star > 5000][Gold]
* [pudge](https://github.com/recoilme/pudge) - **Star : 213** **最近提交 : 2019-05-13**  使用Go的标准库编写的快速和简单的键/值存储。![star > 100][Bronze]
* [rqlite](https://github.com/rqlite/rqlite) - **Star : 4631** **最近提交 : 2019-06-03**  基于SQLite的轻量级分布式关系数据库。![star > 1000][Silver]
* [Scribble](https://github.com/nanobox-io/golang-scribble) - **Star : 55** **最近提交 : 2019-03-10**  小型平面文件JSON存储。
* [slowpoke](https://github.com/recoilme/slowpoke) - **Star : 84** **最近提交 : 2018-12-24**  具有持久性的键值存储。
* [tempdb](https://github.com/rafaeljesus/tempdb) - **Star : 13** **最近提交 : 2018-02-15**  用于临时数据存放的 K/V 存储。
* [tidb](https://github.com/pingcap/tidb) - **Star : 19467** **最近提交 : 2019-07-01**  TiDB是一个分布式SQL数据库。灵感来自谷歌F1的设计。![star > 5000][Gold]
* [tiedot](https://github.com/HouzuoGuo/tiedot) - **Star : 2353** **最近提交 : 2019-01-26**  属于你的NoSQL数据库。![star > 1000][Silver]
* [Vasto](https://github.com/chrislusf/vasto) - **Star : 142** **最近提交 : 2019-03-08**  分布式高性能键值存储。可做磁盘备份。最终一致。高可用。能够在不中断服务的情况下增长或收缩。![star > 100][Bronze]
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - **Star : 862** **最近提交 : 2019-07-01**  开源，快速，可伸缩的时间序列数据库。支持PromQL。![star > 100][Bronze]

*数据库迁移。*

* [avro](https://github.com/khezen/avro) - **Star : 3** **最近提交 : 2019-06-25**  发现SQL schemas并将其转换为AVRO schemas。
* [darwin](https://github.com/GuiaBolso/darwin) - **Star : 84** **最近提交 : 2018-11-28**  用于数据库 schema 升级的库。
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - **Star : 19** **最近提交 : 2018-11-01**  类似 Django fixture，用于 Go 建立内置数据库/sql库。
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - **Star : 24** **最近提交 : 2018-12-23**  用Go -pg/pg编写的迁移包。
* [gondolier](https://github.com/emvi/gondolier) - **Star : 26** **最近提交 : 2019-05-14**  使用结构修饰的数据库迁移库。
* [goose](https://github.com/steinbacher/goose) - **Star : 117** **最近提交 : 2016-09-24**  数据库迁移工具。您可以通过创建增量SQL或Go脚本来管理数据库的升级。![star > 100][Bronze]
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - **Star : 316** **最近提交 : 2019-06-25**  面向Gorm ORM的数据库 schema 迁移辅助程序。![star > 100][Bronze]
* [migrate](https://github.com/golang-migrate/migrate) - **Star : 2412** **最近提交 : 2019-06-27**  基于CLI的数据库迁移库。![star > 1000][Silver]
* [migrator](https://github.com/lopezator/migrator) - **Star : 26** **最近提交 : 2019-06-19**  非常简单的 Go 数据库迁移库。
* [pravasan](https://github.com/pravasan/pravasan) - **Star : 24** **最近提交 : 2018-12-20**  简易的迁移工具-目前只支持MySQL，但计划很快支持Postgres, SQLite, MongoDB等。
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) - 数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。
* [sql-migrate](https://github.com/rubenv/sql-migrate) - **Star : 1369** **最近提交 : 2019-06-18**  数据库迁移工具。允许使用go-bindata将迁移嵌入到应用程序中。![star > 1000][Silver]

*数据库工具。*

* [chproxy](https://github.com/Vertamedia/chproxy) - **Star : 293** **最近提交 : 2019-05-04**  ClickHouse数据库的HTTP代理。![star > 100][Bronze]
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - **Star : 127** **最近提交 : 2019-04-16**  收集小的 insterts 并向 ClickHouse 服务器发送大请求。![star > 100][Bronze]
* [datagen](https://github.com/codingconcepts/datagen) - **Star : 5** **最近提交 : 2019-06-18**  一个快速的数据生成器，支持多表感知和多行DML。
* [dbbench](https://github.com/sj14/dbbench) - **Star : 30** **最近提交 : 2019-02-02**  数据库基准测试工具，支持多个数据库和脚本。
* [go-mysql](https://github.com/siddontang/go-mysql) - **Star : 1799** **最近提交 : 2019-07-01**   Go 工具集，用于处理MySQL协议和复制。![star > 1000][Silver]
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - **Star : 2281** **最近提交 : 2019-06-10**  自动将MySQL数据同步到Elasticsearch中。![star > 1000][Silver]
* [kingshard](https://github.com/flike/kingshard) - **Star : 4523** **最近提交 : 2019-05-15**  kingshard 是基于 Golang 的MySQL高性能代理。![star > 1000][Silver]
* [myreplication](https://github.com/2tvenom/myreplication) - **Star : 141** **最近提交 : 2018-10-05**  MySql二进制日志复制监听器。支持基于语句和行的复制。![star > 100][Bronze]
* [octillery](https://github.com/knocknote/octillery) - **Star : 46** **最近提交 : 2019-04-28**  用于数据库分表(支持每个ORM或原生SQL)。
* [orchestrator](https://github.com/github/orchestrator) - **Star : 2944** **最近提交 : 2019-06-28**  MySQL复制拓扑管理器和可视化工具。![star > 1000][Silver]
* [pgweb](https://github.com/sosedoff/pgweb) - **Star : 5936** **最近提交 : 2019-02-26**  基于web的PostgreSQL数据库浏览器。![star > 5000][Gold]
* [prep](https://github.com/hexdigest/prep) - **Star : 24** **最近提交 : 2017-12-20**  在不更改代码的情况下使用准备好的SQL语句。
* [pREST](https://github.com/nuveo/prest) - **Star : 2053** **最近提交 : 2019-05-29**  基于PostgreSQL database的RESTful API服务。![star > 1000][Silver]
* [rwdb](https://github.com/andizzle/rwdb) - **Star : 10** **最近提交 : 2017-11-08**  rwdb为多个数据库服务器的设置提供读取副本功能。
* [vitess](https://github.com/youtube/vitess) - **Star : 8265** **最近提交 : 2019-07-01**  vitess提供了可以为大规模web服务扩展MySQL数据库提供便利的服务和工具。![star > 5000][Gold]

*SQL查询生成器，用于构建和使用SQL的库。*

* [Dotsql](https://github.com/gchaincl/dotsql) - **Star : 433** **最近提交 : 2019-05-08**  Go library帮助您将sql文件保存在一个地方，并轻松地使用它们。![star > 100][Bronze]
* [gendry](https://github.com/didi/gendry) - **Star : 695** **最近提交 : 2019-05-15**  非入侵的SQL构建器和强大的数据绑定器。![star > 100][Bronze]
* [godbal](https://github.com/xujiajun/godbal) - **Star : 50** **最近提交 : 2019-01-30**  数据库抽象层(dbal)。支持SQL builder，轻松获取结果。
* [goqu](https://github.com/doug-martin/goqu) - **Star : 520** **最近提交 : 2019-06-20**  常用的SQL生成器和查询库。![star > 100][Bronze]
* [igor](https://github.com/galeone/igor) - **Star : 77** **最近提交 : 2018-07-01**  PostgreSQL的抽象层，支持高级功能和类似gorm的语法。
* [ormlite](https://github.com/pupizoid/ormlite) - 包含一些类似orm的特性和sqlite数据库的辅助程序的轻量级包
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - **Star : 434** **最近提交 : 2019-05-14**  Powerful data retrieval methods as well as DB-agnostic query building capabilities.![star > 100][Bronze]
* [scaneo](https://github.com/variadico/scaneo) - **Star : 149** **最近提交 : 2018-04-03**  生成用于将数据库行转换为任意结构体的 Go 代码。![star > 100][Bronze]
* [sqrl](https://github.com/elgris/sqrl) - **Star : 172** **最近提交 : 2019-01-30**  SQL查询生成器，从Squirrel fork而来，并再此基础上对性能做了优化。![star > 100][Bronze]
* [Squalus](https://gitlab.com/qosenergy/squalus) - Go SQL中间层，能使得执行查询更加容易。
* [Squirrel](https://github.com/Masterminds/squirrel) - **Star : 2189** **最近提交 : 2019-06-19**  帮助您构建SQL查询的Go库。![star > 1000][Silver]
* [xo](https://github.com/knq/xo) - **Star : 2113** **最近提交 : 2019-07-01**  基于现有的schema定义和自定义查询生成 Go 代码，基于支持PostgreSQL、MySQL、SQLite、Oracle和Microsoft SQL Server。![star > 1000][Silver]

## 数据库驱动程序

*用于连接和操作数据库的库。*

* Relational Databases
    * [avatica](https://github.com/apache/calcite-avatica-go) - **Star : 31** **最近提交 : 2019-05-15**  Apache Avatica/Phoenix SQL驱动程序。
    * [bgc](https://github.com/viant/bgc) - **Star : 12** **最近提交 : 2019-05-08**  BigQuery 的数据存储连接。
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - **Star : 102** **最近提交 : 2019-06-09**  Firebird RDBMS SQL驱动程序。![star > 100][Bronze]
    * [go-adodb](https://github.com/mattn/go-adodb) - **Star : 90** **最近提交 : 2019-06-06**  Microsoft ActiveX对象数据库驱动程序。
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - **Star : 991** **最近提交 : 2019-06-25**  微软MSSQL驱动程序。![star > 100][Bronze]
    * [go-oci8](https://github.com/mattn/go-oci8) - **Star : 397** **最近提交 : 2019-05-24**  Oracle 驱动程序。![star > 100][Bronze]
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - **Star : 7851** **最近提交 : 2019-06-28**  MySQL驱动程序。![star > 5000][Gold]
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - **Star : 3346** **最近提交 : 2019-06-20**  SQLite3驱动程序。![star > 1000][Silver]
    * [gofreetds](https://github.com/minus5/gofreetds) - **Star : 90** **最近提交 : 2019-02-20**  基于[FreeTDS](http://www.freetds.org)封装的微软MSSQL Go 驱动。
    * [goracle](https://github.com/go-goracle/goracle) - **Star : 226** **最近提交 : 2019-06-27**  基于 ODPI-C 的 Oracle 驱动程序![star > 100][Bronze]
    * [pgx](https://github.com/jackc/pgx) - **Star : 1853** **最近提交 : 2019-06-30**  PostgreSQL驱动，支持比现有database/sql更多的特性。![star > 1000][Silver]
    * [pq](https://github.com/lib/pq) - **Star : 5061** **最近提交 : 2019-06-20**  纯 Go 的Postgres驱动。![star > 5000][Gold]

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - **Star : 301** **最近提交 : 2019-05-22**  Aerospike 客户端。![star > 100][Bronze]
    * [arangolite](https://github.com/solher/arangolite) - **Star : 65** **最近提交 : 2019-04-25**  轻量级的 ArangoDB 驱动。
    * [asc](https://github.com/viant/asc) - **Star : 4** **最近提交 : 2019-04-20**  Aerospike 的数据存储连接器。
    * [dynago](https://github.com/underarmour/dynago) - **Star : 65** **最近提交 : 2017-08-08**  满足 principle of least surprise 的 DynamoDB 客户端。
    * [forestdb](https://github.com/couchbase/goforestdb) - **Star : 30** **最近提交 : 2016-12-16**  基于 Go 的 ForestDB 接口实现。
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - **Star : 291** **最近提交 : 2019-06-28**  Couchbase客户端。![star > 100][Bronze]
    * [go-couchdb](https://github.com/fjl/go-couchdb) - **Star : 52** **最近提交 : 2018-09-05**  基于 Go 的 Yet another CouchDB 的 Http 接口封装。
    * [go-pilosa](https://github.com/pilosa/go-pilosa) - **Star : 32** **最近提交 : 2019-06-26**   Pilosa客户端。
    * [go-rejson](https://github.com/nitishm/go-rejson) - **Star : 81** **最近提交 : 2019-05-31**  实现了基于 Redigo 客户端的redislabs' ReJSON 模块。可简单地将结构体存储为JSON对象并对其进行操作。
    * [gocb](https://github.com/couchbase/gocb) - **Star : 289** **最近提交 : 2019-07-01**  官方Couchbase Go SDK。![star > 100][Bronze]
    * [gocql](http://gocql.github.io) - Apache Cassandra 的 Go 驱动。
    * [godscache](https://github.com/defcronyke/godscache) - **Star : 6** **最近提交 : 2019-02-08**  谷歌云平台Go Datastore包的封装，它采用了memcached添加缓存。
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache客户端库。
    * [gorethink](https://github.com/dancannon/gorethink) - **Star : 1456** **最近提交 : 2019-06-02**  RethinkDB 驱动。![star > 1000][Silver]
    * [goriak](https://github.com/zegl/goriak) - **Star : 24** **最近提交 : 2018-12-28**   Riak KV 驱动。
    * [mgo](https://github.com/globalsign/mgo) - **Star : 1596** **最近提交 : 2019-06-19**  (已停止维护) MongoDB驱动。![star > 1000][Silver]
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - **Star : 2879** **最近提交 : 2019-06-29**  官方的 MongoDB 驱动。![star > 1000][Silver]
    * [neo4j](https://github.com/cihangir/neo4j) - **Star : 24** **最近提交 : 2015-04-03**  Neo4j Rest API实现。
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - **Star : 72** **最近提交 : 2018-06-20**  Neo4j REST 客户端。
    * [neoism](https://github.com/jmcvetta/neoism) - **Star : 355** **最近提交 : 2019-02-19**  Golang 的 Neo4j 客户端。![star > 100][Bronze]
    * [redeo](https://github.com/bsm/redeo) - **Star : 257** **最近提交 : 2018-11-29**  与 redis 协议兼容的 TCP 服务器/服务。![star > 100][Bronze]
    * [redigo](https://github.com/gomodule/redigo) - **Star : 6111** **最近提交 : 2019-06-21**  Redigo 是基于 Go 的Redis 客户端。![star > 5000][Gold]
    * [redis](https://github.com/go-redis/redis) - **Star : 6154** **最近提交 : 2019-07-01**  基于 Go 的 Redis 客户端。![star > 5000][Gold]
    * [xredis](https://github.com/shomali11/xredis) - **Star : 9** **最近提交 : 2019-06-08**  类型安全，可定制，清晰和易用的Redis客户端。

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - **Star : 5740** **最近提交 : 2019-06-29**  基于 Go 的现代文本索引库。![star > 5000][Gold]
    * [elastic](https://github.com/olivere/elastic) - **Star : 3990** **最近提交 : 2019-06-30**  Elasticsearch 客户端。![star > 1000][Silver]
    * [elasticsql](https://github.com/cch123/elasticsql) - **Star : 367** **最近提交 : 2019-03-21**  将 SQL 转换为 elasticsearch dsl。![star > 100][Bronze]
    * [elastigo](https://github.com/mattbaird/elastigo) - **Star : 948** **最近提交 : 2019-02-06**  Elasticsearch 客户端。![star > 100][Bronze]
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - **Star : 1456** **最近提交 : 2019-06-30**  官方 Elasticsearch 客户端。![star > 1000][Silver]
    * [goes](https://github.com/OwnLocal/goes) - **Star : 24** **最近提交 : 2017-03-03**  实现了与 Elasticsearch 交互的库。
    * [riot](https://github.com/go-ego/riot) - **Star : 4621** **最近提交 : 2019-06-03**  基于 Go 的 开源、分布式、简单高效的搜索引擎。![star > 1000][Silver]
    * [skizze](https://github.com/seiflotfy/skizze) - **Star : 68** **最近提交 : 2016-05-10**  面向概率数据结构的服务和存储。

* Multiple Backends.
    * [cachego](https://github.com/fabiorphp/cachego) - **Star : 109** **最近提交 : 2019-05-09**  基于多个驱动程序的缓存组件。![star > 100][Bronze]
    * [cayley](https://github.com/google/cayley) - **Star : 12595** **最近提交 : 2019-07-01**  图形数据库，支持多个后端。![star > 5000][Gold]
    * [dsc](https://github.com/viant/dsc) - **Star : 12** **最近提交 : 2019-06-07**  面向 SQL、NoSQL、结构化文件的数据存储连接。
    * [gokv](https://github.com/philippgille/gokv) - **Star : 74** **最近提交 : 2019-06-20**  可扩展的简单的 K/V 存储(Redis、、etcd、bbolt、BadgerDB、LevelDB、Memcached、DynamoDB、S3、PostgreSQL、MongoDB、CockroachDB等等)。

## 日期和时间

*用于处理日期和时间的库。*

* [carbon](https://github.com/uniplaces/carbon) - **Star : 330** **最近提交 : 2019-01-16**  简单的时间扩展，包含了许多使用方法，从 PHP Carbon 库移植的。![star > 100][Bronze]
* [date](https://github.com/rickb777/date) - **Star : 27** **最近提交 : 2019-06-17**  增加处理日期、日期范围、时间跨度、时间段和time-of-day。
* [dateparse](https://github.com/araddon/dateparse) - **Star : 875** **最近提交 : 2019-06-23**  可以解析很多格式不固定的日期字符串。![star > 100][Bronze]
* [durafmt](https://github.com/hako/durafmt) - **Star : 235** **最近提交 : 2019-06-13**  轻量级、可让time.Duration更加易读的库。![star > 100][Bronze]
* [feiertage](https://github.com/wlbr/feiertage) - **Star : 21** **最近提交 : 2019-05-26**  用于计算德国公共假期的函数，比如复活节、感恩节等
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - **Star : 58** **最近提交 : 2019-03-16**  太阳历实现。
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - **Star : 13** **最近提交 : 2017-11-22**  计算指定位置的日出和日落时间。
* [goweek](https://github.com/grsmv/goweek) - **Star : 18** **最近提交 : 2017-01-04**  用于处理以星期实体单位的库。
* [iso8601](https://github.com/relvacode/iso8601) - **Star : 67** **最近提交 : 2018-12-21**  不用正则表达式有效解析 ISO8601 日期时间。
* [kair](https://github.com/GuilhermeCaruso/kair) - **Star : 9** **最近提交 : 2019-02-24**  用于处理日期和时间的 golang 库。
* [now](https://github.com/jinzhu/now) - **Star : 2126** **最近提交 : 2019-06-13**  now 是时间有关的工具类。![star > 1000][Silver]
* [NullTime](https://github.com/kirillDanshin/nulltime) - **Star : 9** **最近提交 : 2017-03-22**  可以允许 time.Time 为null。
* [strftime](https://github.com/awoodbeck/strftime) - **Star : 5** **最近提交 : 2018-02-21**  C99-compatible strftime formatter。
* [timespan](https://github.com/SaidinWoT/timespan) - **Star : 60** **最近提交 : 2019-03-20**  用于处理时间间隔相关的库，可定义开始时间和持续时间。
* [timeutil](https://github.com/leekchan/timeutil) - **Star : 168** **最近提交 : 2019-02-03**  面向 Golang 的时间库，集成了很多有用的扩展(Timedelta, Strftime, ...)。![star > 100][Bronze]
* [tuesday](https://github.com/osteele/tuesday) - **Star : 7** **最近提交 : 2017-08-30**  Ruby-compatible Strftime function。

## 分布式系统

*协助构建分布式系统的包。*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - **Star : 52** **最近提交 : 2018-12-08**  用于对 Celery worker、任务、事件进行交互和监控的库。
* [consistent](https://github.com/buraksezer/consistent) - **Star : 181** **最近提交 : 2019-05-24**  Consistent hashing with bounded loads。![star > 100][Bronze]
* [dht](https://github.com/anacrolix/dht) - **Star : 121** **最近提交 : 2019-05-13**  BitTorrent Kademlia DHT的实现。![star > 100][Bronze]
* [digota](https://github.com/digota/digota) - **Star : 296** **最近提交 : 2018-10-15**  基于 grpc 的电子商务微服务。![star > 100][Bronze]
* [dot](https://github.com/dotchain/dot/) - 基于 transformation/OT 的分布式同步。
* [doublejump](https://github.com/edwingeng/doublejump) - **Star : 37** **最近提交 : 2019-01-02**  实现了谷歌的jump consistent hash。
* [dragonboat](https://github.com/lni/dragonboat) - **Star : 2434** **最近提交 : 2019-07-01**  一个功能齐全，高性能的库集。![star > 1000][Silver]
* [drmaa](https://github.com/dgruber/drmaa) - **Star : 24** **最近提交 : 2018-05-14**  符合 DRMAA 标准的集群调度程序作业提交库。
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed 分布式锁定实现。
* [dynatomic](https://github.com/tylfin/dynatomic) - **Star : 8** **最近提交 : 2019-02-21**  基于 DynamoDB 的 原子计数器的库。
* [emitter-io](https://github.com/emitter-io/emitter) - **Star : 1869** **最近提交 : 2019-07-01**  高性能、分布式、安全和低延迟的发布-订阅平台，使用MQTT、Websockets和love构建。![star > 1000][Silver]
* [flowgraph](https://github.com/vectaport/flowgraph) - **Star : 17** **最近提交 : 2019-06-20**  flow-based programming package。
* [gleam](https://github.com/chrislusf/gleam) - **Star : 2037** **最近提交 : 2019-06-29**  使用纯Go和Luajit编写的快速、可伸缩的分布式map/reduce系统，结合了Go的高并发性和Luajit的高性能，可以独立运行或分布式运行。![star > 1000][Silver]
* [glow](https://github.com/chrislusf/glow) - **Star : 2492** **最近提交 : 2018-11-02**  全部用 Go 实现，易用、可伸缩，可用于分布式大数据处理，Map-Reduce, DAG执行。![star > 1000][Silver]
* [go-health](https://github.com/InVisionApp/go-health) - **Star : 474** **最近提交 : 2019-06-26**  用于在服务中启用异步依赖项健康检查的库。![star > 100][Bronze]
* [go-jump](https://github.com/dgryski/go-jump) - **Star : 251** **最近提交 : 2018-02-12**  提供了谷歌的 “Jump” 一致哈希函数接口。![star > 100][Bronze]
* [go-kit](https://github.com/go-kit/kit) - **Star : 14082** **最近提交 : 2019-06-27**  支持服务发现、负载平衡、插件式传输、请求跟踪等功能的Microservice toolkit。![star > 5000][Gold]
* [gorpc](https://github.com/valyala/gorpc) - **Star : 546** **最近提交 : 2017-04-07**  简单、快速和可伸缩的RPC库。![star > 100][Bronze]
* [grpc-go](https://github.com/grpc/grpc-go) - **Star : 8715** **最近提交 : 2019-06-28**  gRPC的Go语言实现。![star > 5000][Gold]
* [hprose](https://github.com/hprose/hprose-golang) - **Star : 990** **最近提交 : 2019-06-27**  支持25+种语言RPC库。![star > 100][Bronze]
* [jaeger](https://github.com/jaegertracing/jaeger) - **Star : 8371** **最近提交 : 2019-07-01**  分布式跟踪系统。![star > 5000][Gold]
* [jsonrpc](https://github.com/osamingo/jsonrpc) - **Star : 113** **最近提交 : 2019-04-22**  jsonrpc 包，实现了 JSON-RPC 2.0。![star > 100][Bronze]
* [jsonrpc](https://github.com/ybbus/jsonrpc) - **Star : 95** **最近提交 : 2019-04-20**  JSON-RPC 2.0 HTTP客户端。
* [KrakenD](https://github.com/devopsfaith/krakend) - **Star : 1625** **最近提交 : 2019-06-16**  具有中间件的高性能API网关框架。![star > 1000][Silver]
* [micro](https://github.com/micro/micro) - **Star : 6405** **最近提交 : 2019-06-27**  可插拔的微服务 toolkit 和分布式系统平台。![star > 5000][Gold]
* [NATS](https://github.com/nats-io/gnatsd) - **Star : 5906** **最近提交 : 2019-06-30**  轻量级、高性能消息传递系统，可用于微服务、物联网(IoT)和云。![star > 5000][Gold]
* [outboxer](https://github.com/italolelis/outboxer) - **Star : 1** **最近提交 : 2019-02-22**  实现了 outbox pattern Go 库。
* [pglock](https://cirello.io/pglock) - postgresql 的分布式锁定实现。
* [raft](https://github.com/hashicorp/raft) - **Star : 2767** **最近提交 : 2019-06-27**  Raft consensus协议的实现。 by HashiCorp。![star > 1000][Silver]
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Raft consensus协议的实现。 by CoreOS。
* [redis-lock](https://github.com/bsm/redis-lock) - **Star : 145** **最近提交 : 2019-06-24**  基于redis的分布式锁简易实现。![star > 100][Bronze]
* [resgate](https://resgate.io/) - 用于构建REST、实时和RPC API的实时API网关，其中所有客户端都是无缝同步的。
* [ringpop-go](https://github.com/uber/ringpop-go) - **Star : 563** **最近提交 : 2019-02-19**  可伸缩的，容错、应用分层的的Go应用程序。![star > 100][Bronze]
* [rpcx](https://github.com/smallnest/rpcx) - **Star : 3664** **最近提交 : 2019-06-27**  分布式可插拔的RPC服务框架，如阿里巴巴Dubbo。![star > 1000][Silver]
* [sleuth](https://github.com/ursiform/sleuth) - **Star : 298** **最近提交 : 2018-03-21**  用于HTTP服务之间进行无中心p2p自动发现和RPC通信的库(使用[ZeroMQ](https://github.com/zeromq/libzmq))。![star > 100][Bronze]
* [tendermint](https://github.com/tendermint/tendermint) - **Star : 3057** **最近提交 : 2019-07-01**  一个高性能中间件，可将任何语言的状态机转换为 Byzantine Fault 状态机。使用 Tendermint 一致性及区块链协议。![star > 1000][Silver]
* [torrent](https://github.com/anacrolix/torrent) - **Star : 2763** **最近提交 : 2019-06-24**  BitTorrent 客户端。![star > 1000][Silver]

## 电子邮件

*实现了电子邮件创建和发送。*

* [chasquid](https://blitiri.com.ar/p/chasquid) - 用Go编写的SMTP服务器。
* [douceur](https://github.com/aymerick/douceur) - **Star : 157** **最近提交 : 2018-03-23**  在HTML邮件中支持CSS内联。![star > 100][Bronze]
* [email](https://github.com/jordan-wright/email) - **Star : 1073** **最近提交 : 2019-04-23**  一个强大和灵活的电子邮件库。![star > 1000][Silver]
* [go-dkim](https://github.com/toorop/go-dkim) - **Star : 46** **最近提交 : 2019-05-10**  DKIM库，用于签署 & 验证电子邮件。
* [go-imap](https://github.com/emersion/go-imap) - **Star : 703** **最近提交 : 2019-06-30**  用于客户端和服务器的IMAP库。![star > 100][Bronze]
* [go-message](https://github.com/emersion/go-message) - **Star : 101** **最近提交 : 2019-06-10**  用于Internet消息格式化和邮件消息的流媒体库。![star > 100][Bronze]
* [go-premailer](https://github.com/vanng822/go-premailer) - **Star : 34** **最近提交 : 2019-05-04**  在HTML邮件中支持CSS内联。
* [Gomail](https://github.com/go-gomail/gomail/) - 一个非常简单和强大的邮件发送库。
* [Hectane](https://github.com/hectane/hectane) - **Star : 168** **最近提交 : 2018-04-15**  轻量级的SMTP客户机，提供了HTTP API。![star > 100][Bronze]
* [hermes](https://github.com/matcornic/hermes) - **Star : 1591** **最近提交 : 2019-06-06**  可生成干净的、响应式的HTML电子邮件。![star > 1000][Silver]
* [MailHog](https://github.com/mailhog/MailHog) - **Star : 5016** **最近提交 : 2019-05-28**  电子邮件和SMTP测试工具，对外提供了 web 和 API 接口。![star > 5000][Gold]
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - **Star : 513** **最近提交 : 2019-06-13**  SendGrid 的 Go语言库，用于发送电子邮件。![star > 100][Bronze]
* [smtp](https://github.com/mailhog/smtp) - **Star : 49** **最近提交 : 2018-06-13**  SMTP服务器协议状态机。

## 可嵌入的脚本语言

*在go代码中嵌入其他语言。*

* [agora](https://github.com/PuerkitoBio/agora) - **Star : 322** **最近提交 : 2015-01-26**  基于 Go 的动态类型，可嵌入的编程语言。![star > 100][Bronze]
* [anko](https://github.com/mattn/anko) - **Star : 901** **最近提交 : 2019-06-28**  用Go编写的解释器。![star > 100][Bronze]
* [binder](https://github.com/alexeyco/binder) - **Star : 29** **最近提交 : 2018-07-30**  Lua接口，基于[gopher-lua](https://github.com/yuin/gopher-lua)。
* [expr](https://github.com/antonmedv/expr) - **Star : 556** **最近提交 : 2019-07-01**  一个可以计算表达式的引擎。![star > 100][Bronze]
* [gentee](https://github.com/gentee/gentee) - **Star : 24** **最近提交 : 2019-06-28**  嵌入式脚本编程语言。
* [gisp](https://github.com/jcla1/gisp) - **Star : 428** **最近提交 : 2017-08-25**  LISP 的 Go 接口。![star > 100][Bronze]
* [go-duktape](https://github.com/olebedev/go-duktape) - **Star : 647** **最近提交 : 2019-03-17**  支持 Duktape JavaScript 引擎。![star > 100][Bronze]
* [go-lua](https://github.com/Shopify/go-lua) - **Star : 1637** **最近提交 : 2019-05-17**  用 Go 实现的 Lua 5.2 VM接口。![star > 1000][Silver]
* [go-php](https://github.com/deuill/go-php) - **Star : 669** **最近提交 : 2018-10-07**  PHP 的 Go 接口。![star > 100][Bronze]
* [go-python](https://github.com/sbinet/go-python) - **Star : 889** **最近提交 : 2019-06-15**  CPython C-API 的 Go 接口。![star > 100][Bronze]
* [golua](https://github.com/aarzilli/golua) - **Star : 434** **最近提交 : 2019-06-18**  Lua C 的 Go 接口。![star > 100][Bronze]
* [gopher-lua](https://github.com/yuin/gopher-lua) - **Star : 2903** **最近提交 : 2019-06-19**  用 Go 实现的 Lua 5.1 虚拟机和编译器。![star > 1000][Silver]
* [gval](https://github.com/PaesslerAG/gval) - **Star : 131** **最近提交 : 2019-05-30**  一种用Go编写的高度可定制的表达式语言。![star > 100][Bronze]
* [ngaro](https://github.com/db47h/ngaro) - **Star : 18** **最近提交 : 2018-06-03**  嵌入式 Ngaro VM实现，支持在 Retro 中运行脚本。
* [otto](https://github.com/robertkrimen/otto) - **Star : 4648** **最近提交 : 2019-06-11**  用 Go 编写的 JavaScript 解释器。![star > 1000][Silver]
* [purl](https://github.com/ian-kent/purl) - **Star : 27** **最近提交 : 2014-12-08**  嵌入 Go 的 Perl 5.18.2。
* [tengo](https://github.com/d5/tengo) - **Star : 1264** **最近提交 : 2019-06-25**  字节码编译的脚本语言。![star > 1000][Silver]

## 错误处理

*处理错误的库。*

* [errlog](https://github.com/snwfdhmp/errlog) - **Star : 142** **最近提交 : 2019-04-19**  用于定位抛出错误的源代码(以及一些其他快速调试特性)。可插入到任何 logger 的位置。![star > 100][Bronze]
* [errors](https://github.com/pkg/errors) - **Star : 4688** **最近提交 : 2019-05-30**  可让你很简单的进行错误处理。![star > 1000][Silver]
* [errorx](https://github.com/joomcode/errorx) - **Star : 546** **最近提交 : 2019-03-06**  一个功能丰富的错误包，可进行堆栈跟踪、组装异常信息以及其他。![star > 100][Bronze]
* [go-multierror](https://github.com/hashicorp/go-multierror) - **Star : 703** **最近提交 : 2019-04-20**  可将一系列的错误作为一个整体来显示。![star > 100][Bronze]
* [tracerr](https://github.com/ztrue/tracerr) - **Star : 485** **最近提交 : 2019-03-15**  可展示错误的堆栈跟踪信息和源码片段。![star > 100][Bronze]
* [werr](https://github.com/txgruppi/werr) - **Star : 10** **最近提交 : 2016-03-10**  对错误异常进行了捕获封装，封装信息包含了调用它的文件、行和堆栈。

## 文件

*处理文件和文件系统的库。*

* [afero](https://github.com/spf13/afero) - **Star : 2169** **最近提交 : 2019-06-19**  文件系统的抽象系统。![star > 1000][Silver]
* [checksum](https://github.com/codingsince1985/checksum) - **Star : 6** **最近提交 : 2019-05-18**  生成大型文件的消息摘要(如 MD5 和 SHA256)。
* [flop](https://github.com/homedepot/flop) - **Star : 8** **最近提交 : 2019-04-24**  文件操作库，是[GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp- invoc.html)的镜像。
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - **Star : 44** **最近提交 : 2019-03-31**  使用 tag 加载 csv 文件。
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - **Star : 11** **最近提交 : 2018-10-18**  拷贝文件。
* [go-exiftool](https://github.com/barasher/go-exiftool) - ExifTool 的 Go 实现，这个著名的库用于从文件(图片、PDF、office，…)中提取尽可能多的元数据(EXIF、IPTC，…)。
* [go-gtfs](https://github.com/artonge/go-gtfs) - **Star : 15** **最近提交 : 2019-03-31**  加载gtfs文件。
* [notify](https://github.com/rjeczalik/notify) - **Star : 483** **最近提交 : 2019-04-11**  文件系统事件通知库，具有类似于os/signal的简单API，。![star > 100][Bronze]
* [opc](https://github.com/qmuntal/opc) - **Star : 57** **最近提交 : 2019-04-09**  加载Open Packaging Conventions (OPC)文件。
* [pdfcpu](https://github.com/hhrutter/pdfcpu) - **Star : 918** **最近提交 : 2019-06-17**  PDF处理器。![star > 100][Bronze]
* [skywalker](https://github.com/dixonwille/skywalker) - **Star : 46** **最近提交 : 2017-08-05**  可以轻松地并发地遍历文件系统。
* [stl](https://gitlab.com/russoj88/stl) - 采用并行读取算法的进行读取和写入STL(立体光刻)文件的模块。
* [tarfs](https://github.com/posener/tarfs) - **Star : 34** **最近提交 : 2017-04-02**  tar文件的实现[ FileSystem 接口](https://godoc.org/github.com/kr/fs#FileSystem)。
* [vfs](https://github.com/C2FO/vfs) - **Star : 18** **最近提交 : 2019-06-27**  一组可插拔的、可扩展的和自定义的文件系统功能，用于跨越许多文件系统类型，如os、S3和GCS。

## 金融

*会计和财务软件包。*

* [accounting](https://github.com/leekchan/accounting) - **Star : 476** **最近提交 : 2019-01-31**  货币和货币格式。![star > 100][Bronze]
* [currency](https://github.com/bnkamalesh/currency) - **Star : 8** **最近提交 : 2019-06-01**  高性能、准确的货币计算软件包。
* [decimal](https://github.com/shopspring/decimal) - **Star : 1537** **最近提交 : 2019-06-17**  任意精度定点的十进制数。![star > 1000][Silver]
* [go-finance](https://github.com/FlashBoys/go-finance) - **Star : 538** **最近提交 : 2018-03-09**  综合金融市场数据。![star > 100][Bronze]
* [go-finance](https://github.com/alpeb/go-finance) - **Star : 39** **最近提交 : 2018-05-06**  用于货币时间价值(年金)、现金流、利率转换、债券和折旧计算的金融函数库。
* [go-money](https://github.com/rhymond/go-money) - **Star : 604** **最近提交 : 2019-05-22**  Fowler 货币模式的实现。![star > 100][Bronze]
* [ofxgo](https://github.com/aclindsa/ofxgo) - **Star : 59** **最近提交 : 2019-07-01**  查询 OFX 服务器和/或解析响应。
* [orderbook](https://github.com/i25959341/orderbook) - **Star : 62** **最近提交 : 2019-05-15**  限购单匹配引擎。
* [techan](https://github.com/sdcoffey/techan) - **Star : 140** **最近提交 : 2019-06-19**  拥有先进的市场分析和交易策略的技术分析库。![star > 100][Bronze]
* [transaction](https://github.com/claygod/transaction) - **Star : 52** **最近提交 : 2019-06-13**  嵌入式事务数据库，可多线程模式运行。
* [vat](https://github.com/dannyvankooten/vat) - **Star : 60** **最近提交 : 2018-09-10**  增值税编号验证 & 欧盟增值税税率。

## 表单

*用于处理表单的库。*

* [bind](https://github.com/robfig/bind) - **Star : 23** **最近提交 : 2014-08-17**  将表单数据与任意 Go 变量进行绑定。
* [binding](https://github.com/mholt/binding) - **Star : 752** **最近提交 : 2018-03-29**  将来自 net/HTTP 请求的表单、JSON 数据绑定到结构体。![star > 100][Bronze]
* [conform](https://github.com/leebenson/conform) - **Star : 171** **最近提交 : 2018-06-16**  控制用户输入。基于struct tags可对数据进行修剪、清理和擦除。![star > 100][Bronze]
* [form](https://github.com/go-playground/form) - **Star : 347** **最近提交 : 2019-04-30**   将 url 中的数据解析到 Go 变量中，以及将 Go 语言变量编码进 url。支持 Dual Array 及 Full map。![star > 100][Bronze]
* [formam](https://github.com/monoculum/formam) - **Star : 123** **最近提交 : 2019-03-07**  将表单的值解码为 struct。![star > 100][Bronze]
* [forms](https://github.com/albrow/forms) - **Star : 103** **最近提交 : 2017-07-02**  与框架无关的库，用于解析和验证支持多部分表单和文件的表单/JSON数据。![star > 100][Bronze]
* [gorilla/csrf](https://github.com/gorilla/csrf) - **Star : 421** **最近提交 : 2019-06-26**  用于Go web应用程序和服务的CSRF保护。![star > 100][Bronze]
* [nosurf](https://github.com/justinas/nosurf) - **Star : 957** **最近提交 : 2019-04-24**  CSRF保护中间件。![star > 100][Bronze]

## 方法

*在Go中支持函数式编程的包。*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - **Star : 99** **最近提交 : 2018-07-19**  提供函数式编程功能。
* [fuego](https://github.com/seborama/fuego) - **Star : 34** **最近提交 : 2019-05-03**  Functional Experiment in Go。
* [go-underscore](https://github.com/tobyhede/go-underscore) - **Star : 1058** **最近提交 : 2019-02-15**  常用辅助方法集合。![star > 1000][Silver]

## 游戏开发

*很棒的游戏开发库。*

* [Azul3D](https://github.com/azul3d/engine) - **Star : 421** **最近提交 : 2018-06-25**  用Go编写的 3D 游戏引擎。![star > 100][Bronze]
* [Ebiten](https://github.com/hajimehoshi/ebiten) - **Star : 1775** **最近提交 : 2019-06-27**  很简单的 2D 游戏库。![star > 1000][Silver]
* [engo](https://github.com/EngoEngine/engo) - **Star : 1071** **最近提交 : 2019-04-09**  开源 2D 游戏引擎。它遵循 Entity-Component-System 范式。![star > 1000][Silver]
* [g3n](https://github.com/g3n/engine) - **Star : 721** **最近提交 : 2019-06-13**   3D游戏引擎。![star > 100][Bronze]
* [GarageEngine](https://github.com/vova616/GarageEngine) - **Star : 308** **最近提交 : 2013-09-03**  用 OpenGL 编写的 2D 游戏引擎。![star > 100][Bronze]
* [glop](https://github.com/runningwild/glop) - **Star : 77** **最近提交 : 2015-09-24**  Glop (Game Library Of Power) 是一个相当简单的跨平台游戏库。
* [go-astar](https://github.com/beefsack/go-astar) - **Star : 322** **最近提交 : 2018-03-26**  实现了A\*路径查找算法。![star > 100][Bronze]
* [go-collada](https://github.com/GlenKelley/go-collada) - **Star : 12** **最近提交 : 2013-09-27**  处理Collada文件。
* [go-sdl2](https://github.com/veandco/go-sdl2) - **Star : 1132** **最近提交 : 2019-06-13**  实现了[Simple DirectMedia Layer](https://www.libsdl.org/)。![star > 1000][Silver]
* [go3d](https://github.com/ungerik/go3d) - **Star : 162** **最近提交 : 2019-03-20**  以性能为主的2D/3D数学相关包。![star > 100][Bronze]
* [gonet](https://github.com/xtaci/gonet) - **Star : 1042** **最近提交 : 2017-05-12**  实现了游戏服务器骨架。![star > 1000][Silver]
* [goworld](https://github.com/xiaonanln/goworld) - **Star : 1132** **最近提交 : 2019-05-27**  可伸缩的游戏服务器引擎，具有 space-entity 框架和 hot-swapping 功能。![star > 1000][Silver]
* [Leaf](https://github.com/name5566/leaf) - **Star : 2989** **最近提交 : 2018-12-28**  轻量级游戏服务器框架。![star > 1000][Silver]
* [nano](https://github.com/lonng/nano) - **Star : 956** **最近提交 : 2019-06-30**  轻量级、方便、高性能的基于golang的游戏服务器框架。![star > 100][Bronze]
* [Oak](https://github.com/oakmound/oak) - **Star : 622** **最近提交 : 2019-06-23**  纯 Go 实现的游戏引擎。![star > 100][Bronze]
* [Pitaya](https://github.com/topfreegames/pitaya) - **Star : 283** **最近提交 : 2019-06-21**  可伸缩的游戏服务器框架，支持集群和客户端库的iOS, Android, Unity。![star > 100][Bronze]
* [Pixel](https://github.com/faiface/pixel) - **Star : 2371** **最近提交 : 2019-06-30**  手工制作的 2D 游戏库。![star > 1000][Silver]
* [raylib-go](https://github.com/gen2brain/raylib-go) - **Star : 377** **最近提交 : 2018-11-18**  实现了 [raylib](http://www.raylib.com/)，一个简单易用的库，用于学习视频游戏编程。![star > 100][Bronze]
* [termloop](https://github.com/JoelOtter/termloop) - **Star : 1017** **最近提交 : 2019-06-10**  基于终端的 Go 游戏引擎，建立在 Termbox 之上。![star > 1000][Silver]

## 代码生成与泛型

*增强语言的工具，例如通过代码生成支持泛型。*

* [efaceconv](https://github.com/t0pep0/efaceconv) - **Star : 42** **最近提交 : 2017-10-12**  代码生成工具，可以不通过内存分配就可以高效的将interface{}转换为不可变类型，。
* [gen](https://github.com/clipperhouse/gen) - **Star : 1016** **最近提交 : 2018-06-12**  用于生成泛型等类似方法的功能代码生成工具。![star > 1000][Silver]
* [generis](https://github.com/senselogic/GENERIS) - **Star : 18** **最近提交 : 2019-05-12**  提供泛型、free-form 宏、条件编译和HTML模板的代码生成工具。
* [go-enum](https://github.com/abice/go-enum) - **Star : 80** **最近提交 : 2019-04-19**  从代码注释中生成枚举。
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - **Star : 1759** **最近提交 : 2019-06-08**  提供类似 .NET LINQ 的查询方法。![star > 1000][Silver]
* [goderive](https://github.com/awalterschulze/goderive) - **Star : 717** **最近提交 : 2019-02-24**  从输入类型来派生函数。![star > 100][Bronze]
* [gotype](https://github.com/wzshiming/gotype) - **Star : 19** **最近提交 : 2019-06-20**  Golang 源码解析，用法类似reflect(反射)。
* [GoWrap](https://github.com/hexdigest/gowrap) - **Star : 258** **最近提交 : 2019-04-23**  使用简单模板为 Go 接口生成装饰器。![star > 100][Bronze]
* [interfaces](https://github.com/rjeczalik/interfaces) - **Star : 184** **最近提交 : 2019-05-02**  用于生成接口定义的命令行工具。![star > 100][Bronze]
* [jennifer](https://github.com/dave/jennifer) - **Star : 1248** **最近提交 : 2019-05-04**  不使用模板生成任意 Go 代码。![star > 1000][Silver]
* [pkgreflect](https://github.com/ungerik/pkgreflect) - **Star : 84** **最近提交 : 2017-09-05**  用于包作用域反射的 Go 预处理器。

## 地理

*地理工具和服务器*

* [geocache](https://github.com/melihmucuk/geocache) - **Star : 106** **最近提交 : 2016-06-22**  基于内存缓存的的地理位置的应用程序。![star > 100][Bronze]
* [geoserver](https://github.com/hishamkaram/geoserver) - **Star : 24** **最近提交 : 2018-11-24**  基于geoserver REST API的 geoserver 实例。
* [gismanager](https://github.com/hishamkaram/gismanager) - **Star : 17** **最近提交 : 2018-10-30**  将你的 GIS 数据(矢量数据)发布到 PostGIS 和 Geoserver。
* [osm](https://github.com/paulmach/osm) - **Star : 58** **最近提交 : 2018-12-15**  用于读取、写入和处理 OpenStreetMap 数据和 APIs。
* [pbf](https://github.com/maguro/pbf) - **Star : 15** **最近提交 : 2018-10-15**  基于Golang 的 OpenStreetMap PBF 编码器/解码器。
* [S2 geometry](https://github.com/golang/geo) - **Star : 870** **最近提交 : 2019-05-08**  S2 geometry 库。![star > 100][Bronze]
* [Tile38](https://github.com/tidwall/tile38) - **Star : 6260** **最近提交 : 2019-06-29**  具有空间索引和实时地理定位功能的地理定位数据库。![star > 5000][Gold]

## Go 编译器

*可将 Go 转换为其他语言的编译工具。*

* [c4go](https://github.com/Konstantin8105/c4go) - **Star : 142** **最近提交 : 2019-06-24**  将 C 代码转换为 Go 代码。![star > 100][Bronze]
* [f4go](https://github.com/Konstantin8105/f4go) - **Star : 11** **最近提交 : 2018-12-21**  将 FORTRAN 77 转换为 Go代码。
* [gopherjs](https://github.com/gopherjs/gopherjs) - **Star : 8420** **最近提交 : 2019-05-01**  将 Go 编译成 JavaScript。![star > 5000][Gold]
* [llgo](https://github.com/go-llvm/llgo) - **Star : 986** **最近提交 : 2015-01-05**  基于 llvm 的编译器。![star > 100][Bronze]
* [tardisgo](https://github.com/tardisgo/tardisgo) - **Star : 391** **最近提交 : 2016-11-20**  Golang 转换为 Haxe，再转换为 CPP/CSharp/Java/JavaScript 的编译器.![star > 100][Bronze]

## Goroutines

*管理和处理 Goroutines 的工具。*

* [ants](https://github.com/panjf2000/ants) - **Star : 1740** **最近提交 : 2019-06-27**  一个高性能的协程池。![star > 1000][Silver]
* [artifex](https://github.com/borderstech/artifex) - **Star : 12** **最近提交 : 2018-11-03**  简单的内存作业队列。
* [async](https://github.com/studiosol/async) - **Star : 18** **最近提交 : 2018-09-18**  一种异步执行函数的安全方法，在出现 panic 时恢复它们。
* [breaker](https://github.com/kamilsk/breaker) - **Star : 24** **最近提交 : 2019-06-28**  灵活的机制，可以使执行流可中断。
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - **Star : 27** **最近提交 : 2018-10-27**  基于 Go 的 CyclicBarrier 实现。
* [go-floc](https://github.com/workanator/go-floc) - **Star : 167** **最近提交 : 2018-01-26**  轻松编排 goroutines。![star > 100][Bronze]
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - **Star : 103** **最近提交 : 2019-05-14**  控制 goroutines 的执行顺序。![star > 100][Bronze]
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - **Star : 5** **最近提交 : 2019-03-28**  轻量级的协程池库，可以通过简单的API来管理。
* [go-trylock](https://github.com/subchen/go-trylock) - **Star : 4** **最近提交 : 2018-05-29**  支持 read-write 锁。
* [gollback](https://github.com/vardius/gollback) - **Star : 25** **最近提交 : 2019-06-07**  异步简单的函数实用程序，用于管理闭包和回调的执行
