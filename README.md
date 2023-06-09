### Hi, I'm Joann ☺
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Project Summary:</h1>
This walkthrough outlines and discusses the prerequisites and installation of VPN and remote desktops as well as the use of VPN installation.<br />

<h2>Environments and Technologies Used:</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN
- whatismyipaddress.com

<h2>Operating Systems Used: </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites:</h2>

- Azure Virtual Machine 
- Microsoft Remote Desktop
- VPN

<h2>Installation Steps:</h2>

<p>
<img src="![1st picture to github](https://github.com/Brownj201612/Brownj201612/assets/135289738/d8afdc99-50e9-401c-a779-4eacd8725759)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use a browser through your local PC to visit whatismyipaddress.com where the local PC’s  public IP address and real time location will be displayed in the upper and lower left-hand side of the webpage. Once  the accuracy of your current location has been confirmed , notate your IPV4 address, location, and city into a word document or notepad application for future reference. 
</p>
<br />

<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Through portal.azure.com click on the virtual machines button found under Azure services or type Virtual Machines in the search bar above. Then you will click create and select ‘Azure Virtual Machine’ to begin creating your Virtual Machine settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select your subscription type and press ‘create new’ or allow Azure to prename your resource group. Scroll down to enter your instance details. In this section you will name your virtual machine. Select a region that is not the same as your current location, on your local PC, and select Windows 10  Pro from the drop down menu. Then select a VM size to support the workload that is to be supported through the VM. The size that is chosen will  then predetermine factors such as processing power, memory, and storage capacity. Create your username and password that should be noted for future reference. After clicking ‘I confirm ‘ and ‘review + create’ select ‘create’ once again to begin creating your virtual network/Virtual Machine(VM).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the deployment process is completed click go to ‘resources’ or ‘resource groups’ to copy and paste the  virtual machine's IP address located on the upper right side of the screen.
</p>
<br />

<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step it is recommended to download Microsoft Remote Desktop through the Google Play store onto your  local PC or search remote desktop connection via your search bar. This will be  based on the model of your computer in order to connect to your VM’s remote desktop. Once MIcrosoft Remote Desktop is opened press the ‘+’ symbol to add a PC. Copy the public IP address into  the host name section and press ‘Save’.

</p>
<br />

<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once connected, use the same username and password that was created for the VM through Azure to log into the remote desktop. Select preferred settings  but it is not required to continue, then click ‘accept’.


</p>
<br />

<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Open your virtual machine’s browser and type in the website whatismyipaddress.com and take notice of the new  IP4V address, location, and city created through the virtual machine. Notate the new information into the word document or notepad application that was created during step one. Then Switch back to  your local PC and  browse to ProtonVPN.com and create a free account in which you will then select ‘Get VPN Free’.
 

</p>
<br />

<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have reached this page you will  copy & paste the current  Proton URL into the virtual machine that  is currently  running and use the same credentials that were used to create the free VPN account on your local PC and click on windows 'Download’. Once WIndows is downloaded accept all default settings and select ‘finish’. 
 


</p>
<br />

<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Open the ProtonVPN app and log in. (It is optional to click ‘tour’ ) On the left hand side of the screen free locations will be available to connect to a VPN Server. Once the virtual machine  has established a VPN connection after the  preferred location has been selected a location will be displayed on the upper lefthand corner of the screen.
 


</p>
<br />









<h2>🤳Connect with me:</h2>
