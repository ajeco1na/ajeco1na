Corporate Mail Server Deployment & Support Documentation
Overview

This project documents the deployment and operational support of a self-hosted corporate email service built using Mailcow (Dockerized) and SOGo Webmail, hosted on a Linux VPS and secured through proper DNS and email authentication mechanisms.

The project was designed and documented with a support-first mindset, focusing on end-user usability, onboarding, troubleshooting, and security best practices, while also demonstrating foundational system administration and infrastructure skills.

This repository serves as a portfolio project aimed at IT Support Level 1 / Helpdesk roles within professional IT environments.

Target Roles

IT Support Level 1 / Helpdesk Technician

Junior IT Technician

Entry-level Systems Support

Key Responsibilities Demonstrated
IT Support & Helpdesk Skills

User account and mailbox provisioning

Webmail (SOGo) user support

Password management and basic security guidance

End-user documentation for non-technical staff

First-level troubleshooting of email delivery issues

Communication with users and management

Supporting Infrastructure Knowledge

Linux VPS environment awareness

Docker-based service deployment (Mailcow)

DNS record configuration and propagation

Email authentication concepts (SPF, DKIM, DMARC)

Understanding of spam filtering behavior across clients

Project Scope

The scope of this project includes:

Deployment of a corporate email service on a VPS

Configuration of DNS records using Cloudflare

Creation and onboarding of user mailboxes

Validation of email deliverability and spam behavior

Documentation for both end users and future IT administrators

Post-deployment verification and tuning

This project intentionally focuses on operational readiness and user support, rather than advanced automation or high-availability clustering.

Technical Stack (High-Level)
Component	Purpose
Mailcow (Dockerized)	Complete mail server platform
Postfix	SMTP mail transfer
Dovecot	IMAP/POP3 access
SOGo	Webmail, calendar, contacts
Rspamd	Spam filtering
ClamAV	Antivirus scanning
Docker & Docker Compose	Service orchestration
Linux VPS (Webdock)	Hosting environment
Cloudflare DNS	Domain and DNS management
TLS Certificates	Encrypted communication
User-Facing Support Features

Webmail access through SOGo

Email, calendar, and contact management

Browser-based access (no client configuration required)

Clear security and usage guidelines

Support escalation instructions

All user interaction flows are documented in a non-technical, executive-friendly format.

Documentation Included
📄 Mail Server Deployment Timeline

mailserver-deployment-timeline.pdf

This document provides a chronological log of the deployment process, including:

VPS acquisition and initial setup

Domain purchase and DNS configuration

Docker daemon initialization

Mail service activation

User mailbox creation

Email testing and spam classification results

Post-deployment adjustments and lessons learned

This timeline demonstrates real-world implementation and troubleshooting, including expected issues such as DNS propagation delays and DMARC warm-up behavior.

📄 User & Administrator Mail Service Guide

mailserver-user-and-admin-guide.pdf

This guide was written for:

Non-technical users

Management and executives

IT Support personnel onboarding new users

It covers:

How to access the mail service

Using SOGo (email, calendar, contacts)

Security best practices

Support and escalation procedures

High-level technical architecture (for IT staff reference)

Common Support Scenarios Covered

User cannot log in to webmail

Password reset and credential issues

Email sent to spam folders (Outlook vs Gmail behavior)

DNS propagation delays affecting delivery

User education on phishing and suspicious emails

These scenarios reflect real IT support workflows rather than theoretical lab setups.

Lessons Learned

Email reputation depends heavily on DNS configuration and time

DMARC enforcement may require up to 48 hours to stabilize

Different mail clients handle spam scoring differently

Clear user documentation significantly reduces support load

Proper onboarding prevents most first-level incidents

Why This Project Matters for IT Support

This project demonstrates:

Ability to follow structured deployment procedures

Clear written communication with non-technical users

Awareness of common email-related support tickets

Understanding of where support ends and escalation begins

Professional documentation standards used in real IT teams

Author

Angel Colina
IT Support / Systems Support Portfolio Project
January 2026

Notes

All sensitive information has been sanitized

No live credentials or production systems are exposed

This repository is intended for demonstration and evaluation purposes only