# Ticket 02: Printer Offline

## Issue
User reported that the printer appeared offline and documents could not be printed.

## Environment
- Device: Windows 11
- User Account: TestUser1
- Printer Type: Network Printer (simulated)

## Troubleshooting Steps
1. Verified printer status in Windows printer settings.
2. Checked printer queue for stuck jobs.
<img width="794" height="676" alt="printer_error" src="https://github.com/user-attachments/assets/7591bf7c-eebd-4875-9610-dec406f8f65e" />

3. Restarted the Print Spooler service.
<img width="1024" height="768" alt="restart_print_spooler" src="https://github.com/user-attachments/assets/33bd81ce-d048-443b-bb49-92531e8ce573" />

4. Removed and re-added the printer.

## Tools Used
- Windows Settings
- Services (Print Spooler)

## Resolution
Printer was successfully re-added and returned to an online state. Printing functionality was restored.
<img width="1024" height="768" alt="print_succeeds" src="https://github.com/user-attachments/assets/eb0cb6dc-9e75-47ee-895c-7db72ded25b1" />


## Ticketing System
- Platform: osTicket
- Role: Help Desk Agent

## What I Learned
This ticket improved my understanding of printer services and how restarting the Print Spooler can resolve common printer issues.

