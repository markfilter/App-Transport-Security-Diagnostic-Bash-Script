# App-Transport-Security-Diagnostic-Bash-Script
This Bash Script is an executable that runs in Terminal. You double click the executable, enter in the URL endpoint at the prompt, and the script will run the ats-diagnostic --verbose  and give you the suggested ATS settings for your iOS application.

## Script Contents
```text
#!/bin/bash
read -p 'URL Endpoint: ' endpoint
nscurl --ats-diagnostics $endpoint --verbose
```

## How To Use
1. Clone Repo.
2. Double Click on executable.
3. In Terminal window, add URL Endpoint to test.
4. Hit Enter.
5. View recommended ATS settings to establish connection with server.

## License
MIT License
