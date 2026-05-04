# Dao Ascension — First Pass (Planned and In-Progress Changes)

This file is an automated patch-note created by the assistant before applying changes.

Repository: Realcoder-1/dao-ascension-
Commit plan: Merge the four HTML files into a single `dao_final.html` and apply the Priority A fixes.

Priority A (this commit):
- Merge code from: `index.html`, `dao-ascension-v5.html`, `dao-v7-work.html`, `dao_final (1).html` into a single canonical `dao_final.html`.
- Fix NPC interaction wiring (talk, gift, outing, romance, propose, dao bond, elder interactions) — robust delegated click handler.
- Fix market/auction purchase logic (allow buying items from shop/auction, put items into inventory, avoid duplicate re-listing of unique items).
- Toast and notifications: center toasts, rectangular bubble style, reduce spammy golden pulsing CTA; remove pulsing gold animation for the bottom CTA.
- Sect join flow: present elder choice overlay and three common beast eggs to select when joining a sect.
- Territory/casualty scaling: casualties scale with number of territories (mortal/spiritual/immortal) and elite troops reduce casualties.
- Location danger effects: dangerous locations reduce body/health; low power may cause death.
- Relationship UI tweaks: smaller NPC portraits in relationships tab; add more action buttons per NPC.
- Add "Select Divine Beast" quick action to Path/House to open beast selection overlay.
- Ensure inventory persists all bought/awarded items and they affect stats.

Follow-up (Priority B — after A):
- Disciple system (10 disciples, auto-progression), dynasty & inheritance systems.
- Full combat system with challenge/kill/exile rules and consequences.
- Luxury market, rare pills for body reconstruction, transmigration features.
- Sect ranking mechanics, sect takeover and elder replacement.
- Expanded item pools for every realm and sophisticated auction/market dynamics.

Notes:
- I will create `dao_final.html` and keep originals unchanged.
- I will run the first-pass changes and then provide the commit SHA and a short QA checklist.

If you want to change anything about the immediate scope before I start writing code, reply here now.
