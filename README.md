# App-Transport-Security-Diagnostic-Bash-Script
This Bash Script is an executable that runs in Terminal. You double click the executable, enter in the URL endpoint at the prompt, and the script will run the ats-diagnostic --verbose  and give you the suggested ATS settings for your iOS application.

## Script Contents
```text
#!/bin/bash
read -p 'URL Endpoint: ' endpoint
nscurl --ats-diagnostics $endpoint --verbose
```


## License

The source code for this ATS Script is licensed under the MIT License. 

Copyright (c) 2018 Mark Filter

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
