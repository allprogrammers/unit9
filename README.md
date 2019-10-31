# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

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

Vulnerability #1:  SQL Injection in (https://35.184.88.14/blue/public/salesperson.php?id=')
<img src='sqli.gif'>

Vulnerability #2:  Session Fixation using CSRF


## Green

Vulnerability #1: Cross-Site Scripting (XSS) (Feedback form)
<img src='xss.gif'>

Vulnerability #2: Allows to know if a username is valid or not by checking whether the error message is bold or not
<img src='ue.gif'>

## Red

Vulnerability #1: Cross-Site Request Forgery (CSRF) admin panel edit forms
<img src='csrf.gif'>

Vulnerability #2: Insecure Direct Object Reference (IDOR) listing salespersons
<img src='idor.gif'>

## Notes

Describe any challenges encountered while doing the work

