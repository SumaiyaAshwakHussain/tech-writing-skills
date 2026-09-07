---
name: marcom-edit-standards
description: Microchip Technology's official Marcom Editing Standards (Policy MC-02-03) for all written content — marketing collateral, web content, and technical/wireless documentation. Use this skill whenever reviewing, editing, proofreading, summarizing, or writing any Microchip content, including datasheets, application notes, user guides, product briefs, web copy, or presentations. Always apply this skill for tasks like "review this document," "check this against our editorial standards," "proofread this," "summarize this datasheet," "fix the formatting/style," or "does this follow our style guide." Covers acronym formatting, capitalization, numbers, punctuation, spacing, symbols, trademarks, hyphenation of industry terms, commonly confused words, voice, deprecated terminology, and Microchip's approved acronym list.
compatibility: Works with any agent that supports the Agent Skills format (Claude, OpenCode/Microchip CLI).
---

# Microchip Marcom Editing Standards (MC-02-03)

This skill encodes Microchip's official Marcom Editing Standards so every review, edit, or summary
of Microchip content — marketing or technical — automatically follows the same rules, without
anyone having to restate them.

**Source:** Marcom Editing Standards, Policy No. MC-02-03 (Revised 3/17/25).
**Scope:** Primary focus is marketing content. Exceptions for technical documentation are called
out explicitly below and in the reference files — apply those exceptions when the content being
reviewed is a datasheet, application note, user guide, or other technical document rather than
marketing collateral.

## How to use this skill

1. Identify what kind of content you're reviewing (marketing collateral vs. technical documentation) —
   several rules below have a technical-documentation exception.
2. Apply the **Always-On Quick Rules** below to every review — these are the highest-frequency,
   easiest-to-miss issues.
3. Load the relevant reference file(s) for deeper checks based on what the content contains:

| If the content involves... | Read this reference file |
|---|---|
| Acronyms, bullets, capitalization, dates/times, hyphens/dashes, numbers, punctuation, spacing, symbols, trademarks | `references/editing-standards.md` |
| Word choice, abbreviations, misused words, voice/tone, third-party or competitor mentions, deprecated terminology (master/slave, etc.), words to avoid | `references/writing-guidelines.md` |
| Print/layout documents (columns, line breaks, orphans/widows) | `references/document-formatting.md` |
| Whether a specific industry term should be one word, hyphenated, or capitalized (e.g., "power-down," "real-time," "8-bit") | `references/terminology-glossary.md` |
| Whether/how to expand an acronym (e.g., ADC, MCU, RF, GPIO) | `references/acronyms-glossary.md` |
| Units of measurement, SI prefixes, small caps, bit/pin/mode naming conventions | `references/units-and-conventions.md` |

When flagging issues, cite the specific rule (e.g., "MC-02-03 §1.6 Numbers: spell out numbers 0–9")
so the person understands *why*, not just *what* to change.

## Always-On Quick Rules

These apply to nearly everything and are the most commonly violated:

- **Numbers:** Spell out 0–9 in body text; use digits for 10+. Exception: numbers used as adjectives
  describing a device or in names for bits/registers/channels (e.g., "8-bit MCU," "bit 2") stay as digits.
- **Acronyms:** First use = full term, initial capped, with acronym in parens — e.g., "Analog-to-Digital
  Converter (ADC)." Don't initial-cap a letter that falls mid-word (Electromagnetic, not ElectroMagnetic).
  After that, use the acronym alone. Plural acronyms take a lowercase "s," never an apostrophe (ADCs,
  not ADC's).
- **Capitalization:** Sentence case in body text, not title case. Don't capitalize generic terms
  (analog, automotive) just for emphasis.
- **Voice:** Conversational and customer-focused ("we," "you") for marketing content; this does NOT
  apply to technical documentation, which stays formal/impersonal.
- **Trademarks:** A trademark is an adjective and needs its approved noun every time it appears (e.g.,
  "PIC MCU," never just "PIC" or "PICs"). Never pluralize or possessive a trademark.
- **Microchip/MCHP:** Never write "Microchip®" (not a registered trademark in text — only the logo is).
  Never abbreviate to "MCHP" except for the stock symbol.
- **Words to avoid:** Flag absolute/promissory claims — guarantee, ensure, perfect, zero risk, best,
  fastest, number one, etc. — unless the writer can back the claim with evidence.
- **Symbols:** Use real ×, °, ±, − (minus) symbols, not x, o, +/-, or hyphen substitutes. Use % not
  "percent." One space between a number and a multi-character unit (2.5 MHz) but no space for a
  single-character unit (2.5V, 3A).
- **Spelled-out ordinals:** first, second, third — never 1st, 2nd, 3rd.
- **i.e. / e.g. / etc.:** Avoid — they're confusing; use "for example" / "that is" / or rephrase to avoid
  "etc." entirely.

## Technical Documentation Exceptions to Remember

- Bulleted items may contain full sentences with periods (marketing bullets stay as fragments, no periods).
- Parentheses and the exclamation mark (for system-generated messages) are acceptable.
- Curly quotes may be replaced by straight apostrophes/quotes when reproducing exact code syntax.
- An ellipsis may be used in register/pin tables.
- Section/document titles may follow established technical doc conventions (including ALL CAPS) rather
  than strict title-case rules.

For anything not covered here or in the reference files, default to the Chicago Manual of Style, per
the standard's own guidance.
