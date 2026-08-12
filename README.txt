M&N Foods LLC Dashboard — HTML Prototype

Open index.html in a browser.

Included:
- Dianne / Naveen / Dinos / Albert
- USD and Eastern Time
- Three locations: BK 1869, BK 2127, BK 20769
- Departments: Admin, Purchasing, Maintenance & Repair, General
- Add Task / Payment / Purchase / Maintenance / Project
- Check off tasks
- Nudge Center
- Daily reminder settings
- Calendar .ics export
- Excel-compatible .xls export
- Print-to-PDF via browser
- Email and Calendar connection placeholders

LIVE INTEGRATION NOTE:
The HTML is intentionally not storing passwords, OAuth secrets, Slack tokens, or API keys. For live email/calendar notifications, deploy this behind a small secure backend and connect Google/Microsoft OAuth there. After that, scheduled jobs can send reminders even when nobody has the dashboard open.
