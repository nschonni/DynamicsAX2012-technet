﻿---
title: TillLayout.TotalsLayoutXml Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalsLayoutXml Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.TotalsLayoutXml
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.totalslayoutxml(v=AX.60)
ms:contentKeyID: 62213330
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.TotalsLayoutXml
dev_langs:
- CSharp
- C++
- VB
---

# TotalsLayoutXml Property

Gets or sets the value of name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TOTALSLAYOUTXML")> _
Public Property TotalsLayoutXml As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.TotalsLayoutXml

instance.TotalsLayoutXml = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TOTALSLAYOUTXML")]
public string TotalsLayoutXml { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TOTALSLAYOUTXML")]
public:
property String^ TotalsLayoutXml {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The totals layout xml.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
