﻿---
title: NumberSequenceRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: NumberSequenceRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.NumberSequenceRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.numbersequencerequesthandler(v=AX.60)
ms:contentKeyID: 65320607
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.NumberSequenceRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequenceRequestHandler Class

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class NumberSequenceRequestHandler _
    Inherits WorkflowRequestHandler(Of GetNumberSequenceRequest, GetNumberSequenceResponse)
'Usage
Dim instance As NumberSequenceRequestHandler
```

``` csharp
public sealed class NumberSequenceRequestHandler : WorkflowRequestHandler<GetNumberSequenceRequest, GetNumberSequenceResponse>
```

``` c++
public ref class NumberSequenceRequestHandler sealed : public WorkflowRequestHandler<GetNumberSequenceRequest^, GetNumberSequenceResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetNumberSequenceRequest](getnumbersequencerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetNumberSequenceResponse](getnumbersequenceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.NumberSequenceRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)
