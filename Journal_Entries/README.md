# Journal Entries

This folder stores dated personal/professional journal entries used with the public goal tracker MVP.

Directory structure

Journal_Entries/
├─ YYYY/
│  └─ MM/
│     └─ YYYYMMDD.md

Naming conventions

- Year: 4 digits (e.g., 2025)
- Month: 2 digits, zero-padded 01–12 (e.g., 09)
- Entry file: YYYYMMDD.md (e.g., 20250928.md)

Example

- 2025-09-28 → Journal_Entries/2025/09/20250928.md

How to add a new entry

1. Create the month folder if it does not exist: Journal_Entries/YYYY/MM
2. Create the file YYYYMMDD.md inside that folder.
3. Commit the file with a descriptive message.

Suggested entry outline (optional)

# Manifesto / Reflection

- What did I do today?
- What did I learn?
- What will I improve tomorrow?

Time zone

- Use your local time zone for dating entries (currently Asia/Seoul, UTC+9).

Git tips

- Keep one entry per day.
- Use clear, concise commits describing the entry.
- Do not retroactively rename dated files.

Notes

- The directory names and file names are strictly numeric to keep sorting natural.
- This repository follows a “continuous improvement” approach: ship MVP first, refine over time.