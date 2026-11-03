# ADD-Setup
Active Directory Domain and Domain Controller Setup

#Requirement
1. You already have Window Server 2022 install on your VirtualBox.
2. If not, see this link https://github.com/ChangITTech/WindowServer2022Setup.git on setting it up


#Steps

Step 1.Open up Server Management and get onto the landing page. Here, we are going to change the computer name to to bring context to the server. Open it.

Step 2. Here we can rename the PC full name. A good practice is to name with context, so "State-City-1" is something to use. Make one for your geographic area.

Step 3.Once done, we go to the "local server dashboard" and look for "Add roles and features".

Step 4. After clicking on "Add roles and features", keep clicking "Next" until you get to this page. From here, make sure you check "Active directory Domain Services(Not Installed).

Step 5. Continue clicking next until you reach here. Click on "Add Features"

Step 6.Confirm "Add Features" and it will take you to this page. Click "install". Then wait for it to finish install.

Step 7.Once finish installing "Active Directory Domain Services". Next we need to promote this server to the domain controller. We can click on the icon highlighted to get to the page of promoting it.

Step 8. Click on the icon highlighted from step 7 will bring you here, Active directory Domain Services Configuration Wizard page. We will click on "add a new forest" and give a root domain name of your choice.

Step 9. Add a password of your choice.

Step 10. After adding the password, keep clicking next until you reach here, Prerequisites Check. Here you will install, and wait. After installation is complete. It will restart the computer.

step 11. After reboot, open up server manager and check if the domain is what you name earlier. If it's there, then congratulation. You have successful install Active directory domain into your window server 2022.

#After thoughts

This project teaches me a Window server 2022 need a Active Directory Domain server install and be the domain controller. Having this ADD as the domain controller, will allow authorize machines to join the an access the server. 
 
