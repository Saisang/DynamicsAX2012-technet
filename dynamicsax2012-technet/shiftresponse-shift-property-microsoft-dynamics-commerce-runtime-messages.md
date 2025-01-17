---
title: ShiftResponse.Shift Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Shift Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftResponse.Shift
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.shiftresponse.shift(v=AX.60)
ms:contentKeyID: 62210029
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftResponse.Shift
dev_langs:
- CSharp
- C++
- VB
---

# Shift Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shift details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Shift As Shift
    Get
    Protected Set
'Usage
Dim instance As ShiftResponse
Dim value As Shift

value = instance.Shift

instance.Shift = value
```

``` csharp
[DataMemberAttribute]
public Shift Shift { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property Shift^ Shift {
    Shift^ get ();
    protected: void set (Shift^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ShiftResponse Class](shiftresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

