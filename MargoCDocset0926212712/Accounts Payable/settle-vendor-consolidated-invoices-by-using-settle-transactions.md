---
# required metadata

title: Settle vendor consolidated invoices by using settle transactions
description: In Japan, payments are made and settled against consolidated invoice. This procedure walks you through settling a consolidated invoice using settle transactions. You need to make sure that a consolidated invoice is created and confirmed, and a payment is posted before running this procedure. This procedure was created using the demo data company JPMF.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-17 02:36:02
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Application User
ms.region: Japan
# ms.industry: 
# ms.devlang: 
# ms.reviewer: 
ms.suite: Released: Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
# ms.custom: 
ms.assetid: settle-vendor-consolidated-invoices-by-using-settle-transactions

---

Sub-task: Confirm Consolidation invoice to be settled.
1.
Go to Accounts payable &gt; Periodic tasks &gt; Consolidated invoice.
2.
Note the value in the Consolidation ID field to reference later
Confirm that the consolidated invoice to settle has a status of Confirmed. In this example: Consolidation ID - JPMF-000004
Sub-task: Settle Consolidation invoice .
1.
Go to Accounts payable &gt; Vendors &gt; All vendors.
2.
In the list, find and select the desired record.
Select the vendor that you want to settle the consolidated invoice for. In this example, we use JPMF-000002.
3.
On the Action Pane, click Invoice.
4.
Click Settle transactions.
5.
In the list, find and select the desired record.
Select the record with Consolidation ID = JPMF-000004.
6.
Select or clear the Mark check box.
Mark the Invoice.
7.
In the list, find and select the desired record.
Select the payment transaction, valued more than the Invoice amount.
8.
Select or clear the Mark check box.
Mark the payment transaction.
9.
Click Post.
Sub-task: Validate Consolidation invoice status to Settled.
1.
Go to Accounts payable &gt; Periodic tasks &gt; Consolidated invoice.
2.
Confirm that the status of the consolidated invoice is now "Settled".

