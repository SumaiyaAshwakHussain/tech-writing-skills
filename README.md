# tech-writing-skills

# Writing Skills — Technical Publications Team

This repository holds shared **Skills** for the team's technical documentation and Marcom
editorial work. A "skill" is a set of guideline files that AI tools (Claude, Microchip CLI) read
automatically to apply our editorial standards — so nobody has to re-type the rules into every
prompt.

## What's in here

| Skill | What it covers | Status |
|---|---|---|
| `marcom-edit-standards` | Microchip's official Marcom Editing Standards (Policy MC-02-03) — acronyms, capitalization, numbers, sentence structure, punctuation, trademarks, terminology, and approved acronym list | ✅ Ready to use |
| BU wireless guidelines | Our BU's own wireless-documentation-specific rules | 🚧 Coming soon |
| Document templates | Per-template guidance (datasheet, app note, user guide, etc.) | 🚧 Coming soon |

## How to install a skill

1. Download this repo (green **Code** button → **Download ZIP**, or clone it with GitHub Desktop).
2. Copy the skill folder you want (e.g., `marcom-edit-standards/`) into your local skills folder:
   - `C:\Users\<you>\.config\opencode\skills\`
3. Restart Microchip CLI (or start a new session) so it picks up the new skill.
4. That's it — no configuration needed. The skill activates automatically whenever you ask
   Microchip CLI (or Claude) to review, edit, or summarize documentation.

## How to use it

Just ask naturally — you don't need to name the skill:

- **"Review this against our editorial standards"** → flags issues with the specific rule cited
- **"Rewrite this to comply with our Marcom standards"** → returns a corrected version
- **"Review and fix this"** → both

## Questions or suggestions

Contact Sumaiya Ashwak Hussain - I18369.

---
*Maintained by the Technical Publications team — WSG, Microchip Technology.*
