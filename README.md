<p align="center">
  <a href="https://github.com/alibaba/Chat2DB">
    <img width="100" src="document/logo.ico">
  </a>
</p>
<h1 align="center">Chat2DB</h1>

<div align="center">

一个集成了AIGC的数据库客户端工具

[![MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/alibaba/ali-dbhub/blob/main/LICENSE)
[![GitHub release](https://img.shields.io/github/release/alibaba/ali-dbhub)](https://github.com/alibaba/ali-dbhub/releases)
[![GitHub Stars](https://img.shields.io/github/stars/alibaba/ali-dbhub)](https://github.com/alibaba/ali-dbhub/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/alibaba/ali-dbhub)](https://github.com/alibaba/ali-dbhub/fork)
[![GitHub Contributors](https://img.shields.io/github/contributors/alibaba/ali-dbhub)](https://github.com/alibaba/ali-dbhub/graphs/contributors)

</div>

##### 语言： 中文 | [English](README_EN.md)
&emsp; &emsp; &emsp; &emsp;Chat2DB 是一款有阿里巴巴开源免费的多数据库客户端工具，支持windows、mac本地安装，也支持服务器端部署，web网页访问。和传统的数据库客户端软件Navicat、DBeaver 相比Chat2DB集成了AIGC的能力，能够将自然语言转换为SQL，也可以将SQL转换为自然语言，可以给出研发人员SQL的优化建议，极大的提升人员的效率，是AI时代数据库研发人员的利器，未来即使不懂SQL的运营业务也可以使用快速查询业务数据、生成报表能力。
## ✨ 特性
- 🌈 AI智能助手，支持自然语言转SQL、SQL转自然语言、SQL优化建议
- 👭 支持团队协作，研发无需知道线上数据库密码，解决企业数据库账号安全问题
- ⚙️ 强大的数据管理能力，支持数据表、视图、存储过程、函数、触发器、索引、序列、用户、角色、授权等管理
- 🔌 强大的扩展能力，目前已经支持Mysql、PostgreSQL、Oracle、SQLServer、ClickHouse、Oceanbase、H2、SQLite等等，未来会支持更多的数据库
- 🛡 前端使用 Electron 开发，提供 Windows、Mac、Linux 客户端、网页版本一体化的解决方案
- 🎁 支持环境隔离、线上、日常数据权限分离


## 🌰 使用Demo
- 创建数据源
<a><img src="https://gw.alicdn.com/imgextra/i3/O1CN01PlpLYy1hIq5aMugpg_!!6000000004255-0-tps-3446-1750.jpg" width="100%"/></a>
- 数据源管理
<a><img src="https://gw.alicdn.com/imgextra/i2/O1CN01DpzZJL1T7w2Xv9VMl_!!6000000002336-0-tps-3410-1662.jpg" width="100%"/></a>
- SQL控制台
<a><img src="https://gw.alicdn.com/imgextra/i2/O1CN01aidnkx1Oo0LJ1Pdty_!!6000000001751-0-tps-3440-1736.jpg" width="100%"/></a>
- AI智能助手
<a><img src="https://gw.alicdn.com/imgextra/i4/O1CN01iaSXot1W6VeaDFbK2_!!6000000002739-0-tps-3430-1740.jpg" width="100%"/></a>


## ⏬ 下载安装

Mac、Windows客户端应用下载地址 <a href="https://github.com/alibaba/ali-dbhub/releases">GitHub releases</a>.

网页版本待更新...

## 🎯 运行环境
注意：
如果需要本地调试
- java运行 <a href="https://adoptopenjdk.net/" target="_blank">Open JDK 17</a>
- jre参考打包发布中jre安装方式.
- Node运行环境Node16 <a href="https://nodejs.org/" target="_blank">Node.js</a>.

## 💻 本地调试
- git clone到本地
```bash
$ git clone git@github.com:alibaba/Chat2DB.git
```
- 前端安装
```bash
$ cd Chat2DB/ali-dbhub-client
$ npm install # 安装npm 
$ npm run build:prod # 把js打包生成到后端的source目录
```
- 后端启动
```bash
$ cd ../ali-dbhub-server
$ mvn clean install # 需要安装maven 3.8以上版本
$ cd ali-dbhub-server/ali-dbhub-server-start/target/
$ java -jar -Dchatgpt.apiKey=xxxxx ali-dbhub-server-start.jar  # 启动应用 chatgpt.apiKey 需要输入ChatGPT的key,如果不输入无法使用AIGC功能
```

## 📑 文档

* <a href="https://github.com/alibaba/ali-dbhub/wiki">WIKI</a>
* <a href="https://github.com/alibaba/ali-dbhub/issues">Issue tracker</a>

## ☎️ 联系我们
<a><img src="https://gw.alicdn.com/imgextra/i1/O1CN01VBaYST1MFzhUY9QP6_!!6000000001406-0-tps-723-731.jpg" width="40%"/></a>

微信：yxccw132  钉钉：9135032392

## ❤️ 致谢
感谢所有为Chat2DB贡献力量的同学们~

<a href="https://github.com/alibaba/ali-dbhub/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=alibaba/ali-dbhub" />
</a>


