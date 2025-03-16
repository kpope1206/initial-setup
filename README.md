

<h1>Microsoft Azure - Initial set-up</h1>
This tutorial outlines the initial setup and installation for creating Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Ubuntu

<h2>List of Prerequisites</h2>

- Create Resource Group 
- Create two Virtual Machines (VM1 [Windows], VM2 [Linux])
- Open Remote Desktop
- Pinging between VM's to check for connection in Wireshark

<h2>Installation Steps</h2>

<p>
<img width="923" alt="Image" src="https://github.com/user-attachments/assets/00b7e65d-9b0b-406f-9ca2-00cb47f9d2da" />
</p>
<p>
This is the initial setup page where you will configure your Resource Group and Virtual Network. Once you setup your resource Group, you will have to setup your Virtual Network inside of your Resource Group. Once that is done you will have to set up your two VM's. In this picture we see that the two Virtual Machines have been created and ready for launch. One Windows VM, and one Linux VM.
</p>
<br />

<p>
<img width="397" alt="Image" src="https://github.com/user-attachments/assets/8c407b10-7c85-4ecf-b399-67c74727bef0" />
</p>
<p>
This image is shows how you would open your Remote Desktop using the Microsoft Remote Desktop app on MacOs. You will copy the public ip address from either of the virtual machines you have created and paste it in the PC Name: section. Then you can give your PC a unique name if you want to (not needed). Then press enter. Then you will be prompted to add the username and password that you created when creating your VM to log into your Remote Desktop.
</p>
<br />

<p>
<img width="915" alt="Image" src="https://github.com/user-attachments/assets/16143c44-ac9a-4e1b-aa96-780497a554b9" />
</p>
<p>
In this image we used Wireshark to see the traffic running is the background of our computers. Also, we have used Powershell to open up a command line and used the ping command to check for traffic between our two Virtual Machines. We are looking for requests and responses from one Machine to the other. If an era has occured it will read era, but im this diagram, we had a successful connecgion between our Windows and Linux VM's.
</p>
<br />
