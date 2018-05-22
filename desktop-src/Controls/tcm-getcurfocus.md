---
title: TCM\_GETCURFOCUS message
description: Returns the index of the item that has the focus in a tab control. You can send this message explicitly or by using the TabCtrl\_GetCurFocus macro.
ms.assetid: 'ae6ee159-c769-41d6-b0bb-2a9ade4c0e71'
keywords: ["TCM_GETCURFOCUS message Windows Controls"]
topic_type:
- apiref
api_name:
- TCM_GETCURFOCUS
api_location:
- Commctrl.h
api_type:
- HeaderDef
---

# TCM\_GETCURFOCUS message

Returns the index of the item that has the focus in a tab control. You can send this message explicitly or by using the [**TabCtrl\_GetCurFocus**](tabctrl-getcurfocus.md) macro.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>Must be zero.</dd> <dt>

*lParam* 
</dt> <dd>Must be zero.</dd> </dl>

## Return value

Returns the index of the tab item that has the focus.

## Remarks

The item that has the focus may be different than the selected item.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



�

�




