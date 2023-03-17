# WhatWasIDoingMicrosoftGraph

This is an entry for Hack Together: Microsoft Graph and .NET found at: https://github.com/microsoft/hack-together

Blazor, .NET 7, MudBlazor, and Graph API SDK was used in the creation of this project.

The premise of the app is to refresh your memory of what you were doing in Microsoft apps.

**APP WILL NOT WORK IF YOU DON'T CONFIGURE IT WITH YOUR DETAILS**

To run this app clone the repo, then fill in your details in the appsettings.json file:
```
 "AzureAd": {
    "Instance": "https://login.microsoftonline.com/",
    "Domain": "<your domain>",
    "TenantId": "<your tenant id>",
    "ClientId": "<your client id>",
    "ClientSecret": "<your client secret>",
    "ClientCertificates": [
    ],
    "CallbackPath": "/signin-oidc"
  }
```
![image](https://user-images.githubusercontent.com/22691956/225529437-4ca394a0-23ca-4265-85ca-37778cc58f07.png)


[![Hack Together: Microsoft Graph and .NET](https://img.shields.io/badge/Microsoft%20-Hack--Together-orange?style=for-the-badge&logo=microsoft)](https://github.com/microsoft/hack-together)
