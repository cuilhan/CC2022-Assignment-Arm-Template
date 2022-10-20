# CC2022-Assignment-Arm-Templates

- This repository contains Azure ARM Template that is build and run Virtual Machine and Storage Account.

- We can deploy our template on Azure Portal -> Templates section or we can use Azure CLI with command that below;

- az deployment group create --resource-group MyResourceGroup  --template-file storage-account-with-arm.json

- To do this we need to use upload file functionality of Azure CloudShell.

- If any errors occurs like "this resource not available for this region" make sure you run "az vm list-skus --location centralus --zone --all --output table" command.
