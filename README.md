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

<p align="center">
  <img width="415" height="482" alt="image" src="https://github.com/user-attachments/assets/69968a76-c0c6-4244-99d1-a294034305e0" />
  <img width="407" height="570" alt="image" src="https://github.com/user-attachments/assets/200dc38b-5c5d-46e2-8bc5-0825f57e3b53" />
</p>


<h3>2. Installed PHP Manager</h3>

<p>
Then I installed PHP Manager so IIS could actually run PHP apps like osTicket.
</p>

<p align="center">
<img width="726" height="524" alt="image" src="https://github.com/user-attachments/assets/40245525-2827-45c7-949c-0bd133849162" />
<img width="415" height="679" alt="image" src="https://github.com/user-attachments/assets/2a83e8e3-e531-4db1-a6a1-480d9fb846aa" />
</p>

<h3>3. Installed MySQL (Database)</h3>

<p>
Set up MySQL and created a database for osTicket to store ticket data.
</p>

<p align="center">
  <img width="600" height="452" alt="image" src="https://github.com/user-attachments/assets/2a4438a6-24ba-4bb3-871e-fedc9fb1d0ec" />
<img width="738" height="540" alt="image" src="https://github.com/user-attachments/assets/462ca80a-ccb5-4fe2-824d-084ed2a90e99" />


</p>

<h3>4. Added osTicket Files to IIS</h3>

<p>
Downloaded osTicket and placed the files into the IIS root directory.
</p>

<p align="center">
  <img src="https://i.imgur.com/2rFZk3P.png" width="80%" alt="osTicket Files"/>
</p>

<h3>5. Ran the Web Installer</h3>

<p>
Opened it in the browser, connected the database, and finished setup.
</p>

<p align="center">
  <img src="https://i.imgur.com/Uw6lYkG.png" width="80%" alt="osTicket Installer"/>
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
