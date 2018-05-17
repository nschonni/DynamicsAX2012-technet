﻿---
title: ITaxCodeV1.Calculate Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects)
TOCTitle: Calculate Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.Calculate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businessobjects.itaxcodev1.calculate(v=AX.60)
ms:contentKeyID: 47128497
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.Calculate
dev_langs:
- CSharp
- C++
- VB
---

# Calculate Method

Calculates the tax amount for the tax code.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Calculate As Decimal
'Usage
Dim instance As ITaxCodeV1
Dim returnValue As Decimal

returnValue = instance.Calculate()
```

``` csharp
decimal Calculate()
```

``` c++
Decimal Calculate()
```

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The amount of tax in the transaction's currency.  

## See Also

#### Reference

[ITaxCodeV1 Interface](itaxcodev1-interface-microsoft-dynamics-retail-pos-contracts-businessobjects.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects Namespace](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)
