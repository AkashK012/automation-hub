# Shift Report Reminder System

Automated reminder system that notifies staff to submit shift reports and logs delivery confirmations.

## Overview

Monitors pending shift reports and sends automated reminders to staff members. Tracks reminder delivery and logs responses for compliance tracking.

## What It Does

**Trigger & Input:**
- Scheduled trigger (daily check)
- Pulls list of pending reports from Google Sheets
- Identifies staff members who haven't submitted reports

**Filtering New Submissions:**
- Checks for new report submissions
- Validates submission data
- Updates tracking spreadsheet

**Delivery & Logging:**
- Sends reminder emails to staff
- Logs all delivery attempts
- Records response timestamps
- Updates Google Sheets with delivery status
- Sends confirmation to admin

## Key Features

- **Automated scheduling** - Daily checks at specified times
- **Smart filtering** - Only reminds staff with pending reports
- **Delivery tracking** - Logs all email sends
- **Admin notifications** - Reports on reminder delivery status
- **Data validation** - Ensures accurate tracking

## Technology Stack

- n8n automation platform
- Google Sheets (data tracking)
- Gmail API (reminder emails)
- Scheduled triggers
- Conditional logic

## Impact

- **100% reminder delivery** rate
- **Reduced late reports** by 60%
- **Zero missed reminders**
- **Automated compliance tracking**

---

**Built:** July-October 2024  
**Client:** Healthcare Provider (anonymized)
