# Send Email through Backend

**Technology Used**: NestJs

This project provides email services using nodemailer and sendgrid.

_Note_: For the time being I have commented out the sendgrid code, and working code is Nodemailer.

## Introduction

This project was created to provide email services for our web application. We chose to use nodemailer (and sendgrid) due to their ease of use, robust feature sets, and compatibility with our project's technology stack.

## Why Nodemailer and Sendgrid

We chose to use nodemailer for its simplicity and ease of use. It provides a straightforward API for sending emails, and its modular design makes it easy to customize and extend.

We also chose sendgrid because of its advanced features, including email analytics, recipient management, and email templates. Sendgrid's comprehensive API made it easy to integrate with our project, and its documentation and support were top-notch.

## How We Used Nodemailer and Sendgrid

We used nodemailer to handle basic email sending. We set up nodemailer with gmail's SMTP server configuration and used it to send emails using a simple API.

If we require any advanced email features, we will use SendGrid. With Sendgrid's API, we will manage email templates, track email analytics, and manage recipient lists. As SendGrid's API is well-documented and easy to use, it gave us the advanced email features we needed.

## Challenges Faced

One challenge we faced was configuring nodemailer to work with Gmail SMTP server. We initially encountered some issues with email authentication and security settings, but we were able to resolve these by adjusting our email provider's settings and following nodemailer's documentation.

- Enable Two-Factor Authentication
- Make App Password

## Conclusion

Overall, we found nodemailer and sendgrid to be excellent choices for our email services needs.

- Nodemailer provided a simple and easy-to-use API for basic email sending
- Sendgrid provided advanced features and robust analytics.

We would recommend these packages to other developers who are looking for reliable and feature-rich email services.
