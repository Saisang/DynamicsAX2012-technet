---
title: Fixed asset reserve transactions report (AssetReserveTransactions)
TOCTitle: Fixed asset reserve transactions report (AssetReserveTransactions)
ms:assetid: de8b08c5-a93b-4ce9-ad7e-39967588f3f8
ms:mtpsurl: https://technet.microsoft.com/library/Aa591674(v=AX.60)
ms:contentKeyID: 36687384
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.AssetReserveTransactions
---

# Fixed asset reserve transactions report (AssetReserveTransactions) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print information about reserve transactions.

When a fixed asset is sold with a profit, the profit can be credited to a provision for reserve account, which is typically set up as a balance sheet account. This reserve is dissolved when a replacement fixed asset is acquired or when the legal deadline for the dissolution of the reserve expires.

Use the **Fixed asset posting profiles** form to assign a main account to the **Provision for reserve** transaction type.

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
<td><p>AssetReserveTransactions</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\AssetReserveTransactions</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>AssetReserveTransactions</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Fixed asset reserve transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - AssetReserveTransactionsTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the AssetReserveTransactionsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About fixed asset reserves](about-fixed-asset-reserves.md)

[Fixed asset posting profiles (form)](https://technet.microsoft.com/library/aa571467\(v=ax.60\))

  


