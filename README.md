# Prompty Cookbook: For Hands-on Learning


## About Prompty

[Prompty](https://github.com/microsoft/prompty) is an open-source project at Microsoft that speeds up the developers' inner loop for prompt engineering by bringing the playground experience directly into the IDE. 

Prompty brings agency with observability to the development workflow, while improving developer experience with a focus on understandability.

1. **Agency** -
1. **Observability** -
1. **Understandability** - 

Prompty (OSS) consists of three core components:
 
 1. **Asset** - A language-agnost `.prompty` format with a YAML specification.
 1. **Tooling** - A VS Code extension to create and manage `.prompty` assets.
 1. **Runtime** - A language-specific execution environment for the asset.

The project has runtimes for Python, JS/TS, .NET/C# and Java - in different levels of development. **Python is the most stable of these, and used by default in the cookbook**.

## Prompty Integrations

The project is being **adopted** by different platforms (e.g., Azure AI Foundry) in different contexts (e.g., as prompt template). We'll explore these in the **integrations** section of the cookbook - with clear examples to highlight recommended usage patterns.

Assume that all cookbook examples work with the open-source Prompty tools and runtimes by default. Once validated with a specific integration, that sample will be annotated with additional guidance on usage with that platform.

---

## About This Cookbook

The [Prompty](https://github.com/microsoft/prompty) repository contains the following resources:

1. The [Prompty Specification]() file (asset format)
1. The [Prompty Documentation]() source (powering website)
1. The [Prompty Runtime]() library sources ()

That repository should be considered the ground truth for all Prompty-related questions or usage patterns. When there is a discrepancy between that repo and this one, _prioritize the guidance in that source_.

The cookbook is a supplement to the [official Documentation](https://prompty.ai) site with three objectives:

1. **Show-vs-tell** - Use runnable `.prompty` examples to explain concepts intuitively.
1. **Beginner-friendly** - Have structured paths for self-guided learners of any skill level
1. **Contributor-friendly** - Add your samples to showcase new ideas, extensions

---

## Pre-Requisites


---

## Getting Started

This repo has been populated with:
- a [devcontainer](https://containers.dev) config - for quickstart dev environment setup.
- an [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) - for web-based preview and search-enabled docs.


---

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
