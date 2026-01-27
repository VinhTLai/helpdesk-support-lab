# Ticket 03: No Internet Connection

## Issue
User reported loss of internet connectivity and inability to access websites.

## Environment
- Device: Windows 11
- User Account: TestUser1
- Network Type: NAT (Virtualized Environment)

## Troubleshooting Steps
1. Verified user could not access websites.
<img width="1024" height="678" alt="no_internet" src="https://github.com/user-attachments/assets/90d15e66-161b-4c9c-8115-8992b375bcf7" />

2. Checked network adapter status and found it disabled.
<img width="1024" height="768" alt="disabled_ethernet" src="https://github.com/user-attachments/assets/2ed2e979-93ab-4ca8-95d4-a3446b2814bd" />

3. Used ipconfig to confirm lack of IP connectivity.
4. Tested connectivity using ping.
<img width="1024" height="720" alt="ping_failure" src="https://github.com/user-attachments/assets/b71c3f23-28dc-4e32-a107-7b801d008010" />

5. Re-enabled network adapter.
<img width="1024" height="768" alt="enabled_ethernet" src="https://github.com/user-attachments/assets/96f5f9b4-7374-45a0-9f9b-2a582f33df08" />

11. Verified restored connectivity.
<img width="1024" height="768" alt="ping_success" src="https://github.com/user-attachments/assets/05f98a2a-757f-4102-a322-0afe6137fb80" />
<img width="1024" height="768" alt="internet_works" src="https://github.com/user-attachments/assets/54d0b0f3-7c6a-4bea-ae64-6f929049bee9" />


## Tools Used
- PowerShell
- Network Settings

## Resolution
Network connectivity was restored after re-enabling the network adapter and verifying proper IP configuration.

## Ticketing System
- Platform: osTicket
- Role: Help Desk Agent

## What I Learned
This ticket reinforced basic network troubleshooting techniques and the importance of verifying adapter and IP configuration.
