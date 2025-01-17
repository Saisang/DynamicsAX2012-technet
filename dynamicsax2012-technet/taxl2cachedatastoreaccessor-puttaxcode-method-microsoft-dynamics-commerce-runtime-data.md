---
title: TaxL2CacheDataStoreAccessor.PutTaxCode Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTaxCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxCode(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeUnit)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.puttaxcode(v=AX.60)
ms:contentKeyID: 62213261
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxCode
dev_langs:
- CSharp
- C++
- VB
---

# PutTaxCode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutTaxCode ( _
    taxCode As String, _
    columns As ColumnSet, _
    result As TaxCodeUnit _
)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim taxCode As String
Dim columns As ColumnSet
Dim result As TaxCodeUnit

instance.PutTaxCode(taxCode, columns, _
    result)
```

``` csharp
public void PutTaxCode(
    string taxCode,
    ColumnSet columns,
    TaxCodeUnit result
)
```

``` c++
public:
virtual void PutTaxCode(
    String^ taxCode, 
    ColumnSet^ columns, 
    TaxCodeUnit^ result
) sealed
```

#### Parameters

  - taxCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeUnit](taxcodeunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[ICachedTaxDataManager.PutTaxCode(String, ColumnSet, TaxCodeUnit)](icachedtaxdatamanager-puttaxcode-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

