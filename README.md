# GreenHub-OnlineActivators 🌱

[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

一站式网页激活码获取解决方案，突破传统Python爬取限制，轻松解除跨域访问屏障。

## 功能亮点 ✨
- 🌐 基于浏览器原生能力实现数据抓取
- 🛡️ 内置跨域解决方案指南
- 📦 开箱即用的浏览器配置方案
- 🚀 支持多平台浏览器环境
- 🔄 实时动态数据获取能力

## 快速开始 🚀

### 环境要求
- Chrome 80+ 或 Safari 13+
- 现代浏览器支持 ES6+

## 浏览器配置指南 🔧

### Chrome 配置方案
```batch
:: 保存为 start_chrome.bat 双击运行
@echo off
set CHROME_PATH="C:\Program Files\Google\Chrome\Application\chrome.exe"
set USER_DATA_DIR=C:\DWS

start %CHROME_PATH% --disable-web-security --user-data-dir=%USER_DATA_DIR%
```

### Safari 配置方案
1. 启用开发菜单
   - Safari > 偏好设置 > 高级 > 勾选"在菜单栏中显示开发菜单"
2. 解除安全限制
   - 开发菜单 > 勾选以下两项：
     - 🚫 Disable Cross-Origin Restrictions (解除跨域限制)
     - 📂 Disable Local File Restrictions (解除本地文件访问限制)

![Safari配置示意图](https://via.placeholder.com/600x400?text=Safari+Security+Settings+Demo)


## 注意事项 ⚠️
1. 解除浏览器安全限制仅建议在开发调试时使用
2. 生产环境请通过合法途径解决跨域问题
3. 定期清理浏览器临时数据目录（C:\DWS）

## 贡献指南 🤝
欢迎通过以下方式参与贡献：
1. 提交 Issues 报告问题或建议
2. 发起 Pull Request 提交改进代码
3. 完善项目文档
4. 分享使用案例

## 许可证 📜
本项目采用 [MIT License](LICENSE)

---

**Happy Coding!** 🎉 如有任何问题，欢迎在 Issues 区讨论交流。
