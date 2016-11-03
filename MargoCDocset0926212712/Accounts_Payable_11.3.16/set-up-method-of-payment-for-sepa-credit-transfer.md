---
# required metadata

title: Set up method of payment for SEPA credit transfer | Microsoft Docs
description: 
author: annbe
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
# ms.devlang: 
# ms.reviewer: 
ms.suite: Released- Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
ms.custom: 69864
ms.assetid: f5a89ea2-9c2c-47f9-bd57-99c33c4d19ff
# ms.region: 
# ms.industry: 
ms.author: tfehr

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



