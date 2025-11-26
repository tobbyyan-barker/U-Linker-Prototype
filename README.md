# 🚀 U-Linker 校园互助平台 (Prototype Design)

> 🏆 软工实践 -  2025 秋季 EE308FZ G1 

U-Linker 是一个打破校园信息孤岛、实现技能与需求精准对接的互助平台。针对现有校园群消息杂乱、交易无保障的痛点，我们设计了这套**双角色切换**与**全流程闭环**的交互原型。

---

## 📂 答辩 PPT 下载 (Download)

为了获得最佳的阅读与交互体验，我们提供了两种格式供查阅：

| 文件类型 | 文件名 | 说明 |
| :--- | :--- | :--- |
| **📄 在线阅览版** | [Presentation_Slides.pdf](./U-Linker-AS4_答辩.pdf) | **推荐**:PDF格式，排版稳定，适合快速评审。 |
| **🎬 完整演示版** | [Presentation_Source.pptx](./U-Linker-AS4_答辩.pptx) | 内含完整交互动画与逻辑演示，建议下载观看。 |

*(注：点击文件名即可查看或下载)*

---

## ✨ 核心功能演示 (Highlights)

本项目原型使用 **墨刀 (MoDao)** 制作，以下是我们的核心交互设计亮点：

### 1. 引导式发布 (Smart Publishing)
通过结构化的占位符与悬浮按钮设计，将复杂的发布流程压缩至 3 步以内，极大降低了用户的认知负荷。

![我需要演示](./images/我需要演示2.gif)
![我能提供演示](./images/我能提供演示2.gif)

### 2. 双角色无缝切换 (Dual-Role Switching)
同一账号支持“雇主”与“帮手”两种身份。通过顶部 Tab 一键切换，UI 主色调随之改变（蓝/灰），有效防止操作混淆。

![双端界面演示](./images/双端界面展示.gif)

### 3. 交易安全机制 (Transaction Safety)
针对 C2C 交易的信任问题，我们设计了“二次确认弹窗”与“防骚扰冷却机制”，保障积分安全与用户体验。

![安全交互演示](./images/安全交互演示3.gif)

---


## 🛠️ 技术栈规划 (Tech Stack)

* **Design Tool:** 墨刀 (MoDao), 即时设计 (JsDesign)
* **Frontend:** 微信小程序 (WeChat Mini Program)
* **Backend:** Python Flask
* **Database:** MySQL

---

Copyright © 2025 U-Linker Team. All Rights Reserved.
