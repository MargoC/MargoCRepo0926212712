---
# required metadata

title: Enter and post invoices in the invoice journal | Microsoft Docs
description: This task guide will show how to record vendor invoices that are not associated with purchase orders. Examples of this type of invoice include expenses for supplies or services. This recording uses the USMF demo company. 
author: annbe
manager: AnnBe
ms.date: 2016-02-24 14:16:19
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
ms.custom: 52061
ms.assetid: 7ffa73a6-a4f2-46a8-a985-e7770416dd40
# ms.region: 
# ms.industry: 
ms.author: tfehr

---

|     |                                                                                                        |
|-----|--------------------------------------------------------------------------------------------------------|
| 1.  | Go to Accounts payable &gt; Workspaces &gt; Vendor invoice entry.                                      |
| 2.  | Click New invoice journal.                                                                             |
| 3.  | Click New.                                                                                             |
| 4.  | In the Name field, enter the journal name or click the drop down button to open the lookup.            |
| 5.  | In the Description field, type a value.                                                                |
| 6.  | Click Lines.                                                                                           |
| 7.  | In the Date field, enter the posting date that will update General Ledger.                             |
| 8.  | In the Account field, specify the Vendor account.                                                      |
| 9.  | In the Invoice field, enter the invoice number.                                                        |
| 10. | In the Description field, type a value.                                                                |
| 11. | In the Credit field, enter a number.                                                                   |
| 12. | In the Offset account field, enter the account number or click the drop down button to open the lookup |
| 13. | The Sales tax group will default from the vendor account.                                              |
| 14. | The Item sales tax group will default from the main account specified in the Offset account field.     |
| 15. | The Due date will be calculated based on the Terms of payment.                                         |
| 16. | The Cash discount will default from the Vendor account.                                                |
| 17. | Click Post.                                                                                            |
| 18. | Close the page.                                                                                        |



