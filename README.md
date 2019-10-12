# bilive_server

[![Node.js](https://img.shields.io/badge/Node.js-v10.0%2B-green.svg)](https://nodejs.org)
[![Commitizen friendly](https://img.shields.io/badge/Commitizen-Friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
![GitHub repo size](https://img.shields.io/github/repo-size/Blokura/bilive_server.svg)
[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/Blokura/bilive_server/blob/2.1.0-beta/LICENSE)

* 这是一个次次分支，感谢所有对[主分支](https://github.com/lzghzr/bilive_client)，[次分支](https://github.com/Vector000/bilive_client)做出贡献的人及其他同类开源软件的开发者
* 有兴趣支持原作者的，请朝这里打钱=>[给lzghzr打钱](https://github.com/lzghzr/bilive_client/wiki)
* 有兴趣向次分支投喂的，请朝这里打钱=>[给Vector000我钱](https://github.com/Vector000/Something_Serious/blob/master/pics/mm_reward_qrcode.png)
* 有兴趣支持我的，请不要打钱。

## 自行编译

* 安装Node.js
  1. 命令行 `curl -sL https://rpm.nodesource.com/setup_10.x | sudo bash -`
  2. 命令行 `yum install nodejs`

* 第一次使用
  1. 安装[Git](https://git-scm.com/downloads)
  2. 安装Node.js，见上文
  3. 命令行 `git clone https://github.com/Blokura/bilive_server.git`
  4. 命令行 `cd bilive_server`
  5. 命令行 `mkdir options`
  6. 命令行 `cp nedb/roomList.db options/roomList.db`
  7. 命令行 `npm install`
  8. 命令行 `npm run build`
  9. 命令行 `npm start`

* 使用PM2实现后台运行
  1. 命令行 `npm install pm2 -g`
  2. 命令行 `pm2 start npm --name bilive_server -- start`

* 版本更新
  1. 定位到目录
  2. 命令行 `git pull`
  3. 命令行 `npm install`
  4. 命令行 `npm run build`
  5. 命令行 `npm start`

[点此进入网页远程控制](http://vector000.coding.me/bilive_setting/#path=ws://localhost:20080&protocol=admin)

此为服务端, 仅用来监听房间。
