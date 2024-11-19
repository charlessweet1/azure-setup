<p align="center">
<img src="https://i.imgur.com/6x4HCi7.png" alt="Microsoft Azure logo"/>
</p>

<h1>Microsoft Azure - Setup & Configuring Virtual Machines</h1>
This tutorial outlines setting up the Microsoft Azure environment for (Windows/Linux) virtual machines. <br />

<h2>Environments and Technologies Used</h2>

- <b> Microsoft Azure (Virtual Machines/Compute)</b>

<h2>Operating Systems Used </h2>

- Windows 10 Pro, version 22H2 - x64 Gen2
- Linux Ubuntu Server 22.04 LTS - x64 Gen2

<h2>List of Actions</h2>

- Step 1: Log into the Azure portal
- Step 2: Create a resource group
- Step 3: Setup the Windows 10/Linux virtual machine 


<h2>Windows Virtual MAchine Installation Steps</h2>

<p>
<img src="https://i.imgur.com/nSMJBRQ.png" height="80%" width="80%" alt="Logging into Microsoft Azure"/>
</p>
<p>
Step 1: Log into the Azure Portal. 
</p>
<br />

<p>
<img src="https://i.imgur.com/r6KduZ5.png" height="80%" width="80%" alt="Creating a Resource Group"/>
</p>
<p>
Step 2: Within the Azure portal, create a resource group. This will be used to store the virtual machines and associated files. 
</p>
<br />

<p>
<img src="https://i.imgur.com/mvdcoLE.png" height="80%" width="80%" alt="Create Windows 10 virtual machine"/>
</p>
<p>
Step 3: Create a Windows 10 virtual machine. Ensure that the subscription, resource group, and region options match the resource group you will be using. 

Choose Windows 10 Pro 22H2. The VM architecture should be x64. Your VM size should be at least 2 vcpus to ensure smooth operation. Check the box at the bottom to confirm that you have an eligble Windows 10/11 license.   

Click Review+Create. 

</p>
<p>
<img src="https://i.imgur.com/kZNi51G.png" height="80%" width="80%" alt="Validating deployment"/>
</p>

<p>
If you get an error screen, go back and correct the red-highlighted areas. Once validated, click Create to deploy the Windows 10 virtual machine.   

Click Review+Create. 
</p>

<p>
<img src="https://i.imgur.com/nuOnEk5.png" height="80%" width="80%" alt="Completing Windows VM creation"/>
</p>


<p>
The Windows virtual machine has been successfully deployed!
</p>

<h2>Linux Virtual MAchine Installation Steps</h2>

<p>
<img src="https://i.imgur.com/nSMJBRQ.png" height="80%" width="80%" alt="Logging into Microsoft Azure"/>
</p>
<p>
Step 1: Log into the Azure Portal. 
</p>
<br />

<p>
<img src="https://i.imgur.com/r6KduZ5.png" height="80%" width="80%" alt="Creating a Resource Group"/>
</p>
<p>
Step 2: Within the Azure portal, create a resource group. This will be used to store the virtual machines and associated files. 
</p>
<br />

<p>
<img src="https://i.imgur.com/2blEGro.png" height="80%" width="80%" alt="Create Linux virtual machine"/>
</p>
<p>
Step 3: Create a Linux virtual machine. Ensure that the subscription, resource group, and region options match the resource group you will be using. 

Choose Ubuntu Server 22.04. The VM architecture should be x64. Your VM size should be at least 2 vcpus to ensure smooth operation. Check the box at the bottom to confirm that you have an eligble Windows 10/11 license.   

Click Review+Create. 

</p>
<p>
<img src="https://i.imgur.com/kZNi51G.png" height="80%" width="80%" alt="Validating deployment"/>
</p>

<p>
If you get an error screen, go back and correct the red-highlighted areas. Once validated, click Create to deploy the Windows 10 virtual machine.   

Click Review+Create. 
</p>

<p>
<img src="https://i.imgur.com/nuOnEk5.png" height="80%" width="80%" alt="Completing Windows VM creation"/>
</p>


<p>
The Linux virtual machine has been successfully deployed!
</p>


<br />
