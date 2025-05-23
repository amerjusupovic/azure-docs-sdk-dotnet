---
title: 
keywords: Azure, dotnet, SDK, API, Azure.ResourceManager.Automanage, automanage
ms.date: 05/29/2023
ms.topic: reference
ms.devlang: dotnet
ms.service: automanage
---
# Microsoft Azure Automanage management client library for .NET

The Microsoft Azure Automanage offers a unified solution to simplify IT management. With point-and-click simplicity, automate operations and apply consistent best practices across the entire lifecycle of Windows Server and Linux servers in Azure or in hybrid environments enabled by Azure Arc.

This library supports managing Microsoft Azure Automanage resources.

This library follows the [new Azure SDK guidelines](https://azure.github.io/azure-sdk/general_introduction.html), and provides many core capabilities:

    - Support MSAL.NET, Azure.Identity is out of box for supporting MSAL.NET.
    - Support [OpenTelemetry](https://opentelemetry.io/) for distributed tracing.
    - HTTP pipeline with custom policies.
    - Better error-handling.
    - Support uniform telemetry across all languages.

## Getting started 

### Install the package

Install the Microsoft Azure Automanage management library for .NET with [NuGet](https://www.nuget.org/):

```dotnetcli
dotnet add package Azure.ResourceManager.Automanage
```

### Prerequisites

* You must have an [Azure subscription](https://azure.microsoft.com/free/dotnet/)

### Authenticate the Client

To create an authenticated client and start interacting with Azure resources, please see the [quickstart guide here](https://github.com/Azure/azure-sdk-for-net/blob/Azure.ResourceManager.Automanage_1.1.0-beta.1/doc/dev/mgmt_quickstart.md)

## Key concepts

Key concepts of the Azure .NET SDK can be found [here](https://azure.github.io/azure-sdk/dotnet_introduction.html).

## Documentation

Documentation is available to help you learn how to use this package

- [Quickstart](https://github.com/Azure/azure-sdk-for-net/blob/Azure.ResourceManager.Automanage_1.1.0-beta.1/doc/dev/mgmt_quickstart.md)
- [API References](/dotnet/api/?view=azure-dotnet)
- [Authentication](https://github.com/Azure/azure-sdk-for-net/blob/Azure.ResourceManager.Automanage_1.1.0-beta.1/sdk/identity/Azure.Identity/README.md)

## Examples

Code samples for using the management library for .NET can be found in the following locations
- [.NET Management Library Code Samples](/samples/browse/?branch=master&languages=csharp&term=managing%20using%20Azure%20.NET%20SDK)

## Troubleshooting

-   File an issue via [Github
    Issues](https://github.com/Azure/azure-sdk-for-net/issues)
-   Check [previous
    questions](https://stackoverflow.com/questions/tagged/azure+.net)
    or ask new ones on Stack Overflow using azure and .net tags.


## Next steps

For more information on Azure SDK, please refer to [this website](https://azure.github.io/azure-sdk/)

## Contributing

For details on contributing to this repository, see the [contributing
guide][cg].

This project welcomes contributions and suggestions. Most contributions
require you to agree to a Contributor License Agreement (CLA) declaring
that you have the right to, and actually do, grant us the rights to use
your contribution. For details, visit <https://cla.microsoft.com>.

When you submit a pull request, a CLA-bot will automatically determine
whether you need to provide a CLA and decorate the PR appropriately
(e.g., label, comment). Simply follow the instructions provided by the
bot. You will only need to do this once across all repositories using
our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct][coc]. For
more information see the [Code of Conduct FAQ][coc_faq] or contact
<opencode@microsoft.com> with any additional questions or comments.

<!-- LINKS -->
[cg]: https://github.com/Azure/azure-sdk-for-net/blob/Azure.ResourceManager.Automanage_1.1.0-beta.1/sdk/resourcemanager/Azure.ResourceManager/docs/CONTRIBUTING.md
[coc]: https://opensource.microsoft.com/codeofconduct/
[coc_faq]: https://opensource.microsoft.com/codeofconduct/faq/

