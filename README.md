<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Configuration Steps</h2>

<p>

![Screenshot 2024-11-13 210238](https://github.com/user-attachments/assets/32326268-00ed-4467-a233-6e6894af873f)

![Screenshot 2024-11-13 210304](https://github.com/user-attachments/assets/4329f9c8-5d5c-4ee9-b476-1c4fb80f056a)

</p>
<p>
Configure Roles (for grouping permissions)

Admin Panel -> Agents -> Roles

  -Supreme Admin

</p>
<br />

<p>

![Screenshot 2024-11-13 210514](https://github.com/user-attachments/assets/9f2a8554-60ba-40cc-995f-c53ccd0412bc)

</p>
<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)

Admin Panel -> Agents -> Departments

SysAdmins

</p>
<br />

<p>

![Screenshot 2024-11-13 210955](https://github.com/user-attachments/assets/29e2501c-fefa-49b1-936b-41d5cd3d0f66)

</p>
<p>
Configure Teams

Admin Panel -> Agents -> Teams (Pull Agents from different Departments)

Online Banking

</p>
<br />
<p>

![Screenshot 2024-11-13 211148](https://github.com/user-attachments/assets/23bd5091-cb28-4a54-b565-e28f5638b8e9)

</p>
<p>
Allow anyone to create tickets

Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)

Registration Required: Require registration and login to create tickets

</p>
<br />

<p>

![Screenshot 2024-11-13 211456](https://github.com/user-attachments/assets/558a507d-3880-4898-9afd-c586746e9bda)

</p>
<p>
Configure Agents (workers)

Admin Panel -> Agents -> Add New

Jane (Dept: SysAdmins)

John (Dept: Support)

</p>
<br />

<p>

![Screenshot 2024-11-13 211834](https://github.com/user-attachments/assets/f64a3a12-e3ad-4200-bb4c-50eb596e6a4f)

</p>
<p>
Configure Users (customers)

Agent Panel -> Users -> Add New

Karen

Ken

</p>
<br />
<p>

![Screenshot 2024-11-13 212031](https://github.com/user-attachments/assets/209ff13f-4294-4578-b7bb-bb085f522724)

</p>
<p>
Configure SLA

Admin Panel -> Manage -> SLA

Sev-A (Grace Period: 1 hour, Schedule: 24/7)

Sev-B (Grace Period: 4 hours, Schedule: 24/7)

Sev-C (Grace Period: 8 hours, Business Hours)

</p>
<br />

<p>

![Screenshot 2024-11-13 212205](https://github.com/user-attachments/assets/0a71c16c-e535-44a3-94e5-0c73e3a3078f)

</p>
<p>
Configure Help Topics (For when users create a ticket)

Admin Panel -> Manage -> Help Topics

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset

Other

</p>
<br />

<p>
