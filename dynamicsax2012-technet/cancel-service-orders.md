---
title: Cancel service orders
TOCTitle: Cancel service orders
ms:assetid: 30cb05ee-7e05-4245-8a0e-688d62cc69c6
ms:mtpsurl: https://technet.microsoft.com/library/Aa570041(v=AX.60)
ms:contentKeyID: 36056318
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Cancel service orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can cancel a service order or service order line from the service order itself, or you can cancel multiple service orders by running a periodic job.


> [!NOTE]
> <P>Service orders cannot be canceled if the stage of the service order does not allow cancelation, if the service order has item requirements, or if the service order has already been posted.</P>



## Cancel a service order in the Service orders form

1.  Click **Service management** \> **Common** \> **Service orders** \> **Service orders**. Select the service order, and on the Action Pane, click **Cancel order**.

## Cancel a service order line

1.  Click **Service management** \> **Common** \> **Service orders** \> **Service orders**. Double-click the service order that contains the line you want to cancel.

2.  Select the service order line that you want to cancel, and then click **Cancel order line** to change the status of the line to **Canceled**.


> [!TIP]
> <P>To reverse the cancellation of a service order line and change the status back to <STRONG>Created</STRONG>, click <STRONG>Revoke cancel</STRONG>.</P>



## Cancel multiple service orders

1.  Click **Service management** \> **Periodic** \> **Service orders** \> **Cancel service orders**.

2.  Click the **Select** button.

3.  In the **Inquiry** form, in the **Criteria** column, select the service orders that you want to cancel.

4.  Click **OK** to close the **Inquiry** form.

5.  Select the **Show Infolog** check box to generate an Infolog that lists the canceled service orders.

6.  Select the **Revoke cancel** check box if you want to reverse the **Canceled** status of a service order.

7.  Click **OK**.

The selected service orders are either canceled or their progress status of **Canceled** has been reversed to **In process**.


> [!NOTE]
> <P>If you select the <STRONG>Revoke cancel</STRONG> check box, service orders with a progress status of <STRONG>Canceled</STRONG> are reversed and service orders with a progress status of <STRONG>In process</STRONG> are not canceled.</P>


  


