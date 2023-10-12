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


1. ***BROWSER*** - Netcraft
   - [netcraft.com](http://www.netcraft.com)

2. ***BROWSER*** - dnsdumpster
   - [dnsdumpster.com](https://dnsdumpster.com)

   **Information to Gather from 1 & 2:**
   - IP Address:
   - DNS Info:
   - Domain names:
   - Domain ownership:
   - Email addresses:
   - Social media:
   - Web technologies:
   - Subdomains:

3. ***TERMINAL***
   **Find web application firewall with wafw00f:**
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
   **Find emails with theHarvester:**
   - Using `theHarvester`:
     ```
     theHarvester -d hackersploit.org -b google,linkedin
     ```

6. ***BROWSER***
   - [haveibeenpwned.com](https://haveibeenpwned.com)
   - Find leaked passwords for the email addresses




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
