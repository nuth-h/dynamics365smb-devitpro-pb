---
title: "Text.Split([Text,...]) Method"
description: "Splits a string into a maximum number of substrings based on a collection of separators."
ms.author: solsen
ms.date: 05/14/2024
ms.topic: reference
author: SusanneWindfeldPedersen
ms.reviewer: solsen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# Text.Split([Text,...]) Method
> **Version**: _Available or changed with runtime version 1.0._

Splits a string into a maximum number of substrings based on a collection of separators.


## Syntax
```AL
Result :=   Text.Split([Separators: Text,...])
```
> [!NOTE]
> This method can be invoked without specifying the data type name.
## Parameters
*Text*  
&emsp;Type: [Text](text-data-type.md)  
An instance of the [Text](text-data-type.md) data type.  

*[Optional] Separators*  
&emsp;Type: [Text](text-data-type.md)  
A collection of separators that delimit the substrings in this string.  


## Return Value
*Result*  
&emsp;Type: [List of [Text]](../list/list-data-type.md)  
The collection of substrings from the original string based on the collection of separators.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## Remarks
If no separators are specified, the text is split at white-space characters.

## See Also
[Text Data Type](text-data-type.md)  
[Get Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)
