---
title: "MAPIReallocateBuffer"
description: "MAPIReallocateBuffer reallocates a memory buffer, and it is used with the MAPIAllocateBuffer function."
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
ms.assetid: 182ab0c6-c9d3-4cc8-892f-f6b09312ceb9
---

# MAPIReallocateBuffer

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Reallocates a memory buffer. It is used with the [MAPIAllocateBuffer](mapiallocatebuffer.md) function. 
  
|Property|Value|
|:-----|:-----|
|Header file:  <br/> |omapix.h  <br/> |
|Called by:  <br/> |Client applications and service providers  <br/> |
   
```cpp
STDMETHODIMP_(SCODE) MAPIReallocateBuffer
(
LPVOID lpv, 
ULONG ulSize, 
LPVOID * lppv
);
```

## Parameters

 _lpv_
  
> A pointer to the memory to be reallocated.
    
 _ulSize_
  
> The size, in bytes, of the buffer to be allocated.
    
 _lppv_
  
> A pointer to the returned allocated buffer.
    
## Remarks

 **MAPIReallocateBuffer** allocates a new block of memory of the requested size and copies the contents of the buffer that is passed into this new block of memory. If the block of memory that is passed contains internal pointers, the pointers do not change to match the new location. 
  
## See also



[MAPIAllocateBuffer](mapiallocatebuffer.md)

