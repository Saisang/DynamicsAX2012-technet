---
title: CommerceRuntime.GetRequestHandler Method (Type, String) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandler Method (Type, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.GetRequestHandler(System.Type,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.getrequesthandler(v=AX.60)
ms:contentKeyID: 65321134
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetRequestHandler Method (Type, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Function GetRequestHandler ( _
    requestType As Type, _
    handlerName As String _
) As IRequestHandler
'Usage
Dim instance As CommerceRuntime
Dim requestType As Type
Dim handlerName As String
Dim returnValue As IRequestHandler

returnValue = instance.GetRequestHandler(requestType, _
    handlerName)
```

``` csharp
public IRequestHandler GetRequestHandler(
    Type requestType,
    string handlerName
)
```

``` c++
public:
virtual IRequestHandler^ GetRequestHandler(
    Type^ requestType, 
    String^ handlerName
) sealed
```

#### Parameters

  - requestType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

<!-- end list -->

  - handlerName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)  

#### Implements

[ICommerceRuntime.GetRequestHandler(Type, String)](icommerceruntime-getrequesthandler-method-type-string-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[GetRequestHandler Overload](commerceruntime-getrequesthandler-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

