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

Before installing osTicket, I had to get everything ready:

- Turned on IIS in Windows Features  
- Installed PHP Manager  
- Installed MySQL  
- Installed Visual C++ Redistributable  
- Configured IIS for PHP  

<h2> What I Did (Step-by-Step)</h2>

<h3>1. Enabled IIS (Web Server)</h3>

<p>
First, I turned on IIS so I could host the application locally.
</p>

<table>
<tr>
<td><img src="https://cdn.midas.network/img/kb/00209-02.png" width="400"/></td>
<td><img src="https://learn-attachment.microsoft.com/api/attachments/290a7f21-03f3-4412-91e3-7cd887e9147a?platform=QnA" width="400"/></td>
</tr>
</table>

<h3>2. IIS Features / Configuration</h3>

<p>
Made sure the right IIS features were enabled so everything would work correctly.
</p>

<table>
<tr>
<td><img src="https://learn-attachment.microsoft.com/api/attachments/81930-screen-shot-2021-03-26-at-35143-pm.jpg?platform=QnA" width="400"/></td>
<td><img src="https://docs.appeon.com/ps2022r2/images/ps_tutorial_125_1.png" width="400"/></td>
</tr>
</table>

<h3>3. IIS Manager Running</h3>

<p>
Checked IIS Manager to confirm the web server was up and running.
</p>

<table>
<tr>
<td><img src="https://4js.com/online_documentation/fjs-gas-manual-html/gas-topics/Images/IIS_Windows10_IIS_Manager.jpg" width="400"/></td>
<td><img src="https://learn.microsoft.com/en-us/iis/configuration/system.webserver/management/authentication/index/_static/image7.png" width="400"/></td>
</tr>
</table>

<h3>4. Installed PHP Manager</h3>

<p>
Installed PHP Manager so IIS could run PHP apps like osTicket.
(Add your own screenshot here for best results)
</p>

<h3>5. Installed MySQL (Database)</h3>

<p>
Set up MySQL and created a database for osTicket.
(Add your own screenshot here for best results)
</p>

<h3>6. Added osTicket Files to IIS</h3>

<p>
Downloaded osTicket and placed the files into the IIS directory.
(Add your own screenshot here)
</p>

<h3>7. Ran the Web Installer</h3>

<p>
Finished setup through the browser and connected the database.
(Add your own screenshot here)
</p>

<h2> End Result</h2>

- Users can submit tickets  
- Tickets can be tracked and updated  
- Admins can manage everything  

<p>
Basically a real help desk setup like you’d see in an IT job.
</p>

<h2> What I Learned</h2>

- How to set up IIS and host a web app  
- How a database connects to an application  
- Troubleshooting when stuff doesn’t work (definitely ran into that)  
- How ticketing systems actually work in real IT environments  

<h2> What I’d Do Next</h2>

- Set up email ticketing  
- Add user roles and permissions  
- Practice real help desk scenarios  
