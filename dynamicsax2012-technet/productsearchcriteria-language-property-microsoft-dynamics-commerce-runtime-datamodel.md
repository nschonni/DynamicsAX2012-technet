﻿---
title: ProductSearchCriteria.Language Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Language Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.Language
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.language(v=AX.60)
ms:contentKeyID: 62209611
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.Language
dev_langs:
- CSharp
- C++
- VB
---

# Language Property

Gets or sets the language key for the product search.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Language As String
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As String

value = instance.Language

instance.Language = value
```

``` csharp
[DataMemberAttribute]
public string Language { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Language {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Observations: - This criteria will be ignored for searches with a specified data level less than Standard.

\- If set, the query will return only translations for this language.

\- If invalid/unknown, the query will return the default language translations.

\- If not set, the query will return all existing translations.

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
