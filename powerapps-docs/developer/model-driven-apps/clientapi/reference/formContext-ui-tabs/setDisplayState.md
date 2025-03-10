---
title: "tab.setDisplayState (Client API reference) in model-driven apps| MicrosoftDocs"
description: Includes description and supported parameters for the tab.setDisplayState method.
ms.author: jdaly
author: adrianorth
manager: kvivek
ms.date: 03/12/2022
ms.reviewer: jdaly
ms.topic: "reference"
applies_to: "Dynamics 365 (online)"
search.audienceType: 
  - developer
search.app: 
  - PowerApps
  - D365CE
contributors:
  - JimDaly
---
# tab.setDisplayState (Client API reference)

> [!IMPORTANT]
> The setDisplayState method will be deprecated with the 2021 release wave 1 (April 2021). Use the [setFocus](setfocus.md) method in Unified Interface to ensure the correct tab is opened on a form.

[!INCLUDE[./includes/setDisplayState-description.md](./includes/setDisplayState-description.md)]

## Syntax

`tabObj.setDisplayState(state);`

## Parameter

|Name|Type|Required|Description|
|--|--|--|--|
|state|String|Yes|Specify "expanded" or "collapsed".|

### Related topics

[getDisplayState](getDisplayState.md)





[!INCLUDE[footer-include](../../../../../includes/footer-banner.md)]