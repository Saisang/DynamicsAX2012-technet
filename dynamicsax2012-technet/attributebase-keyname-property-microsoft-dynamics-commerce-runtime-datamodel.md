---
title: AttributeBase.KeyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.KeyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributebase.keyname(v=AX.60)
ms:contentKeyID: 49826275
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.KeyName
dev_langs:
- CSharp
- C++
- VB
---

# KeyName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the property Key Name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("KEYNAME")> _
Public Property KeyName As String
    Get
    Set
'Usage
Dim instance As AttributeBase
Dim value As String

value = instance.KeyName

instance.KeyName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("KEYNAME")]
public string KeyName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"KEYNAME")]
public:
property String^ KeyName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The property Key Name.  

## See Also

#### Reference

[AttributeBase Class](attributebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

