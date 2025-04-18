<p align="center">
  <img src="https://hievents-public.s3.us-west-1.amazonaws.com/website/hi-events-rainbow.png?v=1" alt="Hi.Events 标志" width="200px">
</p>
<h3 align="center">Hi.Events</h3>
<p align="center">
<a href="https://demo.hi.events/event/1/dog-conf-2030">演示活动 🌟</a> <a href="https://hi.events?utm_source=gh-readme">网站 🌎</a>  <a href="https://hi.events/docs">文档 📄</a>  <a href="https://hi.events/docs/getting-started?utm_source=gh-readme">安装 ⚙️</a>
</p>

<h3 align="center">
 轻松管理活动并在线售票。
</h3>

<div align="center">

[![Hi.Events 文档](https://img.shields.io/badge/docs-hi.events-blue)](https://hi.events/docs)
[![许可证: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://github.com/HiEventsDev/hi.events/LICENCE)
[![GitHub 发布](https://img.shields.io/github/v/release/HiEventsDev/hi.events?include_prereleases)](https://github.com/HiEventsDev/hi.events/releases)
[![运行单元测试](https://github.com/HiEventsDev/hi.events/actions/workflows/unit-tests.yml/badge.svg?event=push)](https://github.com/HiEventsDev/hi.events/actions/workflows/unit-tests.yml)
[![Docker 下载](https://img.shields.io/docker/pulls/daveearley/hi.events-all-in-one)](https://hub.docker.com/r/daveearley/hi.events-all-in-one)

</div>

<div align="center">
 🌟 期待您的星标支持！ 🌟
</div>

<hr/>

## 目录

- [介绍](#-介绍)
- [功能](#-功能)
- [快速开始](#-快速开始)
- [更新日志](#-更新日志)
- [贡献](#-贡献)
- [常见问题](#-常见问题)

## 📚 介绍

<a href="https://hi.events">Hi.Events</a> 是一个功能丰富的自托管活动管理和售票平台。从会议到俱乐部夜场，
Hi.Events 旨在帮助您创建、管理和销售各种规模的活动门票。

<img alt="Hi.Events 自托管售票仪表盘" src="https://hievents-public.s3.us-west-1.amazonaws.com/website/dashboard-screenshot.png"/>

## 🌟 功能

<a href="https://hi.events">Hi.Events</a> 拥有众多功能，简化您的活动管理和售票流程：

- 📊 **活动分析:** 深入了解活动表现和门票销售情况。
- 🎟 **可嵌入的售票小部件:** 轻松将售票集成到任何网站。
- 🖥 **可定制的活动主页:** 通过灵活的设计选项创建引人注目的活动页面。
- 🔑 **直观的签到工具:** 使用 Hi.Events 的二维码签到工具轻松签到与会者。
- 💬 **活动消息工具:** 向与会者发送重要更新和提醒。
- 📝 **自定义订单表单:** 在结账时通过定制问题收集与会者信息。
- 🎫 **多种票种:** 免费、付费、捐赠或分级票种。
- 💸 **多功能促销代码:** 高度多功能的折扣代码。预售访问，多种折扣选项。
- 💰 **即时支付:** 通过无缝的 Stripe 集成享受即时支付。
- 🧾 **税费配置:** 按票种添加税费。
- 📦 **数据导出:** 将与会者和订单数据导出为 XLSX 或 CSV。
- 💻 **REST API:** 功能齐全的 REST API 用于自定义集成。
- 🔍 **SEO 工具:** 为每个活动自定义 SEO 设置。
- 🛒 **美观的结账流程:** 确保流畅、美观的结账体验。
- 🔐 **基于角色的访问:** 支持多用户角色。
- 💻 **在线活动支持:** 提供在线活动说明和链接。
- ⏪ **全额和部分退款支持:** 轻松管理全额和部分退款。
- 📧 **邮件通知:** 使用自动邮件通知让与会者知情。
- 📱 **移动响应:** 在任何设备上享受无缝体验。
- 🌐 **多语言支持:** 支持多种语言.
- 🎉 **以及更多！**

## 🚀 快速开始

有关详细的安装说明，请参阅我们的 [文档](https://hi.events/docs/getting-started)。如需快速开始，请按照以下步骤操作：

### 一键部署

[![在 DigitalOcean 上部署](https://www.deploytodo.com/do-btn-blue.svg)](https://github.com/HiEventsDev/hi.events-digitalocean)

[![在 Render 上部署](https://render.com/images/deploy-to-render-button.svg)](https://github.com/HiEventsDev/hi.events-render.com)

[![在 Railway 上部署](https://railway.app/button.svg)](https://railway.app/template/8CGKmu?referralCode=KvSr11)

[![在 Zeabur 上部署](https://zeabur.com/button.svg)](https://zeabur.com/templates/8DIRY6)

### 🐳 使用 Docker 快速开始

> [!重要]  
> 请确保您的系统上已安装 Docker 和 Docker Compose。如果没有，您可以从 Docker 官方网站下载：[Docker](https://www.docker.com/get-started)。

1. **克隆仓库：**
   ```bash
   git clone git@github.com:HiEventsDev/hi.events.git
   ```

2. **导航到 Docker 目录：**
   ```bash
   cd hi.events/docker/all-in-one
   ```

3. **启动 Docker 容器：**
   ```bash
   docker compose up -d
   ```
4. **创建一个账户：**
   ```bash
   打开浏览器并导航到 http://localhost:8123/auth/register。
   ```

ℹ️ 请参阅 [快速开始指南](https://hi.events/docs/getting-started) 了解其他安装方法，以及设置生产或本地开发环境的详细步骤。

## 📝 更新日志

请访问我们的 [GitHub 发布页面](https://github.com/HiEventsDev/hi.events/releases) 了解最新的改进和功能添加。

## 🤝 贡献

我们欢迎贡献、建议和错误报告！在提出新功能或扩展之前，请先打开一个问题进行讨论。

## ❓ 常见问题

有问题吗？我们的 [文档](https://hi.events/docs) 有答案。如果您找不到所需的信息，请随时通过 [support@garbagroove.com](mailto:support@garbagroove.com) 联系我们。

## 📜 许可证

Hi.Events 根据 [AGPL-3.0](https://github.com/HiEventsDev/hi.events/blob/main/LICENCE) 许可证条款进行许可。

有关更多许可信息，包括商业许可选项，请访问我们的许可页面 [此处](https://hi.events/licensing)。
