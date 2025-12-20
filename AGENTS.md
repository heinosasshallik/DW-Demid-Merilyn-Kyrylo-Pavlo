# AGENT GUIDANCE

## Priority
1) Preserve user-written session notes as the single source of truth; if a PDF/book conflicts, favor session notes unless explicitly told otherwise.
2) Write verbose, future-proof summaries; do NOT omit details the user mentioned. Add structure/clarity, not brevity.
3) Keep items/locations fully statted and tagged; if a value is unknown/TBD, mark it clearly and add a TODO on the landing page.
4) Separate plot vs. character info appropriately: characters hold personal/background/mechanics; plot holds events, visions, locations, fronts, stakes.
5) Always add gitkeeps for empty dirs.

## Structure
- `README.md`: Bring list, questions to ask next session, grim portents, stakes, TODOs (esp. unresolved item stats).
- `SUMMARY.md`: TOC mirroring GitBook style.
- `characters/`: one file per PC; include player name (and hair if provided), look, drive, background hooks, notable bonds, open questions.
- `plot/`: per-session detailed notes (no brevity), plus prep files; include dead-ends, maze/route info, item sources, consequences. Keep visions/spirit guidance here.
- `loot/`: item writeups with names, tags, weight, drawbacks, set effects. Mark TBD values.
- `monsters/`: keep gitkeep if empty.

## Items
- Use canonical names from modules when given (e.g., Atgir, Skoldir, Jafnir). Include tags (reach/near/thrown), damage, weight, roll text, drawbacks (e.g., jolts to non-devotees).
- If power level is nerfed/trimmed, explicitly note omissions (e.g., Glass of Rain omitted as too strong).

## Process
- When adding prep/notes, include every bullet the user provides; don’t shorten.
- If asked to “come back to” something, add a TODO on the landing page and resolve later.
- When push is blocked, still commit locally and report branch status.

## Tone/format
- Dungeon World style bullets; clear headings; no AI fluff. Favor actionable GM-facing notes.

## Safety
- Never revert user changes; don’t delete content unless explicitly told.
- If uncertainty remains, flag with TODO and cite the source of ambiguity (session vs. pdf).
