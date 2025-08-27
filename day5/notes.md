# Day 5 – head/tail + sort/uniq

## Linux practice
- Created `list.txt` with repeated fruit names.
- Used `head -n 3` and `tail -n 2` to preview file ends; saved to `preview.txt` (used `>` then `>>` to append).
- De-duplicated lines with `sort | uniq` → `unique_list.txt`.
- Counted occurrences with `sort | uniq -c` → `unique_counts.txt`.

## Commands learned
- `head -n N file` → first N lines of a file.
- `tail -n N file` → last N lines of a file.
- `sort` → alphabetically sort lines.
- `uniq` / `uniq -c` → remove duplicates / show counts (expects sorted input).
- `>` vs `>>` → overwrite vs append.
- `|` (pipe) → send output of one command into the next.

## Cert progress
- Google Cybersecurity Professional Certificate: **Course 2, Module 2** (≈45–60 min today).
