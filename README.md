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
<img src="https://i.imgur.com/NEgLuY0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, I create a Supreme Admin role that gets overall access to the ticketing system essentially. 
</p>
<br />
<img src="https://i.imgur.com/frzPNT6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I now configure departments and create a department called System Administrator. I go to the Admin Panel -> Agents -> Departments
</p>
<br />
<img src="https://i.imgur.com/nCmD2hD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I also configured a team under the name Level II Support. I went to the Admin Panel -> Agents -> Teams. Level I Support already existed by default after the installation of osTicket.
</p>
<br />
<img src="https://i.imgur.com/1TKAP4D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I go to the Admin Panel -> Settings -> User Settings to give the end users access to create tickets. I make sure that the require registration boc is unchecked so that they gain full access since the end users don't have access to a password to login.
</p>
<br />
<img src="https://i.imgur.com/n97OiFZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I configure agents to work on the tickets. I create two agents under the name Alex Hernandez and David Quintanilla, giving them individual emails and passwords, but different access for both. Alex's role is under the System Admin that I had created earlier and the department he's under is the Supreme Admin that I had also made giving him overall access to the tickets and assigning them to whomever. The team I put him in is the Support 
Level II team. For David I gave him limited access under the support department but gave him secondary access to the System Admin departement so he can resolve the tickets that he has assigned. I put him under the Level I Support team. 
<br />

