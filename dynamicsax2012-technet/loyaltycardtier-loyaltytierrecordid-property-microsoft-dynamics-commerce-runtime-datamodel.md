---
title: LoyaltyCardTier.LoyaltyTierRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyTierRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTier.LoyaltyTierRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtier.loyaltytierrecordid(v=AX.60)
ms:contentKeyID: 62205290
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTier.LoyaltyTierRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTierRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the record identifier of the loyalty tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LOYALTYTIER")> _
Public Property LoyaltyTierRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTier
Dim value As Long

value = instance.LoyaltyTierRecordId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LOYALTYTIER")]
public long LoyaltyTierRecordId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LOYALTYTIER")]
public:
property long long LoyaltyTierRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTier Class](loyaltycardtier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

