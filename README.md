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
Blue Website allows the user to input SQL statements as it responds when you attend one.

<img src="Kapture 2022-10-31 at 18.48.23.gif">


## Green

Vulnerability #1: XSS

Description: A stored XSS can be triggered when the opening the feedback.

<img src="Kapture 2022-10-31 at 18.51.01.gif">


## Red

Vulnerability #1: IDOR

Description: Red website does not protect the data enough since it uses id based on numbers. In comparison the Blue Website that even thought uses numbers as IDs it does not reveal users that are not a saleperson.

<img src="Kapture 2022-10-31 at 17.40.20.gif">


## Notes
N/A

