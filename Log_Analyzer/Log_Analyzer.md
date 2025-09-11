# Project Description
The goal of this project is to create a lightweight Python script that helps analyze log files for suspicious activity. Security engineers often have to comb through endless lines of system or application logs, and doing that by hand is inefficient. This script automates the process by scanning logs, filtering specific events (like failed login attempts or access from unusual IPs), and presenting the results in a more readable format.

In short: we want a script that takes in a log file and gives us back useful, filtered security-relevant information. It doesn’t need to be massive or fancy — just something practical that works.

## What We Intend to Accomplish
- Practice scripting basics in Python (file handling, command-line arguments, string searching, etc.).
- Automate a real-world task: instead of manually searching logs, the script will handle it.
- Make it reusable so we can run the script on different log files with different filters.

## Project Outline
- Input Handling
- Script accepts a log file as input.
- User can specify filters via command-line arguments (e.g., keyword = “Failed password”).
- Log Parsing
- Open the log file, read it line by line.
- Search for the given keyword(s).
- Collect and store matching lines.
- Output Formatting
- Display the suspicious entries in a clean, readable way.


Count number of suspicious events.

Color-code or highlight results in the terminal.
