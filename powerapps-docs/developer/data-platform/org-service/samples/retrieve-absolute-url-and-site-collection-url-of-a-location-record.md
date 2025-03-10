---
title: "Sample: Retrieve absolute URL and site collection URL (Microsoft Dataverse) | Microsoft Docs" # Intent and product brand in a unique string of 43-59 chars including spaces
description: "This sample shows how to retrieve the absolute URL and site collection URL of a SharePoint location" # 115-145 characters including spaces. This abstract displays in the search result.
ms.date: 04/03/2022
author: JimDaly #TODO: No Owner
ms.author: jdaly
manager: kvivek
ms.reviewer: pehecke
ms.topic: sample
search.audienceType: 
  - developer
search.app: 
  - PowerApps
  - D365CE
contributors:
 - JimDaly
 - phecke
---
# Sample: Retrieve absolute URL and site collection URL of a location record

This sample shows how to retrieve the absolute URL and the site collection URL of a SharePoint Server location record using the [RetrieveAbsoluteAndSiteCollectionUrlRequest](/dotnet/api/microsoft.crm.sdk.messages.retrieveabsoluteandsitecollectionurlrequest?view=dynamics-general-ce-9) message.

## How to run this sample

[!include[cc-how-to-run-samples](../../includes/cc-how-to-run-samples.md)]

## What this sample does

The `RetrieveAbsoluteAndSiteCollectionUrlRequest` messages is intended to be used in a scenario that contains data that is needed to retrieve the absolute URL nd the site collection URL for a SharePoint location record.

## How this sample works

In order to simulate the scenario described in [What this sample does](#what-this-sample-does), the sample will do the following:

### Setup

1. Checks for the current version of the org. 
1. The `CreateRequireRecords` method creates records that are used by the sample.

### Demonstrate

The `RetrieveAbsoluteAndSiteCollectionUrlRequest` is used to retrieve the absolute URL and site collection URL of the SharePoint record.

### Clean up

Display an option to delete the records created in the [Setup](#setup). The deletion is optional in case you want to examine the tables and data created by the sample. You can manually delete the records to achieve the same result.


[!INCLUDE[footer-include](../../../../includes/footer-banner.md)]
