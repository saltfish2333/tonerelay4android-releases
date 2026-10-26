## ToneRelay for Android 1.0.0-rc12 · Public trial preview

Restores the playback buffer targets to Stable 250 ms, Low latency 150 ms (default), and Fast 100 ms. Existing profile descriptions, quick casting, phone mute/restore, 15-step speaker volume and automatic reconnect are retained. Each failed connection attempt still waits one second before the next attempt; time spent attempting a connection is additional.

Buffer targets are not total audible latency. Choose a more stable profile if playback breaks up.

## 中文说明

仅将三档缓冲恢复为稳定 250ms、低延迟 150ms（默认）、极速 100ms。保留现有档位描述、一键投送、手机静音与结束恢复、15 级音箱音量及自动重试。每次连接尝试结束后仍等待 1 秒重试，尝试本身耗时不计入该间隔。

这些数值是缓冲目标，实际出声延迟取决于手机、网络和音箱；出现断音时可切换更稳定的档位。

## Install / 安装更新

Requires Android 10 or later. Install **ToneRelay-1.0.0-rc12.apk** over the previous official version to retain settings and trial state; do not uninstall first. The website and GitHub provide the same signed universal APK for arm64-v8a, armeabi-v7a, x86 and x86_64.

下载下方 APK，直接覆盖旧版官方安装包。官网和 GitHub 提供同一份正式签名安装包。音频采集依赖来源应用允许 Android 播放采集，手机与兼容 AirPlay 音箱需在同一局域网。

The public trial lasts 168 continuous hours from the first successful transmission of valid audio. First registration requires internet; restarting the phone does not require online time calibration. Paid activation is not open yet. Do not buy a Windows license for Android.

当前继续开放连续 168 小时试用，正式购买尚未开放。首次成功投送有效音频起算，首次登记需联网，重启不要求联网校时。请勿购买 Windows 授权用于安卓版。

APK size, SHA-256 and signing fingerprint are in **release.json** and **SHA256SUMS.txt**. Application source code and signing keys remain private.

[Website](https://tonerelay.com/android/) · [中文官网](https://tonerelay.com/zh/android/) · support@tonerelay.com
