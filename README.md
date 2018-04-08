# Project 8 - Pentesting Live Targets

Time spent: **6** hours spent in total

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

Vulnerability #1: SQL Injection (SQLi) ![GIF](https://github.com/kballard237/CodePathWeek8/blob/master/SQL_Injection.gif)

Vulnerability #2: Session Hijacking/Fixation ![GIF](https://github.com/kballard237/CodePathWeek8/blob/master/Session_Hijacking.gif)


## Green

Vulnerability #1: Username Enumeration ![GIF](https://github.com/kballard237/CodePathWeek8/blob/master/Username_Enumeration.gif)

Vulnerability #2: Cross-Site Scripting (XSS) ![GIF](https://github.com/kballard237/CodePathWeek8/blob/master/Cross_Site_Scripting.gif)


## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR) ![GIF](https://github.com/kballard237/CodePathWeek8/blob/master/IDOR.gif)

Vulnerability #2: Cross-Site Request Forgery (CSRF) ![GIF](https://github.com/kballard237/CodePathWeek8/blob/master/CSRF.gif)


## Notes

For IDOR, I was originally testing the id values while logged in. I had to logout to find the salespeople that were missing from the public site. For Username Enumeration, it took a while for me to pick up on the subtle change in the text. 
