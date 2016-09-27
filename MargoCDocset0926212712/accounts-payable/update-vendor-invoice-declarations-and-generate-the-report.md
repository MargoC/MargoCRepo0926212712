---
# required metadata

title: Update vendor invoice declarations and generate the report
description: 
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-21 20:07:59
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
ms.custom: 69272
ms.assetid: update-vendor-invoice-declarations-and-generate-the-report
ms.region: Iceland
# ms.industry: 

---

Sub-task: Post a vendor invoice.
1.
Go to Accounts payable &gt; Invoices &gt; Invoice journal.
2.
Click New.
3.
In the Name field, In the Name field, select 'APInvoice'.
4.
Click Lines.
5.
In the Account field, specify the values 'IS-001'.
6.
In the Invoice field, type 'IS-001-01'.
7.
In the Credit field, enter a number.
8.
In the Offset account field, specify the values '200130--'.
9.
Click the Invoice tab.
10.
In the Document field, type a value.
11.
In the Invoice date field, enter today's date.
12.
In the Invoice declaration field, click the drop-down button to open the lookup.
13.
In the list, select the Invoice declaration category.
14.
Click Post.
Sub-task: Generate an invoice declaration.
1.
Go to Accounts payable &gt; Inquiries and reports &gt; Invoice &gt; Vendor invoice declaration report.
2.
In the Authority field, click the drop-down button to open the lookup.
3.
In the list, click the link in the selected row.
4.
In the From date field, enter a date.
5.
In the To date field, enter a date.
6.
Check the Create report file checkbox.
7.
In the Name field, select 'Vendor invoice declaration report (IS)'..
8.
Check the Create text file checkbox.
9.
In the Name field, select 'Vendor invoice declaration (IS)'.
10.
Click OK.

