# HTML Authentication System POC

## Project Description
This is a simple HTML-based authentication proof of concept (POC) built using only plain HTML.
No CSS or JavaScript is used.

## Pages Included
1. `login.html`
2. `register.html`
3. `forgot-password.html`
4. `reset-password.html`
5. `dashboard.html`

## Redirection Flow
- Login -> Dashboard (`login.html` -> `dashboard.html`)
- Register -> Login (`register.html` -> `login.html`)
- Forgot Password -> Reset Password -> Login (`forgot-password.html` -> `reset-password.html` -> `login.html`)
- Dashboard Logout -> Login (`dashboard.html` -> `login.html`)

## GitHub Repository
https://github.com/gous-gzone/-html-authentication-poc.git

## Notes
- This repository is public.
- This project uses only HTML forms, inputs, and anchor tags for navigation.