# Workflow

n8n workflow lives here.

Happy path:
1. Webhook receives a lead JSON
2. AI extracts name, phone, address, message
3. Score: emergency | normal | spam
4. Reply to humans (not spam)
5. Log every lead to Google Sheet
6. Route: emergency → owner call/SMS, normal → staff, spam → log only

Export the n8n workflow JSON into this folder when it runs.
