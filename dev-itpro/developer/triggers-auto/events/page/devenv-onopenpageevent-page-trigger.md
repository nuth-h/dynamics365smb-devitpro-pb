---
title: "OnOpenPageEvent (Page) Trigger Event"
description: "Executed after the OnOpenPage trigger, which is called after a page is initialized and run."
ms.author: solsen
ms.date: 08/15/2024
ms.topic: reference
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)

# OnOpenPageEvent (Page) Trigger Event
> **Version**: _Available or changed with runtime version 1.0._

Executed after the OnOpenPage trigger, which is called after a page is initialized and run.


## Syntax
```AL
[EventSubscriber(ObjectType::Page, Page::<Page Name>, 'OnOpenPageEvent', '', <SkipOnMissingLicense>, <SkipOnMissingPermission>)]
local procedure MyProcedure(var Rec: Record)
begin
    ...
end;
```

### Parameters

*Rec*  
&emsp;Type: [Record](../../../methods-auto/record/record-data-type.md)  
The table that raises the event.  



[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also  
[Get Started with AL](../../../devenv-get-started.md)  
[Developing Extensions](../../../devenv-dev-overview.md)   