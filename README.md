<h1>Passive Reconnisance</h1>


<h2>Key Outcomes Required</h2>

- <b>Identify IP addresses & DNS information</b>
- <b>Identify domain names and domain ownership information</b>
- <b>Identify email addresses and social media presence links</b>
- <b>Identify web technologies being used on the site</b>
- <b>Identify Subdomains</b>
  



<h2>Websites & Tools used</h2>
<b>Mentioned in Order</b>

- <b>netcraft.com</b> 
- <b>dnsdumpster.com</b>
- <b>wafw00f</b>
- <b>sublist3r</b>
- <b>theHarvester</b>
- <b>haveibeenpwned.com</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b> 

<h2>Cheatsheet Walkthrough</h2>

<b> 
1. ***BROWSER***
netcraft.com

2. ***BROWSER***
dnsdumpster.com

IP Address:
DNS Info:
Domain names:
Domain ownership:
Email addresses:
Social media:
web technologies:
Subdomains:

3. ***TERMINAL***
Find web application firewall 
wafw00f hackersploit.com
wafw00f hackersploit.com -a = shows all possible WAFs
if saying WAF but not identifying then need to run port scan on IP address of webserver
WAF:

4. ***TERMINAL***
Find Subdomains of domain with sublist3r
sublist3r -d hackersploit.com
sublister -d hackersplpoit.com -e yahoo,google for specific engine.

5. ***TERMINAL***
Find emails 
theHarvester -d hackersploit.org -b google,linkedin

6. ***BROWSER***
Find leaked passwords
haveibeenpwned.com</b>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
