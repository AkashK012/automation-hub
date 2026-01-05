# Daily Shift & Incident Report Generator

Automated reporting system that generates, formats, and distributes daily shift reports to healthcare staff via email and Google Drive.

## Overview

This workflow automatically collects shift data, formats it into professional reports, logs incidents, and distributes reports to relevant staff members. Built during internship at Young Logix for healthcare provider client.

## What It Does

**Debugging Mode:**
- Reads shift data from Google Sheets
- Formats report content
- Validates data integrity
- Checks recipient lists
- Tests email and Drive connections

**Shift Report Format:**
- Pulls shift data from multiple sources
- Merges information into single report
- Generates PDF document
- Stores in Google Drive folder structure
- Sends email notifications to staff

**Logs for SDA (Incident & Error Tracking):**
- Monitors system for incidents
- Logs errors and exceptions
- Creates incident records in Google Sheets
- Sends notifications for critical issues
- Maintains audit trail

**Conditional Logging and Routing:**
- Routes reports based on shift type
- Logs only when incidents occur
- Sends reports to appropriate staff members
- Handles multiple recipient groups

## Technical Features

- **Multi-step workflow** with conditional logic
- **Error handling** with fallback notifications
- **Data validation** before report generation
- **PDF generation** from formatted data
- **Google Drive integration** for file storage
- **Gmail API** for automated email delivery
- **Google Sheets** for data management and logging
- **Conditional routing** based on incident severity

## Impact

- **15+ hours/week** saved in manual report creation
- **100% on-time** report delivery
- **Zero missed incidents** through automated logging
- **50+ staff members** receiving automated reports
- **99% system uptime** over 3-month deployment period

## Workflow Components

1. **Debugging Nodes** - Test and validate data flow
2. **Shift Report Format** - Generate professional reports
3. **Create PDF** - Convert reports to PDF format
4. **Folder Management** - Organize files in Google Drive
5. **Log System** - Track incidents and errors
6. **Email Distribution** - Send reports to staff
7. **Conditional Logger** - Route based on incident type

## Technology Stack

- n8n automation platform
- Google Sheets API (data source)
- Gmail API (email delivery)
- Google Drive API (file storage)
- PDF generation
- JavaScript for data transformation
- Webhooks for real-time triggers

## Security Note

All credentials, API keys, client names, and staff information have been removed from this workflow. Generic placeholders are used for demonstration purposes.

---

**Project Duration:** July - October 2024  
**Client Type:** Healthcare Provider  
**Status:** Production deployment (anonymized for portfolio)
