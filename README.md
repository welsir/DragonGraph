<p align="center">
  <img src="https://welsir.oss-cn-hangzhou.aliyuncs.com/study/2fd72a73-5dcb-4b77-b091-67db45fcbf17.png" alt="LongTu Logo" width="200" />
</p>


<h1 align="center">🐉 LongTu · 龙图</h1>
<h3 align="center">Reimagining Audio/Video at Scale</h3>
<p align="center"><i>“驭流如龙，洞见云端。”</i></p>

---

## 📖 目录 / Contents

1. [项目简介 / Project Overview](#项目简介--project-overview)
2. [核心特性 / Key Features](#核心特性--key-features)
3. [模块划分 / Modules](#模块划分--modules)
4. [系统架构图 / Architecture Diagram](#系统架构图--architecture-diagram)
5. [快速开始 / Quick Start](#快速开始--quick-start)
6. [贡献 & 联系 / Contribute & Contact](#贡献--联系--contribute--contact)

---

## 项目简介 / Project Overview

**龙图（LongTu）** 是一个面向高并发（C10K–C10M）、采用领域驱动设计（DDD）和文化驱动命名的现代化音视频流媒体与 IM 框架。  
LongTu is a modern audio/video streaming & IM framework designed for extreme concurrency (C10K–C10M), leveraging DDD and a dragon-inspired naming convention.

---

## 核心特性 / Key Features

| 🇨🇳 中文               | 🇺🇸 English                                 |
| --------------------- | ------------------------------------------ |
| 🔥 极限性能（C10M 级） | 🔥 Extreme Concurrency (up to C10M)         |
| 🧱 DDD 四层架构        | 🧱 Four-layer DDD Architecture              |
| 🐲 龙文化命名          | 🐲 Dragon-themed Module Names               |
| 📡 多协议音视频支持    | 📡 Multi-protocol AV (WebRTC, RTMP, etc.)   |
| 💬 内建可插拔 IM       | 💬 Pluggable IM (text, emoji, notification) |
| 🛡 防腐层（ACL）解耦   | 🛡 Anti-Corruption Layer (Loose Coupling)   |

---

## 模块划分 / Modules

| 模块名 / Module | 龙意象 / Dragon Element | 职责 / Responsibility                                    |
| --------------- | ----------------------- | -------------------------------------------------------- |
| `dragon-head`   | 🐲 龙首                  | 用户管理、房间调度、开播编排 / User & room orchestration |
| `dragon-breath` | 🌬️ 龙息                  | 推流/拉流、编解码、QoS / AV stream processing            |
| `dragon-wing`   | 🪽 龙翼                  | 实时聊天、状态广播 / IM & presence                       |
| `dragon-scale`  | 🛡️ 龙鳞                  | 鉴权、权限、安全 / Auth & authorization                  |
| `dragon-claw`   | 🐾 龙爪                  | 日志、指标、告警 / Logging & monitoring                  |
| `shared`        | 🧩 通用                  | 公共工具、配置、异常 / Common utilities & configs        |
| `gateway`       | 🌐 网关                  | API 聚合入口 / Unified API gateway                       |

---

## 系统架构图 / Architecture Diagram



## 快速开始 / Quick Start

```
bash复制编辑git clone https://github.com/your-org/longtu.git
cd longtu
./gradlew bootRun   # or mvn spring-boot:run
```

1. 修改 `application.yml` 配置数据库、Redis、Kafka、TLS 证书等。
2. 启动网关与子服务：`gateway`、`dragon-head`、`dragon-breath` 等。
3. 浏览 API 文档：http://localhost:8080/swagger-ui.html

------

## 贡献 & 联系 / Contribute & Contact

我们欢迎你的想法与代码！
We welcome your ideas and contributions!

- 📧 Email: `longtu-dev@yourorg.com`
- 🐦 Twitter: [@LongTuProject](https://twitter.com/LongTuProject)
- 🌐 Site: `https://longtu.yourorg.com`

让我们一起，在高并发的音视频世界里，驭流腾云！
Join us to tame the streams and ride the clouds of extreme concurrency!
