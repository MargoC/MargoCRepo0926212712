---
# required metadata

title: FR-00003 NAF codes and Siret numbers
description: This procedure shows how to create NAF codes and then enter the codes for legal entities, customers, vendors, and prospects. NAF codes are used to identify the business of an enterprise. For instance, if your legal entity manufactures computers, the NAF code for your legal entity may be 300C, which is the NAF code for manufacturing computers and other computer hardware. If your legal entity is involved in building houses, your NAF code may be 452A. This procedure also shows how to enter siret numbers for customers, vendors, and prospects. The siret is a 14-digit number that identifies a business, a branch of the business, and a person who is associated with the business activity. You can use the siret number to verify that an enterprise is correctly registered and authorized to do business with you. This procedure was created using the demo data company FRSI. This functionality is available for legal entities whose primary address is in France.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-07-21 18:22:33
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Application User
ms.region: France
# ms.industry: 
# ms.devlang: 
ms.reviewer: 81
ms.suite: Released: Dynamics AX application 7.0.1
# ms.tgt_pltfrm: 
# ms.custom: 
ms.assetid: fr-00003-naf-codes-and-siret-numbers

---

Steps (34)
Sub-task: Set up a NAF code.
1.
Go to Organization administration &gt; Global address book &gt; Addresses &gt; NAF codes.
2.
Click New.
3.
In the NAF code field, type a value.
4.
In the Description field, type a value.
5.
Click Save.
Sub-task: Enter a NAF code and a siret number for a customer.
1.
Go to Accounts receivable &gt; Customers &gt; All customers.
2.
Click the customer record that you want to update.
3.
Expand the Sales demographics section.
4.
Click Edit.
5.
In the French Siret field, type a value.
6.
In the NAF code field, enter or select a value.
7.
Click Save.
Sub-task: Enter a NAF code and a siret number for a vendor.
1.
Go to Accounts payable &gt; Vendors &gt; All vendors.
2.
Click the vendor record that you want to update.
3.
Expand the Purchasing demographics section.
4.
Click Edit.
5.
In the French Siret field, type a value.
6.
In the NAF code field, enter or select a value.
7.
Click Save.
Sub-task: Enter a NAF code and a siret number for a prospect.
1.
Go to Sales and marketing &gt; Relationships &gt; Prospects &gt; All prospects.
2.
In the list, find and select the desired record.
3.
Click the prospect record that you want to update.
4.
Expand the Sales demographics section.
5.
Click Edit.
6.
In the French Siret field, type a value.
7.
In the NAF code field, enter or select a value.
8.
Click Save.
Sub-task: Set up commerce registration, a legal form, and a NAF code for a legal entity.
1.
Go to Organization administration &gt; Organizations &gt; Legal entities.
2.
Expand the Registration numbers section.
3.
Click Edit.
4.
In the Commerce registration field, type a value.
Enter the name of the French agency where the legal entity is registered, such as the Registre du commerce et des sociétés.
5.
In the NAF code field, enter or select a value.
6.
In the Legal form field, type a value.
Enter the legal type of the legal entity, such as non-profit organization, manufacturing company, or financial institution.
7.
Click Save.



