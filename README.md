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

GitHub Desktop 版本：| 3.2.1 - 3.5.5 | 

GitHub Desktop 汉化补丁包 版本：| 3.2.1 - 3.5.5 | 

---

# 注意：

请一定要保持Github Desktop版本与本汉化补丁包版本对应，否则汉化后Github Desktop可能会报错或打不开。

---

# GitHub Desktop for 2026年02月20日 3.5.5 发布说明

**新的**
- 支持在用户 shell 环境中运行钩子并允许绕过提交钩子 - [#21319](https://github.com/desktop/desktop/pull/21319)
- 允许使用备用编辑器一次性打开代码仓库 - [#21436](https://github.com/desktop/desktop/pull/21436)。谢谢。[@jackfreem](https://github.com/jackfreem)！

**额外**
- 添加 Warp 终端对 Windows 的支持 - [#21471](https://github.com/desktop/desktop/pull/21471)。谢谢。[@Cocodrulo](https://github.com/Cocodrulo)！
- 在分支列表上下文菜单中添加“在 GitHub 上查看分支”选项 - [#21071](https://github.com/desktop/desktop/issues/21071)。谢谢。[@DylanDevelops](https://github.com/DylanDevelops)！

**固定的**
- 修复在包含子模块的分支之间切换时仓库状态异常的问题 - [#21188](https://github.com/desktop/desktop/pull/21188)
- 账户偏好设置中的“企业”拼写已正确 - [#21454](https://github.com/desktop/desktop/pull/21454)
- Copilot 提交的内容现在使用 Copilot 头像 - [#21475](https://github.com/desktop/desktop/pull/21475)
- 防止点击通知时崩溃 - [#21311 ](https://github.com/desktop/desktop/issues/21311)[#20760](https://github.com/desktop/desktop/issues/20760)
- 现在按 Enter 键可以根据分支筛选字段创建新分支 - [#7734](https://github.com/desktop/desktop/issues/7734)。谢谢。[@jackfreem](https://github.com/jackfreem)！
- 修复在非 Git 文件夹中创建仓库时无法移动目录的问题 - [#20991](https://github.com/desktop/desktop/issues/20991)。谢谢。[@DylanDevelops](https://github.com/DylanDevelops)！
- 支持在未发布提交超过 100 个时显示未发布指示器 - [#20882](https://github.com/desktop/desktop/issues/20882)。谢谢。[@ashdawngary](https://github.com/ashdawngary)！
- 切换账户时，存储库写入权限警告立即更新 - [#21329](https://github.com/desktop/desktop/issues/21329)
- 改进分支重命名功能，使其能够处理仅区分大小写的更改 - [#21320](https://github.com/desktop/desktop/issues/21320)
- 提交失败后刷新代码库 - [#21229](https://github.com/desktop/desktop/issues/21229)
- 检查运行列表滚动条是否超出可用空间 - [#20831](https://github.com/desktop/desktop/issues/20831)。谢谢。[@iamarjunsuresh](https://github.com/iamarjunsuresh)！
- 仅在创建仓库时清理禁用的文件系统字符 - [#20973](https://github.com/desktop/desktop/issues/20973)
- 请从“生成提交详情”aria-label中移除多余的撇号 - [#21369](https://github.com/desktop/desktop/pull/21369)。谢谢。[@say25](https://github.com/say25)！

**改进**
- 将 Electron 更新至 40.1.0 版本 - [#21537](https://github.com/desktop/desktop/pull/21537)
- 更新了“推送需要拉取”的警告信息，使其更加清晰 - [#21423](https://github.com/desktop/desktop/pull/21423)。谢谢。[@movahhedi](https://github.com/movahhedi)！
- 波兰语更改选项卡筛选选项按钮和弹出窗口 - [#21412](https://github.com/desktop/desktop/pull/21412)。谢谢。[@jpedroso](https://github.com/jpedroso)！
- 对话框中的“储藏处”菜单项已禁用 - [#21435](https://github.com/desktop/desktop/pull/21435)。谢谢。[@jackfreem](https://github.com/jackfreem)！

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

本地GitHub Desktop资源目录一般为：C:\Users\【用户名】\AppData\Local\GitHub Desktop\【最新版本文件夹 例：app-3.5.5】\resources\app
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
