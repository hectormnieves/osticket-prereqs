<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket Help Desk Lab (My Setup)</h1>

<p align="center">
Built and configured a working help desk system from scratch
</p>

<h2> What I Used</h2>

- Microsoft Azure (Virtual Machine)  
- Remote Desktop  
- IIS (Web Server)  
- PHP Manager  
- MySQL  

<h2> OS</h2>

- Windows 10 (21H2)

<h2> What I Had to Set Up First</h2>

Before installing osTicket, I set up everything needed for it to run:

- Enabled IIS (web server) in Windows  
- Installed PHP Manager so IIS can run PHP  
- Installed MySQL for the database  
- Installed Visual C++ Redistributable  
- Made sure IIS was properly configured  

<h2> Step-by-Step Setup</h2>

<h3> Step 1: Enable IIS</h3>

<p>
First, I enabled IIS (Internet Information Services) in Windows Features. 
This allows me to host a website locally on the machine.
</p>

<!-- INSERT IMAGE HERE -->

<h3> Step 2: Configure IIS Features</h3>

<p>
Next, I made sure the correct IIS features were enabled, especially anything related to application development like CGI.
This is important so PHP applications can run correctly.
</p>

<!-- INSERT IMAGE HERE -->

<h3> Step 3: Open IIS Manager</h3>

<p>
After installing IIS, I opened IIS Manager to confirm everything was working.
I verified that the default website was running.
</p>

<!-- INSERT IMAGE HERE -->

<h3> Step 4: Install PHP Manager</h3>

<p>
Then I installed PHP Manager, which allows IIS to process PHP files.
This is required for osTicket since it is a PHP-based application.
</p>

<!-- INSERT IMAGE HERE -->

<h3> Step 5: Install MySQL</h3>

<p>
Next, I installed MySQL and created a database that osTicket will use to store ticket data.
</p>

<!-- INSERT IMAGE HERE -->

<h3> Step 6: Add osTicket Files</h3>

<p>
I downloaded osTicket and moved the files into the IIS web directory (wwwroot).
This makes the application accessible through the browser.
</p>

<!-- INSERT IMAGE HERE -->

<h3> Step 7: Run osTicket Installer</h3>

<p>
Finally, I opened a browser and navigated to the osTicket setup page.
I connected it to the MySQL database, created an admin account, and completed the installation.
</p>

<!-- INSERT IMAGE HERE -->

<h2> End Result</h2>

- Users can submit tickets  
- Tickets can be tracked and updated  
- Admins can manage everything  

<p>
This is basically a real help desk system like what’s used in IT jobs.
</p>

<h2> What I Learned</h2>

- How to set up IIS and host a web application  
- How databases connect to applications  
- Troubleshooting installation issues  
- How help desk ticketing systems work  

<h2> What I’d Do Next</h2>

- Set up email ticketing  
- Add user roles and permissions  
- Practice real help desk scenarios  
