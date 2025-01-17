---
title: ReasonCode.Prompt Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Prompt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.Prompt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.prompt(v=AX.60)
ms:contentKeyID: 62214188
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.Prompt
dev_langs:
- CSharp
- C++
- VB
---

# Prompt Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the prompt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PROMPT")> _
Public Property Prompt As String
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As String

value = instance.Prompt
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PROMPT")]
public string Prompt { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PROMPT")]
public:
property String^ Prompt {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The prompt.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

