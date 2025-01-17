---
title: OrderManager.UpdateReasonCodeLineOnCartLine Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateReasonCodeLineOnCartLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateReasonCodeLineOnCartLine(System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.updatereasoncodelineoncartline(v=AX.60)
ms:contentKeyID: 62213434
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateReasonCodeLineOnCartLine
dev_langs:
- CSharp
- C++
- VB
---

# UpdateReasonCodeLineOnCartLine Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the reason code line on cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateReasonCodeLineOnCartLine ( _
    cartId As String, _
    customerAccountNumber As String, _
    cartLineId As String, _
    reasonCodeLine As ReasonCodeLine _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim customerAccountNumber As String
Dim cartLineId As String
Dim reasonCodeLine As ReasonCodeLine
Dim returnValue As Cart

returnValue = instance.UpdateReasonCodeLineOnCartLine(cartId, _
    customerAccountNumber, cartLineId, _
    reasonCodeLine)
```

``` csharp
public Cart UpdateReasonCodeLineOnCartLine(
    string cartId,
    string customerAccountNumber,
    string cartLineId,
    ReasonCodeLine reasonCodeLine
)
```

``` c++
public:
Cart^ UpdateReasonCodeLineOnCartLine(
    String^ cartId, 
    String^ customerAccountNumber, 
    String^ cartLineId, 
    ReasonCodeLine^ reasonCodeLine
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartLineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reasonCodeLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

