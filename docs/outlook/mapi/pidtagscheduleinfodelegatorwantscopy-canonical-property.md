---
title: "PidTagScheduleInfoDelegatorWantsCopy Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- MAPI.PidTagScheduleInfoDelegatorWantsCopy
api_type:
- COM
ms.assetid: 48e48e3a-1186-46c4-8ff9-34e03905fb93
description: "Contains TRUE if the delegator wants to receive copies of the meeting-related objects that are sent to the delegate."
---

# PidTagScheduleInfoDelegatorWantsCopy Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains TRUE if the delegator wants to receive copies of the meeting-related objects that are sent to the delegate.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_SCHDINFO_BOSS_WANTS_COPY  <br/> |
|Identifier:  <br/> |0x6842  <br/> |
|Data type:  <br/> |PT_BOOLEAN  <br/> |
|Area:  <br/> |Free/Busy  <br/> |
   
## Remarks

This property must be set in the delegate information object.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides references to related Exchange Server protocol specifications.
    
[[MS-OXODLGT]](https://msdn.microsoft.com/library/01a89b11-9c43-4c40-b147-8f6a1ef5a44f%28Office.15%29.aspx)
  
> Specifies methods for connecting to and configuring mailboxes as delegates, and interactions with message and calendar objects when they act on behalf of another user.
    
[[MS-OXOPFFB]](https://msdn.microsoft.com/library/1a527299-7211-4d27-a74c-b69bd0746320%28Office.15%29.aspx)
  
> Publishes the availability of a user or resource.
    
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

