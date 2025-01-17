---
title: Listing.IsKitVariant Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: IsKitVariant Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing.IsKitVariant
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listing.iskitvariant(v=AX.60)
ms:contentKeyID: 62204299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing.IsKitVariant
dev_langs:
- CSharp
- C++
- VB
---

# IsKitVariant Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether this listing is a kit.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsKitVariant As Boolean
    Get
    Set
'Usage
Dim instance As Listing
Dim value As Boolean

value = instance.IsKitVariant

instance.IsKitVariant = value
```

``` csharp
[DataMemberAttribute]
public bool IsKitVariant { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsKitVariant {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

