---
author: eliotcowley
title: IMLOperatorKernelCreationContext.GetOutputEdgeDescription method
description: Gets the description of the specified output edge of the operator.
ms.author: elcowle
ms.date: 4/1/2019
ms.topic: article
keywords: windows 10, windows machine learning, WinML, custom operators, GetOutputEdgeDescription
ms.localizationpriority: medium
topic_type:
- APIRef
api_type:
- NA
api_name:
- IMLOperatorKernelCreationContext.GetOutputEdgeDescription
api_location:
- MLOperatorAuthor.h
---

# IMLOperatorKernelCreationContext.GetOutputEdgeDescription method

Gets the description of the specified output edge of the operator.

```cpp
void GetOutputEdgeDescription(
    uint32_t outputIndex, 
    _Out_ MLOperatorEdgeDescription* edgeDescription)
```

## Requirements

| | |
|-|-|
| **Minimum supported client** | Windows 10, build 17763 |
| **Minimum supported server** | Windows Server 2019 with Desktop Experience |
| **Header** | MLOperatorAuthor.h |

[!INCLUDE [help](../../includes/get-help.md)]
