![image](https://github.com/user-attachments/assets/825f97d3-91e6-4be2-8faa-86842daaa297)
<h1>Creating and Configuring a virtual machine and then using Remote Desktop (Azure)</h1>
This tutorial showcases the implementation of Azure Virtual Machines and how to connect to them using remote desktop.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop
- Windows App (for macOS)


<h2>Operating Systems Used </h2>

- macOS Sequoia
- Windows 10 (21H2)



<h2>Deployment and Configuration Steps</h2>
<h2>Creating our Virtual Machine</h2>


1. Visit Azure
- Go to azure.microsoft.com.

2. Sign Up for a Free Account
- Sign up for a free 30-day subscription.
- Create a username and password for your tenant.
- Access the portal anytime at portal.azure.com using your credentials.
<img width="1253" height="624" alt="screenshot 1" src="https://github.com/user-attachments/assets/0c9b8e35-d215-4444-bc39-cd60969300b4" />





3. Create a Resource Group
- Click on "Resource Group" and then click "Create".
<img width="1253" height="624" alt="screen 2" src="https://github.com/user-attachments/assets/a64765a9-0e97-43e0-bdee-13f0b1ce66d9" />
<img width="1253" height="624" alt="screen 3" src="https://github.com/user-attachments/assets/c0451b53-ec66-402c-96c8-7e33afb91e5a" />


- Enter a desired name for your resource group.
- Under "Resource Details," choose your desired region.
- Click "Review + Create." After validation, click "Create" to set up the resource group.
<img width="671" height="297" alt="Screenshot 2025-08-15 at 11 23 55 PM" src="https://github.com/user-attachments/assets/32e0fc37-d690-4232-8db3-4213a2c11c1d" />





4. Create a Virtual Machine
- In the Home page, click "Virtual Machines."
<img width="1296" height="647" alt="Screenshot 2025-08-15 at 11 25 50 PM" src="https://github.com/user-attachments/assets/4d7e73da-1d2f-4478-b634-ebf5295228e2" />


- Click "Create," then select "Virtual Machine."
<img width="1296" height="647" alt="Screenshot 2025-08-15 at 11 27 09 PM" src="https://github.com/user-attachments/assets/72df7374-c754-4d46-a0e3-061bd8819566" />


- Select your Azure Subscription and the Resource Group you recently created.
- Name your Virtual Machine as you see fit.
- Choose the same region as your resource group.
<img width="1296" height="647" alt="Screenshot 2025-08-15 at 11 42 36 PM" src="https://github.com/user-attachments/assets/da50bf99-18e2-4363-b5ef-10a8a9d7a534" />


- Select your desired Operating System under "Image." (windows 10 Pro N, Version 22h2 x64 Gen 2)
- Pick the desired Size for your virtual CPU.(Standard D2s_v6 - 2 vcpus, 8 GiB memory)
- Create a username and password for the Administrator account.
- Check the licensing box.
Click "Review + Create." After validation, click "Create." This may take a few minutes.
<img width="1296" height="647" alt="Screenshot 2025-08-15 at 11 42 36 PM" src="https://github.com/user-attachments/assets/54fc8aee-5288-4951-bc0b-c3ab434f52ab" />
<img width="1296" height="647" alt="Screenshot 2025-08-15 at 11 45 01 PM" src="https://github.com/user-attachments/assets/451cbc2e-a628-4295-86af-99b59a627769" />
<img width="1296" height="647" alt="Screenshot 2025-08-15 at 11 46 27 PM" src="https://github.com/user-attachments/assets/6c2b697a-b8b2-4178-8d61-a6aaaa936499" />
<img width="1296" height="647" alt="Screenshot 2025-08-15 at 11 47 27 PM" src="https://github.com/user-attachments/assets/a2d6321b-846a-4ca2-9775-37a4b1f1f57c" />




- Once deployment is finished, congratulations on creating your Virtual Machine!
<img width="1296" height="647" alt="Screenshot 2025-08-15 at 11 49 59 PM" src="https://github.com/user-attachments/assets/5855700f-a2e2-4f7f-9b6c-0faef7ebfc14" />

 
 <h2>Remote access</h2>


1. Access Your Virtual Machine
- After deployment is completed, click "Go to resource"
- Notice the Public IP Address displayed.
<img width="1293" height="648" alt="Screenshot 2025-08-15 at 11 56 00 PM" src="https://github.com/user-attachments/assets/32ba03d5-05ee-44df-84e7-386ba8812c0e" />





2. Since we're using a Mac:
- Use "Windows app" to remotely access the VM we just created.
- On the top left corner, click "+" and then "Add PC"
- Enter the public IP address under "PC Name."
- Enter the name for your VM under "Friendly name."
<img width="1293" height="751" alt="Screenshot 2025-08-16 at 12 01 40 AM" src="https://github.com/user-attachments/assets/982d65e3-45ff-44de-b224-3fbe1c857566" />



- Under "Saved PC," click on the VM you just added and enter the VM's username and password.
- Click continue.
<img width="505" height="246" alt="Screenshot 2025-08-16 at 12 05 41 AM" src="https://github.com/user-attachments/assets/9c4eded5-4a81-49a3-a7f5-8bf678264c99" />


4. Connecting to Your VM
<img width="1294" height="837" alt="Screenshot 2025-08-16 at 12 07 02 AM" src="https://github.com/user-attachments/assets/4e792944-3493-4f47-9c68-daa852ff5f32" />
<img width="1294" height="837" alt="Screenshot 2025-08-16 at 12 07 34 AM" src="https://github.com/user-attachments/assets/3c4bbe41-6c97-4aa3-b0bf-1f903041268b" />


<h2>Conclusion</h2>
This concludes our tutorial showcasing how to create a Virtual Machine in Azure and how to properly connect to it using Remote Desktop (Windows App for macOS users)



