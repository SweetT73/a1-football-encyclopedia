# A1 — Madden NFL League-Wide Roster Building Research

Permanent A1 project record. Started October 31, 2026. Findings updated November 7, 2026. This file preserves ongoing technical evidence; it does not imply background investigation is actively scheduled.

## Purpose
Determine how to build ONE complete NFL-wide custom roster with historical players across 32 teams, with Sweet T's preferred 75-player-per-team target (2,400 total), retaining 70 (2,240 total) as a fallback ONLY if technical restrictions are confirmed. Do not conflate 53 active game-day/regular roster slots with editable league-wide player database capacity, free agents, or franchise preseason capacity.

## November 7, 2026: Madden 27 evidence and production priority

**Sweet T's instruction:** Complete and validate the already locked **70-player Chicago Bears Madden 27 Team Builder roster first**. Do not expand the game roster or displace players until the existing 70 are playable and correctly built. Keep researching extended league-wide capacity as a separate future option; this does not delay the existing 70.

### Verified workflows
- **EA's official Madden 27 league-wide custom roster:** Main Menu → Creation Center → Edit Rosters → Manage Players, where one can edit, release or trade players across the league, and save a complete custom roster file. To use: Creation Center → Load/Delete Files → Roster → Load File, and select Roster File when entering Franchise. This is a *different system* from an individual Team Builder roster. https://help.ea.com/en/articles/madden-nfl/franchise-mode-custom-rosters/
- **EA's official Madden 27 Team Builder:** customizes branding, stadium, uniforms and an individual team's player roster, imports to *online* Franchise (not offline) as a replacement for an NFL team. EA says up to 32 team replacements, which does **not** specify 70 or 75 per team. https://help.ea.com/en/articles/madden-nfl/madden-team-builder/
- **A1 third-party roster editor** https://madden27-tb-editor.com/ currently advertises “70 seats.” This is the existing custom team roster editor's **template**, not EA's confirmed game-wide player database limit.
- **Community 75-player precedent (Madden 27):** Operation Sports TrueSim Franchise Roster discussion identifies “TrueSim75” based on EA's preseason 75-player team files and “TrueSim53” based on regular-season 53-man files. This is evidence that a community *league-wide roster file* may represent 75 per team, **not** proof that Team Builder can create 75 on one franchise-replacement team. https://forums.operationsports.com/forums/forum/football/madden-nfl-football/madden-nfl-football-rosters/26928584-truesim-franchise-roster-madden-27/page6
- **EA fixed relevant franchise problems:** August 26, 2026 Madden 27 update fixed players disappearing after a game from imported roster files; EA notes starting a *new Franchise* and re-importing the custom file is required for that fix. https://www.ea.com/games/madden-nfl/madden-nfl-27/news/m27-title-update-august-26-2026 ; October 21, 2026 update fixed multiple custom-roster import / contract and depth-chart issues. https://www.ea.com/games/madden-nfl/madden-nfl-27/news/madden-nfl-27-title-update-october-21

### Findings still unverified
1. The maximum **individual Madden 27 Team Builder** roster slot count beyond the 70 represented by our editor/template, including whether a supported increase to 75 is possible.
2. Whether any **Xbox-compatible** ordinary *league-wide roster* workflow can hold more than 75 on a particular team and preserve custom heads, historic attributes and Madden ratings as intended.
3. RedzoneJay's original Madden 26 file lineage, creation method and current Xbox download availability. Video depicting roughly 1,500+ players across a whole league does not establish 1,500 individually “created from scratch” entries or any particular per-team limit.

### Finish the 70 first (current historically recovered baseline)
- Original protected A1 Bears 70-player v10 build: **70 unique IDs, 70 distinct roster seats**, original ratings and player identities preserved. Historical import reported “Transplanted 70 of 70”; this does **not** establish complete validated live playable appearances and ratings.
- Outstanding: **29 user-observed visible head/complexion mismatches** (13 in first established pass; 16 in second), **41 others yet to complete final visual audit**, plus final field/overall rating validation in the real Team Builder and loaded Xbox franchise.
- Use original v10 as unchanged baseline. For each player, verify correct A1 ratings, position, attributes, jersey, body and equipment; correct facial rendering by authentic references and actual Team Builder preview. Preserve 70/70 identities and import fields. Then test a new online Franchise load and gameplay, respecting EA's documented fixes. Do not invent success or perform unapproved game changes.
- Player biographies and historical photographs can continue to populate the permanent A1 player folder by position independently; this does not consume in-game roster capacity.

## RedzoneJay evidence
- Video: https://www.youtube.com/watch?v=67Im1dhpcl4
- Title: I Put 32 All-Time Teams Into The NFL!
- Creator Redzone Jay; published March 10, 2026.
- Video description explicitly says Madden 26, an existing "greatest All-Time Team/Legends roster", face scans, portraits, updated ratings, and a simulated alternate NFL timeline. This does NOT prove RedzoneJay personally created all players.
- User's screenshot of a community roster item reads filename **RZJAYALLTIME**, uploader **RedzoneJay**, 22 downloads at screenshot time. Xbox availability as of October 31 unconfirmed.
- Sweet T reports hearing the video reference more than 300 offensive linemen. This exact quote, context, and whether it describes created or existing players remain unverified.
- 32 x 53 = 1,696; 32 x 70 = 2,240; 32 x 75 = 2,400.
- Potential technical method: edit existing player records across all 32 teams, together with separately created players and/or downloaded legends. Verify precisely rather than assuming.
- This project concerns ONE shared all-league roster file, NOT 32 independent Team Builder exports.

## Verified public sources
- YouTube original: https://www.youtube.com/watch?v=67Im1dhpcl4 (Madden 26 legends roster described).
- EA Madden 26 official existing legends content: https://www.ea.com/games/madden-nfl/madden-nfl-26/news/madden-26-all-madden-team (official All-Madden legends are a special game feature; do not assume automatically editable/importable into standard rosters).
- Madden 26 custom roster steps: https://www.destructoid.com/how-to-create-and-use-custom-rosters-in-madden-26/ (Creation Center > Edit Roster; download and load community file separately).
- EA Madden 27 Team Builder: https://help.ea.com/en/articles/madden-nfl/madden-team-builder/ (team-specific and franchise tool, not necessarily equivalent to global roster file).
- Older EA game manual: https://dlassets-ssl.xboxlive.com/public/content/65b6a1be-ad5d-47f4-8714-bd731dcdb1f0/GameManual/16979669-1e28-47c2-a86c-c6ece0eb45db/en-US/index.html (historical evidence that existing players can be edited; confirm current-release restrictions).

## Priority unresolved tests
1. Identify the actual original roster and credited creator from RedzoneJay video, pinned comment, credits, and other uploader mentions.
2. Determine availability and discovery procedure for **RZJAYALLTIME** on Xbox for Madden 26; distinguish Xbox Series X|S, Xbox One, platforms, and Madden 27.
3. Obtain evidence for Madden 26's team roster max/min, franchise preseason and cut-down rules, global database limit, created-player cap, free-agent capacity, depth-chart rules, and any differences in offline/online.
4. Check whether names, face scans, body/appearance, portraits, ages, ratings, positions, contracts, teams, college, jersey numbers are editable for built-in players versus separately created players.
5. Investigate on-console workflow for replacing existing players, moving unwanted players into free agency, retaining historical backups, saving/loading/exporting/uploading a *single* 32-team roster.
6. Clarify if 300+ offensive linemen is a count from a larger source database or players actually simultaneously held in 32 team rosters.
7. Separate verified steps from creator reports, hypotheses, unsupported limits, modded PC techniques, and inaccessible on-Xbox techniques.
8. Build a reproducible Xbox-friendly end-to-end procedure including safe backup, small pilot, then full A1 rollout.

## Archive rules
Update THIS permanent document or subsequent permanent A1 build documentation directly. No temporary folders, checkpoints, or duplicate files. Verify before replacing established content; no unsupported claims. Keep unrelated A1 athlete biographies and images untouched. Preserve sources and exact version applicability.


## Permanent player-slot data structure

An uploaded Madden 27 technical schema provided the following reusable **draft record structure**. Retain the substantive structure in this permanent A1 technical document, not as a separate bridge, handoff, or checkpoint artifact. It is a proposed A1 data representation, **not evidence that Madden NFL 27 accepts this as an import format**.

- A roster/build record may contain an array of player slots. Each slot requires a position code and a structured `fields` object.
- Optional per-slot fields: `slotIndex` (nonnegative integer), `visuals` (structured appearance object), and `gear` (equipment array).
- Position codes defined by the draft: `QB`, `HB`, `FB`, `WR`, `TE`, `LT`, `LG`, `C`, `RG`, `RT`, `LEDG`, `REDG`, `DT`, `SAM`, `MIKE`, `WILL`, `CB`, `FS`, `SS`, `K`, `P`, `LS`.
- The draft did not specify internal player-attribute fields, ratings, body/face IDs, or import compatibility. For complete A1 builds, existing approved permanent player records and the protected original build remain authoritative; never invent missing values or let a technical draft override them.

## Long-snap attribute reconstruction — source distinctions (November 18, 2026)

**Permanent methodology, not an approved numerical rating.** Sweet T's Warren Moon/James Madden discussion concerns distinguishing a player's demonstrated ability to execute a long snap from the default or position-dependent values displayed in particular Madden editions, custom cards, and A1 reconstructed 53-field records. Do not equate a quarterback's Madden OVR, an unrelated specialist's overall, or an automated card filler with demonstrated long-snapping ability.

The earlier A1 conversation audit records **reported Moon long-snap numbers of 80, 84, 77, 51, and 10** from different alleged cards, normalizations, and assistant projections. These are **not five interchangeable observations** and none is adopted here as Moon's real-world long-snap skill. One assistant-suggested, unapproved candidate was `LS = round(10 + 89 × S)`, where `S` was an unspecified weighted skill index; without documented component weights and source measurements this is not a usable final calculation. Moon's existing [permanent Drive profile](https://docs.google.com/document/d/1NIrBdkYXhjgVmKfqWJEAL9wWBEmaHmwqUa_ah4hfZaI/edit) already holds the detailed conflicting card and annual evidence. Preserve it rather than re-entering competing attributes here.

**Name and player distinction:** The audit refers to a **“James Madden” calculation** whose original screenshot/equation remains unrecovered. This must not be silently substituted with James Dearth, James Daniels, Jayden Daniels, or John Madden. [James Dearth's existing permanent profile](https://docs.google.com/document/d/1S-dSE7pJwlU3xzaz0TADrecO_lxy4plLNIXA48GDPg8/edit) documents his actual quarterback background and later NFL long-snapper role, but explicitly leaves his Madden LS attribute unverified. [Tanner Purdum's permanent profile](https://docs.google.com/document/d/1yMPWJyUu-3C-thZUFz-Y75L-DJ5LlhAr6DcNPuEZTgc/edit) is a separate quarterback-to-long-snapper comparison, not a substitute for the missing James Madden source. Sweet T explicitly corrected the earlier assistant's implication that he had called Dearth a quarterback in the relevant comparison; preserve the distinction between **a player's historical QB experience** and **the actual claim Sweet T made about Madden underrating specialist snappers**.

**Evidence required before assigning any LS rating:** the exact game edition/year and mode; original attribute screenshot or roster record with player identity; whether the value is an EA field, MUT card, custom A1 value, or assistant calculation; the complete approved equation with component definitions; and, for a claimed historical ability, actual football evidence of snapping. Until recovered, label the James Madden calculation **unknown**, and do not modify protected Madden 27 player/roster data.

## Madden Ultimate Team out-of-position card identity and annual filing

Sweet T's archival instruction for Madden 18 (2017 season) and Madden 23 (2022 season): retain **game edition**, **corresponding football season**, **MUT program**, **individual card**, and **card's in-game position** as separate fields. A football player may have multiple distinct OOP cards, including cards from different programs within one edition. Do not collapse these into a timeless historical playing position or overwrite the same player's actual-position Madden record. Keep regular-position and OOP card variants linked to the same permanent player identity, with edition-specific subrecords; distinguish official EA card attributes from A1 reconstructions. User-supplied Madden 23 lineup-builder lead: https://www.mut.gg/23/lineup-builder/2916051f-2be6-4aaf-b644-8a0b5c4164d4/ (lineup contents not established from this URL). Sweet T also reported access to some Madden 25 cards associated with the 2024 season; access to other earlier editions is unknown. These are user instructions and source leads, not verification of particular OOP player/card identities. Preserve actual card screenshots and original source links in the corresponding existing player/edition records when available.

## A1 five-player Madden completion order and attribute workflow — user instructions, November 14, 2026

Sweet T designated this exact processing order for a separate Madden player-completion workstream: **(1) Warren Moon — QB; (2) Charles Woodson — CB; (3) Mel Blount — CB; (4) Lane Johnson — RT; (5) Jason Kelce — C.** This is a priority order, not evidence that any player's cards have been finished. Preserve each player's existing permanent identity and edition-specific records; do not create duplicate player profiles.

For each player: finish **actual-position cards** and calculate the actual-position overall; then finish **out-of-position (OOP) cards** and calculate the OOP overall; then derive the **final true overall**, inspect the resulting attribute evidence, and only then advance to the next player. Sweet T specified **53 attributes** and use of the established **A1 equations**. For missing values, he proposed same-overall comparisons from completed modern **99, 98, and 91** player cards, while retaining edition/year and source provenance. **Buzz numbers are post-year only**; later official Madden 24, 25, and 26 material takes precedence where applicable. Neither an unlocated formula nor an analogy constitutes an approved final number.

**Warren Moon-specific source leads from the user's conversation:** a reported **97** card in Madden 98 and **2000** card in Madden 01; Madden 98–99 values to reconstruct; a reported **93 OVR LOLB** variant; competing reported speed values **63 versus 84**. The user also discussed completion percentage to accuracy, minimum passing-attempt sample, age-related tangible-attribute deterioration, and combine analogies for strength/jump. These are calculation/research directions and reported card leads, **not independently checked official EA attributes**. Moon's existing [permanent Drive player record](https://docs.google.com/document/d/1NIrBdkYXhjgVmKfqWJEAL9wWBEmaHmwqUa_ah4hfZaI/edit) holds the player-specific conflicting long-snap evidence; do not merge speed, OOP, or long-snap fields across editions.

**Required output for Moon:** all annual QB cards with 53 attributes and a QB average, followed by OOP cards, then the final true overall. Do not report these as complete without the underlying per-year evidence and calculations. This workflow is distinct from the conversation-recovery audit: the audit preserves user instructions and sources, while the separate player-completion workstream performs the ratings calculations.

## Historical football nicknames — unresolved identity-mapping leads (conversation recovery)

Sweet T supplied the following nickname set for the A1 Madden historical-player workstream, in this order: **Minister of Defense; Samurai; Crazy Legs; Mad Stork; Goose; Butterball; Broadway Joe; Mercury Morris; Peanut; Pacman; The Snake; Dracula in Cleats; The Danimal; Mongo.** These spellings and sequence are user-supplied research leads, **not** verified player-to-nickname assignments or evidence that each nickname belongs to a unique athlete. Before attaching a nickname to a player record, establish the intended person, relevant era, and supporting source; do not generate duplicate player identities from nicknames or infer Madden card ratings from them. This is an unresolved identification list, not a completed roster or an authorization to modify the protected 70-player Bears build.
