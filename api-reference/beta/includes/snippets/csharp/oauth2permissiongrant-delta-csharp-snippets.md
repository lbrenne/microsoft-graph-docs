---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var delta = await graphClient.Oauth2permissiongrants
	.Delta()
	.Request()
	.GetAsync();

```