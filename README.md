# dallas-hvac-lead-qualifier

AI lead qualifier + human-in-the-loop untuk owner HVAC Dallas.

## Problem
Lead masuk saat tim di job / malam. Iklan sudah dibayar, tidak ada yang balas.

## Scoring
- Darurat → telepon + SMS owner
- Normal (termasuk luar area) → staff
- Buang (spam / iseng) → catatan saja

## Flow
lead masuk → extract → score → auto-reply → sheet → routing manusia

## Samples
Lihat `samples/leads.json`
