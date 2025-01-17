---
title: UserResetPasswordRequest.ExtraData Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ExtraData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest.ExtraData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userresetpasswordrequest.extradata(v=AX.60)
ms:contentKeyID: 62214638
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest.ExtraData
dev_langs:
- CSharp
- C++
- VB
---

# ExtraData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Extra Data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExtraData As String
    Get
    Set
'Usage
Dim instance As UserResetPasswordRequest
Dim value As String

value = instance.ExtraData

instance.ExtraData = value
```

``` csharp
[DataMemberAttribute]
public string ExtraData { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ExtraData {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Extra Data.  

## See Also

#### Reference

[UserResetPasswordRequest Class](userresetpasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

