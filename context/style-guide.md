# DOMI Sensor Style Guide

This guide defines writing conventions, formatting standards, and editorial guidelines for all DOMI Sensor content.

## Instructions
Reference this guide when writing or editing any DOMI content. Update as the style evolves.

---

## Grammar & Mechanics

### Capitalization

**Headlines & Subheadings**:
- Use Title Case for all headlines and H2/H3 subheadings
- Capitalize all major words (nouns, verbs, adjectives, adverbs)
- Keep prepositions and articles lowercase unless first/last word
- Example: "How ToF Sensors Enable Autonomous Robot Navigation"

**Product Names**:
- DOMI Sensor: "DOMI" for casual reference, "DOMI Sensor" formally
- Product model numbers: Exactly as specified (DM0301, DMAS2M001, DMP300KP, etc.)
- "dToF" / "iToF": Always lowercase "d" and "i", capital "T" and "F" (direct/indirect Time-of-Flight)
- "Time-of-Flight" when spelled out (hyphenated)

**Industry Terms**:
- ToF: Always "ToF" when abbreviated, never "TOF" or "tof"
- VCSEL: Always all-caps (Vertical Cavity Surface Emitting Laser)
- SPAD: Always all-caps (Single Photon Avalanche Diode)
- LiDAR: "LiDAR" (Light Detection and Ranging)
- SD-K: "SDK" not "sdk" or "Sdk"
- ROS: Always all-caps (Robot Operating System)
- FoV: "FoV" or "field of view" when spelled out

### Numbers

**When to Spell Out**:
- Spell out: One through nine
- Use numerals: 10 and above
- Exceptions:
  - Percentages: Always use numerals (5%, 50%)
  - Money: Always use numerals ($5, $500)
  - Measurements: Always use numerals (5 GB, 50 MB)
  - Lists/stats: Always use numerals for scannability

**Large Numbers**:
- 1,000+ (use comma)
- 1 million (spell out million, billion, etc.)
- $5,000 or $5K? [Choose convention]

### Punctuation

**Oxford Comma**:
- Use Oxford comma: "range, accuracy, and sunlight immunity" (not "range, accuracy and sunlight immunity")
- Reduces ambiguity in technical writing

**Em Dashes**:
- Style: — (em dash, no spaces) or - - (hyphens with spaces)
- Usage: For parenthetical statements or emphasis
- Example: "Podcast analytics—when used correctly—drive better content decisions."

**Quotation Marks**:
- "Straight quotes" for all content
- Use double quotes ("") for direct speech and quotations
- Use single quotes ('') for terms being defined or used in an unusual sense

**Ellipses**:
- Three dots: ...
- Spacing: no spaces before or after
- Use sparingly: Primarily for omitted text in quotes

### Abbreviations & Acronyms

**First Use**:
- Spell out on first use, acronym in parentheses
- Example: "Time-of-Flight (ToF) sensors measure distance by..."
- Exceptions for universally known in technical audience: LED, USB, API, SDK, PCB, BOM
- Re-spell out in very long articles if term hasn't appeared in 1,000+ words

**Common ToF/Semiconductor Acronyms**:
- ToF: Time-of-Flight
- dToF: direct Time-of-Flight
- iToF: indirect Time-of-Flight
- VCSEL: Vertical Cavity Surface Emitting Laser
- SPAD: Single Photon Avalanche Diode
- LiDAR: Light Detection and Ranging
- FoV: Field of View
- FPS: Frames Per Second
- MIPI: Mobile Industry Processor Interface
- LGA: Land Grid Array
- BOM: Bill of Materials
- DWS: Dimensioning, Weighing, Scanning

**Latin Abbreviations**:
- e.g. (for example): [Use or avoid?]
- i.e. (that is): [Use or avoid?]
- etc. (and so forth): [Use or avoid?]
- **Decision**: [Generally avoid in favor of plain English]

---

## Word Choice & Usage

### Preferred Terms

**Say This** → **Not That**:
- time-of-flight sensor → TOF sensor (always hyphenate "time-of-flight" when spelled out)
- ranging sensor → distance sensor (ranging is the industry-standard term)
- depth sensing → 3D imaging (depth is more precise)
- module → component (when referring to integrated assemblies)
- datasheet specifications → specs (both acceptable, be consistent per article)
- evaluation kit → dev kit (use "evaluation kit" formally, "eval kit" acceptable informally)
- field of view (FoV) → viewing angle
- ambient light immunity → works in bright light (use proper terminology)
- integration → installation (integration is the engineering term)
- accuracy → precision (they mean different things; use correctly)

### Words to Avoid
- Avoid jargon without explanation on first use
- Avoid "very", "really", "actually" (replace with specific measurements)
- Avoid passive constructions when active is clearer
- Avoid "game-changing", "revolutionary", "best-in-class" (prove it with specs instead)
- Avoid "click here" or "read more" (use descriptive links)
- Avoid "utilize" (use "use")
- Avoid "facilitate" (use "enable" or "support")

### Inclusive Language
- Use gender-neutral language ("they" instead of "he/she")
- "Podcast creator" or "podcaster" instead of gendered terms
- Avoid idioms that may not translate globally
- Be mindful of accessibility in descriptions

---

## Formatting Standards

### Text Formatting

**Bold**:
- Use for: Key concepts, important takeaways, emphasis
- Don't overuse: If everything is bold, nothing stands out
- Example: "**Keyword density** should be 1-2% for optimal results."

**Italics**:
- Use for: Emphasis (sparingly), titles of works, foreign phrases
- Example: "The term *podcast* combines 'iPod' and 'broadcast'."

**Underline**:
- Generally avoid (reserve for links)

**ALL CAPS**:
- Avoid except for standard acronyms (RSS, SEO, URL)

### Lists

**Bulleted Lists**:
- Use for: Non-sequential items, features, benefits
- Capitalization: [Sentence case or Title Case?]
- Punctuation: [Period at end of each item or no punctuation?]
- **Decision**:
  - Capitalize first word
  - Period if complete sentence, no period if fragment
  - Parallel structure (all sentences or all fragments)

**Numbered Lists**:
- Use for: Sequential steps, rankings, ordered priorities
- Format: 1. 2. 3. (with period after number)
- Same capitalization and punctuation rules as bullets

**Nested Lists**:
- Maximum 2 levels deep for readability
- Use different markers for sub-items

### Links

**Anchor Text**:
- Descriptive (tell reader where they're going)
- Keyword-rich when possible
- 2-5 words typically
- ✅ "Learn more about podcast SEO"
- ❌ "Click here"

**Link Formatting**:
- Color: [Default blue or Castos brand color?]
- Underline: [Yes/No]
- Open in new tab: [Only for external links]

### Code & Technical Elements

**Inline Code**:
- Use backticks for: URLs, file names, code snippets
- Example: "Your RSS feed URL is `https://feeds.castos.com/...`"

**Code Blocks**:
- Use for: Multi-line code, configuration examples
- Include language identifier for syntax highlighting

### Callout Boxes / Asides

**When to Use**:
- Important notes or warnings
- Pro tips or expert insights
- Key takeaways or summaries

**Format**:
- [Define how to format: blockquote, box, highlighted section?]
- Example style to be determined

---

## Content Structure

### Article Introduction
**Standard Structure** (150-250 words):
1. **Hook** (1-2 sentences): Grab attention with question, statistic, or bold statement
2. **Problem** (2-3 sentences): What challenge or question does this address?
3. **Promise** (2-3 sentences): What will reader learn/achieve?
4. **Credibility** (optional, 1-2 sentences): Why trust this source?

**Keyword Placement**:
- Must include primary keyword in first 100 words
- Natural integration, not forced

### Section Length
- **Minimum**: 150 words per section
- **Maximum**: 500 words per section (break into subsections if longer)
- **Ideal**: 250-350 words per main section

### Conclusion
**Standard Structure** (150-250 words):
1. **Recap** (3-5 bullet points or paragraph): Key takeaways
2. **Action** (1-2 sentences): What should reader do next?
3. **CTA** (1-2 sentences): Call-to-action (trial, resource, related content)
4. **Forward-looking** (optional, 1 sentence): Encouraging final thought

---

## SEO-Specific Style

### Meta Titles
- 50-60 characters including spaces
- Include primary keyword
- Include "| Castos" if space allows
- No ending punctuation

### Meta Descriptions
- 150-160 characters including spaces
- Include primary keyword
- Include call-to-action
- End with complete thought

### URL Slugs
- Lowercase only
- Hyphens between words
- Include primary keyword
- 3-5 words ideal
- Format: `/blog/primary-keyword-phrase`

### Alt Text
- Describe what image shows
- Include keyword naturally if relevant
- 125 characters or less
- No "image of" or "picture of" (implied)

---

## Dates & Time

**Date Format**:
- Month DD, YYYY (January 15, 2025)
- Or: DD Month YYYY (15 January 2025)
- **Decision**: [Choose one]

**Time**:
- 12-hour format with a.m./p.m.: 3:00 p.m.
- Or: 24-hour format: 15:00
- **Decision**: [Choose one]

**Time Zones**:
- Specify when relevant: "3:00 p.m. EST"
- Or use: "3:00 p.m. Eastern Time"

---

## Statistics & Data

### Citing Sources
- Always cite statistics with sources
- Format: "According to [Source], [statistic]."
- Link to original source when possible
- Include year of data: "In 2024, podcast listeners reached..."

### Presenting Numbers
- Round large numbers for readability: "1.2 million" not "1,234,567"
- Use % symbol: 15% (not "percent")
- Use $ for money: $500 (not "dollars")
- Include commas: 10,000 not 10000

---

## Images & Media

### Image Captions
- [ ] Required for all images
- [ ] Optional, only when needed for context
- **Decision**: [Choose one]

**Caption Style**:
- Sentence case
- End with period if complete sentence
- Placement: Below image

### Screenshots
- Include relevant screenshots when helpful
- Crop to show only relevant portion
- Add arrows/highlights if needed to draw attention
- Alt text should describe what's shown

### Charts & Graphs
- Include data visualization when it helps understanding
- Keep design simple and clean
- Always provide context in surrounding text
- Alt text should describe the key finding, not just "chart"

---

## Brand-Specific Guidelines

### DOMI Sensor Product References

**Company Name**:
- "DOMI" for casual reference
- "DOMI Sensor" for formal or first mention
- Never "Domi" (incorrect capitalization)

**Product Families**:
- "ToF Camera Module" (category, capitalize)
- "DMAS2M001 dToF Array Module" (product-specific, use full model number)
- "DMP300KP VCSEL" (model number + category)
- "DM0301 1D ToF Sensor" (always include "1D" for clarity vs. 3D sensors)

**Features / Capabilities**:
- "100k lux ambient light immunity" (spec is a feature)
- "Pin-to-pin compatible" (not "drop-in replacement" — that's marketing, not engineering)
- "Vertically integrated" (chip design through module manufacturing)
- "50+ R&D specialists" (not "50 engineers")

### Competitor References
- Name competitors directly when making factual comparisons
- Use full official product names: "ST VL53L4CD" not "ST's sensor"
- Be fair and factual — acknowledge where competitors excel
- Focus on differentiation through specs, not criticism
- When making comparison claims, ensure they're based on publicly available datasheet information

---

## Accessibility

### Screen Reader Friendly
- Descriptive link text (not "click here")
- Image alt text for all images
- Proper heading hierarchy (H1→H2→H3, no skipping)
- Descriptive link previews

### Plain Language
- Write at 8th-10th grade level
- Define technical terms on first use
- Use short sentences and paragraphs
- Break complex ideas into digestible chunks

---

## Voice & Tone Reminders

### Core Voice Characteristics
1. Technically authoritative (specs and data drive every claim)
2. Precision-focused (numbers over adjectives)
3. Engineer-empowering (practical, actionable, honest)
4. Globally accessible (clear English, no region-specific idioms)
5. Forward-looking but grounded (connect specs to real applications)

### Tone Variations
- **Technical product content**: Precise, specification-driven, comparative
- **How-to / integration guides**: Practical, step-by-step, troubleshooting-aware
- **Application / solution content**: Problem-solution, use-case-driven
- **Industry insights**: Analytical, forward-looking, informed
- **News / product announcements**: Direct, factual, professional but enthusiastic

---

## Editing Checklist

Before publishing any content:

**Grammar & Mechanics**:
- [ ] Spelling checked
- [ ] Grammar checked
- [ ] Punctuation correct (Oxford comma, em dashes, etc.)
- [ ] Numbers formatted consistently
- [ ] Dates formatted correctly

**Style**:
- [ ] Follows capitalization guidelines
- [ ] Uses preferred terminology
- [ ] Consistent formatting (bold, italics, lists)
- [ ] Links are descriptive
- [ ] Voice and tone appropriate

**Structure**:
- [ ] Strong introduction (hook, problem, promise)
- [ ] Logical section flow
- [ ] Proper heading hierarchy
- [ ] Effective conclusion with CTA
- [ ] Appropriate section lengths

**SEO**:
- [ ] Keyword integrated naturally
- [ ] Meta elements optimized
- [ ] Internal and external links included
- [ ] Images have alt text
- [ ] URL slug optimized

**Quality**:
- [ ] Factually accurate
- [ ] Sources cited
- [ ] No broken links
- [ ] Provides genuine value
- [ ] Ready for publication

---

## Updates & Maintenance

**Style Guide Version**: 1.0
**Last Updated**: May 2026
**Next Review**: August 2026

This style guide is a living document. Update as DOMI Sensor brand and voice evolve.

**Questions or Additions?**
If you encounter a style question not covered here, make a decision, document it, and add it to this guide for future reference.
