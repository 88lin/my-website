# 88lin · 茉灵智库 ✦

我的个人网站 —— 一个 AI 研究者与 Agent 工程实践者的数字花园。

## 设计

- **苹果字体** — 全站采用 SF Pro / PingFang 系统栈，标题大对比、正文舒适
- **Three.js 星野** — 首屏 WebGL 粒子背景，随鼠标与滚动缓慢漂移
- **荧光笔高亮 + Bento 网格** — 作品集用不规则卡片网格，鼠标聚光灯跟随
- **设计 Token** — 配色遵循 [mydesign-system](https://github.com/88lin/mydesign-system) 语义化 token，主色 60 / 强调 30 / 点缀 10

## 页面结构

1. **Hero** — 3D 星野 + 一句话定位「把前沿 AI，做成能交付的东西」
2. **关于我** — 自我介绍 + 终端卡片 + 实时统计（建站天数 / Stars / 文章 / 入口）
3. **精选项目** — Bento 网格：video_vip、lofi-radio-web、computer-repair-skill 等
4. **站点矩阵** — 博客、导航站、维修站、Lofi Radio、深度研究等
5. **最新文章** — 来自 [茉灵智库博客](https://blog.88lin.eu.org) 的最新内容
6. **联系** — 邮箱 / QQ 群 / 公众号 / B 站 / GitHub

## 交互细节

- 顶部玻璃导航随深浅背景自动换色，滚动联动高亮当前区块
- 项目走马灯、滚动计数、卡片聚光灯、自定义光标（仅桌面）
- 完整响应式；`prefers-reduced-motion` 下自动降级动效

## 相关链接

| 名称 | 地址 |
|------|------|
| 博客 | [blog.88lin.eu.org](https://blog.88lin.eu.org) |
| 导航站 | [go.88lin.eu.org](https://go.88lin.eu.org) |
| 设计系统 | [mydesign-system](https://github.com/88lin/mydesign-system) |
| GitHub | [github.com/88lin](https://github.com/88lin) |

## 技术栈

纯前端，零框架。HTML + CSS + Vanilla JS + Three.js（CDN 引入）。可直接部署在 GitHub Pages。

## License

设计参考了开源个人网站模板的思路，遵循 [CC BY-NC 4.0](./LICENSE.md) — 可以看、学习、参考，但请注明出处，不可商用。
