<p align="center">
<img src="https://i.imgur.com/546t2Db.jpg" height="40%" width="60%" alt="Microsoft Azure Logo"/>          
</p>

<h1>Microsoft Azure</h1>
Microsoft Azure, is a cloud computing platform operated by Microsoft that provides access, management, and development of applications and services via data centers, distributed around the world.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create Free Azure Account</h3>


Create an Azure account [here](https://azure.microsoft.com/en-us/free/).
- Select Start Free
- Follow the prompt to create the account. 
- you will get $200 worth of free Azure credit and will have 30 days to use those credits. after the credits run out you can be charged, so keep an eye on them
- Finish prompt, click Go to Azure Portal and you are ready to begin using Azure!



<p align="center">
<img src="https://i.imgur.com/rk4SD27.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/f1eRIx4.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 2: Create Your Resource Group</h3>

- Go to search bar at the top and search "resource group"
- Select create resource group
- You will then need to name the resource group and select the region 
- Select review + create
- For the example, we will be using RG-Lab-1 for the name and (US) East for the region

<p align="center">
<img src="https://i.imgur.com/Afnk87u.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yBBln5a.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>

<h3>Step 3: Create storage Account</h3>

- Go to search bar and search "storage account"
- Select Create storage account
- You will need to select the resource group, the region, and create a name for the storage group
- For the example we will name the storage group rglab1
- Use same resource group and region as step 2
- Select review, then create.

<p align="center">
<img src="https://i.imgur.com/zhb3GHZ.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/7ryNBQg.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 4: Create Your Virtual Machine</h3>
     
- Go to search bar and search "virtual machine"
- Select create, then select Azure virtual machine
- You will need to select the resource group, the region, and create a name for the virtual machine
- For the example we will name the virtual machine virtualmachine
- Use same resource group and region as step 2/3

<p align="center">
<img src="https://i.imgur.com/y0RafHM.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/PCJ3QAr.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 



- For image we will use Windows 10 Pro
- For size, select Standard 2 vcpus, 8GiB memory
* You will then need to make a username and password
* Click the box under licensing and finally click Review + Create 


<p align="center">
<img src="https://i.imgur.com/p9UJXND.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/GHBDae0.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 
     

<h3>Step 5: Connect to Virtual Machine</h3>

- First you will need to find the Public IP address of your virtual machine
- Select the virtual machhine we created and copy the Public IP on the right hand side 

<p align="center">
<img src="https://i.imgur.com/T4Oc2RX.png" height="80%" width="80%" alt="Azure Free Account"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Paste IP address and select Add
   - enter username and password from step 4
   - Select continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste IP Address and select Connect
     - Enter username and password from step 4
     - Select OK
  
     
     



🎉Congratulations! You have created your first virtual machine with Azure!🎉

<p align="center">
<img src="https://i.imgur.com/hnRSzVv.jpg" height="80%" width="80%" alt="Azure Free Account"/>



   
  
