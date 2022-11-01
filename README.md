# Azure Lighthouse Managed Offer (Sandbox - Cloud Essentials)
Stores the Azure Lighthouse Managed Security Offer template that can be used to provide delegation to customer environments from objects with the Partner Sandbox account

The following permissions are included in this lighthouse offer.

# Delegated Permissions

| User/Group                                | Delegated Permission                                 |
| ----------                                | --------------------                                 |
| Managed Azure - Engineers                 | Reader                                               |
| Managed Azure - Engineers                 | Support Request Contributor                          |
| Managed Azure - Engineers                 | Managed Services Registration assignment Delete Role |
| Managed Azure - Services                  | Reader                                               |
| Managed Azure - Services                  | Support REquest Contributor                          |
| Managed Azure - Service Delivery Managers | Reader                                               |

# Deploy to Azure 

Use the below button to deploy this Azure Lighthouse offer to a tenant.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSoftcatMS%2Fazure-lighthouse-managedoffer-sandbox-cloudessentials%2Fmain%2Fsandbox-cloudessentials-lighthouse-offer-nopim.json)
