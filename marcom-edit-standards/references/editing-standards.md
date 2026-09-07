# Editing Standards (MC-02-03 §1)

## Acronyms (§1.1)
- First instance: initial-cap all words making up the acronym, then the acronym in parentheses.
  Example: Analog-to-Digital Converter (ADC).
- Don't initial-cap a letter that appears mid-word: Electromagnetic Interference (EMI), NOT
  ElectroMagnetic Interference.
- Later references in the same content: acronym only, no need to re-spell it out.
- Plural acronyms: lowercase "s" at the end always, even in all-caps text (HIGH-PERFORMANCE ADCs).
  Never use an apostrophe (ADCs, not ADC's). If the acronym already ends in S, plural still adds
  lowercase "s" (RTOSs, not RTOSes).
- See `acronyms-glossary.md` for Microchip's approved acronym list.

## Bulleted Lists (§1.2)
- Precede a bulleted list with a complete introductory sentence ending in a colon.
- Keep bullet items short and concise; don't use bullets for multi-sentence paragraphs.
- Marketing content: bullets are sentence fragments — no period at the end.
  **Technical documentation exception:** bullets may contain full sentences with normal punctuation.
- Capitalize only the first word of a bullet item unless it's a proper noun, acronym, or unit symbol.
  **Technical documentation exception applies to Features sections:**
  - Primary bullets: initial-cap all major words.
  - Sub-bullets: capitalize only the first word (same rule as general bullets).
- Use parallel wording/structure across bullet items (e.g., all bullets start with an action verb).

## Capitalization (§1.3)
- Sentence case is the default for body text. Only capitalize proper nouns, day/month names,
  trademarks, acronyms, and other standard capitalization cases.
- Don't capitalize generic terms (markets, applications, products) just for emphasis:
  Incorrect: "...for Automotive and Aerospace designs." Correct: "...for automotive and aerospace designs."
- Trademarked words follow the trademark owner's defined capitalization regardless of surrounding
  case: "dsPIC," never "dspic" or "DSPIC."
- Bits, modes, pins, and other technical terms follow `units-and-conventions.md` §6.5.

### Headlines, Titles, Subtitles
- Default: title case. **Technical documentation exception:** follow established doc-specific title
  conventions (may be all caps for some section titles).
- Title case rules: capitalize all major words; lowercase only conjunctions (and, nor, but), articles
  (a, an, the), and prepositions under 4 letters (as, by, for, in). Capitalize prepositions of 4+
  letters (e.g., "From," "With").
- In a compound adjective, capitalize the word after the hyphen if it's a major word:
  "High-Performance Solutions," not "High-performance Solutions."
- Titles are never multiple sentences and never end in a period (unless it's a question — then use "?").

## Dates and Times (§1.4)
- Default (worldwide content): Month Day, Year — e.g., "January 1, 2025." For regional content, local
  date/time conventions are acceptable.
- Day name (if included): always spell out in full, never abbreviate ("Wednesday," not "Wed.").
- Month: always spelled out in full, never abbreviated ("January," not "Jan.").
- No ordinal suffixes on dates with a year ("January 1, 2025," not "January 1st, 2025"). If the year is
  omitted, use the ordinal suffix ("January 1st").
- Comma after the year when a full date is mid-sentence: "Join us Wednesday, January 1, 2025, for..."
- Times: 12-hour format, numeral:numeral, no leading zero ("9:00 a.m.," not "09:00 a.m."), lowercase
  a.m./p.m. with periods, space before a.m./p.m. Midnight = 12:00 a.m.; noon = 12:00 p.m.

## Hyphenation and Dashes (§1.5)
- Hyphenate compound adjectives ("high-performance MCU").
- Don't hyphenate: a word that wraps to a new line/column/page, a URL, a proper noun/name, a
  trademark (unless it already has a hyphen), or "Microchip."
- See `terminology-glossary.md` for hyphenation of specific frequently-used industry terms.
- **En dash (–):** replaces "to" in a number/date range, no surrounding spaces. Example: "June–July,"
  "1–2 months," "Pages 40–45."
- **Em dash (—):** replaces commas/parens to set off extra content, no surrounding spaces.

## Numbers (§1.6)
- Spell out 0–9 in body text ("three host machines," not "3 host machines"). Exception: numbers used
  as adjectives describing a device, or in bit/register/channel names, stay as digits ("8-bit MCU," "bit 2").
- Use digits for 10 and up.
- Always use digits for ages, dates, percentages, ratios, ranges, measurements, decimals.
- Always spell out ordinal numbers (first, second, third), never 1st/2nd/3rd.
- Always spell out a number that begins a sentence.
- Use numerals for fractions (5½, not "5 and one-half").
- Page references: "page 1," never "pg. 1" or "pg1."
- Phone numbers: hyphens between sections, no parens around area code, comma before extension
  ("632-479-2817, ext. 17").
- Never use "#" before booth numbers.

## Punctuation (§1.7)
- **Colons:** Don't cap the first word after a colon introducing a list, unless it's a proper noun. Do
  cap the first word after a colon joining two independent clauses. Every bulleted list needs an
  introductory phrase ending in a colon. Never use "are/to/including/like" immediately before a colon —
  the colon replaces those words. One space after a colon.
- **Commas:** Use to separate items in a series; Oxford comma generally omitted unless needed for
  clarity in a complex sentence.
- **Exclamation marks:** Rare, only for genuine exclamations, never for emphasis. Never double (!!).
  **Technical documentation exception:** acceptable with system-generated messages.
- **Parentheses:** Use judiciously in marketing content (they interrupt flow). **Technical documentation
  exception:** parentheses are common and acceptable — follow doc-specific conventions.
- **Periods:** End every full sentence; never end a sentence fragment with one. One space after a
  period (never two).
- **Quotation marks:** Use curly quotes (" "), not straight/apostrophe substitutes — except in code,
  where exact characters matter. Never quote a term just for emphasis (implies sarcasm/doubt).

## Spacing (§1.8)
- Multi-character unit abbreviations get a space from the number (2.5 MHz, 3 kHz, 100 Mbps).
  Single-character units get no space (2.5V, 3A, 5Ω).
- Spaces around all math operators (2 + 2 = 4, 3 × 3 mm, < 10 mA).
- Temperatures: no space between digits, degree symbol, and scale letter (−40°C to +125°C). Use a
  true minus symbol for negative temps, not a hyphen.
- One space after a period. No space before ? or !. No spaces around slashes (cats/dogs) or en/em dashes.

## Symbols and Special Characters (§1.9)
- **Ampersand (&):** avoid — use "and" — unless it's literally part of a product name (or space is
  extremely limited, e.g., a small ad).
- **Degree (°):** always the real symbol, never a superscript "o."
- **Ellipsis (...):** only for omitted words in a quotation, never in regular copy or headlines.
  **Technical documentation exception:** acceptable in register/pin tables.
- **Minus (−):** always the true minus symbol for negatives (including temperatures), never a hyphen.
- **Multiplication (×):** always the real symbol in equations/dimensions, never the letter "x"
  ("3 × 3 mm package," not "3 x 3 mm package").
- **Percent (%):** always the symbol, never "percent" spelled out.
- **Plus-minus (±):** always the real symbol, never "+/-", unless truly unavailable.
- **Trademark symbols (™ ® ℠):** use the real symbol; if unavailable, use "(TM)," "(R)," "(SM)." Never
  confuse ® with the copyright symbol ©.

## Trademarks (§1.10)
- A trademark is an adjective and must always be paired with its approved noun, every instance in
  the document (not just first use). Example: every "PIC" reference needs its noun — "PIC MCU."
- Never pluralize or possessive a trademark ("PIC MCUs," never "PICs" or "PIC's").
- Use the ™/® symbol on first reference in any piece of content, and on first reference within any
  stand-alone element (table, image, diagram) even if already marked in the main text. Also mark
  first reference on every page of a PowerPoint deck.
- This applies to third-party trademarks too when known (Bluetooth®, Arm®, Wi-Fi®, USB-C®, etc. —
  see the source policy for the fuller reference list and links to third-party trademark pages).
