# PowerGuard 🔋

> 让你的手机更省电、更凉快、更持久

[![Download](https://img.shields.io/badge/Download-v1.0.0-blue.svg)](https://github.com/431144610-afk/powerguard/releases/download/v1.0.0/PowerGuard-v1.0.0.apk)
[![Android](https://img.shields.io/badge/Android-10%2B-green.svg)](https://github.com/431144610-afk/powerguard)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 功能特性

- **📊 实时功耗监控** — 功耗评分 + APP耗电排行 + CPU/内存/温度/电量全掌握
- **⚡ 一键省电** — 批量优化后台APP电池策略，智能排除正在使用的APP
- **🛡️ 后台行为管控** — 电池策略/网络权限/自启动，逐个APP精准控制
- **🌡️ 智能温控预警** — 实时温度监控，超阈值自动通知，保护电池寿命
- **🔒 无需ROOT** — 通过Shizuku调用系统API，无线调试配对即可激活

## 下载安装

1. 下载 [PowerGuard-v1.0.0.apk](https://github.com/431144610-afk/powerguard/releases/download/v1.0.0/PowerGuard-v1.0.0.apk)
2. 在手机上安装（需允许未知来源）
3. 打开APP → 设置 → 激活Shizuku → 开启无线调试 → 配对完成
4. 回到首页，点击"一键省电"，享受更长续航 🎉

## 免费版 vs Pro版

| 功能 | 免费版 | Pro版 |
|------|--------|-------|
| 功耗监控 + 排行 | ✓ | ✓ |
| 温度预警 | ✓ | ✓ |
| 充电保护提醒 | ✓ | ✓ |
| 一键省电 | ✗ | ✓ |
| 电池策略管控 | ✗ | ✓ |
| 网络权限管理 | ✗ | ✓ |
| 自启动管理 | ✗ | ✓ |

## 技术栈

- Kotlin + Jetpack Compose
- Hilt (依赖注入)
- Room (本地数据库)
- Shizuku (系统级API)
- MVVM 架构

## 常见问题

**需要ROOT吗？** 不需要。通过Shizuku调用系统API，只需无线调试配对。

**一键省电会杀后台吗？** 不会。通过修改电池策略优化，不强制停止APP。

**每次重启都要重新激活Shizuku？** 是的，约10秒重新配对一次，这是Android安全机制。

## 反馈

- 酷安评论区留言
- [GitHub Issues](https://github.com/431144610-afk/powerguard/issues)

---

PowerGuard © 2026
