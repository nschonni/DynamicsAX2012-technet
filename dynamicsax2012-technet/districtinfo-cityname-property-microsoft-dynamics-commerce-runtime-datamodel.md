﻿---
title: DistrictInfo.CityName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CityName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DistrictInfo.CityName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.districtinfo.cityname(v=AX.60)
ms:contentKeyID: 49845740
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DistrictInfo.CityName
dev_langs:
- CSharp
- C++
- VB
---

# CityName Property

Gets or sets the name of the city.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CITYNAME")> _
<DataMemberAttribute> _
Public Property CityName As String
    Get
    Set
'Usage
Dim instance As DistrictInfo
Dim value As String

value = instance.CityName

instance.CityName = value
```

``` csharp
[ColumnAttribute("CITYNAME")]
[DataMemberAttribute]
public string CityName { get; set; }
```

``` c++
[ColumnAttribute(L"CITYNAME")]
[DataMemberAttribute]
public:
property String^ CityName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DistrictInfo Class](districtinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
