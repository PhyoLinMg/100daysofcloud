# Azure - Day 3

## Create VM with Azure CLI


## Steps

az account show
az group list

create env name
RG_NAME= "kml_rg_main-sthsth"


az vm create --resource-group $RG_NAME --name (name) --image Ubuntu2204(replace with your image) --size Standard_B2s(replace with your size) --admin-username (replace with your username) --generate-ssh-keys --storage-sku Standard_LRS(replace with your storage sku) --os-disk-size-gb (replace with your os disk size) --verbose


To confirm,

when the vm is created, there is private ip and public ip address. when you try to ssh into the linux vm, you will need the public address.


az vm show --resource-group $RG_NAME --name name of the vm --show-details --query 'publicIps'
In case u didn't know the ip


then ssh to the

ssh username@public ip



## Resources
- https://github.com/Azure-Samples/azure-cli-samples/tree/master/virtual-machine



