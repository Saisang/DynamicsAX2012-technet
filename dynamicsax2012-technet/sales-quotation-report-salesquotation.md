---
title: Sales quotation report (SalesQuotation)
TOCTitle: Sales quotation report (SalesQuotation)
ms:assetid: 6462d251-635d-4c5a-b641-42985c0d78df
ms:mtpsurl: https://technet.microsoft.com/library/Hh242722(v=AX.60)
ms:contentKeyID: 36058985
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SalesQuotation
---

# Sales quotation report (SalesQuotation) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Sales quotation** report to print the sales quotation business document that contains an offer to sell to a customer or prospect.

## How to filter the data on this report

There are several parameters that can be used to filter the data that is displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

For additional information about how to configure the filters for this report, see [Send quotation (class form)](https://technet.microsoft.com/library/aa589556\(v=ax.60\)).

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
<td><p>SalesQuotation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SalesQuotation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SalesQuotation</p>
<p>SalesQuotationCopy</p>
<p>SalesQuotationOriginal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Common</strong> &gt; <strong>Sales quotations</strong> &gt; <strong>All quotations</strong>. Click <strong>Quote</strong> and then <strong>Quotation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SalesQuotationDetailsTmp table

  - SalesQuotationHeaderTmp table


> [!NOTE]
> <P>To learn where the data in the temp tables comes from, view the cross-references for the SalesQuotationDP.processReport.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


