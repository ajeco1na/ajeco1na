# Corporate Mail Server – IT Support Portfolio Project

> Production-ready corporate email service deployed and supported with a focus on
> end-user usability, documentation, and first-level IT support operations.

This project documents the **deployment, support, and user onboarding** of a self-hosted
corporate mail server using **Mailcow (Dockerized)** and **SOGo Webmail**, hosted on a
Linux VPS and managed through Cloudflare DNS.

🔹 Primary focus: **IT Support Level 1 / Helpdesk**  
🔹 Secondary focus: **Junior SysAdmin exposure**

---

## Project Snapshot

- ✔ User mailbox provisioning and onboarding  
- ✔ Webmail (SOGo) end-user support  
- ✔ Password and access troubleshooting  
- ✔ Email delivery and spam investigation  
- ✔ End-user and executive documentation  
- ✔ Real deployment timeline and testing  

---

## Architecture Overview

![Mail Server Architecture](diagrams/architecture.png)

The service is built on a Dockerized mail platform running on a Linux VPS, providing
secure SMTP/IMAP services, webmail access, spam filtering, and antivirus protection.

---

## User Interface (SOGo Webmail)

### Login Screen
![SOGo Login](assets/screenshots/sogo-login.png)

### Inbox View
![SOGo Inbox](assets/screenshots/sogo-inbox.png)

SOGo allows users to manage email, calendars, and contacts from a single web interface,
reducing client-side configuration and support overhead.

---

## Documentation & Evidence

### 📄 Deployment Timeline
A step-by-step chronological log covering:
- VPS provisioning
- Domain and DNS setup
- Mail service initialization
- User creation
- Deliverability testing and tuning

➡️ `mailserver-deployment-timeline.pdf`

---

### 📄 User & Admin Guide
Written for **non-technical users and management**, covering:
- How to access the service
- Using SOGo (email, calendar, contacts)
- Security best practices
- Support and escalation procedures

➡️ `mailserver-user-and-admin-guide.pdf`

---

## Common IT Support Scenarios

- User cannot access webmail
- Password reset requests
- Emails delivered to spam folders
- DNS propagation delays affecting delivery
- Outlook vs Gmail spam behavior
- User education on phishing attempts

These scenarios reflect **real first-level support tickets**.

---

## Lessons Learned

- DNS and email reputation require stabilization time
- DMARC enforcement can take up to 48 hours
- Clear documentation significantly reduces support load
- Webmail solutions simplify user support
- Proactive user education prevents incidents

---

## Author

**Angel Colina**  
IT Support / Systems Support Portfolio  
January 2026

