# Diagnosing Network Connectivity Issues Using Command Line Tools

## A user reports no internet access despite being connected to Wi-Fi.

Objective:
Identify and resolve network connectivity issues.

Tools Used:
Command Prompt
ipconfig
ping
tracert

Steps Taken:
Ran ipconfig to check IP address
Identified missing/invalid IP configuration
Renewed IP using:
ipconfig /release
ipconfig /renew
Tested connection using ping google.com
Used tracert to analyze route if needed

Resolution:
Network connection restored after IP refresh.

Key Takeaways:
IP issues are a common cause of connectivity problems
Command-line tools are essential for quick diagnostics
Step-by-step isolation helps pinpoint issues faster
