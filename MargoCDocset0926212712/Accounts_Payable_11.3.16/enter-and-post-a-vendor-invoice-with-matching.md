---
# required metadata

title: Enter and post a vendor invoice with matching | Microsoft Docs
description: This task guide will help you create a vendor invoice from a purchase order and view the results of matching the purchase order, receipt, and invoice (3 way matching).
author: annbe
manager: AnnBe
ms.date: 2016-02-24 15:46:22
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Application User
# ms.devlang: 
ms.reviewer: 101
ms.suite: Released- Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
ms.custom: 53461
ms.assetid: a1aa60fc-25ae-4beb-aa97-ea7a09aba392
# ms.region: 
# ms.industry: 
ms.author: tfehr

---

Sub-task: Create a purchase order.
1.
Let's start by creating a purchase order.
Go to Accounts payable &gt; Purchase orders &gt; All purchase orders.
2.
Click New.
3.
In the Vendor account field, click the drop-down button to open the lookup.
4.
Find a vendor to select. For example, scroll down to US-104.
5.
Select vendor US-104.
6.
Click OK.
7.
In the Item number field, click the drop-down button to open the lookup.
8.
Select an inventory item. For example, select item number 1000.
9.
Matching policies can be overridden for each line on an invoice. You can do that in the line details.
Expand or collapse the Line details section.
10.
Click the Setup tab.
11.
You can override the matching policy to use no matching, 2-way matching, or 3-way matching.
12.
Expand or collapse the Line details section.
13.
You must confirm the purchase order before you can process receipts against it.
On the Action Pane, click Purchase.
14.
Click Confirm.
Sub-task: Receive the products.
1.
Let's assume that you received the goods. You can now enter the product receipt.
On the Action Pane, click Receive.
2.
Click Product receipt.
3.
In the Product receipt field, enter the product receipt number. For example, enter PR123.
4.
Click OK to post the product receipt.
5.
Close the page.
Sub-task: Create a vendor invoice.
1.
When the invoice arrives, we need to find the purchase order that matches the invoice.
Go to Accounts payable &gt; Purchase orders &gt; Purchase orders received but not invoiced.
2.
Select the purchase order that you created.
3.
Now that we are viewing the purchase order, we can create a vendor invoice for it.
On the Action Pane, click Invoice.
4.
Click Invoice.
5.
This is a required field. If you have turned on duplicate checking in the parameters, you will receive an error during posting if you try to use the same invoice twice on the same day.
In the Number field, enter the invoice number.
6.
In the Invoice description field, type a value.
7.
In the Invoice date field, enter a date.
8.
Let's assume that the invoice came in with a unit price of 1200 instead of the 899 price on the original purchase order.
In the Unit price field, enter 1200.
9.
You can also add lines to the invoice that were not on the original purchase order. For example, you may have an unexpected installation charge.
Click Add line.
10.
Let's add the installation charge.
In the Item number field, click the drop-down button to open the lookup.
11.
In the list, find the installation charge item number. For example, S0001
12.
Select the installation charge item number.
13.
Note that matching has not been performed since you made the changes.
14.
Click Update match status.
15.
Our matching status shows Failed. Let's look at the matching details to find out why it failed.
On the Action Pane, click Review.
16.
Click Matching details.
17.
The new line with services does not need to be matched so the status stays "Not performed".
18.
Select the product receipt for the inventory item that you received.
19.
The line with the product receipt was matched but there is a mismatch of quantity or price so it fails.
20.
Let's assume that you called the vendor and you found that they had made a mistake. They agreed to 899 and they will send another invoice.
In the Unit price field, enter a number.
21.
Now that the unit price matches, the status is updated to Passed. If your policy allows discrepancies or if matching is only a warning, you can still post the invoice.
22.
Close the page.
23.
Click Post.
24.
Close the form.
25.
Note that the purchase order is no longer listed as received but not invoiced.

