---
title: IAddressV4.CityDescription Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CityDescription Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV4.CityDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv4.citydescription(v=AX.60)
ms:contentKeyID: 62203126
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV4.CityDescription
dev_langs:
- CSharp
- C++
- VB
---

# CityDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Description of city (Russia)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CityDescription As String
    Get
    Set
'Usage
Dim instance As IAddressV4
Dim value As String

value = instance.CityDescription

instance.CityDescription = value
```

``` csharp
string CityDescription { get; set; }
```

``` c++
property String^ CityDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IAddressV4 Interface](iaddressv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

