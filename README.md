<img width="960" alt="image" src="https://github.com/TLAlli04/Azure_VM_Creation/assets/145707009/9d1b343e-feca-4bd8-8cd7-39622cee47cf"># Azure_VM_Creation
Documentation of Procedures for Creating Azure VM Using the Azure Portal
## Create a Resource Group for holding all resources required
a. Login to your Microsoft Azure Account
b. Search for Resource group from the Azure Portal by Entering Resource in the Search box provided at the Top
c. Select Create a resource group and press Enter and fill the Basic Tab details. The fields were populated with required vales as: Subscription: **Azure Subscription 1**, Resource Group Name: **VM_RES_GRP** and Region: **East US** as in the link provided below:
         <img width="544" alt="image" src="https://github.com/TLAlli04/Azure_VM_Creation/assets/145707009/c5c168e2-d3bb-4ba0-9c3e-50087a77f759">
d. Click on the Tag tab and populate the Name and Value pair for the resource group.The Tag Name is  **FBN_VM** and Value is **AppServer**.Find the details as in the image below:
         <img width="532" alt="image" src="https://github.com/TLAlli04/Azure_VM_Creation/assets/145707009/249ba951-b392-4263-9a8b-58e7b00e61d1">
   The essence of tagging is for the azure to logically organise all the resources.
e. Click on Review + Create to provide a summary of details entered and thereafter create the resource group.The detail veiw of the resource group created is as below:
      <img width="905" alt="image" src="https://github.com/TLAlli04/Azure_VM_Creation/assets/145707009/266c65a4-559c-4f71-a172-0203a1c275ac">
## Create Virtual Machine
a. Type Virtual in the Search button and Press Enter to list all Azure resouces that start with Virtual
b. Click on Virtual Machine. In the Basic Tab, Populate Subscription and Resource group fields with the correct values as in image below:
      <img width="583" alt="image" src="https://github.com/TLAlli04/Azure_VM_Creation/assets/145707009/944584d2-947d-4d91-94d7-aa9d98eb3ffa">
   Other Tabs should left with default populations.
c. Click on Review + Create Tab, and review all the values populated as in the below image:
      <img width="506" alt="image" src="https://github.com/TLAlli04/Azure_VM_Creation/assets/145707009/21db71e9-9cb7-41c0-9b86-1e5e97b739f0">
d. Click on Create Button to create the Virtual Machine as shown below:
      <img width="680" alt="image" src="https://github.com/TLAlli04/Azure_VM_Creation/assets/145707009/1e4ddb8b-45c6-45b8-bbd6-749d3a25e995">
## Test the Deployment by Logging in to the Machine
a. Click on Overview Option to see the details of the Virtual Machine created as shown in the image below:

b. Copy the Public IP Address of the Virtual Machine created and Connect to the Virtual machine from your local machine using the RDP.Find the details as below:

c. Visualize the whole Resource created from the Resource group to the Virtual Machine.Find the detail Resource Visual diagram as below:
     
        
               
      
            





