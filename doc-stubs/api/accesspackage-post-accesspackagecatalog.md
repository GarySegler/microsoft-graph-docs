---
title: "Add accessPackageCatalog"
description: "Add accessPackageCatalog by posting to the accessPackageCatalog collection."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Add accessPackageCatalog
Namespace: microsoft.graph

Add accessPackageCatalog by posting to the accessPackageCatalog collection.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST /identityGovernance/entitlementManagement/accessPackageCatalogs/$ref
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [accessPackageCatalog](../resources/accesspackagecatalog.md) object.

The following table shows the properties that are required when you create the [accessPackageCatalog](../resources/accesspackagecatalog.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|catalogType|String|**TODO: Add Description**|
|catalogStatus|String|**TODO: Add Description**|
|isExternallyVisible|Boolean|**TODO: Add Description**|
|createdBy|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|modifiedBy|String|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|



## Response

If successful, this method returns a `204 No Content` response code and an [accessPackageCatalog](../resources/accesspackagecatalog.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_accesspackagecatalog_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/accessPackageCatalogs/$ref
Content-Type: application/json
Content-length: 293

{
  "@odata.type": "#Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageCatalog",
  "displayName": "String",
  "description": "String",
  "catalogType": "String",
  "catalogStatus": "String",
  "isExternallyVisible": "Boolean",
  "createdBy": "String",
  "modifiedBy": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageCatalog"
}
-->
``` http
HTTP/1.1 204 No Content

Content-Type: application/json
{
  "@odata.type": "#Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageCatalog",
  "id": "0f10d036-d036-0f10-36d0-100f36d0100f",
  "displayName": "String",
  "description": "String",
  "catalogType": "String",
  "catalogStatus": "String",
  "isExternallyVisible": "Boolean",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)"
}
```
