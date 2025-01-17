---
title: PeriodicDiscount.ValidFromDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidFromDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ValidFromDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.validfromdate(v=AX.60)
ms:contentKeyID: 49854428
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ValidFromDate
dev_langs:
- CSharp
- C++
- VB
---

# ValidFromDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the starting date when this rule becomes active.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VALIDFROM")> _
Public Property ValidFromDate As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As DateTimeOffset

value = instance.ValidFromDate
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VALIDFROM")]
public DateTimeOffset ValidFromDate { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VALIDFROM")]
public:
property DateTimeOffset ValidFromDate {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

