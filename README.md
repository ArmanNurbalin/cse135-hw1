# Homework 1
## Team
- Arman Nurbalin
## Site
- armannur.site
## For grader
- username: grader
- password: grader
## Github Auto Deploy
For the github auto deploy I used git hooks as was explained on the website provided on the assignment page
## Login
- username: arman
- password: testPassword1s
- username: grader
- password: grader
## Compression
The only change I noticed was that in the HTML file the Content-Encoding changed to gzip. Other than that I didn't notice any other changes.
## Server Header
For the server header I first used mod_headers, but the server header did not change so after digging online I found out that I should add mod_security and add a directive into my security.conf after which the server header changed to the intended one.
