<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1: Enable internet infomation services (IIS)
- Item 2: Install web platform installer
- Item 3: Install MySQL
- Item 4: Install PHP manager
- Item 5: Configure permissions and install osTicket

<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/54f8b2fc-c3d6-48b4-87f9-d4d257bdbbfe)

<p>
First, enable IIS in Windows and check the box for CGI under World Wide Web Services > Application Development Features.
</p>
<br />
![MySQL](https://github.com/user-attachments/assets/4b17d6d4-e555-49b5-bea1-964746281f7a)


<p>
  The first step is to click on the MySQL file to download it. After that, I followed the prompts by selecting "Typical" and then clicking "Next" until the installation was complete.
  <p>
I created a new folder named "PHP" on the C: drive in Windows. Next, I started the installation of the PHP software. I located the software file, right-clicked on it, and selected "Extract All." When prompted to choose a destination, I typed in "C:/PHP," and all the files were extracted to that folder. I accepted all prompts and continued through the installation process until it was finished..
</p>
<br />

![image](https://github.com/user-attachments/assets/b3cd7f09-81b9-4b41-9db5-4924130d5904)

<p>
To install osTicket v1.15.8, unzip "osTicket-v1.15.8.zip" from the "osTicket-Installation-Files" folder, and copy the "upload" folder to "C:\inetpub\wwwroot." Then, rename the "upload" folder to "osTicket."

Finally, reload IIS by opening it, stopping the server, and then starting it again.
</p>
<br />
