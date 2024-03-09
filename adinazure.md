# Active Directory in Azure

![alt text](image.png)

- This lab pretent to be a simulation of corporate enviroment, objetive is a Windows 10 machine can login into Active Directory hosted in WS machine.

##

# 1. Deploy and configuration of Windows Server

![alt text](image-1.png)

 - This is the settings to Windows Server machine.
##

 ![alt text](image-2.png) 

- Login in RDP with the credentials

##

![alt text](image-3.png)
![alt text](image-4.png)

- In Windows Server machine, we install Active Directory

##

![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-7.png)

- This is a internal domain.

##

![alt text](image-8.png)

- After installation, automatically the VM gonna restart

##

![alt text](image-9.png)

- Internal domain.

##

# 2. Automated user creation with PowerShell

![alt text](image-10.png)

- To create ours users, we gonna use a PowerShell script.


            Set-ExecutionPolicy Unrestricted

            
![alt text](image-11.png)

##

![alt text](image-12.png)

- If you want to download the scrip and list, is in the repository
- To scrip works, you need to use cd to the correct path

##

![alt text](image-13.png)
![alt text](image-14.png)

- Now, we have a AD with 999 users.
#

# 3. DNS server

![alt text](image-15.png)

- That IP is from the Windows Server VM.
