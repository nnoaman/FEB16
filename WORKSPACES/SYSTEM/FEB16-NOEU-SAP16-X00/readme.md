**SAP System Deployment**

The SAP Application (**X00**) has been deployed to resource group **FEB16-NOEU-SAP16-X00** in subscription **d6c8e3b6-467e-452e-97c9-49d9de9e37da**.

You can access the resource group directly in the Azure Portal using the following link: [FEB16-NOEU-SAP16-X00](https://portal.azure.com/#@c01abe72-ffef-4ecc-bda0-937975b49e6b/resource/subscriptions/d6c8e3b6-467e-452e-97c9-49d9de9e37da/resourceGroups/FEB16-NOEU-SAP16-X00/overview)

**SAP Application Information**


| Setting                    | Value                           |
| :------------------------- | :------------------------------ |
| SID                        | X00                          |
| Database                   | hana                     |
| DB SID                     | HDB                       |
| SCS Server Loadbalancer IP | 10.110.32.9   |
| SCS High Availability      | No        |
| DB High Availability       | No   |


**Server Roles and Names**


| Role                           | Names                           |
| :----------------------------- | :------------------------------ |
| Database                       | x00dhdb01l043                   |
| Central Services               | x00scs01l43f                  |
| Primary Application Server     | x00app01l43f                   |
| Additional Application Servers | x00app01l43f,x00app02l43f          |
| Web Dispatchers                | x00web01l43f              |


**Access credentials**


| Setting                  | Value                                             |
| :----------------------- | :------------------------------------------------ |
| Key Vault Name           | [FEB16NOEUSAP16userC03](https://portal.azure.com/#@c01abe72-ffef-4ecc-bda0-937975b49e6b/resource/subscriptions/d6c8e3b6-467e-452e-97c9-49d9de9e37da/resourceGroups/FEB16-NOEU-SAP16-INFRASTRUCTURE/providers/Microsoft.KeyVault/vaults/FEB16NOEUSAP16userC03/overview)             |
| Secret name for username | [FEB16-NOEU-SAP16-sid-username](https://portal.azure.com/#@c01abe72-ffef-4ecc-bda0-937975b49e6b/asset/Microsoft_Azure_KeyVault/Secret/https://FEB16NOEUSAP16userC03.vault.azure.net/secrets/FEB16-NOEU-SAP16-sid-username) |
| Secret name for password | [FEB16-NOEU-SAP16-sid-password](https://portal.azure.com/#@c01abe72-ffef-4ecc-bda0-937975b49e6b/asset/Microsoft_Azure_KeyVault/Secret/https://FEB16NOEUSAP16userC03.vault.azure.net/secrets/FEB16-NOEU-SAP16-sid-password) |
| Secret name for SSH key  | [FEB16-NOEU-SAP16-sid-sshkey](https://portal.azure.com/#@c01abe72-ffef-4ecc-bda0-937975b49e6b/asset/Microsoft_Azure_KeyVault/Secret/https://FEB16NOEUSAP16userC03.vault.azure.net/secrets/FEB16-NOEU-SAP16-sid-sshkey)           |



