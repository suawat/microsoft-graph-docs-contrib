---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

var graphClient = new GraphServiceClient(requestAdapter);

var requestBody = new Microsoft.Graph.Users.Item.Authentication.Methods.Item.ResetPassword.ResetPasswordPostRequestBody
{
};
var result = await graphClient.Users["{user-id}"].Authentication.Methods["{authenticationMethod-id}"].ResetPassword.PostAsync(requestBody);


```