Security Audit 1: My Personal Laptop
Auditor: Yuvaansh Kapila
Date: July 7, 2025
Device: HP Pavilion Laptop (Windows 11 Home)

1. Purpose
The goal was to check how secure my own laptop is. I use it for school, coding, email, and testing cybersecurity tools like Snort. I wanted to make sure it is not an easy target for malware, tracking, or hacking.

2. System Info
Windows 11 Home version 23H2

16 GB RAM, Intel Core i5

Local admin account not connected to Microsoft account

Regular user account for daily use

3. Audit Process
I checked the following areas

a. System Updates

Windows Update was working and had last run 2 days ago

All important patches were installed

I had paused updates for one week, which I have now resumed

b. Antivirus and Firewall

Windows Defender is running and fully updated

Did a full system scan and no threats were found

Firewall is on for all profiles Private, Public, Domain

I tested with Nmap from my other VM and most ports were closed

c. Account and Access

I had only one admin account and one standard user

No password was set on the admin account before the audit I added one now

BitLocker was off I turned it on after the audit

No two factor authentication for logins I have now enabled Windows Hello PIN and face unlock

d. Network Settings

I checked for open ports using netstat and nothing suspicious came up

No remote desktop was enabled

My Wi-Fi was set to Private network not Public

I disabled file and printer sharing

4. Issues Found
Admin account did not have a password

BitLocker encryption was not enabled

No two factor login protection

Windows Update was paused

5. What I Fixed
Set a strong password for admin

Turned on BitLocker to encrypt my drive

Enabled face unlock using Windows Hello

Turned on two factor login for Google and GitHub accounts

Resumed Windows Updates

6. Conclusion
My laptop was mostly secure but I missed some key things like encryption and account protection. Now that I fixed those I feel safer using it for school and personal projects.

