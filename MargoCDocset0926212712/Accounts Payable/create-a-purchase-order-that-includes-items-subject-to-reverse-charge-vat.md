---
# required metadata

title: Create a purchase order that includes items subject to reverse charge VAT
description: This task walks you through creating a purchase order that includes items subject to reverse charge VAT for the United Kingdom. This walkthrough was created using the demo company GBSI. Prior to this task, the “Set up reverse charge VAT” tasks should be completed.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-21 20:08:11
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Application User
ms.region: United Kingdom
# ms.industry: 
# ms.devlang: 
# ms.reviewer: 
ms.suite: Released: Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
# ms.custom: 
ms.assetid: create-a-purchase-order-that-includes-items-subject-to-reverse-charge-vat

---

Sub-task: Create a purchase order.
1.
Go to Accounts payable &gt; Purchase orders &gt; All purchase orders.
2.
Click New.
3.
In the Vendor account field, click the drop-down button to open the lookup.
Select 'GB\_SI\_000002'
4.
In the list, find and select the desired record.
Select 'GB\_SI\_000002'
5.
In the list, click the link in the selected row.
6.
Click OK.
7.
In the list, mark the selected row.
8.
In the Item number field, type a value.
Enter 'S0020'
9.
In the Quantity field, enter a number.
Set Quantity to '4'
10.
In the Unit price field, enter a number.
Set Unit price to '1000'
11.
Click Add line.
12.
In the Item number field, type a value.
Enter 'S0012'
13.
In the Quantity field, enter a number.
Set Quantity to '6'
14.
In the Unit price field, enter a number.
Set Unit price to '1000'
15.
Click Save.
16.
Expand or collapse the Line details section.
Validate that Reverse charge VAT groups are set in Sales tax group and Item tax group
17.
Click the Setup tab.
Validate that Reverse charge VAT groups are set in Sales tax group and Item tax group: RC-VAT
18.
In the list, select row 1.
Select the 1st line and validate that Reverse charge VAT groups are set in Sales tax group and Item tax group: RC-VAT
19.
On the Action Pane, click Purchase.
20.
Click Sales tax.
Observe the calculated Reverse charge VAT transactions: Sales tax transactions with incoming and outgoing direction
21.
Click OK.

