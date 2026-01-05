# Weekly Report & Task Generator with Logger

Automated weekly report generation system that creates task lists, distributes reports to multiple teams, and maintains comprehensive logging.

## Overview

Generates weekly summary reports, creates task assignments, and distributes to relevant departments. Includes multi-output delivery system and detailed logging for audit trails.

## What It Does

**Scheduled Trigger:**
- Runs automatically every week
- Pulls data from Google Sheets
- Aggregates weekly statistics

**Attendance Tracking:**
- Monitors staff attendance
- Calculates attendance metrics
- Generates attendance reports

**Multi-Output Delivery:**
- **Route 1:** Management team reports
- **Route 2:** Operations team updates  
- **Route 3:** Admin summaries
- Each route receives customized report format

**Task Generation and Logger:**
- Creates weekly task lists
- Assigns tasks to team members
- Logs all task assignments
- Tracks task distribution
- Maintains audit trail in Google Sheets

## Key Features

- **Multi-route delivery** - Different reports for different teams
- **Attendance integration** - Automatic attendance tracking
- **Task automation** - Weekly task list generation
- **Comprehensive logging** - Full audit trail
- **Customized outputs** - Tailored reports per department

## Technology Stack

- n8n automation platform
- Google Sheets (data source & logging)
- Gmail API (report distribution)
- Scheduled triggers (weekly automation)
- Conditional routing
- JavaScript transformations

## Impact

- **6+ hours/week** saved in manual report creation
- **100% on-time** weekly report delivery
- **Complete audit trail** for compliance
- **3 departments** receiving automated reports
- **Zero missed task assignments**

---

**Built:** July-October 2024  
**Client:** Healthcare Provider (anonymized)
