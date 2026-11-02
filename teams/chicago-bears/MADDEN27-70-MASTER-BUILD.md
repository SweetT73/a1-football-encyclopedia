# A1 Football Encyclopedia — Chicago Bears Locked 70: permanent Madden 27 master build

**Build focus:** The existing approved 70-person Chicago Bears team for Madden 27 Team Builder, not a newly selected all-time team. **Status:** baseline recovered and checksum verified November 2, 2026; prior 70/70 Team Builder import reported; current in-game success and visual acceptance NOT independently checked in this run. **Membership LOCKED.**

## Source integrity and preservation
- Original authoritative Library file: `A1_Bears_Locked70_FINAL_IMPORT_v10.build.json`, `buildId=a1-bears-locked70-final-import-v10`.
- **Actual bytes SHA-256:** `a929a6ae113dd074a09feca12d1adbe5baa9438c229751070621959365378e16` (recomputed directly on retrieved file, Nov 2).
- File contains **70 slots / 70 unique targetPids**; 22 position groupings. The 70 historical player identities, ratings, body, equipment, DOB, birthdate translations, team data, targetPid slots, TRUE/OOP/TWO roles, colleges, and other fields are to remain unchanged when doing face-only corrections.
- This document inventories existing roster data. It does **NOT** replace the complete 612 KB JSON build or certify any head replacements. Do not treat the v11–v14 test files as user-approved.
- The source was previously imported with report **“Transplanted 70 of 70 built players onto this team”**. This is a historical report, not evidence of a newly performed console import.
- Only use `Roster → Load build...`; **never** `Load everything...`. Review faces before EA Save, then pull back to verify if actually saved. Do not overwrite v10.
- Locked 70 is **Team Builder Batch 1**, not a cap on A1 master or the future 75-player league-wide roster. An older permanent research pool already protects at least 82 Bears names. Later batches cover the overflow and the full top-100/audit.
- **James "Shack" Harris:** historically Bills/Rams/Chargers, *not* an existing member of this Bears 70. His A1 individual profile is separate; do not place him on the locked Bears team automatically.

## Complete original 70-player position inventory and preserved working OVR
The displayed ratings below are the **actual v10 build's existing working ratings**, not newly calculated values, external lists, or approved changes. Position names reflect the game's roster positions; do not mistake roster proxies for historically true positions.

| Roster position | # | Locked players (existing v10 working overall ratings) |
|---|---:|---|
| QB | 3 | Sid Luckman **96** · Jim McMahon **93** · Bill Wade **94** |
| HB | 5 | Walter Payton **97** · Gale Sayers **99** · Matt Forte **91** · Willie Galimore **88** · Red Grange **98** |
| FB | 2 | Bronko Nagurski **97** · Rick Casares **94** |
| WR | 5 | Devin Hester **85** · Harlon Hill **96** · Johnny Morris **93** · Willie Gault **93** · Curtis Conway **78** |
| TE | 4 | Mike Ditka **98** · Bill Hewitt **97** · Ken Kavanaugh **95** · Emery Moorehead **89** |
| LT | 3 | Jimbo Covert **96** · Joe Stydahar **97** · Bob Wetoska **90** |
| LG | 3 | Danny Fortmann **97** · George Musso **91** · Mark Bortz **93** |
| C | 3 | Clyde Turner **98** · Jay Hilgenberg **95** · George Trafton **94** |
| RG | 3 | Stan Jones **96** · Ray Bray **94** · Kyle Long **80** |
| RT | 3 | Ed Healey **93** · Link Lyman **92** · Keith Van Horne **92** |
| LEDG | 3 | Doug Atkins **98** · Ed Sprinkle **95** · Mike Hartenstine **92** |
| REDG | 3 | Richard Dent **98** · Ed O'Bradovich **93** · George Halas **95** |
| DT | 5 | Dan Hampton **96** · Steve McMichael **90** · Fred Williams **88** · Jim Osborne **92** · William Perry **93** |
| SAM | 3 | George Connor **95** · Otis Wilson **92** · Larry Morris **91** |
| MIKE | 5 | Dick Butkus **99** · Bill George **97** · Brian Urlacher **96** · Mike Singletary **97** · Ron Rivera **90** |
| WILL | 3 | Joe Fortunato **93** · Lance Briggs **92** · Doug Buffone **90** |
| CB | 5 | Charles Tillman **87** · J.C. Caroline **89** · Bennie McRae **91** · Donnell Woolford **78** · George McAfee **96** |
| FS | 3 | Gary Fencik **94** · Mark Carrier **93** · Mike Brown **89** |
| SS | 3 | Richie Petitbon **95** · Dave Duerson **94** · Shaun Gayle **91** |
| K | 1 | Robbie Gould **87** |
| P | 1 | Bobby Joe Green **92** |
| LS | 1 | Patrick Mannelly **91** |
| **TOTAL** | **70** | **70 unique player slots** |

## Preserved position identity sidecars
- George McAfee: **TRUE halfback**, playable roster-sidecar cornerback.
- George Halas: roster-sidecar right-edge defender; his historical playing/other roles must be maintained in the A1 identity record.
- Ken Kavanaugh: roster-sidecar tight end.
- William Perry: genuine defensive tackle, separate FB OOP context; maintain distinct true and OOP versions where available.
- Other multiple-era/two-way players: maintain individualized TRUE, real secondary, EA OOP, and TWO representations, not new identities.

## Highest-priority unfinished work — head/skin/face pass
Sweet T directly reported **29 visibly incorrect player complexions** when inspecting the real Team Builder rendering. **All 29 are OPEN**, even when a software section-family check suggested an acceptable category. The 41 remaining players still require their first full visual review. Apply the user-established exact order:

**Group 1 — 13 previously modified without approved skin-first photo verification (FIRST):** Jim McMahon; Bill Wade; Red Grange; Harlon Hill; George Musso; Jay Hilgenberg; Keith Van Horne; George Halas; Steve McMichael; Fred Williams; Dick Butkus; Bill George; Dave Duerson.

**Group 2 — 16 additional visible-color failures (SECOND):** Gary Fencik; Brian Urlacher; Doug Atkins; Ed Sprinkle; Sid Luckman; Johnny Morris; Mike Ditka; Jimbo Covert; Bob Wetoska; Danny Fortmann; Ed O'Bradovich; Dan Hampton; George Connor; Ron Rivera; George McAfee; Richie Petitbon.

**Group 3 — remaining 41 (THIRD):** review every other locked player using the same methodology.

**Method for EACH:** Confirm unique identity; actually inspect **five distinct authentic historical photographs**; assess the photographed face/color with color reproduction and lighting caveats; inspect Madden’s **330-head catalog** for correct *rendered* section; compare nose, lips, skull, ears, brows, eyes, hair and facial hair; map `HEAD###` to correct `genericHeadName`; check in live Team Builder; accept only when approved. A numerical skin-family filter by itself is NOT a completed visual correction. Do not claim the required **93% appearance acceptance** without evidence.

**Unapproved experiments:** v14 contains 13 provisional face swaps. None has been approved, and none is to replace the original file as a baseline.

## Production status
1. [x] Existing original complete JSON located, retrieved, cryptographic hash verified.
2. [x] 70 slots and 70 unique IDs verified programmatically.
3. [x] Full roster positions and current original OVRs extracted, cataloged in the permanent A1 Bears team location.
4. [ ] First head pass, starting **Jim McMahon**, five authentic photographs + full head comparison.
5. [ ] Validate acceptable head in Team Builder; save separate corrected build with zero mutation outside authorized appearance fields.
6. [ ] Finish group 1 (13), group 2 (16), and remaining 41 in established order; test import/persistence and gameplay.
7. [ ] Build remaining protected Bears in additional player batches without changing locked 70 membership.

## Source provenance
- Authoritative internal Library: `A1_Bears_Locked70_FINAL_IMPORT_v10.build.json`; `Madden27_A1_Conversation_Master_Handoff_2026-10-10.md`; `A1_Bears_Head_Pass_Checkpoint_2026-10-11.md`; `A1_Bears_First_Protected_Pool_2026-09-30.md`.
- Historical franchise source (player audit only; not a numerical Madden ratings formula): https://www.chicagobears.com/news/ranking-best-bears-of-all-time-nos-1-25 and https://www.chicagobears.com/news/bears-nfl-celebrate-100th-birthday-thursday
- All subsequent verified improvements belong in permanent A1 individual records and this master construction reference. **No temporary holding folders. No site page changes without user authorization.**
