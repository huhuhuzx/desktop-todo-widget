# 桌面待办清单

一款轻量的 Windows 11 桌面待办与日程小工具。下载即用，无需安装。

## 下载

前往 [Releases](https://github.com/huhuhuzx/desktop-todo-widget/releases) 下载最新版本，双击即可运行。

## 功能

- 日程、今天、月历、已完成四种视图
- 自定义标题、日期、时间、分类、重复、提醒、地点与备注
- 浅色 / 深色模式，主题色可自由选择
- 玻璃半透明底色，浓度可调
- 任务提醒与漏提醒补报
- 窗口可拖动、缩放，并支持始终置顶
- 数据保存在本地，不上传任何服务器

## 快速开始

1. 下载并运行程序
2. 点击右上角「新建」添加日程
3. 在设置中调整主题色、外观与透明度
4. 勾选任务即可完成；重复日程会自动生成下一次

任务数据保存在程序目录下的 `tasks.json`，本机设置保存在 `widget-settings.json`。

## 从源码编译

在 Windows PowerShell 中运行：

```powershell
powershell -ExecutionPolicy Bypass -File .\Build-Exe.ps1
```

编译需要系统自带的 .NET Framework WPF 工具链，会生成 `桌面日程.exe`。

## 隐私

本项目完全在本地运行，不会联网上传数据。仓库仅包含源码与编译脚本，个人任务数据与本机设置不会纳入版本控制。
