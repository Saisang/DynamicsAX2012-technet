---
title: AttributeBase.NameTranslations Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NameTranslations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.NameTranslations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributebase.nametranslations(v=AX.60)
ms:contentKeyID: 49847428
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.NameTranslations
dev_langs:
- CSharp
- C++
- VB
---

# NameTranslations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a collection of attribute name translations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NameTranslations As ReadOnlyCollection(Of TextValueTranslation)
    Get
    Set
'Usage
Dim instance As AttributeBase
Dim value As ReadOnlyCollection(Of TextValueTranslation)

value = instance.NameTranslations

instance.NameTranslations = value
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TextValueTranslation> NameTranslations { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<TextValueTranslation^>^ NameTranslations {
    ReadOnlyCollection<TextValueTranslation^>^ get ();
    void set (ReadOnlyCollection<TextValueTranslation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TextValueTranslation](textvaluetranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[AttributeBase Class](attributebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

