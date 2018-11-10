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

Vulnerability #1: SQLI
The find a salesperseon page is vulnerable to a SQL Injection.
![blue sqli](https://github.com/ramonpetgrave64/Cybersecurity-University-Project-8/blob/master/blue%20sqli.gif?raw=true)
Bonus: Usernames, password hashes, and information on salespersons can be extracted form the database.
![blue sqli extraction](https://github.com/ramonpetgrave64/Cybersecurity-University-Project-8/blob/master/blue%20sqli%20bonus.gif?raw=true)
Vulnerability #2: __________________


## Green

Vulnerability #1: Username Enumeration
The login page's error HTML for a valid username is different, having a CSS class of "failed" instead of "failure", as in the styles.css
![greenlogin form username enumeration gif](https://github.com/ramonpetgrave64/Cybersecurity-University-Project-8/blob/master/green%20username%20enum.gif?raw=true)
Vulnerability #2: XSS
The public contact page's input is not sanitized, alloing for scripts. When an administrator views the comment a scipt in the comment can be run.
![green contact form xss gif](https://github.com/ramonpetgrave64/Cybersecurity-University-Project-8/blob/master/green%20xss.gif?raw=true)

## Red

Vulnerability #1: IDOR
The id parameter on the salesperson page allows anyone to view profiles of any salesperson, including terminated employees and profiles not meant to be public.
![red salesperson idor gif](https://github.com/ramonpetgrave64/Cybersecurity-University-Project-8/blob/master/red%20idor.gif?raw=true)

Vulnerability #2: __________________


## Notes

Describe any challenges encountered while doing the work
