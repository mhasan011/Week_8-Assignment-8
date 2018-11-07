# Project 8 - Pentesting Live Targets

Time spent: **5** hours spent in total

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

Vulnerability #1: Session Hijacking/Fixation: I can bypass the login by using another browser session ID, which can lead to steal users information.

GIF Walkthrough:

![blue_sessionid](https://user-images.githubusercontent.com/42792775/48116717-f320f400-e234-11e8-9384-4d419ff0f531.gif)



Vulnerability #2: SQL Injection

GIF Walkthrough:

![blue_sqli](https://user-images.githubusercontent.com/42792775/48116826-42ffbb00-e235-11e8-8128-53441640b969.gif)



## Green

Vulnerability #1: Cross-Site Scripting (XSS).

GIF Walkthrough:

![green_xss](https://user-images.githubusercontent.com/42792775/48116963-9d991700-e235-11e8-9331-88196646fca8.gif)



Vulnerability #2: Username Enumeration => It can perform if web application gives hints whether user exists or not.

GIF Walkthrough:

![green_userenum](https://user-images.githubusercontent.com/42792775/48117090-139d7e00-e236-11e8-8ce9-cafc4aa4cfe2.gif)



## Red

Vulnerability #1: Insecure Direct Object Reference => The red color site is missing code which would prevent some sensitive information from being made public.

GIF Walkthrough:



Vulnerability #2: __________________


## Notes

Describe any challenges encountered while doing the work
