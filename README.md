# Consume the Microsoft Graph in the SharePoint Framework

Consuming REST APIs secured with Azure Active Directory (Azure AD) and Open Authorization (OAuth 2.0) from within a SharePoint Framework client-side web part or extension is a common enterprise-level business scenario.

Introduced in v1.4.1, you can use the SharePoint Framework to consume Microsoft Graph REST APIs, or any other REST API that's registered in Azure AD.

In this article, you'll learn how to create a SharePoint Framework solution that uses the Microsoft Graph API with a custom set of permissions. For a conceptual overview of this technology, see Connect to Azure AD-secured APIs in SharePoint Framework solutions.

## Important

You can consume the Microsoft Graph API with versions of SharePoint Framework earlier than v1.4.1, either via the native GraphHttpClient, or via a manual ADAL JS implicit OAuth flow. However, the former approach is bound to a predefined set of permissions, which presents some limitations, and the latter is complex from a development perspective. For details about how to implement an implicit OAuth flow, see Connect to APIs secured with Azure Active Directory


## Create the initial solution
If you have an old version of the SharePoint Framework generator, you need to update it to v1.4.1 or later. To do that, run the following command to globally install the latest version of the package.

npm install -g @microsoft/generator-sharepoint

Next, create a new SharePoint Framework solution:

1. Create a folder in your file system. You'll store the solution source code and move the current path into this folder.

2. Run the Yeoman generator to scaffold a new solution.

yo @microsoft/sharepoint
3. When prompted, enter the following values (select the default option for all prompts omitted below):

What is your solution name? spfx-api-scopes-tutorial
Which baseline packages do you want to target for your component(s)? SharePoint Online only (latest)
Which type of client-side component to create? Web Part
What is your Web part name? GraphConsumer
Which framework would you like to use? React
Start Visual Studio Code (or your favorite code editor) within the context of the current folder.



## Please refer the below documentation

(https://docs.microsoft.com/en-us/sharepoint/dev/spfx/use-aad-tutorial)





## Summary

Short summary on functionality and used technologies.

[picture of the solution in action, if possible]

## Used SharePoint Framework Version

![version](https://img.shields.io/badge/version-1.13-green.svg)

## Applies to

- [SharePoint Framework](https://aka.ms/spfx)
- [Microsoft 365 tenant](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)

> Get your own free development tenant by subscribing to [Microsoft 365 developer program](http://aka.ms/o365devprogram)

## Prerequisites

> Any special pre-requisites?

## Solution

Solution|Author(s)
--------|---------
folder name | Author details (name, company, twitter alias with link)

## Version history

Version|Date|Comments
-------|----|--------
1.1|March 10, 2021|Update comment
1.0|January 29, 2021|Initial release

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- Ensure that you are at the solution folder
- in the command-line run:
  - **npm install**
  - **gulp serve**

> Include any additional steps as needed.

## Features

Description of the extension that expands upon high-level summary above.

This extension illustrates the following concepts:

- topic 1
- topic 2
- topic 3

> Notice that better pictures and documentation will increase the sample usage and the value you are providing for others. Thanks for your submissions advance.

> Share your web part with others through Microsoft 365 Patterns and Practices program to get visibility and exposure. More details on the community, open-source projects and other activities from http://aka.ms/m365pnp.

## References

- [Getting started with SharePoint Framework](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)
- [Building for Microsoft teams](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/build-for-teams-overview)
- [Use Microsoft Graph in your solution](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/using-microsoft-graph-apis)
- [Publish SharePoint Framework applications to the Marketplace](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/publish-to-marketplace-overview)
- [Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp) - Guidance, tooling, samples and open-source controls for your Microsoft 365 development