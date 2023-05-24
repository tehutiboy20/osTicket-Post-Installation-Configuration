<p align="center">
 
<img src="https://i.imgur.com/y8PA27H.png"/></P>

 <h2>osTicket Configuration<h2/>
In the previous tutorial I <a href="https://github.com/AsiaPonder001/osticket-prereqs">INSTALLED</a> osTicket. In this tutorial I will go through the steps to configure and setup osTicket.
<br />
<br />

<h2>Technologies and Environments Used<h2/>

- PHP 
- osTicket (Help Desk Ticketing System)
<br />

<h2>Main Steps<h2/>

Configure roles in the admin panel.
<h2>Admin Panel > Agents > Roles<h2/>
<h2>(NOTE: To switch between the admin and agent panel look at the top of the page. If it reads Admin panel it means you are in the Agent panel. If it reads Agent panel then you are in the Admin panel.)<h2/>


<P><img src="https://i.imgur.com/9ijnXxg.png"/></P> 
<P><img src="https://i.imgur.com/dPA8Ftp.png"/></p> 
<P><img src="https://i.imgur.com/PkQsQak.png"/></P> 
 
<br/>
<P><img src="https://i.imgur.com/Dwq8VYY.png"/></p> 
<p><img src="https://i.imgur.com/TlOHvtv.png"/></P> 
 
 <h2 >Configure the Departments <h2/>

<a>Admin Panel > Agents > Departments > Type: System administrators for department name <a/>
 <br/>
 <br/>

<p><img src="https://i.imgur.com/T3gpaFW.png"/></p>
<P><img src="https://i.imgur.com/esvUrPu.png"/></p>
 <br/>
 <br/>
  
 <h2> Configure Teams<h2/>

<h2>Admin Panel > Agents > Teams > Add Teams(create Level I Support and Level II Support) <h2/>
<a> Name the team <a/>

<P><img src="https://i.imgur.com/qUFmykU.png"/></p>
<a>Add member(s)<a/>
<p><img src="https://i.imgur.com/d0PuCVr.png"/></P>
 
<h2>Allow anyone to create tickets<h2/>

<a>Admin Panel > Settings > User Settings<a/>
 
<a>Check the box to Require Registration and login to create tickets<a>
 
<P><img src="https://i.imgur.com/SWBqmVs.png"/></p>
 
<h2>Configure Agents (these are the workers who will work the tickets)<h2/>

<a>Admin Panel > Agents > Add New <a/>
 
<P><img src="https://i.imgur.com/9ijnXxg.png"/></p>
 
<p><img src="https://i.imgur.com/N6Jrq0b.png"/></P>
 
<h2>Set the Agent password<h2/>
 
<p><img src="https://i.imgur.com/ia1KETC.png"/></P>
 
<h2>and set the department > check permissions > add teams<h2/>
<P><img src="https://i.imgur.com/YE3hIKr.png"/></p>

 
<p><img src="https://i.imgur.com/7dEX70T.png"/></P>
 
 
<h2>Create new user(Customers who can create a service ticket request)<h2/>
<a>Agent Panel > Users > Add User<a/>
 
<P><img src="https://i.imgur.com/vUfVvVc.png"/></p>
<p><img src="https://i.imgur.com/niz88WE.png"/></P>
<P><img src="https://i.imgur.com/UXYoqz8.png"/></p> 
<P><img src="https://i.imgur.com/bOKnRPF.png"/></p>

 
 <h2>Configure SLA (Service Level Agreements)<h2/>
 <h2>Admin Panel > Manage > SLA<h2/>
 
- Sev-A(1 hour, 24/7)
- Sev-B(4 hours, 24/7)
- Sev-C(8 hours, business hours)
  
<P><img src="https://i.imgur.com/cZyR9Wj.png"/></p>
<p><img src="https://i.imgur.com/Zl5SbWx.png"/></P>
<P><img src="https://i.imgur.com/KOiDk1M.png"/></p>
<p><img src="https://i.imgur.com/i7OChax.png"/></P> 
<P><img src="https://i.imgur.com/bliSUHL.png"/></p>
 
 <h2>Configure Help Topics<h2/>
<a>Admin Panel > Manage > Help Topics<a/>
<h2>create four topics<h2/>
 
- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
 
<p><img src="https://i.imgur.com/IMqpNvZ.png"/></P>
<P><img src="https://i.imgur.com/V1nAwrN.png"/></p>





<br />
Thank you 
