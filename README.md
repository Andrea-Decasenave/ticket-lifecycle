<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution as an end user within the open-source help desk ticketing system osTicket. To continue with this lab you should have alredy gone through " post instaltion and cofiguration". <br />



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
  
   <h2>Intake</h2>
  - Copy and paste this end user log in link in to the browser of your virtual machine http://localhost/osTicket/ (this is what we will use to create a ticket)
  
  - Click on **Open a New Ticket** there you will login as one of the users we created in the previous lab (Karen and Ken).
 
  - You fill out in their full name and email ( remember we wrote these down on notepad) as well as select a topic **Bussines Critial Outage** and provide a summary of your problem like I did belowand detials.
  
  - Once youre done just click **Create Ticket** at the bottom
       
  ![image](https://github.com/Andrea-Decasenave/ticket-lifecycle/assets/150068516/aaecf06d-83fd-455d-a81c-a71a48c55567)
  
- Make one more for Karen Select the topic **General Inquiry** and write in the summary "When are we getting a new hardware reset" 
- Repeat the same proccess for your other user "Ken" but this time choose the Help Topic **Personal Computer Issues** and write this in summary "entire accounting dept adobe reader not working" and in details "Ever since the upgrade lastnight, no one has been able to access adobe reader.

  
<h2>Assignment and Communication</h2>

- Use the Help desk Log in:http://localhost/osTicket/scp/login.php link and log in as Jane (Remember we wrote down her credentials in notepad) and make sure you are in the admin panel
- Once in admin panel click on the **Tickets** tab and click on the **entire mobile backing is down** ticket
   - This is Business critical event that could potentially cause loss of money to the company so we are going to change its priority to do this click on priority at the top and change it to **Emergency** and in the notes write " Business Impacting Event" then click update
- Click next to **Assign to** and assign the ticket to **Jane** since she is ssupreme admin of the support team.
- Click next to **Department** and change it to **Supreme Admin** since Jane is assigned to it and in the notes write "Sys Admins reposible for mobile banking infastruture"
- Then click next to **SLA Plan** and set the plan to **SEV-A** since it is a emergancy and has to be reolved as soon as possible. Write Critical incident in the text box undrneath and clikc update
- Finally in the text box under **Response** write "Coordinating wiht Sys Admin to bring online banking back online" then click post reply

![image](https://github.com/Andrea-Decasenave/ticket-lifecycle/assets/150068516/43fd6e92-ca29-42bf-a68c-c99f20fc271e)

  Now we are going to work on Kens ticket
  - click on "entire accounting dept adobe reader not working"  and set the priority to high since it encludes and entrie dept and not just one person
  - The clikc next to **Assign to** and assign it to **John**
  - Set the SLA plan to SEV-B and in the text box under Responce write "Re-assigned to SEV-B, reached out to John for warm hand"
  - Finally click **Post Reply**
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
