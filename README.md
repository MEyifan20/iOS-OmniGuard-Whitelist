# 🛡️ iOS-OmniGuard-Whitelist（Guardian-Standard）

[广告拦截加 2.0]！
标题：iOS-OmniGuard-白名单（标准统一版）！
描述：针对 iOS 环境深度优化的全能白名单防误杀护盾。精准放行苹果核心服务、国内主流支付/社交渠道及关键 CDN，与黑名单完美配合，系统 100% 稳定运行。
版本：2026.02.28.05！
代号：守护者标准！
更新：2026-02-28 05:36 (GMT+8)！
! -----------------------------------------------------------------------------------------------------------

## 📖 项目简介
**iOS-OmniGuard-Whitelist** 是专门为 iOS 高级用户打造的“系统级保活”白名单方案。当你在使用高强度的 DNS 黑名单或代理工具去广告时，经常会遇到 App 无法登录、图片加载失败或系统自动延迟等“误杀”问题。

本项目提取了高频误杀节点，通过高优先级的 `@@` 放行规则，为你张开一张隐形防护盾。

**💡 作者强烈建议：** 请务必将本项目与本作者的兄弟项目 **[iOS-OmniGuard-Blacklist](https://github.com/MEyifan20/iOS-OmniGuard-Blacklist)** 组合使用，构建完美的攻防闭环。

---

## 🚀 订阅地址

### 1️⃣ DNS 过滤器 (标准白名单)
* **jsDelivr CDN (推荐国内直连)**
`https://cdn.jsdelivr.net/gh/MEyifan20/iOS-OmniGuard-Whitelist@main/iOS-OmniGuard-Whitelist.txt`

* **GitHub 原生地址**
`https://raw.githubusercontent.com/MEyifan20/iOS-OmniGuard-Whitelist/main/iOS-OmniGuard-Whitelist.txt`

---

## 💎 核心优势
* 🍎 **苹果生态保活**: 强制放行 iCloud 极速同步、App Store 下载、iMessage 及主动服务。
* 💳 **支付仓储绿灯**: 确保微信支付、支付宝、银联等金融级 API 节点绝对畅通。
* 🔗 **CDN 修复关键**: 修复因误杀导致的淘宝/京东图片不显示、B 站弹幕断流等次生灾害。
* ⚖️ **底层逻辑闭环**: 采用白名单最高优先级逻辑，免疫一切第三方黑名单库的暴力误杀。

---

## 🛠️ 技术指标 (Technical Metrics)
为了实现最大的系统稳定性，本项目遵循以下放行逻辑：
$$Allow \cap \{Apple\_Core, Finance, Essential\_CDN\} \setminus \{Ad\_Tracker\} = 100\%$$

| 模块名称 | 保护目标 | 策略强度 |
| :--- | :--- | :--- |
| **苹果核心** | iCloud、App Store、系统更新 | 绝对放行 (Allow) |
| **金融盾牌** | 微信支付、支付宝、银行网关 | 绝对放行 (Allow) |
| **CN Essential** | 腾讯/阿里/字节云端登录组件 | 修复补吸 (Repair) |
| **全球 CDN** | Akamai、Cloudflare 等云节点 | 节点保障 (Secure) |

---

## ⚙️ 配置建议
1. **安装逻辑**：进入应用 -> DNS 防护 -> DNS 过滤器 -> 添加过滤器 -> 粘贴上述 TXT 链接。
2. **优先级设置**：请务必确保该白名单的排序和优先级高于所有黑名单，让防护盾在第一层生效。
3. **配合使用**：强烈建议与兄弟版本 `iOS-OmniGuard-Blacklist` 组合使用。

---

## 🤖 自动化维护 (Auto-Update)
本项目支持通过 GitHub Actions 实现自动化维护。
- **当前版本**：2026.02.28.05- **最后同步**：2026-02-28 05:36 (GMT+8)- **核心逻辑**：自动合并高频误杀反馈并执行物理去重。

---

## 🤝 致谢与声明
* **致谢**: 感谢各大开源去广告社区提供的排错反馈。
* **声明**: 本项目仅供技术研究与交流使用，禁止用于任何非法用途。

---

## ❤️ 助力项目
- **点亮星星**：点击右上角 ⭐ 星星，这是对我持续维护最大的动力。
- **反馈问题**：请提交 [Issues](https://github.com/MEyifan20/iOS-OmniGuard-Whitelist/issues)。

---
**iOS-OmniGuard-Whitelist** · 愿您的网络环境干净自由。

**最后修改时间**：2026-02-28 05:36 (GMT+8)**维护者**：[MEyifan20](https://github.com/MEyifan20)  
**许可证**：MIT
