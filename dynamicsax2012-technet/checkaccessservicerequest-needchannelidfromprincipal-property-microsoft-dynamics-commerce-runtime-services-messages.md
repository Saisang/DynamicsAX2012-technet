---
title: CheckAccessServiceRequest.NeedChannelIdFromPrincipal Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NeedChannelIdFromPrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.NeedChannelIdFromPrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.checkaccessservicerequest.needchannelidfromprincipal(v=AX.60)
ms:contentKeyID: 65320699
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.NeedChannelIdFromPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# NeedChannelIdFromPrincipal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This member overrides [Request.NeedChannelIdFromPrincipal](request-needchannelidfromprincipal-property-microsoft-dynamics-commerce-runtime-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overrides ReadOnly Property NeedChannelIdFromPrincipal As Boolean
    Get
'Usage
Dim instance As CheckAccessServiceRequest
Dim value As Boolean

value = instance.NeedChannelIdFromPrincipal
```

``` csharp
[IgnoreDataMemberAttribute]
public override bool NeedChannelIdFromPrincipal { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property bool NeedChannelIdFromPrincipal {
    bool get () override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CheckAccessServiceRequest Class](checkaccessservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

