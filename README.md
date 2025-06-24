
## 📦 Shadowrocket 配置文件（精细分流 / 游戏优化）

本项目收集并整合了多个高质量规则集，用于 Shadowrocket 分流配置，支持常用服务、游戏平台、AI 应用、社交媒体等的精准识别与路由。

---

## ⚠️ 安全公告：v1.0.7 之前版本存在 DNS 泄露问题

> **重要提醒：v1.0.6 及更早版本存在严重 DNS 泄露风险，可能导致访问记录被明文暴露。**

虽然早期版本在多个 DNS 检测网站中未显示异常，但我们后来通过抓包发现，部分黑名单网站的 DNS 请求会绕过代理通道，直接以明文形式发送到 `1.1.1.1` / `8.8.8.8` 等公共 DNS 服务器。

这一行为**无法通过常规 DNS 泄露检测网站发现**，但在实际抓包中清晰可见，属于典型的隐性安全问题。

### ✅ 已在 v1.0.7 起修复：

- 多平台实际抓包验证通过。

📢 建议所有用户**立即升级至 v1.0.7 或更高版本**，以确保隐私和安全。

---

## 📚 规则来源

- 🔗 ACL4SSR  
- 🔗 blackmatrix7  
- 🔗 lowertop  

---

## 🔍 DNS 安全检测建议

虽然以下服务可用于辅助测试 DNS 设置是否异常：

👉 https://ipleak.net/  
👉 https://dnsleaktest.com/  

⚠️ 但请注意：  
**这些网站的检测能力有限，无法识别系统级或隐性 DNS 泄露。**

📦 本项目今后的 DNS 安全性均以**实际抓包分析为准**，网站检测仅供参考。

---

## 📬 联系与订阅

- Telegram 频道：https://t.me/Github_ICNNC  
- 项目主页：https://github.com/ICNNC/shadow-config  

---

## 📄 License

This configuration is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You may use, modify, and share this file for any purpose, as long as proper credit is given to the author and this repository.

