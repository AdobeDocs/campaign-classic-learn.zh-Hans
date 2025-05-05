---
title: 配置循环和连续的电子邮件活动
description: 了解如何设置循环和连续投放，并了解两种方法之间的差异。
feature: Workflows, Campaigns
jira: KT-1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '240'
ht-degree: 50%

---

# 配置循环和连续的电子邮件活动

本教程介绍了如何设置循环和连续投放，以及这两种方法之间的差异。

## 循环和连续投放跟踪 {#recurring-and-continuous-delivery-tracking}

循环投放和连续投放在管理联系人数据的方式上有所不同：

* **连续投放**&#x200B;允许您向现有投放添加新收件人，并避免每次添加新收件人时都必须创建新投放。 您可以直接在活动工作流中更新创意，活动工作流将更新投放模板资源文件夹中的模板。

  连续投放将创建单个投放和投放日志(broadLog)以及跟踪日志，日志引用每次执行投放时添加一个投放。

  ![连续投放](/help/assets/delivery_continuous.jpg)

* 每次执行&#x200B;**循环投放**&#x200B;时，都会创建一个新的投放实例。 例如，如果工作流计划每周运行一次，那么一年后将产生 52 次投放。这也意味着广义日志和跟踪日志将按每个投放实例进行分隔。

  ![循环投放](/help/assets/delivery_recurring.jpg)

## 如何设置循环投放 {#how-to-set-up-a-recurring-delivery}

此视频介绍如何配置循环投放和调度程序活动。

>[!VIDEO](https://video.tv.adobe.com/v/27510?quality=12&learn=on&captions=chi_hans){transcript=true}

## 如何设置连续投放 {#how-to-set-up-a-continuous-delivery}

本视频演示了如何使用增量查询配置连续投放。

>[!VIDEO](https://video.tv.adobe.com/v/27515?quality=12&learn=on&captions=chi_hans){transcript=true}
