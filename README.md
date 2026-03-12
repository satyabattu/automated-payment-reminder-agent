# Email Reminder Automation

This project is an automated email reminder system built using n8n.

## How it works

1. A scheduled trigger runs daily.
2. The workflow reads rows from a Google Sheet.
3. A JavaScript node filters rows where the payment date matches today's date.
4. If a match is found, an email reminder is sent automatically using Gmail.

## Workflow

Schedule Trigger → Google Sheets → JavaScript Filter → Gmail

## Technologies Used

- n8n
- Google Sheets API
- Gmail API
- JavaScript

## Use Case

Automates payment reminders so users don't have to manually track due dates.
