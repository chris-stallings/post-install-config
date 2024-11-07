<p align="center">
<img width="699" alt="Screenshot 2024-11-07 at 11 36 30 AM" src="https://github.com/user-attachments/assets/025e7145-fc14-4a54-a4dc-f80e6f45199c">
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2> -->

<!-- - ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles for grouping permissions
- Create a new Department
- Create a new Team
- Configure Agents
- Create Users
- Configure SLA
- Create Help Topics for users to categorize their issues

<h2>Configuration Steps</h2>

<p>
<img width="1710" alt="Screenshot 2024-11-07 at 12 05 41 PM" src="https://github.com/user-attachments/assets/4138500c-4022-44a6-85e9-7388ccc508d6">
</p>
<p>
Log into the admin panel of osTicket. 
</p>
<br />

<p>
<img width="1710" alt="Screenshot 2024-11-07 at 12 34 36 PM" src="https://github.com/user-attachments/assets/5d1feaba-380c-42fc-a052-886c79cf3744">
</p>
<p>
Once logged in navigate to the roles tab by clicking on Agents then Roles. 
</p>
<br />

<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 12 56 35 PM" src="https://github.com/user-attachments/assets/8af6b61b-6dfa-40a9-abff-fe6c3e9b7ffd">
</p>

- Click add a new role. 
- Name will be Supreme Admin
- Go to the permissions tab and make sure everything is checked.  
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 1 04 41 PM" src="https://github.com/user-attachments/assets/e8a01d51-17b6-4c45-9c40-3887ee80727c">
</p>
<p>Click create role and this will give us the new role. </p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 1 20 41 PM" src="https://github.com/user-attachments/assets/49486b87-246e-42d5-8aea-692abec9a857">
</p>
<p>Now we will configure the departments. </p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 2 55 37 PM" src="https://github.com/user-attachments/assets/b67f18e0-e316-4ae7-95b1-e2482d4e8b25">
</p>
<p>Click add new department. Create a top level department. The name will be SysAdmins. Leave everything else default.</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 3 18 26 PM" src="https://github.com/user-attachments/assets/3d96a32b-8d82-4237-919a-a21347ebdd60">
</p>
<p>
  Next we will create a new team. We will call this team Online Banking. Leave all other options default. 
</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 3 32 17 PM" src="https://github.com/user-attachments/assets/eb2f0979-f711-4abb-a0fa-ac454507b9fe">
</p>
<p>We will create a user Jane Doe. Make sure to set the password as something you will remember. Set Jane as a Supreme Admin in the SysAdmin department. These options are on the access tab. Finally go to the teams </p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 4 18 35 PM" src="https://github.com/user-attachments/assets/100e2b6d-3786-42a0-9b27-317588e2ec01">
</p>
<p>Next we will create the user John Doe. Set his password as something you will remember. Set John as a view only in the Support department. Everything else will be left as default.</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 4 28 21 PM" src="https://github.com/user-attachments/assets/8ccf239c-74d5-4e34-bdce-cd93b136f46c">
</p>
<p>
  Next we will move to the agent panel. We are going to create a user. 
</p>
<br />
<p><img width="1710" alt="Screenshot 2024-11-07 at 4 42 55 PM" src="https://github.com/user-attachments/assets/2ed5ca64-5be6-4b14-9d88-652fd331843f">
</p>
<p>We will create two users. One named Karen and one named Ken.</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 5 21 42 PM" src="https://github.com/user-attachments/assets/13e0403a-9cd0-42c5-bd8f-a488c8067ebb">
</p>
<p>
  Now we will create 3 different SLA. To do this go back to the admin panel. Then go to the manage tab. Now go to the SLA tab. We will create 3 SLA with the rules below:
</p>

- Sev-A (Grace Period: 1 hour, Schedule: 24/7)
- Sev-B (Grace Period: 4 hours, Schedule: 24/7)
- Sev-C (Grace Period: 8 hours, Business Hours)
<p>
  <img width="1710" alt="Screenshot 2024-11-07 at 5 51 43 PM" src="https://github.com/user-attachments/assets/cd94de84-8151-4516-a29f-11eeabbf8102">
</p>
<p>Now we will create 5 help topics to give users options when making help tickets. </p>

- Business Critical Outage (Report a Problem)
- Personal Computer Issue (Report A Problem)
- Equipment Request (General Inquiry)
- Password Reset (Report A Problem)
- Other (General Inquiry)

<br />
<p>This concludes the post installation setup. Now you are ready to submit and work tickets.</p>
