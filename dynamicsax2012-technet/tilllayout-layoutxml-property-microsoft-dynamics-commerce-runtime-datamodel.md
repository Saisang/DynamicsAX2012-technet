---
title: TillLayout.LayoutXml Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LayoutXml Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.LayoutXml
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.layoutxml(v=AX.60)
ms:contentKeyID: 62215166
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.LayoutXml
dev_langs:
- CSharp
- C++
- VB
---

# LayoutXml Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of layout xml.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LAYOUTXML")> _
<DataMemberAttribute> _
Public Property LayoutXml As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.LayoutXml

instance.LayoutXml = value
```

``` csharp
[ColumnAttribute("LAYOUTXML")]
[DataMemberAttribute]
public string LayoutXml { get; set; }
```

``` c++
[ColumnAttribute(L"LAYOUTXML")]
[DataMemberAttribute]
public:
property String^ LayoutXml {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The layout xml.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

