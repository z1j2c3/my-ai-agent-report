# 我的 AI Agent 使用报告

一份单页静态报告，记录我在日常与工作中实际使用的三个 AI Agent：**豆包**、**DeepSeek**、**WorkBuddy**。

## 在线访问

通过 GitHub Pages 发布：<https://z1j2c3.github.io/my-ai-agent-report/>

## 页面结构

| 章节 | 内容 |
| --- | --- |
| Hero | 报告标题、导语、关键指标、作者信息 |
| 01 / Agent Map | 三个 Agent 的定位、使用场景与实践状态，附使用强度对比 |
| 02 / Playbook | 五条协作心得，以及在长期使用中总结出的结论 |

## 三个 Agent 的分工

- **WorkBuddy** — 主力协作。不只用嘴回答，而是直接读文件、写代码、跑命令、交付成品。
- **豆包** — 轻量高频。随身问答层，把模糊想法先聊清楚。
- **DeepSeek** — 深度推理。推理过程可见，适合需要多步推导的问题。

## 本地预览

直接用浏览器打开 `index.html` 即可，无需构建、无外部依赖（字体、样式、交互全部内联）。

## 技术说明

- 纯静态 HTML + CSS + 少量原生 JS（滚动渐显 IntersectionObserver）
- 响应式布局，适配桌面与移动端
- 支持 `prefers-reduced-motion` 无障碍降级
