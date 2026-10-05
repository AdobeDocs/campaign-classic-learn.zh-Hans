---
title: 故障排除控制面板
description: 控制面板允许您按实例监视和管理SFTP存储并管理IP地址。
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: fd6e6e36-54e4-4f1a-96fc-1a750e400d50
    internal-label: Campaign Classic v7
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
source-git-commit: d4d4654e5b2dee85947373b8dcf139754844b316
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 67%
---

# 故障排除 [!UICONTROL Control Panel]

## 登录和主页

### 症状：无法登录 Experience Cloud

**要做什么：**
用户须找到其 IMS Org ID (xxx)。 管理员须将用户添加到要管理的每个实例的产品配置文件“Campaign-xxx-Admins”中。 如果用户是所有实例的管理员，他们仍须将自己添加为用户。

### 症状：Experience Cloud 主页中访问 [!UICONTROL Control Panel] 的链接不显示给用户

**原因：**
在将用户添加为产品配置文件_Campaign-xxx-Administrators/Admin_&#x200B;的用户之前，用户不会看到这些链接。

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品配置文件 _Campaign-xxx-Admins_ 中。 如果用户是所有实例的管理员，他们必须将自己添加为“用户”。

### 症状：实例未列在 [!UICONTROL Control Panel] 中

**原因：**
对于缺少的实例，最可能的原因是将用户添加为“用户”产品配置文件_Campaign-xxx-Administrators/Admin_

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品配置文件 _Campaign-xxx-Admins_ 中。 如果用户是所有实例的管理员，他们须将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/34927?captions=chi_hans&quality=12&learn=on){transcript=true}

*检查IMS组织ID（00:26分钟）*

>[!VIDEO](https://video.tv.adobe.com/v/34761?captions=chi_hans&quality=12&learn=on){transcript=true}

*如何向产品配置文件管理员添加管理员，以便能够使用[!UICONTROL Control panel] （01:03分钟）*

### 帮助文档

* [了解控制面板](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)
* [管理[!UICONTROL Control Panel]的权限](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)

## 建立与 SFTP 服务器（客户端或 API）的连接

连接到 SFTP 服务器需要：

* [!UICONTROL Allow listing] 您连接到 SFTP 服务器的 IP 地址
* 须在 Adobe Campaign 中注册的私钥/公钥对
* 如果直接连接到SFTP服务器，则需要SFTP客户端软件

### 帮助文档 {#helpful-docs}

* [登录 SFTP 服务器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)

