
1. Specify the Cloud Environment:

```bash
#Azure Commercial Cloud
az cloud set --name AzureCloud

#Azure Government Cloud
az cloud set --name AzureUSGovernment
```

2. Login to your azure account from the CLI (you can either run `az login` or `az login --use-device-code` and apply the code from your terminal to the link that is output).

3. Create a Resource Group where you want to provision the environment and your ARO Cluster:

> Info: When you run a Bicep / ARM Template, the resource providers referenced 

```bash
az group create --name landing-zone --location eastus
```

az deployment group create --resource-group landing-zone --template-file landing-zone.bicep
```