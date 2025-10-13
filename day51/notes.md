# Day 51 – tail -f real-time log monitoring

## Linux practice
- Created a mock system log (`live_log.log`).
- Used `tail -f` to monitor new log entries live.
- Added new lines from a second terminal to simulate real system activity.
- Saved the final output to `final_log_output.txt`.

## Commands learned
- `tail -f file` → continuously watch a file as it updates.
- `>>` → appends text to a file.
- `Ctrl + C` → stops the live view.

## Use case
- Perfect for monitoring logs in cybersecurity or server management.
- Commonly used to watch `/var/log/auth.log`, `/var/log/syslog`, or web server logs.

## Cert progress
- Google Cybersecurity Professional Certificate: **Course 5, Module 5** (≈45–60 min today).
