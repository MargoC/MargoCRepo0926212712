---
# required metadata

title: Enter and post invoice in the Invoice register using the approval journal
description: This task guide will show you how to use the invoice register to create invoices and then use the approval journal to update the expense accounts.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-02-24 14:16:42
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
ms.custom: 52091
ms.assetid: key-invoice-data-in-ap-system-using-invoice-register
# ms.region: 
# ms.industry: 

---

Sub-task: Create and post and invoice.
1.
Start entering invoices by creating a new invoice register.
Go to Accounts payable &gt; Invoices &gt; Invoice register.
2.
Click New.
3.
Select the name of the invoice register that you want to use.
4.
In the list, click the link in the selected row.
5.
Click on Lines to open the register and enter expense lines.
6.
Select a vendor. For example, enter or select US-104
7.
In the Invoice field, type a value.
8.
In the Description field, type a value.
9.
In the Credit field, enter a number.
10.
All invoices in the invoice register must be approved. You must select the person that will approve the journal.
In the Approved by field, click the drop-down button to open the lookup.
11.
Highlight an approver and click Select to select that approver.
12.
Post the invoice register to add these invoices to the vendor balance. It will also post the expense to a pending invoices account.
Click Post.
13.
Close the page.
14.
Close the page.
Sub-task: Approve an invoice.
1.
You will use the approval journal to move the expenses that were posted to the pending invoices account into an expense account,
Go to Accounts payable &gt; Invoices &gt; Invoice approval.
2.
Click New.
3.
Select the name of the invoice approval journal that you want to use.
4.
In the list, click the link in the selected row.
5.
Click lines to display a page where you will be able to select the invoices that you want to approve.
6.
Select Find Vouchers to display all of the invoices that are ready for approval.
7.
Mark the invoice that you created.
8.
Click Select.
9.
The vouchers that you selected above are moved to this list after you select them.
10.
Click OK.
11.
Click on the account number field to add an expense account to the invoice.
12.
Enter an account number and tab off of the field. For example, enter 600120.
13.
Click Post.
14.
Click Voucher to view the entries that were posted.
15.
The Invoice Pending Approval account is reversed and replaced with the actual expense account.

