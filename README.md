# Security

## Some Concepts

### Cross-Origin Resource Sharing (CORS)

<p align="center">
  <img src="https://github.com/RobertoFreireFerrazPassos/Security/blob/main/img/CORS.jpeg?raw=true">
</p>

### Hashing password and salt

When creating the user for the first time, the database doesn't store the actual password. 

<p align="center">
  <img src="https://github.com/RobertoFreireFerrazPassos/Security/blob/main/img/hashpasswordandsalt.PNG?raw=true">
</p>

To validate the login:

- the application get the password (provided by the user) and the salt (stored in the database using user identification like e-mail)
- the application hash these password and salt and validate with the hash stored in the database

## Most common attacks:

Injection Attacks

Broken Authentication

Sensitive Data Exposure

XML External Entities

Broken Access Control

Security Misconfiguration

Cross-Site Scripting (XSS)

Insecure Deserialization

Using Components With Known Vulnerabilities

Insufficient Logging and Monitoring

# References:

https://www.youtube.com/watch?v=rWHvp7rUka8&list=PLyqga7AXMtPPuibxp1N0TdyDrKwP9H_jD&ab_channel=F5DevCentral
