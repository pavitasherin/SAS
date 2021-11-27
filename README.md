# UTS-Sistem Administrasi Server
------
## Pavita Sherintama Giantoro 1202190051    IT0201
------
**Question**
------
a.Instalasi windows server 2022

b.Instalasi Active Directory Domain Services

c.Instalasi DNS server

d.Instalasi Net Framework 3.5

e.Promote Server a Domain Controller

**Answer**
------
### a. Instalasi windows server 2022
1. Download ISO Installer windows server 2022

   https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
   
2. Open VirtualBox and go to the "New" menu
   
   ![2](https://user-images.githubusercontent.com/78127403/143674901-47b0a0cb-8d5a-4a64-950f-aaba818e6477.png)

3. Enter the name of the machine and type of system to use  
   
   ![3](https://user-images.githubusercontent.com/78127403/143674997-8f1dc09f-4666-4b36-9bd0-70ac7fa5bf5b.png)

4. Define ram, create the disk defining type and size

   ![4](https://user-images.githubusercontent.com/78127403/143675141-6f1c566d-dcc9-4bc6-b8e7-13e54977f71d.png) 
   
   ![5](https://user-images.githubusercontent.com/78127403/143675155-5f325921-a64b-4d57-b7fa-270b2392d1bf.png)
   
   ![6](https://user-images.githubusercontent.com/78127403/143675277-a76f9283-978c-4ef3-b3a5-c986b820e525.png)

   ![7](https://user-images.githubusercontent.com/78127403/143675279-43f7a815-eaf8-4306-a101-d62cf94dbac7.png)
  
   ![8](https://user-images.githubusercontent.com/78127403/143675284-9488ead0-e649-4486-a513-855dc0496746.png)


5. Go to the machine configuration and in the “Network” section set “Bridge adapter”

   ![9](https://user-images.githubusercontent.com/78127403/143675454-b4207887-e716-4ede-91f1-c2e1d58e9aec.png)
   
   ![10](https://user-images.githubusercontent.com/78127403/143675456-8c560048-e080-496c-ad5e-9e65c12c8c6b.png)

6.  Click on “Start” and select the ISO downloaded

    ![11](https://user-images.githubusercontent.com/78127403/143675487-738b14d1-accf-43aa-9793-81b5451392c5.png)
   
    ![12](https://user-images.githubusercontent.com/78127403/143675494-9158393c-4f68-4497-9032-44d7d7bd2378.png)
   
    ![13](https://user-images.githubusercontent.com/78127403/143675496-4c7392d8-0142-49d7-9a4f-6a0517ce4dad.png)


7.  Click on “Start” and the Windows Server 2022 installation wizard will load

    ![14](https://user-images.githubusercontent.com/78127403/143675553-b13fc7da-9f77-44ae-a5c2-11b25465da5d.png)

8.  Click on “Install now”

    ![15](https://user-images.githubusercontent.com/78127403/143675567-598f1372-4b35-4d0c-ba4a-1e52582d8b54.png)

9.  Select windows server 2022 desktop experience

    ![16](https://user-images.githubusercontent.com/78127403/143675675-dcf518f1-0321-47f8-bb3b-d3625608ba93.png)

10. Accept the license and then proceed with the installation of Windows Server 2022

    ![17](https://user-images.githubusercontent.com/78127403/143675687-f6e4e0c2-13d6-4bde-92ce-d34a11c1d1de.png)

11. Select windows server 2022 install microsoft server advanced (Custom)

    ![36](https://user-images.githubusercontent.com/78127403/143675919-9174e91d-2d56-4a04-a87f-8722e1f2a4fe.png)

12. Location installation of windows server 2022

    ![18](https://user-images.githubusercontent.com/78127403/143675947-b91c307a-3bea-41f8-9e4a-4e869200493c.png)

13. installation progress

    ![19](https://user-images.githubusercontent.com/78127403/143676030-a8ce8ffc-87c8-4c9a-af12-dc4a09c9f714.png)

14. The system will reboot to complete the process

15. Next, enter your password administrator
   
    ![20](https://user-images.githubusercontent.com/78127403/143676085-1cdf917a-c270-493e-882a-e1a106db4db6.png)

16. Access the menu “Input – Keyboard – Insert Ctrl + Alt + Del”. Enter the password created and wait for the configuration to load
   
    ![21](https://user-images.githubusercontent.com/78127403/143676131-1b2bf281-fa5c-496b-8d0a-734d2179f10b.png)

    ![22](https://user-images.githubusercontent.com/78127403/143676136-be7070f7-230e-4db8-83a6-b2e9dbe7f36a.png)
   
    ![23](https://user-images.githubusercontent.com/78127403/143676258-9475591f-569f-40fa-b637-4c0b8195010c.png)

17. Go to the menu "Devices-Insert Guest Additions CD Image"
   
    ![24](https://user-images.githubusercontent.com/78127403/143676259-1ceb4181-cd43-449c-8981-ea13b02b43b8.png)
   
    ![25](https://user-images.githubusercontent.com/78127403/143676272-454e7917-6750-47bd-9dc7-bb01be38510f.png)
   
    ![26](https://user-images.githubusercontent.com/78127403/143676276-91c32f01-3a8d-40a5-a170-055690123dd5.png)
   
    ![27](https://user-images.githubusercontent.com/78127403/143676277-2f6c12b9-2834-4691-a0ac-52bd3776e07d.png)
   
    ![28](https://user-images.githubusercontent.com/78127403/143676279-901ca16d-c244-4459-818c-242a6ae3b48d.png)
   
    ![29](https://user-images.githubusercontent.com/78127403/143676281-09f7ce61-cedb-42b3-a034-afa65819b231.png)

    ![30](https://user-images.githubusercontent.com/78127403/143676284-1bd6d1a2-7d64-4d34-a710-4b579ee18f72.png)

18. Run "winver" to Validate the Installed Edition of Windows Server

    ![34](https://user-images.githubusercontent.com/78127403/143676353-1fc8c418-1581-44ae-8cfd-5f2722ac594d.png)
   
    ![35](https://user-images.githubusercontent.com/78127403/143676355-c579fc94-aee8-4dd9-8ef5-36d385ff2dee.png)



### b. Instalasi Active Directory Domain Services
-  Buka menu start lalu pilih Windows PowerShell
   ![b1](https://user-images.githubusercontent.com/92350603/143672373-95676423-bec2-4003-b4a8-600b2fa47e57.png)
   ![b2](https://user-images.githubusercontent.com/92350603/143672377-f95ba41c-982b-4d7d-a578-1cea0feb48df.png)
   ![b3](https://user-images.githubusercontent.com/92350603/143672380-de02fca0-4700-4168-96cb-e96ecf76982b.png)

### c. Instalasi DNS server
### d. Instalasi Net Framework 3.5
### e. Promote Server to a Domain Controller
