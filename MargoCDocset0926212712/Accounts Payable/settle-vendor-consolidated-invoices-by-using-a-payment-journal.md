---
# required metadata

title: Settle vendor consolidated invoices by using a payment journal
description: In Japan, payments are made and settled against consolidated invoices. This procedure walks you through settling a consolidated invoice using a payment journal and payment proposal feature. Before you complete this procedure, be sure that you have a consolidated invoice created and confirmed. This procedure was created using the demo data company JPMF.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-17 02:35:51
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
ms.assetid: settle-vendor-consolidated-invoices-by-using-a-payment-journal

---

|     |                                                                                                        |
|-----|--------------------------------------------------------------------------------------------------------|
| 1.  | Go to Accounts payable &gt; Periodic tasks &gt; Consolidated invoice.                                  |
| 2.  | Find a consolidated invoice that was confirmed.                                                        |
|     | Note the value in the Consolidation ID field to reference later                                        |
|     | You can use JPMF-000002 from the demo data company JPMF.                                               |
| 3.  | Go to Accounts payable &gt; Payments &gt; Payment journal.                                             |
| 4.  | Click New.                                                                                             |
| 5.  | In the Name field, click the drop-down button to open the lookup.                                      |
| 6.  | In the list, click the link in the selected row.                                                       |
| 7.  | Click Lines.                                                                                           |
| 8.  | Click Payment proposal.                                                                                |
| 9.  | Click Create payment proposal.                                                                         |
| 10. | Expand or collapse the Advanced parameters section.                                                    |
| 11. | In the Consolidation ID field, type a value.                                                           |
|     | You can use the value noted previously on the Consolidated invoice page.                               |
| 12. | Click OK.                                                                                              |
| 13. | Click Create payments.                                                                                 |
| 14. | Confirm that the payment line was generated based on the proposal and then provide a date for posting. |
| 15. | Click Post.                                                                                            |
| 16. | Go to Accounts payable &gt; Periodic tasks &gt; Consolidated invoice.                                  |
| 17. | Confirm that the status of the consolidated invoice has been updated to be Settled.                    |



