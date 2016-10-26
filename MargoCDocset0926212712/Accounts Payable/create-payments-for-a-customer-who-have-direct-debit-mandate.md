---
# required metadata

title: Create payments for a customer who have direct debit mandate
description: This task walks you through generating a SEPA direct debit payment file for a customer who has direct debit configured and an invoice to be paid. Before you can complete this task, you must have already completed other SEPA direct debit related tasks. You must first import customer payment electronic reporting configurations, configure method of payments and you must set up your company and customer information.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-21 21:07:09
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
ms.assetid: create-payments-for-a-customer-who-have-direct-debit-mandate

---

Sub-task: Post a free text invoice with direct debit information.
1.
Go to Accounts receivable &gt; Invoices &gt; All free text invoices.
2.
Click New.
3.
In the Customer account field, enter or select a value.
4.
In the Method of payment field, enter or select a value.
5.
In the Direct debit mandate ID field, enter or select a value.
6.
Click Add line.
7.
In the Description field, type a value.
8.
In the Main account field, specify the desired values.
9.
In the Unit price field, enter a number.
10.
Click Post.
11.
Click OK.
Sub-task: Create a payment.
1.
Go to Accounts receivable &gt; Payments &gt; Payment journal.
2.
Click New.
3.
In the Name field, enter or select a value.
4.
Click Lines.
5.
Click Payment proposal.
6.
Click Create payment proposal.
7.
Expand the Records to include section.
8.
Click Filter.
9.
In the list, find and select the desired record.
10.
In the Criteria field, enter or select a value.
11.
Click OK.
12.
Click OK.
13.
Click Create payments.
Sub-task: Generate a payment file.
1.
Click Functions.
2.
Click Generate payments.
3.
In the Method of payment field, enter or select a value.
4.
In the File name field, type a value.
5.
In the Bank account field, enter or select a value.
6.
Click OK.
7.
In the Processing date field, enter a date.
8.
Click OK.

