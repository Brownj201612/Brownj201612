### Hi, I'm Joann ☺

<h2>👨‍💻 Information Technology Projects:</h2>
Installing and Observing ProtonVPN 


Project Summary: 
This walkthrough outlines and discusses the prerequisites and installation of VPN and remote desk as well as the use of VPN installation. 

Environment and Technology Used: 

Microsoft  Azure
Remote desktop
Proton VPN
whatismyipaddress.com

Operating System(s) used:
WIndows 10 Pro  (22H2)

Prerequisites:
Azure Virtual Machine
Microsoft Remote Desktop  
VPN Proton
____________________________________________________________________


















Installation Steps:

 
 Step 1: Identifying your IP address,Location, and City


 Use a browser through your local PC to visit whatismyipaddress.com where the local PC’s  public IP address and real time location will be displayed in the upper and lower left-hand side of the webpage. Once  the accuracy of your current location has been confirmed , notate your IPV4 address, location, and city into a word document or notepad application for future reference. 


Step 2: Locating the VM portals through Azure.



Through portal.azure.com click on the virtual machines button found under Azure services or type Virtual Machines in the search bar above. Then you will click create and select ‘Azure Virtual Machine’ to begin creating your Virtual Machine settings.



Step 3: Creating a Virtual Machine  (Basics Settings)



Select your subscription type and press ‘create new’ or allow Azure to prename your resource group. Scroll down to enter your instance details. In this section you will name your virtual machine. Select a region that is not the same as your current location, on your local PC, and select Windows 10  Pro from the drop down menu. Then select a VM size to support the workload that is to be supported through the VM. The size that is chosen will  then predetermine factors such as processing power, memory, and storage capacity. Create your username and password that should be noted for future reference. After clicking ‘I confirm ‘ and ‘review + create’ select ‘create’ once again to begin creating your virtual network/Virtual Machine(VM).


Step 4: Copy & Paste IP into RDP 


After the deployment process is completed click go to ‘resources’ or ‘resource groups’ to copy and paste the  virtual machine's IP address located on the upper right side of the screen.









Step 5: Connecting to a remote desktop         
                                     Google Play Example:                                                    
      
Remote Connection Example:  


In this step it is recommended to download Microsoft Remote Desktop through the Google Play store onto your  local PC or search remote desktop connection via your search bar. This will be  based on the model of your computer in order to connect to your VM’s remote desktop. Once MIcrosoft Remote Desktop is opened press the ‘+’ symbol to add a PC. Copy the public IP address into  the host name section and press ‘Save’.


Step 6: Logging into your remote desktop



Once connected, use the same username and password that was created for the VM through Azure to log into the remote desktop. Select preferred settings  but it is not required to continue, then click ‘accept’. 


Step 7: Connecting VPNs through VM



Open your virtual machine’s browser and type in the website whatismyipaddress.com and take notice of the new  IP4V address, location, and city created through the virtual machine. Notate the new information into the word document or notepad application that was created during step one.  Then Switch back to  your local PC and  browse to ProtonVPN.com and create a free account in which you will then select ‘Get VPN Free’

Step 8: Downlaoding Windows into VM




Once you have reached this page you will  copy & paste the current  Proton URL into the virtual machine that  is currently  running and use the same credentials that were used to create the free VPN account on your local PC and click on windows 'Download’. Once WIndows is downloaded accept all default settings and select ‘finish’. 



Step 10: Setting up VPN 

Open the ProtonVPN app and log in. (It is optional to click ‘tour’ ) On the left hand side of the screen free locations will be available to connect to a VPN Server. Once the virtual machine  has established a VPN connection after the  preferred location has been selected a location will be displayed on the upper lefthand corner of the screen.
 
Step 11: Identifying the new IP address.

Through the virtual machine you can either refresh whatismyipaddress.com or open the website on a different tab and notate that the IPV4, location and city of the Azure VM has changed to the preselected location through ProtonVPN. 

-

<h2>🤳Connect with me:</h2>
