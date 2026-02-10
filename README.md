# Intelligent_Lead_Management_System

This scenario automates lead enrichment and management by integrating email verification, person and company enrichment, and lead source tracking.

**Requirements:**
1. Make.com Account
2. Create API of Hunter io
3. create airtable,google sheet, typeform, Linked Lead Form modules account.

**Importing the Scenario:**
1. Download Json file.
2. Open your Make.com dashboard.
3. Click “Create a new scenario”.
4. Click “Import scenario” (usually available at the top-right menu).
5. Upload the scenario JSON file provided.
6. Wait for the import to complete — all modules and connections will appear.

**Setup**
1. Connect your accounts:
- Go through each module (HTTP, Airtable, Google Sheets, etc.) and connect your respective accounts.
- Add API keys for email verification, Clearbit/Hunter, or other enrichment services.

2. Configure webhooks :
- For modules triggered by forms or other services, copy the webhook URL from the main scenario (Intelligent lead management system).
- Paste it in the source service (e.g., Typeform form settings, website form, LinkedIn automation).
3. Scheduler:
- for daily report scenario add a scheduler for timing on which you want to send daily summary.

Main Workflow:
<img width="1493" height="694" alt="image" src="https://github.com/user-attachments/assets/e92083aa-3e13-4546-aca1-d35117770713" />

Daily Report Workflow:
<img width="1334" height="527" alt="image" src="https://github.com/user-attachments/assets/12ffbe54-ac45-497f-b5b4-6aa3077726ef" />





