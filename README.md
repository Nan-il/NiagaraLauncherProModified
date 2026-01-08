<div align="center">
  <img style="width: 128px; height: 128px;" src="https://raw.githubusercontent.com/Nan-il/NiagaraLauncherLogo/main/Logo/LogoWithoutShadow.svg" alt="logo" />

  <h1 align="center">Niagara Launcher Pro Modified</h1>

  <p><em> 免费使用 Niagara Pro 的专属功能</em></p>

  <a href="https://github.com/Nan-il/NiagaraLauncherProModified/releases"><img src="https://img.shields.io/github/release/Nan-il/NiagaraLauncherProModified" alt="latest version" /></a>
</div>

---

## 新版本

上游 Niagara Launcher 已发布新版本1.15.7。本仓库将在1月9日发布新版本更新。

另：新年快乐！

---

## 项目说明

Niagara Launcher Pro Modified 是一个基于 Niagara Launcher 进行修改，仅供学习研究使用的分支项目，移除了对 Niagara Pro 的付费检测。

使用此项目的版本，你可以免费使用 Niagara Pro 的专属功能。

你可以下载本项目的 Release 文件，将它们与原项目的文件进行对比，以了解修改部分的逻辑。

有条件的用户请移步原项目以支持其开发，这是其 Repo：[Niagara Launcher/Niagara-Issues](https://github.com/NiagaraLauncher/Niagara-Issues)。

## 下载（Releases）

<a href="https://github.com/Nan-il/NiagaraLauncherProModified/releases"><img src="https://raw.githubusercontent.com/Nan-il/get-it-on-github/main/get-it-on-github.svg" alt="Download from GitHub releases" width="32%" /></a>

## 安装

### 从零安装
- 说明：手机上未安装原项目版本的 Niagara Launcher
- 方法：直接安装
- 由于使用了 Debug 签名，部分厂商的定制系统可能会阻止安装（例如小米的 MIUI 、HyperOS ），请自行关闭应用安装检查。</br>
无法关闭或关闭后仍然无法安装的，请检查SDK版本或尝试使用 adb 或 InstallerX（见后文）。

### 覆盖安装
- 说明：手机上已安装原项目版本的 Niagara Launcher
- 方法：先备份 Niagara Launcher 的数据（可能有部分数据无法被备份），卸载原版后再安装本项目版本，最后恢复数据。
- 由于使用了 Debug 签名，部分厂商的定制系统可能会阻止安装（例如小米的 MIUI 、HyperOS ），请自行关闭应用安装检查。</br>
无法关闭或关闭后仍然无法安装的，请检查SDK版本或尝试使用 InstallerX（见后文）。

### 升级安装
- 说明：手机上已安装本项目版本的 Niagara Launcher
- 方法一：尝试直接安装，签名相同理论上可以进行升级（需要测试！）
- 方法二：进行覆盖安装（见上文）
- 一般而言，升级不会遇到安全检查，只会检查两个版本的签名是否相同。

### 使用 adb 辅助安装
- adb（Android Debug Bridge，安卓调试桥）是一种具有较高权限的命令行工具，可利用 adb 的流式安装功能完成对 apk 文件的安装并绕过部分对安装包的检查。

### 使用 InstallerX 辅助安装
- InstallerX 是一个谷歌原生/厂商定制的安装包管理器的替代品，它使用更高的权限执行安装工作，并因此需要 Shizuku 或 Dhizuku 的授权。</br>
在 Shizuku 模式下，它的行为与使用 adb 直接进行安装没有区别，因为 Shizuku 本身即是 adb 的 Shell 权限的分享者。
- InstallerX 的 Repo：[InstallerX Revived (Community Edition)](https://github.com/wxxsfxyzm/InstallerX-Revived)

## 反馈

如有证实为本项目的问题（例如安装的问题等），请前往 [Issues](https://github.com/Nan-il/NiagaraLauncherProModified/issues) 进行反馈。

对于功能方面的需求和 Launcher 本身的问题，请前往[原项目 Repo ](https://github.com/NiagaraLauncher/Niagara-Issues)并根据 Repo 的说明提出建议和进行反馈。

## 许可证与免责声明

原项目 [NiagaraLauncher](https://github.com/NiagaraLauncher/Niagara-Issues) 不是开源软件，所有权利归开发者所有；

本项目 ‘NiagaraLauncherProModified’ 作为其分支亦没有许可证，且本项目作者对因使用项目而造成的影响概不负责。

## 开发者

原项目 [NiagaraLauncher](https://github.com/NiagaraLauncher/Niagara-Issues)；[Nan'il（林岸）](https://github.com/Nan-il)。
