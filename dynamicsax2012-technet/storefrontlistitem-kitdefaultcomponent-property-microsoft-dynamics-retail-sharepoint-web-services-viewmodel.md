---
title: StorefrontListItem.KitDefaultComponent Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: KitDefaultComponent Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.KitDefaultComponent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storefrontlistitem.kitdefaultcomponent(v=AX.60)
ms:contentKeyID: 62204824
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.KitDefaultComponent
dev_langs:
- CSharp
- C++
- VB
---

# KitDefaultComponent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the identifiers of the kit masters that contain the item as a default component.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitDefaultComponent As String
    Get
    Set
'Usage
Dim instance As StorefrontListItem
Dim value As String

value = instance.KitDefaultComponent

instance.KitDefaultComponent = value
```

``` csharp
[DataMemberAttribute]
public string KitDefaultComponent { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ KitDefaultComponent {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StorefrontListItem Class](storefrontlistitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

