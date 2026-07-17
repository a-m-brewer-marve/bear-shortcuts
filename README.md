# Bear daily note shortcuts — Obsidian date tags

## What is included

- **Bear — Create Daily Note (Obsidian Date Tags)**
  - creates a daily note titled `yyyy-MM-dd` (for example, `2026-07-17`);
  - creates `JOURNAL` and `LOG` sections; and
  - places the Bear hierarchy tag `#yyyy/MM/yyyy-MM-dd` at the foot of the note (for example, `#2026/07/2026-07-17`).

- **Bear — Log Daily Note (Obsidian Date Tags)**
  - asks for a multiline entry;
  - turns each entered line into a timestamped Markdown bullet; and
  - adds it immediately beneath the `LOG` heading in today’s note.

## Install

1. Download both `.shortcut` files to an iPhone/iPad/Mac with **Shortcuts** and **Bear** installed.
2. Open each file in Shortcuts and choose **Add Shortcut**.
3. Run **Create Daily Note** once before using **Log Daily Note**. Optionally create a personal automation in Shortcuts to run the former each morning.

## Important date-format detail

Apple Shortcuts custom date formatting uses lowercase `dd` for day of month. `DD` means day of year, so the requested practical tag format is `yyyy/MM/yyyy-MM-dd`, not `yyyy/MM/yyyy-MM-DD`.

## Provenance

These are minimally adapted copies of Patrick La Roque’s published **Create Daily Note in Bear 2** and **Log to Bear 2 Daily Note** workflows. Only the date/title/tag logic and explanatory comments were changed:

- https://www.laroquephoto.com/blog/2024/3/7/bear-days-the-shortcuts
- https://community.bear.app/t/minimalist-daily-note-shortcut-and-many-others/13595

Bear’s documented actions support creating notes and appending text at a named heading; these files use Bear’s native Shortcut actions for that purpose.
