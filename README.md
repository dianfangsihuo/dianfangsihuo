<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f172a,42:6d28d9,76:06b6d4,100:22c55e&text=%E7%AA%A6%E4%B9%A6%E8%88%AA%20%7C%20AI%20Product%20Builder&fontColor=ffffff&fontSize=38&fontAlignY=36&desc=AI%20Gateway%20%C2%B7%20Agentic%20Coding%20%C2%B7%20ComfyUI%20%C2%B7%20Local%20AI&descAlignY=58&animation=fadeIn" alt="窦书航 | AI Product Builder" />
</p>

<p align="center">
  <a href="https://api.dianfangsihuo.tech"><img src="https://img.shields.io/badge/Dianfang_API-在线服务-6d28d9?style=for-the-badge&logo=openai&logoColor=white" /></a>
  <a href="https://api.dianfangsihuo.tech/docs"><img src="https://img.shields.io/badge/API_文档-快速开始-06b6d4?style=for-the-badge&logo=readthedocs&logoColor=white" /></a>
  <a href="https://status.dianfangsihuo.tech"><img src="https://img.shields.io/badge/服务状态-Status-22c55e?style=for-the-badge&logo=statuspage&logoColor=white" /></a>
  <a href="https://space.bilibili.com/476191884"><img src="https://img.shields.io/badge/Bilibili-殿方四火-00a1d6?style=for-the-badge&logo=bilibili&logoColor=white" /></a>
</p>

<p align="center">
  <strong>把模型、工具调用、语音、视觉工作流和真实业务接成可交付产品。</strong><br/>
  Building AI systems that can code, create, speak, use tools, and ship.
</p>

---

## 现在主要在做什么

我目前就读于郑州轻工业大学计算机科学与技术专业。最近的工作已经从单点 AI Demo，延伸到 **模型服务、Agentic Coding、ComfyUI 创作工具、Windows 本地 AI 与完整产品交付**。

```text
Dianfang AI Stack
├─ Model Gateway    多模型接入、计费、路由、故障切换与状态监控
├─ Agentic Coding   Codex / Claude Code 工具链、兼容层与自动化
├─ Visual Workflow  ComfyUI 提示词工作台、LoRA 管理与 3D 作品画廊
├─ Voice Workflow   FunASR、翻译、GPT-SoVITS 与自动播报
└─ Product Delivery React / Electron / FastAPI / Three.js / PowerShell
```

---

## Dianfang API

<p align="center">
  <img src="https://api.dianfangsihuo.tech/logo.png?v=8" width="120" alt="Dianfang API anime mascot" />
</p>

[Dianfang API](https://api.dianfangsihuo.tech) 是我正在持续运营的多模型 API 中转服务。它不只是一个接口页面，而是一套包含 **模型路由、余额计费、充值兑换、流式调用、故障兜底、使用文档和状态监控** 的线上产品。

| 能力 | 当前进展 |
| --- | --- |
| 模型路线 | GPT、Claude、Grok、图像生成等多类模型 |
| 接入方式 | OpenAI-compatible API、流式与非流式调用 |
| 充值体验 | ¥0.88 = $1 站内额度，提供 $1–$100 多档购买 |
| 可用性 | 主渠道 + 分级兜底，并对真实请求与渠道状态进行监控 |
| 新用户 | 注册赠送 $0.10；邀请双方各赠送 $0.25 |
| 使用支持 | 购买、兑换码、API Key、Base URL、日志查询完整文档 |

当前站内展示的参考口径：

- GPT‑5.6：约为官网价格的 **3.3%**
- Claude：约为官网价格的 **4.1%**
- Grok：约为官网价格的 **2.4%**
- GPT Image 2：约 **¥0.088 / 次**

> 价格与模型可用性会随上游成本动态调整，最终以 [Dianfang API 定价页](https://api.dianfangsihuo.tech/pricing) 和站内公告为准。目前为防止滥用，仅支持 QQ 邮箱注册。

<p align="center">
  <a href="https://api.dianfangsihuo.tech"><b>进入控制台</b></a>
  ·
  <a href="https://api.dianfangsihuo.tech/docs"><b>阅读使用文档</b></a>
  ·
  <a href="https://api.dianfangsihuo.tech/store"><b>购买额度</b></a>
</p>

---

## 最近的公开项目

### 1. [ComfyUI WebUI Prompt Bridge](https://github.com/dianfangsihuo/ComfyUI-WebUI-Prompt-Bridge)

把 WebUI 式的提示词体验真正带进 ComfyUI。它已经从“提示词输入节点”发展成一套完整工作台，支持中文翻译、Tag 编辑、自动补全、收藏、LoRA 浏览与真实加载、模型切换、区域控制、生成参数接管，以及 ADetailer / ControlNet / Inpaint 等高级模块入口。

- 最新公开版本：**v0.4.23**
- 已注册 Comfy Registry：`comfyui-webui-prompt-bridge`
- 支持本地完整词库回退、全库搜索、窄版布局与可调摘要阈值
- 提供 Anima / Qwen、SDXL、图生图最小工作流与中文教程

### 2. [ComfyUI Image Hang Gallery](https://github.com/dianfangsihuo/ComfyUI-ImageHang-Gallery)

让 ComfyUI 生成图直接进入一个可行走、可编辑的 3D 画廊。扩展会自动收集作品，并支持第一人称观赏、俯视编辑、扩建房间、挂画调整和跨浏览器本地保存。

- ComfyUI 内置作品管理面板
- 一键启动独立 Three.js 3D 画廊
- 作品、房间、墙体、门与布局均保存为本地项目数据
- [Bilibili 演示视频](https://www.bilibili.com/video/BV1ruLb69Ecc/)

### 3. [Voxel Terra](https://github.com/dianfangsihuo/voxel-terra)

一个由 GPT‑5.6‑Sol 在 Codex 中从空仓库完成的浏览器 3D 生存游戏实验。它不是预渲染概念 Demo，而是包含程序化世界、生存循环、合成、熔炼、装备、附魔、村庄、交易、生物 AI、昼夜天气和存档系统的可运行项目。

- TypeScript 5.9 · React 19 · Three.js · WebGL · Zustand
- 20 个测试文件、166 项测试
- 桌面与移动端真实浏览器验收
- 记录 AI 原生软件开发的速度与复杂度上限

### 4. [Claude Code 中文启动器](https://github.com/dianfangsihuo/claude-code-zh-launcher)

面向 Windows 的 Claude Code 一键安装、中文配置与多服务商启动器。支持 OpenAI-compatible 中转、DeepSeek、OpenRouter、硅基流动等服务，并尽量保留模型的 thinking / reasoning 能力。

### 5. Codex 与本地 AI 工具

- [Codex Session Visibility Repair](https://github.com/dianfangsihuo/codex-session-visibility-repair)：诊断和修复 Windows Codex Desktop 会话存在但侧边栏不显示的问题。
- [Codex OAuth Refresh Tools](https://github.com/dianfangsihuo/codex-oauth-refresh-tools)：面向自有/获授权账号的本地 OAuth 凭证管理与刷新工具。
- [GPT-SoVITS Codex Voice](https://github.com/dianfangsihuo/gptsovits-codex-voice-skill)：监听 Codex 新回复，通过本地 GPT-SoVITS 自动合成并播放语音。
- [Local ASR + Translation + TTS](https://github.com/dianfangsihuo/local-asr-translation-tts)：浏览器录音、FunASR 识别、本地翻译与 GPT-SoVITS 播放的一体化工具。

---

## 技术栈

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/ComfyUI-Workflow-6d28d9?style=flat-square" />
</p>

主要关注：

- AI Gateway、模型兼容层、计费与可靠性工程
- Codex / Claude Code Agentic Coding 工作流
- MCP、工具调用、多 Agent 协作与任务可观测性
- ComfyUI、LoRA、提示词工程与可复用视觉管线
- FunASR、GPT-SoVITS 与本地多模态交互
- React / Electron / FastAPI / Three.js 端到端产品交付

---

## GitHub Signal

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=dianfangsihuo&theme=tokyo-night&hide_border=true&area=true&custom_title=Building%20in%20Public" alt="GitHub contribution graph" />
</p>

---

## 联系我

- Email: [dianfangsihuo@gmail.com](mailto:dianfangsihuo@gmail.com)
- Bilibili: [殿方四火](https://space.bilibili.com/476191884)
- Pixiv: [109349091](https://www.pixiv.net/users/109349091)
- GitHub: [@dianfangsihuo](https://github.com/dianfangsihuo)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:22c55e,40:06b6d4,75:6d28d9,100:0f172a" alt="footer" />
</p>
