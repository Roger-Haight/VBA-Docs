---
title: WebBrowserControl.Height property (Access)
keywords: vbaac10.chm14373
f1_keywords:
- vbaac10.chm14373
ms.prod: access
api_name:
- Access.WebBrowserControl.Height
ms.assetid: 8f4223ac-fefa-3ac6-a84e-9cd776bc56d6
ms.date: 06/08/2017
localization_priority: Normal
---


# WebBrowserControl.Height property (Access)

Gets or sets the height of the specified object in twips. Read/write  **Integer**.


## Syntax

_expression_.**Height**

_expression_ A variable that represents a **[WebBrowserControl](Access.WebBrowserControl.md)** object.


## Remarks

For report controls, you can set the  **Height** property when you print or preview a report only by using a macro or an event procedure specified in a section's **OnFormat** event property setting.

Microsoft Access automatically sets the  **Height** property when you create or size a control or when you size a window in form Design View or report Design view.

The height of controls is measured from the center of their borders so controls with different border widths align correctly. 


## See also


[WebBrowserControl Object](Access.WebBrowserControl.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]