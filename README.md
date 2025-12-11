# MyEmbyApp

由于没找到免费好用且支持弹幕的 Android TV 的 Emby 客户端，于是借助 ai 写了个。

## 功能特色

- 🎬 **原生 TV 体验** - 专为遥控器操作优化，流畅的焦点导航
- 💬 **弹幕支持** - 可配置兼容弹弹play弹幕api，支持自动匹配和手动搜索，最多配置5个弹幕API
- 🎮 **播放器功能** - 倍速播放、多音轨/字幕切换、外挂字幕延迟调整
- 📱 **扫码配置** - 手机扫码快速配置服务器和弹幕API
- 🔄 **播放进度同步** - 自动同步播放进度到 Emby 服务器
- 📺 **多服务器管理** - 支持添加多个 Emby 服务器

## 技术栈

- **UI 框架**: Jetpack Compose + TV Compose
- **播放器**: AndroidX Media3 + FFmpeg 扩展
- **弹幕引擎**: 快手 AkDanmaku
- **网络**: Retrofit + OkHttp
- **架构**: MVVM + Kotlin Coroutines + Flow

## 下载安装

前往 [Releases](../../releases) 页面下载最新版本 APK。

| 架构 | 说明 |
|------|------|
| `arm64-v8a` | 64位 ARM 设备（推荐，大多数新设备） |
| `armeabi-v7a` | 32位 ARM 设备（老设备） |

## 使用说明

1. 安装 APK 到 Android TV 设备
2. 打开应用，扫码或手动添加 Emby 服务器
3. 添加 emby 服务后即可浏览和播放媒体
4. 在设置中配置弹幕 API（可选）
5. 在设置中配置 http/socks5 代理（可选）


## 许可证

本项目仅供学习交流使用。

## 致谢

- [Emby](https://emby.media/) - 媒体服务器
- [AkDanmaku](https://github.com/aspect-ux/AkDanmaku) - 弹幕渲染引擎
- [misaka_danmu_server](https://github.com/l429609201/misaka_danmu_server) 、 [danmu_api](https://github.com/huangxd-/danmu_api) - 弹幕api服务
- [Jellyfin Media3](https://github.com/nicknsy/jellyfin-androidtv) - FFmpeg 解码器扩展
- [LINUX.DO论坛](https://linux.do/) - 提供了很多免费好用的公益ai
