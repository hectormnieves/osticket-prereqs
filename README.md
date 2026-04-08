<p align="center">
  <img src="https://i.imgur.com/8fK4h6G.png" alt="osTicket logo"/>
</p>

<h1>osTicket Help Desk Lab (My Setup)</h1>

<p>
For this project, I set up <b>osTicket</b>, which is an open-source help desk ticketing system. 
The goal was to get hands-on experience with something similar to what real IT support teams use every day.
</p>

<p>
I built everything inside a Windows virtual machine and configured all the pieces needed to get it running from scratch.
</p>

<hr>

<h2>🎥 Demo</h2>

- I’ll add a video walkthrough here soon (showing install + ticket system working)

<hr>

<h2>🧰 What I Used</h2>

- Microsoft Azure (Virtual Machine)
- Remote Desktop
- IIS (Web Server)
- PHP Manager
- MySQL

<hr>

<h2>💻 OS</h2>

- Windows 10 (21H2)

<hr>

<h2>📋 What I Had to Set Up First</h2>

Before installing osTicket, I had to get a few things ready:

- Turned on IIS in Windows Features  
- Installed PHP Manager so IIS can run PHP  
- Installed MySQL for the database  
- Installed Visual C++ Redistributable  
- Made sure IIS was configured correctly  

<hr>

<h2>⚙️ What I Did (Step-by-Step)</h2>

<h3>1. Set up IIS</h3>

<p>
First thing I did was enable IIS so I could host the web app locally.
</p>

<p align="center">
  <img src="https://i.imgur.com/Zk6TR5k.png" width="80%" />
</p>

---

<h3>2. Got PHP working</h3>

<p>
Installed PHP Manager and made sure IIS could actually process PHP files.
</p>

---

<h3>3. Set up the database</h3>

<p>
Installed MySQL and created a database that osTicket would use to store all the tickets.
</p>

---

<h3>4. Installed osTicket</h3>

<p>
Downloaded the files, moved them into the IIS directory, and started the setup through the browser.
</p>

---

<h3>5. Finished setup</h3>

<p>
Connected it to the database, created my admin account, and completed the install.
</p>

---

<h2>✅ End Result</h2>

<p>
At the end, I had a fully working help desk system where:
</p>

- Users can submit tickets  
- Tickets can be tracked and updated  
- Admins can manage and respond  

<p>
Basically a real-world help desk environment.
</p>

<hr>

<h2>🧠 What I Learned</h2>

- How to set up a web server (IIS)
- How databases connect to applications
- Troubleshooting when things don’t work (this happened a lot 😅)
- How ticketing systems actually function in IT jobs

<hr>

<h2>🚀 What I’d Do Next</h2>

- Set up email so tickets come in automatically  
- Add different user roles  
- Practice real help desk scenarios  
