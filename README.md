# Azure_WebApp_Deployment_with_Terraform
Please start with Creating
1.	Variable.tf
2.	Providers.tf (We configure Azure as a provider)
3.	Backend.tf (we will store .ftstate file and configure existing or new storage container)

After than,
Creat
1-azurerm_resource_group
2-azurerm_virtual_network
3-azurerm_subnet
  a-frontend
  b-backend
  c-midle subnet
(these subnets will use dir koad balancer)
4-Creat a loadbalancer
5-Creat a storage account
