# Week 4
- Used Google's "AI Overview" to figure out how to install nginx using chocolatey
    - Prompt: chocolately install nginx
    - Answer: To install Nginx using Chocolatey, run the command choco install nginx in an elevated command prompt or PowerShell window. This process requires administrative privileges.
- Used ChatGPT to figure out why I was getting an error 403 when trying to access a website running in a docker container with an nginx image. 
    - Prompt: docker nginx image giving error 403
    - Answer By default, Nginx expects:  
    index.html  
    index.htm  
    If the directory exists but doesn’t contain one → 403 Forbidden.
