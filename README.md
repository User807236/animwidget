# 帧工坊 / FrameSmith

Turn **video / GIF / images** into live animated widgets on your Android home screen.
Zero third-party dependencies. No network access. No data collection.

把**视频 / 动图 / 图片**做成安卓桌面的动态组件。零第三方依赖，不联网，不收集任何数据。

## Download / 下载

[Latest release / 最新版本](../../releases/latest)

| Version | Size | SHA-256 |
|---|---|---|
| v1.10.358 | 6,614,600 bytes | `6a24c9a00152fb66174deddf229519e32091a6b7cb7f7e96b329173aadfc3ed7` |

Requires Android 8.0+ (API 26). / 系统要求 Android 8.0 及以上。

## Install / 安装

1. Download the `.apk` / 下载 APK
2. Enable "install from unknown sources" for your browser or file manager
   / 允许当前浏览器或文件管理器安装应用
3. **vivo / iQOO**: a warning about missing ICP filing (备案) is expected —
   tap **"Authorize this installation"**.
   If "Pure Mode" (纯净模式) blocks it, disable it in `Settings → Security → Pure Mode`.
   / vivo / iQOO 会提示「未备案」或「纯净模式拦截」，点「授权本次安装」；
   若被纯净模式拦截，去 `设置 → 安全 → 纯净模式` 关闭。

## Features / 功能

- Video ≤1080p / ≤50fps / ≤40s; GIF and still images supported
  / 视频 ≤1080p、≤50fps、≤40s；支持动图与静态图
- 48 shapes, shadow curves, borders, rotation, offset
  / 48 种形状、阴影曲线、边框、旋转、偏移
- "1:1" mode: preview = home screen = original resolution / frame rate / duration
  / 「1:1」档：预览 = 桌面 = 原清晰度 / 原帧率 / 原时长
- Widgets re-fit automatically after you resize them, without cropping
  / 桌面组件拖动改尺寸后自动适配，不裁切画面

## Permissions / 权限

| Permission | Why / 用途 | Optional? |
|---|---|---|
| `FOREGROUND_SERVICE` | per-frame widget delivery service / 组件逐帧投递服务 | No / 否 |
| `POST_NOTIFICATIONS` | playback status notification / 播放状态通知 | Yes / 可拒绝 |
| `SYSTEM_ALERT_WINDOW` | only for the "adjust position" overlay / 仅「调整位置」功能 | Yes / 可拒绝 |
| `PACKAGE_USAGE_STATS` | detect whether the launcher is in foreground, to pause when hidden / 判断桌面是否前台，不在则停播省电 | Yes / 可拒绝 |
| `READ_MEDIA_IMAGES` | preview gallery when picking image assets / 选图片素材时预览相册 | Yes / 可拒绝 |

**No network access, no analytics, no ads, no data collection.**
/ **本应用不联网、无统计 SDK、无广告、不收集任何数据。**

## Feedback / 反馈

Open an [issue](../../issues) with your device model, OS version, launcher name,
and the diagnostic log exported from `Settings → Diagnostic log → Export`.
/ 到 Issues 提，请附手机型号、系统版本、桌面名称，以及应用内
`设置 → 诊断日志 → 导出` 生成的文件。
