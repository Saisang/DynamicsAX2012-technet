---
title: GetRoundQuantityServiceRequest.UnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundQuantityServiceRequest.UnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundquantityservicerequest.unitofmeasure(v=AX.60)
ms:contentKeyID: 62203988
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundQuantityServiceRequest.UnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasure Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the unit of measure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitOfMeasure As String
    Get
    Private Set
'Usage
Dim instance As GetRoundQuantityServiceRequest
Dim value As String

value = instance.UnitOfMeasure
```

``` csharp
[DataMemberAttribute]
public string UnitOfMeasure { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UnitOfMeasure {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetRoundQuantityServiceRequest Class](getroundquantityservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

