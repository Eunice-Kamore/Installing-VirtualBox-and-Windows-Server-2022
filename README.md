<H1>Overview: Lab 1 Installing VirtualBox and Server 2022</H1>

Welcome to the first lab of my home lab series! This section of my home lab documents the process of **Installing VirtualBox** and setting up a **Windows Server 2022** virtual machine within the VirtualBox. It outlines the steps for downloading and installing **VirtualBox**, followed by the creation of a virtual machine to host **Windows Server 2022**. This task serves as the foundation for building a virtualized lab environment that mimics real-world IT infrastructure, ideal for practicing administrative tasks and learning server management techniques.

<H2>Objectives</H2>

This repository documents a comprehensive home lab project focused on installing and configuring VirtualBox and Windows Server 2022. The key objectives include:

- Demonstrating the setup and installation process of VirtualBox as a virtualization platform formally known as a hypervisor.
- Installing and configuring Windows Server 2022 in a virtualized environment.
- Creating a platform for further experiments involving System Administration, Active Directory and Group Policy Configurations.



<H2>Documentation</H2>

In this documentation, I will outline the initial steps of setting up my home lab. This includes downloading and preparing the essential tools: VirtualBox and Windows Server 2022.

Before creating a virtual environment ensure you confirm that your host computer supports virtualization and you check this information through checking your system information. A shortcut to this page is typing "msinfo" on the search tab  to open system information page. Once we have confirmed this we can now begin our set-up.
To start, we’ll download VirtualBox from the official website at https://www.virtualbox.org/wiki/Downloads.

1. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/9200c774c0a6c5e371306e49e2755f3be7c9a306/Files/Edited%20one.PNG" width="400px"/>
   <br />
   <br />
Here, we select our options depending on the operating system that our computer is running on. For this lab we will choose Windows Hosts option because our host pc is running a Windows OS.

2. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Three.png?raw=true" width="400px"/>
   <br />
   <br />
   
Next, we’ll download Windows Server 2022 from the official Microsoft Evaluation Center at https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022.

3. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Downloading%20server%202022.png?raw=true" width="400px"/>
   <br />
   <br />

To access the free trial, you’ll need to provide your information during the registration process. The trial period lasts for 180 days. Once the trial ends Microsoft provides a command to renew the trial period.

4. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Fill%20in%20your%20details%20to%20download.png?raw=true" width="400px"/>
   <br />
   <br />

After filling our information in the form, we can finally download the ISO which will be the 64-bit edition (English). Clicking on the link shown your download will begin and you can locate it within your downloads folder.

5. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/After%20completing%20your%20details%20click%20download%20now%20and%20come%20to%20this%20page,click%20on%20the%2064%20bit%20link%20and%20your%20download%20will%20begin.png?raw=true" width="400px"/>
   <br />
   <br />

After everything has finished downloading, we can launch VirtualBox and begin configuring the settings for Windows Server 2022. Once VirtualBox is open, navigate to the "Machine" tab at the top and select "New" to create a new virtual machine.

6. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/1-creating%20a%20vm.png?raw=true" width="400px" />
   <br />
   <br />

First, we’ll name our virtual machine "Server 2022". Next, we’ll locate the ISO image in our Downloads folder. To do this, click the dropdown menu under "ISO Image" and select "Other." From there, we can browse to the Downloads folder and select the Windows Server ISO that we downloaded earlier.

7. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step2.png?raw=true" width="400px" />
   <br />
   <br />
After renaming the server and mounting the ISO image. Tick the "Skip Unattended Installation" box so you set the hardware configurations yourself depending on the capacity of resources you have on your host machine.

8. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step2.1.png?raw=true" width="400px" />
   <br />
   <br />
By default, the base memory is set to 2048 MB, which should be sufficient for running the virtual machine. However, since our computer has 16 GB of RAM, we can allocate around 4 GB for our virtual machine. We will ramp up the CPU to 2 since our host has 8 CPUs.  As long you remain in the green region you are safe, except you do not want to allocate too much which might slow down your host PC.
9. <p align="center">
   <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step3.1.png?raw=true" width="400px" />
   <br />
   <br />

Next, we will configure hadrdisk settings. It all depends with the storage available in your host computer. We will stick with the 50GB allocated. Once finished, click finish.
10. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step3.2.png?raw=true" width="400px" />
    <br />
    <br />
    
Now the virtual machine set up is complete. Click on the "Start" button to start the installation for our Windows Server 2022 on the VM. When the next screen appears,choose your languages and click "Next" which takes you to the next screen and click on the "Install" button.
11. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step4y.PNG?raw=true" width="400px" />
    <br />
    <br />
12. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step5.png?raw=true" width="400px" />
    <br />
    <br />
13. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step6.png?raw=true" width="400px" />
    <br />
    <br />

Then in the next screen, choose "Windows Server 2022 Standard Evaluation (Desktop Experience)," then click "Next" to continue.

14. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step7.png?raw=true" width="400px" />
    <br />
    <br />

Accept the terms and click "Next." In the next step, when prompted to choose the type of installation, select "Custom" to proceed because its a fresh installation and not an upgrade.

15. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step8.png?raw=true" width="400px" />
    <br />
    <br />

    
16. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step9.png?raw=true" width="400px" />
    <br />
    <br />

Click "Next," and the installation of Windows Server will begin.

17. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step10.png?raw=true" width="400px" />
    <br />
    <br />

18. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step11.png?raw=true" width="400px" />
    <br />
    <br />

Once the installation is complete, create a password for the “Administrator” account and click "Finish".

19. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step12.png?raw=true" width="400px" />
    <br />
    <br />

Type Ctrl + Alt + Del to bring up the log on screen. Alternatively at the top menu you can click on "Input" and select "Keyboard" and choose "Insert Ctrl + Alt + Del". After logging in the server manager launches on start up.

20. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step13.png?raw=true" width="400px" />
    <br />
    <br />

21. <p align="center">
    <img src="https://github.com/Eunice-Kamore/Installing-VirtualBox-and-Windows-Server-2022/blob/main/Files/Step14.png?raw=true" width="400px" />
    <br />
    <br />


Well done!! Successfully created our virtualized environment with Virtual Box and installed Server 2022 on our Virtual Machine.

 👉 [Next Lab 2 : Renaming Windows Server 2022 and Installing Active Directory](https://github.com/Simokid/Renaming-Server-2022-and-Installing-Active-Directory/tree/main)


















