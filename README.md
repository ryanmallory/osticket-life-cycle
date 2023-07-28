<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Life Cycle: Intake Through Resolution</h1>
In the previous lab, I set up osTicket (help desk ticketing system) by creating creating user and employee accounts, teams, departments, SLAs, permissions, and help topics. In this lab, I'll use those existing attributes as I create 2 help desk tickets and walk you through the process of working and resolving a ticket.<br />

<h2>Technologies Used</h2>

- VMWare Workstation (Virtual Machine)
- osTicket (Help Desk Ticketing Software)
- Internet Information Services (IIS)

<h2>Operating System Used </h2>

- Windows 10 Pro

<h2>Ticket Life Cycle Stages</h2>

- Intake
- Assignment
- Working the Issue
- Resolution

<h2>Life Cycle Stages</h2>

<p>
<img src="https://i.imgur.com/qB474bL.jpg" height="90%" width="90%"/>
</p>
<p>
Browsing to localhost/osTicket takes you to osTicket's Support Center. This is where end-users can create tickets which will be sent to the help desk staff. I'll create 2 tickets, and afterwards I'll login with an agent account (Jane Doe) in order to access them.
</p>
<br />

<h2>Stage 1: Intake</h2>

<p>
<img src="https://i.imgur.com/Kim1ehB.jpg" height="49%" width="49%"/> <img src="https://i.imgur.com/1K2qdIZ.jpg" height="49%" width="49%"/>
</p>
<p>
This is the stage when a new ticket is created. Two common ways in which tickets can be submitted is through a form – such as the one shown here – or by sending an email to an email address that is designated to receive tickets. In this form, the users provide their contact information, select a Help Topic, and provide details about the issue. 
</p>
<br />

<h2>Stage 2: Assignment</h2>

<p>
<img src="https://i.imgur.com/rHe0ujl.jpg" height="49%" width="49%"/> <img src="https://i.imgur.com/xjUsdHZ.jpg" height="49%" width="49%"/>
</p>
<p>
After a ticket has been submitted, the ticket can be assigned to an IT professional. In order for the ticket to be handled properly, information regarding the level of severity can be changed. For Ticket A, the priority was changed to “Emergency”, the SLA plan was changed to “SEV-1”, and the Department was changed to “System Administrators”. The ticket was also assigned to “Jane Doe”, who is an administrator in this scenario. 

For Ticket B, the priority was changed to "high", the SLA plan was changed to "SEV-1", and the Department was changed to "Support". This ticket was assigned to "John Doe", a Level I support professional.
</p>
<br />

<h2>Stage 3: Working the Issue</h2>

<p>
<img src="https://i.imgur.com/N5NRov0.jpg" height="49%" width="49%"/> <img src="https://i.imgur.com/OZSjfEJ.jpg" height="49%" width="49%"/>
</p>
<p>
Now that the tickets have been assigned to the appropriate departments and agents, the IT staff can work on finding solutions to the issues. Each time a change is made to the ticket or there is an update to the situation, a comment can be made in the Ticket Thread. This allows everyone viewing the ticket to be aware of what has already happened and facilitates communication between everyone involved.
</p>
<br />

<h2>Stage 4: Resolution</h2>

<p>
<img src="https://i.imgur.com/TgzC9JE.jpg" height="90%" width="90%"/>
<p>
Once the issue has been resolved, the ticket can be closed. In the osTicket system, the ticket will move from the Open section to the Closed section in this stage. For IT professionals, it is important to know where to find closed tickets since they can be browsed and used to find solutions to open tickets.
</p>
<br />
