---
title: ICardInfoV1.Issuer Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Issuer Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.Issuer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.issuer(v=AX.60)
ms:contentKeyID: 47128960
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.Issuer
dev_langs:
- CSharp
- C++
- VB
---

# Issuer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the name of the card issuer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Issuer As String
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As String

value = instance.Issuer

instance.Issuer = value
```

``` csharp
string Issuer { get; set; }
```

``` c++
property String^ Issuer {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

