# Smart Lead Management Automation

A no-code workflow automation project built with Google Sheets, Make.com, and Gmail under the **Full Potential** brand.

## Overview

This project automates email notifications for new leads recorded in a Google Sheets tracker. Make.com checks for new rows on a schedule and sends an email containing the lead's details.

## Problem

Manually checking a spreadsheet for new leads can delay follow-up and create unnecessary administrative work.

## Solution

Connect Google Sheets to Gmail through Make.com to notify the recipient when a new lead is detected.

## Technology Stack

- **Google Sheets:** Lead data storage
- **Make.com:** Workflow automation and scheduling
- **Gmail:** Email notifications

## Workflow

1. Add a new lead as a row in Google Sheets.
2. Make.com checks the sheet on its configured schedule.
3. The workflow retrieves the new row's fields.
4. Gmail sends a notification containing the mapped details.
5. The recipient can follow up with the lead.

## Lead Tracker Fields

- Name
- Email
- Business
- Requirements
- Status

## Testing and Results

The workflow was tested end to end.

- A test email arrived with the expected lead details.
- After the scenario was activated, adding another spreadsheet row triggered an email automatically.
- Long-term reliability, average notification delay, duplicate handling, and business impact have not yet been measured.

## Current Limitations

- The workflow depends on valid Google and Gmail connections.
- Notification timing depends on the configured schedule and successful execution.
- This version sends notifications; it does not provide a complete CRM or automatically qualify leads.
- Error recovery and duplicate handling need additional testing.

## Future Improvements

- Add follow-up reminders.
- Record lead creation and follow-up dates.
- Improve error monitoring and duplicate protection.
- Measure successful notifications and time saved over a longer test period.

## Security

Only fictional or anonymized lead information should be used in public demonstrations. Do not publish credentials, API keys, private connection details, or customer data.

## Author

**Full Potential** — Practical automation projects using accessible tools to simplify business workflows.