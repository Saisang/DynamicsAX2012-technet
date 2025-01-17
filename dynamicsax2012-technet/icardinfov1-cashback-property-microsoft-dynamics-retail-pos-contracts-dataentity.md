---
title: ICardInfoV1.CashBack Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CashBack Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.CashBack
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.cashback(v=AX.60)
ms:contentKeyID: 47128407
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.CashBack
dev_langs:
- CSharp
- C++
- VB
---

# CashBack Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The cash back amount associated with the transaction for a debit card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CashBack As Decimal
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As Decimal

value = instance.CashBack

instance.CashBack = value
```

``` csharp
decimal CashBack { get; set; }
```

``` c++
property Decimal CashBack {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

