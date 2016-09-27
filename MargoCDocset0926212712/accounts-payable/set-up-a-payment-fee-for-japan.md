---
# required metadata

title: Set up a payment fee for Japan
description: This task walks you through setting up a payment fee for Japan. This task was created using the demo data company JPMF.
author: lcstaskguide
manager: AnnBe
ms.date: 2016-03-16 20:16:46
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
ms.custom: 65133
ms.assetid: set-up-a-payment-fee-for-japan
ms.region: Japan
# ms.industry: 

---

Sub-task: Create a bank group.
1.
Go to Cash and bank management &gt; Setup &gt; Bank groups.
2.
Click New.
3.
In the Bank groups field, type a value.
4.
In the Name field, type a value.
5.
Expand the General section.
6.
In the Bank code field, type a value.
7.
In the Branch code field, type a value.
8.
Click Save.
Sub-task: Create a vendor payment fee group.
1.
Go to Accounts payable &gt; Payment setup &gt; Vendor payment fee groups.
2.
Click New.
3.
In the Vendor payment fee group field, type a value.
For example: enter 'PaymFee'.
4.
In the Description field, type a value.
5.
Click Save.
Sub-task: Specify a payment fee group for a vendor.
1.
Go to Accounts payable &gt; Vendors &gt; All vendors.
2.
In the list, click the link in the selected row.
3.
Click Edit.
4.
Expand the Payment section.
5.
In the Vendor payment fee group field, click the drop-down button to open the lookup.
6.
In the list, click the link in the selected row.
For example: select 'VendPayFee'.
7.
Click Save.
Sub-task: Create bank rules for payment fee.
1.
Go to Accounts payable &gt; Payment setup &gt; Bank rules for payment fee.
2.
Click New.
3.
In the ID field, type a value.
4.
In the Name field, type a value.
5.
Expand the General section.
6.
Click Add.
Add one or more filters to create the bank rule.
7.
In the Third party bank group field, click the drop-down button to open the lookup.
Enter the vendor's bank criteria to filter.
8.
In the list, find and select the desired record.
9.
In the list, click the link in the selected row.
For example: select 'Bank code'.
10.
In the Company bank group field, click the drop-down button to open the lookup.
11.
In the list, click the link in the selected row.
12.
Repeat the steps to add criteria for the payment fee generation rule.
13.
Click Save.
Sub-task: Create a payment fee.
1.
Go to Accounts payable &gt; Payment setup &gt; Payment fee.
2.
Click New.
3.
In the Fee ID field, type a value.
4.
In the Name field, type a value.
5.
In the Fee description field, type a value.
6.
In the Charge field, select 'Ledger'.
7.
In the Ledger account field, specify the desired values.
8.
In the Payment fee account field, specify the desired values.
9.
In the Journal type field, select an option.
For example: select 'Vendor disbursement'.
10.
Click Save.
11.
Click Payment fee setup.
12.
In the Groupings field, select an option.
For example: select 'Group'.
13.
In the Bank relation field, click the drop-down button to open the lookup.
14.
In the list, click the link in the selected row.
For example: select '0001\_009'.
15.
In the Vendor group type field, select an option.
If you select 'Group', it can be easier to configure.
16.
In the Vendor account/group field, type a value.
For example: enter 'VendPayFee'.
17.
In the Method of payment field, click the drop-down button to open the lookup.
18.
In the list, click the link in the selected row.
For example: select 'Bank'.
19.
In the Bank rule ID for payment fee field, type a value.
For example: enter 'DiffBank'.
20.
Click the General tab.
21.
In the Payment currency field, type a value.
For example: enter 'JPY'.
22.
In the Minimum field, enter a number.
For example: enter '30000'.
23.
In the Percentage/Amount field, select an option.
For example: select 'Amount'.
24.
In the Fee amount field, enter a number.
Set field '630'
25.
In the Fee currency field, type a value.
For example: enter 'JPY'.
26.
In the Sales tax group field, click the drop-down button to open the lookup.
27.
In the list, click the link in the selected row.
For example: select 'JP'.
28.
In the Item sales tax group field, click the drop-down button to open the lookup.
29.
In the list, click the link in the selected row.
For example: select 'Taxable'.
30.
Click Save.

