---
title: Transaction.ShippingAddress Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShippingAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Transaction.ShippingAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.transaction.shippingaddress(v=AX.60)
ms:contentKeyID: 62203012
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Transaction.ShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# ShippingAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shipping address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingAddress As Address
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As Address

value = instance.ShippingAddress

instance.ShippingAddress = value
```

``` csharp
[DataMemberAttribute]
public Address ShippingAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ ShippingAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

