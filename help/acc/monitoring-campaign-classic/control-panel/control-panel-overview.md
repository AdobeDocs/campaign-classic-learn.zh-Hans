---
title: 控制面板
seo-title: 控制面板
description: 该控制面板允许您按实例和允许列表IP地址监视和管理SFTP存储。
seo-description: 该控制面板允许您按实例和允许列表IP地址监视和管理SFTP存储。
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 5%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>术语“[!UICONTROL whitelist]”和“[!UICONTROL blacklist]”已在Adobe Campaign文档中[!UICONTROL allow list]替换为“[!UICONTROL block list]”和“”。
>产品UI、选项名称、内部代码以及教程视频中可能仍然存在这些术语的某些实例。 在即将发布的控制面板版中将替换它们。

Adobe Campaign管 [!UICONTROL Control Panel] 理员可以监视关键资产并执行管理任务，如按实例或IP地址管理SFTP [!UICONTROL allow list] 存储。

## 访问 [!UICONTROL Control Panel]

要访问控制面板，请转至Experience Cloud主页： [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   或
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **活动** > **[!UICONTROL Control Panel]卡&#x200B;**

   或

* 直接从URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## 先决条件

在开始之前，请完成以下先决条件：

### 确认 [!DNL IMS Org ID]

你需要了解你的 [!DNL IMS org ID]。 以下视频介绍了查找实例的位置 [!DNL IMS org ID]。

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*检[!DNL IMS Org ID]查（00:26分钟）*

### 管理员权限

需要管理员权限才能访问 [!UICONTROL Control Panel]。
以下视频介绍如何向活动实例添加管理员

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*如何向产品用户档案“”中添加[!UICONTROL Administrators]管理员以便能够[!UICONTROL Control Panel]使用（01:03分钟）*

## [!UICONTROL Control Panel] 教程

* **管理SFTP服务器**

   *了解如何监控服务器容量、[!UICONTROL allow list]IP地址和添加SSH密钥*

   * [监视服务器容量、允许列出IP地址和添加SSH密钥](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [生成SSH密钥](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [连接到SFTP服务器](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[委派子域](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *了解如何将子域完全委派到[!UICONTROL Adobe Campaign]*

* **[添加SSL证书](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *了解如何添加SSL证书以使用控制面板保护子域。*

* **[管理SSL证书](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *了解如何视图子域的SSL证书状态以及请求续订。*

* **[添加URL权限](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *如何将一些外部URL添加到授权URL的列表，以便您的实例可以连接到它们。*

* **[将 IP 添加到允许列表以进行实例访问](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *了解如何按IP地址范围设置与实例[!UICONTROL allow listing]的新连接。*

* **[Google TXT 记录管理](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *了解如何将站[!DNL Google TXT]点验证记录添加到用于通过向地址发送电子邮件[!DNL GMAIL]的所有子域[!UICONTROL Campaign Control Panel]。*

* **GPG密钥管理**

   *了解如何在指定的活动实例上生成和安装公钥／私钥对以加密出站数据，以及在活动实例上导入和安装公钥以解密入站数据：*

   * [生成和安装用于数据加密的GPG密钥](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [使用GPG密钥加密数据](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [解密数据](./gpg-key-management/decrypting-data.md)

* **[控制面板故障排除](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *了解如何对[!UICONTROL Control Panel]*

## 其他资源

* [控制面板帮助中心](https://docs.adobe.com/content/help/zh-Hans/control-panel/using/control-panel-home.html)