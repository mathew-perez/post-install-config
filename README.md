# post-install-config

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Setup</h1>
This tutorial will go over the post install setup of osTicket. This will require the complete of the prerequisites and install of osTicket. Please see the tutorial if that has not been done yet. 

<p></p>

The tutorial is [here](https://github.com/klcarpio/osTicket-Prerequisites-and-How-to-Install).

All work in this tutorial will be done in the "Admin Panel."

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Setup</h2>

- Step 1: Add Roles
- Step 2: Add Departments
- Step 3: Add Teams
- Step 4: Add Agents
- Step 5: Add Users
- Step 6: Add Service Level Agreements (SLAs)
- Step 7: Add Help Topics

<h2>Setup Steps</h2>

<h3>1. Step 1: Add Roles</h3>
First step is to add a role. Create an administrator that has all the permissions (Supreme Admin). 

<p>
<img src="https://i.imgur.com/PGjokdZ.png" height="80%" width="80%" alt="1."/>
</p>

<p>
<img src="https://i.imgur.com/QWSezhb.png" height="80%" width="80%" alt="2."/>
</p>

<p>
<img src="https://i.imgur.com/I34JbsS.png" height="80%" width="80%" alt="3."/>
</p>

<p>
<img src="https://i.imgur.com/IZZkBRK.png" height="80%" width="80%" alt="4."/>
</p>

<p>
<img src="https://i.imgur.com/fWQxRCs.png" height="80%" width="80%" alt="5."/>
</p>

<h3>2. Step 2: Add Departments</h3>
Second step is add departments. 

<p>
<img src="https://i.imgur.com/Q1X1q6l.png" height="80%" width="80%" alt="6."/>
</p>

<p>
<img src="https://i.imgur.com/6YClBSL.png" height="80%" width="80%" alt="7."/>
</p>

<p>
<img src="https://i.imgur.com/AeRKqge.png" height="80%" width="80%" alt="8."/>
</p>

Ensure you do this before you move on. Go to "Settings" then "User Settings." Make sure this setting is unchecked. 

<p>
<img src="https://i.imgur.com/C06CzAA.png" height="80%" width="80%" alt="9."/>
</p>

<h3>3. Step 3: Add Teams</h3>
Third step is to add teams. 

<p>
<img src="https://i.imgur.com/J1n1lqh.png" height="80%" width="80%" alt="10."/>
</p>

<p>
<img src="https://i.imgur.com/z2aWJXl.png" height="80%" width="80%" alt="11."/>
</p>

<h3>4. Step 4: Add Agents</h3>
Fourth step is to add agents. Create two agents, one with adminitrator capablities (Jane Doe) and one with regular capabilities (John Doe). Make sure to set the passwords for the agents. 

<p>
<img src="https://i.imgur.com/1rlNbBz.png" height="80%" width="80%" alt="12."/>
</p>

<p>
<img src="https://i.imgur.com/eOz2Ylx.png" height="80%" width="80%" alt="13."/>
</p>

<p>
<img src="https://i.imgur.com/TDapqhD.png" height="80%" width="80%" alt="14."/>
</p>

<h3>5. Step 5: Add Users</h3>
Fifth step is to add users. Users can be added in either the Agent Panel or Admin Panel. In this example, the Agent Panel was utilized and two users were created. 

<p>
<img src="https://i.imgur.com/toIlWlF.png" height="80%" width="80%" alt="15."/>
</p>

<p>
<img src="https://i.imgur.com/VyNZb2S.png" height="80%" width="80%" alt="16."/>
</p>

<p>
<img src="https://i.imgur.com/CXwjmJ8.png" height="80%" width="80%" alt="17."/>
</p>

<h3>6. Step 6: Add Service Level Agreements (SLAs)</h3>
The sixth step is to add Service Level Agreements (SLAs). SLAs are basically the expected turn around times that tickets are created by the user. SLAs can vary in severity and in this example, three were created. 

1. Sev-A (1 hour turnaround, 24/7 schedule)
2. Sev-B (4 hour turnaround, 24/7 schedule)
3. Sev-C (8 hour turnaround, Monday - Friday 8AM - 5PM)

<p>
<img src="https://i.imgur.com/6RMaLcV.png" height="80%" width="80%" alt="18."/>
</p>

<p>
<img src="https://i.imgur.com/k6upd9b.png" height="80%" width="80%" alt="19."/>
</p>

<p>
<img src="https://i.imgur.com/tx1rAy1.png" height="80%" width="80%" alt="20."/>
</p>

<p>
<img src="https://i.imgur.com/tx1rAy1.png" height="80%" width="80%" alt="21."/>
</p>

<h3>7. Step 7: Add Help Topics</h3>
Seventh and final step is to add help topics. These topics can be selected by the user however agents and administrators can change them once received. 

<p>
<img src="https://i.imgur.com/WMdg6VY.png" height="80%" width="80%" alt="22."/>
</p>

<p>
<img src="https://i.imgur.com/r4fFjdU.png" height="80%" width="80%" alt="23."/>
</p>

After all that is done, osTicket is setup. The next tutorial will showcase how to submit tickets and answer them. This will build intuition and skills for ticketing systems for both users and IT professionals. 


**REMEMBER TO DELETE YOUR RESOURCES ONCE YOU ARE DONE WITH THE LAB!**
