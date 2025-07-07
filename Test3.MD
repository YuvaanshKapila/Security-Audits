Security Audit 3: Work Laptop at Community Center
Auditor: Yuvaansh Kapila
Date: July 5, 2025
Environment: Work laptop used at a local community center (Windows 10 Pro)

1. Purpose
I was helping at a community coding workshop. I used one of their older work laptops to set up Python and noticed some things that seemed risky. I decided to do a full audit.

2. System Details
Lenovo ThinkPad (Windows 10 Pro)

Not part of a domain

One local admin account used by everyone

Wi-Fi connected to public guest network

No physical locks or cable locks on the laptop

3. What I Investigated
a. User Accounts

One admin account called Admin

No password set

No other user accounts created

No restrictions on access or software installs

b. Protection Tools

No antivirus installed (Defender was disabled manually)

Firewall was on but with most exceptions allowed

No backup tool or recovery partition

Updates were disabled in the Services panel

c. Software and Logs

I checked installed programs and found

uTorrent

Outdated Chrome

No updates since early 2023

No event logs were being cleared

Internet history showed random users visiting shady sites

4. High Risks
Anyone could walk up and use the laptop

No password or login protection

No antivirus or active security software

Suspicious software like torrent client

Unsafe web usage

No logs or audit trail

5. What I Did and Recommended
Created a new standard user account

Set a password for the admin account

Re-enabled Windows Defender and ran a scan (found 2 potentially unwanted programs)

Installed Chrome updates and removed uTorrent

Turned on Windows Update again

Suggested to the staff

Buy a lock cable

Remove admin rights for shared use

Set up automatic updates

Install a free antivirus like Avast or Bitdefender

6. Conclusion
This work laptop was completely exposed. Anyone could have installed malware or stolen information. Some quick fixes helped but the organization needs better rules for shared computers.

