﻿---
title: SalesLine.DiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.DiscountAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.discountamount(v=AX.60)
ms:contentKeyID: 49820208
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.DiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# DiscountAmount Property

Gets or sets the discount amount on this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property DiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.DiscountAmount

instance.DiscountAmount = value
```

``` csharp
[ColumnAttribute("DISCOUNTAMOUNT")]
[DataMemberAttribute]
public decimal DiscountAmount { get; set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Decimal DiscountAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
