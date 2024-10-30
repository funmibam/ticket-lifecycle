# osTicket Lab Exercise

This lab exercise involves creating, observing, and completing tickets within the osTicket system, both as an end-user and as a help desk agent. This project will help me develop essential ticket management skills for a help desk or IT support role.

## Access URLs

- **Admin/Analyst Login Page:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End Users osTicket URL:** [http://localhost/osTicket](http://localhost/osTicket)

---

## Lab Overview

In this lab, I created:

- Create tickets as an end-user.
- Observe and manage ticket properties as a help desk agent.
- Work through ticketing scenarios to completion.
- Explore osTicket system features, including role management, SLAs, and department configuration.

---

## Configuration Tasks

### 1. Update Department Settings

- Change the **SysAdmins Department** to a **Top Level Department**.
- **DELETE** the Maintenance Department (instead of archiving it).

### Screenshot: Update Department Settings
<img width="718" alt="image" src="https://github.com/user-attachments/assets/a5bc362b-a73b-4a9a-93af-6c1a4152c4c7">



---

## Ticket Scenarios

### Scenario 1: Mobile/Online Banking System Down

1. **As an End User**, create a ticket with the following description:  
   - **Issue**: "Entire mobile/online banking system is down."

2. **As a Help Desk Agent (John)**, observe the ticket's properties:
   - **Priority**: Default
   - **Department**: SysAdmins
   - **SLA**: Default
   - **Assigned To**: Unassigned

### Screenshot: End-User Ticket Creation

<img width="635" alt="image" src="https://github.com/user-attachments/assets/7a80f15e-8349-4cd7-82ce-21ff0a51939e">




3. **Set Properties for the Ticket**:
   - **SLA**: Sev-A (1 hour, 24/7)
   - **Department**: Online Banking Department

### Screenshot: Setting Ticket Properties
<img width="720" alt="image" src="https://github.com/user-attachments/assets/dfa21441-4aba-484f-8b1e-756dd469dbfc">


<img width="727" alt="image" src="https://github.com/user-attachments/assets/0baf6af9-ebbe-4042-9a80-1c096a57d9fa">


4. **As John**, attempt to view or change the ticket after setting properties. Note whether you have access.

5. **As Jane**, work the ticket to completion.

---

### Scenario 2: Accounting Department Needs Adobe Upgrade

1. **As an End User**, create a ticket with the following description:  
   - **Issue**: "Accounting department needs Adobe upgrade, broken."

2. **As a Help Desk Agent (John)**, observe the ticket's properties:
   - **Priority**: Default
   - **Department**: Accounting
   - **SLA**: Default
   - **Assigned To**: Unassigned

3. **Set Properties for the Ticket**:
   - **SLA**: Sev-B (4 hours, 24/7)
   - **Department**: Support

### Screenshot: Help Desk Agent Observing Ticket Properties

<img width="722" alt="image" src="https://github.com/user-attachments/assets/432d6cfd-49aa-44ac-bdfd-80b2260efc99">

4. **As John**, work the ticket to completion.

---

### Scenario 3: CFO’s Laptop Will No Longer Turn On

1. **As an End User**, create a ticket with the following description:  
   - **Issue**: "CFO’s laptop will no longer turn on."

2. **As a Help Desk Agent (John)**, observe the ticket's properties:
   - **Priority**: Default
   - **Department**: Support
   - **SLA**: Default
   - **Assigned To**: Unassigned

### Screenshot: End-User Ticket Creation for CFO Laptop

<img width="635" alt="image" src="https://github.com/user-attachments/assets/4a543975-7d8d-4d0a-90bf-fb7df53f1dab">

3. **Set Properties for the Ticket**:
   - **SLA**: Sev-B (4 hours, 24/7)
   - **Department**: Support

4. **As John**, work the ticket to completion.

---

## Managing Escalated Tickets

1. **Set Properties** to all the tickets. Assign **SEV-A** for the SysAdmins ticket last. 
2. Observe that the ticket becomes **inaccessible** after setting SEV-A.
3. Switch to the **Admin Panel** and assign yourself view access to SysAdmins.
4. Switch back to the **Agent Panel** and observe the **escalated ticket**.
5. Note that you can no longer make changes to this ticket.

### Screenshot: Escalated Ticket
<img width="707" alt="image" src="https://github.com/user-attachments/assets/e6f1b76e-b8b5-42a3-9cf2-4bc08c1c80c0">


---

## Final Steps and Observations

1. **Solve all of the tickets**.
2. Discuss the **email feature**:
   - In most ticketing systems, including osTicket, there’s an email notification feature. Each time a ticket is updated, the user is notified, and they can respond via email.
3. **Real-Life Ticket Intake**:
   - Tickets are often created through various channels like phone, chat, email, web forms, or in-person requests. It’s important to document everything you work on for accurate metrics and reporting.
   - Even if you resolve an issue on the spot, make sure to create a ticket for it.

### Screenshot: Ticket Resolution
<img width="718" alt="image" src="https://github.com/user-attachments/assets/80da9995-fb3c-49c4-a4b5-8e9ce53ae527">


---

## Additional Practice

This lab covers only a portion of osTicket's capabilities. You are encouraged to explore the system further, especially the email feature. Try repeating the lab steps multiple times to build intuition.

---

## Key Skills Developed

This lab will help build your proficiency in:
- **Technical Ability**: Understanding osTicket’s ticketing workflow and configuration.
- **Problem Solving**: Using ticket properties like SLAs, departments, and priority to manage and complete tickets efficiently.



 
