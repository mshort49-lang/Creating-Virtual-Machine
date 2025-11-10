<p align="center">
<img width="261" height="174" alt="image" src="https://github.com/user-attachments/assets/651260d9-8e6c-470b-865e-88e684de8c48" />
</p>

<h1>Creating Vertual Machine and Resource Group(Azure)</h1>
This tutorial outlines the process of creating a Virtual Machine and resource.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Resource Group)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 11 (25H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Creating Virtual Machine and Resource Group
- Obtaining a public IP Address for remote desktop

<h2>Deployment and Configuration Steps</h2>

<p>
<img width="650" height="732" alt="image" src="https://github.com/user-attachments/assets/1c9a3ef5-05aa-4898-8c22-929cb7c5edc8" />
</p>
<p>
In Azure, I went to create a virtual machine. Created a new resource group, osTicket. Selected (US) East US 2, and changed the zone from 1 to 2 due to size availability (Standard_D2_v3 - 2 vcpus). Picked Windows 11 PRO for the image. Set a username and password.
</p>
<br />

<p>
<img width="661" height="812" alt="image" src="https://github.com/user-attachments/assets/11ee0d3e-a948-43dc-a6ef-d4397c7b9a90" />

</p>
<p>
In networking, I keep the virtual network and subnet as Azure created. Nic network security group stayed basic. Inbound ports set to RDP (3389), I reviewed and created a virtual machine and resource group. 
</p>
<br />

<p>
<img width="400" height="230" alt="image" src="https://github.com/user-attachments/assets/437a307d-e1c0-4044-ae32-7ac3bbff2edf" />

</p>
<p>
After creating it, I went into the virtual machine in Azure. Scrolled down to networking, obtained the public IP Address. I opened the remote desktop program, and I pasted the IP Address in the computer section. Clicked connect, put in username and password. Successfully connected to the virtual machine, to be able to install osTicket.
</p>
<br />
