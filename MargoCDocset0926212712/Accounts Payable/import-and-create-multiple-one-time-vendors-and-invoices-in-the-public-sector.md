---
# required metadata

title: Import and create multiple one-time vendors and invoices in the public sector
description: 
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-31 20:35:56
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Application User
# ms.region: 
ms.industry: Public sector
# ms.devlang: 
# ms.reviewer: 
ms.suite: Released: Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
# ms.custom: 
ms.assetid: import-and-create-multiple-one-time-vendors-and-invoices-in-the-public-sector

---

Steps (7)
|     |                                                                                                                                                                                                                                                                                                                                   |
|-----|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.  | Caution: Importing a new file overwrites any records that have been imported but not processed, and the invoices for those vendors won’t be created. To determine whether unprocessed records exist, click Cancel, and then go to the Process one-time vendors and generate invoices page. Then continue with the following step. |
|     | Go to Accounts payable &gt; Periodic tasks &gt; Import one-time vendors and invoices.                                                                                                                                                                                                                                             |
| 2.  | Browse for and select the CSV file that contains vendor information.                                                                                                                                                                                                                                                              |
| 3.  | In the Account structure field, click the drop-down button to open the lookup.                                                                                                                                                                                                                                                    |
| 4.  | In the list, find and select the desired record.                                                                                                                                                                                                                                                                                  |
| 5.  | Click OK.                                                                                                                                                                                                                                                                                                                         |
|     | The vendor and invoice information is imported. If there are errors, a report will be printed, and you should correct any listed entries in the import file and then reimport the file.                                                                                                                                           |
| 6.  | Select whether you want to process vendor records for vendors who already have a record in your system.                                                                                                                                                                                                                           |
|     | Go to Accounts payable &gt; Periodic tasks &gt; Process one-time vendors and invoices.                                                                                                                                                                                                                                            |
|     | Microsoft Dynamics AX looks for duplicate vendor names or Federal tax IDs. Important: If you choose not to process duplicate vendors, the related invoices won’t be processed either. You can manually create an invoice by using the information in the CSV file.                                                                |
| 7.  | Click OK.                                                                                                                                                                                                                                                                                                                         |



