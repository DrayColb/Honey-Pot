<h1>Honey Pot (Microsoft Azure) </h1>

<h2>Description</h2>
This project is a Honey Pot created using Microsoft Azure. I will be creating a vulnerble virtual machine, a log that will contain the failed RDP attempts, and a SIEM to ingest the log and show the location of the attackers.



  
 <h2> Here is the virtual machine that I have made vulnerable by allowing any ports and protocol </h2> 

![H1](https://github.com/user-attachments/assets/24626bfc-cd06-4421-a4af-14cef3760403)

<h2> Here I will create the log "Honeylog" </h2>

![H3](https://github.com/user-attachments/assets/f5d3a595-21ea-445c-9af2-b247426a9385)

<h2> Here is where I create the SIEM and link the Honeylog </h2>

![H4](https://github.com/user-attachments/assets/6ed579c9-cd06-47ce-8bc4-5a5ac1685727)


<h2> Now I will RDP into the virtual machine</h2>

![H5](https://github.com/user-attachments/assets/e47fe014-bb60-429a-a9b9-f00c9c8075fc)



<h2> Now to make this virtual machine more accessible I will disable the firewall </h2>

![H6](https://github.com/user-attachments/assets/57ee38d9-dfa5-4afe-9378-d486f01ac1d0)


<h2> Here I will be using an API in Powershell ISE that will collect the attackers country, longitude, lattitude, ip, and timestamp then saving it to a failed RDP file  </h2>

![H8](https://github.com/user-attachments/assets/dcc9f871-a521-4f64-8a18-354d90e9dc1b)

<h2> Next I will add the failed rdp log to the Azure Honeylog</h2>

![H9](https://github.com/user-attachments/assets/9d528b2a-5635-4073-9e05-57e1f2644a01)


<h2> Finally I will ingest the log into the SIEM and display where the attackers are coming from</h2>

![H13](https://github.com/user-attachments/assets/bcc3fbe6-6cad-4a2c-936f-5083eedd0c49)















