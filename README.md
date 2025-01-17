# Awesome Go

[Gold]: https://cdn.jsdelivr.net/gh/guozhen-robot/awesome-go-cn@cdn/docs/Gold.svg "star > 5000"
[Silver]: https://cdn.jsdelivr.net/gh/guozhen-robot/awesome-go-cn@cdn/docs/Silver.svg "star > 1000"
[Bronze]: https://cdn.jsdelivr.net/gh/guozhen-robot/awesome-go-cn@cdn/docs/Bronze.svg "star > 100"
[Green]: https://cdn.jsdelivr.net/gh/guozhen-robot/awesome-go-cn@cdn/docs/Green.svg "最近一周有更新"
[Yellow]: https://cdn.jsdelivr.net/gh/guozhen-robot/awesome-go-cn@cdn/docs/Yellow.svg "最近一年没有更新"

**此项目是 [awesome-go](https://awesome-go.com/) 中文版，最后一次同步时间 : 2019-07-18 09:41:30(每隔1天同步一次)**

**:star:项目地址 : [yinggaozhen/awesome-go-cn](https://github.com/yinggaozhen/awesome-go-cn):star:**

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinosource) 为Awesome Go打赏~

精选了一系列很棒的Go框架、库和软件。灵感来自于[awesome-python](https://github.com/vinta/awesome-python)。

**小图标说明** :


小图标 | 说明  
:-:|-
![star > 5000][Gold] | star数量 > 5000 的项目
![star > 1000][Silver] | star数量 > 1000 的项目
![star > 100][Bronze] | star数量 > 100 的项目
![最近一个周有更新][Green] | 最近一周有更新。可以基本判断当前库处于积极维护状态。
![最近一年未更新][Yellow] | 最近一年没有更新。反应了此库的维护积极性不高，使用时需谨慎。
 

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

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [EasyMIDI](https://github.com/algoGuy/EasyMIDI)  | 22 |  EasyMidi是一个简单可靠的库，用于处理标准midi文件(SMF)。 |![最近一年没有更新][Yellow]
| [flac](https://github.com/eaburns/flac)  | 83 |  原生 Go FLAC解码器，将FLAC文件解码为字节片。 |![最近一年没有更新][Yellow]
| [flac](https://github.com/mewkiz/flac)  | 100 |  原生 Go FLAC编码器/解码器，支持FLAC流。 |![star > 100][Bronze]   
| [gaad](https://github.com/Comcast/gaad)  | 55 |  原生 Go AAC位流解析器。 |![最近一年没有更新][Yellow]
| [go-sox](https://github.com/krig/go-sox)  | 92 |  libsox 的 Go 语言实现接口。 |![最近一年没有更新][Yellow]
| [go_mediainfo](https://github.com/zhulik/go_mediainfo)  | 24 |  libmediainfo 的 Go 语言实现接口。 |![最近一年没有更新][Yellow]
| [gosamplerate](https://github.com/dh1tw/gosamplerate)  | 8 |  libsamplerate 的 Go 语言实现接口。 |![最近一年没有更新][Yellow]
| [id3v2](https://github.com/bogem/id3v2)  | 107 |  快速稳定的 ID3 解析及写入Go库。 |![star > 100][Bronze]   
| [malgo](https://github.com/gen2brain/malgo)  | 70 |  迷你音频库。 |
| [minimp3](https://github.com/tosone/minimp3)  | 25 |  轻量级MP3解码器库。 |
| [mix](https://github.com/go-mix/mix)  | 98 |  基于序列的 Go 原生音乐混音器。 |![最近一年没有更新][Yellow]
| [mp3](https://github.com/tcolgate/mp3)  | 89 |  原生 Go MP3解码器。 |![最近一年没有更新][Yellow]
| [music-theory](https://github.com/go-music-theory/music-theory)  | 252 |  基于 Go 的音乐理论模型。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Oto](https://github.com/hajimehoshi/oto)  | 423 |  多平台的 low-level 声音播放库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [PortAudio](https://github.com/gordonklaus/portaudio)  | 299 |  基于 Go 的PortAudio audio I/O库。 |![star > 100][Bronze]   
| [portmidi](https://github.com/rakyll/portmidi)  | 205 |  PortMidi的 Go 语言实现接口。。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [taglib](https://github.com/wtolson/go-taglib)  | 66 |  taglib 的 Go 语言实现接口。。 |![最近一年没有更新][Yellow]
| [vorbis](https://github.com/mccoyst/vorbis)  | 22 |  “原生” Go Vorbis解码器(使用CGO，但没有依赖关系)。 |
| [waveform](https://github.com/mdlayher/waveform)  | 247 |  通过音频流生成波形图像的包。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 身份验证和OAuth

*用于实现验证方案的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [authboss](https://github.com/volatiletech/authboss)  | 1909 |  web模块化认证系统。它试图删除尽可能多的模板文件和硬编码，以便每次新建一个新的web项目时，您都可以插入、配置并开始构建您的应用程序，而不必每次都构建一个身份验证系统。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [branca](https://github.com/hako/branca)  | 70 |  基于 Go 实现Branca令牌。 |
| [casbin](https://github.com/hsluoyz/casbin)  | 4823 |  支持ACL、RBAC、ABAC等访问控制模型的授权库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [cookiestxt](https://github.com/mengzhuo/cookiestxt)  | 2 |  提供cookie .txt文件格式的解析器。 |![最近一年没有更新][Yellow]
| [go-jose](https://github.com/square/go-jose)  | 1112 |  相当完整地实现了JOSE工作组的JSON Web令牌、JSON Web签名和JSON Web加密规范。 |![star > 1000][Silver]   
| [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server)  | 1264 |  用 Golang 编写的独立且符合规范的OAuth2服务器。 |![star > 1000][Silver]   
| [gologin](https://github.com/dghubble/gologin)  | 1034 |  用于使用OAuth1和OAuth2身份验证提供者登录的可链处理程序。 |![star > 1000][Silver]   
| [gorbac](https://github.com/mikespook/gorbac)  | 899 |  轻量级的基于角色的访问控制(RBAC)实现。 |![star > 100][Bronze]   
| [goth](https://github.com/markbates/goth)  | 2235 |  提供了 OAuth 和 OAuth2 的简单清晰易用的方法。可开箱即用处理多个提供程序。 |![star > 1000][Silver]   
| [httpauth](https://github.com/goji/httpauth)  | 177 |  HTTP身份验证中间件。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [jwt](https://github.com/robbert229/jwt)  | 68 |  简单易用的JSON Web令牌实现(JWT)。 |
| [jwt](https://github.com/pascaldekloe/jwt)  | 77 |  轻量级JSON Web令牌库。 |
| [jwt-auth](https://github.com/adam-hanna/jwt-auth)  | 151 |  JWT中间件，可用于Golang http服务器，提供了许多配置选项。 |![star > 100][Bronze]   
| [jwt-go](https://github.com/dgrijalva/jwt-go)  | 5829 |  JSON Web令牌(JWT)。 |![star > 5000][Gold]   
| [loginsrv](https://github.com/tarent/loginsrv)  | 800 |  JWT登录微服务带有可插拔的后端服务，如OAuth2 (Github)、htpasswd、osiam。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [oauth2](https://github.com/golang/oauth2)  | 2357 |  goauth2的继任者。通用OAuth 2.0包，附带JWT、谷歌api、计算引擎和应用程序引擎支持。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [osin](https://github.com/openshift/osin)  | 1537 |  OAuth2服务器库。 |![star > 1000][Silver]   
| [paseto](https://github.com/o1egl/paseto)  | 225 |  平台无关的安全令牌(PASETO)。 |![star > 100][Bronze]   
| [permissions2](https://github.com/xyproto/permissions2)  | 348 |  用于跟踪用户、登录状态和权限的库。依赖于cookie安全和bcrypt。 |![star > 100][Bronze]   
| [rbac](https://github.com/zpatrick/rbac)  | 27 |  最小的RBAC包。 |
| [scs](https://github.com/alexedwards/scs)  | 519 |  HTTP服务器的会话管理器。 |![star > 100][Bronze]   
| [securecookie](https://github.com/chmike/securecookie)  | 32 |  高效安全的cookie编码/解码。 |
| [session](https://github.com/icza/session)  | 88 |  web服务器会话管理(包括支持谷歌应用程序引擎 - GAE)。 |
| [sessiongate-go](https://github.com/f0rmiga/sessiongate-go)  | 8 |  使用SessionGate Redis模块进行会话管理。 |
| [sessions](https://github.com/adam-hanna/sessions)  | 46 |  非常简单，高性能，可深度定制的会话服务，主要用于的 go http 服务器。 |
| [signedvalue](https://github.com/sashka/signedvalue)  | 7 |  与[Tornado's](https://github.com/tornadooweb/tornado) 完全兼容的签名和时间戳字符串实现. create_signed_value '， ' decode_signed_value '，因此' set_secure_cookie '和' get_secure_cookie '。 |
| [sjwt](https://github.com/brianvoe/sjwt)  | 30 |  简单的jwt生成器和解析器。 |![最近一个周有更新][Green]

## Bot建设

*用于构建和使用机器人的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [go-chat-bot](https://github.com/go-chat-bot/bot)  | 462 |  用 Go 编写的IRC, Slack和电报机器人。 |![star > 100][Bronze]   
| [go-sarah](https://github.com/oklahomer/go-sarah)  | 136 |  此框架提供了聊天机器人相关的服务，包括LINE、Slack、Gitter等。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-tgbot](https://github.com/olebedev/go-tgbot)  | 83 |  由swagger文件、基于会话的路由器和中间件生成的纯Golang Telegram Bot API包装器。 |![最近一年没有更新][Yellow]
| [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot)  | 210 |  基于控制台的，用于加密货币交易所的的交易机器人。 |![star > 100][Bronze]   
| [govkbot](https://github.com/nikepan/govkbot)  | 23 |  简单的Go [VK](https://vk.com) bot库。 |
| [hanu](https://github.com/sbstjn/hanu)  | 108 |  用于编写Slack机器人的框架。 |![star > 100][Bronze]   
| [Kelp](https://github.com/stellar/kelp)  | 152 |  官方交易和做市机器人为[Stellar](https://www.stellar.org/) DEX。开箱即用的作品，用 Golang 编写，兼容集中交易和定制交易策略。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [margelet](https://github.com/zhulik/margelet)  | 56 |  构建电报机器人的框架。 |![最近一年没有更新][Yellow]
| [micha](https://github.com/onrik/micha)  | 10 |  基于 GO 实现的Telegram 机器人API库。 |![最近一年没有更新][Yellow]
| [slacker](https://github.com/shomali11/slacker)  | 304 |  可简单创建Slack机器人的框架。 |![star > 100][Bronze]   
| [slackscot](https://github.com/alexandre-normand/slackscot)  | 10 |  另一个构建Slack机器人的框架。 |![最近一个周有更新][Green]
| [tbot](https://github.com/yanzay/tbot)  | 214 |  带有类似于net/http API的Telegram bot服务器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [telebot](https://github.com/tucnak/telebot)  | 937 |  用Go编写的Telegram bot框架。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api)  | 1590 |  简单轻量级的Telegram bot客户端。 |![star > 1000][Silver]   
| [Tenyks](https://github.com/kyleterry/tenyks)  | 167 |  面向服务的IRC bot，使用Redis和JSON进行消息传递。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 命令行

### 标准CLI

*用于构建标准或基本命令行应用程序的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [argparse](https://github.com/akamensky/argparse)  | 102 |  命令行参数分析器，灵感来自Python的argparse模块。 |![star > 100][Bronze]   
| [argv](https://github.com/cosiner/argv)  | 17 |  基于Base 语法，用于分隔命令行字符串并将其作为参数的 Go 语言库， |
| [cli](https://github.com/mkideal/cli)  | 474 |  基于golang结构标签，功能丰富易于使用的命令行包。 |![star > 100][Bronze]   
| [cli](https://github.com/teris-io/cli)  | 56 |  为 Go 构建命令接口提供简单而完整的API。 |
| [cli-init](https://github.com/tcnksm/gcli)  | 866 |  一个简单就可开启构建Golang命令行的应用程序。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [climax](http://github.com/tucnak/climax)  | - |  Alternative CLI with "human face", in spirit of Go command. |
| [cmdr](https://github.com/hedzr/cmdr)  | 8 |  一个POSIX/GNU风格的、类似getopt的命令行UI Go库。 |![最近一个周有更新][Green]
| [cobra](https://github.com/spf13/cobra)  | 12982 |  现代Go CLI命令行交互工具。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [commandeer](https://github.com/jaffee/commandeer)  | 83 |  开发友好的CLI应用程序。 |
| [complete](https://github.com/posener/complete)  | 610 |  使用 Go 语言编写的 bash 命令补全工具以及 Go 命令补全工具. |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [docopt.go](https://github.com/docopt/docopt.go)  | 1160 |  会让你满意的命令行参数解析器。 |![star > 1000][Silver]   
| [env](https://github.com/codingconcepts/env)  | 41 |  基于标记的结构化的环境配置。 |
| [flag](https://github.com/cosiner/flag)  | 100 |  简单但功能强大的命令行选项解析库，用于支持Go子命令。 |![star > 100][Bronze]   
| [flaggy](https://github.com/integrii/flaggy)  | 443 |  一个健壮的、易用的标志包，具有出色的子命令支持。 |![star > 100][Bronze]   
| [flagvar](https://github.com/sgreben/flagvar)  | 31 |  符合 Go 标准的“flag”标志参数类型包。 |
| [go-arg](https://github.com/alexflint/go-arg)  | 649 |  基于结构的参数解析。 |![star > 100][Bronze]   
| [go-commander](https://github.com/yitsushi/go-commander)  | 14 |  用于简化CLI工作流的 Go 库。 |
| [go-flags](https://github.com/jessevdk/go-flags)  | 1497 |   Go 命令行选项解析器。 |![star > 1000][Silver]   
| [go-getoptions](https://github.com/DavidGamba/go-getoptions)  | 6 |   Go 选择解析器，借鉴于Perl灵活性的GetOpt::Long。 |![最近一个周有更新][Green]
| [gocmd](https://github.com/devfacet/gocmd)  | 33 |  用于构建命令行应用程序。 |
| [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli)  | - |  具有自动配置和依赖注入的cli应用程序框架。 |
| [job](https://github.com/liujianping/job)  | 47 |  工作，把你的短期指令当作长期任务。 |
| [kingpin](https://github.com/alecthomas/kingpin)  | 2509 |  支持子命令的命令行和标志解析器。 |![star > 1000][Silver]   
| [liner](https://github.com/peterh/liner)  | 573 |  类似readline-like的命令行接口库。 |![star > 100][Bronze]   
| [mitchellh/cli](https://github.com/mitchellh/cli)  | 990 |  用于实现命令行接口的Go库。 |![star > 100][Bronze]   
| [mow.cli](https://github.com/jawher/mow.cli)  | 619 |  用于构建具有复杂标志和参数解析和验证的CLI应用程序。 |![star > 100][Bronze]   
| [ops](https://github.com/nanovms/ops)  | 248 |  Unikernel 构建器/协调器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [pflag](https://github.com/spf13/pflag)  | 739 |  基于POSIX/GNU-style --flags实现的包，主要用于替换Go的falg包。 |![star > 100][Bronze]   
| [readline](https://github.com/chzyer/readline)  | 1361 |  纯golang实现，在MIT许可下提供了GNU-Readline的大部分特性。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [sand](https://github.com/Zaba505/sand)  | 5 |  用于创建解释器等的简单API。 |
| [sflags](https://github.com/octago/sflags)  | 84 |  基于结构的flag生成器，用于flag、urfave/cli、pflag、cobra、kingpin和其他库。 |
| [strumt](https://github.com/antham/strumt)  | 27 |  用于创建提示链。 |
| [ukautz/clif](https://github.com/ukautz/clif)  | 97 |  简小的命令行接口框架。 |
| [urfave/cli](https://github.com/urfave/cli)  | 11175 |  可让你简单、快速和愉快的构建命令行应用(之前是codegangsta/cli)。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [wlog](https://github.com/dixonwille/wlog)  | 35 |  支持跨平台和并发的简单日志记录接口。 |![最近一年没有更新][Yellow]
| [wmenu](https://github.com/dixonwille/wmenu)  | 82 |  为cli程序提供了简单上手的菜单，可提示用户作出选择。 |

### 高级控制台用户界面

*用于构建控制台应用程序和控制台用户界面的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [asciigraph](https://github.com/guptarohit/asciigraph)  | 1128 |  在命令行中构建轻量级ASCII线图╭┈╯，应用程序中没有其他依赖项。 |![star > 1000][Silver]   
| [aurora](https://github.com/logrusorgru/aurora)  | 614 |  支持fmt.Printf/Sprintf的ANSI终端颜色。 |![star > 100][Bronze]   
| [cfmt](https://github.com/mingrammer/cfmt)  | 67 |  提供上下文的fmt，灵感来自于bootstrap color classes。 |
| [chalk](https://github.com/ttacon/chalk)  | 302 |  美化终端/控制台输出。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [color](https://github.com/fatih/color)  | 2994 |  多功能包装，彩色终端输出。 |![star > 1000][Silver]   
| [colourize](https://github.com/TreyBastian/colourize)  | 16 |  在终端提供ANSI彩色文本。 |![最近一年没有更新][Yellow]
| [ctc](https://github.com/wzshiming/ctc)  | 9 |  不需要Print方法的非侵入性跨平台终端颜色库。 |
| [go-ataman](https://github.com/workanator/go-ataman)  | 8 |  在终端提供ANSI彩色文本模板。 |![最近一年没有更新][Yellow]
| [go-colorable](https://github.com/mattn/go-colorable)  | 372 |  适用于windows的颜色编写器。 |![star > 100][Bronze]   
| [go-colortext](https://github.com/daviddengcn/go-colortext)  | 197 |  在终端中使用彩色文字。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-isatty](https://github.com/mattn/go-isatty)  | 340 |  Go 实现的 isatty。 |![star > 100][Bronze]   
| [go-prompt](https://github.com/c-bata/go-prompt)  | 2284 |  构建一个强大的交互式提示，借鉴于[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) |![star > 1000][Silver]   
| [gocui](https://github.com/jroimartin/gocui)  | 5201 |  旨在创建控制台用户界面的极简Go库。 |![star > 5000][Gold]   
| [gommon/color](https://github.com/labstack/gommon/tree/master/color)  | - |  更换终端文本样式。 |
| [gookit/color](https://github.com/gookit/color)  | 196 |  终端显色工具库，支持16种颜色，256种颜色，RGB显色输出，兼容Windows。 |![star > 100][Bronze]   
| [mpb](https://github.com/vbauerster/mpb)  | 504 |  可在终端显示多进度条。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [progressbar](https://github.com/schollz/progressbar)  | 561 |  基本线程安全的进度条，在每个操作系统工作。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [simpletable](https://github.com/alexeyco/simpletable)  | 154 |  可在终端显示简易表格。 |![star > 100][Bronze]   
| [tabby](https://github.com/cheynewallace/tabby)  | 246 |  一个可在终端生成一个极简Golang表格轻量级库 |![star > 100][Bronze]   
| [tabular](https://github.com/InVisionApp/tabular)  | 29 |  不需要向API传递大量参数就可从命令行实用程序中打印ASCII表。 |![最近一年没有更新][Yellow]
| [termbox-go](https://github.com/nsf/termbox-go)  | 3452 |  基于文本的跨平台接口库。 |![star > 1000][Silver]   
| [termdash](https://github.com/mum4k/termdash)  | 793 |  此库是基于**termbox-go**实现的，借鉴于[termui](https://github.com/gizak/termui)。 |![star > 100][Bronze]   
| [termtables](https://github.com/apcera/termtables)  | 212 |  使用Ruby库[terminal-tables](https://github.com/tj/terminal-table)的端口生成简单的ASCII表，并提供标记和HTML输出。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [termui](https://github.com/gizak/termui)  | 8846 |  此库是基于**termbox-go**实现的，借鉴于[blessed-contrib](https://github.com/yaronn/blessed-contrib)。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [uilive](https://github.com/gosuri/uilive)  | 821 |  用于实时更新终端输出的库。 |![star > 100][Bronze]   
| [uiprogress](https://github.com/gosuri/uiprogress)  | 1523 |  在终端呈现进度条，可灵活配置的。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [uitable](https://github.com/gosuri/uitable)  | 497 |  改善终端应用程序中表格数据的可读性。 |![star > 100][Bronze]   

## 配置

*配置解析的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [config](https://github.com/JeremyLoy/config)  | 188 |  云本地应用程序配置。将ENV绑定到结构体仅需两行代码。 |![star > 100][Bronze]   
| [config](https://github.com/olebedev/config)  | 209 |  带有环境变量和标记解析的JSON或YAML配置包装器。 |![star > 100][Bronze]   
| [configure](https://github.com/paked/configure)  | 48 |  通过多个源提供配置，包括JSON、flags和环境变量。 |
| [confita](https://github.com/heetch/confita)  | 237 |  从多个后端级联加载配置到struct中。 |![star > 100][Bronze]   
| [conflate](https://github.com/the4thamigo-uk/conflate)  | 8 |  合并来自任意url的多个JSON/YAML/TOML文件、针对JSON模式的验证以及模式中定义的默认值的应用程序。 |
| [env](https://github.com/caarlos0/env)  | 842 |  解析环境变量并赋值到struct中(默认值)。 |![star > 100][Bronze]   
| [envcfg](https://github.com/tomazk/envcfg)  | 89 |  对环境变量进行解析，并赋值到struct。 |![最近一年没有更新][Yellow]
| [envconf](https://github.com/ian-kent/envconf)  | 7 |  从环境配置中读取配置。 |![最近一年没有更新][Yellow]
| [envconfig](https://github.com/vrischmann/envconfig)  | 145 |  从环境变量中读取配置。 |![star > 100][Bronze]   
| [envh](https://github.com/antham/envh)  | 93 |  协助管理环境变量的Helpers。 |
| [gcfg](https://github.com/go-gcfg/gcfg)  | 116 |  将ini的配置文件读入 Go structs中;支持用户定义的类型和子选项。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-up](https://github.com/ufoscout/go-up)  | 24 |  一个简单的配置库，具有递归占位符解析功能。 |
| [goConfig](https://github.com/crgimenes/goConfig)  | 105 |  将结构体解析为输入，并用来自命令行、环境变量和配置文件的参数填充该结构体的字段。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [godotenv](https://github.com/joho/godotenv)  | 2076 |  Ruby 的 dotenv 库的 Go移植版(从.env文件加载环境变量)。 |![star > 1000][Silver]   
| [gofigure](https://github.com/ian-kent/gofigure)  | 57 |  让程序配置变得简单。 |![最近一年没有更新][Yellow]
| [gone/jconf](https://github.com/One-com/gone/tree/master/jconf)  | - |  模块化的JSON配置。保持配置结构及其配置的代码，并将解析委托给子模块，而不牺牲配置的完整序列化。 |
| [gookit/config](https://github.com/gookit/config)  | 73 |  程序配置管理(load,get,set)。支持JSON, YAML, TOML, INI, HCL。支持多文件加载，数据覆盖合并。 |
| [harvester](https://github.com/beatlabs/harvester)  | 39 |  一个易于使用的静态和动态配置包 |![最近一个周有更新][Green]
| [hjson](https://github.com/hjson/hjson-go)  | 170 |  更加人性化的JSON配置。轻松的语法，更少的错误，更多的注释。 |![star > 100][Bronze]   
| [ingo](https://github.com/schachmat/ingo)  | 23 |  flag保存在类ini的配置文件中。 |![最近一年没有更新][Yellow]
| [ini](https://github.com/go-ini/ini)  | 1554 |   读和写INI文件。 |![star > 1000][Silver]   
| [joshbetz/config](https://github.com/joshbetz/config)  | 193 |  一个可解析环境变量、JSON文件小巧的配置库，在SIGHUP时会自动重新加载。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig)  | 2372 |  管理来自环境变量的配置数据。 |![star > 1000][Silver]   
| [koanf](https://github.com/knadh/koanf)  | 78 |  轻量级可扩展库，用于读取Go应用程序中的配置。内置支持JSON, TOML, YAML, env，命令行。 |
| [konfig](https://github.com/lalamove/konfig)  | 508 |  可组合、可观察和高性能的分布式配置管理。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [mini](https://github.com/sasbury/mini)  | 19 |  用于解析ini类型的配置文件。 |
| [sprbox](https://github.com/oblq/sprbox)  | 3 |  支持构建环境的工具箱工厂和其他不确定的配置解析器(如YAML、TOML、JSON和环境vars)。 |
| [store](https://github.com/tucnak/store)  | 241 |  轻量级配置管理器。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [viper](https://github.com/spf13/viper)  | 9134 |  配置管理。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [xdg](https://github.com/OpenPeeDeeP/xdg)  | 32 |  遵循[XDG标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html)的跨平台包。 |

## 持续集成

*用于帮助进行持续集成的工具。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [drone](https://github.com/drone/drone)  | 18805 |  Drone 是一个基于 Docker 的持续集成平台，用 Go 编写。 |![star > 5000][Gold]   
| [duci](https://github.com/duck8823/duci)  | 44 |  一个简单的 ci 服务。 |![最近一个周有更新][Green]
| [gomason](https://github.com/nikogura/gomason)  | 27 |  在一个干净的工作区中对你的 Go 二进制文件进行测试、构建、签名和发布。 |
| [goveralls](https://github.com/mattn/goveralls)  | 571 |  Coveralls.io 是一个用 Go 编写，可持续对代码覆盖率进行检测的系统。 |![star > 100][Bronze]   
| [overalls](https://github.com/go-playground/overalls)  | 97 |  针对多package 的 Go 语言项目，可为类似 goveralls 这样的工具生成覆盖率报告。 |
| [roveralls](https://github.com/LawrenceWoodman/roveralls)  | 12 |  递归覆盖测试工具。 |![最近一年没有更新][Yellow]

## CSS预处理器

*用于预处理CSS文件的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gcss](https://github.com/yosssi/gcss)  | 422 |  纯Go编写的 CSS 预处理器。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-libsass](https://github.com/wellington/go-libsass)  | 129 |   采用 Go封装，100% 与 Sass 兼容的 libsass 项目。 |![star > 100][Bronze]   

## 数据结构

*用 Go 实现的通用的数据结构和算法。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [algorithms](https://github.com/shady831213/algorithms)  | 232 |  算法和数据结构。来源于CLRS。 |![star > 100][Bronze]   
| [binpacker](https://github.com/zhuangsirui/binpacker)  | 123 |  帮助用户构建自定义二进制流的二进制封装器和解包器 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [bit](https://github.com/yourbasic/bit)  | 52 |  Go 语言集合数据结构。提供了额外的位操作功能。 |![最近一年没有更新][Yellow]
| [bitset](https://github.com/willf/bitset)  | 476 |  实现了 bitsets 的 Go 包。 |![star > 100][Bronze]   
| [bloom](https://github.com/zhenjl/bloom)  | 128 |  在Go中实现了Bloom过滤器。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [bloom](https://github.com/yourbasic/bloom)  | 38 |  Golang Bloom过滤器的实现。 |![最近一年没有更新][Yellow]
| [boomfilters](https://github.com/tylertreat/BoomFilters)  | 1128 |  用于处理连续的概率数据结构。 |![star > 1000][Silver]   
| [concurrent-writer](https://github.com/free/concurrent-writer)  | 23 |  具备高并发能力，可替换 bufio.Writer。 |![最近一年没有更新][Yellow]
| [conjungo](https://github.com/InVisionApp/conjungo)  | 76 |  一个小型、强大和灵活的合并库。 |
| [count-min-log](https://github.com/seiflotfy/count-min-log)  | 43 |  Go实现Count-Min-log sketch的功能 : 使用近似计数器进行近似计数(类似Count-Min sketch，但使用更少内存)。 |![最近一年没有更新][Yellow]
| [crunch](https://github.com/superwhiskers/crunch)  | 19 |  打包实现缓冲区，以便轻松处理各种数据类型。 |
| [cuckoofilter](https://github.com/seiflotfy/cuckoofilter)  | 503 |  布谷鸟过滤器:一个用Go实现，可替代计数 bloom 过滤器。 |![star > 100][Bronze]   
| [deque](https://github.com/edwingeng/deque)  | 6 |  高度优化的双端队列。 |
| [deque](https://github.com/gammazero/deque)  | 62 |  快速环缓冲区deque(双端队列)。 |
| [dict](https://github.com/srfrog/dict)  | 8 |  实现类似 python dict的功能(dict)。 |
| [encoding](https://github.com/zhenjl/encoding)  | 94 |  整形压缩库。 |![最近一年没有更新][Yellow]
| [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree)  | 87 |  自适应基数树。 |
| [go-datastructures](https://github.com/Workiva/go-datastructures)  | 5088 |  可靠的、高性能的和线程安全的数据结构的集合。 |![star > 5000][Gold]   
| [go-ef](https://github.com/amallia/go-ef)  | 10 |  实现了 Elias-Fano 编码。 |![最近一年没有更新][Yellow]
| [go-geoindex](https://github.com/hailocab/go-geoindex)  | 309 |  基于内存的地理索引。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-mcache](https://github.com/OrlovEvgeny/go-mcache)  | 34 |  基于内存的实现了高性能的key:value存储库。指针缓存。 |
| [go-rquad](https://github.com/aurelien-rainone/go-rquad)  | 99 |  区域四叉树具有高效的点定位和邻域查找功能。 |![最近一年没有更新][Yellow]
| [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue)  | 25 |  并行FIFO队列。 |![最近一个周有更新][Green]
| [gods](https://github.com/emirpasic/gods)  | 6177 |  数据结构。容器、集合、列表、堆栈、地图、BidiMaps、树、HashSet等。 |![star > 5000][Gold]   
| [golang-set](https://github.com/deckarep/golang-set)  | 1140 |  线程安全和非线程安全的高性能集。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [goset](https://github.com/zoumo/goset)  | 16 |  一个有用的Go集合实现。 |![最近一年没有更新][Yellow]
| [goskiplist](https://github.com/ryszard/goskiplist)  | 191 |  基于 Go 的跳表实现。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gota](https://github.com/kniren/gota)  | 859 |  实现了数据帧，序列以及数据噪音。 |![star > 100][Bronze]   
| [hide](https://github.com/emvi/hide)  | 7 |  ID type with marshalling to/from hash to prevent sending IDs to clients. |
| [hilbert](https://github.com/google/hilbert)  | 179 |  用于映射空间填充曲线（例如 Hilbert 曲线和 Peano 曲线）和数值。 |![star > 100][Bronze]   
| [hyperloglog](https://github.com/axiomhq/hyperloglog)  | 660 |  HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. |![star > 100][Bronze]   
| [levenshtein](https://github.com/agext/levenshtein)  | 32 |  Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. |![最近一个周有更新][Green]
| [levenshtein](https://github.com/agnivade/levenshtein)  | 54 |  实现在Go中计算levenshtein距离。 |
| [mafsa](https://github.com/smartystreets/mafsa)  | 273 |  实现了 MA-FSA ，包含最小完美哈希。 |![star > 100][Bronze]   
| [merkletree](https://github.com/cbergoon/merkletree)  | 143 |  实现了merkle树，提供了对数据结构内容的有效和安全的验证。 |![star > 100][Bronze]   
| [mspm](https://github.com/BlackRabbitt/mspm)  | 7 |  用于信息检索的多字符串模式匹配算法。 |![最近一年没有更新][Yellow]
| [null](https://github.com/emvi/null)  | 5 |  对空的 Go 数据类型也可以进行JSON进行解析/反解析。 |
| [parsefields](https://github.com/MonaxGT/parsefields)  | 3 |  用于解析类似json的日志的工具，用于收集惟一的字段和事件。 |
| [pipeline](https://github.com/hyfather/pipeline)  | 15 |  实现了 fan-in 和 fan-out 的管道功能。 |
| [ptrie](https://github.com/viant/ptrie)  | - |  前缀树的一种实现。 |
| [ring](https://github.com/TheTannerRyan/ring)  | 87 |  高性能、线程安全的bloom过滤器。 |
| [roaring](https://github.com/RoaringBitmap/roaring)  | 646 |  实现了压缩 bitsets 的Go包。 |![star > 100][Bronze]   
| [set](https://github.com/StudioSol/set)  | 6 |  使用LinkedHashMap在Go中实现简单的set数据结构。 |
| [skiplist](https://github.com/MauriceGit/skiplist)  | 98 |  高性能的 Go 跳表实现。 |
| [skiplist](https://github.com/gansidui/skiplist)  | 63 |  在Go中实现了跳表。 |![最近一年没有更新][Yellow]
| [timedmap](https://github.com/zekroTJA/timedmap)  | 1 |  实现了有生命周期的键值对Map。 |
| [treap](https://github.com/perdata/treap)  | 7 |  使用树堆进行持久、快速有序的映射。 |
| [trie](https://github.com/derekparker/trie)  | 412 |  在Go中实现Trie。 |![star > 100][Bronze]   
| [ttlcache](https://github.com/diegobernardes/ttlcache)  | 93 |  基于内存的LRU算法实现。 |
| [typ](https://github.com/gurukami/typ)  | 9 |  从复杂结构中获取值，支持空类型、安全的类型转换。 |
| [willf/bloom](https://github.com/willf/bloom)  | 655 |  实现Bloom过滤器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]

## 数据库

*数据库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [badger](https://github.com/dgraph-io/badger)  | 6180 |  快速 K/V 存储。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [bcache](https://github.com/iwanbk/bcache)  | 26 |  基于内存的最终一致的分布式缓存。 |
| [BigCache](https://github.com/allegro/bigcache)  | 2420 |  高效的键/值缓存为千兆字节的数据。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [bolt](https://github.com/boltdb/bolt)  | 9911 |  K/V 数据库。 |![star > 5000][Gold]   ![最近一年没有更新][Yellow]
| [buntdb](https://github.com/tidwall/buntdb)  | 2424 |  基于内存的K/V，快速，可嵌入的数据库，可自定义索引和空间支持。 |![star > 1000][Silver]   
| [cache](https://github.com/akyoto/cache)  | 13 |  基于内存的 K/V 存储:带生命周期的值存储，0个依赖项，<100 LoC, 100%覆盖率。 |
| [cache2go](https://github.com/muesli/cache2go)  | 990 |  基于内存的 K/V 缓存，支持超时的自动失效。 |![star > 100][Bronze]   
| [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache)  | 29 |  BigCache 支持集群和独立且生命周期存储项。 |![最近一年没有更新][Yellow]
| [cockroach](https://github.com/cockroachdb/cockroach)  | 16662 |  可伸缩、区域备份、事务性数据存储。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [couchcache](https://github.com/codingsince1985/couchcache)  | 40 |  由 Couchbase服务 支持的RESTful缓存微服务。 |
| [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL)  | 1441 |  区块链领域的一个SQL数据库。 |![star > 1000][Silver]   
| [dgraph](https://github.com/dgraph-io/dgraph)  | 10039 |  可伸缩、分布式、低延迟、高吞吐量的图形数据库。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [diskv](https://github.com/peterbourgon/diskv)  | 742 |  支持磁盘备份的可持久化 K/V 存储。 |![star > 100][Bronze]   
| [eliasdb](https://github.com/krotik/eliasdb)  | 532 |  无其他依赖项，支持REST API，短语搜索和sql类似的查询语言的事务图数据库。 |![star > 100][Bronze]   
| [fastcache](https://github.com/VictoriaMetrics/fastcache)  | 475 |  基于内存的快速线程安全的缓存，可缓存大量的条目。最大限度地减少GC开销。 |![star > 100][Bronze]   
| [GCache](https://github.com/bluele/gcache)  | 875 |  支持过期缓存、LFU、LRU和ARC的缓存库。 |![star > 100][Bronze]   
| [go-cache](https://github.com/pmylund/go-cache)  | 2830 |  基于内存的 K/V 存储/缓存 : (类似于Memcached)，适用于单机应用程序。 |![star > 1000][Silver]   
| [goleveldb](https://github.com/syndtr/goleveldb)  | 3130 |  在Go中实现[LevelDB](https://github.com/google/leveldb) key/value数据库。 |![star > 1000][Silver]   
| [gorocksdb](https://github.com/kapitan-k/gorocksdb)  | 8 |  用 Go 对[RocksDB](https://rocksdb.org)实现了封装。 |![最近一年没有更新][Yellow]
| [groupcache](https://github.com/golang/groupcache)  | 7597 |  Groupcache是一个缓存和缓存填充库，在许多情况下，它是memcached的替代品。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [influxdb](https://github.com/influxdb/influxdb)  | 16832 |  可伸缩的数据存储，用于指标衡量、事件和实时分析。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [ledisdb](https://github.com/siddontang/ledisdb)  | 3054 |  Ledisdb是一种高性能的NoSQL，类似于基于LevelDB的Redis。 |![star > 1000][Silver]   
| [levigo](https://github.com/jmhodges/levigo)  | 364 |  实现了对LevelDB封装。 |![star > 100][Bronze]   
| [moss](https://github.com/couchbase/moss)  | 716 |  Moss是一个用100% Go编写的简单LSM键值存储引擎。 |![star > 100][Bronze]   
| [nutsdb](https://github.com/xujiajun/nutsdb)  | 849 |  Nutsdb是一个用纯Go编写的简单、快速、可嵌入、持久的键/值存储。它支持完全序列化的事务和许多数据结构，如列表、集合、排序集。 |![star > 100][Bronze]   
| [piladb](https://github.com/fern4lvarez/piladb)  | 171 |  基于堆栈数据结构的轻量级RESTful数据库引擎。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [prometheus](https://github.com/prometheus/prometheus)  | 25173 |  用于监控系统和时序的数据库。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [pudge](https://github.com/recoilme/pudge)  | 218 |  使用Go的标准库编写的快速和简单的键/值存储。 |![star > 100][Bronze]   
| [rqlite](https://github.com/rqlite/rqlite)  | 4660 |  基于SQLite的轻量级分布式关系数据库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [Scribble](https://github.com/nanobox-io/golang-scribble)  | 57 |  小型平面文件JSON存储。 |
| [slowpoke](https://github.com/recoilme/slowpoke)  | 85 |  具有持久性的键值存储。 |
| [tempdb](https://github.com/rafaeljesus/tempdb)  | 13 |  用于临时数据存放的 K/V 存储。 |![最近一年没有更新][Yellow]
| [tidb](https://github.com/pingcap/tidb)  | 19747 |  TiDB是一个分布式SQL数据库。灵感来自谷歌F1的设计。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [tiedot](https://github.com/HouzuoGuo/tiedot)  | 2359 |  属于你的NoSQL数据库。 |![star > 1000][Silver]   
| [Vasto](https://github.com/chrislusf/vasto)  | 144 |  分布式高性能键值存储。可做磁盘备份。最终一致。高可用。能够在不中断服务的情况下增长或收缩。 |![star > 100][Bronze]   
| [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)  | 950 |  开源，快速，可伸缩的时间序列数据库。支持PromQL。 |![star > 100][Bronze]   ![最近一个周有更新][Green]

*数据库迁移。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [avro](https://github.com/khezen/avro)  | 5 |  发现SQL schemas并将其转换为AVRO schemas。 |![最近一个周有更新][Green]
| [darwin](https://github.com/GuiaBolso/darwin)  | 83 |  用于数据库 schema 升级的库。 |
| [go-fixtures](https://github.com/RichardKnop/go-fixtures)  | 20 |  类似 Django fixture，用于 Go 建立内置数据库/sql库。 |
| [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations)  | 23 |  用Go -pg/pg编写的迁移包。 |
| [gondolier](https://github.com/emvi/gondolier)  | 26 |  使用结构修饰的数据库迁移库。 |
| [goose](https://github.com/steinbacher/goose)  | 117 |  数据库迁移工具。您可以通过创建增量SQL或Go脚本来管理数据库的升级。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gormigrate](https://github.com/go-gormigrate/gormigrate)  | 324 |  面向Gorm ORM的数据库 schema 迁移辅助程序。 |![star > 100][Bronze]   
| [migrate](https://github.com/golang-migrate/migrate)  | 2518 |  基于CLI的数据库迁移库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [migrator](https://github.com/lopezator/migrator)  | 29 |  非常简单的 Go 数据库迁移库。 |![最近一个周有更新][Green]
| [pravasan](https://github.com/pravasan/pravasan)  | 24 |  简易的迁移工具-目前只支持MySQL，但计划很快支持Postgres, SQLite, MongoDB等。 |
| [soda](https://github.com/gobuffalo/pop/tree/master/soda)  | - |  数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。 |
| [sql-migrate](https://github.com/rubenv/sql-migrate)  | 1384 |  数据库迁移工具。允许使用go-bindata将迁移嵌入到应用程序中。 |![star > 1000][Silver]   ![最近一个周有更新][Green]

*数据库工具。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [chproxy](https://github.com/Vertamedia/chproxy)  | 297 |  ClickHouse数据库的HTTP代理。 |![star > 100][Bronze]   
| [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk)  | 129 |  收集小的 insterts 并向 ClickHouse 服务器发送大请求。 |![star > 100][Bronze]   
| [datagen](https://github.com/codingconcepts/datagen)  | 6 |  一个快速的数据生成器，支持多表感知和多行DML。 |![最近一个周有更新][Green]
| [dbbench](https://github.com/sj14/dbbench)  | 30 |  数据库基准测试工具，支持多个数据库和脚本。 |
| [go-mysql](https://github.com/siddontang/go-mysql)  | 1842 |   Go 工具集，用于处理MySQL协议和复制。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch)  | 2333 |  自动将MySQL数据同步到Elasticsearch中。 |![star > 1000][Silver]   
| [kingshard](https://github.com/flike/kingshard)  | 4561 |  kingshard 是基于 Golang 的MySQL高性能代理。 |![star > 1000][Silver]   
| [myreplication](https://github.com/2tvenom/myreplication)  | 141 |  MySql二进制日志复制监听器。支持基于语句和行的复制。 |![star > 100][Bronze]   
| [octillery](https://github.com/knocknote/octillery)  | 51 |  用于数据库分表(支持每个ORM或原生SQL)。 |![最近一个周有更新][Green]
| [orchestrator](https://github.com/github/orchestrator)  | 2983 |  MySQL复制拓扑管理器和可视化工具。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [pgweb](https://github.com/sosedoff/pgweb)  | 5950 |  基于web的PostgreSQL数据库浏览器。 |![star > 5000][Gold]   
| [prep](https://github.com/hexdigest/prep)  | 24 |  在不更改代码的情况下使用准备好的SQL语句。 |![最近一年没有更新][Yellow]
| [pREST](https://github.com/nuveo/prest)  | 2074 |  基于PostgreSQL database的RESTful API服务。 |![star > 1000][Silver]   
| [rwdb](https://github.com/andizzle/rwdb)  | 10 |  rwdb为多个数据库服务器的设置提供读取副本功能。 |![最近一年没有更新][Yellow]
| [vitess](https://github.com/youtube/vitess)  | 8345 |  vitess提供了可以为大规模web服务扩展MySQL数据库提供便利的服务和工具。 |![star > 5000][Gold]   ![最近一个周有更新][Green]

*SQL查询生成器，用于构建和使用SQL的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Dotsql](https://github.com/gchaincl/dotsql)  | 437 |  Go library帮助您将sql文件保存在一个地方，并轻松地使用它们。 |![star > 100][Bronze]   
| [gendry](https://github.com/didi/gendry)  | 743 |  非入侵的SQL构建器和强大的数据绑定器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [godbal](https://github.com/xujiajun/godbal)  | 50 |  数据库抽象层(dbal)。支持SQL builder，轻松获取结果。 |
| [goqu](https://github.com/doug-martin/goqu)  | 620 |  常用的SQL生成器和查询库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [igor](https://github.com/galeone/igor)  | 77 |  PostgreSQL的抽象层，支持高级功能和类似gorm的语法。 |![最近一年没有更新][Yellow]
| [ormlite](https://github.com/pupizoid/ormlite)  | - |  包含一些类似orm的特性和sqlite数据库的辅助程序的轻量级包 |
| [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx)  | 433 |  Powerful data retrieval methods as well as DB-agnostic query building capabilities. |![star > 100][Bronze]   
| [scaneo](https://github.com/variadico/scaneo)  | 149 |  生成用于将数据库行转换为任意结构体的 Go 代码。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [sqrl](https://github.com/elgris/sqrl)  | 175 |  SQL查询生成器，从Squirrel fork而来，并再此基础上对性能做了优化。 |![star > 100][Bronze]   
| [Squalus](https://gitlab.com/qosenergy/squalus)  | - |  Go SQL中间层，能使得执行查询更加容易。 |
| [Squirrel](https://github.com/Masterminds/squirrel)  | 2216 |  帮助您构建SQL查询的Go库。 |![star > 1000][Silver]   
| [xo](https://github.com/knq/xo)  | 2146 |  基于现有的schema定义和自定义查询生成 Go 代码，基于支持PostgreSQL、MySQL、SQLite、Oracle和Microsoft SQL Server。 |![star > 1000][Silver]   

## 数据库驱动程序

*用于连接和操作数据库的库。*

* Relational Databases
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [avatica](https://github.com/apache/calcite-avatica-go)  | 32 |  Apache Avatica/Phoenix SQL驱动程序。 |
| [bgc](https://github.com/viant/bgc)  | 12 |  BigQuery 的数据存储连接。 |
| [firebirdsql](https://github.com/nakagami/firebirdsql)  | 102 |  Firebird RDBMS SQL驱动程序。 |![star > 100][Bronze]   
| [go-adodb](https://github.com/mattn/go-adodb)  | 90 |  Microsoft ActiveX对象数据库驱动程序。 |
| [go-mssqldb](https://github.com/denisenkom/go-mssqldb)  | 1011 |  微软MSSQL驱动程序。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [go-oci8](https://github.com/mattn/go-oci8)  | 400 |  Oracle 驱动程序。 |![star > 100][Bronze]   
| [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql)  | 7976 |  MySQL驱动程序。 |![star > 5000][Gold]   
| [go-sqlite3](https://github.com/mattn/go-sqlite3)  | 3392 |  SQLite3驱动程序。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gofreetds](https://github.com/minus5/gofreetds)  | 90 |  基于[FreeTDS](http://www.freetds.org)封装的微软MSSQL Go 驱动。 |
| [goracle](https://github.com/go-goracle/goracle)  | 229 |  基于 ODPI-C 的 Oracle 驱动程序 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [pgx](https://github.com/jackc/pgx)  | 1878 |  PostgreSQL驱动，支持比现有database/sql更多的特性。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [pq](https://github.com/lib/pq)  | 5123 |  纯 Go 的Postgres驱动。 |![star > 5000][Gold]   ![最近一个周有更新][Green]

* NoSQL Databases
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [aerospike-client-go](https://github.com/aerospike/aerospike-client-go)  | 301 |  Aerospike 客户端。 |![star > 100][Bronze]   
| [arangolite](https://github.com/solher/arangolite)  | 65 |  轻量级的 ArangoDB 驱动。 |
| [asc](https://github.com/viant/asc)  | 4 |  Aerospike 的数据存储连接器。 |
| [dynago](https://github.com/underarmour/dynago)  | 64 |  满足 principle of least surprise 的 DynamoDB 客户端。 |![最近一年没有更新][Yellow]
| [forestdb](https://github.com/couchbase/goforestdb)  | 29 |  基于 Go 的 ForestDB 接口实现。 |![最近一年没有更新][Yellow]
| [go-couchbase](https://github.com/couchbase/go-couchbase)  | 292 |  Couchbase客户端。 |![star > 100][Bronze]   
| [go-couchdb](https://github.com/fjl/go-couchdb)  | 51 |  基于 Go 的 Yet another CouchDB 的 Http 接口封装。 |
| [go-pilosa](https://github.com/pilosa/go-pilosa)  | 31 |   Pilosa客户端。 |![最近一个周有更新][Green]
| [go-rejson](https://github.com/nitishm/go-rejson)  | 86 |  实现了基于 Redigo 客户端的redislabs' ReJSON 模块。可简单地将结构体存储为JSON对象并对其进行操作。 |
| [gocb](https://github.com/couchbase/gocb)  | 290 |  官方Couchbase Go SDK。 |![star > 100][Bronze]   
| [gocql](http://gocql.github.io)  | - |  Apache Cassandra 的 Go 驱动。 |
| [godis](https://github.com/piaohao/godis)  | 58 |  由GoLang实现的redis客户端，灵感来自jedis。 |![最近一个周有更新][Green]
| [godscache](https://github.com/defcronyke/godscache)  | 6 |  谷歌云平台Go Datastore包的封装，它采用了memcached添加缓存。 |
| [gomemcache](https://github.com/bradfitz/gomemcache/)  | - |  memcache客户端库。 |
| [gorethink](https://github.com/dancannon/gorethink)  | 1454 |  RethinkDB 驱动。 |![star > 1000][Silver]   
| [goriak](https://github.com/zegl/goriak)  | 24 |   Riak KV 驱动。 |
| [mgo](https://github.com/globalsign/mgo)  | 1620 |  (已停止维护) MongoDB驱动。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [mongo-go-driver](https://github.com/mongodb/mongo-go-driver)  | 2973 |  官方的 MongoDB 驱动。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [neo4j](https://github.com/cihangir/neo4j)  | 24 |  Neo4j Rest API实现。 |![最近一年没有更新][Yellow]
| [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO)  | 72 |  Neo4j REST 客户端。 |![最近一年没有更新][Yellow]
| [neoism](https://github.com/jmcvetta/neoism)  | 356 |  Golang 的 Neo4j 客户端。 |![star > 100][Bronze]   
| [redeo](https://github.com/bsm/redeo)  | 258 |  与 redis 协议兼容的 TCP 服务器/服务。 |![star > 100][Bronze]   
| [redigo](https://github.com/gomodule/redigo)  | 6197 |  Redigo 是基于 Go 的Redis 客户端。 |![star > 5000][Gold]   
| [redis](https://github.com/go-redis/redis)  | 6324 |  基于 Go 的 Redis 客户端。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [xredis](https://github.com/shomali11/xredis)  | 9 |  类型安全，可定制，清晰和易用的Redis客户端。 |

* Search and Analytic Databases.
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [bleve](https://github.com/blevesearch/bleve)  | 5769 |  基于 Go 的现代文本索引库。 |![star > 5000][Gold]   
| [elastic](https://github.com/olivere/elastic)  | 4063 |  Elasticsearch 客户端。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [elasticsql](https://github.com/cch123/elasticsql)  | 377 |  将 SQL 转换为 elasticsearch dsl。 |![star > 100][Bronze]   
| [elastigo](https://github.com/mattbaird/elastigo)  | 947 |  Elasticsearch 客户端。 |![star > 100][Bronze]   
| [go-elasticsearch](https://github.com/elastic/go-elasticsearch)  | 1510 |  官方 Elasticsearch 客户端。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [goes](https://github.com/OwnLocal/goes)  | 24 |  实现了与 Elasticsearch 交互的库。 |![最近一年没有更新][Yellow]
| [riot](https://github.com/go-ego/riot)  | 4654 |  基于 Go 的 开源、分布式、简单高效的搜索引擎。 |![star > 1000][Silver]   
| [skizze](https://github.com/seiflotfy/skizze)  | 68 |  面向概率数据结构的服务和存储。 |![最近一年没有更新][Yellow]

* Multiple Backends.
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [cachego](https://github.com/fabiorphp/cachego)  | 110 |  基于多个驱动程序的缓存组件。 |![star > 100][Bronze]   
| [cayley](https://github.com/google/cayley)  | 12634 |  图形数据库，支持多个后端。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [dsc](https://github.com/viant/dsc)  | 13 |  面向 SQL、NoSQL、结构化文件的数据存储连接。 |![最近一个周有更新][Green]
| [gokv](https://github.com/philippgille/gokv)  | 77 |  可扩展的简单的 K/V 存储(Redis、Consul、etcd、bbolt、BadgerDB、LevelDB、Memcached、DynamoDB、S3、PostgreSQL、MongoDB、CockroachDB等等)。 |

## 日期和时间

*用于处理日期和时间的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [carbon](https://github.com/uniplaces/carbon)  | 333 |  简单的时间扩展，包含了许多使用方法，从 PHP Carbon 库移植的。 |![star > 100][Bronze]   
| [date](https://github.com/rickb777/date)  | 27 |  增加处理日期、日期范围、时间跨度、时间段和time-of-day。 |![最近一个周有更新][Green]
| [dateparse](https://github.com/araddon/dateparse)  | 880 |  可以解析很多格式不固定的日期字符串。 |![star > 100][Bronze]   
| [durafmt](https://github.com/hako/durafmt)  | 236 |  轻量级、可让time.Duration更加易读的库。 |![star > 100][Bronze]   
| [feiertage](https://github.com/wlbr/feiertage)  | 22 |  用于计算德国公共假期的函数，比如复活节、感恩节等 |
| [go-persian-calendar](https://github.com/yaa110/go-persian-calendar)  | 60 |  太阳历实现。 |
| [go-sunrise](https://github.com/nathan-osman/go-sunrise)  | 13 |  计算指定位置的日出和日落时间。 |![最近一年没有更新][Yellow]
| [goweek](https://github.com/grsmv/goweek)  | 18 |  用于处理以星期实体单位的库。 |![最近一年没有更新][Yellow]
| [iso8601](https://github.com/relvacode/iso8601)  | 68 |  不用正则表达式有效解析 ISO8601 日期时间。 |
| [kair](https://github.com/GuilhermeCaruso/kair)  | 9 |  用于处理日期和时间的 golang 库。 |
| [now](https://github.com/jinzhu/now)  | 2151 |  now 是时间有关的工具类。 |![star > 1000][Silver]   
| [NullTime](https://github.com/kirillDanshin/nulltime)  | 9 |  可以允许 time.Time 为null。 |![最近一年没有更新][Yellow]
| [strftime](https://github.com/awoodbeck/strftime)  | 5 |  C99-compatible strftime formatter。 |![最近一年没有更新][Yellow]
| [timespan](https://github.com/SaidinWoT/timespan)  | 60 |  用于处理时间间隔相关的库，可定义开始时间和持续时间。 |
| [timeutil](https://github.com/leekchan/timeutil)  | 168 |  面向 Golang 的时间库，集成了很多有用的扩展(Timedelta, Strftime, ...)。 |![star > 100][Bronze]   
| [tuesday](https://github.com/osteele/tuesday)  | 7 |  Ruby-compatible Strftime function。 |![最近一年没有更新][Yellow]

## 分布式系统

*协助构建分布式系统的包。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [celeriac](https://github.com/svcavallar/celeriac.v1)  | 52 |  用于对 Celery worker、任务、事件进行交互和监控的库。 |
| [consistent](https://github.com/buraksezer/consistent)  | 183 |  Consistent hashing with bounded loads。 |![star > 100][Bronze]   
| [dht](https://github.com/anacrolix/dht)  | 124 |  BitTorrent Kademlia DHT的实现。 |![star > 100][Bronze]   
| [digota](https://github.com/digota/digota)  | 297 |  基于 grpc 的电子商务微服务。 |![star > 100][Bronze]   
| [dot](https://github.com/dotchain/dot/)  | - |  基于 transformation/OT 的分布式同步。 |
| [doublejump](https://github.com/edwingeng/doublejump)  | 38 |  实现了谷歌的jump consistent hash。 |
| [dragonboat](https://github.com/lni/dragonboat)  | 2479 |  一个功能齐全，高性能的库集。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [drmaa](https://github.com/dgruber/drmaa)  | 24 |  符合 DRMAA 标准的集群调度程序作业提交库。 |![最近一年没有更新][Yellow]
| [dynamolock](https://cirello.io/dynamolock)  | - |  DynamoDB-backed 分布式锁定实现。 |
| [dynatomic](https://github.com/tylfin/dynatomic)  | 8 |  基于 DynamoDB 的 原子计数器的库。 |
| [emitter-io](https://github.com/emitter-io/emitter)  | 1893 |  高性能、分布式、安全和低延迟的发布-订阅平台，使用MQTT、Websockets和love构建。 |![star > 1000][Silver]   
| [flowgraph](https://github.com/vectaport/flowgraph)  | 18 |  flow-based programming package。 |
| [gleam](https://github.com/chrislusf/gleam)  | 2052 |  使用纯Go和Luajit编写的快速、可伸缩的分布式map/reduce系统，结合了Go的高并发性和Luajit的高性能，可以独立运行或分布式运行。 |![star > 1000][Silver]   
| [glow](https://github.com/chrislusf/glow)  | 2502 |  全部用 Go 实现，易用、可伸缩，可用于分布式大数据处理，Map-Reduce, DAG执行。 |![star > 1000][Silver]   
| [go-health](https://github.com/InVisionApp/go-health)  | 474 |  用于在服务中启用异步依赖项健康检查的库。 |![star > 100][Bronze]   
| [go-jump](https://github.com/dgryski/go-jump)  | 251 |  提供了谷歌的 “Jump” 一致哈希函数接口。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-kit](https://github.com/go-kit/kit)  | 14249 |  支持服务发现、负载平衡、插件式传输、请求跟踪等功能的Microservice toolkit。 |![star > 5000][Gold]   
| [gorpc](https://github.com/valyala/gorpc)  | 547 |  简单、快速和可伸缩的RPC库。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [grpc-go](https://github.com/grpc/grpc-go)  | 8884 |  gRPC的Go语言实现。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [hprose](https://github.com/hprose/hprose-golang)  | 995 |  支持25+种语言RPC库。 |![star > 100][Bronze]   
| [jaeger](https://github.com/jaegertracing/jaeger)  | 8504 |  分布式跟踪系统。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [jsonrpc](https://github.com/osamingo/jsonrpc)  | 113 |  jsonrpc 包，实现了 JSON-RPC 2.0。 |![star > 100][Bronze]   
| [jsonrpc](https://github.com/ybbus/jsonrpc)  | 98 |  JSON-RPC 2.0 HTTP客户端。 |
| [KrakenD](https://github.com/devopsfaith/krakend)  | 1703 |  具有中间件的高性能API网关框架。 |![star > 1000][Silver]   
| [micro](https://github.com/micro/micro)  | 6491 |  可插拔的微服务 toolkit 和分布式系统平台。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [NATS](https://github.com/nats-io/gnatsd)  | 6185 |  轻量级、高性能消息传递系统，可用于微服务、物联网(IoT)和云。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [outboxer](https://github.com/italolelis/outboxer)  | 2 |  实现了 outbox pattern Go 库。 |![最近一个周有更新][Green]
| [pglock](https://cirello.io/pglock)  | - |  postgresql 的分布式锁定实现。 |
| [raft](https://github.com/hashicorp/raft)  | 2808 |  Raft consensus协议的实现。 by HashiCorp。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [raft](https://github.com/coreos/etcd/tree/master/raft)  | - |  Raft consensus协议的实现。 by CoreOS。 |
| [redis-lock](https://github.com/bsm/redis-lock)  | 146 |  基于redis的分布式锁简易实现。 |![star > 100][Bronze]   
| [resgate](https://resgate.io/)  | - |  用于构建REST、实时和RPC API的实时API网关，其中所有客户端都是无缝同步的。 |
| [ringpop-go](https://github.com/uber/ringpop-go)  | 568 |  可伸缩的，容错、应用分层的的Go应用程序。 |![star > 100][Bronze]   
| [rpcx](https://github.com/smallnest/rpcx)  | 3706 |  分布式可插拔的RPC服务框架，如阿里巴巴Dubbo。 |![star > 1000][Silver]   
| [sleuth](https://github.com/ursiform/sleuth)  | 297 |  用于HTTP服务之间进行无中心p2p自动发现和RPC通信的库(使用[ZeroMQ](https://github.com/zeromq/libzmq))。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [tendermint](https://github.com/tendermint/tendermint)  | 3091 |  一个高性能中间件，可将任何语言的状态机转换为 Byzantine Fault 状态机。使用 Tendermint 一致性及区块链协议。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [torrent](https://github.com/anacrolix/torrent)  | 2803 |  BitTorrent 客户端。 |![star > 1000][Silver]   ![最近一个周有更新][Green]

## 电子邮件

*实现了电子邮件创建和发送。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [chasquid](https://blitiri.com.ar/p/chasquid)  | - |  用Go编写的SMTP服务器。 |
| [douceur](https://github.com/aymerick/douceur)  | 158 |  在HTML邮件中支持CSS内联。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [email](https://github.com/jordan-wright/email)  | 1084 |  一个强大和灵活的电子邮件库。 |![star > 1000][Silver]   
| [go-dkim](https://github.com/toorop/go-dkim)  | 46 |  DKIM库，用于签署 & 验证电子邮件。 |
| [go-imap](https://github.com/emersion/go-imap)  | 717 |  用于客户端和服务器的IMAP库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-message](https://github.com/emersion/go-message)  | 104 |  用于Internet消息格式化和邮件消息的流媒体库。 |![star > 100][Bronze]   
| [go-premailer](https://github.com/vanng822/go-premailer)  | 35 |  在HTML邮件中支持CSS内联。 |
| [Gomail](https://github.com/go-gomail/gomail/)  | - |  一个非常简单和强大的邮件发送库。 |
| [Hectane](https://github.com/hectane/hectane)  | 168 |  轻量级的SMTP客户机，提供了HTTP API。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [hermes](https://github.com/matcornic/hermes)  | 1603 |  可生成干净的、响应式的HTML电子邮件。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [MailHog](https://github.com/mailhog/MailHog)  | 5089 |  电子邮件和SMTP测试工具，对外提供了 web 和 API 接口。 |![star > 5000][Gold]   
| [SendGrid](https://github.com/sendgrid/sendgrid-go)  | 516 |  SendGrid 的 Go语言库，用于发送电子邮件。 |![star > 100][Bronze]   
| [smtp](https://github.com/mailhog/smtp)  | 49 |  SMTP服务器协议状态机。 |![最近一年没有更新][Yellow]

## 可嵌入的脚本语言

*在go代码中嵌入其他语言。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [agora](https://github.com/PuerkitoBio/agora)  | 321 |  基于 Go 的动态类型，可嵌入的编程语言。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [anko](https://github.com/mattn/anko)  | 911 |  用Go编写的解释器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [binder](https://github.com/alexeyco/binder)  | 29 |  Lua接口，基于[gopher-lua](https://github.com/yuin/gopher-lua)。 |
| [expr](https://github.com/antonmedv/expr)  | 677 |  一个可以计算表达式的引擎。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [gentee](https://github.com/gentee/gentee)  | 25 |  嵌入式脚本编程语言。 |![最近一个周有更新][Green]
| [gisp](https://github.com/jcla1/gisp)  | 429 |  LISP 的 Go 接口。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-duktape](https://github.com/olebedev/go-duktape)  | 648 |  支持 Duktape JavaScript 引擎。 |![star > 100][Bronze]   
| [go-lua](https://github.com/Shopify/go-lua)  | 1652 |  用 Go 实现的 Lua 5.2 VM接口。 |![star > 1000][Silver]   
| [go-php](https://github.com/deuill/go-php)  | 671 |  PHP 的 Go 接口。 |![star > 100][Bronze]   
| [go-python](https://github.com/sbinet/go-python)  | 898 |  CPython C-API 的 Go 接口。 |![star > 100][Bronze]   
| [golua](https://github.com/aarzilli/golua)  | 439 |  Lua C 的 Go 接口。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [gopher-lua](https://github.com/yuin/gopher-lua)  | 2923 |  用 Go 实现的 Lua 5.1 虚拟机和编译器。 |![star > 1000][Silver]   
| [gval](https://github.com/PaesslerAG/gval)  | 133 |  一种用Go编写的高度可定制的表达式语言。 |![star > 100][Bronze]   
| [ngaro](https://github.com/db47h/ngaro)  | 19 |  嵌入式 Ngaro VM实现，支持在 Retro 中运行脚本。 |![最近一年没有更新][Yellow]
| [otto](https://github.com/robertkrimen/otto)  | 4691 |  用 Go 编写的 JavaScript 解释器。 |![star > 1000][Silver]   
| [purl](https://github.com/ian-kent/purl)  | 27 |  嵌入 Go 的 Perl 5.18.2。 |![最近一年没有更新][Yellow]
| [tengo](https://github.com/d5/tengo)  | 1279 |  字节码编译的脚本语言。 |![star > 1000][Silver]   

## 错误处理

*处理错误的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [errlog](https://github.com/snwfdhmp/errlog)  | 143 |  用于定位抛出错误的源代码(以及一些其他快速调试特性)。可插入到任何 logger 的位置。 |![star > 100][Bronze]   
| [errors](https://github.com/pkg/errors)  | 4786 |  可让你很简单的进行错误处理。 |![star > 1000][Silver]   
| [errorx](https://github.com/joomcode/errorx)  | 549 |  一个功能丰富的错误包，可进行堆栈跟踪、组装异常信息以及其他。 |![star > 100][Bronze]   
| [go-multierror](https://github.com/hashicorp/go-multierror)  | 715 |  可将一系列的错误作为一个整体来显示。 |![star > 100][Bronze]   
| [tracerr](https://github.com/ztrue/tracerr)  | 491 |  可展示错误的堆栈跟踪信息和源码片段。 |![star > 100][Bronze]   
| [werr](https://github.com/txgruppi/werr)  | 11 |  对错误异常进行了捕获封装，封装信息包含了调用它的文件、行和堆栈。 |![最近一年没有更新][Yellow]

## 文件

*处理文件和文件系统的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [afero](https://github.com/spf13/afero)  | 2193 |  文件系统的抽象系统。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [checksum](https://github.com/codingsince1985/checksum)  | 6 |  生成大型文件的消息摘要(如 MD5 和 SHA256)。 |
| [flop](https://github.com/homedepot/flop)  | 8 |  文件操作库，是[GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invoc.html)的镜像。 |
| [go-csv-tag](https://github.com/artonge/go-csv-tag)  | 45 |  使用 tag 加载 csv 文件。 |
| [go-decent-copy](https://github.com/hugocarreira/go-decent-copy)  | 11 |  拷贝文件。 |
| [go-exiftool](https://github.com/barasher/go-exiftool)  | 1 |  ExifTool 的 Go 实现，这个著名的库用于从文件(图片、PDF、office，…)中提取尽可能多的元数据(EXIF、IPTC，…)。 |
| [go-gtfs](https://github.com/artonge/go-gtfs)  | 15 |  加载gtfs文件。 |
| [notify](https://github.com/rjeczalik/notify)  | 487 |  文件系统事件通知库，具有类似于os/signal的简单API，。 |![star > 100][Bronze]   
| [opc](https://github.com/qmuntal/opc)  | 57 |  加载Open Packaging Conventions (OPC)文件。 |
| [pdfcpu](https://github.com/hhrutter/pdfcpu)  | 935 |  PDF处理器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [skywalker](https://github.com/dixonwille/skywalker)  | 48 |  可以轻松地并发地遍历文件系统。 |![最近一年没有更新][Yellow]
| [stl](https://gitlab.com/russoj88/stl)  | - |  采用并行读取算法的进行读取和写入STL(立体光刻)文件的模块。 |
| [tarfs](https://github.com/posener/tarfs)  | 35 |  tar文件的实现[ FileSystem 接口](https://godoc.org/github.com/kr/fs#FileSystem)。 |![最近一年没有更新][Yellow]
| [vfs](https://github.com/C2FO/vfs)  | 21 |  一组可插拔的、可扩展的和自定义的文件系统功能，用于跨越许多文件系统类型，如os、S3和GCS。 |![最近一个周有更新][Green]

## 金融

*会计和财务软件包。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [accounting](https://github.com/leekchan/accounting)  | 482 |  货币和货币格式。 |![star > 100][Bronze]   
| [currency](https://github.com/bnkamalesh/currency)  | 8 |  高性能、准确的货币计算软件包。 |
| [decimal](https://github.com/shopspring/decimal)  | 1574 |  任意精度定点的十进制数。 |![star > 1000][Silver]   
| [go-finance](https://github.com/FlashBoys/go-finance)  | 536 |  综合金融市场数据。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-finance](https://github.com/alpeb/go-finance)  | 41 |  用于货币时间价值(年金)、现金流、利率转换、债券和折旧计算的金融函数库。 |![最近一年没有更新][Yellow]
| [go-money](https://github.com/rhymond/go-money)  | 610 |  Fowler 货币模式的实现。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [ofxgo](https://github.com/aclindsa/ofxgo)  | 60 |  查询 OFX 服务器和/或解析响应。 |
| [orderbook](https://github.com/i25959341/orderbook)  | 67 |  限购单匹配引擎。 |
| [techan](https://github.com/sdcoffey/techan)  | 152 |  拥有先进的市场分析和交易策略的技术分析库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [transaction](https://github.com/claygod/transaction)  | 55 |  嵌入式事务数据库，可多线程模式运行。 |
| [vat](https://github.com/dannyvankooten/vat)  | 60 |  增值税编号验证 & 欧盟增值税税率。 |

## 表单

*用于处理表单的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [bind](https://github.com/robfig/bind)  | 23 |  将表单数据与任意 Go 变量进行绑定。 |![最近一年没有更新][Yellow]
| [binding](https://github.com/mholt/binding)  | 752 |  将来自 net/HTTP 请求的表单、JSON 数据绑定到结构体。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [conform](https://github.com/leebenson/conform)  | 171 |  控制用户输入。基于struct tags可对数据进行修剪、清理和擦除。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [form](https://github.com/go-playground/form)  | 348 |   将 url 中的数据解析到 Go 变量中，以及将 Go 语言变量编码进 url。支持 Dual Array 及 Full map。 |![star > 100][Bronze]   
| [formam](https://github.com/monoculum/formam)  | 122 |  将表单的值解码为 struct。 |![star > 100][Bronze]   
| [forms](https://github.com/albrow/forms)  | 103 |  与框架无关的库，用于解析和验证支持多部分表单和文件的表单/JSON数据。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gorilla/csrf](https://github.com/gorilla/csrf)  | 426 |  用于Go web应用程序和服务的CSRF保护。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [nosurf](https://github.com/justinas/nosurf)  | 962 |  CSRF保护中间件。 |![star > 100][Bronze]   

## 方法

*在Go中支持函数式编程的包。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [fpGo](https://github.com/TeaEntityLab/fpGo)  | 104 |  提供函数式编程功能。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [fuego](https://github.com/seborama/fuego)  | 34 |  Functional Experiment in Go。 |
| [go-underscore](https://github.com/tobyhede/go-underscore)  | 1064 |  常用辅助方法集合。 |![star > 1000][Silver]   

## 游戏开发

*很棒的游戏开发库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Azul3D](https://github.com/azul3d/engine)  | 425 |  用Go编写的 3D 游戏引擎。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Ebiten](https://github.com/hajimehoshi/ebiten)  | 1814 |  很简单的 2D 游戏库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [engo](https://github.com/EngoEngine/engo)  | 1076 |  开源 2D 游戏引擎。它遵循 Entity-Component-System 范式。 |![star > 1000][Silver]   
| [g3n](https://github.com/g3n/engine)  | 732 |   3D游戏引擎。 |![star > 100][Bronze]   
| [GarageEngine](https://github.com/vova616/GarageEngine)  | 308 |  用 OpenGL 编写的 2D 游戏引擎。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [glop](https://github.com/runningwild/glop)  | 77 |  Glop (Game Library Of Power) 是一个相当简单的跨平台游戏库。 |![最近一年没有更新][Yellow]
| [go-astar](https://github.com/beefsack/go-astar)  | 324 |  实现了A\*路径查找算法。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-collada](https://github.com/GlenKelley/go-collada)  | 12 |  处理Collada文件。 |![最近一年没有更新][Yellow]
| [go-sdl2](https://github.com/veandco/go-sdl2)  | 1141 |  实现了[Simple DirectMedia Layer](https://www.libsdl.org/)。 |![star > 1000][Silver]   
| [go3d](https://github.com/ungerik/go3d)  | 164 |  以性能为主的2D/3D数学相关包。 |![star > 100][Bronze]   
| [gonet](https://github.com/xtaci/gonet)  | 1047 |  实现了游戏服务器骨架。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [goworld](https://github.com/xiaonanln/goworld)  | 1151 |  可伸缩的游戏服务器引擎，具有 space-entity 框架和 hot-swapping 功能。 |![star > 1000][Silver]   
| [Leaf](https://github.com/name5566/leaf)  | 3025 |  轻量级游戏服务器框架。 |![star > 1000][Silver]   
| [nano](https://github.com/lonng/nano)  | 968 |  轻量级、方便、高性能的基于golang的游戏服务器框架。 |![star > 100][Bronze]   
| [Oak](https://github.com/oakmound/oak)  | 622 |  纯 Go 实现的游戏引擎。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [Pitaya](https://github.com/topfreegames/pitaya)  | 293 |  可伸缩的游戏服务器框架，支持集群和客户端库的iOS, Android, Unity。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [Pixel](https://github.com/faiface/pixel)  | 2410 |  手工制作的 2D 游戏库。 |![star > 1000][Silver]   
| [raylib-go](https://github.com/gen2brain/raylib-go)  | 377 |  实现了 [raylib](http://www.raylib.com/)，一个简单易用的库，用于学习视频游戏编程。 |![star > 100][Bronze]   
| [termloop](https://github.com/JoelOtter/termloop)  | 1020 |  基于终端的 Go 游戏引擎，建立在 Termbox 之上。 |![star > 1000][Silver]   

## 代码生成与泛型

*增强语言的工具，例如通过代码生成支持泛型。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [efaceconv](https://github.com/t0pep0/efaceconv)  | 43 |  代码生成工具，可以不通过内存分配就可以高效的将interface{}转换为不可变类型，。 |![最近一年没有更新][Yellow]
| [gen](https://github.com/clipperhouse/gen)  | 1028 |  用于生成泛型等类似方法的功能代码生成工具。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [generis](https://github.com/senselogic/GENERIS)  | 18 |  提供泛型、free-form 宏、条件编译和HTML模板的代码生成工具。 |
| [go-enum](https://github.com/abice/go-enum)  | 80 |  从代码注释中生成枚举。 |
| [go-linq](https://github.com/ahmetalpbalkan/go-linq)  | 1781 |  提供类似 .NET LINQ 的查询方法。 |![star > 1000][Silver]   
| [goderive](https://github.com/awalterschulze/goderive)  | 731 |  从输入类型来派生函数。 |![star > 100][Bronze]   
| [gotype](https://github.com/wzshiming/gotype)  | 20 |  Golang 源码解析，用法类似reflect(反射)。 |![最近一个周有更新][Green]
| [GoWrap](https://github.com/hexdigest/gowrap)  | 260 |  使用简单模板为 Go 接口生成装饰器。 |![star > 100][Bronze]   
| [interfaces](https://github.com/rjeczalik/interfaces)  | 185 |  用于生成接口定义的命令行工具。 |![star > 100][Bronze]   
| [jennifer](https://github.com/dave/jennifer)  | 1260 |  不使用模板生成任意 Go 代码。 |![star > 1000][Silver]   
| [pkgreflect](https://github.com/ungerik/pkgreflect)  | 85 |  用于包作用域反射的 Go 预处理器。 |![最近一年没有更新][Yellow]

## 地理

*地理工具和服务器*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [geocache](https://github.com/melihmucuk/geocache)  | 109 |  基于内存缓存的的地理位置的应用程序。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [geoserver](https://github.com/hishamkaram/geoserver)  | 25 |  基于geoserver REST API的 geoserver 实例。 |
| [gismanager](https://github.com/hishamkaram/gismanager)  | 19 |  将你的 GIS 数据(矢量数据)发布到 PostGIS 和 Geoserver。 |
| [osm](https://github.com/paulmach/osm)  | 64 |  用于读取、写入和处理 OpenStreetMap 数据和 APIs。 |
| [pbf](https://github.com/maguro/pbf)  | 15 |  基于Golang 的 OpenStreetMap PBF 编码器/解码器。 |
| [S2 geometry](https://github.com/golang/geo)  | 877 |  S2 geometry 库。 |![star > 100][Bronze]   
| [Tile38](https://github.com/tidwall/tile38)  | 6289 |  具有空间索引和实时地理定位功能的地理定位数据库。 |![star > 5000][Gold]   

## Go 编译器

*可将 Go 转换为其他语言的编译工具。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [c4go](https://github.com/Konstantin8105/c4go)  | 142 |  将 C 代码转换为 Go 代码。 |![star > 100][Bronze]   
| [f4go](https://github.com/Konstantin8105/f4go)  | 11 |  将 FORTRAN 77 转换为 Go代码。 |
| [gopherjs](https://github.com/gopherjs/gopherjs)  | 8484 |  将 Go 编译成 JavaScript。 |![star > 5000][Gold]   
| [llgo](https://github.com/go-llvm/llgo)  | 989 |  基于 llvm 的编译器。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [tardisgo](https://github.com/tardisgo/tardisgo)  | 393 |  Golang 转换为 Haxe，再转换为 CPP/CSharp/Java/JavaScript 的编译器. |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## Goroutines

*管理和处理 Goroutines 的工具。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [ants](https://github.com/panjf2000/ants)  | 1796 |  一个高性能的协程池。 |![star > 1000][Silver]   
| [artifex](https://github.com/borderstech/artifex)  | 11 |  简单的内存作业队列。 |
| [async](https://github.com/studiosol/async)  | 18 |  一种异步执行函数的安全方法，在出现 panic 时恢复它们。 |
| [breaker](https://github.com/kamilsk/breaker)  | 27 |  灵活的机制，可以使执行流可中断。 |
| [cyclicbarrier](https://github.com/marusama/cyclicbarrier)  | 27 |  基于 Go 的 CyclicBarrier 实现。 |
| [go-floc](https://github.com/workanator/go-floc)  | 167 |  轻松编排 goroutines。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-flow](https://github.com/kamildrazkiewicz/go-flow)  | 103 |  控制 goroutines 的执行顺序。 |![star > 100][Bronze]   
| [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools)  | 5 |  轻量级的协程池库，可以通过简单的API来管理。 |
| [go-trylock](https://github.com/subchen/go-trylock)  | 4 |  支持 read-write 锁。 |![最近一年没有更新][Yellow]
| [gollback](https://github.com/vardius/gollback)  | 26 |  异步简单的函数实用程序，用于管理闭包和回调的执行。 |
| [GoSlaves](https://github.com/themester/GoSlaves)  | 74 |  简单异步的协程池。 |
| [goworker](https://github.com/benmanns/goworker)  | 2229 |  基于 go 的后台 worker。 |![star > 1000][Silver]   
| [gpool](https://github.com/Sherifabdlnaby/gpool)  | 57 |  manages a resizeable pool of context-aware goroutines to bound concurrency |
| [grpool](https://github.com/ivpusic/grpool)  | 490 |  轻量级协程池。 |![star > 100][Bronze]   
| [Hunch](https://github.com/AaronJan/Hunch)  | 9 |  Hunch 提供了诸如 All、First、Retry、Waterfall 等功能，这使得异步流控制更加直观。 |
| [oversight](https://cirello.io/oversight)  | - |  完整的实现了Erlang supervision trees。 |
| [parallel-fn](https://github.com/rafaeljesus/parallel-fn)  | 24 |  并行运行函数。 |![最近一年没有更新][Yellow]
| [pool](https://github.com/go-playground/pool)  | 472 |  有限消费者协程或无限协程池，可用于更加简单的处理和取消协程 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [queue](https://github.com/AnikHasibul/queue)  | 1 |  提供类似队列组可访问性 sync.WaitGroup 的功能。帮助你节流和限制协程、等待所有协程结束以及更多功能。 |
| [routine](https://github.com/x-mod/routine)  | 2 |  go routine control with context, support: Main, Go, Pool and some useful Executors. |
| [semaphore](https://github.com/kamilsk/semaphore)  | 74 |  信号量模式实现，可根据通道和上下文进行具备超时功能的锁定/解锁操作。 |
| [semaphore](https://github.com/marusama/semaphore)  | 70 |  基于 CAS 的可快速调整的信号量实现(比基于通道的信号量实现更快)。 |
| [stl](https://github.com/ssgreg/stl)  | 7 |  基于软件事务内存(STM)并发控制机制的软件事务锁。 |
| [threadpool](https://github.com/shettyh/threadpool)  | 17 |  Golang 的 threadpool 实现。 |
| [tunny](https://github.com/Jeffail/tunny)  | 1320 |  golang 的协程池。 |![star > 1000][Silver]   
| [worker-pool](https://github.com/vardius/worker-pool)  | 43 |  一个简单的 Go 异步工作池。 |
| [workerpool](https://github.com/gammazero/workerpool)  | 127 |  限制任务执行并发数，而不是队列中的任务数量的协程池，。 |![star > 100][Bronze]   

## GUI

*用于构建GUI应用程序的库。*

*工具包*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [app](https://github.com/murlokswarm/app)  | 2935 |  用于创建包含了 GO, HTML 和 CSS 的应用程序。支持 MacOS, Windows 正在开发中。 |![star > 1000][Silver]   
| [fyne](https://github.com/fyne-io/fyne)  | 6123 |  为 Go 而设计的跨平台的本地GUIs，使用EFL呈现。支持 : Linux, macOS, Windows。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [go-astilectron](https://github.com/asticode/go-astilectron)  | 2622 |  使用 GO 和 HTML/JS/CSS (电子驱动)进行构建跨平台 GUI 应用程序。 |![star > 1000][Silver]   
| [go-gtk](http://mattn.github.io/go-gtk/)  | - |  实现了 GTK 的 Go接口。 |
| [go-sciter](https://github.com/sciter-sdk/go-sciter)  | 1433 |  实现了 Sciter 的 Go 接口 : 用于现代桌面 UI 开发的可嵌入HTML/CSS/脚本引擎。可跨平台。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gotk3](https://github.com/gotk3/gotk3)  | 754 |  实现了 GTK3 的 Go接口。 |![star > 100][Bronze]   
| [gowd](https://github.com/dtylman/gowd)  | 207 |  跨平台、快速、简单的桌面UI开发，采用了GO, HTML, CSS和NW.js实现。 |![star > 100][Bronze]   
| [qt](https://github.com/therecipe/qt)  | 5917 |  实现了 Qt 的 Go接口(支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi)。 |![star > 5000][Gold]   
| [ui](https://github.com/andlabs/ui)  | 6868 |  跨平台的 Platform-native GUI 库。 |![star > 5000][Gold]   
| [Wails](https://wails.app)  | - |  Mac, Windows, Linux桌面应用程序，主要基于含有内置的OS HTML渲染器的HTML UI。 |
| [walk](https://github.com/lxn/walk)  | 3658 |  Windows应用程序库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [webview](https://github.com/zserge/webview)  | 4570 |  跨平台webview窗口，具有简单的双向JavaScript绑定(Windows / macOS / Linux)。 |![star > 1000][Silver]   

*交互*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [go-appindicator](https://github.com/dawidd6/go-appindicator)  | 1 |  实现了 libappindicator3 C库 的 Go接口。 |
| [gosx-notifier](https://github.com/deckarep/gosx-notifier)  | 492 |  OSX 桌面通知库。 |![star > 100][Bronze]   
| [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker)  | 1 |  用于通知计算机上的任何(可插入的)活动的 OSX 库。 |
| [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier)  | - |  OSX 睡眠/唤醒通知。 |
| [robotgo](https://github.com/go-vgo/robotgo)  | 4384 |  实现跨平台的GUI系统自动化。包含了控制鼠标、键盘等功能。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [systray](https://github.com/getlantern/systray)  | 769 |  跨平台 Go 库，可在通知区放置图标和菜单。 |![star > 100][Bronze]   
| [trayhost](https://github.com/shurcooL/trayhost)  | 158 |  跨平台 Go 库，可用于在主机操作系统的任务栏中放置图标。 |![star > 100][Bronze]   


## 硬件

*硬件交互相关的库、工具和教程。*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## 图片

*图像处理相关的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [bild](https://github.com/anthonynsimon/bild)  | 2025 |  纯Go语言实现的图像处理算法合集。 |![star > 1000][Silver]   
| [bimg](https://github.com/h2non/bimg)  | 780 |  使用libvips实现的快速高效的图像处理包。 |![star > 100][Bronze]   
| [cameron](https://github.com/aofei/cameron)  | 31 |  一个Go语言的头像生成器。 |
| [darkroom](https://github.com/gojek/darkroom)  | 21 |  An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. |![最近一个周有更新][Green]
| [geopattern](https://github.com/pravj/geopattern)  | 1008 |  由字符串创建漂亮图案的图片生成器。 |![star > 1000][Silver]   
| [gg](https://github.com/fogleman/gg)  | 1893 |  纯Go语言实现的2D渲染。 |![star > 1000][Silver]   
| [gift](https://github.com/disintegration/gift)  | 1207 |  图像处理包。 |![star > 1000][Silver]   
| [gltf](https://github.com/qmuntal/gltf)  | 36 |  一个高效、健壮的glTF 2.0文件读取、写入和验证器。 |
| [go-cairo](https://github.com/ungerik/go-cairo)  | 85 |   cairo图形库的Go binding。 |
| [go-gd](https://github.com/bolknote/go-gd)  | 49 |   GD库的Go binding。 |![最近一年没有更新][Yellow]
| [go-nude](https://github.com/koyachi/go-nude)  | 286 |  Go语言实现的裸照检测工具。 |![star > 100][Bronze]   
| [go-opencv](https://github.com/lazywei/go-opencv)  | 1085 |  OpenCV库的Go bindings。 |![star > 1000][Silver]   
| [go-webcolors](https://github.com/jyotiska/go-webcolors)  | 24 |  Python下webcolors库的Go语言调用。 |![最近一年没有更新][Yellow]
| [gocv](https://github.com/hybridgroup/gocv)  | 2399 |  使用OpenCV 3.3+实现的计算机视觉(ComputerVision)的Go语言包。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [goimagehash](https://github.com/corona10/goimagehash)  | 209 |   图像哈希处理的Go语言包。 |![star > 100][Bronze]   
| [goimghdr](https://github.com/corona10/goimghdr)  | 26 |  Go语言实现的imghdr模块用于确定文件的图像类型。 |
| [govatar](https://github.com/o1egl/govatar)  | 309 |  生成有趣头像的库和CMD工具。 |![star > 100][Bronze]   
| [image2ascii](https://github.com/qeesung/image2ascii)  | 285 |  将图像转换为ASCII码。 |![star > 100][Bronze]   
| [imagick](https://github.com/gographics/imagick)  | 960 |   ImageMagick下MagickWand的C API的Go binding。 |![star > 100][Bronze]   
| [imaginary](https://github.com/h2non/imaginary)  | 2568 |  用于图像大小调整的快速、简单的HTTP微服务。 |![star > 1000][Silver]   
| [imaging](https://github.com/disintegration/imaging)  | 2484 |  简单的Go图像处理包。 |![star > 1000][Silver]   
| [img](https://github.com/hawx/img)  | 129 |  图像处理工具的集合。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [ln](https://github.com/fogleman/ln)  | 2455 |  Go实现的3D线艺术（3D Line Art）渲染。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [mergi](https://github.com/noelyahan/mergi)  | 70 |  用于图像处理(合并、裁剪、调整大小、水印、动画)的工具和Go库。 |
| [mort](https://github.com/aldor007/mort)  | 364 |  Go语言实现的图像存储和处理服务器。 |![star > 100][Bronze]   
| [mpo](https://github.com/donatj/mpo)  | 6 |  MPO三维照片的解码和转换工具。 |
| [picfit](https://github.com/thoas/picfit)  | 1054 |  Go实现的图像调整服务器。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [pt](https://github.com/fogleman/pt)  | 1762 |  Go实现的路径跟踪（path tracing）引擎。 |![star > 1000][Silver]   
| [resize](https://github.com/nfnt/resize)  | 2115 |  Go实现的使用常用的插值法（interpolation methods）调整图像大小的库。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [rez](https://github.com/bamiaux/rez)  | 189 |  纯Go语言和SIMD实现的图像大小调整。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [smartcrop](https://github.com/muesli/smartcrop)  | 1246 |  为任意图片寻找合适的位置进行图片裁剪。 |![star > 1000][Silver]   
| [steganography](https://github.com/auyer/steganography)  | 25 |  纯Go实现的LSB隐写（LSB steganography）的库。 |
| [stegify](https://github.com/DimitarPetrov/stegify)  | 485 |   Go实现的LSB隐写（LSB steganography），能够隐藏任何文件到一个图像中。 |![star > 100][Bronze]   
| [svgo](https://github.com/ajstarks/svgo)  | 1322 |   Go实现的SVG生成库。 |![star > 1000][Silver]   
| [tga](https://github.com/ftrvxmtrx/tga)  | 23 |  tga包是一个TARGA图像的解码、编码器。 |![最近一年没有更新][Yellow]

## 物联网

*物联网设备编程库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [connectordb](https://github.com/connectordb/connectordb)  | 167 |  自我量化和物联网的开源平台。 |![star > 100][Bronze]   
| [devices](https://github.com/goiot/devices)  | 225 |  一套用于物联网设备的库，实验性地用于x/exp/io。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [eywa](https://github.com/xcodersun/eywa)  | 36 |  Eywa是一个用于跟踪连接的设备连接管理器。 |![最近一年没有更新][Yellow]
| [flogo](https://github.com/tibcosoftware/flogo)  | 1107 |  Flogo是一个面向物联网边缘应用和集成的开源框架。 |![star > 1000][Silver]   
| [gatt](https://github.com/paypal/gatt)  | 809 |  Gatt是一个用于构建低能耗蓝牙外围设备的Go语言包。 |![star > 100][Bronze]   
| [gobot](https://github.com/hybridgroup/gobot/)  | - |  Gobot是一个用于机器人、物理计算和物联网的框架。 |
| [huego](https://github.com/amimof/huego)  | 109 |  一个包含广泛的Philips Hue客户端的Go语言库。 |![star > 100][Bronze]   
| [iot](https://github.com/vaelen/iot/)  | - |  IoT是一个实现谷歌物联网核心设备的简单框架。 |
| [mainflux](https://github.com/Mainflux/mainflux)  | 573 |  工业物联网消息和设备管理服务器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [periph](https://periph.io/)  | - |  外围设备I/O与低级板(low-level board)设备接口。 |
| [sensorbee](https://github.com/sensorbee/sensorbee)  | 178 |  轻量级物联网流处理引擎。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 作业调度器

*用于作业调度的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [clockwerk](http://github.com/onatm/clockwerk)  | - |  使用简单、流畅的语法调度作业的Go语言库。 |
| [clockwork](https://github.com/whiteShtef/clockwork)  | 75 |  Go实现的简单直观的作业调度库。 |
| [go-cron](https://github.com/rk/go-cron)  | 177 |  一个Go实现的简单的定时任务库。可以在不同的时间间隔（每秒一次到在每年在特定的日期执行）执行闭包或函数。主要用于web应用和长时间运行的守护进程。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gron](https://github.com/roylee0704/gron)  | 624 |  使用简单的Go API定义基于时间的任务。 之后Gron的调度程序将运行它们。 |![star > 100][Bronze]   
| [JobRunner](https://github.com/bamzi/jobrunner)  | 566 |  智能和功能丰富的cron作业调度程序（包含任务队列和实时监控）。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [jobs](https://github.com/albrow/jobs)  | 450 |  持久和灵活的后台作业库。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [leprechaun](https://github.com/kilgaloon/leprechaun)  | 36 |  支持webhook、crons和经典调度的作业调度程序。 |
| [scheduler](https://github.com/carlescere/scheduler)  | 291 |  Cronjobs让调度变得很简单。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## JSON

*用于JSON处理的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [ajson](https://github.com/spyzhov/ajson)  | 12 |  为Go语言开发的包含JSONPath支持的抽象JSON。 |
| [gjo](https://github.com/skanehira/gjo)  | 57 |  用于创建JSON对象的小工具。 |
| [GJSON](https://github.com/tidwall/gjson)  | 4797 |  使用一行代码获取JSON的值。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [go-respond](https://github.com/nicklaw5/go-respond)  | 21 |  用于处理常见的HTTP JSON响应的Go语言库。 |
| [gojq](https://github.com/elgs/gojq)  | 140 |  Go语言实现的JSON请求。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gojson](https://github.com/ChimeraCoder/gojson)  | 2021 |  从JSON自动生成Go的结构（struct）定义。 |![star > 1000][Silver]   
| [JayDiff](https://github.com/yazgazan/jaydiff)  | 38 |  用Go编写的JSON比对工具。 |
| [JSON-to-Go](https://mholt.github.io/json-to-go/)  | - |  将JSON转换为Go的结构（struct）。 |
| [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors)  | 5 |  基于JSON API错误引用的Go bindings。 |![最近一年没有更新][Yellow]
| [jsonf](https://github.com/miolini/jsonf)  | 54 |  用于高亮展示和查询JSON的控制台工具。 |![最近一年没有更新][Yellow]
| [jsongo](https://github.com/ricardolonga/jsongo)  | 92 |  使用Fluent API来更容易地创建Json对象。 |![最近一年没有更新][Yellow]
| [jsonhal](https://github.com/RichardKnop/jsonhal)  | 9 |  让自定义结构（struct）转化为JSON兼容的HAL（Hypertext Application Language）返回数据的简单Go包。 |
| [kazaam](https://github.com/Qntfy/kazaam)  | 128 |  用于任意JSON文档转换的API。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [mp](https://github.com/sanbornm/mp)  | 33 |  简单的cli电子邮件解析器。它目前接受stdin并输出JSON。 |![最近一年没有更新][Yellow]

## 日志记录

*用于生成和处理日志文件的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [distillog](https://github.com/amoghe/distillog)  | 18 |  distilled日志记录(可以将其视为stdlib +日志)。 |
| [glg](https://github.com/kpango/glg)  | 52 |  glg是一个简单而快速的Go日志库。 |![最近一个周有更新][Green]
| [glo](https://github.com/lajosbencz/glo)  | 8 |  参照PHP的Monolog实现的具有相同日志等级的Go日志库。 |
| [glog](https://github.com/golang/glog)  | 2286 |  为Go提供了多等级日志记录。 |![star > 1000][Silver]   
| [go-cronowriter](https://github.com/utahta/go-cronowriter)  | 19 |  基于当前日期和时间的自动日志文件写入工具，类似cronolog。 |
| [go-log](https://github.com/subchen/go-log)  | 10 |  Go实现的简单且可配置的日志工具，并带有多等级、日志格式化和日志写入工具。 |![最近一年没有更新][Yellow]
| [go-log](https://github.com/siddontang/go-log)  | 24 |  支持多等级和多处理程序的日志库。 |
| [go-log](https://github.com/ian-kent/go-log)  | 34 |  Log4j的Go语言。 |![最近一年没有更新][Yellow]
| [go-logger](https://github.com/apsdehal/go-logger)  | 233 |  简单的日志程序的 Go 程序，与级别处理程序。 |![star > 100][Bronze]   
| [gologger](https://github.com/sadlil/gologger)  | 39 |  为Go提供方便简单的日志操作; 在彩色控制台，简单控制台，文件或Elasticsearch上。 |![最近一年没有更新][Yellow]
| [gomol](https://github.com/aphistic/gomol)  | 15 |  为Go实现可多方式输出、结构化日志, 并可扩展日志输出方式。 |
| [gone/log](https://github.com/One-com/gone/tree/master/log)  | - |  快速、可扩展、功能齐全、std-lib源兼容的日志库。 |
| [journald](https://github.com/ssgreg/journald)  | 18 |   Go实现systemd Journal的原生API用于日志记录。 |
| [log](https://github.com/aerogo/log)  | 4 |  一个O(1)日志系统，允许您将一个日志连接到多个日志写入(例如stdout、文件和TCP连接)。 |
| [log](https://github.com/apex/log)  | 727 |  Go的结构化日志包。 |![star > 100][Bronze]   
| [log](https://github.com/go-playground/log)  | 266 |  Go的简单、可配置和可伸缩的结构化日志。 |![star > 100][Bronze]   
| [log](https://github.com/teris-io/log)  | 22 |  Go的结构化日志接口，清晰地将日志facade与其实现(implementation)分离开来。 |![最近一年没有更新][Yellow]
| [log-voyage](https://github.com/firstrow/logvoyage)  | 82 |  用Go编写的功能齐全的日志写入saas。 |![最近一年没有更新][Yellow]
| [log15](https://github.com/inconshreveable/log15)  | 879 |  简单、强大的日志操作。 |![star > 100][Bronze]   
| [logdump](https://github.com/ewwwwwqm/logdump)  | 8 |  用于多等级级日志记录的包。 |![最近一年没有更新][Yellow]
| [logex](https://github.com/chzyer/logex)  | 32 |  由标准日志库封装的Go日志库，支持跟踪和多等级。 |![最近一年没有更新][Yellow]
| [logger](https://github.com/azer/logger)  | 135 |  Go的精简日志库。 |![star > 100][Bronze]   
| [logmatic](https://github.com/borderstech/logmatic)  | 6 |  Go的彩色日志记录器，带有可配置的日志级别。 |
| [logo](https://github.com/mbndr/logo)  | 4 |  Go的日志工具，可配置的日志写入器。 |![最近一年没有更新][Yellow]
| [logrus](https://github.com/Sirupsen/logrus)  | 11693 |  Go的结构化日志操作 。 |![star > 5000][Gold]   
| [logrusly](https://github.com/sebest/logrusly)  | 26 |  [logrus](https://github.com/sirupsen/logrus)的插件，将错误信息发送到[Loggly](https://www.loggly.com/)。 |![最近一年没有更新][Yellow]
| [logutils](https://github.com/hashicorp/logutils)  | 247 |  Go的用于更好地进行日志操作的实用程序，继承了标准日志库。 |![star > 100][Bronze]   
| [logxi](https://github.com/mgutz/logxi)  | 334 |  12-factor app的日志程序，快速且让人高兴地使用。 |![star > 100][Bronze]   
| [lumberjack](https://github.com/natefinch/lumberjack)  | 1415 |  简单的滚动日志，io.WriteCloser的实现。 |![star > 1000][Silver]   
| [mlog](https://github.com/jbrodriguez/mlog)  | 18 |  简单的go日志模块，有5个级别，可选循环(rotation)日志文件记录功能和stdout/stderr输出。 |
| [onelog](https://github.com/francoispqt/onelog)  | 327 |  Onelog是一个非常简单但非常高效的JSON日志程序。它是所有场景中速度最快的JSON日志程序。而且，它是配置要求最低的日志记录器之一。 |![star > 100][Bronze]   
| [ozzo-log](https://github.com/go-ozzo/ozzo-log)  | 109 |  支持日志多等级、分类和过滤的高性能日志记录。可以发送过滤后的日志消息到各种目标(如控制台，网络，邮件)。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [rollingwriter](https://github.com/arthurkiller/rollingWriter)  | 94 |  RollingWriter是一个自动循环的io.Writer的实现,带有多种策略以提供日志文件循环(rotation)。 |
| [seelog](https://github.com/cihub/seelog)  | 1343 |  具有灵活调度、过滤和格式化的日志功能。 |![star > 1000][Silver]   
| [spew](https://github.com/davecgh/go-spew)  | 3253 |  为Go数据结构实现一个漂亮的printer用于帮助调试。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [stdlog](https://github.com/alexcesaro/log)  | 43 |  Stdlog是一个面向对象的库，提供了多等级日志记录。它对cron任务非常有用。 |![最近一年没有更新][Yellow]
| [tail](https://github.com/hpcloud/tail)  | 1514 |  努力模拟实现BSD的tail的特性的Go包。 |![star > 1000][Silver]   
| [xlog](https://github.com/xfxdev/xlog)  | 7 |  插件架构和灵活的日志系统，带有多级别、多日志目标和自定义日志格式。 |
| [xlog](https://github.com/rs/xlog)  | 129 |  针对'net/context`实现的结构化的记录器，用于HTTP处理程序。 |![star > 100][Bronze]   
| [zap](https://github.com/uber-go/zap)  | 7288 |  快速、结构化、多等级的日志记录。 |![star > 5000][Gold]   
| [zerolog](https://github.com/rs/zerolog)  | 2128 |  Zero-allocation JSON日志记录。 |![star > 1000][Silver]   

## 机器学习

*机器学习库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [bayesian](https://github.com/jbrukh/bayesian)  | 626 |  Go的朴素贝叶斯分类。 |![star > 100][Bronze]   
| [CloudForest](https://github.com/ryanbressler/CloudForest)  | 643 |  快速、灵活、多线程集成的决策树，用于机器学习。 |![star > 100][Bronze]   
| [eaopt](https://github.com/MaxHalford/eaopt)  | 616 |  一个进化优化（evolutionary optimization）库。 |![star > 100][Bronze]   
| [evoli](https://github.com/khezen/evoli)  | 8 |  遗传算法（Genetic Algorithm）和粒子群优化（Particle Swarm Optimization）库。 |
| [fonet](https://github.com/Fontinalis/fonet)  | 31 |  一个用Go编写的深度神经网络库。 |![最近一年没有更新][Yellow]
| [go-cluster](https://github.com/e-XpertSolutions/go-cluster)  | 21 |  Go实现的k-modes和k-prototypes聚类算法。 |
| [go-deep](https://github.com/patrikeh/go-deep)  | 214 |  一个功能丰富的神经网络库 。 |![star > 100][Bronze]   
| [go-fann](https://github.com/white-pony/go-fann)  | 99 |  快速人工神经网络(FANN)库的Go bindings。 |![最近一年没有更新][Yellow]
| [go-galib](https://github.com/thoj/go-galib)  | 171 |  用Go编写的遗传算法库。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-pr](https://github.com/daviddengcn/go-pr)  | 57 |  Go编写的模式识别包。 |![最近一年没有更新][Yellow]
| [gobrain](https://github.com/goml/gobrain)  | 373 |  用 Go 编写的神经网络库。 |![star > 100][Bronze]   
| [godist](https://github.com/e-dard/godist)  | 24 |  各种概率分布，以及相关的method。 |![最近一年没有更新][Yellow]
| [goga](https://github.com/tomcraven/goga)  | 78 |  Go的遗传算法库。 |![最近一年没有更新][Yellow]
| [GoLearn](https://github.com/sjwhitworth/golearn)  | 6624 |  通用机器学习库。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [golinear](https://github.com/danieldk/golinear)  | 39 |   Go实现的liblinear bindings。 |
| [GoMind](https://github.com/surenderthakran/gomind)  | 6 |  一个简单的神经网络库。 |
| [goml](https://github.com/cdipaolo/goml)  | 1006 |  在线机器学习。 |![star > 1000][Silver]   
| [goRecommend](https://github.com/timkaye11/goRecommend)  | 141 |  用Go编写的推荐算法库。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gorgonia](https://github.com/chewxy/gorgonia)  | 2662 |  基于图形（graph-based）的计算库，如Theano：它为构建各种机器学习和神经网络算法提供了基本框架。 |![star > 1000][Silver]   
| [gorse](https://github.com/zhenghaoz/gorse)  | 517 |  基于协同过滤（Collaborative Filtering ）的高性能推荐系统包。 |![star > 100][Bronze]   
| [goscore](https://github.com/asafschers/goscore)  | 34 |   为预言模型标记语言（PMML）实现的评分API。 |
| [gosseract](https://github.com/otiai10/gosseract)  | 855 |  使用c++的Tesseract库实现的OCR。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [libsvm](https://github.com/datastream/libsvm)  | 63 |  基于LIBSVM 3.14实现。 |![最近一年没有更新][Yellow]
| [mlgo](https://github.com/NullHypothesis/mlgo)  | 5 |  这个项目的用于在Go中提供最精简的机器学习算法。 |![最近一年没有更新][Yellow]
| [neat](https://github.com/jinyeom/neat)  | 55 |  即插即用的并行Go框架，用于增强拓扑的神经进化(NeuroEvolution of Augmenting Topologies)。 |![最近一年没有更新][Yellow]
| [neural-go](https://github.com/schuyler/neural-go)  | 61 |  多层感知器网络在Go中的实现，使用反向传播算法进行训练。 |![最近一年没有更新][Yellow]
| [ocrserver](https://github.com/otiai10/ocrserver)  | 218 |  一个简单的OCR API服务器，非常容易地使用Docker和Heroku部署。 |![star > 100][Bronze]   
| [onnx-go](https://github.com/owulveryck/onnx-go)  | 147 |  Go Interface， 用于开放式神经网络交换(Open Neural Network Exchange)。 |![star > 100][Bronze]   
| [probab](https://github.com/ThePaw/probab)  | 10 |  概率分布函数。贝叶斯推理。使用Go写的。 |![最近一年没有更新][Yellow]
| [regommend](https://github.com/muesli/regommend)  | 245 |  推荐和协同过滤引擎。 |![star > 100][Bronze]   
| [shield](https://github.com/eaigner/shield)  | 124 |  贝叶斯文本分类器，具有灵活的tokenizers和存储后端。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [tfgo](https://github.com/galeone/tfgo)  | 1172 |  易于使用的Tensorflow bindings:简化了官方Tensorflow Go bindings的使用。在Go中定义计算图形，在Python中加载和执行训练的模型。 |![star > 1000][Silver]   
| [Varis](https://github.com/Xamber/Varis)  | 24 |  Go实现的神经网络。 |

## 消息

*实现消息传递系统的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [APNs2](https://github.com/sideshow/apns2)  | 2032 |  HTTP / 2苹果消息推送provider——发送推送消息到iOS, tvOS, Safari和OSX应用。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [Beaver](https://github.com/Clivern/Beaver)  | 713 |  一个实时消息服务器，可用于在web和手机app端构建一个可伸缩的应用内通知，多人游戏，聊天应用。 |![star > 100][Bronze]   
| [Benthos](https://github.com/Jeffail/benthos)  | 1928 |  一系列协议之间的消息流桥接。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [Bus](https://github.com/mustafaturan/bus)  | 112 |  内部通信的最小消息总线实现。 |![star > 100][Bronze]   
| [Centrifugo](https://github.com/centrifugal/centrifugo)  | 3638 |  实时消息(Websockets或SockJS)服务器。 |![star > 1000][Silver]   
| [Commander](https://github.com/jeroenrinzema/commander)  | 21 |  高级事件驱动的消费者/生产者(consumer/producer)，支持各种“方言”，如Apache Kafka。 |![最近一个周有更新][Green]
| [dbus](https://github.com/godbus/dbus)  | 352 |  D-Bus的Go bindings。 |![star > 100][Bronze]   
| [drone-line](https://github.com/appleboy/drone-line)  | 60 |  使用二进制、docker或Drone CI发送[Line](https://at.line.me/en)通知。 |
| [emitter](https://github.com/olebedev/emitter)  | 308 |  使用Go的方式发出事件, 带有通配符、谓词、取消可能性和许多其他优点。 |![star > 100][Bronze]   
| [event](https://github.com/agoalofalife/event)  | 27 |  观察者模式的实现。 |![最近一年没有更新][Yellow]
| [EventBus](https://github.com/asaskevich/EventBus)  | 549 |  具有异步兼容性的轻量级事件总线。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [gaurun-client](https://github.com/osamingo/gaurun-client)  | 8 |  用Go编写的Gaurun客户端。 |
| [Glue](https://github.com/desertbit/glue)  | 314 |  健壮的Go和Javascript Socket库(替代Socket.io)。 |![star > 100][Bronze]   
| [go-notify](https://github.com/TheCreeper/go-notify)  | 47 |  原生的freedesktop通知规范实现。 |
| [go-nsq](https://github.com/nsqio/go-nsq)  | 1445 |  NSQ的官方Go包。 |![star > 1000][Silver]   
| [go-socket.io](https://github.com/googollee/go-socket.io)  | 2850 |  go的socket.io库，一个实时应用程序框架。 |![star > 1000][Silver]   
| [go-vitotrol](https://github.com/maxatome/go-vitotrol)  | 11 |  用于Viessmann Vitotrol web服务的客户端库。 |
| [Gollum](https://github.com/trivago/gollum)  | 763 |  一个n:m多路复用器(n:m multiplexer)，收集不同来源的消息并将其广播到一组目的地。 |![star > 100][Bronze]   
| [golongpoll](https://github.com/jcuga/golongpoll)  | 422 |  HTTP longpoll服务器库，使web发布-订阅变得简单。 |![star > 100][Bronze]   
| [goose](https://github.com/ian-kent/goose)  | 36 |  服务器在Go中发送事件。 |![最近一年没有更新][Yellow]
| [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster)  | 1825 |  gopush-cluster是一个gopush服务器集群。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [gorush](https://github.com/appleboy/gorush)  | 3665 |  使用[APNs2](https://github.com/sideshow/apns2)和谷歌[GCM](https://github.com/google/go-gcm)推送通知服务器。 |![star > 1000][Silver]   
| [guble](https://github.com/smancke/guble)  | 137 |  使用推送通知服务(谷歌Firebase云消息、苹果推送通知服务、SMS)的消息服务器, 支持websockets,REST API，并具有分布式操作和消息持久性。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [hub](https://github.com/leandro-lugaresi/hub)  | 24 |  适用于Go应用程序的消息/事件中心，使用publish/subscribe模式，并支持别名(类似rabbitMQ exchanges)。 |![最近一年没有更新][Yellow]
| [jazz](https://github.com/socifi/jazz)  | 6 |  一个简单的RabbitMQ抽象层，用于队列管理和消息的发布和消费。 |
| [machinery](https://github.com/RichardKnop/machinery)  | 3329 |  基于分布式消息传递的异步任务/作业队列。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [mangos](https://github.com/go-mangos/mangos)  | 1531 |  Nanomsg(“可伸缩协议”)的纯go实现,具有传输互操作性。 |![star > 1000][Silver]   
| [melody](https://github.com/olahol/melody)  | 1533 |  处理websocket session的极简框架，包括广播和自动ping/pong处理。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [Mercure](https://github.com/dunglas/mercure)  | 1460 |  使用Mercure协议分派服务器发送(server-sent)更新的服务器和库(构建在服务器发送事件之上)。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [messagebus](https://github.com/vardius/message-bus)  | 63 |  messagebus是一个Go的简单异步消息总线，非常适合在执行事件sourcing、CQRS和DDD时用作事件总线。 |
| [NATS Go Client](https://github.com/nats-io/nats)  | 2355 |  轻量级和高性能的发布-订阅(publish-subscribe)和分布式队列消息传递系统——这是一个Go库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus)  | 50 |  一个围绕NSQ topic和channel的小工具。 |![最近一年没有更新][Yellow]
| [oplog](https://github.com/dailymotion/oplog)  | 94 |  用于REST api的通用oplog/replication系统。 |![最近一年没有更新][Yellow]
| [pubsub](https://github.com/tuxychandru/pubsub)  | 271 |  简单的pubsub的go包。 |![star > 100][Bronze]   
| [rabbus](https://github.com/rafaeljesus/rabbus)  | 61 |  amqp exchanges和队列上的一个小工具。 |
| [rabtap](https://github.com/jandelgado/rabtap)  | 71 |  RabbitMQ的瑞士军刀cli应用。 |![最近一个周有更新][Green]
| [RapidMQ](https://github.com/sybrexsys/RapidMQ)  | 54 |  RapidMQ是用于管理本地消息队列的轻量且可靠的库。 |![最近一年没有更新][Yellow]
| [rmqconn](https://github.com/sbabiv/rmqconn)  | - |  RabbitMQ重新连接。amqp.Connection和amqp.Dial之上的Wrapper。允许在强制调用Close()方法关闭连接之前重新连接。 |
| [sarama](https://github.com/Shopify/sarama)  | 4540 |   Apache Kafka的Go库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [Uniqush-Push](https://github.com/uniqush/uniqush-push)  | 1095 |  Redis支持的统一推送服务, 用于服务端向移动设备的消息通知。 |![star > 1000][Silver]   
| [zmq4](https://github.com/pebbe/zmq4)  | 772 |  ZeroMQ的Go interface第4版。也可用于[第3版](https://github.com/pebbe/zmq3)和[第2版](https://github.com/pebbe/zmq2)。 |![star > 100][Bronze]   

## 微软办公软件

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [unioffice](https://github.com/unidoc/unioffice)  | 1653 |  用于创建和处理Office Word (.docx)、Excel (.xlsx)和Powerpoint (.pptx)文档的纯go库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]

### Microsoft Excel

*用于操作Microsoft Excel的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [excelize](https://github.com/360EntSecGroup-Skylar/excelize)  | 4362 |  用于读写Microsoft Excel™(XLSX)文件的Go语言库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [go-excel](https://github.com/szyhf/go-excel)  | 46 |  一个简单轻便的阅读器，可以将类关系型数据库(relate-db-like)的excel作为表来读取。 |
| [goxlsxwriter](https://github.com/fterrag/goxlsxwriter)  | 12 |  libxlsxwriter的Go binding, 用于编写XLSX (Microsoft Excel)文件。 |
| [xlsx](https://github.com/tealeg/xlsx)  | 3321 |  用以简化在Go程序中读取使用最新版本Microsoft Excel的XML格式文件的库。 |![star > 1000][Silver]   
| [xlsx](https://github.com/plandem/xlsx)  | 60 |  在Go程序以快速和安全的方式读取/更新现有的Microsoft Excel文件。 |![最近一个周有更新][Green]

## 杂项

### 依赖注入

*用于处理依赖项注入的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [alice](https://github.com/magic003/alice)  | 34 |  Go的外挂的依赖注入容器。 |![最近一年没有更新][Yellow]
| [dig](https://github.com/uber-go/dig)  | 883 |  一个基于反射的Go依赖注入工具包。 |![star > 100][Bronze]   
| [fx](https://github.com/uber-go/fx)  | 650 |  基于依赖注入的Go应用程序框架(构建在dig之上)。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [gocontainer](https://github.com/vardius/gocontainer)  | 8 |  简单的依赖注入容器。 |
| [inject](https://github.com/defval/inject)  | 19 |  一个基于反射的依赖注入容器，具有简单的接口。 |
| [linker](https://github.com/logrange/linker)  | 4 |  A reflection based dependency injection and inversion of control library with components lifecycle support. |
| [wire](https://github.com/Fs02/wire)  | 19 |  适用于Go的严格运行时依赖注入(Strict Runtime Dependency Injection)。 |

### 项目布局

*用于组织项目的非正式模式集。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [go-sample](https://github.com/zitryss/go-sample)  | 20 |  带有实际代码的Go应用程序项目的示例布局。 |
| [golang-standards/project-layout](https://github.com/golang-standards/project-layout)  | 8718 |  Go生态系统中历史和新兴的项目布局模式集合。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [scaffold](https://github.com/catchplay/scaffold)  | 21 |  快速生成Go项目布局的脚手架。让您专注于已实现的业务逻辑。 |

### 字符串

*处理字符串的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [strutil](https://github.com/ozgio/strutil)  | 61 |  字符串工具。 |
| [xstrings](https://github.com/huandu/xstrings)  | 615 |  从其他语言移植的有用字符串函数的集合。 |![star > 100][Bronze]   

*这些库之所以放在这里，是因为其他类别似乎都不适合。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [anagent](https://github.com/mudler/anagent)  | 11 |  最小化，可插入的Golang evloop/计时器处理程序与依赖注入。 |
| [antch](https://github.com/antchfx/antch)  | 138 |  一个快速、强大和可扩展的web爬行和抓取框架。 |![star > 100][Bronze]   
| [archiver](https://github.com/mholt/archiver)  | 2468 |  用于生成和提取.zip和.tar.gz存档的库和命令。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [autoflags](https://github.com/artyom/autoflags)  | 24 |  Go package从struct字段自动定义命令行标志。 |
| [avgRating](https://github.com/kirillDanshin/avgRating)  | 9 |  根据Wilson评分方程计算平均分和评分。 |![最近一年没有更新][Yellow]
| [banner](https://github.com/dimiro1/banner)  | 229 |  在Go应用程序中添加漂亮的横幅。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [base64Captcha](https://github.com/mojocn/base64Captcha)  | 615 |  Base64captch支持数字，数字，字母，算术，音频和数字-字母验证码。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [battery](https://github.com/distatus/battery)  | 134 |  跨平台、标准化的电池信息库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [bitio](https://github.com/icza/bitio)  | 92 |  高度优化的位级读写器。 |![最近一年没有更新][Yellow]
| [browscap_go](https://github.com/digitalcrab/browscap_go)  | 29 |  用于[浏览器功能项目]的GoLang库(http://browscap.org/)。 |
| [captcha](https://github.com/steambap/captcha)  | 43 |  软件包captcha为captcha的生成提供了一个易于使用的、未绑定的API。 |
| [conv](https://github.com/cstockton/go-conv)  | 340 |  包conv提供了跨Go类型的快速和直观的转换。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [datacounter](https://github.com/miolini/datacounter)  | 27 |  读取器/写入器/http.ResponseWriter的计数器。 |![最近一年没有更新][Yellow]
| [ffmt](https://github.com/go-ffmt/ffmt)  | 126 |  美化数据显示为人类。 |![star > 100][Bronze]   
| [ghorg](https://github.com/gabrie30/ghorg)  | 23 |  将所有repos从GitHub org复制到一个目录中。 |
| [go-commons-pool](https://github.com/jolestar/go-commons-pool)  | 661 |  Golang的通用对象池。 |![star > 100][Bronze]   
| [go-openapi](https://github.com/go-openapi)  | - |  用于解析和利用开放api模式的包的集合。 |
| [go-resiliency](https://github.com/eapache/go-resiliency)  | 838 |   Go 的弹性模式。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-unarr](https://github.com/gen2brain/go-unarr)  | 67 |  用于RAR、TAR、ZIP和7z存档的解压缩库。 |
| [gofakeit](https://github.com/brianvoe/gofakeit)  | 406 |  用go编写的随机数据生成器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [gommit](https://github.com/antham/gommit)  | 65 |  分析git提交消息，确保它们遵循已定义的模式。 |
| [gopsutil](https://github.com/shirou/gopsutil)  | 3864 |  用于检索进程和系统利用率(CPU、内存、磁盘等)的跨平台库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gosh](https://github.com/osamingo/gosh)  | 16 |  提供Go统计处理程序，结构，测量方法。 |
| [gosms](https://github.com/haxpax/gosms)  | 1222 |  您自己的本地短信网关在Go，可以用来发送短信。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [gotoprom](https://github.com/cabify/gotoprom)  | 15 |  为Prometheus客户端提供类型安全的度量构建器包装库。 |
| [gountries](https://github.com/pariz/gountries)  | 208 |  公开国家和细分数据的包。 |![star > 100][Bronze]   
| [health](https://github.com/dimiro1/health)  | 358 |  易于使用，可扩展的健康检查库。 |![star > 100][Bronze]   
| [healthcheck](https://github.com/etherlabsio/healthcheck)  | 79 |  用于RESTful服务的自以为是的并发健康检查HTTP处理程序。 |
| [hostutils](https://github.com/Wing924/hostutils)  | 7 |  一个用于打包和解包FQDNs列表的golang库。 |
| [indigo](https://github.com/osamingo/indigo)  | 51 |  分布式唯一ID生成器使用Sonyflake，并由Base58编码。 |
| [lk](https://github.com/hyperboloide/lk)  | 112 |  一个简单的golang授权库。 |![star > 100][Bronze]   
| [llvm](https://github.com/llir/llvm)  | 406 |  用于在纯Go中与LLVM IR交互的库。 |![star > 100][Bronze]   
| [metrics](https://github.com/pascaldekloe/metrics)  | 4 |  用于度量仪器和普罗米修斯博览会的库。 |
| [morse](https://github.com/alwindoss/morse)  | 49 |  转换成莫尔斯电码和从莫尔斯电码转换成莫尔斯电码的程序库。 |
| [numa](https://github.com/lrita/numa)  | 2 |  NUMA是一个用go编写的实用程序库。它帮助我们编写一些NUMA-AWARED代码。 |
| [pdfgen](https://github.com/hyperboloide/pdfgen)  | 32 |  HTTP服务从Json请求生成PDF。 |![最近一年没有更新][Yellow]
| [persian](https://github.com/mavihq/persian)  | 33 |  一些实用的波斯语在 Go 。 |
| [sandid](https://github.com/aofei/sandid)  | 12 |  地球上的每一粒沙子都有自己的身份。 |
| [shellwords](https://github.com/Wing924/shellwords)  | 7 |  一个Golang库，根据UNIX Bourne shell的单词解析规则操纵字符串。 |![最近一年没有更新][Yellow]
| [shortid](https://github.com/teris-io/shortid)  | 446 |  分布式生成超短、唯一、非顺序、URL友好的id。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [stats](https://github.com/go-playground/stats)  | 121 |  显示器 Go MemStats +系统统计，如内存，交换和CPU，并通过UDP发送到任何地方，你想记录等… |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [turtle](https://github.com/hackebrot/turtle)  | 72 |  Emojis Go 。 |![最近一年没有更新][Yellow]
| [url-shortener](https://github.com/pantrif/url-shortener)  | 17 |  一个现代的、强大的、健壮的URL缩短器微服务，支持mysql。 |![最近一年没有更新][Yellow]
| [VarHandler](https://github.com/azr/generators/tree/master/varhandler)  | - |  生成样板http输入和输出处理。 |
| [xdg](https://github.com/rkoesters/xdg)  | 19 |  FreeDesktop.org (xdg)规范在Go中实现。 |
| [xkg](https://github.com/go-xkg/xkg)  | 39 |  X键盘打捞工具。 |![最近一年没有更新][Yellow]

## 自然语言处理

*用于处理人类语言的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [getlang](https://github.com/rylans/getlang)  | 72 |  快速自然语言检测包。 |
| [go-eco](https://github.com/ThePaw/go-eco)  | 4 |  相似、不相似和距离矩阵;多样性、公平性和不平等度量;物种丰富度估计;coenocline模型。 |![最近一年没有更新][Yellow]
| [go-i18n](https://github.com/nicksnyder/go-i18n/)  | - |  软件包和用于处理本地化文本的附带工具。 |
| [go-mystem](https://github.com/dveselov/mystem)  | 23 |  CGo绑定到Yandex。Mystem -俄罗斯形态学分析仪。 |![最近一年没有更新][Yellow]
| [go-nlp](https://github.com/nuance/go-nlp)  | 79 |  用于处理离散概率分布的实用程序和用于进行NLP工作的其他工具。 |![最近一年没有更新][Yellow]
| [go-pinyin](https://github.com/mozillazg/go-pinyin)  | 517 |  中文汉字到汉语拼音的转换。 |![star > 100][Bronze]   
| [go-stem](https://github.com/agonopol/go-stem)  | 51 |  波特词干算法的实现。 |![最近一年没有更新][Yellow]
| [go-unidecode](https://github.com/mozillazg/go-unidecode)  | 55 |  Unicode文本的ASCII音译。 |
| [go2vec](https://github.com/danieldk/go2vec)  | 30 |  用于word2vec嵌入式的阅读器和实用程序函数。 |
| [gojieba](https://github.com/yanyiwu/gojieba)  | 805 |  这是一个Go实现的[jieba](https://github.com/fxsjy/jieba)，这是一个中文分词算法。 |![star > 100][Bronze]   
| [golibstemmer](https://github.com/rjohnsondev/golibstemmer)  | 15 |   Go 绑定斯诺鲍libstemmer库，包括波特2。 |![最近一年没有更新][Yellow]
| [gotokenizer](https://github.com/xujiajun/gotokenizer)  | 6 |  一种基于字典和双字母格朗语言模型的记号赋予器。(现在只支持中文分割) |
| [gounidecode](https://github.com/fiam/gounidecode)  | 68 |  用于Go的Unicode音译器(也称为unidecode)。 |![最近一年没有更新][Yellow]
| [gse](https://github.com/go-ego/gse)  | 1059 |  高效的文本分割;支持英语、汉语、日语等。 |![star > 1000][Silver]   
| [icu](https://github.com/goodsign/icu)  | 19 |  Cgo绑定用于icu4c C库的检测和转换功能。保证与版本50.1兼容。 |![最近一年没有更新][Yellow]
| [kagome](https://github.com/ikawaha/kagome)  | 411 |  JP形态学分析仪编写的纯Go。 |![star > 100][Bronze]   
| [libtextcat](https://github.com/goodsign/libtextcat)  | 10 |  用于libtextcat C库的Cgo绑定。保证与版本2.2兼容。 |![最近一年没有更新][Yellow]
| [MMSEGO](https://github.com/awsong/MMSEGO)  | 59 |  这是一个 Go 实现的[MMSEG](http://technology.chtsai.org/mmseg/)，这是一个中文分词算法。 |![最近一年没有更新][Yellow]
| [nlp](https://github.com/Shixzie/nlp)  | 353 |  从字符串中提取值并用nlp填充结构。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [nlp](https://github.com/james-bowman/nlp)  | 214 |  支持LSA(潜在语义分析)的Go自然语言处理库。 |![star > 100][Bronze]   
| [paicehusk](https://github.com/rookii/paicehusk)  | 25 |  Golang实现了Paice/外壳阻塞算法。 |![最近一年没有更新][Yellow]
| [petrovich](https://github.com/striker2000/petrovich)  | 22 |  彼得罗维奇是一个图书馆，它把俄语名字的词形变化成特定的语法格。 |
| [porter](https://github.com/a2800276/porter)  | 8 |  这是Martin Porter在C语言中实现的Porter词干分析算法的一个相当简单的移植。 |![最近一年没有更新][Yellow]
| [porter2](https://github.com/zhenjl/porter2)  | 33 |  非常快的波特2史坦默。 |![最近一年没有更新][Yellow]
| [prose](https://github.com/jdkato/prose)  | 2033 |  用于支持标记化、词性标记、名称实体提取等文本处理的库。 |![star > 1000][Silver]   
| [RAKE.go](https://github.com/Obaied/RAKE.go)  | 45 |  快速自动关键字提取算法(RAKE)的Go端口。 |
| [segment](https://github.com/blevesearch/segment)  | 46 |  Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/) |![最近一年没有更新][Yellow]
| [sentences](https://github.com/neurosnap/sentences)  | 260 |  句子标记器:将文本转换为句子列表。 |![star > 100][Bronze]   
| [shamoji](https://github.com/osamingo/shamoji)  | 10 |  shamoji是用Go编写的word过滤包。 |
| [snowball](https://github.com/goodsign/snowball)  | 24 |  滚雪球柄端口(cgo包装)为 Go 。提供词干提取功能[Snowball native](http://snowball.tartarus.org/)。 |![最近一年没有更新][Yellow]
| [stemmer](https://github.com/dchest/stemmer)  | 47 |  用于Go编程语言的Stemmer包。包括英语和德语词根。 |![最近一年没有更新][Yellow]
| [textcat](https://github.com/pebbe/textcat)  | 60 |  Go package支持基于n-gram的文本分类，支持utf-8和原始文本。 |
| [whatlanggo](https://github.com/abadojack/whatlanggo)  | 350 |  Go的自然语言检测包。支持84种语言和24种脚本(书写系统，如拉丁语、西里尔语等)。 |![star > 100][Bronze]   
| [when](https://github.com/olebedev/when)  | 924 |  带有可插入规则的自然EN和RU语言日期/时间解析器。 |![star > 100][Bronze]   

## 网络

*用于处理网络各层的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [arp](https://github.com/mdlayher/arp)  | 192 |  包arp实现了arp协议，如RFC 826中所述。 |![star > 100][Bronze]   
| [buffstreams](https://github.com/stabbycutyou/buffstreams)  | 232 |  通过TCP传输协议缓冲区数据变得很容易。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [canopus](https://github.com/zubairhamed/canopus)  | 133 |  CoAP客户机/服务器实现(RFC 7252)。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [cidranger](https://github.com/yl2chen/cidranger)  | 384 |  快速IP到CIDR查找 Go 。 |![star > 100][Bronze]   
| [dhcp6](https://github.com/mdlayher/dhcp6)  | 62 |  包dhcp6实现了一个DHCPv6服务器，如RFC 3315所述。 |
| [dns](https://github.com/miekg/dns)  | 3756 |  使用DNS的库。 |![star > 1000][Silver]   
| [ether](https://github.com/songgao/ether)  | 62 |  用于发送和接收以太网帧的跨平台Go包。 |![最近一年没有更新][Yellow]
| [ethernet](https://github.com/mdlayher/ethernet)  | 183 |  包以太网实现了对IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的编组和解组。 |![star > 100][Bronze]   
| [fasthttp](https://github.com/valyala/fasthttp)  | 9162 |  软件包fasthttp是Go的一个快速HTTP实现，比net/http快10倍。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [fortio](https://github.com/fortio/fortio)  | 850 |  负载测试库和命令行工具，先进的echo服务器和web UI。允许指定一组每秒查询的负载，并记录延迟直方图和其他有用的统计数据，并将它们作图。Tcp、Http、gRPC。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [ftp](https://github.com/jlaffaye/ftp)  | 514 |  包ftp实现了[RFC 959](http://tools.ietf.org/html/rfc959)中描述的ftp客户机。 |![star > 100][Bronze]   
| [gmqtt](https://github.com/DrmagicE/gmqtt)  | 66 |  Gmqtt是一个灵活、高性能的MQTT代理库，它完全实现了MQTT协议V3.1.1。 |
| [gNxI](https://github.com/google/gnxi)  | 98 |  一组使用gNMI和gNOI协议的网络管理工具。 |
| [go-getter](https://github.com/hashicorp/go-getter)  | 717 |   Go 图书馆下载文件或目录从各种来源使用一个URL。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-stun](https://github.com/ccding/go-stun)  | 329 |  Go实现了STUN客户机(RFC 3489和RFC 5389)。 |![star > 100][Bronze]   
| [gobgp](https://github.com/osrg/gobgp)  | 1656 |  用 Go 编程语言实现的BGP。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [golibwireshark](https://github.com/sunwxg/golibwireshark)  | 14 |  golibwireshark包使用libwireshark库解码pcap文件并分析解剖数据。 |![最近一年没有更新][Yellow]
| [gopacket](https://github.com/google/gopacket)  | 2819 |  使用libpcap绑定访问包处理库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gopcap](https://github.com/akrennmair/gopcap)  | 352 |   Go 包装libpcap。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [goshark](https://github.com/sunwxg/goshark)  | 9 |  goshark包使用tshark来解码IP包，并创建数据结构来分析包。 |![最近一年没有更新][Yellow]
| [gosnmp](https://github.com/soniah/gosnmp)  | 427 |  用于执行SNMP操作的本机Go库。 |![star > 100][Bronze]   
| [gotcp](https://github.com/gansidui/gotcp)  | 411 |   Go 包快速编写tcp应用程序。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [grab](https://github.com/cavaliercoder/grab)  | 543 |   Go 软件包管理文件下载。 |![star > 100][Bronze]   
| [graval](https://github.com/koofr/graval)  | 24 |  实验FTP服务器框架。 |![最近一年没有更新][Yellow]
| [HTTPLab](https://github.com/gchaincl/httplab)  | 3393 |  HTTPLabs允许您检查HTTP请求并伪造响应。 |![star > 1000][Silver]   
| [iplib](https://github.com/c-robinson/iplib)  | 24 |  用于处理IP地址的库(net)。受python [ipaddress](https://docy-doc.org/3/library/ipaddress.html)和ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)的启发 |
| [jazigo](https://github.com/udhos/jazigo)  | 123 |  Jazigo是一个用Go编写的工具，用于检索多个网络设备的配置。 |![star > 100][Bronze]   
| [kcp-go](https://github.com/xtaci/kcp-go)  | 2224 |  快速可靠的ARQ协议。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [kcptun](https://github.com/xtaci/kcptun)  | 10604 |  非常简单和快速udp隧道基于KCP协议。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [lhttp](https://github.com/fanux/lhttp)  | 510 |  强大的websocket框架，使您的IM服务器更容易构建。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [linkio](https://github.com/ian-kent/linkio)  | 44 |  用于读写器接口的网络链路速度模拟。 |![最近一年没有更新][Yellow]
| [llb](https://github.com/kirillDanshin/llb)  | 8 |  这是一个非常简单但快速的代理服务器后端。可用于快速重定向到预定义域，具有零内存分配和快速响应。 |![最近一年没有更新][Yellow]
| [mdns](https://github.com/hashicorp/mdns)  | 544 |  Golang中的简单mDNS(多播DNS)客户机/服务器库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [mqttPaho](https://eclipse.org/paho/clients/golang/)  | - |  Paho Go客户机提供一个MQTT客户机库，用于通过TCP、TLS或WebSockets连接到MQTT代理。 |
| [NFF-Go](https://github.com/intel-go/nff-go)  | 646 |  快速开发云计算和裸机网络功能的框架(原YANFF)。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [packet](https://github.com/aerogo/packet)  | 26 |  通过TCP和UDP发送数据包。如果需要，它可以缓冲消息和热交换连接。 |
| [peerdiscovery](https://github.com/schollz/peerdiscovery)  | 358 |  使用UDP组播进行跨平台本地对等点发现的纯Go库。 |![star > 100][Bronze]   
| [portproxy](https://github.com/aybabtme/portproxy)  | 42 |  简单的TCP代理将CORS支持添加到不支持它的API中。 |![最近一年没有更新][Yellow]
| [publicip](https://github.com/polera/publicip)  | 18 |  包publicip返回面向公共的IPv4地址(internet出口)。 |![最近一年没有更新][Yellow]
| [quic-go](https://github.com/lucas-clemente/quic-go)  | 2851 |  在纯Go中实现了QUIC协议。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [raw](https://github.com/mdlayher/raw)  | 302 |  Package raw支持在设备驱动程序级别读取和写入网络接口的数据。 |![star > 100][Bronze]   
| [sftp](https://github.com/pkg/sftp)  | 719 |  Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. |![star > 100][Bronze]   
| [ssh](https://github.com/gliderlabs/ssh)  | 1093 |  用于构建SSH服务器的高级API(封装密码/ SSH)。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [sslb](https://github.com/eduardonunesp/sslb)  | 113 |  它是一个超级简单的负载平衡器，只是一个实现某种性能的小项目。 |![star > 100][Bronze]   
| [stun](https://github.com/go-rtc/stun)  | 263 |  Go实现的RFC 5389 STUN协议。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [tcp_server](https://github.com/firstrow/tcp_server)  | 279 |   Go 图书馆建设tcp服务器更快。 |![star > 100][Bronze]   
| [tspool](https://github.com/two/tspool)  | 6 |  TCP库使用工作池来提高性能并保护服务器。 |
| [utp](https://github.com/anacrolix/utp)  | 149 |  Go uTP微传输协议的实现。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [water](https://github.com/songgao/water)  | 831 |  简单TUN / TAP图书馆。 |![star > 100][Bronze]   
| [webrtc](https://github.com/pions/webrtc)  | 2142 |  WebRTC API的纯Go实现。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [winrm](https://github.com/masterzen/winrm)  | 210 |   Go WinRM客户端远程执行Windows机器上的命令。 |![star > 100][Bronze]   
| [xtcp](https://github.com/xfxdev/xtcp)  | 81 |  TCP服务器框架具有同时全双工通信，优雅关机，自定义协议。 |

### HTTP客户端

*用于发出HTTP请求的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gentleman](https://github.com/h2non/gentleman)  | 673 |  功能齐全的插件驱动HTTP客户端库。 |![star > 100][Bronze]   
| [goreq](https://github.com/smallnest/goreq)  | 98 |  基于gorequest的增强简化HTTP客户机。 |
| [grequests](https://github.com/levigross/grequests)  | 1398 |  一个 Go “克隆”的伟大和著名的请求库。 |![star > 1000][Silver]   
| [heimdall](https://github.com/gojektech/heimdall)  | 1059 |  具有重试和hystrix功能的增强http客户机。 |![star > 1000][Silver]   
| [pester](https://github.com/sethgrid/pester)  | 324 |  使用重试、后退和并发执行HTTP客户机调用。 |![star > 100][Bronze]   
| [rq](https://github.com/ddo/rq)  | 26 |  golang stdlib HTTP客户端更好的接口。 |
| [sling](https://github.com/dghubble/sling)  | 965 |  Sling是一个用于创建和发送API请求的Go HTTP客户端库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]

## OpenGL

*用于在Go中使用OpenGL的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gl](https://github.com/go-gl/gl)  | 635 |  OpenGL的Go绑定(通过glow生成)。 |![star > 100][Bronze]   
| [glfw](https://github.com/go-gl/glfw)  | 724 |  Go绑定用于glfw3。 |![star > 100][Bronze]   
| [goxjs/gl](https://github.com/goxjs/gl)  | 131 |  跨平台的OpenGL绑定(OS X, Linux, Windows，浏览器，iOS, Android)。 |![star > 100][Bronze]   
| [goxjs/glfw](https://github.com/goxjs/glfw)  | 58 |  使用跨平台glfw库创建OpenGL上下文并接收事件。 |
| [mathgl](https://github.com/go-gl/mathgl)  | 288 |  纯Go数学软件包专门为三维数学，与灵感来自GLM。 |![star > 100][Bronze]   ![最近一个周有更新][Green]

## ORM

*实现对象关系映射或数据映射技术的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [beego orm](https://github.com/astaxie/beego/tree/master/orm)  | - |  强大的orm框架。支持:pq / mysql / sqlite3。 |
| [go-firestorm](https://github.com/jschoedt/go-firestorm)  | 1 |  一个用于谷歌/Firebase云Firestore的简单ORM。 |
| [go-pg](https://github.com/go-pg/pg)  | 2918 |  关注PostgreSQL的特性和性能。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [go-queryset](https://github.com/jirfag/go-queryset)  | 447 |  100%类型安全ORM与代码生成和MySQL, PostgreSQL, Sqlite3, SQL Server支持基于GORM。 |![star > 100][Bronze]   
| [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder)  | 228 |  一个灵活而强大的SQL字符串构建器库加上一个零配置ORM。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-store](https://github.com/gosuri/go-store)  | 93 |  简单而快速的Redis支持的键值存储库。 |![最近一年没有更新][Yellow]
| [GORM](https://github.com/jinzhu/gorm)  | 14374 |  Golang出色的ORM库的目标是对开发人员友好。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [gorp](https://github.com/go-gorp/gorp)  | 3068 |  Go的关系持久性，ORM-ish库。 |![star > 1000][Silver]   
| [grimoire](https://github.com/Fs02/grimoire)  | 113 |  Grimoire是golang的数据库访问层和验证。(支持:MySQL, PostgreSQL和SQLite3)。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [lore](https://github.com/abrahambotros/lore)  | 4 |  用于Go的简单轻量级伪orm /伪结构映射环境。 |![最近一年没有更新][Yellow]
| [Marlow](https://github.com/dadleyy/marlow)  | 63 |  从项目结构生成ORM，用于编译时安全保证。 |
| [pop/soda](https://github.com/gobuffalo/pop)  | 667 |  数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [QBS](https://github.com/coocood/qbs)  | 538 |  表示结构查询。一个ORM。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [reform](https://github.com/go-reform/reform)  | 789 |  更好的ORM for Go，基于非空接口和代码生成。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [SQLBoiler](https://github.com/volatiletech/sqlboiler)  | 2231 |  ORM生成器。根据您的数据库模式生成一个功能强大且运行速度快的ORM。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [upper.io/db](https://github.com/upper/db)  | 1837 |  通过使用封装成熟数据库驱动程序的适配器与不同数据源交互的单一接口。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [Xorm](https://github.com/go-xorm/xorm)  | 5088 |  简单而强大的ORM for Go。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [Zoom](https://github.com/albrow/zoom)  | 239 |  基于Redis的快速数据存储和查询引擎。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 包管理

*用于管理依赖和包的官方工具*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more)  | - |  Modules 是源码的版本控制和交换的单位。go命令直接支持处理模块，包括记录和解决对其他模块的依赖关系。 |

*包管理的官方实验工具*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [dep](https://github.com/golang/dep)  | 12490 |   Go 的依赖管理工具，需要 Go 1.9+ |![star > 5000][Gold]   
| [vgo](https://go.googlesource.com/vgo/)  | - |  Go 命令版本管理 |

*用于包和依赖项管理的非官方库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gigo](https://github.com/LyricalSecurity/gigo)  | 196 |  类似pip的golang依赖工具，支持私有存储库和散列。 |![star > 100][Bronze]   
| [glide](https://github.com/Masterminds/glide)  | 7758 |  轻松管理您的 golang 第三方包。受Maven、Bundler和Pip等工具的启发。 |![star > 5000][Gold]   
| [godep](https://github.com/tools/godep)  | 5651 |  godep是go的依赖工具，它通过修复包的依赖关系来帮助构建可重复的包。 |![star > 5000][Gold]   ![最近一年没有更新][Yellow]
| [gom](https://github.com/mattn/gom)  | 1351 |  Go Manager - bundle for Go。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [goop](https://github.com/nitrous-io/goop)  | 777 |  Go 的简单依赖管理器，灵感来自Bundler。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gop](https://github.com/lunny/gop)  | 50 |  在GOPATH之外构建和管理Go应用程序。 |
| [gopm](https://github.com/gpmgo/gopm)  | 2343 |  包管理器。 |![star > 1000][Silver]   
| [govendor](https://github.com/kardianos/govendor)  | 4699 |  包管理器。使用 vendor 文件的 Go vendor 工具。 |![star > 1000][Silver]   
| [gpm](https://github.com/pote/gpm)  | 1205 |  基本的 Go 依赖管理器。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [johnny-deps](https://github.com/VividCortex/johnny-deps)  | 214 |  使用Git的最小依赖版本。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [mvn-golang](https://github.com/raydac/mvn-golang)  | 87 |  插件，为自动加载Golang SDK，依赖关系管理和启动Maven项目基础设施中的构建环境提供了方法。 |![最近一个周有更新][Green]
| [nut](https://github.com/jingweno/nut)  | 245 |  vendor 依赖。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [VenGO](https://github.com/DamnWidget/VenGO)  | 115 |  创建和管理可导出的隔离go虚拟环境。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 查询语言

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gojsonq](https://github.com/thedevsaddam/gojsonq)  | 846 |  一个用来查询JSON数据的Go包。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [graphql](https://github.com/tmc/graphql)  | 51 |  graphql解析器+工具集 |![最近一年没有更新][Yellow]
| [graphql](https://github.com/neelance/graphql-go)  | 2734 |  关注易用性的GraphQL服务器。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [graphql-go](https://github.com/graphql-go/graphql)  | 5118 |  为Go实现GraphQL。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [jsonql](https://github.com/elgs/jsonql)  | 201 |  Golang中的JSON查询表达式库。 |![star > 100][Bronze]   
| [jsonslice](https://github.com/bhmj/jsonslice)  | 23 |  使用高级过滤器查询Jsonpath。 |
| [rql](https://github.com/a8m/rql)  | 110 |  用于REST API的资源查询语言。 |![star > 100][Bronze]   ![最近一个周有更新][Green]

## 嵌入的资源

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [esc](https://github.com/mjibson/esc)  | 462 |  将文件嵌入到Go程序中并提供http文件系统接口。 |![star > 100][Bronze]   
| [fileb0x](https://github.com/UnnoTed/fileb0x)  | 417 |  一个可定制的工具用来在Go中嵌入文件 |![star > 100][Bronze]   
| [go-embed](https://github.com/pyros2097/go-embed)  | 14 |  生成go代码，将资源文件嵌入到库或可执行文件中。 |![最近一年没有更新][Yellow]
| [go-resources](https://github.com/omeid/go-resources)  | 154 |  嵌入到Go中的普通资源。 |![star > 100][Bronze]   
| [go.rice](https://github.com/GeertJohan/go.rice)  | 1629 |  go.rice 是一个Go包，它使处理html、js、css、图像和模板等资源变得非常容易。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [packr](https://github.com/gobuffalo/packr)  | 2055 |  将静态文件嵌入到Go二进制文件中的简单方法。 |![star > 1000][Silver]   
| [statics](https://github.com/go-playground/statics)  | 53 |  将静态资源嵌入到go文件中，用于单个二进制编译+使用http。文件系统+符号链接。 |![最近一年没有更新][Yellow]
| [statik](https://github.com/rakyll/statik)  | 2060 |  将静态文件嵌入到Go可执行文件中。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [templify](https://github.com/wlbr/templify)  | 19 |  将外部模板文件嵌入到Go代码中，以创建单个文件二进制文件。 |
| [vfsgen](https://github.com/shurcooL/vfsgen)  | 644 |  生成一个vfsdata。静态实现给定虚拟文件系统的go文件。 |![star > 100][Bronze]   

## 科学与数据分析

*用于科学计算和数据分析的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [assocentity](https://github.com/ndabAP/assocentity)  | 3 |  assocentity 返回单词到给定实体的平均距离。 |
| [bradleyterry](https://github.com/seanhagen/bradleyterry)  | - |  为成对比较提供了一个 Bradley-Terry 模型。 |
| [chart](https://github.com/vdobler/chart)  | 580 |  简单的图表绘制库。支持多种图形类型。 |![star > 100][Bronze]   
| [dataframe-go](https://github.com/rocketlaunchr/dataframe-go)  | 68 |  用于机器学习和统计的数据模型(类似于 pandas)。 |![最近一个周有更新][Green]
| [evaler](https://github.com/soniah/evaler)  | 40 |  简单的浮点算术表达式求值器。 |
| [ewma](https://github.com/VividCortex/ewma)  | 264 |  提供指数加权移动平均算法。 |![star > 100][Bronze]   
| [geom](https://github.com/skelterjohn/geom)  | 40 |   Go 的二维几何。 |![最近一年没有更新][Yellow]
| [go-dsp](https://github.com/mjibson/go-dsp)  | 624 |  Go数字信号处理。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-fn](https://github.com/ematvey/go-fn)  | 11 |  用Go语言编写的数学函数，不包括在math pkg中。 |![最近一年没有更新][Yellow]
| [go-gt](https://github.com/ThePaw/go-gt)  | 5 |  用“Go”语言编写的图论算法。 |![最近一年没有更新][Yellow]
| [gocomplex](https://github.com/varver/gocomplex)  | 5 |  用于 Go 编程语言的复数库。 |![最近一年没有更新][Yellow]
| [goent](https://github.com/kzahedi/goent)  | 13 |   Go 实现熵度量。 |
| [gohistogram](https://github.com/VividCortex/gohistogram)  | 126 |  数据流的近似直方图。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gonum](https://github.com/gonum/gonum)  | 2886 |  Gonum是一组用于Go编程语言的数字库。它包含用于矩阵、统计、优化等的库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gonum/plot](https://github.com/gonum/plot)  | 1198 |  gonum/plot提供了一个API，用于在Go中构建和绘制绘图。 |![star > 1000][Silver]   
| [goraph](https://github.com/gyuho/goraph)  | 597 |  纯Go图论库(数据结构，算法可视化)。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gosl](https://github.com/cpmech/gosl)  | 1296 |  提供线性代数，FFT，几何，NURBS，数值方法，概率，优化，微分方程，等等。 |![star > 1000][Silver]   
| [GoStats](https://github.com/OGFris/GoStats)  | 9 |  GoStats是一个开放源码的GoLang库，主要用于机器学习领域的数学统计，它涵盖了大多数统计度量函数。 |
| [graph](https://github.com/yourbasic/graph)  | 228 |  基本图形算法库。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [ode](https://github.com/ChristopherRabotin/ode)  | 10 |  常微分方程(ODE)求解器，支持扩展状态和基于信道的迭代停止条件。 |![最近一年没有更新][Yellow]
| [orb](https://github.com/paulmach/orb)  | 193 |  2D几何类型，支持剪切、GeoJSON和Mapbox矢量平铺。 |![star > 100][Bronze]   
| [pagerank](https://github.com/alixaxel/pagerank)  | 47 |  加权 PageRank 算法在Go中的实现。 |
| [piecewiselinear](https://github.com/sgreben/piecewiselinear)  | 5 |  微型线性插值库。 |
| [PiHex](https://github.com/claygod/PiHex)  | 9 |  实现了针对16进制数 Pi 的“bailee - borwein - plouffe”算法。 |
| [rootfinding](https://github.com/khezen/rootfinding)  | 3 |  二次函数求根算法库。 |
| [sparse](https://github.com/james-bowman/sparse)  | 68 |   Go 稀疏矩阵格式的线性代数支持科学和机器学习应用程序，兼容gonum矩阵库。 |
| [stats](https://github.com/montanaflynn/stats)  | 1331 |  包含Golang标准库中缺少的公共函数的统计软件包。 |![star > 1000][Silver]   
| [streamtools](https://github.com/nytlabs/streamtools)  | 1314 |  通用图形工具，用于处理数据流。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [TextRank](https://github.com/DavidBelicza/TextRank)  | 65 |  TextRank在Golang中的实现，支持扩展特性(摘要、加权、短语提取)和多线程(goroutine)。 |
| [triangolatte](https://github.com/tchayen/triangolatte)  | 11 |  二维三角库。允许将线和多边形(都基于点)转换为gpu语言。 |![最近一个周有更新][Green]

## 安全

*用于帮助您的应用程序更安全的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [acmetool](https://github.com/hlandau/acme)  | 1691 |  ACME(让我们用自动更新加密)客户端工具。 |![star > 1000][Silver]   
| [acra](https://github.com/cossacklabs/acra)  | 444 |  网络加密代理保护基于数据库的应用程序免受数据泄漏:强选择性加密，SQL注入预防，入侵检测系统。 |![star > 100][Bronze]   
| [argon2pw](https://github.com/raja/argon2pw)  | 72 |  使用常量时间密码比较生成Argon2密码散列。 |
| [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert)  | - |  让我们加密证书并启动TLS服务器。 |
| [BadActor](https://github.com/jaredfolkins/badactor)  | 244 |  一个驻留在内存中的，应用驱动的监控程序，受 fail2ban 的启发 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Cameradar](https://github.com/Ullaakut/cameradar)  | 1802 |  工具和库，以远程入侵RTSP流从监控摄像头。 |![star > 1000][Silver]   
| [certificates](https://github.com/mvmaasakkers/certificates)  | 6 |  用于生成tls证书的自定义工具。 |
| [go-yara](https://github.com/hillu/go-yara)  | 131 |  YARA的 Go 语言接口，号称是 “对于恶意软件研究者（以及其他人）来说是模式匹配的瑞士军刀” |![star > 100][Bronze]   
| [goArgonPass](https://github.com/dwin/goArgonPass)  | 11 |  Argon2密码散列和验证设计为与现有Python和PHP实现兼容。 |
| [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword)  | 28 |  一个安全哈希和加密密码的偏执包。 |
| [Interpol](https://bitbucket.org/vahidi/interpol)  | - |  基于规则的数据生成器，用于模糊和渗透测试。 |
| [jwc](https://github.com/khezen/jwc)  | 5 |  JSON Web加密库。 |
| [lego](https://github.com/xenolf/lego)  | 3440 |  纯 Go ACME 客户端库及命令行工具 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [memguard](https://github.com/awnumar/memguard)  | 997 |  一个用于处理内存中敏感值的纯Go库。 |![star > 100][Bronze]   
| [nacl](https://github.com/kevinburke/nacl)  | 449 |   Go 实现NaCL API的集合。 |![star > 100][Bronze]   
| [passlib](https://github.com/hlandau/passlib)  | 225 |  不过时的密码哈希库。 |![star > 100][Bronze]   
| [secure](https://github.com/unrolled/secure)  | 1191 |  Go 语言 HTTP 中间件，为 Go 提供了一些安全功能 |![star > 1000][Silver]   
| [simple-scrypt](https://github.com/elithrar/simple-scrypt)  | 155 |  Scrypt 库，具有简单、易懂的 API，同时具有内置的自动校准功能 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [ssh-vault](https://github.com/ssh-vault/ssh-vault)  | 195 |  使用ssh密钥加密/解密。 |![star > 100][Bronze]   
| [sslmgr](https://github.com/adrianosela/sslmgr)  | 7 |  使用围绕acme/autocert的高级包装器，SSL证书变得很容易。 |

## 序列化

*用于二进制序列化的库和工具。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [asn1](https://github.com/PromonLogicalis/asn1)  | 40 |  面向golang的BER和DER编码库。 |
| [bambam](https://github.com/glycerine/bambam)  | 60 |  用于 Go 语言生成 Cap'n Proto schemas 的生成器 |![最近一年没有更新][Yellow]
| [bel](https://github.com/32leaves/bel)  | 5 |  从Go structs/interface生成TypeScript接口。对JSON RPC很有用。 |
| [binstruct](https://github.com/ghostiam/binstruct)  | 7 |  用于将数据映射到结构中的Golang二进制解码器。 |
| [colfer](https://github.com/pascaldekloe/colfer)  | 472 |  为Colfer二进制格式生成代码。 |![star > 100][Bronze]   
| [csvutil](https://github.com/jszwec/csvutil)  | 299 |  高性能、惯用的CSV记录编码和解码到本机Go结构。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [fwencoder](https://github.com/o1egl/fwencoder)  | 6 |  用于Go的固定宽度文件解析器(编码和解码库)。 |![最近一年没有更新][Yellow]
| [go-capnproto](https://github.com/glycerine/go-capnproto)  | 272 |  Go 语言用的 Cap'n Proto 库及解析器 |![star > 100][Bronze]   
| [go-codec](https://github.com/ugorji/go)  | 1222 |  高性能、多功能、规范化编码解码以及 rpc 库， 用于 msgpack, cbor 和 json，支持基于运行时的 OR 码生成 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gogoprotobuf](https://github.com/gogo/protobuf)  | 2881 |  Go 语言的 Protocol Buffer 库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [goprotobuf](https://github.com/golang/protobuf)  | 4979 |  通过库和协议编译器插件使 Go 语言支持 Google的 protocol buffers. |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [jsoniter](https://github.com/json-iterator/go)  | 5383 |  高性能，100% 兼容的“encoding/json” 替代品 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [mapstructure](https://github.com/mitchellh/mapstructure)  | 2360 |  用于对原生键值对进行解码生成 Go 语言结构体 |![star > 1000][Silver]   
| [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder)  | 118 |  用于协同 PHP session 格式数据和 PHP 序列化／反序列化函数工作的go语言库 |![star > 100][Bronze]   
| [structomap](https://github.com/tuvistavie/structomap)  | 92 |  用于从静态结构体简单、动态的生成键值对的库 |

## 服务器应用程序

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [algernon](https://github.com/xyproto/algernon)  | 1577 |  内置支持Lua、Markdown、GCSS和Amber的HTTP/2 web服务器。 |![star > 1000][Silver]   
| [Caddy](https://github.com/mholt/caddy)  | 22893 |  Caddy是另一种HTTP/2 web服务器，易于配置和使用。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [consul](https://www.consul.io/)  | - |  Consul 是一个用于服务发现、监控和配置的工具 |
| [devd](https://github.com/cortesi/devd)  | 2793 |  为开发人员提供本地web服务器。 |![star > 1000][Silver]   
| [discovery](https://github.com/Bilibili/discovery)  | 657 |  用于弹性中间层负载平衡和故障转移的注册表。 |![star > 100][Bronze]   
| [etcd](https://github.com/coreos/etcd)  | 26076 |  为共享配置和服务发现提供高可用的键值存储。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [Fider](https://github.com/getfider/fider)  | 784 |  Fider是一个收集和组织客户反馈的开放平台。 |![star > 100][Bronze]   
| [Flagr](https://github.com/checkr/flagr)  | 807 |  Flagr是一个开源特性标记和A/B测试服务。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [flipt](https://github.com/markphelps/flipt)  | 981 |  一个用Go和Vue.js编写的自包含特性标志解决方案 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [jackal](https://github.com/ortuman/jackal)  | 709 |  用Go编写的XMPP服务器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [minio](https://github.com/minio/minio)  | 17022 |  Minio是一个分布式对象存储服务器。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus)  | 5 |  Nginx日志解析器和Prometheus 导出。 |
| [nsq](http://nsq.io/)  | - |  一个实时分布式消息平台。 |
| [psql-streamer](https://github.com/blind-oracle/psql-streamer)  | 5 |  从PostgreSQL到Kafka的流数据库事件。 |
| [riemann-relay](https://github.com/blind-oracle/riemann-relay)  | - |  传递到负载平衡Riemann事件并/或将其转换为 Carbon。 |
| [RoadRunner](https://github.com/spiral/roadrunner)  | 3192 |  高性能PHP应用服务器，负载平衡器和进程管理器。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [yakvs](https://git.sci4me.com/sci4me/yakvs)  | - |  小型化、网络化、基于内存的键值存储 |

## 模板引擎

*用于模板和词法分析的库和工具。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [ace](https://github.com/yosssi/ace)  | 759 |  Ace 是一个 Go 语言的 HTML 模板引擎，受到了 Slim 和 Jade 的启发。 Ace 是对Gold的一种改进。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [amber](https://github.com/eknkc/amber)  | 821 |  Amber是一个优雅的Go编程语言模板引擎，它的灵感来自HAML和Jade。 |![star > 100][Bronze]   
| [damsel](https://github.com/dskinner/damsel)  | 20 |  标记语言，通过css选择器实现了 html 框架 ，并可以通过 pkg html/template 等进行扩展 |![最近一年没有更新][Yellow]
| [ego](https://github.com/benbjohnson/ego)  | 408 |  轻量级模板语言，允许您在Go中编写模板。模板被翻译成Go并编译。 |![star > 100][Bronze]   
| [extemplate](https://github.com/dannyvankooten/extemplate)  | 13 |   对 html/template 进行了简单的封装，支持基于文件的模板可以利用其他模板文件进行扩展 |
| [fasttemplate](https://github.com/valyala/fasttemplate)  | 288 |  简单快速的模板引擎。进行模板元素替换时，速度是比[text/template](http://golang.org/pkg/text/template/)快10倍。 |![star > 100][Bronze]   
| [gofpdf](https://github.com/jung-kurt/gofpdf)  | 3039 |  PDF 文档生成器，支持文本，绘图和图片 |![star > 1000][Silver]   
| [goview](https://github.com/foolin/goview)  | 40 |  Goview是一个轻量级、极简的模板库，基于golang html/template构建Go web应用程序。 |![最近一个周有更新][Green]
| [hero](https://github.com/shiyanhui/hero)  | 1196 |  Hero是一个方便、快速和强大的go模板引擎。 |![star > 1000][Silver]   
| [jet](https://github.com/CloudyKit/jet)  | 579 |  Jet模板引擎。 |![star > 100][Bronze]   
| [kasia.go](https://github.com/ziutek/kasia.go)  | 70 |  一个用于HTML 和其他文本文件的模板系统，使用go语言实现 |![最近一年没有更新][Yellow]
| [liquid](https://github.com/osteele/liquid)  | 81 |  Go 语言实现的 Shopify Liquid 模板. |
| [mustache](https://github.com/hoisie/mustache)  | 967 |  Go 语言实现的 Mustache 模板语言 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [pongo2](https://github.com/flosch/pongo2)  | 1483 |  类似 DjanGo 的模板引擎 |![star > 1000][Silver]   
| [quicktemplate](https://github.com/valyala/quicktemplate)  | 1380 |  快速、强大且易用的模板引擎。将模板转化为 Go 语言并进行编译 |![star > 1000][Silver]   
| [raymond](https://github.com/aymerick/raymond)  | 335 |  使用 Go 语言实现的完整的 handlebars |![star > 100][Bronze]   
| [Razor](https://github.com/sipin/gorazor)  | 691 |  Go 语言的 Razor 视图引擎 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [Soy](https://github.com/robfig/soy)  | 144 |  Go 语言实现的谷歌闭包模板(也就是 Soy templates) ,遵循[官方规范](https://developer.google.com/closure/templates/)。 |![star > 100][Bronze]   
| [velvet](https://github.com/gobuffalo/velvet)  | 64 |  使用 Go 语言实现的完整的 handlebars |![最近一年没有更新][Yellow]

## 测试

*用于测试代码库和生成测试数据的库。*

* Testing Frameworks
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [assert](https://github.com/go-playground/assert)  | 13 |  基础断言库，用于对 Go 语言程序进行测试，提供了一些用于自定义断言的代码块 |![最近一年没有更新][Yellow]
| [badio](https://github.com/cavaliercoder/badio)  | 8 |  Go 语言 testing/iotest 包的扩展。 |![最近一年没有更新][Yellow]
| [baloo](https://github.com/h2non/baloo)  | 640 |  表达性强、多功能的、端到端的HTTP API 测试工具 |![star > 100][Bronze]   
| [biff](https://github.com/fulldump/biff)  | 6 |  分支测试框架，BDD兼容。 |![最近一年没有更新][Yellow]
| [bro](https://github.com/marioidival/bro)  | 26 |  监控目录中的文件并对其进行测试 |![最近一年没有更新][Yellow]
| [charlatan](https://github.com/percolate/charlatan)  | 188 |  为测试生成假接口实现的工具。 |![star > 100][Bronze]   
| [commander](https://github.com/SimonBaeumer/commander)  | 32 |  用于在windows、linux和osx上测试cli应用程序的工具。 |
| [cupaloy](https://github.com/bradleyjkemp/cupaloy)  | 81 |  测试框架的简单快照测试插件。 |
| [dbcleaner](https://github.com/khaiql/dbcleaner)  | 84 |  清空数据库用于测试，受到database_cleaner 的启发 |
| [dsunit](https://github.com/viant/dsunit)  | 25 |  用于SQL、NoSQL、结构化文件的数据存储测试。 |![最近一个周有更新][Green]
| [endly](https://github.com/viant/endly)  | 90 |  声明性端到端功能测试。 |![最近一个周有更新][Green]
| [frisby](https://github.com/verdverm/frisby)  | 248 |  REST API测试框架。 |![star > 100][Bronze]   
| [ginkgo](http://onsi.github.io/ginkgo/)  | - |  Go的BDD测试框架。 |
| [go-carpet](https://github.com/msoap/go-carpet)  | 195 |  在终端中查看测试覆盖率的工具。 |![star > 100][Bronze]   
| [go-cmp](https://github.com/google/go-cmp)  | 1116 |  用于比较测试中的Go值的包。 |![star > 1000][Silver]   
| [go-mutesting](https://github.com/zimmski/go-mutesting)  | 284 |  变异测试的Go源代码。 |![star > 100][Bronze]   
| [go-testdeep](https://github.com/maxatome/go-testdeep)  | 55 |  极具灵活性的golang深度比较，扩展了go测试包。 |
| [go-vcr](https://github.com/dnaeon/go-vcr)  | 327 |  记录并回放HTTP交互，以便进行快速、确定和准确的测试。 |![star > 100][Bronze]   
| [goblin](https://github.com/franela/goblin)  | 614 |  类似Mocha的测试框架。 |![star > 100][Bronze]   
| [gocheck](http://labix.org/gocheck)  | - |  更加高级的测试框架，用于替换 Gotest |
| [GoConvey](https://github.com/smartystreets/goconvey/)  | - |  BDD 风格的测试框架，具有 web 界面和计时刷新功能 |
| [gocrest](https://github.com/corbym/gocrest)  | 8 |  用于 Go 断言的可组合的类似 hamcrest 的 matchers。 |![最近一年没有更新][Yellow]
| [godog](https://github.com/DATA-DOG/godog)  | 733 |  类似 Cucumber 或 Behat 的 BDD 框架 |![star > 100][Bronze]   
| [gofight](https://github.com/appleboy/gofight)  | 252 |  对 Go 语言的路由框架进行 API 测试 |![star > 100][Bronze]   
| [gogiven](https://github.com/corbym/gogiven)  | 7 |  类似于 YATSPEC 的Go BDD测试框架。 |![最近一年没有更新][Yellow]
| [gomatch](https://github.com/jfilipczyk/gomatch)  | 30 |  为针对模式测试JSON而创建的库。 |
| [gomega](http://onsi.github.io/gomega/)  | - |  类似 Rspec 的 matcher/assertion 库 |
| [GoSpec](https://github.com/orfjackal/gospec)  | 111 |  用于 Go 编程语言的bdd风格的测试框架。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gospecify](https://github.com/stesla/gospecify)  | 51 |  支持 BDD 语法 。对于任何使用过 rspec 等库的人来说应该非常熟悉。 |![最近一年没有更新][Yellow]
| [gosuite](https://github.com/pavlo/gosuite)  | 9 |  轻量级测试套，为 Go1.7's Subtests 带来了setup/teardown 功能 |![最近一年没有更新][Yellow]
| [gotest.tools](https://github.com/gotestyourself/gotest.tools)  | 118 |  一组包，用于增强go测试包并支持公共模式。 |![star > 100][Bronze]   
| [Hamcrest](https://github.com/rdrdr/hamcrest)  | 26 |  用于声明性 Matcher 对象的连贯框架，当将其应用于输入值时，将产生自描述结果。 |![最近一年没有更新][Yellow]
| [httpexpect](https://github.com/gavv/httpexpect)  | 1124 |  简洁的、声明式的、易用的端到端HTTP 及 REST API 测试 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [jsonassert](https://github.com/kinbiko/jsonassert)  | 21 |  用于验证JSON有效负载已正确序列化的包。 |
| [restit](https://github.com/yookoala/restit)  | 48 |  帮助编写 RESTful API 集成测试的 Go 语言微型框架.。 |![最近一年没有更新][Yellow]
| [testcase](https://github.com/adamluzsi/testcase)  | 8 |  行为驱动开发的惯用测试框架。 |![最近一个周有更新][Green]
| [testfixtures](https://github.com/go-testfixtures/testfixtures)  | 322 |  类似 Rails 的测试工具，用于测试数据库应用 |![star > 100][Bronze]   
| [Testify](https://github.com/stretchr/testify)  | 7949 |  对标准测试包的扩展。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd)  | - |  将markdown代码段转换为可测试的go代码。 |
| [testsql](https://github.com/zhulongcheng/testsql)  | 7 |  在测试前从SQL文件生成测试数据，并在测试完成后清除数据。 |
| [Tt](https://github.com/vcaesar/tt)  | 5 |  简单而丰富多彩的测试工具。 |![最近一个周有更新][Green]
| [wstest](https://github.com/posener/wstest)  | 61 |  用于单元测试Websocket http.Handler的Websocket客户机。 |![最近一年没有更新][Yellow]

* Mock
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter)  | 355 |  用于生成自包含 mock 对象的工具 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock)  | 1682 |  Mock SQL ，用于测试数据库交互 |![star > 1000][Silver]   
| [go-txdb](https://github.com/DATA-DOG/go-txdb)  | 157 |  基于单事务的数据库驱动，主要用于测试目的 |![star > 100][Bronze]   
| [gock](https://github.com/h2non/gock)  | 796 |  多功能、易用 HTTP mock |![star > 100][Bronze]   
| [gomock](https://github.com/golang/mock)  | 2731 |  用于Go编程语言的mock框架。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [govcr](https://github.com/seborama/govcr)  | 81 |  HTTP mock : 离线测试时记录和重放浏览器的动作 |![最近一个周有更新][Green]
| [hoverfly](https://github.com/SpectoLabs/hoverfly)  | 1425 |  使用可扩展中间件和易于使用的CLI记录和模拟REST/SOAP api的HTTP(S)代理。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [httpmock](https://github.com/jarcoal/httpmock)  | 570 |  轻松模拟来自外部资源的HTTP响应。 |![star > 100][Bronze]   
| [minimock](https://github.com/gojuno/minimock)  | 191 |  Go接口的模拟生成器。 |![star > 100][Bronze]   
| [mockhttp](https://github.com/tv42/mockhttp)  | 22 |  Go http.ResponseWriter的模拟对象。 |![最近一年没有更新][Yellow]

* Fuzzing and delta-debugging/reducing/shrinking.
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [go-fuzz](https://github.com/dvyukov/go-fuzz)  | 2856 |  随机测试系统。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gofuzz](https://github.com/google/gofuzz)  | 526 |  用于生成随机值来初始化 Go 语言对象的库 |![star > 100][Bronze]   
| [Tavor](https://github.com/zimmski/tavor)  | 209 |  通用模糊测试框架 |![star > 100][Bronze]   

* Selenium and browser control tools.
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [cdp](https://github.com/mafredri/cdp)  | 347 |  用于Chrome调试协议的类型安全绑定，可与实现该协议的浏览器或其他调试目标一起使用。 |![star > 100][Bronze]   
| [chromedp](https://github.com/knq/chromedp)  | 3465 |  用于驱动和测试 Chrome, Safari, Edge, Android Webviews, 以及其他支持 Chrome 调试协议的产品 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [ggr](https://github.com/aerokube/ggr)  | 208 |  一个轻量级服务器，可以将 Selenium Wedriver 的请求路由或代理到多个 Selenium hubs |![star > 100][Bronze]   
| [selenoid](https://github.com/aerokube/selenoid)  | 1196 |  Selenium hub 服务器的替代品，在容器中启动浏览器 |![star > 1000][Silver]   ![最近一个周有更新][Green]

* Fail injection
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [failpoint](https://github.com/pingcap/failpoint)  | 375 |  为Golang实现[failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail)。 |![star > 100][Bronze]   

## 文本处理

*用于解析和操作文本的库。*

* Specific Formats
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [align](https://github.com/Guitarbum722/align)  | 56 |  对文本进行对齐的通用应用程序。 |![最近一年没有更新][Yellow]
| [allot](https://github.com/sbstjn/allot)  | 33 |  用于CLI工具和机器人的占位符和通配符文本解析。 |
| [bbConvert](https://github.com/CalebQ42/bbConvert)  | 5 |  将bbCode转换为HTML，使您可以添加对自定义bbCode标记的支持。 |![最近一年没有更新][Yellow]
| [blackfriday](https://github.com/russross/blackfriday)  | 3847 |  Markdown 解析器 |![star > 1000][Silver]   
| [bluemonday](https://github.com/microcosm-cc/bluemonday)  | 1221 |  HTML 清理工具 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [codetree](https://github.com/aerogo/codetree)  | 7 |  解析缩进代码(python、pixy、scarlet等)并返回树结构。 |
| [colly](https://github.com/asciimoo/colly)  | 8182 |  快速和优雅的 Scraping 框架。 |![star > 5000][Gold]   
| [commonregex](https://github.com/mingrammer/commonregex)  | 551 |  一组用于Go的公共正则表达式。 |![star > 100][Bronze]   
| [dataflowkit](https://github.com/slotix/dataflowkit)  | 284 |  Web抓取框架将网站转换为结构化数据。 |![star > 100][Bronze]   
| [did](https://github.com/ockam-network/did)  | 22 |  DID(分散标识符)解析器和Stringer。 |
| [doi](https://github.com/hscells/doi)  | 4 |  文档对象标识符(doi)解析器。 |![最近一年没有更新][Yellow]
| [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go)  | 37 |  Editorconfig文件解析器和Go操作器。 |![最近一个周有更新][Green]
| [enca](https://github.com/endeveit/enca)  | 7 |  [libenca](http://cihar.com/software/enca/)的最小cgo绑定。 |![最近一年没有更新][Yellow]
| [encdec](https://github.com/mickep76/encdec)  | 3 |  软件包为编码器和解码器提供了通用接口。 |
| [genex](https://github.com/alixaxel/genex)  | 50 |  将正则表达式计数并展开为所有匹配的字符串。 |
| [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown)  | - |  GitHub 风格的 Markdown 渲染器 (使用 blackfriday) ，支持代码块高亮以及可点击的锚点 |
| [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth)  | 24 |  固定宽度的文本格式(带反射的编码器/解码器)。 |![最近一个周有更新][Green]
| [go-humanize](https://github.com/dustin/go-humanize)  | 1867 |  格式化程序，用于将时间、数字和内存大小转换为可读格式。 |![star > 1000][Silver]   
| [go-nmea](https://github.com/adrianmo/go-nmea)  | 94 |  用于Go语言的NMEA解析器库。 |![最近一个周有更新][Green]
| [go-runewidth](https://github.com/mattn/go-runewidth)  | 208 |  函数获取字符或字符串的固定宽度。 |![star > 100][Bronze]   
| [go-slugify](https://github.com/mozillazg/go-slugify)  | 27 |  生成漂亮的固定链接地址（slug），支持多种语言 |![最近一年没有更新][Yellow]
| [go-toml](https://github.com/pelletier/go-toml)  | 601 |  使用带有查询支持和方便的cli工具的TOML格式库。 |![star > 100][Bronze]   
| [go-vcard](https://github.com/emersion/go-vcard)  | 24 |  解析和格式化vCard。 |
| [go-zero-width](https://github.com/trubitsyn/go-zero-width)  | 41 |  用于Go的零宽度字符检测和删除。 |
| [gofeed](https://github.com/mmcdole/gofeed)  | 1085 |  在Go中解析RSS和Atom feeds。 |![star > 1000][Silver]   
| [gographviz](https://github.com/awalterschulze/gographviz)  | 291 |  解析Graphviz DOT语言。 |![star > 100][Bronze]   
| [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes)  | - |  格式化二进制为字符串。 |
| [gonameparts](https://github.com/polera/gonameparts)  | 29 |  将人名解析为单独的名称部分。 |![最近一年没有更新][Yellow]
| [goq](https://github.com/andrewstuart/goq)  | 143 |   声明式 HTML 编组，使用结构标签和 jQuery 语法 (使用 GoQuery). |![star > 100][Bronze]   
| [GoQuery](https://github.com/PuerkitoBio/goquery)  | 7477 |  GoQuery 为 Go 语言带来了一组类似 jQuery 的语法和功能 |![star > 5000][Gold]   
| [goregen](https://github.com/zach-klippenstein/goregen)  | 35 |  根据正则表达式生成随机字符串 |![最近一年没有更新][Yellow]
| [gotext](https://github.com/leonelquinteros/gotext)  | 229 |  GNU gettext 工具 |![star > 100][Bronze]   
| [guesslanguage](https://github.com/endeveit/guesslanguage)  | 44 |  通过一个 unicode 文本来猜测该文本使用的语言 |![最近一年没有更新][Yellow]
| [htmlquery](https://github.com/antchfx/htmlquery)  | 119 |  用于HTML的XPath查询包，允许您通过XPath表达式从HTML文档中提取数据或求值。 |![star > 100][Bronze]   
| [inject](https://github.com/facebookgo/inject)  | 1131 |  包注入提供了一个基于反射的注入器。 |![star > 1000][Silver]   
| [ltsv](https://github.com/Wing924/ltsv)  | 2 |  用于Go的高性能[LTSV(标签为Tab Separeted Value)](http://ltsv.org/)阅读器。 |
| [mxj](https://github.com/clbanning/mxj)  | 327 |  将XML编码/解码为JSON或map[string]接口{};使用点符号路径和通配符提取值。替换x2j和j2x包。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [sdp](https://github.com/gortc/sdp)  | 68 |  SDP:会话描述协议[[RFC 4566](https://tools.ietf.org/html/rfc4566)]。 |
| [sh](https://github.com/mvdan/sh)  | 1939 |  Shell解析器和格式化工具。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [slug](https://github.com/gosimple/slug)  | 365 |  URL 友好的 slug 化工具，支持多种语言 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [Slugify](https://github.com/avelino/slugify)  | 26 |  字符串 slug 化的工具。 |![最近一年没有更新][Yellow]
| [syndfeed](https://github.com/zhengchun/syndfeed)  | 4 |  Atom 1.0和RSS 2.0的联合提要。 |![最近一年没有更新][Yellow]
| [toml](https://github.com/BurntSushi/toml)  | 2741 |  TOML配置格式(带反射的编码器/解码器)。 |![star > 1000][Silver]   
* Utility
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself)  | 15 |  一个基于 sanitization 的 Go 敏感词过滤器。 |
| [gotabulate](https://github.com/bndr/gotabulate)  | 198 |  使用 Go 语言简单、美观的打印表格数据 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [kace](https://github.com/codemodus/kace)  | 12 |  通用大小写转换工具 |
| [parseargs-go](https://github.com/nproc/parseargs-go)  | 5 |  字符串参数解析器，能够理解引用及反斜杠。 |![最近一年没有更新][Yellow]
| [parth](https://github.com/codemodus/parth)  | 31 |  URL路径分割解析。 |
| [radix](https://github.com/yourbasic/radix)  | 141 |  快速字符串排序算法。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Tagify](https://github.com/zoomio/tagify)  | - |  从给定源生成一组标记。 |
| [TySug](https://github.com/Dynom/TySug)  | 3 |  关于键盘布局的其他建议。 |
| [xj2go](https://github.com/stackerzzq/xj2go)  | 17 |  将xml或json转换为struct。 |
| [xurls](https://github.com/mvdan/xurls)  | 456 |  从文本中提取url。 |![star > 100][Bronze]   ![最近一个周有更新][Green]

## 第三方api

*用于访问第三方api的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api)  | 39 |  [Amazon Product Advertising API](https://program.amazon.com/gp/advertising /api/detail/main.html)的客户端库。 |![最近一年没有更新][Yellow]
| [anaconda](https://github.com/ChimeraCoder/anaconda)  | 985 |   Twitter 1.1 API 的 go 语言客户端 |![star > 100][Bronze]   
| [aws-sdk-go](https://github.com/aws/aws-sdk-go)  | 4974 |  AWS 提供的官方go语言 SDK |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [brewerydb](https://github.com/naegelejd/brewerydb)  | 16 |  用于访问 BreweryDB API的 Go 语言库 |![最近一年没有更新][Yellow]
| [cachet](https://github.com/andygrunwald/cachet)  | 66 |  使用客户端库[Cachet(开源状态页系统)](https://cachethq.io/)。 |![最近一年没有更新][Yellow]
| [circleci](https://github.com/jszwedko/go-circleci)  | 41 |  CircleCI的API的客户端 |
| [clarifai](https://github.com/samuelcouch/clarifai)  | 57 |  Clarifai API的客户端。 |![最近一年没有更新][Yellow]
| [codeship-go](https://github.com/codeship/codeship-go)  | 14 |   Codeship API v2的客户端。 |
| [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client)  | 12 |  Coinpaprika API的客户端。 |
| [discordgo](https://github.com/bwmarrin/discordgo)  | 950 |   Discord Chat API的客户端。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [ethrpc](https://github.com/onrik/ethrpc)  | 163 |   Ethereum JSON RPC API的客户端。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [facebook](https://github.com/huandu/facebook)  | 765 |  支持 Facebook Graph API 的库 |![star > 100][Bronze]   
| [fcm](https://github.com/maddevsio/fcm)  | 32 |   Firebase Cloud Messaging 的 Go 语言库 |
| [gads](https://github.com/emiddleton/gads)  | 43 |   Google Adwords 非官方 API |
| [gami](https://github.com/bit4bit/gami)  | 26 |   Asterisk Manager Interface 的 Go 语言库 |![最近一年没有更新][Yellow]
| [gcm](https://github.com/Aorioli/gcm)  | 29 |   Google Cloud Messaging 库 |![最近一年没有更新][Yellow]
| [geo-golang](https://github.com/codingsince1985/geo-golang)  | 302 |  Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. |![star > 100][Bronze]   
| [github](https://github.com/google/go-github)  | 4716 |  访问GitHub REST API v3的库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [githubql](https://github.com/shurcooL/githubql)  | 494 |  访问GitHub GraphQL API v4的库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-chronos](https://github.com/axelspringer/go-chronos)  | 3 |  用于与[Chronos](https://mesos.github.io/chronos/)作业调度程序进行交互的Go库 |![最近一年没有更新][Yellow]
| [go-hacknews](https://github.com/PaulRosset/go-hacknews)  | 9 |  HackerNews API的小型Go客户端。 |![最近一年没有更新][Yellow]
| [go-imgur](https://github.com/koffeinsource/go-imgur)  | 13 |  Go [imgur](https://imgur.com)的客户端库 |
| [go-jira](https://github.com/andygrunwald/go-jira)  | 560 |   Go [Atlassian JIRA](https://www.atlassian.com/software/jira)的客户端库 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-marathon](https://github.com/gambol99/go-marathon)  | 188 |   用于和 Mesosphere's Marathon PAAS 交互的 Go 语言库 |![star > 100][Bronze]   
| [go-myanimelist](https://github.com/nstratos/go-myanimelist)  | 16 |  [MyAnimeList API](http://myanimelist.net/modules.php?go=api)的客户端库。 |![最近一年没有更新][Yellow]
| [go-sophos](https://github.com/esurdam/go-sophos)  | 5 |  无任何依赖的[Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/pdfs/documentation/utmonaws/sophos-ut-restful-api.pdf?la=en)客户端 |
| [go-sptrans](https://github.com/sergioaugrod/go-sptrans)  | 8 |   SPTrans Olho Vivo API 的客户端。 |![最近一年没有更新][Yellow]
| [go-telegraph](https://gitlab.com/toby3d/telegraph)  | - |  Telegraph 发布平台 API 客户端。 |
| [go-trending](https://github.com/andygrunwald/go-trending)  | 100 |  在Github上访问[trends repository](https://github.com/trends)和[developers](https://github.com/trending/developers)的库。 |![star > 100][Bronze]   
| [go-twitch](https://github.com/knspriggs/go-twitch)  | 16 |   Twitch v3 API 的客户端。 |![最近一年没有更新][Yellow]
| [go-twitter](https://github.com/dghubble/go-twitter)  | 699 |   Twitter v1.1 api 的客户端。。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-unsplash](https://github.com/hbagdi/go-unsplash)  | 20 |  使用[Unsplash.com](https://unsplash.com) API的客户端库。 |![最近一年没有更新][Yellow]
| [go-xkcd](https://github.com/nishanths/go-xkcd)  | 38 |   xkcd API 的客户端。 |![最近一年没有更新][Yellow]
| [golyrics](https://github.com/mamal72/golyrics)  | 29 |  Golyrics是一个从Wikia网站获取音乐歌词数据的Go库。 |![最近一年没有更新][Yellow]
| [gomalshare](https://github.com/MonaxGT/gomalshare)  | 1 |  Go library MalShare API [malshare.com](http://www.malshare.com/) |
| [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz)  | 36 |   Go MusicBrainz WS2客户端库。 |
| [google](https://github.com/google/google-api-go-client)  | 1905 |  为Go自动生成谷歌api。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [google-analytics](https://github.com/chonthu/go-google-analytics)  | 12 |  简单的包装，方便的谷歌分析报告。 |![最近一年没有更新][Yellow]
| [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang)  | 1753 |  谷歌云api Go 客户端库。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api)  | 6 |  [谷歌G Suite Email Audit API](https://developer.google.com/admin-sdk/email-audit/) 的客户端。 |![最近一年没有更新][Yellow]
| [gostorm](https://github.com/jsgilmore/gostorm)  | 118 |  GoStorm是一个Go库，它实现了编写Storm spout和bolt所需的通信协议，这些协议用于与Storm shell通信。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [hipchat](https://github.com/andybons/hipchat)  | 110 |  这个项目为Hipchat API实现了一个golang客户端库。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [hipchat (xmpp)](https://github.com/daneharrigan/hipchat)  | 113 |  一个用于通过XMPP与HipChat通信的golang包。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [igdb](https://github.com/Henry-Sarabia/igdb)  | 52 |  [Internet Game Database API](https://api.igdb.com/) 客户端。 |
| [Medium](https://github.com/Medium/medium-sdk-go)  | 115 |  Medium的OAuth2 API 客户端。 |![star > 100][Bronze]   
| [megos](https://github.com/andygrunwald/megos)  | 57 |  用于访问[Apache Mesos](http://mesos.apache.org/)集群的客户端库。 |![最近一年没有更新][Yellow]
| [minio-go](https://github.com/minio/minio-go)  | 710 |  用于Amazon S3兼容云存储的Minio Go库。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [mixpanel](https://github.com/dukex/mixpanel)  | 29 |  Mixpanel是一个库，用于跟踪事件并将Mixpanel概要文件更新从go应用程序发送到Mixpanel。 |
| [patreon-go](https://github.com/mxpv/patreon-go)  | 18 |   Go Patreon API库。 |
| [paypal](https://github.com/logpacker/PayPal-Go-SDK)  | 299 |  PayPal支付API的包装器。 |![star > 100][Bronze]   
| [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk)  | 1 |  Playlyfe Rest API Go SDK。 |![最近一年没有更新][Yellow]
| [pushover](https://github.com/gregdel/pushover)  | 57 |   Go 包装的 Pushover API。 |
| [rrdaclient](https://github.com/Omie/rrdaclient)  | 8 |  用于接入 statdns.com API 的库——RRDA API。通过HTTP协议进行 DNS查询。 |![最近一年没有更新][Yellow]
| [shopify](https://github.com/rapito/go-shopify)  | 19 |  一个用于通过 Shopify API 进行增删改查的 Go 语言库。 |![最近一年没有更新][Yellow]
| [simples3](https://github.com/rhnvrm/simples3)  | 9 |  使用REST和用Go编写的V4签名的AWS S3库非常简单。 |
| [slack](https://github.com/nlopes/slack)  | 2379 |  Slack API。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [smite](https://github.com/sergiotapia/smitego)  | 10 |  对 Smite game API 的封装。 |![最近一年没有更新][Yellow]
| [spotify](https://github.com/rapito/go-spotify)  | 16 |   用于接入 Spotify WEB API 的 Go 语言库 |![最近一年没有更新][Yellow]
| [steam](https://github.com/sostronk/go-steam)  | 14 |   用于与Steam服务器进行交互的库。 |![最近一年没有更新][Yellow]
| [stripe](https://github.com/stripe/stripe-go)  | 931 |   Stripe API 的 Go 语言客户端 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [textbelt](https://github.com/dietsche/textbelt)  | 14 |  textbelt.com txt messaging API 的go语言客户端。 |![最近一年没有更新][Yellow]
| [TheMovieDb](https://github.com/jbrodriguez/go-tmdb)  | 12 |  能与[themoviedb.org](https://themoviedb.org)简易通信的golang包。 |![最近一年没有更新][Yellow]
| [translate](https://github.com/poorny/translate)  | 27 |   Go 在线翻译包。 |![最近一年没有更新][Yellow]
| [Trello](https://github.com/adlio/trello)  | 100 |   Trello API的 Go 语言封装。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang)  | 1 |   TripAdvisor API 的 Go 语言封装。 |
| [tumblr](https://github.com/mattcunningham/gumblr)  | 6 |   Tumblr v2 API 的 Go 语言封装。 |![最近一年没有更新][Yellow]
| [uptimerobot](https://github.com/bitfield/uptimerobot)  | 34 |  运行时Robot v2 API 的 Go 语言封装和命令行客户端。 |
| [webhooks](https://github.com/go-playground/webhooks)  | 340 |  GitHub 和 Bitbucket 的Webhook接收器。 |![star > 100][Bronze]   
| [wit-go](https://github.com/wit-ai/wit-go)  | 45 |  wit.ai HTTP API 客户端。 |
| [ynab](https://github.com/brunomvsouza/ynab.go)  | 12 |   YNAB API 的 Go 语言封装。 |
| [zooz](https://github.com/gojuno/go-zooz)  | 5 |   Zooz API 的 Go 语言客户端。 |

## 公用事业公司

*可以让你的生活变得更简单的实用工具.。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [abutil](https://github.com/bahlo/abutil)  | 51 |  常用 Go 语言工具的集合。 |![最近一年没有更新][Yellow]
| [apm](https://github.com/topfreegames/apm)  | 126 |  Go 语言进程管理工具具有HTTP API.。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [backscanner](https://github.com/icza/backscanner)  | 8 |  类似 bufio 的扫描器，但它以相反的顺序读取和返回行，从给定的位置开始，然后返回。 |
| [blank](https://github.com/Henry-Sarabia/blank)  | 1 |  验证或删除字符串中的空白。 |
| [boilr](https://github.com/tmrts/boilr)  | 925 |  非常快的CLI工具，用于从样板模板创建项目。 |![star > 100][Bronze]   
| [chyle](https://github.com/antham/chyle)  | 106 |  使用具有多种配置可能性的git存储库生成变更日志。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [circuit](https://github.com/cep21/circuit)  | 321 |  一个高效和功能齐全的 类似 Hystrix Go 实现断路器模式。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [circuitbreaker](https://github.com/rubyist/circuitbreaker)  | 782 |  接通断路器。 |![star > 100][Bronze]   
| [clockwork](https://github.com/jonboulle/clockwork)  | 219 |  一个简单的假 clock 。 |![star > 100][Bronze]   
| [command](https://github.com/txgruppi/command)  | 9 |  命令模式，支持线程安全的串行、并行调度。 |![最近一年没有更新][Yellow]
| [copy-pasta](https://github.com/jutkko/copy-pasta)  | 36 |  通用多工作站剪切板，使用类似 S3 的后端作为存储。 |
| [ctop](https://github.com/bcicen/ctop)  | 8733 |  [Top-like](http://ctop.sh)接口(例如htop)， 用于容器数据收集。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [ctxutil](https://github.com/posener/ctxutil)  | 6 |  上下文工具。 |
| [dbt](https://github.com/nikogura/dbt)  | 10 |  用于从中心可信存储库运行自更新签名二进制文件的框架。 |
| [Death](https://github.com/vrecan/death)  | 132 |  利用信号管理应用程序的关闭。 |![star > 100][Bronze]   
| [Deepcopier](https://github.com/ulule/deepcopier)  | 207 |  结构体拷贝 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [delve](https://github.com/derekparker/delve)  | 11837 |  Go 语言调试器 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [dlog](https://github.com/kirillDanshin/dlog)  | 15 |  编译时控制的日志，让你的 release 包变得更小而不需移除 debug 调用。 |![最近一年没有更新][Yellow]
| [ergo](https://github.com/cristianoliveira/ergo)  | 309 |  管理运行在不同端口上的多个本地服务变得很容易。 |![star > 100][Bronze]   
| [evaluator](https://github.com/nullne/evaluator)  | 14 |  基于 s-expression。它很简单，很容易扩展。 |![最近一年没有更新][Yellow]
| [fastlz](https://github.com/digitalcrab/fastlz)  | 12 |  [FastLz](http://fastlz.org/)(免费，开源，可移植实时压缩库) 的一个封装 |![最近一年没有更新][Yellow]
| [filetype](https://github.com/h2non/filetype)  | 929 |  通过数字签名来推测文件类型。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [filler](https://github.com/yaronsumel/filler)  | 14 |  使用“fill”标签填充结构的小工具。 |![最近一年没有更新][Yellow]
| [filter](https://github.com/gookit/filter)  | 11 |  提供Go数据的过滤、清理和转换。 |
| [fzf](https://github.com/junegunn/fzf)  | 22747 |  用Go编写的命令行模糊查找器。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [gaper](https://github.com/maxcnunes/gaper)  | 38 |  当Go项目崩溃或一些人看到文件更改时，构建并重新启动该项目。 |
| [generate](https://github.com/go-playground/generate)  | 19 |  针对一个路径或环境变量，递归的执行 Go generate，可以通过正则表达式来进行过滤。 |![最近一年没有更新][Yellow]
| [ghokin](https://github.com/antham/ghokin)  | 12 |  没有外部依赖的gherkin (cucumber, behat…)并行格式化程序。 |
| [git-time-metric](https://github.com/git-time-metric/gtm)  | 711 |  git-time-metric - 。 |![star > 100][Bronze]   
| [go-astitodo](https://github.com/asticode/go-astitodo)  | 45 |  解析你 Go 语言代码中的 TODOs（待办事项）。 |
| [go-bind-plugin](https://github.com/wendigo/go-bind-plugin)  | 159 |  Go:generate 工具，用于构建 Go 语言插件(1.8 only)，并对导出的符号进行包装。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-bsdiff](https://github.com/gabstv/go-bsdiff)  | 81 |  纯Go bsdiff和bspatch库和CLI工具。 |
| [go-dry](https://github.com/ungerik/go-dry)  | 432 |  DRY(don't repeat yourself)库。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-funk](https://github.com/thoas/go-funk)  | 1134 |  现代 Go 语言工具库，提供了很多有用的工具 (map, find, contains, filter, chunk, reverse, ...) |![star > 1000][Silver]   
| [go-health](https://github.com/Talento90/go-health)  | 62 |  健康包简化了向服务中添加健康检查的方式。 |![最近一年没有更新][Yellow]
| [go-httpheader](https://github.com/mozillazg/go-httpheader)  | 14 |   用于将结构体编码进 http 头的 Go 语言库 |
| [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails)  | 2 |  打包处理问题细节。 |
| [go-rate](https://github.com/beefsack/go-rate)  | 291 |   Go 限速器。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator)  | 103 |  用Go编写的XML站点地图生成器。 |![star > 100][Bronze]   
| [go-torch](https://github.com/uber/go-torch)  | 3625 |  为 Go 语言程序生成火焰图。 |![star > 1000][Silver]   
| [go-trigger](https://github.com/sadlil/go-trigger)  | 180 |  Go 语言全局事件触发器，通过 id 和触发器，在程序的任何地方注册事件。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [goback](https://github.com/carlescere/goback)  | 39 |   一个 Go 语言的简单的指数补偿包。 |![最近一年没有更新][Yellow]
| [godaemon](https://github.com/VividCortex/godaemon)  | 402 |  用于编写守护进程的工具 |![star > 100][Bronze]   
| [godropbox](https://github.com/dropbox/godropbox)  | 3733 |  用于编写 Go 语言服务／应用的库，来自 Dropbox.。 |![star > 1000][Silver]   
| [gohper](https://github.com/cosiner/gohper)  | 248 |  多种能够帮助你进行软件开发的工具和模块。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [golarm](https://github.com/msempere/golarm)  | 34 |  告警（支持系统事件）。 |![最近一年没有更新][Yellow]
| [golog](https://github.com/mlimaloureiro/golog)  | 43 |  简单、轻量级的命令后工具，用于对你的计划任务进行跟踪。 |
| [gopencils](https://github.com/bndr/gopencils)  | 423 |  小而简单的包，可以轻松地使用REST api。 |![star > 100][Bronze]   
| [goplaceholder](https://github.com/michiwend/goplaceholder)  | 22 |  一个小巧的 Go 语言库用于生成占位图片。 |![最近一年没有更新][Yellow]
| [goreadability](https://github.com/philipjkim/goreadability)  | 28 |  网页摘要提取器使用Facebook开放图形和arc90的可读性。 |
| [goreleaser](https://github.com/goreleaser/goreleaser)  | 4445 |  尽可能快速的发布 Go 语言二进制文件。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [goreporter](https://github.com/wgliang/goreporter)  | 2466 |  进行代码静态分析，单元测试，代码检视并生成代码质量报告的工具 |![star > 1000][Silver]   
| [goseaweedfs](https://github.com/linxGnu/goseaweedfs)  | 27 |  conseilSeaweedFS 客户端，几乎具有全部的特性。 |
| [gostrutils](https://github.com/ik5/gostrutils)  | 14 |  字符串操作和转换函数的集合。 |
| [gotenv](https://github.com/subosito/gotenv)  | 137 |  从 `.env` 或者任何 `io.Reader`。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [gpath](https://github.com/tenntenn/gpath)  | 25 |   用于简化结构体域访问的库。 |![最近一年没有更新][Yellow]
| [gubrak](https://github.com/novalagung/gubrak)  | 135 |  带有语法糖的Golang实用工具，就像lodash。 |![star > 100][Bronze]   
| [handy](https://github.com/miguelpragier/handy)  | 44 |  许多实用程序和帮助程序，如字符串处理程序/格式化程序和验证器。 |
| [htcat](https://github.com/htcat/htcat)  | 479 |  并行及流水线的 HTTP GET 工具。 |![star > 100][Bronze]   
| [hub](https://github.com/github/hub)  | 16786 |  封装了 git 命令，提供了额外的功能用于在终端中和 Github 进行交互。 |![star > 5000][Gold]   
| [hystrix-go](https://github.com/afex/hystrix-go)  | 1973 |  实现 Hystrix 风格的、程序员预定义的 fallback 机制（熔断。 |![star > 1000][Silver]   
| [immortal](https://github.com/immortal/immortal)  | 601 |  \*nix 跨平台 (与操作系统无关的)监控程序。 |![star > 100][Bronze]   
| [intrinsic](https://github.com/mengzhuo/intrinsic)  | 39 |  不需要编写任何汇编代码就能使用 x86 SIMD。 |![最近一年没有更新][Yellow]
| [jump](https://github.com/gsamokovarov/jump)  | 647 |  通过学习你的习惯，可以帮助你更快地导航。 |![star > 100][Bronze]   
| [koazee](https://github.com/wesovilabs/koazee)  | 286 |  库的灵感来自于延迟计算和函数式编程，从而减少了使用数组的麻烦。 |![star > 100][Bronze]   
| [lrserver](https://github.com/jaschaephraim/lrserver)  | 100 |  LiveReload 服务器。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [mc](https://github.com/minio/mc)  | 1087 |  Minio Client 提供了一组工具，用于操作 Amazon S3 兼容云存储和文件系统。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [mergo](https://github.com/imdario/mergo)  | 830 |  用于将结构体和map合并进 Go 语言的工具。对于配置默认值，避免杂乱的if语句很有帮助。 |![star > 100][Bronze]   
| [mimemagic](https://github.com/zRedShift/mimemagic)  | 42 |  纯粹 Go 超性能MIME嗅探库/实用程序。 |
| [mimesniffer](https://github.com/aofei/mimesniffer)  | 7 |  一个用于Go的MIME类型嗅探器。 |
| [mimetype](https://github.com/gabriel-vasile/mimetype)  | 104 |  用于基于神奇数字的MIME类型检测的包。 |![star > 100][Bronze]   
| [minify](https://github.com/tdewolff/minify)  | 1849 |  用于HTML、CSS、JS、XML、JSON和SVG文件格式的快速缩小器。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [minquery](https://github.com/icza/minquery)  | 50 |  MongoDB / mgo.v2, 支持高效分页查询(用于继续列出我们停止的文档的游标)。 |
| [mmake](https://github.com/tj/mmake)  | 1449 |  现代 Make 工具 |![star > 1000][Silver]   
| [moldova](https://github.com/StabbyCutyou/moldova)  | 148 |  基于输入目标生成随机数据的工具 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [mole](https://github.com/davrodpin/mole)  | 1296 |  cli应用程序可以轻松创建ssh隧道。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [mssqlx](https://github.com/linxGnu/mssqlx)  | 57 |  数据库客户端，用于主-从 (或主-主) 数据库，集成了简单的、轻量级的轮询调度负载均衡。 |
| [multitick](https://github.com/VividCortex/multitick)  | 58 |  用于 aligned tickers 的多路复用 |![最近一年没有更新][Yellow]
| [myhttp](https://github.com/inancgumus/myhttp)  | 34 |  简单的API，使HTTP GET请求与超时支持。 |![最近一年没有更新][Yellow]
| [netbug](https://github.com/e-dard/netbug)  | 65 |  远程对你的服务进行性能分析 |![最近一年没有更新][Yellow]
| [okrun](https://github.com/xta/okrun)  | 14 |   Go 运行错误 steamroller。 |![最近一年没有更新][Yellow]
| [olaf](https://github.com/btnguyen2k/olaf)  | 1 |  Twitter Snowflake 在Go中实现。 |
| [onecache](https://github.com/adelowo/onecache)  | 99 |  支持多个后端存储(Redis、Memcached、文件系统等)的缓存库。 |
| [panicparse](https://github.com/maruel/panicparse)  | 2094 |  将类似的协程分组并对调用栈进行着色 |![star > 1000][Silver]   
| [peco](https://github.com/peco/peco)  | 5419 |  简单的交互过滤工具。 |![star > 5000][Gold]   
| [pgo](https://github.com/arthurkushman/pgo)  | 24 |  用于PHP社区的 Convenient 函数。 |
| [pm](https://github.com/VividCortex/pm)  | 71 |  进程(即goroutine)管理器与HTTP API。 |
| [profile](https://github.com/pkg/profile)  | 991 |  Go的简单分析支持包。 |![star > 100][Bronze]   
| [rclient](https://github.com/zpatrick/rclient)  | 27 |  可读、灵活、易于使用的REST api客户端。 |
| [realize](https://github.com/tockins/realize)  | 3112 |  Go 语言构建系统，可以监控文件变化并重新加载。运行，构建，监控文件并支持自定义路径。 |![star > 1000][Silver]   
| [repeat](https://github.com/ssgreg/repeat)  | 56 |  执行不同的后 backoff 策略，这对重新尝试操作和心跳非常有用。 |
| [request](https://github.com/mozillazg/request)  | 355 |  Go 语言版的 HTTP Requests for Humans™.。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [rerate](https://github.com/abo/rerate)  | 12 |  基于 Redis 的速率计数器和限速器 |![最近一年没有更新][Yellow]
| [rerun](https://github.com/ivpusic/rerun)  | 153 |  当源代码发生更改时，重新编译和重新运行go应用程序。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [resty](https://github.com/go-resty/resty)  | 1846 |  简单的 HTTP 和 REST 客户端，受到 Ruby rest-client 的启发。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [retry](https://github.com/kamilsk/retry)  | 144 |  基于上下文的功能机制，反复执行命令直到成功。 |![star > 100][Bronze]   
| [retry](https://github.com/percolate/retry)  | 2 |  一个简单但高度可配置的Go重试包。 |
| [retry](https://github.com/thedevsaddam/retry)  | 34 |  简单易用的重试机制包，为 Go 。 |![最近一年没有更新][Yellow]
| [retry](https://github.com/shafreeck/retry)  | 9 |  一个相当简单的库，以确保您的工作可以完成。 |
| [retry-go](https://github.com/rafaeljesus/retry-go)  | 26 |  对 Go 来说，重试变得简单而容易。 |
| [robustly](https://github.com/VividCortex/robustly)  | 133 |  有弹性的执行函数，遇到错误时捕获并重新运行。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [scan](https://github.com/blockloop/scan)  | 11 |  扫描golang的sql。行直接指向结构、片或基本类型。 |![最近一个周有更新][Green]
| [serve](https://github.com/syntaqx/serve)  | 190 |  任何您需要的静态http服务器。 |![star > 100][Bronze]   
| [silk](https://github.com/chrispassas/silk)  | 4 |  阅读silk netflow文件。 |
| [sliceconv](https://github.com/Henry-Sarabia/sliceconv)  | 2 |  基本类型之间的片转换。 |
| [slicer](https://github.com/leaanthony/slicer)  | 3 |  使处理切片更容易。 |
| [spinner](https://github.com/briandowns/spinner)  | 774 |   一个 Go 语言软件包，提供多种选项，方便在终端中创建加载动画。 |![star > 100][Bronze]   
| [sqlx](https://github.com/jmoiron/sqlx)  | 6675 |  为内建的数据库/sql 软件包提供一组扩展。 |![star > 5000][Gold]   
| [sslice](https://github.com/yaa110/sslice)  | 4 |  创建一个总是排序的切片。 |![最近一个周有更新][Green]
| [Storm](https://github.com/asdine/storm)  | 1338 |  一个简单又强大的用于 BoltDB 的工具 |![star > 1000][Silver]   
| [structs](https://github.com/PumpkinSeed/structs)  | 12 |  简单来讲就是 "Make" 的替代品。 |![最近一年没有更新][Yellow]
| [Task](https://github.com/go-task/task)  | 1874 |  简单的“Go”的选择。 |![star > 1000][Silver]   
| [toolbox](https://github.com/viant/toolbox)  | 88 |  切片, map, multimap, 结构体, 函数,数据转换工具。服务路由，宏求值和标记器。 |
| [tracer](https://github.com/kamilsk/tracer)  | 5 |  简单、轻量级的跟踪。 |![最近一个周有更新][Green]
| [ugo](https://github.com/alxrm/ugo)  | 20 |  uGo 是一个切片工具箱，有着和 Go 语言一致的语法法。 |![最近一年没有更新][Yellow]
| [UNIS](https://github.com/esemplastic/unis)  | 69 |  Go 语言字符串处理函数的通用架构 。 |![最近一年没有更新][Yellow]
| [usql](https://github.com/knq/usql)  | 4656 |  usql 是一个通用的命令行接口，用于操作 sql 数据库。 |![star > 1000][Silver]   
| [util](https://github.com/shomali11/util)  | 132 |  有用实用函数的集合。(字符串，并发，操作，…) |![star > 100][Bronze]   
| [wuzz](https://github.com/asciimoo/wuzz)  | 8244 |  用于HTTP检查的交互式cli工具。 |![star > 5000][Gold]   
| [xferspdy](https://github.com/monmohan/xferspdy)  | 68 |  Xferspdy在golang中提供二进制diff和补丁库。 |![最近一年没有更新][Yellow]

## UUID

*用于处理uuid的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [goid](https://github.com/jakehl/goid)  | 20 |  生成和解析RFC4122兼容的V4 uuid。 |
| [nanoid](https://github.com/aidarkhanov/nanoid)  | 3 |  一个小而有效的Go唯一字符串ID生成器。 |
| [sno](https://github.com/muyo/sno)  | 14 |  使用嵌入元数据的紧凑、可排序和快速的惟一id。 |
| [ulid](https://github.com/oklog/ulid)  | 1658 |  实现了ULID(普遍唯一的词典分类标识符)。 |![star > 1000][Silver]   
| [uniq](https://gitlab.com/skilstak/code/uniq/go)  | - |  没有麻烦，安全，快速的唯一标识符与命令。 |
| [uuid](https://github.com/agext/uuid)  | 10 |  使用快速或加密质量的随机节点标识符生成、编码和解码UUIDs v1。 |
| [uuid](https://github.com/gofrs/uuid)  | 561 |  通用唯一标识符(UUID)的实现。支持uuid的创建和解析。积极维护satori uuid的fork。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [wuid](https://github.com/edwingeng/wuid)  | 279 |  一个非常快的唯一数字生成器，比UUID快10-135倍。 |![star > 100][Bronze]   

## 验证

*库进行验证。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [checkdigit](https://github.com/osamingo/checkdigit)  | 44 |  提供校验数字算法(Luhn, Verhoeff, Damm)和计算器(ISBN, EAN, JAN, UPC等)。 |
| [govalidator](https://github.com/asaskevich/govalidator)  | 3515 |  用于字符串，数字，切片和结构的验证器和sanitizers。 |![star > 1000][Silver]   
| [govalidator](https://github.com/thedevsaddam/govalidator)  | 707 |  用简单的规则验证Golang请求数据。深受Laravel请求验证的启发。 |![star > 100][Bronze]   
| [jio](https://github.com/faceair/jio)  | 21 |  jio是一个json模式验证器，类似于[joi](https://github.com/hapijs/joi)。 |
| [ozzo-validation](https://github.com/go-ozzo/ozzo-validation)  | 1021 |  支持各种数据类型(结构、字符串、映射、片等)的验证，使用可配置和可扩展的验证规则，这些规则在通常的代码构造中指定，而不是在结构标签中指定。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [validate](https://github.com/gookit/validate)  | 89 |   Go 封装数据验证和过滤。支持验证映射、结构、请求(表单、JSON、url)。值，上载文件)数据和更多特性。 |
| [validate](https://github.com/gobuffalo/validate)  | 19 |  这个包提供了一个框架，用于为Go应用程序编写验证。 |
| [validator](https://github.com/go-playground/validator)  | 3400 |   Go 结构体及域验证，包括：跨域、跨结构体, Map, 切片和数组。 |![star > 1000][Silver]   ![最近一个周有更新][Green]

## 版本控制

*用于版本控制的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gh](https://github.com/rjeczalik/gh)  | 68 |  用于GitHub webhook的可编写脚本的服务器和net/http中间件。 |
| [git2go](https://github.com/libgit2/git2go)  | 1347 |   libgit2 的 Go 语言接口。 |![star > 1000][Silver]   
| [go-git](https://github.com/src-d/go-git)  | 4148 |  纯Go中高度可扩展的Git实现。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [go-vcs](https://github.com/sourcegraph/go-vcs)  | 69 |  在Go中操作和检查VCS存储库。 |![最近一个周有更新][Green]
| [hercules](https://github.com/src-d/hercules)  | 510 |  从Git存储库历史中获得高级见解。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [hgo](https://github.com/beyang/hgo)  | 12 |  Hgo是一组Go包的集合，提供对本地Mercurial存储库的读取访问。 |![最近一年没有更新][Yellow]

## 视频

*用于操作视频的库。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gmf](https://github.com/3d0c/gmf)  | 519 |   FFmpeg av\* 库的 Go 语言接口。 |![star > 100][Bronze]   
| [go-astisub](https://github.com/asticode/go-astisub)  | 163 |  使用 Go 语言操作字幕(.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.)。 |![star > 100][Bronze]   
| [go-astits](https://github.com/asticode/go-astits)  | 257 |  在GO中解析和演示MPEG传输流(.ts)。 |![star > 100][Bronze]   
| [go-m3u8](https://github.com/quangngotan95/go-m3u8)  | 36 |  苹果m3u8播放列表的解析器和生成器库。 |
| [goav](https://github.com/giorgisio/goav)  | 765 |  FFmpeg的Comphrensive。 |![star > 100][Bronze]   
| [gst](https://github.com/ziutek/gst)  | 152 |   GStreamer的Go工具。 |![star > 100][Bronze]   
| [libgosubs](https://github.com/wargarblgarbl/libgosubs)  | 11 |  字幕格式支持 .srt、.ttml和.ass。 |
| [libvlc-go](https://github.com/adrg/libvlc-go)  | 61 |  Go绑定libvlc 2.X/3.X/4。X(由VLC媒体播放器使用)。 |![最近一个周有更新][Green]
| [v4l](https://github.com/korandiz/v4l)  | 27 |  用于Linux的视频捕捉库，用Go编写。 |![最近一年没有更新][Yellow]

## Web框架

*全栈 web 框架。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [aah](https://aahframework.org)  | - |  可伸缩、高性能、快速开发的Go Web框架。 |
| [Aero](https://github.com/aerogo/aero)  | 154 |  高性能的Go web框架，在Lighthouse中达到最高分。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [Air](https://github.com/aofei/air)  | 516 |  一个理想的精细化的Go web框架。 |![star > 100][Bronze]   
| [Banjo](https://github.com/nsheremet/banjo)  | 7 |  非常简单和快速的网络框架 Go 。 |![最近一年没有更新][Yellow]
| [Beego](https://github.com/astaxie/beego)  | 21202 |  beego是一种用于 Go 编程语言的开源高性能web框架。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [Buffalo](http://gobuffalo.io)  | - |  为 Go 语言带来堪比 Rails 的高生产效率! |
| [Echo](https://github.com/labstack/echo)  | 14491 |  高性能、极简的Go web框架。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [Fireball](https://github.com/zpatrick/fireball)  | 48 |  感觉更加自然的 web 框架。 |
| [Gem](https://github.com/go-gem/gem)  | 153 |  简单快速的web框架，对REST API友好。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Gin](https://github.com/gin-gonic/gin)  | 29245 |  Gin是一个用Go编写的web框架!它具有一个类似于martini的API，性能更好，速度快40倍。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [Gizmo](https://github.com/NYTimes/gizmo)  | 2824 |  《纽约时报》使用的微服务工具包。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [go-json-rest](https://github.com/ant0ine/go-json-rest)  | 3322 |  设置RESTful JSON API的快速简便方法。 |![star > 1000][Silver]   
| [go-rest](https://github.com/ungerik/go-rest)  | 115 |  小型的 REST 框架。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Goa](https://github.com/goadesign/goa)  | 3476 |  Goa为在Go中开发远程api和微服务提供了一种全面的方法。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [Golax](https://github.com/fulldump/golax)  | 71 |  一个非Sinatra快速HTTP框架，支持谷歌自定义方法、深度拦截器、递归等。 |![最近一年没有更新][Yellow]
| [Golf](https://github.com/dinever/golf)  | 235 |  Golf 是一个快速、简单、轻量级的 Go 语言微型 web 框架。具有强大的功能且没有标准库以外的依赖。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Gondola](https://github.com/rainycape/gondola)  | 314 |  web框架写的网站越快越好。 |![star > 100][Bronze]   
| [gongular](https://github.com/mustafaakin/gongular)  | 415 |   快速 Go web 框架，支持输入映射／验证以及依赖注入。 |![star > 100][Bronze]   
| [hiboot](https://github.com/hidevopsio/hiboot)  | 86 |  hiboot是一个高性能的web应用程序框架，支持自动配置和依赖注入。 |
| [Macaron](https://github.com/go-macaron/macaron)  | 2790 |  Macaron 是一个高效的模块化设计的web框架 |![star > 1000][Silver]   
| [mango](https://github.com/paulbellamy/mango)  | 339 |  ManGo 是一个模块化 web 应用框架，受到 Rack 和 PEP333 的启发。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Microservice](https://github.com/claygod/microservice)  | 56 |  创建微服务的框架，用Golang编写。 |
| [neo](https://github.com/ivpusic/neo)  | 393 |  Neo是一个非常简单且快速的Web框架API。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [nio](https://github.com/go-nio/nio)  | 21 |  现代的、最小的和高效的Go HTTP框架。 |
| [patron](https://github.com/beatlabs/patron)  | 33 |  Patron是一个遵循最佳云实践的微服务框架，专注于提升开发效率。 |![最近一个周有更新][Green]
| [Resoursea](https://github.com/resoursea/api)  | 29 |  用于快速编写基于资源的服务的REST框架。 |![最近一年没有更新][Yellow]
| [REST Layer](http://rest-layer.io)  | - |  框架，用于在数据库之上构建REST/GraphQL API，主要是通过代码进行配置。 |
| [Revel](https://github.com/revel/revel)  | 11207 |  用于Go语言的高效web框架。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [rex](https://github.com/goanywhere/rex)  | 25 |   Rex 是一个用于进行模块化开发的库，基于Gorilla/mux 完全兼容大多数的 net/HTTP. |![最近一年没有更新][Yellow]
| [sawsij](https://github.com/jaybill/sawsij)  | 2 |  轻量级、开源的web框架，用于构建高性能、数据驱动的web应用程序。 |![最近一年没有更新][Yellow]
| [tango](https://github.com/lunny/tango)  | 816 |  微型的、支持插件的 web 框架。 |![star > 100][Bronze]   
| [tigertonic](https://github.com/rcrowley/go-tigertonic)  | 995 |  用于构建 JSON web 服务的 Go 语言框架，受到 Dropwizard 的启发。 |![star > 100][Bronze]   
| [traffic](https://github.com/pilu/traffic)  | 519 |  Sinatra启发了regexp/pattern mux和用于Go的web框架。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [uAdmin](https://github.com/uadmin/uadmin)  | 49 |  受到 Sinatra 启发的 Go 语言 web 框架。 |![最近一个周有更新][Green]
| [utron](https://github.com/gernest/utron)  | 2135 |  Go(Golang)的轻量级MVC框架。 |![star > 1000][Silver]   
| [vox](https://github.com/aisk/vox)  | 39 |  一个面向人类的golang web框架，深受Koa的启发。 |
| [WebGo](https://github.com/bnkamalesh/webgo)  | 73 |  构建web应用程序的微框架;处理程序链接、中间件和上下文注入。与标准库兼容的HTTP处理程序(即http.HandlerFunc)。 |
| [YARF](https://github.com/yarf-framework/yarf)  | 50 |  快速微框架，旨在以快速和简单的方式构建REST api和web服务。 |
| [Zerver](https://github.com/cosiner/zerver)  | - |  Zerver是一个表现力强、模块化、功能完备的RESTful框架。 |

### 中间件

#### 仿真中间件

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [client-timing](https://github.com/posener/client-timing)  | 13 |  用于服务器定时报头的HTTP客户机。 |
| [CORS](https://github.com/rs/cors)  | 1197 |  轻松地向API添加CORS功能。 |![star > 1000][Silver]   
| [formjson](https://github.com/rs/formjson)  | 33 |  透明地将JSON输入作为标准表单POST处理。 |![最近一年没有更新][Yellow]
| [go-server-timing](https://github.com/mitchellh/go-server-timing)  | 743 |  添加/解析Server-Timing头。 |![star > 100][Bronze]   
| [Limiter](https://github.com/ulule/limiter)  | 776 |  简单的速度限制中间件。 |![star > 100][Bronze]   
| [ln-paywall](https://github.com/philippgille/ln-paywall)  | 86 |  使用Lightning Network(比特币)实现基于每个请求的api货币化中间件。 |
| [Tollbooth](https://github.com/didip/tollbooth)  | 1232 |  限制速率的 HTTP 请求处理程序。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [XFF](https://github.com/sebest/xff)  | 72 |  处理 X-Forwarded-For 头的中间件。 |

#### 用于创建HTTP中间件的库

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [alice](https://github.com/justinas/alice)  | 1814 |  用于连接中间件的库，简单无痛苦。 |![star > 1000][Silver]   
| [catena](https://github.com/codemodus/catena)  | 7 |  HTTP.Handler wrapper catenation (和chain具有相同的 API ).。 |
| [chain](https://github.com/codemodus/chain)  | 63 |  带有范围数据的处理程序包装器链接(基于网络/上下文的“中间件”)。 |
| [go-wrap](https://github.com/go-on/wrap)  | 58 |  net/http的小型中间件包。 |
| [gores](https://github.com/alioygur/gores)  | 81 |  处理HTML、JSON、XML等响应的Go包。对于RESTful api非常有用。 |
| [interpose](https://github.com/carbocation/interpose)  | 289 |  golang的极简网络/http中间件。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [muxchain](https://github.com/stephens2424/muxchain)  | 207 |  用于net/http的轻量级中间件。 |![star > 100][Bronze]   
| [negroni](https://github.com/urfave/negroni)  | 6301 |  符合语言习惯的 HTTP 中间件库。 |![star > 5000][Gold]   
| [render](https://github.com/unrolled/render)  | 1262 |  Go package用于方便地呈现JSON、XML和HTML模板响应。 |![star > 1000][Silver]   
| [renderer](https://github.com/thedevsaddam/renderer)  | 167 |  简单、轻量级和更快的响应(JSON、JSONP、XML、YAML、HTML、文件)。 |![star > 100][Bronze]   
| [rye](https://github.com/InVisionApp/rye)  | 92 |  支持JWT、CORS、Statsd和Go 1.7上下文的小型Go中间件库(带有罐装中间件)。 |
| [stats](https://github.com/thoas/stats)  | 536 |  使用中间件来存储关于web应用程序的各种信息。 |![star > 100][Bronze]   

### 路由器

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [alien](https://github.com/gernest/alien)  | 105 |  轻量级和快速http路由器从外层空间。 |![star > 100][Bronze]   
| [bellt](https://github.com/GuilhermeCaruso/bellt)  | 38 |  一个简单的Go HTTP路由器。 |
| [Bone](https://github.com/go-zoo/bone)  | 1217 |  闪电快速HTTP多路复用器。 |![star > 1000][Silver]   
| [Bxog](https://github.com/claygod/Bxog)  | 93 |  简单和快速的HTTP路由器 Go 。它可以处理不同难度、长度和嵌套的路径。他还知道如何根据接收到的参数创建URL。 |
| [chi](https://github.com/go-chi/chi)  | 5934 |  小巧、快速、具有丰富表达力的 HTTP 路由，基于net/context.。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [fasthttprouter](https://github.com/buaazp/fasthttprouter)  | 741 |  高性能路由器分叉从`httprouter`。第一个路由器适合`fasthttp`。 |![star > 100][Bronze]   
| [FastRouter](https://github.com/razonyang/fastrouter)  | 18 |  一个快速，灵活的HTTP路由器写在Go。 |![最近一年没有更新][Yellow]
| [gocraft/web](https://github.com/gocraft/web)  | 1393 |  Mux和中间件包在Go中。 |![star > 1000][Silver]   
| [Goji](https://github.com/goji/goji)  | 764 |  枸杞是一种简约的和灵活的与支持'net/context` HTTP请求多路复用器。 |![star > 100][Bronze]   
| [GoRouter](https://github.com/vardius/gorouter)  | 49 |  GoRouter 是一个服务器/API 微型框架、HTTP 请求路由 router, 数据分选器，提供了支持net/context的中间件。 |
| [gowww/router](https://github.com/gowww/router)  | 157 |  超快的HTTP 路由，完全兼容 net/HTTP.Handler 接口.。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [httprouter](https://github.com/julienschmidt/httprouter)  | 9570 |  高性能路由。使用这个库和标准http处理工具可以构建一个非常高性能大web框架。 |![star > 5000][Gold]   
| [httptreemux](https://github.com/dimfeld/httptreemux)  | 384 |  高速，灵活，基于树的 HTTP 路由。受到了 httprouter 的启发。 |![star > 100][Bronze]   
| [lars](https://github.com/go-playground/lars)  | 375 |  是一个轻量级、快速、可扩展、零分配的HTTP路由，用于创建定制化的框架。 |![star > 100][Bronze]   
| [mux](https://github.com/gorilla/mux)  | 9520 |  强大的URL路由器和调度器为golang。 |![star > 5000][Gold]   
| [ozzo-routing](https://github.com/go-ozzo/ozzo-routing)  | 357 |  一个非常快的Go (golang) HTTP路由器，支持正则表达式路由匹配。完全支持构建RESTful api。 |![star > 100][Bronze]   
| [pure](https://github.com/go-playground/pure)  | 84 |  是一个轻量级HTTP路由器，它坚持net/ HTTP“实现”的std。 |
| [Siesta](https://github.com/VividCortex/siesta)  | 348 |  编写中间件和处理程序的可组合框架。 |![star > 100][Bronze]   
| [vestigo](https://github.com/husobee/vestigo)  | 250 |  高性能，独立，HTTP兼容的URL路由器的go web应用程序。 |![star > 100][Bronze]   
| [violetear](https://github.com/nbari/violetear)  | 94 |  HTTP路由器。 |
| [xmux](https://github.com/rs/xmux)  | 87 |  高性能mux基于httprouter 'net/context`支持。 |![最近一年没有更新][Yellow]
| [xujiajun/gorouter](https://github.com/xujiajun/gorouter)  | 446 |  一个简单和快速的HTTP路由器 Go 。 |![star > 100][Bronze]   

## Windows

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [d3d9](https://github.com/gonutz/d3d9)  | 85 |   Direct3D9 的 Go 语言接口。 |
| [go-ole](https://github.com/go-ole/go-ole)  | 547 |  为 Go 语言实现的 Win32 OLE。 |![star > 100][Bronze]   
| [gosddl](https://github.com/MonaxGT/gosddl)  | 1 |  从SDDL-string到用户友好的JSON的转换器。SDDL由四个部分组成:所有者、主群、DACL、SACL。 |

## XML

*用于操作XML的库和工具。*

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [XML-Comp](https://github.com/xml-comp/xml-comp)  | 15 |  简单的命令行XML比较器，生成文件夹、文件和标记的差异。 |![最近一年没有更新][Yellow]
| [xml2map](https://github.com/sbabiv/xml2map)  | 15 |  XML来映射转换器编写的Golang。 |
| [xmlwriter](https://github.com/shabbyrobe/xmlwriter)  | 6 |  基于libxml2的xmlwriter模块的过程性XML生成API。 |
| [xpath](https://github.com/antchfx/xpath)  | 157 |  Go的XPath包。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [xquery](https://github.com/antchfx/xquery)  | 145 |  XQuery允许您使用XPath表达式从HTML/XML文档中提取数据。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [zek](https://github.com/miku/zek)  | 248 |  从XML生成Go结构。 |![star > 100][Bronze]   

# 工具

* Go 软件和插件。*

## 代码分析

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [apicompat](https://github.com/bradleyfalzon/apicompat)  | 165 |  检查 Go 项目最近的向下不兼容修改。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [dupl](https://github.com/mibk/dupl)  | 167 |  用于代码克隆检测的工具。 |![star > 100][Bronze]   
| [errcheck](https://github.com/kisielk/errcheck)  | 1314 |  Errcheck是一个用于检查Go程序中未检查错误的程序。 |![star > 1000][Silver]   
| [gcvis](https://github.com/davecheney/gcvis)  | 913 |  实时可视化跟踪 GC 数据。 |![star > 100][Bronze]   
| [go-checkstyle](https://github.com/qiniu/checkstyle)  | 95 |  checkstyle是一个类似于java checkstyle的检查工具。 |
| [go-cleanarch](https://github.com/roblaszczak/go-cleanarch)  | 280 |  go-cleanarch 的创建是为了验证 Clean 体系结构规则，比如 Go 项目中的依赖关系。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-critic](https://github.com/go-critic/go-critic)  | 563 |  源代码检查工具。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-mod-outdated](https://github.com/psampaz/go-mod-outdated)  | 180 |  找出项目中过期的依赖项。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-outdated](https://github.com/firstrow/go-outdated)  | 45 |  显示过期包的终端应用。 |
| [goast-viewer](https://github.com/yuroyoro/goast-viewer)  | 368 |  基于 Web 的 Golang AST 可视化工具。 |![star > 100][Bronze]   
| [GoCover.io](http://gocover.io/)  | - |  GoCover.io 提供了任意 golang 包的代码覆盖率服务。 |
| [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports)  | - |  来修复(添加，删除) Go 中自动导入的工具。 |
| [GolangCI](https://golangci.com/)  | - |  GolangCI 是一个针对 GitHub pull 请求的自动代码审查服务。服务是开源的，对开源项目是免费的。 |
| [GoLint](https://github.com/golang/lint)  | 3124 |  Go 源码的 linter。 |![star > 1000][Silver]   
| [Golint online](http://go-lint.appspot.com/)  | - |  Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package. |
| [goreturns](https://sourcegraph.com/github.com/sqs/goreturns)  | - |  添加 zero 返回声明，以匹配 func 返回类型。 |
| [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple)  | - |  gosimple 是 Go 源代码的linter，专门用于简化代码。 |
| [gostatus](https://github.com/shurcooL/gostatus)  | 241 |  用于显示包含 Go 包的存储库的状态的命令行工具，。 |![star > 100][Bronze]   
| [lint](https://github.com/surullabs/lint)  | 63 |  将 linters 作为测试的一部分。 |
| [php-parser](https://github.com/z7zmey/php-parser)  | 615 |  用 Go 编写的 PHP 解析器。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck)  | - |  用于大量静态分析检查，您可能已经从 c# 的 ReSharper 等工具中习惯了这些检查。 |
| [tarp](https://github.com/verygoodsoftwarenotvirus/tarp)  | 14 |  在源码中寻找没有直接单元测试的函数和方法。 |![最近一年没有更新][Yellow]
| [unconvert](https://github.com/mdempsky/unconvert)  | 257 |  在源码中删除不必要的类型转换。 |![star > 100][Bronze]   
| [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused)  | - |  对未使用的常量、变量、函数和类型的代码进行检查。 |
| [validate](https://github.com/mccoyst/validate)  | 62 |  使用 tags 自动验证结构体字段。 |![最近一年没有更新][Yellow]

## 编辑器插件

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go)  | - |  JetBrains IDEs 的 Go 插件。 |
| [go-language-server](https://github.com/theia-ide/go-language-server)  | 28 |  A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. |
| [go-mode](https://github.com/dominikh/go-mode.el)  | 944 |  在 GNU/Emacs 支持 GO。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [go-plus](https://github.com/joefitzgerald/go-plus)  | 1480 |  在 Atom 中添加自动完成，格式化，语法检查，高亮和审查。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gocode](https://github.com/nsf/gocode)  | 4721 |  Autocompletion daemon for the Go programming language. |![star > 1000][Silver]   
| [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof)  | - |  在 VS Code 中支持 Go 的基准分析。 |
| [GoSublime](https://github.com/DisposaBoy/GoSublime)  | 3223 |  包含了可为文本编辑器 SublimeText 3 提供代码自动填充和其他类似IDE的功能的 Golang IDE 插件集合。 |![star > 1000][Silver]   
| [gounit-vim](https://github.com/hexdigest/gounit-vim)  | 17 |  基于函数或方法的签名生成Go测试的Vim插件。 |
| [theia-go-extension](https://github.com/theia-ide/theia-go-extension)  | 12 |  在 Theia IDE中支持 Go。 |
| [velour](https://github.com/velour/velour)  | 16 |  acme编辑器的IRC客户端。 |
| [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go)  | 80 |  在保存时突出显示语法错误的 Vim 插件。 |![最近一年没有更新][Yellow]
| [vim-go](https://github.com/fatih/vim-go)  | 10726 |  Go 开发会用到的 Vim 插件。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [vscode-go](https://github.com/Microsoft/vscode-go)  | 5068 |  Visual Studio代码的扩展(VS代码)，它提供了对Go语言的支持。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [Watch](https://github.com/eaburns/Watch)  | 166 |  Runs a command in an acme win on file changes. |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## Go 生成工具

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [generic](https://github.com/usk81/generic)  | 27 |  灵活的 Go 数据类型。 |
| [genny](https://github.com/cheekybits/genny)  | 933 |  优雅的 Go 泛型。 |![star > 100][Bronze]   
| [gocontracts](https://github.com/Parquery/gocontracts)  | 52 |  通过同步代码和文档来实现 design-by-contract 设计。 |
| [gonerics](http://github.com/bouk/gonerics)  | - |  Go中的易用的泛型。 |
| [gotests](https://github.com/cweill/gotests)  | 2147 |  从源代码生成测试用例。 |![star > 1000][Silver]   
| [gounit](https://github.com/hexdigest/gounit)  | 28 |  使用您自己的模板生成Go测试用例。 |
| [hasgo](https://github.com/DylanMeeus/hasgo)  | 12 |  可生成用于切片的 Haskell。 |
| [re2dfa](https://github.com/opennota/re2dfa)  | 168 |  将正则表达式转换为有限状态机，并输出 Go 源代码。 |![star > 100][Bronze]   
| [TOML-to-Go](https://xuri.me/toml-to-go)  | - |  在浏览器中将 TOML 转换为 Go 类型。 |

## Go 工具

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [colorgo](https://github.com/songgao/colorgo)  | 96 |  将 go 命令包装成彩色的 go build 输出。 |![最近一年没有更新][Yellow]
| [depth](https://github.com/KyleBanks/depth)  | 372 |  通过分析导入，将包依赖关系树可视化输出。 |![star > 100][Bronze]   
| [gb](https://getgb.io/)  | - |  一个基于项目的易用的构建工具。 |
| [generator-go-lang](https://github.com/axelspringer/generator-go-lang)  | 13 |  一个[Yeoman](http://yeoman.io)生成器，用于启动新的 Go 项目。 |
| [gilbert](https://go-gilbert.github.io)  | - |  一个为 Go 项目而生的构建系统和任务运行器。 |
| [go-callvis](https://github.com/TrueFurby/go-callvis)  | 1956 |  使用 dot format 可视化 Go 程序的调用图。 |![star > 1000][Silver]   
| [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete)  | 37 |  Bash completion for go and wgo。 |![最近一年没有更新][Yellow]
| [go-swagger](https://github.com/go-swagger/go-swagger)  | 3895 |  基于 Go 的Swagger 2.0实现。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [godbg](https://github.com/tylerwince/godbg)  | 157 |  实现了 Rusts 的 dbg! 宏，可以方便的在开发过程中快速、容易地调试。 |![star > 100][Bronze]   
| [OctoLinker](https://github.com/OctoLinker/browser-extension)  | 3717 |  借助的 OctoLinker 浏览器扩展，可以高效的地浏览  GitHub go文件。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [richgo](https://github.com/kyoh86/richgo)  | 383 |  用文本装饰丰富 go test 的输出。 |![star > 100][Bronze]   
| [rts](https://github.com/galeone/rts)  | 184 |  从服务器响应生成Go结构。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 软件包

*用Go编写的软件。*

### DevOps 工具

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [aptly](https://github.com/smira/aptly)  | - |  Debian存储库管理工具。 |
| [aurora](https://github.com/xuri/aurora)  | 396 |  基于web的跨平台 Beanstalkd 队列服务器控制台。 |![star > 100][Bronze]   
| [awsenv](https://github.com/soniah/awsenv)  | 21 |  可以为 profile 加载Amazon (AWS)环境变量的轻量二进制文件。 |![最近一年没有更新][Yellow]
| [Blast](https://github.com/dave/blast)  | 168 |  一个用于API负载测试和批处理作业的简单工具。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [bombardier](https://github.com/codesenberg/bombardier)  | 1700 |  快速跨平台 HTTP 基准测试工具。 |![star > 1000][Silver]   
| [bosun](https://github.com/bosun-monitor/bosun)  | 2848 |  按照时间轴发出告警的框架。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [DepCharge](https://github.com/centerorbit/depcharge)  | 9 |  Helps orchestrating the execution of commands across the many dependencies in larger projects. |
| [dogo](https://github.com/liudng/dogo)  | 217 |  监视源文件中的更改并自动编译和运行(restart)。 |![star > 100][Bronze]   
| [drone-jenkins](https://github.com/appleboy/drone-jenkins)  | 24 |  使用二进制文件、docker或 Drone CI 来触发下游Jenkins作业。 |
| [drone-scp](https://github.com/appleboy/drone-scp)  | 55 |  通过 SSH 进行文件拷贝。其中 SSH 通过二进制文件、docker 或 Drone CI触发。 |
| [Dropship](https://github.com/chrismckenzie/dropship)  | 46 |  通过 cdn 部署代码的工具。 |
| [easyssh-proxy](https://github.com/appleboy/easyssh-proxy)  | 99 |  Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. |
| [fac](https://github.com/mkchoi212/fac)  | 1602 |  修复 git 合并冲突。 |![star > 1000][Silver]   
| [gaia](https://github.com/gaia-pipeline/gaia)  | 3722 |  可用于任何编程语言来构建强大的管道。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [Gitea](https://github.com/go-gitea/gitea)  | 14848 |  从 Gogs fork，完全由社区驱动。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator)  | - |  将所有GitHub repositories、issues、milestones 和 labels 都迁移到 Gitea。 |
| [go-furnace](https://github.com/go-furnace/go-furnace)  | 63 |  用Go编写的托管解决方案，可轻松地在AWS、GCP或DigitalOcean上部署应用程序。 |
| [go-selfupdate](https://github.com/sanbornm/go-selfupdate)  | 660 |  允许你的 Go应用程序 进行自我更新。 |![star > 100][Bronze]   
| [gobrew](https://github.com/cryptojuice/gobrew)  | 175 |  gobrew 允许您轻松地在 go 的多个版本之间切换。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [godbg](https://github.com/sirnewton01/godbg)  | 219 |  基于 web 的 gdb 前端应用程序。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Gogs](https://gogs.io/)  | - |  自托管的Git服务。 |
| [gonative](https://github.com/inconshreveable/gonative)  | 313 |  用原生 Go 创建一个跨平台的 Go 工具链。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [govvv](https://github.com/ahmetalpbalkan/govvv)  | - |  可轻松地添加版本信息到 Go 二进制文件。 |
| [gox](https://github.com/mitchellh/gox)  | 3333 |  非常简单，没有多余的跨平台编译工具。 |![star > 1000][Silver]   
| [goxc](https://github.com/laher/goxc)  | 1625 |  专注于跨平台编译和打包的 Go 构建工具。 |![star > 1000][Silver]   ![最近一年没有更新][Yellow]
| [grapes](https://github.com/yaronsumel/grapes)  | 135 |  旨在轻松地通过ssh分发命令的轻量级工具。 |![star > 100][Bronze]   
| [GVM](https://github.com/moovweb/gvm)  | 4442 |  GVM 提供了一个接口来管理 Go 版本。 |![star > 1000][Silver]   
| [Hey](https://github.com/rakyll/hey)  | 6159 |  压力测试工具，可用来代替 ApacheBench (ab)。 |![star > 5000][Gold]   
| [kala](https://github.com/ajvb/kala)  | 1351 |  简单、现代和高性能的作业调度程序。 |![star > 1000][Silver]   
| [kcli](https://github.com/cswank/kcli)  | 76 |  用于检查kafka主题/分区/消息的命令行工具。 |
| [kubernetes](https://github.com/kubernetes/kubernetes)  | 55406 |  来自谷歌的容器集群管理器。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [lstags](https://github.com/ivanilves/lstags)  | 220 |  提供了工具和API，可用来同步不同注册中心的Docker图像。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [lwc](https://github.com/timdp/lwc)  | 8 |  UNIX wc命令的实时更新版本。 |![最近一年没有更新][Yellow]
| [manssh](https://github.com/xwjdsh/manssh)  | 203 |  manssh是一个命令行工具，可以方便地管理ssh别名配置。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Moby](https://github.com/moby/moby)  | 54152 |  Collaborative project for the container ecosystem to assemble container-based systems. |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [Mora](https://github.com/emicklei/mora)  | 265 |  用于访问 MongoDB 文档和元数据的 REST 服务器。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [ostent](https://github.com/ostrost/ostent)  | 164 |  收集和显示系统指标，并可选 Graphite and/or fluxdb作为依赖。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Packer](https://github.com/mitchellh/packer)  | - |  用于从一个源配置为多个平台创建相同的机器图像。 |
| [Pewpew](https://github.com/bengadbois/pewpew)  | 199 |  灵活的 HTTP 命令行压测工具。 |![star > 100][Bronze]   
| [Pomerium](https://github.com/pomerium/pomerium)  | 471 |  Pomerium是一个可识别身份的访问代理。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [Rodent](https://github.com/alouche/rodent)  | 30 |  管理Go版本、项目和跟踪依赖项。 |![最近一年没有更新][Yellow]
| [s3gof3r](https://github.com/rlmcpherson/s3gof3r)  | 988 |  小型实用程序/库，针对大型对象在Amazon S3中的高速传输进行了优化。 |![star > 100][Bronze]   
| [Scaleway-cli](https://github.com/scaleway/scaleway-cli)  | 534 |  从命令行管理 BareMetal 服务器(与使用Docker一样容易)。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [script](https://github.com/bitfield/script)  | 882 |  让DevOps编写类shell和系统管理任务变得更加容易。 |![star > 100][Bronze]   ![最近一个周有更新][Green]
| [sg](https://github.com/ChristopherRabotin/sg)  | 5 |  可测试一组HTTP极限(如ab)，可以在每个调用之间使用响应代码和数据，根据之前的响应来确定特定的服务器压力。 |![最近一年没有更新][Yellow]
| [skm](https://github.com/TimothyYe/skm)  | 546 |  SKM是一个简单而强大的SSH密钥管理器，它可以帮助您轻松地管理多个SSH密钥! |![star > 100][Bronze]   
| [StatusOK](https://github.com/sanathp/statusok)  | 1152 |  监视您的网站和REST api。当服务器宕机或响应时间超过预期时，通过Slack、电子邮件获得通知。 |![star > 1000][Silver]   
| [traefik](https://github.com/containous/traefik)  | 23400 |  反向代理和负载均衡器，支持多个后端。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [Vegeta](https://github.com/tsenart/vegeta)  | 11977 |  HTTP负载测试工具和库。超过9000 ! |![star > 5000][Gold]   
| [webhook](https://github.com/adnanh/webhook)  | 4021 |  允许用户创建在服务器上执行命令的 HTTP hooks。 |![star > 1000][Silver]   
| [Wide](https://wide.b3log.org/login)  | - |  为使用 Golang 的团队提供基于 web 的 IDE。 |
| [winrm-cli](https://github.com/masterzen/winrm-cli)  | 66 |  在Windows机器上远程执行命令的Cli工具。 |

### 其他软件

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [borg](https://github.com/crufter/borg)  | - |  基于终端的bash代码段搜索引擎。 |
| [boxed](https://github.com/tejo/boxed)  | 72 |  基于Dropbox的博客引擎。 |
| [Cherry](https://github.com/rafael-santiago/cherry)  | 193 |  微型网络聊天服务器。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [Circuit](https://github.com/gocircuit/circuit)  | 1782 |  Circuit 是一个可编程平台即服务(PaaS)和/或基础设施即服务(IaaS)，用于管理、发现、同步和编排包含云应用程序的服务和主机。 |![star > 1000][Silver]   
| [Comcast](https://github.com/tylertreat/Comcast)  | 6157 |  模拟坏的网络连接。 |![star > 5000][Gold]   
| [confd](https://github.com/kelseyhightower/confd)  | 6359 |  使用 etcd 或 consul 的模板和数据管理本地应用程序配置文件。 |![star > 5000][Gold]   
| [DDNS](https://github.com/skibish/ddns)  | 97 |  个人 DDNS 客户端。 |
| [Docker](http://www.docker.com/)  | - |  面向开发人员和系统管理员的分布式应用程序的开放平台。 |
| [Documize](https://github.com/documize/community)  | 806 |  集成了SaaS工具数据的现代wiki软件。 |![star > 100][Bronze]   
| [drive](https://github.com/odeke-em/drive)  | 4936 |  基于命令行的谷歌驱动器客户端。 |![star > 1000][Silver]   
| [Duplicacy](https://github.com/gilbertchen/duplicacy)  | 2670 |  跨平台网络和云备份工具。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [gfile](https://github.com/Antonito/gfile)  | 493 |  通过WebRTC在两台计算机之间安全地传输文件，不需要任何第三方依赖。 |![star > 100][Bronze]   
| [Go Package Store](https://github.com/shurcooL/Go-Package-Store)  | 876 |  App that displays updates for the Go packages in your GOPATH. |![star > 100][Bronze]   
| [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix)  | 372 |  视频流 torrent 客户端。 |![star > 100][Bronze]   
| [GoBoy](https://github.com/Humpheh/goboy)  | 2098 |  用 Go 编写的任天堂Game Boy彩色模拟器。 |![star > 1000][Silver]   
| [gocc](https://github.com/goccmack/gocc)  | 339 |  Gocc是一个用Go编写的编译器工具包。 |![star > 100][Bronze]   
| [GoDNS](https://github.com/timothyye/godns)  | 419 |  一个动态DNS客户端工具，支持DNSPod & HE.net。 |![star > 100][Bronze]   
| [GoDocTooltip](https://github.com/diankong/GoDocTooltip)  | 12 |  包含了 Go 使用手册文档的 Chrome 扩展。 |![最近一年没有更新][Yellow]
| [GoLand](https://jetbrains.com/go)  | - |  功能齐全的跨平台 Go IDE。 |
| [Gor](https://github.com/buger/gor)  | - |  Http 流量复制工具，用于实时回放从生产环境到阶段/开发环境的流量。 |
| [hugo](http://gohugo.io/)  | - |  快速、现代的静态网站引擎。 |
| [ide](https://github.com/thestrukture/ide)  | 250 |  基于浏览器的IDE |![star > 100][Bronze]   
| [ipe](https://github.com/dimiro1/ipe)  | 274 |  Open source Pusher server implementation compatible with Pusher client libraries written in GO. |![star > 100][Bronze]   
| [joincap](https://github.com/assafmo/joincap)  | 120 |  用于合并多个pcap文件的命令行实用程序。 |![star > 100][Bronze]   
| [Juju](https://jujucharms.com/)  | - |  Cloud-agnostic的服务部署和编制 —— 支持EC2、Azure、Openstack、MAAS等。 |
| [Leaps](https://github.com/jeffail/leaps)  | 639 |  使用操作转换的成对编程服务。 |![star > 100][Bronze]   
| [lgo](https://github.com/yunabe/lgo)  | 1779 |  与 Jupyter 可进行交互 Go 程序。它支持代码完成、代码检查以及与Go 100% 兼容性。 |![star > 1000][Silver]   
| [limetext](http://limetext.org/)  | - |  一个强大而优雅的文本编辑器。 |
| [LiteIDE](https://github.com/visualfc/liteide)  | 5435 |  简单的、开源的、跨平台的Go IDE。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [mockingjay](https://github.com/quii/mockingjay-server)  | 411 |  一份配置文件中便可伪造HTTP服务器与用户之间的行为。您还可以使服务器随机宕机，以帮助进行更实际的性能测试。 |![star > 100][Bronze]   
| [myLG](https://github.com/mehrdadrad/mylg)  | 2192 |  命令行网络诊断工具。 |![star > 1000][Silver]   
| [naclpipe](https://github.com/unix4fun/naclpipe)  | 20 |  基于加密管的简单的NaCL EC25519工具。 |
| [nes](https://github.com/fogleman/nes)  | 4117 |  任天堂娱乐系统(NES)模拟器。 |![star > 1000][Silver]   
| [orange-cat](https://github.com/noraesae/orange-cat)  | - |  用Go编写的Markdown预览器。 |
| [Orbit](https://github.com/gulien/orbit)  | 128 |  一个根据模板来运行命令和生成文件的简单小工具。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [peg](https://github.com/pointlander/peg)  | 587 |  解析表达式语法，是Packrat解析器生成器的实现。 |![star > 100][Bronze]   
| [Pipe](https://github.com/b3log/pipe)  | 2721 |  一个小巧漂亮的博客平台。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [restic](https://github.com/restic/restic)  | 7311 |  消除重复项备份程序。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [rkt](https://github.com/coreos/rkt)  | - |  一个应用容器，与其他容器格式(如Docker)兼容，并支持其他执行引擎(如KVM)。 |
| [scc](https://github.com/boyter/scc)  | 762 |  一个非常快速准确的代码计数器，采用了复杂的计算和 COCOMO 预估。 |![star > 100][Bronze]   
| [Seaweed File System](https://github.com/chrislusf/seaweedfs)  | 8102 |  快速、简单、可伸缩的分布式文件系统，采用了O(1)磁盘查找。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [shell2http](https://github.com/msoap/shell2http)  | 398 |  通过http服务器执行shell命令(用于原型或远程控制)。 |![star > 100][Bronze]   
| [snap](https://github.com/intelsdi-x/snap)  | 1804 |  强大的遥测框架。 |![star > 1000][Silver]   
| [Snitch](https://github.com/lucasgomide/snitch)  | 15 |  当有人通过 Tsuru 部署任何应用程序时，会通知您的团队以及其他工具。 |
| [Stack Up](https://github.com/pressly/sup)  | 1985 |  Stack Up 是一个超级简单的部署工具 — 只面向Unix。 |![star > 1000][Silver]   
| [syncthing](https://syncthing.net/)  | - |  开放，分散的文件同步工具和协议。 |
| [term-quiz](https://github.com/crazcalm/term-quiz)  | 17 |  测试你的终端。 |
| [toxiproxy](https://github.com/shopify/toxiproxy)  | 3826 |  为自动化测试模拟网络和系统条件的代理。 |![star > 1000][Silver]   
| [tsuru](https://tsuru.io/)  | - |  Extensible and open source Platform as a Service software. |
| [vFlow](https://github.com/VerizonDigital/vflow)  | 592 |  高性能、可伸缩和可靠的 IPFIX、sFlow和 Netflow 收集器。 |![star > 100][Bronze]   
| [wellington](https://github.com/wellington/wellington)  | 288 |  Sass 项目管理工具，使用sprite函数(如Compass)扩展语言。 |![star > 100][Bronze]   

# 资源

*在哪里可以找到新的Go库。*

## 基准

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [autobench](https://github.com/davecheney/autobench)  | 89 |  用来来比较不同Go版本之间的性能的框架。 |![最近一年没有更新][Yellow]
| [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app)  | 19 |  强大的HTTP基准测试工具，包含了Аb，Wrk，Siege工具。收集统计和各种参数指标，并比较相关结果。 |![最近一年没有更新][Yellow]
| [go-benchmarks](https://github.com/tylertreat/go-benchmarks)  | 121 |  Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark)  | 1255 |  HTTP请求路由器基准测试和比较。 |![star > 1000][Silver]   
| [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark)  | 981 |  web框架基准测试。 |![star > 100][Bronze]   
| [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks)  | 853 |  Go序列化方法的基准测试。 |![star > 100][Bronze]   
| [gocostmodel](https://github.com/PuerkitoBio/gocostmodel)  | - |  Go语言常用基本操作的基准测试。 |
| [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks)  | 17 |  Go 基础操作的基准测试集合。其目的是将一些语言特性与其他特性进行比较。 |
| [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark)  | 48 |  为流行的 Go 数据库/SQL实用程序收集基准测试。 |![最近一年没有更新][Yellow]
| [gospeed](https://github.com/feyeleanor/GoSpeed)  | 93 |  计算语言结构的速度的微观基准测试。 |
| [kvbench](https://github.com/jimrobinson/kvbench)  | 14 |  K / V 类型数据库基准测试。 |![最近一年没有更新][Yellow]
| [skynet](https://github.com/atemerev/skynet)  | 910 |  天网 1M 线程微基准测试。 |![star > 100][Bronze]   
| [speedtest-resize](https://github.com/fawick/speedtest-resize)  | 172 |  对比各种图像大小调整算法性能。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 会议

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Capital Go](http://www.capitalgolang.com)  | - |  华盛顿特区。,美国。 |
| [dotGo](http://www.dotgo.eu)  | - |  巴黎,法国。 |
| [GoCon](http://gocon.connpass.com/)  | - |  东京,日本。 |
| [GoDays](https://www.godays.io/)  | - |  德国柏林。 |
| [GoLab](http://golab.io/)  | - |  佛罗伦萨,意大利。 |
| [GolangUK](http://golanguk.com/)  | - |  伦敦,英国。 |
| [GopherChina](http://gopherchina.org)  | - |  上海,中国。 |
| [GopherCon](http://www.gophercon.com/)  | - |  美国丹佛。 |
| [GopherCon Australia](https://gophercon.com.au/)  | - |  澳大利亚悉尼。 |
| [GopherCon Brazil](https://gopherconbr.org)  | - |  弗洛,BR。 |
| [GopherCon Europe](https://gophercon.is/)  | - |  雷克雅未克,冰岛。 |
| [GopherCon India](https://www.gophercon.in/)  | - |  印度浦那。 |
| [GopherCon Israel](https://www.gophercon.org.il/)  | - |  特拉维夫,以色列。 |
| [GopherCon Russia](https://www.gophercon-russia.ru)  | - |  莫斯科,俄罗斯。 |
| [GopherCon Singapore](https://gophercon.sg)  | - |  新加坡枫树商贸城。 |
| [GopherCon Vietnam](https://gophercon.vn/)  | - |  越南胡志明市。 |
| [GothamGo](http://gothamgo.com/)  | - |  美国纽约市。 |
| [GoWayFest](https://goway.io/)  | - |  白俄罗斯明斯克。 |

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Go 101](https://go101.org)  | - |  一本关注 Go 语法/语义和各种细节的书。 |
* [Go Bootcamp](http://golangbootcamp.com)
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Go Succinctly](https://github.com/thedevsir/gosuccinctly)  | 10 |  in Persian. |
| [GoBooks](https://github.com/dariubs/GoBooks)  | 6727 |  一份精选的 Go 书籍清单。 |![star > 5000][Gold]   
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack)  | 1472 |  由 Maria Letta 提供的与 Gopher 有关的图片包，其中包含了插图,表情文字。 |![star > 1000][Silver]   
| [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector)  | 32 |  与 Go gopher 相关的媒介数据[。ai . svg)。 |![最近一年没有更新][Yellow]
| [gopher-logos](https://github.com/GolangUA/gopher-logos)  | 63 |  可爱的 gopher 标识。 |![最近一年没有更新][Yellow]
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector](https://github.com/golang-samples/gopher-vector)
* [gophericons](https://github.com/shalakhin/gophericons)
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [gopherize.me](https://github.com/matryer/gopherize.me)  | 313 |  Gopherize自己。 |![star > 100][Bronze]   
| [gophers](https://github.com/ashleymcnamara/gophers)  | 1830 |  阿什莉·麦克纳马拉的歌斐艺术品。 |![star > 1000][Silver]   
| [gophers](https://github.com/egonelbre/gophers)  | 1562 |  Free gophers. |![star > 1000][Silver]   
| [gophers](https://github.com/rogeralsing/gophers)  | 50 |  随机gopher图形。 |![最近一年没有更新][Yellow]
| [gophers](https://github.com/sillecelik/go-gopher)  | 40 |  Gopher amigurumi玩具图案。 |

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
* [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
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

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Awesome Go @LibHunt](https://go.libhunt.com)  | - |  属于你的 Go 工具箱。 |
| [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job)  | 14453 |  Curated list of awesome remote jobs. A lot of them are looking for Go hackers. |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)  | 24552 |  其他 awesome 系列的列表。 |![star > 5000][Gold]   ![最近一个周有更新][Green]
| [CodinGame](https://www.codingame.com/)  | - |  以小游戏互动完成任务的形式来学习 Go。 |
| [Go Blog](http://blog.golang.org)  | - |  官方 Go 博客。 |
| [Go Challenge](http://golang-challenge.org/)  | - |  通过解决问题并从 Go 专家那里得到反馈来学习 Go。 |
| [Go Community on Hashnode](https://hashnode.com/n/go)  | - |  Hashnode上的Go社区。 |
| [Go Forum](https://forum.golangbridge.org)  | - |  讨论 Go 的论坛。 |
| [Go In 5 Minutes](https://www.goin5minutes.com/)  | - |  5 minute screencasts focused on getting one thing done. |
| [Go Projects](https://github.com/golang/go/wiki/Projects)  | - |  wiki上的 Go 社区项目列表。 |
| [Go Report Card](https://goreportcard.com)  | - |  为你的 Go 包生成一份报告单。 |
| [gocryforhelp](https://github.com/ninedraft/gocryforhelp)  | 36 |  专门收集需要帮助的Go项目，这是你开启开源之路的好去处。 |![最近一年没有更新][Yellow]
| [godoc.org](https://godoc.org/)  | - |  开源 Go 包的文档。 |
| [Golang Flow](https://golangflow.io)  | - |  发布更新、新闻、包等等。 |
| [Golang News](https://golangnews.com)  | - |  关于 Go 编程的链接和新闻。 |
| [golang-graphics](https://github.com/mholt/golang-graphics)  | 141 |  收藏的 Go 图像，图形和艺术作品。 |![star > 100][Bronze]   ![最近一年没有更新][Yellow]
| [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts)  | - |  Go 邮件列表。 |
| [Google Plus Community](https://plus.google.com/communities/114112804251407510571)  | - |  Google+社区 golang爱好者聚集地。 |
| [Gopher Community Chat](https://invite.slack.golangbridge.org)  | - |  加入我们为Gophers设立的全新Slack社区([了解它是如何产生的](https://blog.gopheracademy.com/gophers-slack-community/))。 |
| [Gophercises](https://gophercises.com/)  | - |  为 Go 初学者提供免费的代码训练。 |
| [gowalker.org](https://gowalker.org)  | - |   Go API 文档。 |
| [justforfunc](https://www.youtube.com/c/justforfunc)  | - |  致力于传授 Go 编程语言技巧和技巧的Youtube 频道，由Francesc Campoy [@francesc](https://twitter.com/francesc)主办。 |
| [r/Golang](https://www.reddit.com/r/golang)  | - |  与 Go 有关的新闻。 |
| [studygolang](https://studygolang.com)  | - |  Go语言中文网 |
| [Trending Go repositories on GitHub today](https://github.com/trending?l=go)  | - |  寻找最新的 Go库 的好地方。 |
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### 教程

        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/)  | - |  Go 初学者经常遇到的陷阱、误区、错误 |
| [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo)  | - |  教你如何用 Go 搭建一个电商平台 (包括demo)。 |
| [A Tour of Go](http://tour.golang.org/)  | - |  互动的 Go 之旅。 |
| [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang)  | 31182 |  Golang电子书，主要讲述如何用 Golang 建立一个web应用程序。 |![star > 5000][Gold]   
| [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin)  | - |  Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline. |
| [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9)  | - |  如何缓存数据库的慢查询。 |
| [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30)  | - |  如何取消MySQL查询。 |
| [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book)  | 443 |  一本讲述如何用 Go 进行以太开发的小册。 |![star > 100][Bronze]   
| [Games With Go](http://gameswithgo.org/)  | - |  关于编程和游戏开发系列教学视频。 |
| [Go By Example](https://gobyexample.com/)  | - |  手把手教你 如何在 Go 应用程序中使用注释。 |
| [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet)  | 4001 |   Go's reference card。 |![star > 1000][Silver]   
| [Go database/sql tutorial](http://go-database-sql.org/)  | - |  数据库概论/ sql。 |
| [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8)  | - |  在你的移动设备上编辑你编辑和运行你的 Go 代码。 |
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers)  | 676 |  引入示例讲述 Golang 与Node.js在学习上的差异。 |![star > 100][Bronze]   
| [Golangbot](https://golangbot.com/learn-golang-series/)  | - |  Go 编程教程。 |
| [Hackr.io](https://hackr.io/tutorials/learn-golang)  | - |  Go社区投票选举出来的最好的在线 Go 教程。 |
| [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go)  | - |  快速使用Godog —— 一个行为驱动开发的构建和测试应用程序框架。 |
| [Learn Go with TDD](https://github.com/quii/learn-go-with-tests)  | 4265 |  学习使用测试驱动开发。 |![star > 1000][Silver]   ![最近一个周有更新][Green]
| [package main](https://www.youtube.com/packagemain)  | - |  关于 Go 编程的YouTube频道。 |
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
        
| name  | star  | desc  | tag&nbsp;&nbsp;&nbsp; |
|---|---|---|---|
| [Working with Go](https://github.com/mkaz/working-with-go)  | 1130 |  由一个经验丰富的Go程序员群体编写的一系列Go学习范例。 |![star > 1000][Silver]   
| [Your basic Go](http://yourbasic.org/golang)  | - |  如何收集大量的教程。 |

