Security Audit 2: School Lab Computer
Auditor: Yuvaansh Kapila
Date: July 6, 2025
Environment: Computer Lab PC at North High School Windows 10 Education

1. Purpose
This audit was done on a school computer in the programming lab. I used it during a Python class and wanted to see how secure the setup was especially since other students use the same machines.

2. Computer Info
Windows 10 Education

Part of the school domain

Intel i3 with 8 GB RAM

No admin access student user account

3. What I Checked
a. User Access and Restrictions

I could not install software or run PowerShell as admin good

Local C drive access was limited I could not open System32

Task Manager was enabled could be misused by some students

b. Antivirus and Updates

Defender was active and scanning

Virus definitions were 3 days old should be more frequent

Windows Update seemed disabled or controlled by group policy

c. Browser and Internet Controls

Tried going to blocked sites most adult gaming and social media were blocked

Some online games still worked through mirrors

Students could still use incognito mode

d. Shared Folder and Network

Public network folder was open to all users

Anyone could copy or delete files

No logging of file access as far as I could tell

Firewall was turned off used netsh advfirewall show allprofiles

4. Problems Found
Some game and chat sites were not blocked

Public folder was wide open

Defender was not updating fast enough

Firewall was disabled which surprised me

5. Suggestions
Turn on Windows Firewall using group policy

Force weekly Defender updates

Limit access to public folder and turn on file access logging

Block incognito mode through Chrome group policy

Improve DNS filtering to block game mirrors

6. Conclusion
The school system was set up to stop most bad stuff but there were a few holes. Students can find ways around filters and share stuff they should not. If the firewall is off on all computers that is a big deal and should be fixed.

