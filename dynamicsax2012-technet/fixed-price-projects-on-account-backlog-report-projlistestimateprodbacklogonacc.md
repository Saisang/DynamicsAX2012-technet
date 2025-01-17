---
title: Fixed-price projects - on-account backlog report (ProjListEstimateProdBacklogOnAcc)
TOCTitle: Fixed-price projects - on-account backlog report (ProjListEstimateProdBacklogOnAcc)
ms:assetid: 9c2a6145-209b-47ad-a4e9-929fa0bf6ccc
ms:mtpsurl: https://technet.microsoft.com/library/Aa617273(v=AX.60)
ms:contentKeyID: 37820223
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListEstimateProdBacklogOnAcc
---

# Fixed-price projects - on-account backlog report (ProjListEstimateProdBacklogOnAcc) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze any on-account backlogs for fixed-price projects.

The on-account backlog is the amount of hours, expenses, and items that remain to be invoiced on an estimate project. When the amount already invoiced on an estimate project is deducted from the contract amount, the remaining amount is the on-account backlog.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Period code</strong></p></td>
<td><p>Select a period code for estimate projects. The period code that you select determines the date range.</p></td>
</tr>
<tr class="even">
<td><p><strong>Estimate date</strong></p></td>
<td><p>Select an estimate date range that you want to include on the report.</p></td>
</tr>
</tbody>
</table>


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
<td><p>ProjListEstimate</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListEstimate</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListEstimateProdBacklogOnAcc</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Estimates</strong> &gt; <strong>Backlog</strong> &gt; <strong>Fixed-price projects - on-account backlog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListEstimateDP.processReport

  - ProjListEstimateTmp table

  - ProjWIPTable


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListEstimateDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


