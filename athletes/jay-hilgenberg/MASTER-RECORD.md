# Jay Hilgenberg — A1 permanent individual master record

**Identity:** Jay Hilgenberg • Chicago Bears • jersey **#63** • Center (C). His jersey number is visible both in the #63 C player header and on the uniform in Sweet T's three supplied card screenshots.

**Permanent A1 source consolidation:** The original Library record `JAY_HILGENBERG_A1_COMPLETE_FOR_NOW_PLAYER_RECORD.md` is preserved in full below; the newer 99 LTD screenshot card's complete 53-field harvest is preserved in full afterward. These are distinct ratings datasets and MUST NOT be silently merged. The old A1 95 OVR is a derived working TRUE build; the newer screenshot shows a 99 OVR LTD with chemistry-affected displayed attributes, not verified unboosted base ratings. The edition of the LTD is not directly legible. Existing protected Bears roster must not be overwritten.

## Original complete-for-now player record (verbatim Library content)

# Madden 27-A1 American Football Project
## Jay Hilgenberg — Bears Top 70 #18 — COMPLETE FOR NOW / PRODUCTION-READY

**Primary position:** C  
**Jersey:** #63  
**Height:** 6'3"  
**Weight:** 257 lb  
**College:** Iowa  
**Historical peak target:** 1988  
**Archetype:** Athletic zone/pull center  
**A1 OVR:** 95  

## Production decision

This primary TRUE build is usable and production-ready under the authorized A1 COMPLETE FOR NOW rule. Ratings are a player-specific historical/era derivation anchored to the Bears Top 70 placement, documented career role, measurements, and position-relative peak. Direct EA/Madden values override derived cells whenever recovered. Cosmetic and schema uncertainties are review flags and do not hold the player open.

TRUE is the listed primary position. Legitimate secondary or two-way capability is preserved in the role description and supporting ratings, but no OOP family is averaged into TRUE. Missing evidence is not treated as zero.

## Madden 27 build

- Team Builder seat: 455; position code 7.
- Body type enum: 2.
- Skin band: 1.
- Selected head: HEAD185; genericHeadName review flag retained.
- Helmet: GearHelmet_RiddellTK.
- Facemask: GearFaceMask_FullCage.
- Core equipment map: complete exact-name loadout in the machine-readable block below.

## Review-later flags

- HEAD185 Frostbite genericHeadName recipe.
- Iowa numeric PLYR_COLLEGE enum.
- Team Builder trait/ability field schema.
- Replace derived fields if stronger direct EA values are recovered.

## Machine-readable A1 record

```json
{
  "official_rank": 18,
  "a1_player_id": 19,
  "name": {
    "canonical": "Jay Hilgenberg",
    "first": "Jay",
    "last": "Hilgenberg",
    "jersey_name": "Hilgenberg"
  },
  "status": "PRIMARY_COMPLETE_FOR_NOW",
  "shell_player_id": "455",
  "shell_container_id": 455,
  "primary_position": "C",
  "team_builder_fields": {
    "PLYR_FIRSTNAME": "Jay",
    "PLYR_LASTNAME": "Hilgenberg",
    "PLYR_JERSEYNUM": "63",
    "PLYR_POSITION": "7",
    "PLYR_HEIGHT": "75",
    "PLYR_WEIGHT": "97",
    "PLYR_OVERALLRATING": "95",
    "PLYR_SPEED": "67",
    "PLYR_ACCELERATION": "73",
    "PLYR_AGILITY": "68",
    "PLYR_CHANGEOFDIRECTION": "68",
    "PLYR_AWARENESS": "99",
    "PLYR_STRENGTH": "98",
    "PLYR_JUMPING": "75",
    "PLYR_CATCHING": "35",
    "PLYR_CARRYING": "55",
    "PLYR_KICKRETURN": "20",
    "PLYR_INJURY": "92",
    "PLYR_STAMINA": "94",
    "PLYR_TOUGHNESS": "96",
    "PLYR_TRUCKING": "55",
    "PLYR_BCVISION": "55",
    "PLYR_STIFFARM": "55",
    "PLYR_SPINMOVE": "50",
    "PLYR_JUKEMOVE": "50",
    "PLYR_BREAKTACKLE": "55",
    "PLYR_RUNBLOCK": "97",
    "PLYR_PASSBLOCK": "97",
    "PLYR_IMPACTBLOCKING": "97",
    "PLYR_RUNBLOCKPOWER": "98",
    "PLYR_RUNBLOCKFINESSE": "93",
    "PLYR_PASSBLOCKPOWER": "97",
    "PLYR_PASSBLOCKFINESSE": "95",
    "PLYR_LEADBLOCK": "95",
    "PLYR_TACKLE": "35",
    "PLYR_HITPOWER": "45",
    "PLYR_POWERMOVES": "30",
    "PLYR_FINESSEMOVES": "40",
    "PLYR_BLOCKSHEDDING": "35",
    "PLYR_PURSUIT": "50",
    "PLYR_PLAYRECOGNITION": "55",
    "PLYR_MANCOVERAGE": "35",
    "PLYR_ZONECOVERAGE": "40",
    "PLYR_PRESS": "35",
    "PLYR_SPECTACULARCATCH": "35",
    "PLYR_CATCHINTRAFFIC": "40",
    "PLYR_SHORTROUTERUN": "35",
    "PLYR_MEDROUTERUN": "30",
    "PLYR_DEEPROUTERUN": "30",
    "PLYR_RELEASE": "40",
    "PLYR_THROWPOWER": "35",
    "PLYR_THROWACCURACYSHORT": "25",
    "PLYR_THROWACCURACYMID": "20",
    "PLYR_THROWACCURACYDEEP": "20",
    "PLYR_THROWONTHERUN": "20",
    "PLYR_THROWUNDERPRESSURE": "25",
    "PLYR_BREAKSACK": "35",
    "PLYR_PLAYACTION": "25",
    "PLYR_KICKPOWER": "20",
    "PLYR_KICKACCURACY": "20",
    "PLYR_CHARACTERBODYTYPE": "2"
  },
  "character_visuals": {
    "heightInches": 75,
    "weightPounds": 257,
    "bodyType": 2,
    "skinTone_working": 1,
    "genericHead_ui_id": "HEAD185",
    "genericHeadName": null,
    "loadout": {
      "0": "GearFaceMask_FullCage",
      "2": "GearVisor_None",
      "9": "GearSpats_none",
      "10": "GearFootwear_shoe_high_Adidas_LeatherTurf80s",
      "11": "GearFootwear_shoe_high_Adidas_LeatherTurf80s",
      "12": "Backplate_None",
      "25": "Small_Pads",
      "26": "Towel_None",
      "29": "GearNeckpad_None",
      "30": "Flakjacket_None",
      "51": "FaceMarks_None",
      "54": "GearSpats_none",
      "71": "GearKneeBrace_None",
      "72": "GearKneeBrace_None",
      "101": "HandwarmerStyle_None",
      "106": "GearHelmet_RiddellTK",
      "107": "BottomBase_None",
      "108": "Undershirt_None",
      "109": "Gear_Socks_High",
      "110": "ArmSleeve_None",
      "111": "ArmSleeve_None",
      "112": "CalfGear_None",
      "113": "CalfGear_None",
      "114": "GearHand_None",
      "115": "GearHand_None",
      "116": "ElbowGear_None",
      "117": "ElbowGear_None",
      "118": "KneePad_Regular",
      "120": "GearWrist_None",
      "121": "GearWrist_None",
      "122": "GearMouthpiece_None",
      "124": "GearPants_Standard",
      "125": "Gear_JerseyStyle_SleeveStandard",
      "127": "Handwarmer_None",
      "142": "ThighPad_Regular",
      "143": "ThighPad_Regular"
    }
  },
  "traits": {
    "clutch": true,
    "high_motor": true,
    "penalty_tendency": "Normal"
  },
  "rating_provenance": {
    "method": "AUTHORIZED_HISTORICAL_DERIVATION_COMPLETE_FOR_NOW",
    "overall_basis": "Bears Top 70 rank 18, career peak and position-relative historical tier",
    "direct_ea_override": true
  },
  "import_readiness": "PRODUCTION_READY_REVIEW_FLAGS",
  "unresolved": [
    "HEAD185 Frostbite genericHeadName recipe",
    "Iowa numeric PLYR_COLLEGE enum",
    "Team Builder trait/ability field schema",
    "Replace derived fields if stronger direct EA values are recovered"
  ]
}
```

---

## 99 OVR LTD — complete screenshot harvest (verbatim separate card record)

# Jay Hilgenberg — 99 OVR LTD card — screenshot harvest

**Source:** Three screenshots supplied directly by Sweet T on 2026-11-19: `14239.jpg` (KEY and GENERAL), `14240.jpg` (OFFENSE), `14241.jpg` (DEFENSE and SPECIAL TEAMS). Original screenshots are conversation attachments; this text record does not claim to have copied the binary images into GitHub.

**Player:** Jay Hilgenberg; Chicago Bears; #63; C (center); card type LTD; card archetype AGILE; **displayed OVR 99**. Displayed height 6 ft 3 in; weight 255 lb.

**Critical provenance warning:** Screenshot states “Indicates Chemistry is affecting an attribute” with green indicator. All 53 visible ratings are displayed at 99. Do **not** treat these as verified unboosted/base card ratings, or use 99 for every field in an unboosted A1 annual average without resolving chemistry effects. Exact Madden edition is not explicitly visible in the screenshots; do not invent a year. The user described this as a card being harvested while researching Madden 2026, but that is not an independently verified edition label.

## KEY (duplicates of full attribute fields)
- STR: 99
- AWR: 99
- PBK: 99
- PBP: 99
- PBF: 99
- RBK: 99
- RBP: 99
- RBF: 99

## GENERAL — 9 fields
- STR: 99
- AGI: 99
- SPD: 99
- ACC: 99
- AWR: 99
- CTH: 99
- JMP: 99
- INJ: 99
- STA: 99

## OFFENSE — 30 fields
- CAR: 99
- THP: 99
- PBK: 99
- RBK: 99
- TRK: 99
- COD: 99
- BCV: 99
- SFA: 99
- SPM: 99
- JKM: 99
- IBL: 99
- RBP: 99
- RBF: 99
- PBP: 99
- PBF: 99
- SPC: 99
- CIT: 99
- MRR: 99
- RLS: 99
- LBK: 99
- SAC: 99
- MAC: 99
- DAC: 99
- RUN: 99
- PAC: 99
- BTK: 99
- BSK: 99
- TUP: 99
- SRR: 99
- DRR: 99

## DEFENSE — 10 fields
- TAK: 99
- PMV: 99
- FMV: 99
- BSH: 99
- PUR: 99
- PRC: 99
- MCV: 99
- ZCV: 99
- POW: 99
- PRS: 99

## SPECIAL TEAMS — 4 fields
- KPW: 99
- KAC: 99
- RET: 99
- LS: 99

**Total:** 53 distinct displayed attribute fields, all 99. KEY fields are repeated, not additional attributes. Long Snap (LS) is explicitly 99. No missing fields in the 53-field display; **unboosted base ratings and confirmed Madden edition remain unresolved**.

**Filing rule:** Supplemental card-source record only. Preserve existing Jay Hilgenberg master, protected Bears roster, and other card records unchanged.


---

**Source and storage note:** The Library source and the original screenshot attachments remain in their original locations. The screenshot harvest is also filed as a permanent separate card-specific GitHub document. This master consolidates their substantive contents without deleting sources, creating a temporary staging folder, or declaring conflicting versions equivalent.
