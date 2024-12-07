<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial will cover the steps necessary to set up osTicket within Microsoft Azure VM's and then test and experiment with several different features of osTicket<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)


<h2>Setting Up the VM</h2>

![image](https://github.com/user-attachments/assets/167e9e99-374b-4556-b04b-e721d347af28)

<p>
When setting up the VM, create a new resource group and assign the vm to that group. Then, give your vm a name and make it a Windows 10 pro version 22H2 with a size of at least 2 vcpus and 8GB memory. Also create a username and password for your vm while making sure to take note of both in a notepad. After everything is ready, press review + create and then create.
</p>
<br />

![image](https://github.com/user-attachments/assets/f0bd3ebb-019a-472d-864d-0d69643f1db5)

<p>
Once the vm has finished deploying, use a remote desktop client to access the vm (In the image, I am using Windows built in Remote Desktop Client). You will need the public IP of the machine as well as the credentials you created for it.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When you are inside the vm, download the following files inside the vm - https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD 
You can just copy the link inside of the Edge browser. Once is is downloaded, extract it somewhere on your computer. We will use the files in this folder to install osTicket and some of the dependencies.
</p>
<br />
