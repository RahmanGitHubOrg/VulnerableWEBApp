# VulnerableWEBApp
Coded a sample vulnerable web application for learning purpose..

It has following vulnerabilities which can be exploited

--> SQLI (Select , Update , Insert, Delete)
[select SQLI in login bypass]
[Insert SQLI in Register process]
[Update SQLI in profile update , changing password]
[Delete SQLI in Deleting account]

--> Clickjacking (Framebursting technique, X-frame options missing)
[Framebursting is used in all the pages which can be exploited using sandbox="allow-forms" ]
[X-frame options missing in all pages]

-->Insecure Direct Object reference
[Account deletion ]
[Password change]

-->Command Injection
[ping functionality vulnerable to command injection using | we can concatenate commands]

-->CSRF
[ csrf token missing]

-->XSS
[No user input enconding/sanitizaion . output also without encoding/sanitization which is vulnerable to xss ]
