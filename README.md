<p align="center">
<img src="https://github.com/ColtonTrauCC/vm-network/assets/147654000/2cb238ff-4e46-4a75-8967-7ef5d124ab74" height="15%" width="15%" alt="Microsoft Azure logo"/>
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
    <li>The <b>Storage Account</b> is a Resource in Microsoft Azure that serves as a general 500 TB storage unit for data in the cloud, more information <a href ="https://azure.microsoft.com/en-us/products/category/storage/">here</a></li>
    <li>First, have a simple image or txt file on hand for uploading</li>
    <li>Head to the <b>Storage account</b> page and click on <b>create</b></li>
    <li>Storage Accounts have multiple fields for creation</li>
    <ul>
      <li><b>Basics</b> - What Resourc Group the Resource will be in and instance details for the name of the storage account and determining performance</li>
      <li><b>Advanced</b> - Offers more complex options such as adjusting the security and protocols; some options are not available depending on your storage account's instance details from Basics</li>
      <li><b>Networking</b> - Connectivity and Routing options</li>
      <li><b>Data Protection</b> - Enables how data is recovered and tracked in storage</li>
      <li><b>Encryption</b> - Determines how data is encrpted, uses Microsoft-managed keys by default</li>
      <li><b>Tags</b> - Same as creation of tags in Resource Group creation</li>
      <li><b>Review</b> - checking validation and overview of the Resource's information</li>
    </ul>
    <li>After inputting information, click on <b>Create</b> to create the resource and wait for deployment to finish</li>
    <li>Now to store data in the Storage Account, we need to create a <b>container</b> by going to the Storage Account you made and navigating to <b>Containers</b> under <b>Data Storage</b>. Click on <b>(Plus Sign) Container</b> and enter information in the window on the right</li>
    <ul>
      <li><img src= "https://github.com/ColtonTrauCC/azure-portal/assets/147654000/ff9d532a-eb33-4a0f-a9be-709cd8a5b06b" /></li>
    </ul>
    <li>Through here it's self explanitory as you use the <b>Upload</b> icon in the container to upload files in selected container. If your file is a coding language or txt file, you can edit its information through Azure</li>
  </ul>
</p>

<br />

<h2>Clean Up</h2>

<p>
  <ul>
    <li>If no longer used, it is best to delete Resource Groups and it Resource to prevent billing from stacking up.</li>
    <li>Head to the Resource Group and select <b>Delete</b> to open a window on the right. Deletion of the Resource Group require verification by entering its name, it's also convenient since it deletes all resources in that group</li>
    <ul>
      <li><img src ="https://github.com/ColtonTrauCC/azure-portal/assets/147654000/6d0f216d-f7fb-4409-98d0-aa7bb4d9c7b6"/></li>
    </ul>
  </ul>
</p>
