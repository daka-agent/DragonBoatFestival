<p align="center">
  <img src="https://em-content.zobj.net/source/apple/391/dragon-face_1f409.png" width="80">
</p>

<h1 align="center">端午文化探险</h1>
<p align="center">
  <strong>Dragon Boat Festival Game</strong> — 一款面向 Z 世代的端午文化 H5 小游戏
</p>

<p align="center">
  <a href="#-在线体验">在线游玩</a> •
  <a href="#-游戏截图">截图</a> •
  <a href="#-三关玩法">玩法</a> •
  <a href="#-技术特点">技术</a> •
  <a href="#-快速开始">开始</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/版本-v1.2-red?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/风格-国潮水墨-c41e3a?style=flat-square" alt="Style">
  <img src="https://img.shields.io/badge/HTML5-单文件-orange?style=flat-square&logo=html5" alt="HTML5">
  <img src="https://img.shields.io/badge/依赖-零CDN-green?style=flat-square" alt="No Dependencies">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License">
</p>

---

## 📖 简介

屈原穿越时空来到现代，带来了被遗忘的**端午文化碎片**。玩家需要通过三关挑战，帮他把文化记忆传递给更多人。

> *屈原的肉身随江水而去，但他留下的诗篇、节日与精神，两千年来从未离开——这就是文化的力量。*

本项目为**广东财经大学 23 物流 2 班**端午节班级活动设计，通过互动游戏传递传统文化，适合公众号推送和手机端传播。

## 🖼️ 游戏截图

| 🏠 标题页 | 🥁 第一关·击鼓 | 🍃 第三关·投粽 |
|:---:|:---:|:---:|
| 国潮水墨开场 | 节奏敲击鼓面 | CSS 锥形粽子投掷 |

> 💡 实际效果请访问 [在线体验地址](#-在线体验)

## 🎮 三关玩法

| 关卡 | 操作 | 文化内涵 |
|:---|:---|:---|
| 🥁 **击鼓传声** | 点击鼓面 / 按空格键，跟随节奏敲击 | 龙舟非遗 · 鼓点韵律 |
| 📜 **端午问答** | 4 选 1 知识问答，共 5 题 | 楚辞诗词 · 节日习俗 · 历史典故 |
| 🍃 **投粽入江** | 点击粽子投入江中，击退鱼群 | 粽子起源 · 南北差异 · 地域文化 |

🎉 **通关奖励**：解锁端午祝福分享卡 + 屈原寄语

## ⌨️ 操作指南

```
📱 手机端：直接点击屏幕操作（触屏优化）
🖥️ 电脑端：鼠标点击 + 空格键 / 回车键
🔊 音效：Web Audio API 自动生成，无需额外文件
```

## 🛠️ 技术特点

| 特性 | 说明 |
|:---|:---|
| **单文件架构** | `duanwu.html` 一个文件包含 HTML + CSS + JS 全部代码 |
| **零外部依赖** | 无 CDN、无框架、无构建工具，打开即玩 |
| **离线可用** | 下载后断网也能运行，支持微信内嵌浏览 |
| **Web Audio 音效** | 程序化生成鼓声、水声、命中音效，无需音频文件 |
| **CSS 粽子造型** | `clip-path` 绘制三角锥形粽子（碱水粽 / 肉粽 / 甜粽） |
| **响应式布局** | 自适应手机（375px）到桌面（1440px） |
| **本地排行榜** | localStorage 存储，保护隐私 |

## 🎨 视觉设计

| 元素 | 设计方案 |
|:---|:---|
| 主色调 | 朱砂红 `#c41e3a` → 墨黑过渡 |
| 辅助色 | 宣纸白 `#fffae8` / 金色点缀 `#d4af37` |
| 背景 | 水墨纹理渐变 + 微动效 |
| 字体 | PingFang SC / Microsoft YaHei 中文字体栈 |
| 风格定位 | 国潮 × 水墨 × 现代 UI |

## 🚀 在线体验

### 👉 [daka-agent.github.io/DragonBoatFestival](https://daka-agent.github.io/DragonBoatFestival/duanwu.html)

> 支持 Chrome / Safari / Edge / 微信内置浏览器

### 本地运行

```bash
# 方式一：直接双击打开
duanwu.html

# 方式二：本地服务器（推荐调试用）
python -m http.server 8080
# 浏览器访问 http://localhost:8080/duanwu.html
```

## 📁 项目结构

```
DragonBoatFestival/
├── duanwu.html      # 游戏主文件（~970 行，含 HTML/CSS/JS）
└── README.md        # 项目说明文档
```

## 📌 设计原则

1. **正能量叙事** — 不渲染投江悲剧，聚焦「文化传承」精神内核
2. **寓教于乐** — 楚辞、习俗、节气知识自然融入关卡
3. **轻量易传播** — 单文件 = 即分享，适配手机和电脑双端
4. **隐私优先** — 本地存储为主，不强制联网，不采集数据

## 🔧 技术栈

```
HTML5 + CSS3 + Vanilla JavaScript
├── Web Audio API        （程序化音效引擎）
├── CSS clip-path        （粽子几何造型）
├── CSS Animations       （飞行动画 / 波浪 / 光晕）
├── requestAnimationFrame（游戏主循环 / 鱼群游动）
└── localStorage         （本地排行榜）
```

## 📅 版本历史

| 版本 | 日期 | 更新内容 |
|:---|:---|:---|
| v1.0 | 2026-06-08 | 基础三关流程完成 |
| v1.1 | 2026-06-08 | 修复第三关碰撞检测；新增命中光环反馈 |
| v1.2 | 2026-06-08 | 重构第三关布局；CSS 锥形粽子；修复鼓面点击 |

## 🏗️ 开发信息

| 项目 | 内容 |
|:---|:---|
| 开发者 | 大卡 ([@daka-agent](https://github.com/daka-agent)) |
| 所属 | 广东财经大学 23 物流 2 班 |
| 场景 | 端午节班级公众号推送 H5 |
| 目标用户 | Z 世代学生群体 |

## 📜 License

[MIT License](LICENSE) © 2026 大卡

自由使用、修改和分享。

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/daka-agent">大卡</a> @ GDUFE
</p>
