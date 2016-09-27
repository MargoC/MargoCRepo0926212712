---
# required metadata

title: Set up vendor master and purchase order to be target of consolidated invoice
description: In Japan, the vendors usually use consolidated invoice for transactions. This task walks you through configuring a vendor master and purchase order to use the consolidated invoice. This task was created using the demo data company JPMF.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-16 20:16:58
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
ms.custom: 65163
ms.assetid: set-up-vendor-master-and-purchase-order-to-be-target-of-consolidated-invoice
ms.region: Japan
# ms.industry: 

---

Sub-task: Set up vendor master.
1.
Go to Accounts payable &gt; Vendors &gt; All vendors.
2.
In the list, click the link in the selected row.
3.
Expand or collapse the Payment section.
4.
Verify that the terms of payment uses the Cutoff day.
5.
Specify a Consolidation day for the vendor.
Sub-task: Set a purchase order to be target of consolidated invoice.
1.
Go to Accounts payable &gt; Purchase orders &gt; All purchase orders.
2.
In the list, click the link in the selected row.
3.
On the Action Pane, click Options.
4.
Click Change view.
5.
Click Header view.
6.
Verify that the Target of consolidation slider is set to 'Yes'.

