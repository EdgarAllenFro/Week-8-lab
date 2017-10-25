# Week-8-lab
# Project 8 - Pentesting Live Targets

Time spent: **7** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: __SQLi : https://github.com/EdgarAllenFro/Week-8-lab/blob/master/sqli_week8.gif : running sqlmap proves that the blue site is vulnerable through the php?id=x field of the salesperson pages.

Vulnerability #2: __________________


## Green

Vulnerability #1: __Username Enumeration : https://github.com/EdgarAllenFro/Week-8-lab/blob/master/username_enum.gif : a correct username results in bold text while incorrect usernames result in non-bold text.

Vulnerability #2: __XSS


## Red

Vulnerability #1: __IDOR : https://github.com/EdgarAllenFro/Week-8-lab/blob/master/idor_week8.gif : changing the id in the url can result in a user that is not meant to be displayed.

Vulnerability #2: __________________


## Notes

Describe any challenges encountered while doing the work
