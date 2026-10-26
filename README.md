# Digicut Desktop

Windows 10 / 11 x64 桌面版安装与自动更新产物。

[下载最新安装器](https://github.com/digitor-it/digicut-releases/releases/latest/download/Digitor.Digicut-win-Setup.exe) · [所有版本与更新说明](https://github.com/digitor-it/digicut-releases/releases)

## 安装与使用

1. 下载并运行 `Digitor.Digicut-win-Setup.exe`。安装器检查 .NET Framework 4.7.2+ 和 WebView2 先决条件。
2. 打开 Digicut Desktop。通过 **File → Open Project** 打开 `.digicut` 项目，移动项目时保留旁边的 assets 文件夹。
3. 软件启动时检查更新；也可使用 **Help → Check for updates** 或 **Settings → Application updates**。
4. 先查看版本与更新说明，点击 **Update now** 才下载；下载完成后保存工作、安装并重新打开。

项目、素材与设置保存在安装目录之外，更新和卸载保留这些资料。旧的开发目录或普通 ZIP 版本需要先安装一次 Setup，才能使用自动更新。

目前安装器没有 Windows Authenticode 代码签名，Windows SmartScreen 或防病毒软件可能显示提示；更新清单另有 RSA-SHA256 签名和文件校验。不要关闭系统安全功能。

## Release 文件

每个版本同时提供安装器、完整 `.nupkg`、`releases.win.json` 与签名 `latest.json`。普通安装请使用 Setup.exe，其余文件供自动更新读取。此仓库只维护分发说明和安装/更新产物。
