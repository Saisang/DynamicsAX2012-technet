---
title: GetPromotionsResponse.Cart Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Cart Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetPromotionsResponse.Cart
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getpromotionsresponse.cart(v=AX.60)
ms:contentKeyID: 62214033
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetPromotionsResponse.Cart
dev_langs:
- CSharp
- C++
- VB
---

# Cart Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the shopping cart updated with promotions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Cart As Cart
    Get
    Private Set
'Usage
Dim instance As GetPromotionsResponse
Dim value As Cart

value = instance.Cart
```

``` csharp
[DataMemberAttribute]
public Cart Cart { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Cart^ Cart {
    Cart^ get ();
    private: void set (Cart^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetPromotionsResponse Class](getpromotionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

