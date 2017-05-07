# one-with-angular-api


https://starwarsangularapp.azurewebsites.net//api/rebels

https://starwarsangularapp.azurewebsites.net//api/rebels?id=11

https://starwarsangularapp.azurewebsites.net//api/droids

https://starwarsangularapp.azurewebsites.net//api/planets


## Azure Deployment

```bash
az login

az group create --name "starwarsangulargroup" --location "North Europe"

az group deployment create --name StarWarsAngularDeployment --resource-group starwarsangulargroup --template-file azuredeploy.json --parameters @parameters.json
```

## Try It

[Free Azure Account](https://azure.microsoft.com/free/)

[Try Azure Functions Playground](https://azure.microsoft.com/try/app-service/functions/)
