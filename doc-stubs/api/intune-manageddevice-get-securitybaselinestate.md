---
title: "Get securityBaselineStates"
description: "Read the properties and relationships of a securityBaselineState object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get securityBaselineStates
Namespace: microsoft.graph

Read the properties and relationships of a [securityBaselineState](../resources/intune-securitybaselinestate.md) object.

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
GET /users/{usersId}/managedDevices/{managedDeviceId}/securityBaselineStates
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [securityBaselineState](../resources/intune-securitybaselinestate.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_securitybaselinestate"
}
-->
``` http
GET https://graph.microsoft.com/beta/users/{usersId}/managedDevices/{managedDeviceId}/securityBaselineStates
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.securityBaselineState"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": {
    "@odata.type": "#microsoft.graph.securityBaselineState",
    "id": "0eaaeac2-eac2-0eaa-c2ea-aa0ec2eaaa0e",
    "securityBaselineTemplateId": "String",
    "userPrincipalName": "String",
    "displayName": "String",
    "state": "String"
  }
}
```
