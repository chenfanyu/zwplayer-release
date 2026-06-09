<div align="center">
  <h1>🚀 ZWPlayer - Full-Stack Interactive HTML5 Video Player Ecosystem</h1>
  <p><strong>Enterprise-grade WebRTC / RTSP / HLS Player with 8 Zero-Code Online Tools</strong></p>

  [![Version](https://img.shields.io/badge/version-v3.3.0-blue.svg)]()
  [![License](https://img.shields.io/badge/license-Commercial-red.svg)]()

  [English](#english-version) | [简体中文](#chinese-version)
</div>

---

<h2 id="english-version">🇺🇸 English</h2>

**ZWPlayer** is an enterprise-grade interactive HTML5 video player and a comprehensive audiovisual ecosystem. With its plugin-free, ultra-fast core, it supports **WebRTC** ultra-low latency live streaming, plugin-free **RTSP** monitoring, and standard **HLS/DASH/FLV** formats. Powered by the proprietary **ZWMAP engine**, developers can easily build highly interactive and secure cross-platform video applications.

This repository (`zwplayer-release`) is dedicated to distributing the compiled artifacts (minified JS, CSS, and plugins) of ZWPlayer. **It contains no source code** and acts primarily as a CDN hub.

### 🌟 Key Features

- ⚡️ **Unified Protocol Architecture**: Seamlessly mix WebRTC (WHEP/ARTC/TRTC), RTSP, HLS, DASH, and FLV playback natively in the browser.
- 🛡️ **Enterprise DRM & Anti-Screen Recording**: Built-in dynamic marquee and tile watermarks with millisecond real-time rendering. Inject custom user data for precise leak tracing.
- 💡 **Interactive Video Elements**: Move beyond one-way viewing. Overlay quizzes, forms, branching choices, and 13 other dynamic nodes directly onto your videos.
- 🧩 **Cross-Framework Support**: Written in pure vanilla JS with official wrappings for **Vue 2/3** and **React**, featuring robust CSS isolation.
- 🔍 **Subtitle Engine & Full-Text Search**: Render dual-track subtitles (VTT/SRT/BCC/JSON) and allow users to search through dialogues to jump to specific scenes instantly.

### 🛠️ The 8 Visual Online Tools Ecosystem

To minimize integration barriers, ZWPlayer offers 8 out-of-the-box, zero-code visual online tools:

1. 📺 **[Online Video Player](https://www.zwplayer.com/zh/tools/videoplayer/)**: A full-featured testbed for any protocol, including drag-and-drop local playback, PiP, and casting.
2. ⚙️ **[Code Generator](https://www.zwplayer.com/zh/tools/generator/)**: Visually configure player parameters and instantly export ready-to-use HTML, Vue, or React snippets.
3. 🎯 **[Annotation Editor](https://www.zwplayer.com/zh/tools/annotation/)**: Drag and drop interactive hotspots, quizzes, and forms over your video timeline.
4. 📝 **[Subtitle Editor](https://www.zwplayer.com/zh/tools/subtitle/)**: Create and fine-tune VTT/SRT subtitles with a bilingual interface and precise timeline alignment.
5. 📑 **[Chapter Editor](https://www.zwplayer.com/zh/tools/chapter/)**: Visually segment long videos to auto-generate progress bar chapter markers and navigation menus.
6. 🖼️ **[Thumbnail Generator](https://www.zwplayer.com/zh/tools/thumbnail/)**: Extract keyframes entirely in the browser and automatically synthesize sprite sheets for progress bar previews.
7. 📋 **[Playlist Editor](https://www.zwplayer.com/zh/tools/playlist/)**: Build hierarchical JSON playlists ideal for online courses, TV series, or IPTV.
8. 💧 **[Watermark Editor](https://www.zwplayer.com/zh/tools/watermark/)**: WYSIWYG configuration for static logos and dynamic anti-recording marquee watermarks.

### 🧩 Framework Adapters

ZWPlayer ships official component packages for seamless integration with popular frameworks and CMS:

| Framework / Platform | NPM Package | Install | GitHub Demo | Gitee Demo |
|---|---|---|---|---|
| **Vue 2** | `zwplayer-vue2x` | `npm install zwplayer-vue2x --save` | [GitHub](https://github.com/chenfanyu/zwplayer-vue2x-demo) | [Gitee](https://gitee.com/chenfanyu/zwplayer-vue2x-demo) |
| **Vue 3** | `zwplayervue3` | `npm install zwplayervue3 --save` | [GitHub](https://github.com/chenfanyu/zwplayervue3-demo) | [Gitee](https://gitee.com/chenfanyu/zwplayervue3-demo) |
| **React** | `zwplayer-react` | `npm i zwplayer-react --save` | [GitHub](https://github.com/chenfanyu/zwplayer-react-demo) | [Gitee](https://gitee.com/chenfanyu/zwplayer-react-demo) |
| **WordPress** | — | [WordPress Plugin Directory](https://wordpress.org/plugins/zw-player-video-embed/) | — | — |

**Quick Example:**

```js
// Vue 2 / Vue 3
import { zwplayer } from 'zwplayer-vue2x'   // or 'zwplayervue3'

// React (supports React 16.8+ / 17 / 18 / 19)
import { ZwPlayer } from 'zwplayer-react'
```

**WordPress** — install [ZW Player Video Embed](https://wordpress.org/plugins/zw-player-video-embed/) directly from the plugin directory. Supports Gutenberg block, classic editor button, and `[zwplviem]` shortcode:

```
[zwplviem url="https://example.com/video.mp4" autoplay="true"]
```

Covers HLS, DASH, FLV, WebRTC, RTSP live streaming, dual subtitles, chapters, watermark, and more. See the [WordPress integration guide](https://www.zwplayer.com/plugin/wordpress.html) for details.

### 📥 Download & Usage

You can easily load ZWPlayer's compiled assets directly via our official CDN:
```html
<script src="https://cdn.zwplayer.com/v3/zwplayer/zwplayer.js"></script>
```

*(Alternatively, since this repository is public, it is also automatically mirrored and served globally via public open-source CDNs like jsDelivr)*

Please visit the [official documentation](https://www.zwplayer.com/) for the latest builds and integration guides.

- 📖 **Official Site & Documentation**: [https://www.zwplayer.com/](https://www.zwplayer.com/)

---

<h2 id="chinese-version">🇨🇳 简体中文</h2>

**ZWPlayer** 不仅仅是一个纯前端网页播放器，更是为企业量身定制的**全链路视音频交互工作流**。基于免插件的极速内核，支持 **WebRTC** 超低延迟直播、**RTSP** 免插件安防监控以及标准 **HLS/DASH/FLV** 点播流。凭借独创的 **ZWMAP 统一交互数据协议**，开发者能以极低门槛打造高互动、强安全、多端的视频应用。

本仓库 (`zwplayer-release`) 专用于分发 ZWPlayer 核心构建产物（包含混淆压缩后的 `.js`、`.css` 以及各类插件）。**本库不含源码**，主要作为 CDN 分发中心。

### 🌟 核心特性 (Key Features)

- ⚡️ **全流媒体协议融合**：单页面无缝混播 WebRTC (支持 WHEP/ARTC/TRTC)、RTSP (免插件直连)、HLS、DASH 和 FLV。
- 🛡️ **企业级防盗防录屏**：内置动态跑马灯水印 (Marquee Watermark) 与全屏平铺水印，毫秒级实时渲染，支持注入自定义用户信息以进行精准防录屏溯源。
- 💡 **双向交互式视频体验**：突破单向观看！原生支持在视频内叠加测验题、表单、分支选项、网页嵌入等 13 种动态节点。
- 🧩 **现代框架原生适配**：采用纯 JavaScript 编写，原生提供 **Vue 2/3** 与 **React** 组件接入方式，彻底解决样式污染。
- 🔍 **全格式字幕与检索**：支持双轨外挂字幕 (VTT/SRT/BCC/JSON)，内建全局字幕与章节实时检索面板，台词秒级跳转。

### 🛠️ 完善的在线工具生态 (8 大零代码可视化工具)

为了极大降低集成和开发成本，ZWPlayer 官方配备了 8 款免安装、即开即用的在线可视化编辑器：

1. 📺 **[在线全能播放器](https://www.zwplayer.com/zh/tools/videoplayer/)**：支持所有格式的在线试播、本地文件免上传拖拽播放，含弹幕、倍速、投屏、画中画测试。
2. ⚙️ **[代码生成器](https://www.zwplayer.com/zh/tools/generator/)**：可视化调节播放器几百种参数，实时预览，一键导出可用的 HTML / Vue / React 接入代码。
3. 🎯 **[交互标注编辑器 (Annotation Editor)](https://www.zwplayer.com/zh/tools/annotation/)**：无需写代码，拖拽式设计视频内的测验、投票、热区，一键导出交互配置。
4. 📝 **[字幕编辑器 (Subtitle Editor)](https://www.zwplayer.com/zh/tools/subtitle/)**：在线制作和微调多语种外挂字幕，支持双语对照与时间轴高精度对齐。
5. 📑 **[章节编辑器 (Chapter Editor)](https://www.zwplayer.com/zh/tools/chapter/)**：为长视频打点分章，自动生成播放进度条上的彩色标记及导航目录。
6. 🖼️ **[缩略图生成器 (Thumbnail Generator)](https://www.zwplayer.com/zh/tools/thumbnail/)**：纯前端无损提取视频关键帧，一键合成进度条预览所需的雪碧图 (Sprite Sheet)。
7. 📋 **[双级播放列表编辑器 (Playlist Editor)](https://www.zwplayer.com/zh/tools/playlist/)**：可视化构建带有层级目录的剧集或课程列表，完美适配网课及 IPTV 场景。
8. 💧 **[水印编辑器 (Watermark Editor)](https://www.zwplayer.com/zh/tools/watermark/)**：所见即所得地调整防录屏跑马灯、静态 Logo 的大小与透明度。

### 🧩 框架适配器 (Framework Adapters)

ZWPlayer 提供官方框架组件包，可无缝集成到主流前端框架和 CMS 中：

| 框架 / 平台 | NPM 包名 | 安装命令 | GitHub 示例 | Gitee 示例 |
|---|---|---|---|---|
| **Vue 2** | `zwplayer-vue2x` | `npm install zwplayer-vue2x --save` | [GitHub](https://github.com/chenfanyu/zwplayer-vue2x-demo) | [Gitee](https://gitee.com/chenfanyu/zwplayer-vue2x-demo) |
| **Vue 3** | `zwplayervue3` | `npm install zwplayervue3 --save` | [GitHub](https://github.com/chenfanyu/zwplayervue3-demo) | [Gitee](https://gitee.com/chenfanyu/zwplayervue3-demo) |
| **React** | `zwplayer-react` | `npm i zwplayer-react --save` | [GitHub](https://github.com/chenfanyu/zwplayer-react-demo) | [Gitee](https://gitee.com/chenfanyu/zwplayer-react-demo) |
| **WordPress** | — | [WordPress 插件目录](https://wordpress.org/plugins/zw-player-video-embed/) | — | — |

**快速示例：**

```js
// Vue 2 / Vue 3
import { zwplayer } from 'zwplayer-vue2x'   // 或 'zwplayervue3'

// React (支持 React 16.8+ / 17 / 18 / 19)
import { ZwPlayer } from 'zwplayer-react'
```

**WordPress** — 直接在插件市场安装 [ZW Player Video Embed](https://wordpress.org/plugins/zw-player-video-embed/)，支持 Gutenberg 区块编辑器、经典编辑器按钮及 `[zwplviem]` 短代码：

```
[zwplviem url="https://example.com/video.mp4" autoplay="true"]
```

覆盖 HLS、DASH、FLV、WebRTC、RTSP 直播流、双字幕、章节、水印等全部功能。详情参阅 [WordPress 集成文档](https://www.zwplayer.com/plugin/wordpress.html)。

### 📥 下载与引用

你可以直接通过官方专属 CDN 获取最新的构建资源：
```html
<script src="https://cdn.zwplayer.com/v3/zwplayer/zwplayer.js"></script>
```

*(如果你更倾向于使用免费的开源镜像加速，本仓库也会通过 GitHub 自动同步到 jsDelivr 等公共 CDN 节点)*

请前往 [官方文档](https://www.zwplayer.com/) 获取最新版本的更多接入指引。

- 📖 **官方文档与演示**：[https://www.zwplayer.com/zh](https://www.zwplayer.com/)
