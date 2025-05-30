---
title: 如何在Adobe Campaign Classic中配置验证工作流
description: 了解如何配置不同的批准验证工作流。
feature: Workflows, Approvals
jira: KT-1566
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 96%

---


# 创建验证工作流

Adobe Campaign 为营销人员提供了多个选项，用于审核和提供投放内容、活动目标、数据提取和预算批准。

本教程介绍了如何配置不同的批准验证工作流。

## 先决条件 {#prerequisite}

在启用批准步骤之前，营销团队必须定义审阅人：

* 批准活动中的 Adobe Campaign 审阅人角色可以是单个审阅人（操作员）或一组审阅人（操作员角色）。
* 要使活动开发人员能够选择审阅人作为活动或投放中的批准者，必须由管理员在 Adobe Campaign 中配置审阅人和审阅人组。

## 为营销活动配置审批  {#configuring-approvals-for-campaigns}

如果活动工作流中所有投放都设定同一组审阅人，那么您要在活动级别设置批准和审阅人来应用活动批准功能。执行工作流后，审批任务和审阅人会被向下推送到工作流的每个投放活动中。

>[!VIDEO](https://video.tv.adobe.com/v/27476?quality=12&learn=on&captions=chi_hans){transcript=true}

## 为投放配置审批  {#configuring-approvals-for-deliveries}

您还可以在投放级别设置批准。如果投放批准步骤及审阅人与活动批准步骤及审阅人不同，那么投放设置会覆盖活动设置。

>[!VIDEO](https://video.tv.adobe.com/v/27481?quality=12&learn=on&captions=chi_hans){transcript=true}

## 配置审批活动  {#configuring-an-approval-activity}

与投放或营销活动批准不同，批准活动允许您在工作流中创建批准流程。如此便可以在启动投放之前批准定位选择逻辑。如有必要，您还可以在工作流的多个级别进行批准。

>[!VIDEO](https://video.tv.adobe.com/v/27486?quality=12&learn=on&captions=chi_hans){transcript=true}

有关更多信息，请参阅[批准文档](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=zh-Hans)
