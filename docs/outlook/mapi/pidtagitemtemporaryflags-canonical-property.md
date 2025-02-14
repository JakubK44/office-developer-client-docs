---
title: "PidTagItemTemporaryflags Canonical Property"
description: Outlines the PidTagItemTemporaryflags canonical property, which contains a flag that indicates that a message has been read, but not marked as read.
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidTagItemTemporaryflags
api_type:
- HeaderDef
ms.assetid: 8066de8e-2b77-4bac-8df3-e64b03ee42b9
---

# PidTagItemTemporaryflags Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains a flag that indicates that a message has been read, but not marked as read.
  
|Property|Value|
|:-----|:-----|
|Associated properties:  <br/> |PR_ITEM_TMPFLAGS  <br/> |
|Identifier:  <br/> |0x1097  <br/> |
|Data type:  <br/> |PT_LONG  <br/> |
|Area:  <br/> |General messaging  <br/> |
   
## Remarks

This property is used in Outlook's Unread Messages search folder to keep track of which messages have been read without actually marking them as read, which would remove them from the folder. When the view changes this property is removed and the item is marked as read. This property will not synchronize to the Exchange Server.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides references to related Exchange Server protocol specifications.
    
[[MS-OXCFOLD]](https://msdn.microsoft.com/library/c0f31b95-c07f-486c-98d9-535ed9705fbf%28Office.15%29.aspx)
  
> Handles folder operations.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
Mapitags.h
  
> Contains definitions of properties listed as alternate names.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

