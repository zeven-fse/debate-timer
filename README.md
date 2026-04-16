# debate-timer
A pure vanilla JS debate timer featuring chess-clock logic and native Web Audio API alerts. Zero dependencies, optimized for offline big-screen projection.
# Debate Timer System | 辩论赛现场控制系统

[![Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-f7df1e?style=flat-square&logo=javascript&logoColor=black)]()
[![Web Audio API](https://img.shields.io/badge/API-Web_Audio-0052CC?style=flat-square)]()
[![Zero Dependency](https://img.shields.io/badge/Dependencies-0-success?style=flat-square)]()

A pure frontend, zero-dependency web application designed for offline formal debate competitions. Built with HTML, CSS, and Vanilla JavaScript, featuring chess-clock logic and native synthesized audio alerts.

这是一个专为线下正式辩论赛设计的纯前端网页计时系统。采用单文件、零依赖开发，完美还原赛制逻辑，无需联网或部署后端即可在任意浏览器中运行。

## 🌐 Live Demo / 在线体验
**[Click here to use the system directly / 点击这里直接使用系统](https://您的用户名.github.io/debate-timer/)**
*(Note: Press `F11` for the best full-screen projection experience / 提示：按 `F11` 进入全屏模式获得最佳投影体验)*

---

## ✨ Key Features / 核心特性

- **Zero-Dependency Architecture / 纯粹的单文件架构** Built entirely with inline HTML, CSS, and Vanilla JS. No npm, Webpack, or external libraries required.  
  HTML + CSS + JS 内联编写，无需任何构建工具或外部依赖，双击即用。

- **Chess-Clock Algorithm / “象棋钟”交替计时算法** Deeply customized for the "Free Debate" and "Cross-Examination" stages. Supports a global hotkey (`Spacebar`) to seamlessly switch speaking turns, preventing operator panic.  
  针对自由辩论与对辩环节深度定制，支持全局快捷键（空格键）一键无缝切换双方发言权，防止场控手忙脚乱。

- **Native Web Audio Engine / 原生底层的合成音效** Discards traditional external MP3 files. Utilizes the underlying `AudioContext` to generate square waves (beep) in real-time, eliminating network latency or browser media policy blocking.  
  摒弃了传统的外部音频文件加载方式，直接通过底层 `AudioContext` 实时合成方波提示音，彻底杜绝音频加载失败、网络延迟或浏览器自动播放策略拦截的风险。

- **Dynamic Visual Feedback / 动态视觉反馈** Built-in 30-second warning (color blinking) and 0-second timeout alert (screen flashing). UI is adapted to a dark tech style, optimized for large screen projections.  
  内置 30 秒警告（颜色闪烁）与 0 秒超时警报（屏幕强闪），UI 适配深色科技风，专为大屏幕投影优化。

---

## 🎮 Operation Guide / 操作指南

1. Click the top navigation bar to switch between different debate stages. / 点击顶部导航栏切换不同的赛制环节。
2. In "Free Debate" and "Cross-Examination" stages, press **`Spacebar`** to alternate speaking turns. / 在“自由辩论”与“对辩”环节，使用 **空格键 (Space)** 进行发言权交替。
3. **Developer Quick Test:** Press **`T`** to set the timer to 35 seconds across all stages for rapid rehearsal of audio and visual warnings. / **开发者测试秘籍:** 在任意环节按下 **`T`** 键，可将时间快速跳转至 35 秒，用于快速彩排测试音效及闪烁逻辑。
