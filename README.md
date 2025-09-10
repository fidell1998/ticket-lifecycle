<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. This specific guide is designed for a broad audience, from non-technical users to IT professionals, making it accessible regardless of your technical background. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- **Windows 10** used for installing and configuring osTicket

A Windows 10 virtual machine was created using **Microsoft Azure**, with **macOS** as the host system.

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Intake</h3>

Navigate to the ticket submission page by entering the following URL in your browser: localhost/osticket/

Click on **"Open a New Ticket"** to begin the process.

<img width="1920" height="1004" alt="1" src="https://github.com/user-attachments/assets/35200000-ee4c-4134-86df-1821919cb144" />

Fill out the ticket form using the test user account created in the previous guide: *"osTicket - Post-Install Configuration."*

Ensure the following fields are completed:

- **Help Topic**
- **Issue Summary**
- **Message (Description)**

Once the form is filled out, click **"Create Ticket"** to submit.

<img width="934" height="964" alt="2" src="https://github.com/user-attachments/assets/ffa6c5ea-2aaa-4dbe-b301-3a59aaa607f0" />

Log in as the **Admin user** to view the newly submitted ticket in the ticket queue.

<img width="1002" height="446" alt="3" src="https://github.com/user-attachments/assets/91ae9dcd-02cb-47d5-b80a-909931b3fdc2" />

Next, log out from the Admin account and log in as the **Agent** created in the previous guide.  
In this example, we’re using the agent account for **Spider-Man**. The ticket should be visible in the agent's dashboard as well.

<img width="1010" height="445" alt="4" src="https://github.com/user-attachments/assets/02733833-d4c3-4b52-ac2d-c3457d51cf9e" />

> **Note:**  
> If the ticket is not visible under the agent account, refer to the final step of the previous guide: *"osTicket - Post-Install Configuration."*  
> This issue is often caused by the agent not being assigned to the correct **Department**, **Team**, or not having sufficient **access permissions**.

<br>

<h3>Assignment and Communication</h3>

Click the ticket to open it.

<img width="973" height="647" alt="5" src="https://github.com/user-attachments/assets/72ae7fa0-93e1-4709-b57b-4d98a26f5664" />

Once opened, you’ll be able to view all backend details associated with the ticket.  
Because the agent account (e.g., Spider-Man) has full access, you have the ability to:

- Update the **Priority**
- Change the **Department**
- Reassign the ticket to another **Agent or Team**
- Modify the **SLA Plan**

These administrative options help in managing the ticket's workflow effectively.

<img width="1005" height="310" alt="6" src="https://github.com/user-attachments/assets/e6a009db-5620-48ca-a74c-cba037a4f7a8" />

<br>

<h3>Working the Issue</h3>

<img width="958" height="259" alt="7" src="https://github.com/user-attachments/assets/d3e360f3-de64-4009-8298-26bf61766fef" />

<img width="1024" height="380" alt="8" src="https://github.com/user-attachments/assets/918b8f0c-6ca3-435b-9889-34ba127bba39" />

<br>

<h3> Resolution </h3>

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

<br>
