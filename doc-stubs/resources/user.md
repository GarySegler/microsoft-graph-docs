---
title: "user resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# user resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [directoryObject](../resources/directoryobject.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List createdByUser](../api/site-list-createdbyuser.md)|[user](../resources/user.md) collection|Get the user resources from the createdByUser navigation property.|
|[Add createdByUser](../api/site-post-createdbyuser.md)|[user](../resources/user.md)|Add createdByUser by posting to the createdByUser collection.|
|[Remove createdByUser](../api/site-delete-createdbyuser.md)|None|Remove a [user](../resources/user.md) object.|
|[List users](../api/user-list.md)|[user](../resources/user.md) collection|Get a list of the [user](../resources/user.md) objects and their properties.|
|[Create user](../api/user-create.md)|[user](../resources/user.md)|Create a new [user](../resources/user.md) object.|
|[Get user](../api/user-get.md)|[user](../resources/user.md)|Read the properties and relationships of a [user](../resources/user.md) object.|
|[Update user](../api/user-update.md)|[user](../resources/user.md)|Update the properties of a [user](../resources/user.md) object.|
|[Delete user](../api/user-delete.md)|None|Deletes a [user](../resources/user.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md)|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.user",
  "baseType": "Microsoft.IGAELM.PDS.FrontEnd.ExternalModel.directoryObject",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.user",
  "id": "String (identifier)"
}
```
