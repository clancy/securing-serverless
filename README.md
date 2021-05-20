# securing-serverless

The base deployment template is included in this repository.

NOTE: You will have to change the names of the resources and update the adminPassword field in the Virtual Machine configuration.

[base_azuredeploy.json](./base_azuredeploy.json)

## Azure documentation reference for demos

- Azure AD authentication for App Service/Azure Function
  - https://docs.microsoft.com/en-us/azure/app-service/configure-authentication-provider-aad
- Key Vault references for App Service/Azure Function
  - https://docs.microsoft.com/en-us/azure/app-service/app-service-key-vault-references
- Azure Private Endpoints for Azure Key Vault
  - https://docs.microsoft.com/en-us/azure/key-vault/general/private-link-service
- Azure Private Endpoints for App Service/Azure Function
  - https://docs.microsoft.com/en-us/azure/app-service/networking/private-endpoint
