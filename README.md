
# osTicket Tickets and Ticket Lifecycle


---
---
<br />


<h2>Create A Support Ticket As An End-User</h2>

- Visit the User Portal at this local address in the browser: `https://http://localhost/osTicket/`
- Log in with the User account [we created in the osTicket Post-Installation Setup at this link.](https://github.com/ian-bates-it/osticket-post-installation-setup?tab=readme-ov-file#add-new-user)
    - In my example, I created a user named `karen`.
 
  
- On the **Support Center** homepage (`https://http://localhost/osTicket/`), click the `Open a New Ticket` button as shown below.


  <img src="https://github.com/user-attachments/assets/fb83128d-3126-4297-b853-e53e0aba804b" height="50%" width="50%" />


<br />
<br />

---

<h3>Open A New Ticket Form</h3>

- I will enter the osTicker User `Karen Doe` which [I created in the post-installation setup inside of osTicket at this link here.](https://github.com/ian-bates-it/osticket-post-installation-setup?tab=readme-ov-file#add-new-user)

- An osTicket User must have a full name and email address which I entered as shown below.

![image](https://github.com/user-attachments/assets/7dc1ac62-c063-496c-b34b-9b511c7bc38d)



<br />

<h3>Select A Help Topic</h3>

- Karen’s issue will be that the entire mobile online banking system is down.
- The appropriate `Help Topic` would be `Business Critical Outage`, but we will instead select the more generic topic of `Report a Problem`.
- A lot of the time, the end-user won’t select the correct category/Help Topic.
    - So we are deliberately selecting a category that does not quite match the issue to replicate a typical end-user.

![image](https://github.com/user-attachments/assets/4ac62f93-6a50-486f-81e8-8ec3970c3265)



<br />
<h4>Full Image</h4>
  <img src="https://github.com/user-attachments/assets/aadacf49-8251-4e41-87ee-09d42b4512e8" height="50%" width="50%" />



<br />
<br />

---

<h3>New Ticket Issue Summary and Details</h3>

- Below I attempted to provide an issue summary and description that an end-user might provide regarding a website being unreachable.
- Then press the `Create Ticket` button to submit this ticket into the queue.

  <img src="https://github.com/user-attachments/assets/70547fb1-a272-4900-b7cf-8a383fb455c3" height="60%" width="60%" />

<br />
<br />

<h3>User Ticket Confirmation</h3>

- Confirmation that Karen Doe's ticket was successfully submitted on her end:

  ![image](https://github.com/user-attachments/assets/3ac2e0b7-7a21-4379-88f2-9a5b10f9dd58)




---
---
<br />


<h2>Login to the Admin Panel As Agent John</h2>

- In the osTicket post-installation section [we created an agent named `John Doe` which you can view at this link.](https://github.com/ian-bates-it/osticket-post-installation-setup/blob/main/README.md#add-another-agent-john-doe)
- John Doe's username was `john` so I will log into the `Admin Panel` as `john`

  <img src="https://github.com/user-attachments/assets/82fc598a-4642-4d53-8648-3f9ff561ef69" height="40%" width="40%" />

<br />
<br />

- In the Admin Panel under `Open` tickets, we can see that Karen Doe's ticket has been received.

  <img src="https://github.com/user-attachments/assets/fba57716-0a85-4ef2-b6c7-74921e471d1c" height="50%" width="50%" />


<br />
<br />

---

<h3>View Ticket Properties</h3>

- Clicking on user Karen Doe's ticket as Agent John from, we can examine some key properties of the ticket.
  - The **SLA Plan** is defaulted to `Default SLA`
  - **Assigned To:** It is currently `Unassigned`.
  - **Priority**: Set to `Normal`.
  - **Department**: Assigned to `Support`.



<br />
<br />

---

<h2>Adjust the SLA Severity Level</h2>

- The stated issue seems very serious.
- In this case, I would try contacting the user to guage their tone of voice and description of the issue.
- If I couldn't reach them by phone, I would try to ping them on Teams, Slack or similar messaging system to get more details about the issue.
  
- If I received confirmation from the user that the issue (_entire network down_), I would adjust the SLA properties associated with this ticket.
- 


![image](https://github.com/user-attachments/assets/92775925-dca2-4891-bb45-251df91854f2)





<br />
<br />

---

<h3>Adjust the SLA Plan Severity Level</h3>

- To adjust the SLA level originally assigned on Karen's ticket, click the hypertext link on the current SLA assignment (`Default SLA`) as shown below.

![image](https://github.com/user-attachments/assets/f13a9c1b-3383-462d-811d-b57dade2e820)


<br />
<br />

---

<h3>Update SLA Plan</h3>

- Using the `SLA Plan` drop-down menu, adjust the SLA Plan.
    - Here, I will change the  `SLA Plan` from `Default SLA` to `Sev-A` which is the highest level of severity we have in the current list of SLA Plans for the potential network outage.

  <img src="https://github.com/user-attachments/assets/b5ec8ad6-0f53-4a8a-91be-5accf4764802" height="50%" width="50%" />



<br />
<br />

- Then provide a note on why you are adjusting the SLA.
  - Here I noted, "_This ticket has the potential for a company-wide impact. Customers may be unable to perform online banking functions._" as shown below.
  - Click the `Update` button to save your changes.
 
  <img src="https://github.com/user-attachments/assets/3aba6eae-a1e8-4f69-bf74-41b65badd439" height="50%" width="50%" />


<br />
<br />

---

<h3>Update The `Help Topic`</h3>

- In this example, User Karen Doe assigned a `Help Topic` of merely `Report a Problem`.
- However, in this case, given that the stated issue could be impacting all of the company's customers from accessing their online banking, we should update the `Help Topic` to `Report a Problem / Business Critical Outage` as shown below.

<br />
<br />

- Click on the hypertext link for the currently assigned `Help Topic`, which in this case is `Report a Problem`, as shown below.

  <img src="https://github.com/user-attachments/assets/5235d98a-125b-46a3-9f4d-9ee0c72830a1" height="50%" width="50%" />



<br />
<br />

- In the `Update Help Topic` pop-up window, change the `Help Topic` from the drop-down menu from `Report a Problem` to `Report a Problem \ Business Critical Outage` as shown below.

  <img src="https://github.com/user-attachments/assets/6c04c1b5-a360-4d20-97c9-83f95a942f54" height="50%" width="50%" />


<br />
<br />


- Then provide a reason for the change to the assigned `Help Topic` in the text box.
  - Here, I provided the following explanation, "_It was reported that no customers or employees are able to access the online banking portal. _" as shown below.
  - Click the `Update` button to save our changes.

  <img src="https://github.com/user-attachments/assets/c55a8cfb-f213-48f1-95b2-1f4459c47e1b" height="50%" width="50%" />





<br />
<br />


<h3>Now the ticket has been updated with the new `SLA Plan` and the new `Help Topic`</h3>

- Updated SLA Plan and Help Topic outlined below.

  ![image](https://github.com/user-attachments/assets/37d721b4-7468-4501-89ce-febcbbfbc0d2)



<br />
<br />

---

<h3>View Ticket Thread Log To See The Changes We Made To the SLA and Help Topic</h3>

- Refresh the ticket.
- Scroll down to ticket `Ticket Thread`, showing the two changes we made as shown below.

  <img src="https://github.com/user-attachments/assets/093ef458-a04f-483c-b8e6-5a8d94c6eced" height="70%" width="70%" />



<br />
<br />

---

<h2>Assign Karen Doe's Ticket To A Team (`Online Banking`)/h2>

<h3>Step 1. Ensure Team has at least 1 agent member</h3>

**In order to assign a ticket to a Team, the Team must have at least 1 member**
- So in `Admin Panel > Agents > Teams` click on the `Members` tab.
  - Select the desired agents to join a Team.
  - Click Add button
  - Click Save Changes as shown below.

  <img src="https://github.com/user-attachments/assets/f537bd3d-871c-4493-9815-33833d09cad2" height="40%" width="40%" />


Now the `Online Banking` Team can be assigned tickets. 

![image](https://github.com/user-attachments/assets/eb653778-3bc5-4b71-a11c-8118af903042)


<br />
<br />

<h3>Step 2. Assign Karen Doe's Ticket To Team `Online Banking`</h3>

- In the open ticket, click on the hypertext link for the `Assigned To` field, which is currently set to `--Unassigned--` as shown below.

  <img src="https://github.com/user-attachments/assets/0398b8aa-6a1d-4c33-b169-7566058b073c" height="50%" width="50%" />


<br />
<br />

---

<h3>Select `Online Banking` Team From Assignee Drop Down</h3>

- Select `Online Banking` from the **Assignee** drop-down menu as shown below.

  <img src="https://github.com/user-attachments/assets/99ea3d06-d86d-4cf5-81d9-040fdd1dde57" height="50%" width="50%" />



<br />
<br />


<h3>Add A Reason For Assigning Ticket To Team</h3>

- Provide a breif explanation for assigning Karen Doe's ticket to the `Online Banking` Team.
  - Here, I entered "_Customers are not able to access the online banking portal, assigning to online banking team._" as shown below.

  <img src="https://github.com/user-attachments/assets/07657277-4207-4bd4-a6d2-5f702d4a6128" height="50%" width="50%" />




Now the ticket has been assigned to the `Online Banking` team, as shown below.

![image](https://github.com/user-attachments/assets/8542e88d-f459-43a7-8b81-74b56e384b1d)




<br />
<br />


<h3>Log Out and Log Back In As Jane To Work The Ticket.</h3>

- We are currently logged into the Admin Panel as Agent John.

- When we [set up the agent John account, we did NOT make him a member of the `Online Banking` Team or any other Team, which you can see at this link.](https://github.com/ian-bates-it/osticket-post-installation-setup/blob/main/README.md#add-another-agent-john-doe)

- Because agent John is not a member of the `Online Banking` team, we need to log out and log back in with an agent account that is a member of the `Online Banking` Team.






<br />
<br />


<h2>Work The Ticket.</h2>


- Log into the Admin Panel with [the Jane Doe account we created in this part of the post-installation setup at this link.](https://github.com/ian-bates-it/osticket-post-installation-setup/blob/main/README.md#create-new-agent-account)







