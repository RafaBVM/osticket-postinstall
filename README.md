# osticket-postinstall
<p>
<img src="https://i.imgur.com/w4qxGDf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is now the setup of the post installation of osTicket for the agents and users functionality/access. I do this under my main admin account as you can see in the image above.
</p>
<br />
<p>
<img src="https://i.imgur.com/qdNilP7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I go to the Admin Panel -> Agents -> Roles
</p>
<br />
<p>
<img src="https://i.imgur.com/NEgLuY0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, I create a Supreme Admin role that gets overall access to the ticketing system essentially. 
</p>
<br />
<p>
<img src="https://i.imgur.com/frzPNT6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I now configure departments and create a department called System Administrator. I go to the Admin Panel -> Agents -> Departments
</p>
<br />
<p>
<img src="https://i.imgur.com/nCmD2hD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I also configured a team under the name Level II Support. I went to the Admin Panel -> Agents -> Teams. Level I Support already existed by default after the installation of osTicket.
</p>
<br />
<p>
<img src="https://i.imgur.com/1TKAP4D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I go to the Admin Panel -> Settings -> User Settings to give the end users access to create tickets. I make sure that the require registration box is unchecked so that they gain full access since the end users don't have access to a password login.
</p>
<br />
<p>
<img src="https://i.imgur.com/n97OiFZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I configure agents to work on the tickets. I create two agents under the name Alex Hernandez and David Quintanilla, giving them individual emails and passwords, but different access for both. Alex's role is under Supreme Admin in which I had created earlier, and the department he's under is the System Admin that I had also made giving him overall access to the tickets and assigning them to whomever. The team I put him in is the Support 
Level II team. For David I gave him limited access under the Support department but gave him secondary access to the System Admin departement so he can resolve the tickets that he has assigned. I put him under the Level I Support team. 
</p>
<br />
<p>
<img src="https://i.imgur.com/38Xgys0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I configure the end users under the names Karen Duff and Ken Clark. I go to the Agent Panel -> Users -> Add New. Pretty self explanatory as you can see in the image above.
</p>
<br />
<p>
<img src="https://i.imgur.com/JMavsMf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I now configure some SLA's dictacting the severity of the tickets given to the agents. I go back to the Admin Panel -> Manage -> SLA and add new SLA plan. I add three SLA's, A, B, and C.
</p>
<br />
<p>
<img src="https://i.imgur.com/qOPWXWD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I set SEV-A to a 1 hour grace period under a 24/7 schedule, SEV-B to a 4 hour grace period under a 24/7 schedule, and SEV-C to a 8 hour grace period under bussiness hours (weekday) schedule.
</p>
<br />
<p>
<img src="https://i.imgur.com/O3feGih.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To conclude I go to Admin Panel -> Manage -> Help Topics to create some help topics for the agents. I create a Business Critical Outage topic, a Personal Computer Issues topic, a Equipment Request, and a Password Reset topic. Now that that's been created, I can go ahead and make tickets for the agents under the end users on the end users osTicket URL.
<br />
<p>
