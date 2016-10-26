---
# required metadata

title: Set up method of payment for SEPA credit transfer
description: 
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-22 20:01:58
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
ms.assetid: set-up-method-of-payment-for-sepa-credit-transfer

---

|     |                                                                                                                                                                                                                             |
|-----|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.  | Go to Accounts payable &gt; Payment setup &gt; Methods of payment.                                                                                                                                                          |
| 2.  | Use the Quick Filter to find records. For example, filter on the Method of payment field with a value of 'SEPA CT'.                                                                                                         |
| 3.  | Click Edit.                                                                                                                                                                                                                 |
| 4.  | In the Period field, select 'Total'.                                                                                                                                                                                        |
| 5.  | In the Payment type field, select 'Electronic payment'.                                                                                                                                                                     |
| 6.  | Select Yes in the Generic electronic reporting field.                                                                                                                                                                       |
| 7.  | In the Export format configuration field, enter or select a value.                                                                                                                                                          |
|     | In the list, select the value ISO20022 Credit transfer (DE). If the list is empty, it means that there is no vendor payment export format configuration imported and active. Please follow the relevant guide to import it. |
| 8.  | In the Account type field, select 'Bank'.                                                                                                                                                                                   |
| 9.  | In the Payment account field, specify the values 'DEMF OPER'.                                                                                                                                                               |
| 10. | Click Save.                                                                                                                                                                                                                 |



