# 镜界 · 液态玻璃落地页

✦ 一款采用**液态玻璃（Glassmorphism）** 风格的小程序品牌落地页。

## 设计亮点

- **动态流体背景** — 三色光晕缓慢浮动，营造液态流动感
- **玻璃拟态卡片** — `backdrop-filter: blur()` 实现磨砂玻璃质感
- **虹彩渐变边框** — 图标和玻璃元素带有光折射般的渐变色描边
- **极简暗色主题** — 深色背景凸显玻璃通透感，减少视觉干扰
- **固定导航栏** — 毛玻璃效果导航，平滑滚动定位

## 技术栈

- 纯 HTML + CSS，零依赖
- Google Fonts: Syne（标题）+ DM Sans（正文）
- CSS `backdrop-filter` 玻璃效果
- CSS `@keyframes` 流体动画

## 在线预览

👉 https://1994umbrella.github.io/mirror-landing/

## 本地运行

```bash
git clone https://github.com/1994Umbrella/mirror-landing.git
# 直接用浏览器打开 index.html
```

## 自定义

修改 `index.html` 中的以下内容即可适配你的项目：

- 标题/描述（`<h1>` / `<p>`）
- 功能卡片文字
- 图标样式
- 品牌色（CSS 变量 `--accent-*`）
