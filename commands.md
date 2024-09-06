# In this file: useful AZ CLI commands
Login to AZ CLI
- az login
List all available resource groups
- az group list --output table
Deploy template with resources
- az deployment group create --resource-group $AZURE_RESOURCE_GROUP --template-file infrastructure/template.json --parameters @infrastructure/parameters.json
