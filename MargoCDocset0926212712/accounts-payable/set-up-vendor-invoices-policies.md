---
# required metadata

title: Set up vendor invoices policies
description: Vendor invoice policies are run when you post a vendor invoice by using the Vendor invoice page and when you open the vendor invoice Policy violations page. You can also configure the vendor invoice workflow to run vendor invoice policies every time that you submit an invoice to workflow. Vendor invoice policies do not apply to invoices that were created in the invoice register or invoice journal. Invoice matching validation does not use vendor invoice policies, but is instead set up in the Accounts payable parameters page. This recording uses the USMF demo company. The accounts payable manager or accounting manager role would perform these steps. Before you begin, make sure that the Invoice matching configuration key is selected.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-02-29 18:26:51
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
ms.custom: 56681
ms.assetid: set-up-vendor-invoices-policies
# ms.region: 
# ms.industry: 

---

Steps (43)
Sub-task: Prepare to create vendor invoice policies.
1.
Go to Accounts payable &gt; Setup &gt; Accounts payable parameters.
2.
Click the Invoice validation tab.
3.
Select or clear the Automatically update invoice header status check box.
4.
Click OK.
5.
In the Post invoice with discrepancies field, select an option.
6.
Close the page.
7.
Go to Accounts payable &gt; Policy setup &gt; Vendor invoice policies.
8.
Click Parameters.
9.
Click Add.
10.
Close the page.
Sub-task: Create policy rule types for vendor invoices.
1.
Go to Accounts payable &gt; Policy setup &gt; Vendor invoice policy rule types.
2.
Click New.
3.
In the Rule name field, type a value.
4.
In the Description field, type a value.
5.
In the Query name field, click the drop-down button to open the lookup.
6.
In the list, find and select the desired record.
7.
In the list, click the link in the selected row.
8.
Click Save.
9.
Close the page.
Sub-task: Define a vendor invoice policy.
1.
Go to Accounts payable &gt; Policy setup &gt; Vendor invoice policies.
2.
Click New.
3.
In the Name field, type a value.
4.
In the Description field, type a value.
5.
Expand or collapse the Policy organizations section.
6.
In the tree, select 'Contoso Entertainment System USA'.
7.
Click Add.
8.
Expand or collapse the Policy rules section.
9.
Click Create policy rule.
10.
In the Policy rule description field, type a value.
11.
Click Filter.
12.
Click Add.
13.
In the list, mark the selected row.
14.
In the Table field, click the drop-down button to open the lookup.
15.
In the list, click the link in the selected row.
16.
In the Derived table field, click the drop-down button to open the lookup.
17.
In the list, click the link in the selected row.
18.
In the Field field, click the drop-down button to open the lookup.
19.
In the Field field, type a value.
20.
Close the page.
21.
In the Criteria field, type a value.
22.
Click OK.
23.
Click OK.
24.
Close the page.
