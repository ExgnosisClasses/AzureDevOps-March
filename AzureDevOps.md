# Azure DevOps

---

![](images/Microsoft-Azure-DevOps-logo-1662554207.png?raw=true)

- Author: Rod Davison
- Date: March 10, 2024

This is the class demo/lab reference document for the class "Azure DevOps" held on March 12 and March 14, 2024

The official Microsoft Azure documentation for Azure DevOps is here:
[Azure DevOps documentation](https://learn.microsoft.com/en-us/azure/devops/?view=azure-devops)

---

## Section One - Getting Set Up

You need to have an Azure account in order to work through this set of exercises. I you don't have one, then you can set up a free account at Azure provided you have a credit card to use for identity verification.

To start, go the the [DevOps Login](https://dev.azure.com) page. If you are already logged into your Azure account, you may see a link user your account, or you can select the "start for free" option which will pick up you account info. This behaviour will vary depending on how your account and local environment are configured.

![](images/01%20Loging%20Screen.png?raw=true)

When you login, you will be asked to create or select an existing organization. If you do not have an organization, enter a name for one. The name of your organization has to be unique and descriptive. Names like "Demo1" and other common throwaway names are not allowed because they are reserved.

![](images/02%20opening%20dialog.png?raw=true)

### Organizations

An organization in Azure DevOps is the top-level container where all your DevOps projects, teams, users, and processes are stored and managed. It allows for the grouping of various projects under a single umbrella, enabling easier management, collaboration, and resource sharing among different projects and teams.

Organizations in Azure DevOps are used for:

1. **Project Management**: Organizations allow for the separation and organization of work based on different goals, teams, or products. For example, an organization may represent a specific product line or all work related to a specific client. Think of an organization as like a department or division in a company.

2. **Access Control and Permissions**: An organization allows administrators to be able to define and manage user permissions and access levels for different projects and resources within that organization, ensuring that team members have the appropriate access to the tools and information they need while preventing them from accessing anything that is not related to that organization.

3. **Collaboration**: Organizations provide a collaboration mechanism for team members by providing a shared space for code repositories, build and release pipelines, work items (tasks, bugs, features, etc.), and test management.

4. **Resource Sharing**: Teams within an organization can share resources such as build pipelines, libraries, and test environments, making it more efficient and cost-effective to manage development and deployment processes.

5. **Integration and Extensions**: Organizations can leverage various integrations and extensions available in Azure DevOps or connect to third-party tools, enhancing their development, testing, and deployment workflows.

Once the organization has been created, You can inspect the properties of the organization by selecting the link in the bottom left corner of the screen.

![](images/03%20org%20button.png?raw=true)

You can browse through the settings for the organization, but exploring these is beyond the scope of our class.

### Projects

For the class, we will be looking at a few canned demo projects provided by Azure. Go to the webpage 
[Azure DevOps Demos](https://azuredevopsdemogenerator.azurewebsites.net/)

![](images/04%20demo%20page.png?raw=true)

Sign in with your Azure account, if you are already signed in, it should just pick it up and log you in.

Once you are on the page. Select a template, give your project a name and use the organization you just set up.

![](images/05-CreateProject.png?raw=true)

*Be sure to make the modifications to your organization setting that are specificed by the red text.*

![](images/06-Warning.png?raw=true)

Create the project (note this screenshot is of a different project) and then wait until you are told it is finished and locate to the project.

If the project is created successfully, your DevOps homes screen will look something like this.

![](images/08%20Project%20Created.png?ra w=true)

Open the project. Notice that there are a number of options related to the DevOps, CICD and other processes discussed earlier.

![](images/09%20Opening%20Menu.png?raw=true)

