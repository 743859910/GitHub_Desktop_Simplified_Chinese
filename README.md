# GitHub_Desktop_Simplified_Chinese

---

<p align="center"><a href=""><img src="https://desktop.github.com/images/desktop-icon.svg" alt="logo" width="300" /></a></p>
<p align="center"><b>GitHub Desktop</b></p>
<p align="center"><b>专注于重要的事情，而不是与Git斗争。无论您是Git新手还是经验丰富的用户，GitHub Desktop都可以简化您的开发工作流程。</b></p>
<p align="center">
<a href="https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/stars"><img src="https://img.shields.io/github/stars/743859910/GitHub_Desktop_Simplified_Chinese?color=yellow"></a>
<a href="https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/forks"><img src="https://img.shields.io/github/forks/743859910/GitHub_Desktop_Simplified_Chinese?color=Yellow"></a>
<a href="https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/issues"><img src="https://img.shields.io/github/issues/743859910/GitHub_Desktop_Simplified_Chinese?color=Yellow"></a>
<a href="https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/languages/code-size"><img src="https://img.shields.io/github/languages/code-size/743859910/GitHub_Desktop_Simplified_Chinese?color=Yellow"></a>
<a href="https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/license"><img src="https://img.shields.io/github/license/743859910/GitHub_Desktop_Simplified_Chinese?color=Yellow"></a>
<a href="https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/releases"><img src="https://img.shields.io/github/release/743859910/GitHub_Desktop_Simplified_Chinese?color=Yellow"></a>
<a href="https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/discussions"><img src="https://img.shields.io/github/discussions/743859910/GitHub_Desktop_Simplified_Chinese?color=Yellow"></a>
<a href="https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/watchers"><img src="https://img.shields.io/github/watchers/743859910/GitHub_Desktop_Simplified_Chinese?color=Yellow"></a>
<a href="https://github.com/743859910/followers"><img src="https://img.shields.io/github/followers/743859910?color=Yellow"></a><br>
</p>

---

GitHub Desktop 官网：https://desktop.github.com

GitHub Desktop 仓库：https://github.com/desktop/desktop

GitHub Desktop 发行版：https://github.com/desktop/desktop/releases/latest

GitHub Desktop 发行说明：https://desktop.github.com/release-notes

GitHub Desktop 客户端下载：| [Linux](https://github.com/shiftkey/desktop/releases/latest) | [MacOS](https://central.github.com/deployments/desktop/desktop/latest/darwin) | [Windows](https://central.github.com/deployments/desktop/desktop/latest/win32) | 

GitHub Desktop 客户端仓库下载：| [Linux](https://github.com/shiftkey/desktop/releases/latest) | [MacOS](https://github.com/desktop/desktop/releases/latest/download/GitHub.Desktop-x64.zip) | [Windows](https://github.com/desktop/desktop/releases/latest/download/GitHubDesktopSetup-x64.exe) | 

GitHub Desktop 版本：| 3.2.1 - 3.4.17 | 

GitHub Desktop 汉化补丁包 版本：| 3.2.1 - 3.4.17 | 

蓝奏云：https://www.lanzouy.com/b00roqguj

如链接打不开，可将lanzouy中的y用26个英文字母中的任意一个替换即可。

密码：1234

注意：
请一定要保持Github Desktop版本与本汉化补丁包版本对应，否则汉化后Github Desktop可能会报错或打不开。

---

# 这里温馨提醒一下：

从官网下载 GitHub Desktop 安装包时，推荐使用：迅雷、IDM、FDM、NDM、Motrix 等专业下载工具。有VPN的可以无视墙内下载慢问题！

---

# GitHub Desktop for 2025年2月27日 3.4.17 发布说明

**固定的**
 - 对话框在 macOS Sequoia 上为 VoiceOver 用户宣布其标题 - [#20009](https://github.com/desktop/desktop/pull/20009)
 - 提交按钮单词以空格分隔，方便屏幕阅读器用户使用 - [#20011](https://github.com/desktop/desktop/pull/20011)
 - 尝试启动权限不足的外部编辑器时防止崩溃 - [#19929](https://github.com/desktop/desktop/issues/19929)
 - 在 Windows 上运行桌面 CLI 不再等待桌面退出后再自行退出 - [#19916](https://github.com/desktop/desktop/issues/19916)

**改进**
 - 在关于对话框中宣布更新进度 - [#20018](https://github.com/desktop/desktop/pull/20018)
 - 带有下拉插入符号的按钮可以通过向下箭头打开，从而触发上下文菜单 - [#20007](https://github.com/desktop/desktop/pull/20007)
 - 不打开外部 URL 的链接现在具有按钮的作用，以改进屏幕阅读器语义 - [#20010](https://github.com/desktop/desktop/pull/20010)
 - 电子邮件归因警告仅考虑已验证的电子邮件 - [#19968](https://github.com/desktop/desktop/pull/19968)
 - 改进未知合著者的工具提示 - [#19992](https://github.com/desktop/desktop/pull/19992)
 - 缩短的 SHA 的长度始终为 7 个字符 - [#19902](https://github.com/desktop/desktop/issues/19902)。谢谢[@molnarriso](https://github.com/molnarriso)！
 - 将 Electron 升级到 v34.0.1 - [#19919](https://github.com/desktop/desktop/pull/19919)

**已移除**
 - 删除对 macOS 10.15 的支持 - [#19919](https://github.com/desktop/desktop/pull/19919)

---

# Linux 简体中文汉化

将本仓库中Linux文件夹下的main.js和renderer.js拷贝粘贴替换本地GitHub Desktop的资源目录

本地GitHub Desktop资源目录一般为：/usr/lib/github-desktop/resources/app
     【请一定记得提前做好备份】
     
替换完成后 重新打开GitHub Desktop

完成后界面
---
![](https://hub.tcpmini.news/https://raw.githubusercontent.com/743859910/GitHub_Desktop_Simplified_Chinese/master/img/Linux.webp)

---

# MacOS 简体中文汉化
将本仓库中Mac文件夹下的main.js和renderer.js拷贝粘贴替换本地GitHub Desktop的资源目录

本地GitHub Desktop资源目录一般为：/Applications/GitHub Desktop.app/Contents/Resources/app
     【请一定记得提前做好备份】
     
替换完成后 重新打开GitHub Desktop

完成后界面
---
![](https://hub.tcpmini.news/https://raw.githubusercontent.com/743859910/GitHub_Desktop_Simplified_Chinese/master/img/MacOS.webp)

---

# Windows 简体中文汉化
将本仓库中Windows文件夹下的main.js和renderer.js拷贝粘贴替换本地GitHub Desktop的资源目录

本地GitHub Desktop资源目录一般为：C:\Users\【用户名】\AppData\Local\GitHub Desktop\【最新版本文件夹 例：app-3.4.17】\resources\app
     【请一定记得提前做好备份】
     
替换完成后 重新打开GitHub Desktop

完成后界面
---
![](https://hub.tcpmini.news/https://raw.githubusercontent.com/743859910/GitHub_Desktop_Simplified_Chinese/master/img/Windows.webp)

---

# 如果您觉得本工具对您有帮助，不妨在右上角点亮一颗小星星，以示鼓励！

---

<p align="center">
  <img src="https://hub.tcpmini.news/https://raw.githubusercontent.com/743859910/GitHub_Desktop_Simplified_Chinese/master/img/1.webp">
</p>

<p align="center">
  <img src="https://hub.tcpmini.news/https://raw.githubusercontent.com/743859910/GitHub_Desktop_Simplified_Chinese/master/img/2.webp">
</p>

<p align="center">
  <img src="https://hub.tcpmini.news/https://raw.githubusercontent.com/743859910/GitHub_Desktop_Simplified_Chinese/master/img/3.webp">
</p>

<p align="center">
  <img src="https://hub.tcpmini.news/https://raw.githubusercontent.com/743859910/GitHub_Desktop_Simplified_Chinese/master/img/4.webp">
</p>

<p align="center">
  <img src="https://hub.tcpmini.news/https://raw.githubusercontent.com/743859910/GitHub_Desktop_Simplified_Chinese/master/img/5.webp">
</p>

---

![Visitor Count](https://profile-counter.glitch.me/{GitHub_Desktop_Simplified_Chinese}/count.svg)

---

昵称：我只是你的过客

个性签名：每个人都是每个人的过客

国籍：中华人民共和国 / 现居：中国湖北省武汉市

---

[MIT License](https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/blob/master/LICENSE)

Copyright © 2008-2025 Powered by 743859910. Inc. All Rights Reserved. 我只是你的过客工作室. 版权所有

---
