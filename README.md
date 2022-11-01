# Unit-8-Project-Pen-Testing-Live-Targets
# Pen Testing Live Targets

Time spent: 10 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQLI

Description:
Blue Website allows the user to input SQL statements as it responds when you attempt one.

<img src="Kapture 2022-10-31 at 19.10.48.gif">


## Green

Vulnerability #1: XSS

Description: A stored XSS can be triggered when the admin opens the feedback section.

<img src="Kapture 2022-10-31 at 18.51.01.gif">


## Red

Vulnerability #1: IDOR

Description: Red website does not protect the data enough since it uses id based on numbers and it reveals information that is not supposed to be seen on the public website.

<img src="Kapture 2022-10-31 at 18.51.01.gif">


## Notes
N/A

