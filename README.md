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

---

## Contributors

Thanks to everyone who builds with this project! 🙏

<a href="https://github.com/irwanformal-cmd">
  <img src="https://github.com/irwanformal-cmd.png?size=100" width="50" height="50" style="border-radius:50%" alt="irwanformal-cmd" />
</a>

**[@irwanformal-cmd](https://github.com/irwanformal-cmd)** — creator & maintainer
