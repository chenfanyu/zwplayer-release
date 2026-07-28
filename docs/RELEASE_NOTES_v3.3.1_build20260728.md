# 🚀 ZWPlayer v3.3.1 (Build 20260728)

[![Version](https://img.shields.io/badge/version-v3.3.1-blue.svg)]()
[![Build](https://img.shields.io/badge/build-20260728-green.svg)]()
[![License](https://img.shields.io/badge/license-Free%20(inc.%20commercial)-brightgreen.svg)]()

> 🇺🇸 English | [🇨🇳 简体中文](#-简体中文)

A feature release adding native VR/360° panoramic playback and multi-audio-track support to the ZWPlayer ecosystem.

## 📦 Download

| Asset | Description |
|---|---|
| `zwplayer-v3.3.1-build20260728.zip` | Full build (minified JS + CSS + plugins) — attached to this release |
| CDN | `<script src="https://cdn.zwplayer.com/v3/zwplayer/zwplayer.js"></script>` |

## ✨ v3.3.1 Highlights

- 🥽 **VR / 360° Panoramic Playback**: Native equirectangular 360° video support — any protocol (MP4/HLS/FLV/DASH/WebRTC/RTSP) can carry panoramic content. Auto-detects 2:1 panoramic videos and activates spherical rendering. Interactive controls: mouse drag, touch gestures, arrow keys. Built-in view settings panel with live Yaw/Pitch/FOV preview and one-click config copy.
- 🎵 **Multi-Audio-Track Switching**: Dynamic loading and seamless switching of external multi-language audio tracks via `audioTracks` config. Frame-level sync, zero-stutter switching. Plus TTS subtitle-to-speech synthesis.
- 🎨 **Control Bar Polish**: Streamlined control bar UI with refined time progress, speed controller, and playback state indicators.
- 🌐 **Framework Coverage**: Vue 2/3, React components, and WordPress plugin upgraded in sync.

## ⚙️ Quick Start (VR)

```js
// Simple: auto-detect panoramic videos
new ZWPlayer({ playerElm: '#mse', url: '360video.mp4', vr: true });

// Custom initial view
new ZWPlayer({ playerElm: '#mse', url: '360video.mp4', vr: { yaw: 90, pitch: -10, fov: 80 } });
```

## ⬆️ Upgrade

Replace `zwplayer` — **fully backward compatible**, all new features are opt-in.

## 📖 Links

- 📚 Full changelog: https://www.zwplayer.com/changelog
- 🛠️ Online tools: https://www.zwplayer.com/tools/

---

<a id="-简体中文"></a>
# 🚀 ZWPlayer v3.3.1 (Build 20260728)

[![Version](https://img.shields.io/badge/version-v3.3.1-blue.svg)]()
[![Build](https://img.shields.io/badge/build-20260728-green.svg)]()
[![License](https://img.shields.io/badge/license-Free%20(inc.%20commercial)-brightgreen.svg)]()

为 ZWPlayer 生态新增原生 VR/360° 全景播放与多音轨支持的功能版本。

## 📦 下载

| 资源 | 说明 |
|---|---|
| `zwplayer-v3.3.1-build20260728.zip` | 完整构建（压缩混淆 JS + CSS + 插件）——见本发布附件 |
| CDN | `<script src="https://cdn.zwplayer.com/v3/zwplayer/zwplayer.js"></script>` |

## ✨ v3.3.1 核心特性

- 🥽 **VR / 360° 全景播放**：原生支持等距柱状 360° 视频，任意协议（MP4/HLS/FLV/DASH/WebRTC/RTSP）均可承载全景内容。自动检测 2:1 全景视频并激活球面渲染。交互控制：鼠标拖拽、触摸手势、方向键。内置视角设置面板，支持偏航/俯仰/视场角实时预览与一键复制配置。
- 🎵 **多音轨智能切换**：通过 `audioTracks` 配置动态加载外挂多语言音轨，无缝切换。帧级同步，切换零卡顿。并支持 TTS 字幕转语音合成。
- 🎨 **控制条优化**：简洁化控制条界面，优化时间进度条、倍速控制器与播放状态指示。
- 🌐 **框架生态**：Vue 2/3、React 组件与 WordPress 插件同步升级。

## ⚙️ 快速上手（VR）

```js
// 简单启用：自动检测全景视频
new ZWPlayer({ playerElm: '#mse', url: '360video.mp4', vr: true });

// 自定义初始视角
new ZWPlayer({ playerElm: '#mse', url: '360video.mp4', vr: { yaw: 90, pitch: -10, fov: 80 } });
```

## ⬆️ 升级

替换 `zwplayer目录` 即可，**完全向后兼容**，所有新功能均为可选启用。

## 📖 相关链接

- 📚 完整更新日志：https://www.zwplayer.com/zh/changelog
- 🛠️ 在线工具：https://www.zwplayer.com/zh/tools/
