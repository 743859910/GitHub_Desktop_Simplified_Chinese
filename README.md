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

GitHub Desktop 客户端官网下载：| [Linux](https://github.com/shiftkey/desktop/releases/latest) | [MacOS](https://central.github.com/deployments/desktop/desktop/latest/darwin) | [Windows](https://central.github.com/deployments/desktop/desktop/latest/win32) | 

GitHub Desktop 客户端Releases下载：| [Linux](https://github.com/shiftkey/desktop/releases/latest) | [MacOS](https://github.com/desktop/desktop/releases/latest/download/GitHub.Desktop-x64.zip) | [Windows](https://github.com/desktop/desktop/releases/latest/download/GitHubDesktopSetup-x64.exe) | 

GitHub Desktop 版本：| 3.2.1 - 3.5.4 | 

GitHub Desktop 汉化补丁包 版本：| 3.2.1 - 3.5.4 | 

---

# 注意：
请一定要保持Github Desktop版本与本汉化补丁包版本对应，否则汉化后Github Desktop可能会报错或打不开。

---

# GitHub Desktop for 2025年11月07日 3.5.4 发布说明

**固定的**
- 将 Git LFS 更新至 3.7.1 以修复[CVE-2025-26625 漏洞](https://github.com/advisories/GHSA-6pvw-g552-53c5)
- 重新运行检查对话框中的运行状态图标应包含屏幕阅读器可访问的状态提示信息 - [#21191](https://github.com/desktop/desktop/pull/21191)
- 当启用“隐藏空格更改”时，右键单击差异行会弹出空格提示 - [#20848](https://github.com/desktop/desktop/issues/20848)。谢谢。[@zekariasasaminew](https://github.com/zekariasasaminew)！
- 登录对话框中的取消按钮在登录尝试后启用 - [#21144](https://github.com/desktop/desktop/issues/21144)。谢谢。[@zekariasasaminew](https://github.com/zekariasasaminew)！
- 使用其他帐户登录后，“错误归属的提交”弹出窗口中的“更新电子邮件”按钮可以正常工作 - [#21176](https://github.com/desktop/desktop/pull/21176)
- 改进使用身份验证代理时的主机发现功能 - [#19039 ](https://github.com/desktop/desktop/issues/19039)[#19120](https://github.com/desktop/desktop/issues/19120)
- 修复添加代码块时差异搜索结果高亮显示不可见的问题 - [#21134](https://github.com/desktop/desktop/pull/21134)
- 将 Copilot 提交消息生成功能添加到右键菜单 - [#21000](https://github.com/desktop/desktop/issues/21000)。谢谢。[@zekariasasaminew](https://github.com/zekariasasaminew)！
- 覆盖复选框和单选按钮的系统强调色 - [#21088](https://github.com/desktop/desktop/pull/21088)

**改进**
- 拉取请求检查运行按钮上的图标对比度符合至少 3:1 的对比度要求 - [#21189](https://github.com/desktop/desktop/pull/21189)
- macOS Tahoe 系统标题栏高度增加 - [#21135](https://github.com/desktop/desktop/issues/21135)。谢谢。[@berkcebi](https://github.com/berkcebi)！
- 在 PR 预览对话框中显示行更改次数 - [#21126](https://github.com/desktop/desktop/pull/21126)。谢谢。[@iammola](https://github.com/iammola)！
- 允许用户跳过提交消息覆盖确认 - [#21025](https://github.com/desktop/desktop/pull/21025)。谢谢。[@ilyassesalama](https://github.com/ilyassesalama)！
- 允许在非 GitHub 仓库中使用 Copilot 生成提交 - [#20698](https://github.com/desktop/desktop/issues/20698)。谢谢。[@schroedermarius](https://github.com/schroedermarius)！

---

# Linux 简体中文汉化

将本仓库中Linux文件夹下的main.js和renderer.js拷贝粘贴替换本地GitHub Desktop的资源目录

本地GitHub Desktop资源目录一般为：/usr/lib/github-desktop/resources/app
     【请一定记得提前做好备份】
     
替换完成后 重新打开GitHub Desktop

完成后界面
---
![](img/image/images/Linux.webp)

---

# MacOS 简体中文汉化
将本仓库中Mac文件夹下的main.js和renderer.js拷贝粘贴替换本地GitHub Desktop的资源目录

本地GitHub Desktop资源目录一般为：/Applications/GitHub Desktop.app/Contents/Resources/app
     【请一定记得提前做好备份】
     
替换完成后 重新打开GitHub Desktop

完成后界面
---
![](img/image/images/MacOS.webp)

---

# Windows 简体中文汉化
将本仓库中Windows文件夹下的main.js和renderer.js拷贝粘贴替换本地GitHub Desktop的资源目录

本地GitHub Desktop资源目录一般为：C:\Users\【用户名】\AppData\Local\GitHub Desktop\【最新版本文件夹 例：app-3.5.4】\resources\app
     【请一定记得提前做好备份】
     
替换完成后 重新打开GitHub Desktop

完成后界面
---
![](img/image/images/Windows.webp)

---

### 如果您觉得本工具对您有帮助，不妨在右上角点亮一颗小星星，以示鼓励！

---

<p align="center">
  <img src="img/image/images/1.webp">
</p>

<p align="center">
  <img src="img/image/images/2.webp">
</p>

<p align="center">
  <img src="img/image/images/3.webp">
</p>

<p align="center">
  <img src="img/image/images/4.webp">
</p>

<p align="center">
  <img src="img/image/images/5.webp">
</p>

---

昵称：我只是你的过客

个性签名：每个人都是每个人的过客

国籍：中华人民共和国 / 现居：中国湖北省武汉市

---

[MIT License](https://github.com/743859910/GitHub_Desktop_Simplified_Chinese/blob/master/LICENSE)

Copyright © 2008 - 2025 743859910. All Rights Reserved. 我只是你的过客工作室. 版权所有

---
