# Instructions

In this exercise you will audit the source code of the given application for security vulnerabilities.
Add your findings in the WRITE-UP.md file and send it back by email.

# Requirements

You need to install [Docker](https://docs.docker.com/get-docker/) to run the application.

# Context

This application allows a user to register one or multiple accounts with a unique username and link a public avatar to this username.
All pages are meant to be public except the page to edit an avatar.

# Scope

There is a limited amount of vulnerabilities to find. All of them are exploitable.

Here is a list of potential security problems in this application that you should *not* report:
* Application only accessible through HTTP
* Vulnerabilities in dependencies or the Docker image itself
* Missing security headers
* Missing brute force protection, rate limiting, or captchas
* User enumeration
* Hard-coded credentials
* Publicly accessible pages
