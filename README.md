# CyberSecMod9

During this module I deployed the required Donaea with HTTP honeypot and the Snort Honeypot utlizing the Google Cloud Platform service. I followed the instructions included with the lab.
I encountered a few issues. After my initial setup of the MHN Admin VM, I was unable to SSH into it after installing all of the requisite packages. This meant that I had to delete the VM and recreate it, adding an additional hour or so to my project time. Additionally, I ran into an issue accessing the browser GUI for the server, until I added TCP port 80 to the firewall. Otherwise, the project went fairly smoothly.

A summary of data follows:

Number of attacks while running: 2684

<p>Top 5 ports: 42, 8088, 23, 445, 8545</p>
<p>Top 5 Attack Signatures: ET DROP Dshield Block Listed Source group 1 (34 times). <b>ET CINS Active Threat Intelligence Poor Reputation IP TCP group 75</b> (2 times).<b> ET CINS Active Threat Intelligence Poor Reputation IP TCP group 30</b> (1 time). <b>ET CINS Active Threat Intelligence Poor Reputation IP TCP group 23</b> (1 times). <b>ET CINS Active Threat Intelligence Poor Reputation IP TCP group 47</b> (1 times)
                         
<p>I had no real unanswered questions concerning the data. Overall this project took approximately 3 hours to complete.</p>
<img src=https://github.com/Calberrycoder/CyberSecMod9/blob/master/Honeypot.gif>
      

