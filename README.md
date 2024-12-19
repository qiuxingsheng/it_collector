# 技术整理
收集我所了解的较新it技术，以java和大数据为主，慢慢积累

# Java
## 框架
### SpringBoot
### SpringCloud Alibaba

## 文档相关
### 文档在线预览
kkFileView

https://kkview.cn/zh-cn/index.html
### 文档内容解析
Apache Tika

https://tika.apache.org/
# 大数据

## 元数据管理

### Datahub 

https://github.com/datahub-project/datahub

## 实时计算
### Flink

### web开发平台

#### StreamPark

https://streampark.apache.org/

#### dinky

https://github.com/DataLinkDC/dinky

## 湖仓一体

### hudi

### Paimon

# 人工智能
## 大模型开发
https://github.com/hpcaitech/ColossalAI

# 运维
## 监控告警
### sentry

https://docs.sentry.io/

Sentry 是一个开源的实时错误追踪系统，可以帮助开发者实时监控并修复异常问题。它主要专注于持续集成、提高效率并且提升用户体验。Sentry 分为服务端和客户端 SDK，前者可以直接使用它家提供的在线服务，也可以本地自行搭建；后者提供了对多种主流语言和框架的支持，包括 React、Angular、Node、Django、RoR、PHP、Laravel、Android、.NET、JAVA 等。同时它可提供了和其他流行服务集成的方案，例如 GitHub、GitLab、bitbuck、heroku、slack、Trello 等。目前公司的项目也都在逐步应用上 Sentry 进行错误日志管理。

### prometheus + Grafana

Prometheus 是一款基于时序数据库的开源监控告警系统，非常适合Kubernetes集群的监控。Prometheus的基本原理是通过HTTP协议周期性抓取被监控组件的状态，任意组件只要提供对应的HTTP接口就可以接入监控。不需要任何SDK或者其他的集成过程。这样做非常适合做虚拟化环境监控系统，比如VM、Docker、Kubernetes等。输出被监控组件信息的HTTP接口被叫做exporter 。目前互联网公司常用的组件大部分都有exporter可以直接使用，比如Varnish、Haproxy、Nginx、MySQL、Linux系统信息(包括磁盘、内存、CPU、网络等等)。

## 自动化部署

### 自动化运维平台 - Spug
https://github.com/openspug/spug

### Jenkins

# 常用工具

## 梯子

dev-sidecar

一元机场

## redis 客户端

Another Redis Desktop Manager 

https://github.com/qishibo/AnotherRedisDesktopManager

## 文本编辑器 

Visual Studio Code

## 剪切板工具 ditto

## 思维导图

xmind

## 流程图画图工具 

draw.io

## 远程终端
Tabby Terminal

https://tabby.sh/

## FTP
filezilla

https://www.filezilla.cn/
## 电子书格式转换

TEBookConverter

基本简介

TEBookConverter是一款免费的电子书转换工具，它支持从多格式（are cbz, cbr, cbc, chm, djvu, docx, epub, fb2, html, htmlz, lit, lrf, mobi, odt, pdf, prc, pdb, pml, rb, rtf, snb, tcr, txt, txtz 等等）。

软件特色

TEBookConverter是一种使用Calibre的电子书转换器。支持的输入格式有cbz、cbr、cbc、chm、djvu、docx、epub、fb2、html、htmlz、lit、lrf、mobi、odt、prc、pdb、pml、rb、rtf、snb、tcr、txt、txtz。支持的输出格式是azw3、epub、fb2、oeb、lit、lrf、mobi、htmlz、pdb、pml、rb、pdf、rtf、snb、tcr、txt、txtz。由于多线程，您可以快速转换电子书。


## 原型绘制工具

Balsamiq Mockups

## 测试工具

https://github.com/metersphere/metersphere

jmeter

## 数据库设计工具

https://gitee.com/robergroup/pdmaner

## 其他

### 本地播放器 

PotPlayer

https://potplayer.daum.net/

vlc

https://www.videolan.org/vlc/

mediago m3u8 视频下载

https://github.com/caorushizi/mediago

### 系统hosts管理

switchhosts

https://github.com/oldj/SwitchHosts

### 本地文件搜索

Everything

### 文件夹大小排序，优化磁盘

WizTree

https://www.diskanalyzer.com/

### pdf 格式转换

CleverPDF

https://www.cleverpdf.com/

### node版本管理

nvm

### windows 命令增强 PSTools

### IDEA插件

Chinese (Simplified) Language Pack  idea中文包

EasyYapi 接口文档生成插件

GsonFormat-Plus gson格式化插件

Key Promoter X 快捷键提示插件

Alibaba Java Coding Guidelines 阿里java开发规范插件

Maven Helper maven插件 解决冲突等

MyBatisX mybatis插件

TONGYl Lingma 通义灵码

Leeks 小韭菜





