---
# required metadata

title: Set up an invoice declaration for vendors
description: This procedure walks you through setting up the Icelandic invoice declaration. The demo data company used to create this procedure is DEMF with the country of legal entity primary address updated to Iceland.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-21 20:07:06
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
ms.custom: 69242
ms.assetid: set-up-an-invoice-declaration-for-vendors
ms.region: Iceland
# ms.industry: 

---

Sub-task: Import invoice declaration GER configurations.
1.
Go to Organization administration &gt; Workspaces &gt; Electronic reporting.
2.
Click Set active.
3.
Click Repositories.
4.
Click Open.
5.
Find or select configuration.
Click Show filters.
Please add a criterion to filter by the Configuration name and enter Vendor invoice declaration (IS) or find the configuration in the list, select it and move to the next step.
6.
Click Apply.
7.
Click Import.
8.
Click Yes.
9.
Find or select a configuration
Add filter
Add a criterion to filter by the Configuration name and enter Vendor invoice declaration report (IS) or find the configuration in the list, select it and move to the next step.
10.
Click Apply.
11.
Click Import.
12.
Click Yes.
Sub-task: Enable vendor invoice declaration.
1.
Go to Accounts payable &gt; Setup &gt; Vendor invoice declaration.
2.
Click New.
3.
In the Invoice declaration field, type 'SubC'.
4.
In the Description field, type 'Sub-contractor'.
5.
In the Reporting code field, type '06'.
6.
Click New.
7.
In the Invoice declaration field, type 'Gift'.
8.
In the Description field, type 'Gifts'.
9.
In the Reporting code field, type '34'.
10.
In the Record type field, select 'LA'.
11.
Click Save.

