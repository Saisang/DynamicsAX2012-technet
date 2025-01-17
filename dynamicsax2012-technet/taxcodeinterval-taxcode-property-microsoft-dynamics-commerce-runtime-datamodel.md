---
title: TaxCodeInterval.TaxCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxcode(v=AX.60)
ms:contentKeyID: 62201849
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxCode
dev_langs:
- CSharp
- C++
- VB
---

# TaxCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXCODE")> _
<DataMemberAttribute> _
Public Property TaxCode As String
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As String

value = instance.TaxCode
```

``` csharp
[ColumnAttribute("TAXCODE")]
[DataMemberAttribute]
public string TaxCode { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXCODE")]
[DataMemberAttribute]
public:
property String^ TaxCode {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

