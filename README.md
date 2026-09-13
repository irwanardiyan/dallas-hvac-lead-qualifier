# dallas-hvac-lead-qualifier

AI lead qualifier with human-in-the-loop routing for a Dallas HVAC business.

## Problem

Leads arrive while the crew is on a job or after hours. Ad spend is already paid, but nobody replies in time.

## Scoring

- Urgent → call + SMS the owner immediately
- Normal (including out-of-area) → route to staff
- Junk (spam / prank) → log only

## Flow

```text
lead in → extract → score → auto-reply → sheet → human routing
```

## Samples

See `samples/leads.json`.
