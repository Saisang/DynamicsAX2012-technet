---
title: SalesTransactionData.ModifiedDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ModifiedDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.ModifiedDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata.modifieddatetime(v=AX.60)
ms:contentKeyID: 62211032
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.ModifiedDateTime
dev_langs:
- CSharp
- C++
- VB
---

# ModifiedDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the last modified date of the sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MODIFIEDDATETIME")> _
<IgnoreDataMemberAttribute> _
<RequiredToBeUtcAttribute(True)> _
Public Property ModifiedDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As SalesTransactionData
Dim value As DateTimeOffset

value = instance.ModifiedDateTime

instance.ModifiedDateTime = value
```

``` csharp
[ColumnAttribute("MODIFIEDDATETIME")]
[IgnoreDataMemberAttribute]
[RequiredToBeUtcAttribute(true)]
public DateTimeOffset ModifiedDateTime { get; set; }
```

``` c++
[ColumnAttribute(L"MODIFIEDDATETIME")]
[IgnoreDataMemberAttribute]
[RequiredToBeUtcAttribute(true)]
public:
property DateTimeOffset ModifiedDateTime {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransactionData Class](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

