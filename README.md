# GraphRAG Accelerator

[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/Azure-Samples/graphrag-accelerator)

Welcome to the GraphRAG solution accelerator! This accelerator builds on top of the [graphrag](https://github.com/microsoft/graphrag) python package and exposes API endpoints hosted on Azure, which can be used to trigger indexing pipelines and enable querying of the graphrag knowledge graph.

For FAQ, access instructions, and our roadmap, please visit `aka.ms/graphrag`

![](docs/assets/graphrag-architecture-diagram.png)

## Getting Started with GraphRAG on Azure

### Deployment Guide
To deploy the solution accelerator, see the [deployment guide](docs/DEPLOYMENT-GUIDE.md). This will result in a full deployment of graphrag as an API.
Afterwards, check out the [Quickstart](notebooks/1-Quickstart.ipynb) notebook for a demonstration of various API calls.

### setup
Model Name	            TPM Threshold
gpt-4 turbo	            80K
text-embedding-ada-002  300K

# login to Azure - may need to use the "--use-device-code" flag if using a remote host/virtual machine
az login
# check what subscription you are logged into
az account show
# set appropriate subscription
az account set --subscription "<subscription_name> or <subscription id>"

## Development Guide
Interested in contributing? Check out the [development guide](docs/DEVELOPMENT-GUIDE.md).

### How to file issues and get help
This project uses GitHub Issues to track bugs and feature requests. Please search the existing issues before filing new issues to avoid duplicates. For new issues, file your bug or feature request as a new Issue.

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to
agree to a Contributor License Agreement (CLA) declaring that you have the right to,
and actually do, grant us the rights to use your contribution. For details, visit
https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need
to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the
instructions provided by the bot. You will only need to do this once across all repositories using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft’s Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party’s policies.
