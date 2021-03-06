<h1 align="center">Welcome to headwolf 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-v0.01-blue.svg?cacheSeconds=2592000" />
  <a href="w文档" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
</p>

> 基于Xposed和Sekiro搭建的敏捷开发的脚手架

### 🏠 [Homepage]()

暂无

### ✨ [Demo]()

暂无

## Structure introduction

> 公共类
- commons 
  > 统一日志类
  - Logger
> 入口类 
- entry
  > Hook第一层入口（包括免重启等功能）
  - BaseEntry
  > Hook逻辑入口，由第一层入口加载，包含具体的Hook逻辑
  - RealEntry
> 事件处理类 
- handlers
  > 基础处理类
  - BaseHandler
> 初始化管理类
- initialization
  > 基础初始化类
  - BaseInit
  > 注册类，管理与Sekiro服务端通信
  - Register
> 工具类
- utils
  > 通信助手
  - CommunicationAssistant
  > 算法助手
  - AlgorithmAssistant
- Config

## Install

```sh
step1: git clone https://github.com/lateautumn4lin/headwolf
step2: import project into android studio
step3: run the test project E.g kuaishou
```

## Usage

```sh
follow my steps
```

## Run tests

```sh
follow my steps
```

## Author

👤 **lateautumn4lin**

* Website: https://cloudcrawler.club/
* Github: [@lateautumn4lin](https://github.com/lateautumn4lin)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_