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

<b>1. [netcraft.com](netcraft.com) - BROWSER</b>
- <b>Shows alot of information</b>

<b>2. [dnsdumpster.com](dnsdumpster.com) - BROWSER</b>
- <b>Shows alot of information</b>

<b>3. wafw00f - TERMINAL</b>

- <b>***Use wafw00f to find web application firewall***</b>
- <b>`wafw00f` zonetransfer.me</b>

<b>4. Sublist3r - TERMINAL</b>
- <b>***Find Subdomains of domain with sublist3r***</b>
- <b>`subblist3r -d` zonetransfer.me</b>

<b>5. theHarvester - TERMINAL</b>
- <b>***Find domain email addresses***</b>
- <b>`theHarvester -d` zonetransfer.me</b>

<b>6. [haveibeenpwned.com](haveibeenpwned.com) - BROWSER</b>
- <b>***Find leaked passwords for the identified emails***</b>

<b></b>
<b></b>
<b></b>
<b></b>
<b></b>
<b></b>
<b></b>
<b></b>
<b></b>

1. ***BROWSER***
   - [netcraft.com](http://www.netcraft.com)

2. ***BROWSER***
   - [dnsdumpster.com](https://dnsdumpster.com)

   **Information to Gather:**
   - IP Address:
   - DNS Info:
   - Domain names:
   - Domain ownership:
   - Email addresses:
   - Social media:
   - Web technologies:
   - Subdomains:

3. ***TERMINAL***
   **Find web application firewall:**
   - Using `wafw00f`:
     ```
     wafw00f hackersploit.com
     ```
   - Show all possible WAFs:
     ```
     wafw00f hackersploit.com -a
     ```
   - If WAF is detected but not identified, then perform a port scan on the IP address of the webserver.
   - WAF:

4. ***TERMINAL***
   **Find Subdomains of domain with sublist3r:**
   - Using `sublist3r`:
     ```
     sublist3r -d hackersploit.com
     ```
   - Use specific engines (e.g., Yahoo, Google):
     ```
     sublister -d hackersploit.com -e yahoo,google
     ```

5. ***TERMINAL***
   **Find emails:**
   - Using `theHarvester`:
     ```
     theHarvester -d hackersploit.org -b google,linkedin
     ```

6. ***BROWSER***
   - [haveibeenpwned.com](https://haveibeenpwned.com)
   **Information to Gather:**
   - Find leaked passwords




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
