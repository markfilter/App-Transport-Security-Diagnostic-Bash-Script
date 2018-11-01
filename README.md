# App-Transport-Security-Diagnostic-Bash-Script
This Bash Script is an executable that runs in Terminal. You double click the executable, enter in the URL endpoint at the prompt, and the script will run the ats-diagnostic --verbose  and give you the suggested ATS settings for your iOS application.

## Script Contents
```text
#!/bin/bash
read -p 'URL Endpoint: ' endpoint
nscurl --ats-diagnostics $endpoint --verbose
```
