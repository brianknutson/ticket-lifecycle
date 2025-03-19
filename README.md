<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/lDMGnBg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/FEhK3Zu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1 - The beginning of a ticket lifecycle is the creation of the ticket. Let's create a ticket. To create a ticket with osTicket, go to the webpage http://localhost/osTicket. Then click on "Open New Ticket". In this example, the person who is creating a ticket is Karen Doe. She choose the "Help Topic" called "Report a Problem/Business Critical Outage" since the online banking system is down. Once the neccessary information is filled in, click on "Create Ticket". 
</p>
<br />

<p>
<img src="https://i.imgur.com/HobCyxn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/gWT322K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/OdXmOTw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2 - The next stage of a ticket lifecycle is the assigment and communicaiton phase. In this phase, a help desk agent called John will assign the ticket to the appropriate department, so the ticket can be finish to completion. To assign a ticket, go to the webpage http://localhost/osTicket/scp/login.php. Then login. Next go to "Tickets" then click on the recent ticket created by Karen Doe. With some tickets, you may want to communicate with the person who created the ticket to get further insights as to what is going on and if the problem is still persisting. In this example, the "SLA Plan" will be set to "Sev-A" because there is a wide impacted on the online banking affecting most users. Once the info is filled in, click on "Update Plan". Next is to assign the ticket. Click on "— Unassigned —". The "Assignee" will be "Online Banking" since it is the online banking that is being affected. Now login off, and sign into Jane who is on the online banking team.     
</p>
<br />

<p>
<img src="https://i.imgur.com/NQenpkK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/yxcbQ1w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3 - The next stage of a ticket lifecycle is working the issue. In this stage, Jane Doe who is a part of the online banking team will be working through this ticket. Like before, go to "Tickets" then click on the rencet ticket created by Karen Doe. Jane decides to work on this ticket herself, so she clicks on the "Online Banking" next to the "Assigned To". Then she assigns the ticket to herself. With osTickets you can make updates with other agents through "Post a Reply". Karen believes the issue could stem from the recent updates to the online banking system, so she posted a reply relaying this belief. After working through the issue, Karen determined that the root cause of the issue was the recent update to the online banking system. She rolled back the update, making the online banking system up and running. Then she nofitied the vendor. Karen made another post explaining this situation. 
</p>
<br />

<p>
<img src="https://i.imgur.com/cvkLlAG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/H4eBbHE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4 - The final stage of a ticket lifecycle is resolution. Since the online banking system is up and running, Karen clicked on "Open" next to "Status" to set the status as resolved. Once, the status has been set to resolved, the ticket should now not be seen in the ticketing menu. However, certain permissions can allow certain agents to see the resolved ticket. 
</p>
<br />
