<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://github.com/user-attachments/assets/cd9da2eb-9697-4d68-8099-f391afdf107f"/>
</p>
<p>
First, we will intake each ticket and assess the priority of each ticket.  
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/4a240d0c-34ee-49d9-aae5-2554c2e722e2"/>
</p>
<p>
Each ticket needs the appropriate Service Level Agreement (SLA) selected based on the severity of the ticket. In the provided example, we will set this to Emergency priority with a SEV-A (1 hour, 24/7) SLA due to the ticket being a business impacting event, and then assign the ticket to the appropriate staff member. We can also assign the ticket to a differnet department if warranted.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/d408aaab-9d9a-40a9-a15e-1ef34906a06b"/>
</p>
<p>
In this case, we will coordinate with the System Administrators department and work to resolve the issue making sure to add notes to the orginal ticket.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/bf8d126e-220a-407f-99da-4d73a0f6e694"/>
</p>
<p>
Once the issue has been solved, we will add a note explaing that the issues has been corrected and resolve the ticket.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/63c9d2d8-0c81-46f2-9fa3-0fac00631ca7"/> <img src="https://github.com/user-attachments/assets/80d53742-7724-4828-9fc3-ab7f27462df4"/>
</p>
<p>
Depending on the nature of the ticket, it may require a lesser SLA/priority. Tickets that may be impacting an entire department may not be considered an emergency, but would still be high priority and may require SEV-B SLA (4 hours, 24/7). Another example would be tickets relating to hardware refreshed, where the priority would be low/normal with a SEV-C SLA (8 hours, business hours).
</p>
<br />

<p>
Note: When working and resolving tickets, it is vital to maintain communication with the end user that created the ticket. Letting the user know what the status of the ticket is and acknowledging what the issue was when resolving.
</p>
