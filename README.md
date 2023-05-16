# Terraform-Azure-KeyVault-AppService
This example to showcases how you can use Terraform for an App service application that uses KeyVault

# Have you encountred an error 403 whilst using Terrafor for an App service application uses KeyVault?

This is the error

```
error: checking for presence of existing Secret "saterradev-access-key" (Key Vault "https://mykv.vault.azure.net/"): keyvault.BaseClient#GetSecret: Failure responding to request: StatusCode=403 -- Original Error: autorest/azure: Service returned an error. Status=403 Code="Forbidden" Message="The user, group or application 'appid=2c8...;iss=https://sts.windows.net/a43...' does not have secrets get permission on key vault 'mykvv;location=francecentral'. For help resolving this issue, please see https://go.microsoft.com/fwlink/?linkid=2125287" InnerError={"code":"AccessDenied"}

```


