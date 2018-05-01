---
title: "EventType"
 
 
manager: sethgros
ms.date: 9/17/2015
ms.audience: Developer
ms.topic: reference
 
localization_priority: Normal
api_name:
- EventType
api_type:
- schema
ms.assetid: 04b70f9e-c226-4130-958e-0db0275cf58b
description: "The EventType element is used to create a subscription and identifies an event type to be reported in a notification."
---

# EventType

The **EventType** element is used to create a subscription and identifies an event type to be reported in a notification. 
  
```
<EventType/>
```

 **NotificationEventTypeType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
#### Attributes

None.
  
#### Child elements

None.
  
#### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[EventTypes](eventtypes.md) <br/> |Contains a collection of event notification event types that are used to create a subscription.  <br/> |
   
## Text value

A text value is required. The following are the possible values:
  
- CopiedEvent
    
- CreatedEvent
    
- DeletedEvent
    
- ModifiedEvent
    
- MovedEvent
    
- NewMailEvent
    
- FreeBusyChangedEvent
    
## Remarks

The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema Name  <br/> |Types schema  <br/> |
|Validation File  <br/> |Types.xsd  <br/> |
|Can be Empty  <br/> |False  <br/> |
   
## See also

#### Reference

[Subscribe operation](subscribe-operation.md)
  
[GetEvents operation](getevents-operation.md)
  
[Unsubscribe operation](unsubscribe-operation.md)
