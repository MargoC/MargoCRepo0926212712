---
# required metadata

title: Set up vendors and vendor bank accounts for SEPA credit transfers
description: This procedure demonstrates how to set up the vendor and vendor specific bank account information required for SEPA payment file generation. The demo data company used to create this procedure is DEMF.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-18 19:56:12
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Application User
# ms.region: 
# ms.industry: 
# ms.devlang: 
# ms.reviewer: 
ms.suite: Released: Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
# ms.custom: 
ms.assetid: set-up-vendor-and-vendor-bank-account-for-sepa-payment-generation

---

Sub-task: Set up bank details.
1.
Go to Accounts payable &gt; Vendors &gt; All vendors.
2.
Use the Quick Filter to find records. For example, filter on the Vendor account field with a value of 'DE-001'.
3.
Click DE-001 to open vendor details.
4.
On the Action Pane, click Vendor.
5.
Click Bank accounts.
6.
Click Edit.
If there is no bank account available, you need to create a new one.
7.
In the SWIFT code field, type 'COBADEFFXXX'.
8.
In the IBAN field, type 'DE36200400000628808808'.
9.
Close the page.
Sub-task: Set up method of payment for the vendor.
1.
Click Edit.
2.
Expand or collapse the Payment section.
3.
In the Method of payment field, click the drop-down button to open the lookup.
4.
In the list, click the link in the SEPA CT row.
5.
Click Save.

