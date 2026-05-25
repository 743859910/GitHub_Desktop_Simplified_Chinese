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

GitHub Desktop 版本：| 3.5.0 - 3.5.9 | 

GitHub Desktop 汉化补丁包 版本：| 3.5.0 - 3.5.9 | 

---

# 注意：

请一定要保持Github Desktop版本与本汉化补丁包版本对应，否则汉化后Github Desktop可能会报错或打不开。

---

# GitHub Desktop for 2026年05月21日 3.5.9 发布说明

**固定的**
- 修剪期间跳过已检出的关联工作树中的分支 - [#8043](https://github.com/desktop/desktop/issues/8043)。谢谢。[@KRRT7](https://github.com/KRRT7)！
- 修复提交信息区域中按钮的样式 - [#22075](https://github.com/desktop/desktop/pull/22075)
- 修复已更改文件长列表的渲染问题 - [#21630](https://github.com/desktop/desktop/issues/21630)
- 为 .astro 文件添加语法高亮显示 - [#21987](https://github.com/desktop/desktop/issues/21987)。谢谢。[@JunDev76](https://github.com/JunDev76)！
- 修复 Windows 滚动条与 react-virtualized Grid 的同步问题 - [#21940](https://github.com/desktop/desktop/issues/21940)
- 改进发行说明对话框的间距 - [#21962](https://github.com/desktop/desktop/issues/21962)。谢谢。[@DylanDevelops](https://github.com/DylanDevelops)！
- 修复了在执行多提交操作期间，当冲突对话框打开时可能发生的崩溃（超出最大更新深度）问题 - [#21879](https://github.com/desktop/desktop/pull/21879)
- 从企业登录界面移除已停用的 GitHub AE 引用 - [#21926](https://github.com/desktop/desktop/pull/21926)。谢谢。[@toddmanion](https://github.com/toddmanion)！

**改进**
- 启用最大 1MB 的差异展开和语法高亮显示 - [#21876](https://github.com/desktop/desktop/pull/21876)
- 更新 re2js 正则表达式引擎，使用优化的 DFA 路径以提升性能 - [#21924](https://github.com/desktop/desktop/pull/21924)。谢谢。[@le0pard](https://github.com/le0pard)！

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

本地GitHub Desktop资源目录一般为：C:\Users\【用户名】\AppData\Local\GitHub Desktop\【最新版本文件夹 例：app-3.5.9】\resources\app
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

Copyright © 2008 - 2026 743859910. All Rights Reserved. 我只是你的过客工作室. 版权所有

---
