﻿# Prepare development environment
>Last update: 10/14/2017
>
>Author: [Dariusz Porowski](http://DariuszPorowski.MS/about/)

## Exercises
This hands-on lab includes the following exercises:
* [Exercise 1A (Option 1): Deploy developer environment](#exercise-1a-option-1-deploy-developer-environment)
* [Exercise 1B (Option 2): Setup developer machine](#exercise-1b-option-2-setup-developer-machine)

Estimated time to complete this lab: **60** minutes.

## Exercise 1A (Option 1): Deploy developer environment
1. Click on **Deploy to Azure** button below.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDariuszPorowski%2FAzureDevWorkshop%2Fmaster%2F00-PreDevEnv%2Farmtemplates%2Fdevtestlab.json" target="_blank">![Deploy to Azure](https://azuredeploy.net/deploybutton.png)</a>

2. Fill the parameters - for **Resource Group** select **Create new** and input name using a pattern like **\<your initials\>\<today's date in YYYYMMDD format\>**, e.g., **jd20170821**, set **Location** to **West Europe**, input name for **Lab Name** using the same pattern like for Resource Group, e.g., **jd20170821**. For **User Name** and **User Password** you can provide your values or use default: **AzureDev** and **Passw0rd1!**
![Developer environment deployment form](./_img/devtestdeploy.png)

3. Deployment process takes about 1 hour. After successful deployment go to **DevTest Labs** -> **\<your Lab Name\>dtl** (e.g. **jd20170821dtl**) -> **My virtual machines** -> **DevVM**
![DevTest Labs - My virtual machines](./_img/devtestmyvms.png)

4. Click **Connect**, save and open RDP file, and login using default credentials: **DevVM\AzureDev** for username, and **Passw0rd1!** for password.
![DevTest Labs - RDP Connection](./_img/rdpconnectvm.png)

5. Verify that you can run Visual Studio. 

[Scroll to Top](#prepare-development-environment)

## Exercise 1B (Option 2): Setup developer machine
Coming soon...
1. [Microsoft Windows 10 (version 1703)](https://www.microsoft.com/en-us/windowsforbusiness/try)
2. [Microsoft Visual Studio 2017 (version 15.3)](https://www.visualstudio.com/downloads/)
3. [Microsoft Visual Studio Code](https://code.visualstudio.com/)
4. [Microsoft Azure Storage Explorer](http://www.storageexplorer.com/)
5. [Microsoft Azure CLI 2.0](https://azure.github.io/projects/clis/)
6. [Microsoft Azure PowerShell](https://azure.github.io/projects/clis/)
7. [Docker for Windows](https://www.docker.com/docker-windows)

[Scroll to Top](#prepare-development-environment)