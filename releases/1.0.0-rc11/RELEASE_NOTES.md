## ToneRelay for Android 1.0.0-rc11 · Public trial preview

- Start casting from a device entry, restore previous speakers, or use the notification and Quick Settings controls. Android audio sharing permission is still required.
- Updated playback profiles: Stable 180 ms, Low latency 120 ms (default), Fast 80 ms. These are buffer targets; total audible delay also depends on the phone, network and speaker. If audio breaks up, select a more stable profile.
- Unexpected connection failures retry one second after each completed attempt. Disconnecting or cancelling stops retries; pairing errors retain their prompts.
- Retains phone mute/restore, optional simultaneous phone playback, and 15-step speaker volume control.

Paid activation is not open yet. The trial runs for 168 continuous hours from the first successful transmission of valid audio. The first registration requires internet; restarting the phone does not require online time calibration. Casting stops when the trial expires. Do not buy a Windows license for Android.

## 中文说明

本版更新一键投送、恢复上次音箱、通知栏和快捷设置控制；仍需同意 Android 系统音频共享。三档调整为稳定 180ms、低延迟 120ms（默认）、极速 80ms。这些数值为缓冲目标，实际延迟取决于手机、网络及音箱；出现断音时请选择更稳定的档位。意外断连会在每次尝试结束后等待 1 秒重试，取消或断开可停止重试。保留手机自动静音与结束恢复、手机同时播放开关及 15 级音箱音量控制。

当前仍为公开试用预览，正式购买未开放。首次成功投送有效音频后开始连续 168 小时试用，首次登记需联网，重启不要求联网校时，到期停止投送。请勿购买 Windows 授权用于安卓版。

## Install / 安装更新

Download **ToneRelay-1.0.0-rc11.apk** from Assets below. Requires Android 10 or later. Website and GitHub downloads provide the same signed universal APK. Install over the previous official APK to retain data; do not uninstall first. Supports arm64-v8a, armeabi-v7a, x86 and x86_64.

下载下方 APK，直接覆盖旧版官方安装包以保留设置和试用状态。官网与 GitHub 提供同一个包。部分来源应用可能限制 Android 音频采集；手机与支持 AirPlay 的音箱须处于同一局域网。HomePod、Apple TV 及支持 AirPlay 的 Sonos 已有用户测试记录，兼容情况依机型及网络而异。

APK size, SHA-256 and signing fingerprint are provided in **release.json** and **SHA256SUMS.txt**. Application source code and signing keys remain private.

[Website](https://tonerelay.com/android/) · [中文官网](https://tonerelay.com/zh/android/) · support@tonerelay.com
