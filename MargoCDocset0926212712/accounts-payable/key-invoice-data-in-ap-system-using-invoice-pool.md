---
# required metadata

title: Enter and post invoice in the Invoice register and invoice pool
description: This task guide will show you how to use the invoice register to create invoices. Then use the invoice pool to match the invoice to a purchase order and finalize the expense in the vendor invoice page.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-02-24 14:18:22
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
ms.suite: Released: Dynamics AX 7.0.0 (February 2016)
# ms.tgt_pltfrm: 
ms.custom: 52121
ms.assetid: key-invoice-data-in-ap-system-using-invoice-pool
# ms.region: 
# ms.industry: 

---

Sub-task: Create a purchase order.
1.
Let's create a purchase order to match to our invoice. This purchase will be a services purchase order.
Go to Accounts payable &gt; Purchase orders &gt; All purchase orders.
2.
Click New to create a purchase order.
3.
In the Vendor account field, click the drop-down button to open the lookup.
4.
Select the vendor from the list. For example, vendor 1001.
5.
Click OK.
6.
In the Item number field, click the drop-down button to open the lookup.
7.
Find the services item number in the list. For example, select S0001.
8.
Click on the item number and select it.
9.
The net amount is 75.00. That is the amount that we will expect on the invoice.
10.
The purchase order needs to be confirmed before we continue.
On the Action Pane, click Purchase.
11.
Click Confirm.
Sub-task: Create and post and invoice.
1.
Create a new invoice register so that you can add an invoice.
Go to Accounts payable &gt; Invoices &gt; Invoice register.
2.
Click New.
3.
Open the lookup to select the name of the invoice register that you want to use.
4.
Select the name of the invoice register that you want to use.
5.
Click on Lines to open the register and enter expense lines.
6.
In the lookup, select a vendor. For example, click on vendor 1001.
7.
In the Invoice field, enter the invoice number.
8.
In the Description field, type a value.
9.
Enter the invoice amount. It should match your purchase order.
In the Credit field, enter a number.
10.
Add the purchase order that you created earlier. By adding it here, you will be able to apply the invoice to the purchase order from the invoice pool.
In the Purchase order field, click the drop-down button to open the lookup.
11.
Select the purchase order that you created earlier.
12.
All invoices in the invoice register must be approved. Select the person that will approve the journal.
In the Approved by field, click the drop-down button to open the lookup.
13.
Highlight an approver and click Select to select that approver.
14.
Post the invoice register to add these invoices to the vendor balance. It will also post the expense to a pending invoices account.
Click Post.
15.
Close the page.
16.
Close the page.
Sub-task: Open an invoice from the pool and match it to a purchase order to complete the invoice process.
1.
Now we will go to the invoice pool to find approved invoices that we want to finalize with a vendor invoice.
Go to Accounts payable &gt; Invoices &gt; Invoice pool.
2.
Click Purchase order to create a vendor invoice from the invoice in the pool.
3.
Select the invoice that you want to review.
4.
Click Update match status to complete the matching.
5.
Once you have validated the invoice amounts, you can post the invoice. This must be done from the vendor invoice grid.
On the Action Pane, click Options.
6.
Click Change view.
7.
Click Grid view.
8.
The posting process will reverse the accrual and post the expense to the account on the purchase order.
Click Post.
9.
Close the page.
10.
Let's review the journal entries that were created for the invoice.
Go to Accounts payable &gt; Vendors &gt; All vendors.
11.
Select the vendor that was on the purchase order. For example, select vendor 1001.
12.
In the list, click the link in the selected row.
13.
On the Action Pane, click Vendor.
14.
Click Transactions.
15.
Select the invoice that you created.
16.
The invoice register accrual was reversed and posted to the appropriate expense account.
 

