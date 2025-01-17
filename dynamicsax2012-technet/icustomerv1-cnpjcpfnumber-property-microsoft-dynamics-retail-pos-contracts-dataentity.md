---
title: ICustomerV1.CNPJCPFNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CNPJCPFNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.CNPJCPFNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.cnpjcpfnumber(v=AX.60)
ms:contentKeyID: 47129059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.CNPJCPFNumber
dev_langs:
- CSharp
- C++
- VB
---

# CNPJCPFNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the CNPJ/CPF number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CNPJCPFNumber As String
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As String

value = instance.CNPJCPFNumber

instance.CNPJCPFNumber = value
```

``` csharp
string CNPJCPFNumber { get; set; }
```

``` c++
property String^ CNPJCPFNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## Remarks

This is a Brazil-specific tax ID field.

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

