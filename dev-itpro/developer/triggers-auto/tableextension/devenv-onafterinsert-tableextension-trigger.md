---
title: "OnAfterInsert (Table Extension) Trigger"
description: "Runs when a user inserts a new record into the table."
ms.author: solsen
ms.date: 08/15/2024
ms.topic: reference
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)

# OnAfterInsert (Table Extension) Trigger
> **Version**: _Available or changed with runtime version 1.0._

Runs when a user inserts a new record into the table.


## Syntax
```AL
trigger OnAfterInsert()
begin
    ...
end;
```



[//]: # (IMPORTANT: END>DO_NOT_EDIT)

## Remarks  
 This trigger is run after default insert behavior, which checks that the record to be inserted does not already exist before the insertion occurs. It runs automatically after the user chooses to insert a new record in a page from the Web Client. The new record is not inserted if an error occurs in the trigger code.  

## See Also  
[Get Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)  
