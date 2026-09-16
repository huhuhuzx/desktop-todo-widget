# 桌面待办清单

一款适用于 Windows 11 的桌面待办与日程小工具。窗口支持拖动、调整大小、浅色／深色模式与透明度设置；可查看任务详情、切换视图和管理日程。

## 编译

在 Windows 11 上使用 Windows PowerShell 运行：

```powershell
powershell -ExecutionPolicy Bypass -File .\Build-Exe.ps1
```

编译脚本使用系统的 .NET Framework WPF 编译器，生成 `桌面日程.exe`。运行程序后，任务和本机设置分别保存在程序所在目录的 `tasks.json` 与 `widget-settings.json` 中。

## 隐私

仓库仅包含源码、界面定义、图标、清单及编译脚本。个人任务数据 `tasks.json`、本机设置 `widget-settings.json` 和编译产物均不纳入版本控制。发布或分享时请勿手动上传这些本地文件。

