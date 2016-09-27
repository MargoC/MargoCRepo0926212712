---
# required metadata

title: Enable the JBA payment file format
description: In Japan, the Japanese Bankers Association (JBA) has specified a file format for electronic fund transfers (EFT). This procedure walks you through importing the JBA payment model and enabling the JBA payment file for vendor methods of payment. This procedure was created using the demo data company JPMF.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-07 20:13:57
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Application User
# ms.devlang: 
# ms.reviewer: 
ms.suite: Released: Dynamics AX 7.0.0 (February 2016)
# ms.tgt_pltfrm: 
ms.custom: 59291
ms.assetid: enable-the-jba-payment-file-format
ms.region: Japan
# ms.industry: 

---

Sub-task: Import the JBA payment model.
1.
Go to Organization administration &gt; Workspaces &gt; Electronic reporting.
2.
Click Repositories.
3.
Click Open.
4.
In the tree, select 'Payment model\\JBA Payment model\\JBA Payment file (JP)'.
5.
Click Import.
6.
Click Yes.
Sub-task: Use the JBA payment file in the vendor method of payment.
1.
Go to Accounts payable &gt; Payment setup &gt; Methods of payment.
2.
Click Edit.
3.
Expand or collapse the File formats section.
4.
Select the Generic electronic reporting check box.
5.
In the Export format configuration field, click the drop-down button to open the lookup.
6.
In the list, select JBA Payment file (JP).
7.
Click Save.

