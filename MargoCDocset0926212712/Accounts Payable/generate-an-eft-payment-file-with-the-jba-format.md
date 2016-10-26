---
# required metadata

title: Generate an EFT payment file with the JBA format
description: In Japan, the Japanese Bankers Association (JBA) file format is commonly used for Electronic Fund Transfer (EFT) among banks. Use this task to learn how to generate an EFT file with the JBA format. This task uses the JPMF demo company data.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-07 20:14:22
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
ms.assetid: generate-an-eft-payment-file-with-the-jba-format

---

|     |                                                                                                      |
|-----|------------------------------------------------------------------------------------------------------|
| 1.  | Go to Accounts payable &gt; Payments &gt; Payment journal.                                           |
| 2.  | Click New.                                                                                           |
| 3.  | In the Name field, type 'VendPay'.                                                                   |
| 4.  | Click Lines.                                                                                         |
| 5.  | In the Account field, specify the values 'JPMF-000001'.                                              |
| 6.  | In the Debit field, enter a number.                                                                  |
| 7.  | Note the value in the Offset account field to reference later                                        |
| 8.  | Click Save.                                                                                          |
| 9.  | Click Generate payments.                                                                             |
| 10. | In the Method of payment field, select a method of payment that is enabled for the JBA file format.. |
| 11. | In the File name field, Specify a file name for the generated file..                                 |
| 12. | Use the value noted previously in the Bank account field                                             |
|     | Select a Offset bank account in the vendor journal lines.                                            |
| 13. | Click OK.                                                                                            |
| 14. | Toggle the slider if you want to print the payment control report.                                   |
| 15. | Click OK.                                                                                            |
| 16. | A .zip file will be generated and you will be prompted to download the file.                         |



