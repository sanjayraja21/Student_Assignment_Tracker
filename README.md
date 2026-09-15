# Student_Assignment_Tracker
n8n automation workflow for tracking student assignments and sending deadline reminders.
# Student Assignment Tracker

An n8n automation workflow that helps students track assignment details and receive email reminders about upcoming deadlines.

## Features

* Student assignment submission form
* Student name and email collection
* Subject and assignment details
* Assignment deadline tracking
* Priority selection
* Input validation
* Assignment data storage
* HTTP request processing
* Automatic Gmail reminder
* Simple n8n workflow automation

## Workflow

```text
Student Form
     ↓
Validation
     ↓
Store Assignment
     ↓
HTTP Request
     ↓
Gmail Reminder
```

## Technologies Used

* n8n
* n8n Form Trigger
* n8n Data Table
* HTTP Request
* Gmail
* JSON

## How to Use

1. Download or clone this repository.
2. Open n8n.
3. Import `Assignment_remainder.json`.
4. Configure your own n8n Data Table.
5. Connect your own Gmail OAuth credential.
6. Test the form.
7. Activate the workflow when everything works correctly.

## Important Security Note

This repository contains a sanitized workflow template.

Do not add the following to GitHub:

* API keys
* OAuth client secrets
* Gmail access tokens
* Gmail refresh tokens
* Passwords
* `.env` files containing secrets
* Private credentials

Configure your own credentials inside n8n after importing the workflow.

## Project Purpose

The project demonstrates how n8n can automate student assignment tracking and email reminder tasks using a simple workflow without manually managing every reminder.

