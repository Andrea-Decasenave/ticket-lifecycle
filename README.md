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
  
- Make one more for Karen Select the topic **General Inquiry** and write in the summary "When are we getting a new hardware reset" and in details write "Moast of my department is having issues wiht thei current tablets, we need this ASAP,PLease provide info" 
- Repeat the same proccess for your other user "Ken" but this time choose the Help Topic **Personal Computer Issues** and write this in summary "entire accounting dept adobe reader not working" and in details "Ever since the upgrade lastnight, no one has been able to access adobe reader.

  
<h2>Assignment,Communication and Resoution</h2>

- Use the Help desk Log in:http://localhost/osTicket/scp/login.php link and log in as Jane (Remember we wrote down her credentials in notepad) and make sure you are in the admin panel
- Once in admin panel click on the **Tickets** tab and click on the **entire mobile backing is down** ticket
   - This is Business critical event that could potentially cause loss of money to the company so we are going to change its priority to do this click on priority at the top and change it to **Emergency** and in the notes write " Business Impacting Event" then click update
- Click next to **Assign to** and assign the ticket to **Jane** since she is ssupreme admin of the support team.
- Click next to **Department** and change it to **Supreme Admin** since Jane is assigned to it and in the notes write "Sys Admins reposible for mobile banking infastruture"
- Then click next to **SLA Plan** and set the plan to **SEV-A** since it is a emergancy and has to be reolved as soon as possible. Write Critical incident in the text box undrneath and clikc update
- Finally in the text box under **Response** write "Coordinating wiht Sys Admin to bring online banking back online" then click post reply

![image](https://github.com/Andrea-Decasenave/ticket-lifecycle/assets/150068516/43fd6e92-ca29-42bf-a68c-c99f20fc271e)

  Now we are going to work on Kens ticket
  - click on "entire accounting dept adobe reader not working"  and set the priority to high since it includes an entrie dept and not just one person
  - The clikc next to **Assign to** and assign it to **John**
  - Set the SLA plan to SEV-B and in the text box under Responce write "Re-assigned to SEV-B, reached out to John for warm hand off"
  - Finally click **Post Reply**
![image](https://github.com/Andrea-Decasenave/ticket-lifecycle/assets/150068516/1b814dd2-e680-4dcf-b07e-23a7801c1bad)
![image](https://github.com/Andrea-Decasenave/ticket-lifecycle/assets/150068516/5f8951f2-5ba7-4404-b60c-26dff9d65cb6)


  
  
  
  
  
  For Karen's second ticket "when are we getting a new hardware refresh" set the **Priority** to low then Set the **Assign to** Jane doe
- Set the **SLA** paln to SEV-C since its not and urget matter
- Then at the bottom wirte "Hardware refresh is slated for Q1. If you like you and your dept can start testing the new units today.just shoot me an email." change the ticket status to **resolved** and post the reply
![image](https://github.com/Andrea-Decasenave/ticket-lifecycle/assets/150068516/2887c2e4-9ee9-47ce-9df0-43843a7e966e)
![image](https://github.com/Andrea-Decasenave/ticket-lifecycle/assets/150068516/c19e9539-985c-42ce-97f6-f303f2009469)



Now we are going to solve the ticket we assign to John doe

- Log out of OsTicket and log in as john doe(we wrote the username and password on notepad app)
- Once logged in go to the tickets tab where the tickets should appear
- in  the details write " Rolled back version of Adobe reader to previous version allowing them to work in mean time, I will reasearch why the new version doesn't work on the accounting departments hardware"
- Change the ticket status to **Resolved** then Post Reply


<h2>Clean up</h2>
- Go to azure portal and make sure to delete botht the Resource group and the Virtual machine and then you are done
  

