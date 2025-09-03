# IaC
This repository contains Infrastructure as Code (IaC) templates using [Bicep](https://learn.microsoft.com/azure/azure-resource-manager/bicep/overview), a domain-specific language (DSL) for deploying Azure resources declaratively.

## Overview

- **Purpose:** Automate and standardize Azure infrastructure deployments.
- **Technology:** All templates are written in `.bicep` files for modular, reusable, and maintainable infrastructure definitions.

## Getting Started

1. **Prerequisites:**
    - [Azure CLI](https://docs.microsoft.com/cli/azure/install-azure-cli)
    - [Bicep CLI](https://learn.microsoft.com/azure/azure-resource-manager/bicep/install)

2. **Deployment Example:**
    ```sh
    az deployment sub create --location <location> --template-file main.bicep
    ```

## Structure

- `/modules` - Reusable Bicep modules
- `/environments` - Environment-specific deployment files
- `main.bicep` - Entry point for deployments

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or new modules.

## License

This project is licensed under the MIT License.