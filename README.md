<p align="center">
<img src="https://i.imgur.com/Bp7tRX1.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>
<h1>Creating a Virtual Machine (VM) in Microsoft Azure</h1>
This project demonstartes how to create a virtual machine in Azure and view the created topology using Network Watcher.<br />

<h2>Requirements</h2>

- Computer with internet connection
- Microsoft Azure account
  - Credit card (required for free Azure credits)

<h2>High-Level Steps</h2>

- Select “Virtual machines” and select to Create an “Azure virtual machine”
- Fill in the required fields on the “Basics” page
- Click “Review + create”
- Click “Create” if the VM has passed validation
- View newly created VM in Network Watcher
- Delete Resource Groups to minimize charges to free Azure credits

<h2>Summary</h2>

<p>
<img src="https://i.imgur.com/zkr3A9P.png" height="70%" width="70%"/>
</p>
<p>
To get started on creating the virtual machine, search for “virtual machine” in the search bar at the top of the Azure homepage and select “Virtual machines.” Click “Create” in the top left corner (the blue “Create” button in the middle of the screen also works) and then select “Azure virtual machine.”
</p>
<br />

<p>
<img src="https://i.imgur.com/bwTogp0.png" height="50%" width="50%"/>
</p>
<p>
<img src="https://i.imgur.com/3h91vqh.png" height="50%" width="50%"/>
</p>
<p>
The first page is the “Basics” page to fill in the required fields. For the Resource group, make a new one by selecting “Create new” and also select an appropriate region based on your location. The location you select can affect your options for the “Size” field, so this may need to be carefully checked. Be sure to check the box under Licensing. Once finished, click “Review + create”.
</p>
<br />

<p>
<img src="https://i.imgur.com/ksIytig.png" height="50%" width="50%"/>
</p>
<p>
Before the VM is created, make sure it passes validation. Once the message at the top confirms a successful set up, click “Create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/3iB9u1P.png" height="70%" width="70%"/>
</p>
<p>
It is likey the VM will take time to get set up by Azure, but once finished, you'll be able to look at the configuration of the VM. It is important to know the location of the public and private IP addresses on this page, since finding this information would be important for future labs.
</p>
<br />

<p>
<img src="https://i.imgur.com/J9BB8fA.png" height="70%" width="70%"/>
</p>
<p>
The Network Watcher feature is helpful because it dsiplays a diagram of various components of the VM in Azure. As you can see, when you create a VM, it’s not just the virtual machine itself that is created. Along with the VM (VM-1), Azure also created a virtual network (VM-Lab-vnet), a subnet (default), a virtual NIC (vm-1960), a Network Security Group a.k.a. firewall (VM-1-nsg), and a public IP address (VM-1-ip).
</p>
<br />

<p>
After successfully creating the VM be sure to delete the machine when not in use to mitigate credit cost for usage.
</p>
<br />
