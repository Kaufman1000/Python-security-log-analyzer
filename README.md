# Python-security-log-analyzer
# A simple cybersecurity project that analyzes system, firewall, IDS, and web server logs using Python.


# Python Security Log Analyzer

A simple cybersecurity project that analyzes system, firewall, IDS, and web server logs using Python.

## Features

- Reads log files
- Detects and extracts:
  - INFO messages
  - ERROR messages
  - Failed SSH login attempts
- Counts security events
- Generates a security report

## Example Logs Parsed

- Apache / Nginx logs
- Firewall logs
- IDS alerts
- SSH authentication logs

## Technologies Used

- Python
- File Handling
- Log Parsing

## How It Works

1. The script reads a log file.
2. It searches for specific security events.
3. It prints detected events.
4. It generates a summary report.

## Run the Script

```bash
python log_analyzer.py
