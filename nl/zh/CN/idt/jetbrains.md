---

copyright:

  years: 2018

lastupdated: "2018-04-17"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# 用于 Jetbrains IDE 的 IBM Developer Tools
{: #ibm-dev-tools-for-jetbrains}

用于 Jetbrains IDE（包括 IntelliJ、WebStorm 和 Android Studio 等）的 IBM Developer Tools 扩展提供了用于从 IDE 中直接访问 IDT CLI 命令的新菜单项。它支持快速访问适用于 Docker 和 CloudFoundry 工作流的 `bx dev` 命令子集，包括应用程序部署、在 {{site.data.keyword.Bluemix_notm}} 上启动/停止/重新启动应用程序、查看远程应用程序日志等等，这一切操作都无需离开编辑器的上下文。
{:shortdesc}

![在 WebStorm IDE 中运行的 IBM Developer Tools 的截屏。](jetbrains.png "在 WebStorm IDE 中运行的 IDT 菜单示例")

## 依赖项
{: #dependencies}

要使用针对基于 Jetbrains 的 IDE 的 IBM Developer Tools 扩展，您需要在系统上安装 [IBM Cloud Developer Tools CLI](index.html)。

## 安装
{: #installation}

安装用于 Jetbrains IDE 的 IBM Developers Tools 扩展的最简单方法是转至 [IDT Github 存储库的 Jetbrains](https://github.com/IBM-Cloud/ibm-cloud-developer-tools/tree/master/jetbrains) 页面，并遵循相关指示信息进行操作。

## 用法
{: #usage}

您可以从现有服务器端应用程序开始，针对 IBM Cloud 启用该应用程序，或使用 IDT CLI 通过 StarterKit (bx dev create) 创建新应用程序。在您有应用程序项目后，请在 JetBrains IDE 中将其打开。

如果您有通用服务器端应用程序，请选择“工具”> IBM Cloud Developer Tools >“针对 IBM Cloud 启用应用程序”。这将检查所有必需的文件并添加任何缺少的文件，以支持您在本地构建应用程序，以及使用 Cloud Foundry 应用程序将其部署到 IBM Cloud，或者将其部署到 Kubernetes 集群中。

使用 IDT 菜单中的基本构建/运行/部署操作，可开发云本机应用程序。如果需要执行不在菜单中的操作，请打开“终端”选项卡并手动输入所需命令。

