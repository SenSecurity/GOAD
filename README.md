Template for Game of Active Directory V2

1. git clone https://github.com/SenSecurity/GOAD.git
2. az group create --name GOADLab --location francecentral
3. az deployment group create --resource-group GOADLab --template-file template.json --parameters @parameters.json
