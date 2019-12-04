# What is the Azure portal?

The Azure portal is a web-based, unified console that provides an alternative to command-line tools. With the Azure portal, you can manage your Azure subscription using a graphical user interface. You can build, manage, and monitor everything from simple web apps to complex cloud deployments, create custom dashboards for an organized view of resources, and configure accessibility options for the best experience.
The Azure portal is designed for resiliency and continuous availability. It has a presence in every Azure Datacenter thereby making it resilient to individual Datacenter failures and avoids network slowdowns by being close to users. The Azure portal updates continuously and requires no downtime for maintenance activities.
## Follow the below steps to Login into Azure Portal:

1.	Navigate to: https://portal.azure.com/ to access Azure Portal with provided Azure Credentials.
  ![](images/work.png)

2.	Once you logged-in successfully, you’d be able to access the Azure Portal as shown in below image:
![](images/work.png)

>Note: You can close the recommendations window as this is not needed for this lab. 

**Azure Dashboard**

Dashboards provide a focused view of the resources in your subscription that matter most to you. We’ve given you a default dashboard to get you started. You can customize this dashboard to bring the resources you use most into a single view. Any changes you make to the default view affect your experience only. However, you can create additional dashboards for your own use or publish your customized dashboards and share them with other users in your organization.

## Become Familiar:
1. **What is subscription in Azure?**

The Azure account is a global unique entity that gets you access to Azure services and your Azure subscriptions. You can create multiple subscriptions in your Azure account to create separation e.g. for billing or management purposes. In your subscription(s) you can manage resources in resources groups

2. **What are Azure Resource Group:**

A container that holds related resources for an Azure solution. The resource group includes those resources that you want to manage as a group. You decide which resources belong in a resource group based on what makes the most sense for your organization. 
There are some important factors to consider when defining your resource group:

•	All the resources in your group should share the same lifecycle. You deploy, update, and delete them together. If one resource, such as a database server, needs to exist on a different deployment cycle it should be in another resource group.
•	Each resource can only exist in one resource group.
•	You can add or remove a resource to a resource group at any time.
•	You can move a resource from one resource group to another group. 
•	A resource group can contain resources that are located in different regions.
•	A resource group can be used to scope access control for administrative actions.

3.	**Azure Cloud Shell:**

Azure Cloud Shell is an interactive, authenticated, browser-accessible shell for managing Azure resources. It provides the flexibility of choosing the shell experience that best suits the way you work, either Bash or PowerShell.
Launch Azure Cloud Shell:
You can launch azure shell using Azure portal by clicking on shell icon as shown below. Users can use drop-down option to select Bash or Powershell as per their requirements. 
![](images/work.png)
