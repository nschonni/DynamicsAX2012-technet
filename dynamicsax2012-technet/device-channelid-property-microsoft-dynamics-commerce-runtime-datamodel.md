﻿---
title: Device.ChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.ChannelId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.device.channelid(v=AX.60)
ms:contentKeyID: 62205141
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.ChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelId Property

Gets or sets the associated channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANNELID")> _
<RequiredAttribute> _
Public Property ChannelId As Long
    Get
    Set
'Usage
Dim instance As Device
Dim value As Long

value = instance.ChannelId

instance.ChannelId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANNELID")]
[RequiredAttribute]
public long ChannelId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANNELID")]
[RequiredAttribute]
public:
property long long ChannelId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The channel identifier.  

## See Also

#### Reference

[Device Class](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
