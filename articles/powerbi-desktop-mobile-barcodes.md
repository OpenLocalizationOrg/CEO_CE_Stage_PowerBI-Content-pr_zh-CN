<properties 
   pageTitle="标记条形码域在 Power BI Desktop 中的 Power BI 移动应用程序"
   description="在 Power BI Desktop 模型中标签条形码域时，您可以在 iPhone 上筛选条码自动 Power BI 应用中的数据。"
   services="powerbi" 
   documentationCenter="" 
   authors="maggiesMSFT" 
   manager="mblythe" 
   editor=""
   tags=""
   qualityFocus="no"
   qualityDate=""/>
 
<tags
   ms.service="powerbi"
   ms.devlang="NA"
   ms.topic="article"
   ms.tgt_pltfrm="NA"
   ms.workload="powerbi"
   ms.date="06/09/2016"
   ms.author="maggies"/>

# 在 Power BI Desktop 中的 Power BI 移动应用程序的标记条形码

在 Power BI Desktop，您可以在一列[对数据进行分类](powerbi-desktop-data-categorization.md)以便 Power BI Desktop 知道如何处理报表中的可视化对象中的值。 您还可以为**条形码**分类列。 当您或您的同事[扫描条码上的一款产品与 Power BI 应用](powerbi-mobile-scan-barcode-for-report.md)在 iPhone 上，您将看到的任何报表，包括该条形码。 当您在移动应用中打开报表时，Power BI 自动筛选对与该条形码相关的数据的报表。

1. 在 Power BI Desktop，切换到数据视图。

2. 选择具有条形码的数据的列。 请参阅[支持的条码格式](#supported-barcode-formats)下面的列表。

3. 在**建模**选项卡上，选择**数据类别** > **条形码**。

    ![](media/powerbi-desktop-mobile-barcodes/power-bi-desktop-barcode.png)

4. 在报表视图中，将此字段添加到所需的条形码筛选可视化效果。

5. 保存报表，并将其发布到 Power BI 服务。

现在当您打开[Power BI 应用的 iPhone](powerbi-mobile-ipad-iphone-apps.md)上扫描仪，扫描条码，您将看到此报表在报表的列表。 当您打开该报表时，按扫描产品条形码过滤其视觉效果。

## 支持的条码格式
以下是当您可以将它们标记 Power BI 报表中的 Power BI 识别条码︰ 

- UPCECode 
- Code39Code  
- A39Mod43Code 
- EAN13Code 
- EAN8Code  
- 93Code  
- 128Code 
- PDF417Code 
- Interleaved2of5Code 
- ITF14Code 

### 另请参阅  
- [扫描从 iPhone 上的 Power BI 应用条码](powerbi-mobile-scan-barcode-for-report.md)
- [使用扫描条形码在 iPhone 上的时出现问题](powerbi-mobile-scan-barcode-for-report.md#issues-with-scanning-a-barcode)
- [在 Power BI Desktop 中的数据分类](powerbi-desktop-data-categorization.md)  
- [Power bi 入门 iPhone 应用程序](powerbi-mobile-iphone-app-get-started.md)  
- [Power BI 入门](powerbi-service-get-started.md)  
