# Introduction

App Modernization is a one day workshop lead by Microsoft or Microsoft partners.The scenario will include implementing compute, storage, security, and search, using various components of Microsoft Azure.

# Sign-up for Workshop Environment
To make it easier for you to work on the labs, you are provided with pre-provisioned Azure environment. You will receive sign-up link for the lab environment from your instructor. 

* Register for the lab environment by providing your information and clicking on **Submit** button.

* On the next page, click the **Launch Lab** button.
  
* Wait for the lab environment to be provisioned. Sometimes this can take upto **10 minutes**. Once environment provisioning is complete, you will receive details in email as well as in the browser.
 
 > Note: Lab environment is enabled only for specific duration or workshop end time - whichever is earlier. At the end of the allowed time, environment will be self-destructed.
 
 # Verify the pre-provisioned Environment
 1. Launch a browser using incognite or in-private mode, and navigate to https://portal.azure.com. Once prompted, login with the Microsoft Azure credentials you received.   

2. Once you are logged in to the portal, navigate to Resource Groups. 

3. Note that you have access to two resource groups – ODL_App-xxxxx-01 and ODL_App-xxxxx-02. Note: ODL_ARM-xxxxx-01 has the pre-deployed environment **ODL_App-xxxxx-02** is a Resource group.you will use **ODL_App-xxxxx-02** to deploy new resources. 

4. Navigate to the resource group **ODL_App-xxxxx-01** and view the already existing resources such as LABVM Virtual Machine, Disk, etc.

* **LABVM** has been configured with the following:
  1. IE Enhanced Security has been disabled
  2. SQL Server Express 2017
  3. SQL Server Management Studio 2017
  4. Files are downloaded into **C:\Hackathon**

5. Users can select **LABVM** and click on **Connect** to download the RDP file
* Open the RDP file to connect to the LABVM. Provide the credentials you received to login to the VM
* Once you login to the LABVM, server manager will open. Select Local Server and verify that IE Enhanced Security Configuration has also been turned off
6. Now go to C:\Hackathon and verify the student files are there.
 
## Verify Azure Access

Open a browser instance in private or incognito mode and login to [Microsoft Azure Portal](https://portal.azure.com) using the credentials provided.

> Note: You might have an existing Azure Credential. For the pre-provisioned environment, new Microsoft Azure environment is provisioned and new AAD user is created for you. To prevent conflict with your existing accounts, it is advised to use In Private mode of IE / IE Edge or Incognito mode of Chrome browser.

## Verify Virtual Machine

You are provided a Visual Studio Community 2017 on Windows Server 2016 (x64)Microsoft with additional softwares configured.FQDN of the virtual machine and administrator credentials are provided in the lab details page. You can remote into the virutal machine using the provided credentials.

> Note: VM is provisioned in the resource group, in which you have access. Once you login to Microsoft Azure Portal, you can navigate to this VM to find more details.

# Known Issues

* In Exercise 5 - Task 1 - Users can face issue with Provision function app, **consumption tier is not existing in resource group**, In this case Users can select different region it will work.

* In Exercise 8 - Task 1 - Step 4 - Users open the solution file,after opening the solution file, it will show one error, users should ignore and can continue.

* Exercise 9 - Task 3 - Users can deploy the web app and verifying it. It will only publish the web app. Users have to skip steps 6-8.

# Notes to Instructors / Proctors

* Exercise 1 - Task 3 - Step 2: Connect to your local SQL Express instance, Use Default Username: **sa**  and Password: **P@ssword**

* Exercise 3 - Task 3 - Step 6: Users should create new guid.User can generate a new Guid by opening PowerShell and running the following command: **[guid]::NewGuid()** 

* Exercise 4 - Task 3 - Step 6: FILE-SOURCE: This is the path to the Files folder in your sample project directory, such as C:\Hackathon\Files

* Users should use the Azure Credentials given to them to login to Visual Studio.

* Users should always open the visual studio **Run as administrator**.

# Help and Support

If you require any help during the workshop, please reach out to the instructor / proctors. Instructors / proctors might escalate the issue to remote support team, at that time, please pass on your AAD User ID (aad_user_xyz), so that it is easier to look up your environment.





























