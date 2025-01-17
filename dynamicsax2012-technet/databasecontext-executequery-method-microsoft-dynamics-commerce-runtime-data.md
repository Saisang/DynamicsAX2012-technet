---
title: DatabaseContext.ExecuteQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ExecuteQuery(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasecontext.executequery(v=AX.60)
ms:contentKeyID: 65322121
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ExecuteQuery
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteQuery Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes a SQL query.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Function ExecuteQuery ( _
    query As IDatabaseQuery _
) As IDatabaseResult
'Usage
Dim instance As DatabaseContext
Dim query As IDatabaseQuery
Dim returnValue As IDatabaseResult

returnValue = instance.ExecuteQuery(query)
```

``` csharp
public IDatabaseResult ExecuteQuery(
    IDatabaseQuery query
)
```

``` c++
public:
IDatabaseResult^ ExecuteQuery(
    IDatabaseQuery^ query
)
```

#### Parameters

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery](idatabasequery-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)  
The associated database result.  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

