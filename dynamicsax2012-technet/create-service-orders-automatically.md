---
title: Create service orders automatically
TOCTitle: Create service orders automatically
ms:assetid: 2451b8f7-f35a-4892-b12c-2d5667cbbb79
ms:mtpsurl: https://technet.microsoft.com/library/Aa496810(v=AX.60)
ms:contentKeyID: 36056187
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create service orders automatically 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create service orders for one service agreement or for several service agreements. When they are created, you can view your service orders in the **Service orders** form.

Service orders are created only for the valid period of the service agreement. If the interval that you specify in the **Create service orders** form is before the starting date or after the ending date of the service agreement, service orders are created only for the part of the interval that is within the service agreement dates.

When you create service orders manually or automatically from the service agreement line, the service order must be in the time interval that is defined by the starting and ending dates for the line, unless you do not specify an ending date on the line.

## Create service orders automatically for a service agreement

1.  Click **Service management** \> **Common** \> **Service agreements** \> **Service agreements**.

2.  Select a service agreement.

3.  Click the **Deliver** tab, and then click **Planned service orders**.

4.  Specify dates in the **From date** and **To date** fields to define the service period.

5.  Select the **Show Infolog** check box to display a list of the service orders that are created.

6.  Select transaction types in the **Include transaction types** field group. The transaction types represent the lines that are created in the service agreement, and each transaction type that you select generates several service orders, depending on the service interval that is specified on the service agreement line.

7.  To create any service orders that are missing from continuous series of service orders, select the **Continuous** check box.

8.  Click **OK**.

## Create service orders automatically for several service agreements

1.  Click **Service management** \> **Periodic** \> **Service orders** \> **Create service orders**.

2.  Click **Select** to make selections to add or remove criteria to use to create service orders.

3.  Click **OK**.

## See also

[About service orders](about-service-orders.md)

[About automatically creating service orders](about-automatically-creating-service-orders.md)

  


