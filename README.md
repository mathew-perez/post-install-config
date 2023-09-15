<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Setup</h1>
This tutorial will go over the post install setup of osTicket. This will require the completion of the prerequisites and install of osTicket. Please see the tutorial if that has not been done yet. 

<p></p>

The tutorial is [here](https://github.com/mathew-perez/osticket-prereqs/).

First go to http://localhost/osTicket/scp/login.php in your browser and log in with the information entered from the prerequestites install.

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
The first step is to add a role. Create an administrator that has all the permissions (Supreme Admin). 

Admin Panel -> Agents -> Roles -> Add New Role

![image](https://github.com/mathew-perez/post-install-config/assets/144407220/6154a4ec-2940-4a77-929a-832f63d18270)
![image](https://github.com/mathew-perez/post-install-config/assets/144407220/8d1dc1f0-a4c8-4ef3-82bb-fb4236ff4bf3)

</p>

<h3>2. Step 2: Add Departments</h3>
The second step is add departments. 

Admin Panel -> Agents -> Department -> Add New Department

![image](https://github.com/mathew-perez/post-install-config/assets/144407220/9a9e120e-90c9-4ca4-a0eb-21dd5eca64da)
![image](https://github.com/mathew-perez/post-install-config/assets/144407220/7913e645-14cb-4d0f-8f8f-3dc6accaa8b8)


Ensure you do this before you move on. Go to "Settings" then "User Settings." Make sure require registration and login to create tickets sure setting is unchecked. This allows anyone to create tickets. 

![image](https://github.com/mathew-perez/post-install-config/assets/144407220/c5b97324-1f01-4ee0-bd74-b83553d852d5)

<h3>3. Step 3: Add Teams</h3>
The third step is to add teams. 

Admin Panel -> Agents -> Teams -> Add New Team

![image](https://github.com/mathew-perez/post-install-config/assets/144407220/a2bfc8a9-bdf4-40c9-99b0-b7755f6a5868)
![image](https://github.com/mathew-perez/post-install-config/assets/144407220/8451834f-818c-497a-8590-a83ccdec24bf)

<h3>4. Step 4: Add Agents</h3>
The fourth step is to add agents. Create two agents, one with adminitrator capablities (Jane Doe) and one with regular capabilities (John Doe). Make sure to set the passwords for the agents. 

Admin Panel -> Agents -> Add New Agent

![image](https://github.com/mathew-perez/post-install-config/assets/144407220/bb3d3b4a-4b34-4983-ac64-23a4bd07bd8d)
![image](https://github.com/mathew-perez/post-install-config/assets/144407220/b256fca5-671b-468e-891b-c2260c594bbf)


<h3>5. Step 5: Add Users</h3>
The fifth step is to add users. Users can be added in either the Agent Panel or Admin Panel. In this example, the Agent Panel was utilized and two users were created. 

Agent Panel -> Users -> Add User

![image](https://github.com/mathew-perez/post-install-config/assets/144407220/f580e2c8-c683-4d26-a221-0f0ece561fed)
![image](https://github.com/mathew-perez/post-install-config/assets/144407220/241fb6e7-d579-487d-b8ce-59116bddf532)


<h3>6. Step 6: Add Service Level Agreements (SLAs)</h3>
The sixth step is to add Service Level Agreements (SLAs). SLAs are basically the expected turn around times that tickets are created by the user. SLAs can vary in severity and in this example, three were created. 

1. Sev-A (1 hour turnaround, 24/7 schedule)
2. Sev-B (4 hour turnaround, 24/7 schedule)
3. Sev-C (8 hour turnaround, Monday - Friday 8AM - 5PM)

Admin Panel -> Manage -> SLA -> Add New SLA Plan

![image](https://github.com/mathew-perez/post-install-config/assets/144407220/b61e0bab-ee35-4588-b0a0-c2e83bcdee03)
![image](https://github.com/mathew-perez/post-install-config/assets/144407220/96443978-a91c-4323-8a40-4051c69ba4da)
![image](https://github.com/mathew-perez/post-install-config/assets/144407220/ac3c7e41-8172-4d54-870f-6594d9db6103)



<h3>7. Step 7: Add Help Topics</h3>
The last step is to add help topics. These topics can be selected by the user however agents and administrators can change them once received. 

<p>
<img src="https://i.imgur.com/WMdg6VY.png" height="80%" width="80%" alt="22."/>
</p>

<p>
<img src="https://i.imgur.com/r4fFjdU.png" height="80%" width="80%" alt="23."/>
</p>

After all that is done, osTicket is setup. The next tutorial will showcase how to submit tickets and answer them. This will build intuition and skills for ticketing systems for both users and IT professionals. 


**REMEMBER TO DELETE YOUR RESOURCES ONCE YOU ARE DONE WITH THE LAB!**
