---
title: Bank reconciliation report (BankReconciliation)
TOCTitle: Bank reconciliation report (BankReconciliation)
ms:assetid: 5bdd1889-f95b-4865-a571-a21fef090303
ms:mtpsurl: https://technet.microsoft.com/library/Aa583948(v=AX.60)
ms:contentKeyID: 36058819
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankReconciliation
- reconciliation
- bank report
- bank reconciliation report
- reconciliation report
---

# Bank reconciliation report (BankReconciliation) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Bank reconciliation** report displays the bank statement ending balance, the unreconciled bank transactions by the ending date, the closing amount, and the difference between the unreconciled bank transactions by the ending date and the closing amount.

## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>BankReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Common</strong> &gt; <strong>Bank accounts</strong>. On the <strong>Action Pane</strong>, on the <strong>Bank account</strong> tab, click <strong>Account reconciliation</strong>. Click <strong>Print</strong> &gt; <strong>Bank reconciliation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankReconciliationTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the BankReconciliationController.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


