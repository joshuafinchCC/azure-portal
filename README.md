<p align="center">
  <img width="600" height="300" src="https://github.com/joshuafinchCC/VM-VN-RDC/assets/155266044/945ededb-aa45-40b7-a2d7-c44243483fc8">
</p>

<h1 align = "center">Azure Portal Basics</h1>
This tutorial covers the creation and management of various Azure services such as <b>Resource Groups and Storage Accounts</b>. Resource groups are the basis for which all your other projects are created within Azure

<br />


<h2>List of Prerequisites</h2>
<ul>
  <li>Microsoft Azure Account and Subscription</li>
  <ul>
    <li><a href ="https://azure.microsoft.com/en-us/free/search/?ef_id=_k_CjwKCAiAnL-sBhBnEiwAJRGignR4_uWjL2YXh4iV2JXqrqL51NmTGyR6au_yGopLcqholZVLIHKPzRoCZMIQAvD_BwE_k_&OCID=AIDcmmfq865whp_SEM__k_CjwKCAiAnL-sBhBnEiwAJRGignR4_uWjL2YXh4iV2JXqrqL51NmTGyR6au_yGopLcqholZVLIHKPzRoCZMIQAvD_BwE_k_&gad_source=1&gclid=CjwKCAiAnL-sBhBnEiwAJRGignR4_uWjL2YXh4iV2JXqrqL51NmTGyR6au_yGopLcqholZVLIHKPzRoCZMIQAvD_BwE">Create your free Azure account</a></li>
  </ul>
  Creating a new account comes with $200 of credits on your free subscription, more than enough to play around with all the guides listed here
</ul>
<h2>Essentials:</h2>

<h3>Portal Navigation</h3>
<p>
  <ul>
  <li>After creating your account and logging into the <b>Azure Portal Home Page</b> you will see several ways of navigating your resources</li> 

![image](https://github.com/joshuafinchCC/azure-portal/assets/155266044/60751ff9-3d68-4ae3-91ef-ef63b8645f6e)

<p>
</ul>
      <li><b>The Search Bar or Azure Resource Icons</b> can be used to locate and create your first projects</i></li>
      <li><b>Resources</b> - This Section displays all your most recently created resources (<i>Resource Groups, Virtual Machines, Network Security Groups, etc.</i>) as well as any project recently updated/modified</li>

  </ul>
</p>
<br/>
<h3>Creating a Resource Group</h3>

<p>
  <ul>
    <li>On the main Azure Portal, Search either <b>Resource Groups</b>  or click the Resource Groups Icon. Afterwards, click create. </li>
  </ul>

![image](https://github.com/joshuafinchCC/azure-portal/assets/155266044/6768d7f7-24a7-43ce-bd32-2638429a6145)

  
 <ul>
    <h3 align = "center">Resource Groups have three fields for creation</h3>
    <li><b>Basics</b> - This is where you select your <b>Subscription</b> (default created upon subscription) and name the group. The region is where this group is based</li>
      <li><b>Tags</b> -A Simple organizational tool for managing resources by applying the same tag to multiple resources and resource groups</li>
      <li><b>Review + Create</b> - Validation processing to check if credentials (notably a name) are filled and the Subscription is usable</li>
    </ul>
   After validation passed, click on <b>Create</b> in the bottom and your Resource Group is created. Note: based on server speed and Internet connection, Resources and Resource Groups will take some time to deploy, take note of the <b>notification bell</b> at the top right to see when deployment is complete

![Screenshot 2023-12-30 174449](https://github.com/joshuafinchCC/azure-portal/assets/155266044/0934b3e8-7ab5-4be1-a0ef-6284001cf058)


</p>

<br />

<h3>Creating and using the Storage Account</h3>

<p>
  <ul>
    <li>The <b>Storage Account</b> is a Resource in Microsoft Azure that serves as a general 500 TB storage unit for data in the cloud</li>
    <li>Head to the <b>Storage account</b> icon on the home portal and click on <b>create</b></li>

![Screenshot 2023-12-30 180058](https://github.com/joshuafinchCC/azure-portal/assets/155266044/ee09b964-43a8-4de3-ab79-8d07a194730d)

    
  <li>Storage Accounts have multiple fields for creation</li>
    <ul>
      <li><b>Basics</b> - What Resource Group the storage account will be in, the name, as well as determining the region and performance</li>
      <li><b>Advanced</b> - Offers more complex options such as adjusting the security and protocols; some options are not available depending on your storage account's details from basics</li>
      <li><b>Networking</b> - Connectivity and routing options</li>
      <li><b>Data Protection</b> - Enables how data is recovered and tracked in storage</li>
      <li><b>Encryption</b> - Determines how data is encrypted, uses Microsoft-managed keys by default</li>
      <li><b>Tags</b> - Same organizational tool as the Resource Groups creation</li>
      <li><b>Review</b> - General overview of your storage account's details and settings before validation and creation</li>
    </ul>
    </p>
    
After inputting and validating your information, click on <b>Create</b> to create the resource and wait for deployment to finish

  ![Screenshot 2023-12-30 180808](https://github.com/joshuafinchCC/azure-portal/assets/155266044/942d7e83-1112-457b-b3e4-8e6628a3a41b)
    <li>To store data in the Storage Account, we need to create a <b>container</b> by navigating to <b>Containers</b> under <b>Data Storage</b>. Click on <b>(+) Container</b> and enter the name in the New Container window on the right</li>
    <ul>
      

![image](https://github.com/joshuafinchCC/azure-portal/assets/155266044/dca51448-d9bc-4bc3-9517-b3f1d48de355)

      
   </ul>
    <li>After you create the container within your Storage Account, simply select that container and click upload </li>
  </ul>

![image](https://github.com/joshuafinchCC/azure-portal/assets/155266044/ea2e0c82-adf2-4dc3-b530-b7e9e7e26c1d)

  
</p>

<br />

<h2>Clean Up</h2>

<p>
  <ul>
    <li>Azure Portal charges your subscription based off the resources you have created, varying depending on the intensity of whats being used. All the storage accounts, virtual machines and networks you create are calculated upon validation, so a good thing to get into the habit of doing is to clean up your resources when you are done!</li>
    <li>As everything we have created in this tutorial is within one resource group, deleting the group will delete everything inside of it</li>
  
  ![image](https://github.com/joshuafinchCC/azure-portal/assets/155266044/81becd36-cc77-48fd-934c-17146f861811)
  </ul>

   <li>To finish, simply select "Delete resource group" on the toolbar and enter your resource group name. Your Notifications bell on the right will keep you updated on the deletion status, and once it is complete you can navigate to the <b>Azure Home Portal</b> and find your resource groups tab empty!

