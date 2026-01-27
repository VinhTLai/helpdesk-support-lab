# Ticket 03: No Internet Connection

## Issue
User reported loss of internet connectivity and inability to access websites.
<img width="1024" height="678" alt="no_internet" src="https://github.com/user-attachments/assets/90d15e66-161b-4c9c-8115-8992b375bcf7" />


## Environment
- Device: Windows 11
- User Account: TestUser1
- Network Type: NAT (Virtualized Environment)

## Troubleshooting Steps
1. Checked network adapter status.
<img width="1024" height="768" alt="disabled_ethernet" src="https://github.com/user-attachments/assets/65265b76-7fad-4e70-af36-cda4e41119f8" />

2. Used ipconfig to verify IP address assignment.
3. Used ping to test network connectivity.
<img width="1024" height="720" alt="ping_failure" src="https://github.com/user-attachments/assets/0ea1a46a-e0d4-4ddb-bf02-f2e8913af2ca" />

4. Disabled and re-enabled the network adapter.
<img width="1024" height="768" alt="disabled_ethernet" src="https://github.com/user-attachments/assets/80d6a4c1-02dc-4e56-8011-dbb9c0a4806e" />
<img width="1024" height="768" alt="enabled_ethernet" src="https://github.com/user-attachments/assets/fff34361-9ced-435b-b731-c55d10bd71fa" />

## Tools Used
- PowerShell
- Network Settings

## Resolution
Network connectivity was restored after re-enabling the network adapter and verifying proper IP configuration.
<img width="1024" height="768" alt="ping_success" src="https://github.com/user-attachments/assets/05f98a2a-757f-4102-a322-0afe6137fb80" />
<img width="1024" height="768" alt="internet_works" src="https://github.com/user-attachments/assets/e7d5a4db-9e16-4dd8-9df8-bbba9379d44c" />

## Ticketing System
- Platform: osTicket
- Role: Help Desk Agent

## What I Learned
This ticket reinforced basic network troubleshooting techniques and the importance of verifying adapter and IP configuration.
