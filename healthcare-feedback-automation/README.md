
# Healthcare Automation Workflows

Collection of production automation workflows built during internship at Young Logix (July-October 2025) for healthcare provider client managing 50+ staff members.

## Overview

These workflows automated critical operational processes including shift reporting, staff notifications, incident logging, and compliance tracking. Combined impact: 20+ hours/week saved in manual work with 99% system uptime.

## Projects

### 1. Daily Shift & Incident Report Generator
Automated daily shift report generation with incident logging and multi-recipient distribution.

**Key Features:**
- Automated report formatting and PDF generation
- Conditional incident logging
- Google Drive file organization
- Multi-recipient email distribution

**Impact:** 15+ hours/week saved, 100% on-time delivery

[View Project →](./daily-shift-incident-report)

---

### 2. Shift Report Reminder System
Automated reminder system tracking pending shift reports with delivery confirmation.

**Key Features:**
- Daily automated checks for pending reports
- Smart filtering of submission status
- Delivery tracking and logging
- Admin notifications

**Impact:** 60% reduction in late reports, 100% reminder delivery rate

[View Project →](./shift-report-reminder)

---

### 3. Weekly Report & Task Generator
Weekly summary report generation with task assignment and multi-department distribution.

**Key Features:**
- Attendance tracking integration
- Multi-route delivery system
- Automated task list generation
- Comprehensive audit logging

**Impact:** 6+ hours/week saved, 3 departments automated

[View Project →](./weekly-report-task-generator)

---

## Technology Stack

- **Platform:** n8n automation
- **Email:** Gmail API
- **Storage:** Google Drive API
- **Database:** Google Sheets
- **Logic:** JavaScript transformations
- **Triggers:** Scheduled & webhook-based

## Overall Impact

- **20+ hours/week** total time saved
- **100% on-time** delivery for all automated processes
- **Zero data loss** incidents
- **Complete audit trails** for compliance

## Skills Demonstrated

- Complex workflow automation
- API integration (Google Workspace)
- Error handling and reliability engineering
- Multi-step conditional logic
- Data transformation and validation
- Healthcare data handling (HIPAA-aware practices)
- System documentation and knowledge transfer

## Security & Privacy

All workflows have been sanitized for portfolio use:
- API keys and credentials removed
- Staff names and emails anonymized
- Client information replaced with generic placeholders
- Sensitive data structures preserved to demonstrate technical complexity

## Files Included

Each project folder contains:
- `README.md` - Detailed project documentation
- `workflow-screenshot.png` - Visual workflow overview
- `workflow.json` - Complete n8n workflow (credentials removed)


**Built by Akash Kunwar**  
Automation Engineer | Building tools that save time  
[LinkedIn](https://linkedin.com/in/akash-kunwar-300530334/) | [GitHub](https://github.com/AkashK012)
```


**Structure:**
```
healthcare-automation-workflows/
├── README.md (THIS FILE - overview of all 3 projects)
├── daily-shift-incident-report/
│   ├── README.md (specific to this workflow)
│   ├── workflow-screenshot.png
│   └── workflow.json
├── shift-report-reminder/
│   ├── README.md
│   ├── workflow-screenshot.png
│   └── workflow.json
└── weekly-report-task-generator/
    ├── README.md
    ├── workflow-screenshot.png
    └── workflow.json
