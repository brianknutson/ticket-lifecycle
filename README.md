<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This demonstration outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



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

Step 1
------
The beginning of a ticket lifecycle is the creation of the ticket. To create a ticket with osTicket, I went to the webpage http://localhost/osTicket. Then I clicked on "Open New Ticket".
In this example, the person who is creating the ticket is Karen Doe. She chose the "Help Topic" called "Report a Problem/Business Critical Outage" since the online banking system is down. Once the necessary information was filled in, she clicked on "Create Ticket".

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/1.1.PNG)

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/1.2.PNG)

Step 2
------
The next stage of a ticket lifecycle is the assignment and communication phase. In this phase, a help desk agent called John will assign the ticket to the appropriate department, so the ticket can be completed. To assign a ticket, he went to the webpage http://localhost/osTicket/scp/login.php. Then he logged in. 

Next, he went to "Tickets" and then clicked on the recent ticket created by Karen Doe. With some tickets, you may want to communicate with the person who created the ticket to get further insights as to what is going on and if the problem is persisting. In this example, the "SLA Plan" will be set to "Sev-A" because there is a wide impact on online banking, affecting most users. Once the info was filled in, he clicked on "Update Plan". 

Next, he assigned the ticket. He clicked on "— Unassigned —". The "Assignee" was to be "Online Banking" since the online banking system is affected. 

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/2.1.PNG)

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/2.2.PNG)

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/2.3.PNG)

Step 3
------
The next stage of a ticket lifecycle is working on the issue. At this stage, Jane Doe, who is a part of the online banking team, worked through this ticket. Like before, she went to "Tickets" and then clicked on the recent ticket created by Karen Doe. 

Jane decides to work on this ticket herself, so she clicks on the "Online Banking" next to the "Assigned To". Then she assigns the ticket to herself. With osTicket, you can make updates with other agents through "Post a Reply".

Karen believes the issue could stem from the recent updates to the online banking system, so she posted a reply relaying this belief. After working through the issue, Karen determined that the root cause of the issue was the recent update to the online banking system. She rolled back the update, getting the online banking system up and running. Then she notified the vendor. Karen made another post explaining this situation. 

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/3.1.PNG)

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/3.2.PNG)

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/3.3.PNG)

Step 4
------
The final stage of a ticket lifecycle is resolution. Since the online banking system is running, Karen clicked on "Open" next to "Status" to set the status as resolved.

Once the status has been set to resolved, the ticket will no longer be seen in the ticketing menu. However, certain permissions can allow certain agents to see the resolved ticket. 

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/4.1.PNG)

![image alt](https://github.com/brianknutson/ticket-lifecycle/blob/e2cf5ed9a6604198e07ad530fd47aefb6e2d5d5b/4.2.PNG)
