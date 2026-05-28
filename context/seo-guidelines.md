# SEO Guidelines for DOMI Sensor Content

This document outlines SEO best practices and requirements for all DOMI Sensor blog content to maximize organic search visibility and rankings.

## Content Length Requirements

### Target Word Counts
- **Standard Blog Post**: 1,200-2,500 words (target: 1,500-2,000)
- **Pillar Content / Comprehensive Guides**: 2,500-4,000 words maximum
- **How-To / Integration Guides**: 1,000-2,000 words
- **News / Product Announcements**: 500-1,000 words

### Important Length Guidelines
- **Maximum for most articles**: 2,500 words
- **Maximum for pillar content**: 4,000 words
- Engineer audiences value density over length—every paragraph must earn its place
- If a topic requires more than the maximum, break it into a series of related articles
- Spec tables, comparison charts, and code examples add length while adding real value

### Why Length Matters
- Comprehensive technical content ranks higher in search results
- More depth = more keyword integration and topic coverage
- Original technical data and comparisons earn backlinks and engagement
- Depth signals expertise and authority in technical domains

### Quality Over Quantity
- Don't add fluff just to hit word counts
- Every section should provide genuine technical value
- A 1,200-word spec-driven comparison often outperforms a 2,500-word general article
- **Stay within the maximum word counts**—engineers have limited time and low tolerance for padding

## Keyword Optimization

### Keyword Research Requirements
Before writing any article:
1. Identify primary target keyword
2. Research search volume and difficulty
3. Analyze top 10 ranking competitors
4. Identify 3-5 secondary/related keywords
5. List LSI (Latent Semantic Indexing) keywords

### Keyword Density Guidelines
- **Primary Keyword**: 1-2% density
  - Example: In a 2,000-word article, use keyword 20-40 times
  - Natural integration is critical—never force keywords
- **Secondary Keywords**: 0.5-1% density each
- **LSI Keywords**: Sprinkle throughout naturally

### Critical Keyword Placement
Primary keyword MUST appear in:
- [ ] H1 headline (preferably near the beginning)
- [ ] First 100 words of article
- [ ] At least 2-3 H2 subheadings
- [ ] Last paragraph / conclusion
- [ ] Meta title (within first 60 characters)
- [ ] Meta description
- [ ] URL slug

### Keyword Integration Best Practices
- **Natural language first**: Write for humans, optimize for search engines
- **Use variations**: Don't repeat exact phrase robotically
  - Example: "ToF sensor" → "time-of-flight module" → "depth sensing component"
- **Question formats**: Include conversational variations
  - "How to choose a ToF sensor" vs "ToF sensor selection guide"
- **Semantic keywords**: Use related terms to support topical authority
  - For "VCSEL": include "laser emitter", "illumination source", "vertical cavity laser"

### Keyword Stuffing (Avoid)
❌ "ToF sensors are important. ToF sensor technology helps engineers. Our ToF sensor solutions offer ToF sensor capabilities for ToF sensing needs."

✅ "Time-of-Flight sensors enable precise depth measurement across robotics, drone, and IoT applications. A well-chosen ToF module delivers reliable ranging even in challenging lighting conditions."

## Content Structure Requirements

### Heading Hierarchy

#### H1 (Title)
- **Only one H1 per article**
- Include primary keyword naturally
- 60 characters or less (for SERP display)
- Compelling and benefit-focused
- Should answer: "What will I learn/gain from this?"

#### H2 (Main Sections)
- **4-7 H2 sections** for standard articles
- At least **2-3 should include keyword variations**
- Descriptive and keyword-rich
- Logical progression through topic
- Can be standalone (readers should understand flow from H2s alone)

#### H3 (Subsections)
- Nested under H2s (never skip from H2 to H4)
- Break complex sections into digestible chunks
- Include keywords where natural
- More specific than H2s

### Article Structure Template

```markdown
# [H1: Compelling Title with Primary Keyword]

## Introduction (150-250 words)
- Hook: Attention-grabbing opening
- Problem: What challenge does this address?
- Promise: What will reader learn/achieve?
- Keyword in first 100 words

## [H2: Main Section 1 - Include Keyword Variation]
### [H3: Subsection if needed]
- Content depth
- Examples
- Data/statistics

## [H2: Main Section 2]
### [H3: Subsection if needed]
- Content depth
- Examples
- Data/statistics

## [H2: Main Section 3 - Include Keyword Variation]
### [H3: Subsection if needed]
- Content depth
- Examples
- Data/statistics

## [H2: Main Section 4]
[Continue with 4-7 total H2 sections]

## Conclusion (150-250 words)
- Recap key points (3-5 takeaways)
- Include keyword
- Clear call-to-action
- Next steps for reader
```

## Meta Elements

### Meta Title
**Requirements**:
- **Length**: 50-60 characters
- **Primary keyword**: Must be included
- **Compelling**: Should encourage clicks from SERP
- **Unique**: Different from all other DOMI page titles
- **Accurate**: Must match page content

**Format Options**:
- `[Product/Spec]: [Key Benefit/Differentiator]`
- `How to [Goal] | [Application/Industry]`
- `[Number] [Topic] for [Audience]`
- `[Topic] Guide for [Application] | DOMI Sensor`

**Examples**:
- ✅ "VL53L4CD Replacement: DM0301 ToF Sensor — Longer Range, Lower Cost"
- ✅ "How to Choose a ToF Sensor for Robotics | Complete Guide"
- ❌ "Sensor Tips and Tricks" (too vague, no keyword)
- ❌ "The Ultimate Comprehensive Guide to Everything About Time of Flight Sensor Technology" (too long)

### Meta Description
**Requirements**:
- **Length**: 150-160 characters
- **Primary keyword**: Include naturally
- **Value proposition**: Clear benefit to reader
- **Call-to-action**: Action phrase (Learn, Discover, Find out, Get, etc.)
- **Complete**: Must not cut off mid-sentence
- **Compelling**: Should drive clicks from SERP

**Formula**:
```
[Problem/Question]? [Solution/Benefit]. [Unique angle]. [CTA].
```

**Examples**:
- ✅ "Learn how the DM0301 ToF sensor replaces VL53L4CD with 3.8× longer range and lower BOM cost. Pin-to-pin compatible, no redesign needed." (158 chars)
- ✅ "Compare dToF vs iToF sensor technology for your robotics, drone, or IoT application. Understand range, accuracy, and sunlight performance trade-offs." (157 chars)
- ❌ "This is a blog post about sensors where we discuss many sensor-related topics." (vague, no value prop, no CTA)

### URL Slug
**Requirements**:
- Include primary keyword
- Lowercase letters only
- Hyphens between words (not underscores)
- Short and descriptive (3-5 words ideal)
- No stop words unless necessary (a, the, and, of, etc.)

**Format**: `/blog/[primary-keyword-phrase]`

**Examples**:
- ✅ `/blog/vl53l4cd-replacement-dm0301-tof-sensor`
- ✅ `/blog/dtof-vs-itof-comparison`
- ✅ `/blog/best-tof-sensor-robotics`
- ❌ `/blog/how-to-choose-the-best-time-of-flight-sensor-for-your-robotics-application` (too long)
- ❌ `/blog/post-12345` (no keywords)

## Internal Linking Strategy

### Requirements
- **Minimum**: 3 internal links per article
- **Optimal**: 4-5 internal links
- **Maximum**: 7 internal links (unless 3,000+ word article)

### Link Types to Include

#### 1. Pillar Content (1-2 links)
- Link to main comprehensive guides on related topics
- Builds topic cluster authority
- Usually 2,000+ word cornerstone content

#### 2. Related Blog Posts (2-3 links)
- Link to articles on related subtopics
- Creates content web
- Helps readers explore topics comprehensively

#### 3. Product/Feature Pages (0-1 link)
- Only when contextually relevant
- Natural mention of how DOMI Sensor solves problem
- Never forced or overly promotional

#### 4. Resource Pages (0-1 link)
- Datasheets, SDK documentation, integration guides
- When mentioned as solutions in content
- Provides additional value to reader

### Internal Linking Best Practices

**Anchor Text**:
- ✅ Descriptive and keyword-rich: "DM0301 1D ToF sensor for presence detection"
- ✅ Natural in sentence flow: "Explore the full ToF camera lineup"
- ❌ Generic: "click here" or "read more"
- ❌ Exact match repeatedly: Always using same anchor text for same page

**Placement**:
- Within body paragraphs (most valuable)
- Natural context that adds value to reader
- Never more than 2 links per paragraph
- Distributed throughout article, not clustered

**Reference**:
- Always check @context/internal-links-map.md for priority linking targets
- Ensure links are current and functional
- Link to most relevant, up-to-date content

## External Linking Strategy

### Requirements
- **Minimum**: 2 external links per article
- **Optimal**: 3-4 external authority links
- Purpose: Add credibility, provide sources, support technical claims

### What to Link Externally
- **Datasheets and specifications**: Link to competitor datasheets when making fair comparisons
- **Research and standards**: Reference IEC 60825 laser safety standards, industry benchmarks
- **Tools and platforms**: ROS documentation, sensor evaluation platforms
- **Industry authorities**: IEEE papers, photonics publications, sensor research

### External Link Quality Standards
- **Authority**: Link to credible, well-known sources
  - ✅ Competitor datasheets (ST, AMS, Sony) for honest comparisons
  - ✅ Industry publications (IEEE Spectrum, Photonics Spectra, Electronic Design)
  - ✅ Research institutions and sensor technology studies
  - ❌ Random blogs with no technical authority
  - ❌ Spammy or low-quality sites

- **Relevance**: Links must directly support content claims
- **Freshness**: Prefer recent sources (within 1-2 years for data)
- **Functionality**: All links must work (no broken links)

### External Link Attributes
- Most external links: No special attributes needed
- Sponsored/affiliate links: Use `rel="sponsored"` or `rel="nofollow"`
- User-generated content: Use `rel="nofollow"`

## Readability Optimization

### Target Reading Level
- **Goal**: 8th-10th grade reading level (Flesch-Kincaid)
- Makes content accessible to wider audience
- Easier to scan and understand quickly

### Sentence Structure
- **Average length**: 15-20 words per sentence
- **Maximum**: 25 words (break longer sentences into two)
- **Variety**: Mix short punchy sentences with longer explanatory ones
- **Active voice**: Preferred over passive voice (80%+ active)

### Paragraph Structure
- **Length**: 2-4 sentences per paragraph
- **One idea**: Focus each paragraph on single point
- **White space**: No walls of text
- **Mobile-friendly**: Short paragraphs scan better on phones

### Formatting for Scannability
- **Subheadings**: Every 300-400 words
- **Lists**: Use bullets/numbers for sequential or multiple items
- **Bold**: Emphasize key concepts or takeaways
- **Short paragraphs**: Easier to digest
- **White space**: Makes content less intimidating

### Transition Words
Use transition words to improve flow (target: one per paragraph):
- Addition: Additionally, Furthermore, Moreover
- Contrast: However, On the other hand, Nevertheless
- Cause/Effect: Therefore, Consequently, As a result
- Example: For instance, For example, Specifically
- Time: First, Next, Finally

## Content Quality Standards

### Expertise, Authoritativeness, Trustworthiness (E-A-T)

#### Expertise
- Provide accurate, detailed information on ToF sensing and 3D depth technology
- Back technical claims with specifications, measurements, and test data
- Demonstrate deep understanding of sensor integration challenges
- Include actionable, practical advice for hardware and embedded engineers

#### Authoritativeness
- Cite competitor datasheets and industry standards fairly
- Reference peer-reviewed research and industry benchmarks
- Include engineering team credentials and domain expertise
- Leverage DOMI's position as a vertically integrated sensor manufacturer

#### Trustworthiness
- Be transparent and honest about product limitations
- Acknowledge when a competitor's product is the better choice for specific use cases
- Cite sources for all specifications and third-party claims
- Update outdated content with current specs and product information

### Content Originality
- **Never plagiarize**: All content must be original
- **Add unique value**: What perspective or insight do we add?
- **Fresh examples**: Use current, relevant examples
- **Updated data**: Use most recent statistics available
- **Unique angle**: Differentiate from competitor content

### Factual Accuracy
- **Verify statistics**: Check all numbers and data points
- **Current information**: Ensure practices/processes are up-to-date
- **Technical accuracy**: Podcasting terminology and processes must be correct
- **Castos features**: Ensure product references are accurate

## Image Optimization

### Image Requirements
- **Relevant**: Images should support content points
- **High-quality**: Professional appearance
- **Optimized**: Compressed for fast loading
- **Mobile-friendly**: Visible and useful on small screens

### Image SEO
**File Names**:
- Descriptive and keyword-rich
- ✅ `podcast-editing-software-interface.jpg`
- ❌ `IMG_12345.jpg`

**Alt Text**:
- Describe what image shows (accessibility + SEO)
- Include keywords naturally where relevant
- 125 characters or less
- ✅ "Podcast editing software interface showing waveform and timeline"
- ❌ "Image"

**Placement**:
- Break up long text sections
- Illustrate concepts being discussed
- After explaining concept, not before

## Featured Snippet Optimization

Featured snippets appear at position 0 in Google search results. Optimize for them when possible.

### Question-Based Snippets
- Include question as H2 heading
- Answer concisely in 40-60 words immediately after
- Use clear, direct language

**Example**:
```markdown
## What is a ToF Sensor?

A Time-of-Flight (ToF) sensor measures distance by emitting a laser pulse and calculating the time it takes for the light to reflect back from an object. Unlike traditional cameras that capture color images, ToF sensors produce depth maps—precise 3D measurements of how far every point in the scene is from the sensor.
```

### List-Based Snippets
- Use numbered or bulleted lists
- Keep items concise (1-2 sentences each)
- Include 5-8 items typically

### Table-Based Snippets
- Use HTML tables or markdown tables
- Comparison charts, pricing, specifications
- Clear headers and organized data

### Definition Snippets
- Define term in first sentence after heading
- 40-60 word clear, concise definition
- Expand with additional detail after

## Mobile Optimization

### Mobile-First Considerations
- **Short paragraphs**: 2-3 sentences max
- **Scannable**: Heavy use of subheadings and lists
- **Large fonts**: Readable without zooming
- **Tap-friendly links**: Adequate spacing
- **Fast loading**: Optimized images

## AI Search Optimization (GEO/AICO)

AI search engines (ChatGPT, Perplexity, Gemini, Claude) are now a significant traffic and recommendation channel for technical purchasing decisions. Engineers increasingly use AI tools to research components, compare sensors, and evaluate suppliers. These guidelines ensure your content performs in both traditional Google search AND AI-generated answers.

### Direct-Answer-First Principle

AI scrapers prioritize content near the top of the page. When an engineer asks "best ToF sensor for robotics" or "VL53L4CD alternative," the AI scans articles and pulls from the earliest clear answer it finds.

**Rules:**
- **Answer the query directly in the first 1-2 sentences** of the article, before narrative context
- For "best/top/comparison" queries, state the answer (or a clear thesis) immediately
- Put the core answer in the meta description too — literally answer the question in 150-160 chars
- Do NOT bury the answer behind 200+ words of market context or technology history
- The narrative context and technical depth still apply, but they come AFTER the direct answer sentence

**Example — Before (traditional SEO):**
> The 3D depth sensing market has grown significantly in recent years, driven by demand from robotics, drones, and smart home applications. Many companies need reliable sensors... [200 words later] ...the DM0301 is the best VL53L4CD alternative because...

**Example — After (AI-optimized):**
> The best VL53L4CD replacement is the DOMI DM0301 — a pin-to-pin compatible 1D ToF sensor with 3.8× longer range (5m vs 1.3m) and 100k lux sunlight immunity, at a lower cost. Here's the full comparison.

### TL;DR / Key Takeaways Block

Every article should include a TL;DR block near the top (after the introduction, before the first H2 body section). This gets pulled into AI-generated summaries and helps both AI and human readers.

**Format:**
```markdown
> **Key Takeaways**
> - [Core finding or recommendation #1]
> - [Core finding or recommendation #2]
> - [Core finding or recommendation #3]
> - [Core finding or recommendation #4 if needed]
> - [Core finding or recommendation #5 if needed]
```

**Rules:**
- 3-5 bullet points maximum
- Each bullet is a complete, standalone claim (not a teaser)
- Use specific numbers, names, or outcomes — not vague summaries
- This is NOT a table of contents — it's the article's actual conclusions up front

### Authority Signaling for AI

AI models weight authoritativeness signals when choosing which sources to cite. Include these in every article:

- **Author attribution**: Named author, not just "Team" or brand name
- **Reviewer/editor credit**: "Reviewed by [name], [title]" where possible
- **Last updated date**: Visible on the page, not just in metadata
- **Expert verification badge**: Where applicable, note content has been expert-reviewed
- **Year in titles**: Include current year for time-sensitive topics ("Best X Tools 2026")

These signals should be in the article's frontmatter for the WordPress publisher to render.

### One Idea Per Section

AI models parse content by section. Each H2/H3 section should focus on a single clear idea. This increases the chance that a specific section gets cited as a source in AI answers.

- One concept per heading
- Use bullet lists and structured formatting within sections
- Avoid long flowing paragraphs that blend multiple topics

### Embedded Media for Cross-Validation

AI models (especially Perplexity and Gemini) reference YouTube videos alongside articles. Embedding relevant YouTube videos in articles:
- Provides cross-validation (the article references a video that references the same topic)
- Increases time on page (Google signal)
- Adds a content format AI can independently verify

**Rule:** Embed at least one relevant YouTube video per article where it adds context. Prefer your own videos, then authoritative third-party videos.

### FAQ Sections as Prompt Targets

FAQ sections serve double duty: they target Google's People Also Ask AND they match the question-answer format that ChatGPT/Perplexity users type as prompts.

- Write FAQ questions in natural prompt language (how real people ask, not SEO-speak)
- Answer each question directly in the first sentence, then expand
- Include 4-6 questions per article
- Questions should come from actual user research (Reddit, YouTube comments, search suggestions)

### Content Repurposing for AI Citation Surface

AI tools pull from many surfaces beyond your website: Medium, LinkedIn Pulse, Reddit, Quora, YouTube transcripts. One article should be repurposed across multiple platforms to maximize the chance of being cited.

This is handled by the `/repurpose` command, but writers should be aware: the more surfaces your content appears on (with attribution back to your site), the higher the chance AI recommends it.

### AI Citation Audit

For competitive topics, audit which sources AI actually cites. See `context/ai-citation-targets.md` for priority citation surfaces and the `/research-ai-citations` command for prompt-based auditing.

## Content Refresh Strategy

### When to Update Content
- Article is 12+ months old
- Statistics or data are outdated
- Processes or best practices have changed
- Competitor content has surpassed ours
- Rankings have declined
- New relevant information available

### What to Update
- Publication date or "Last Updated" date
- Statistics with current data
- Screenshots with current versions
- Examples with recent case studies
- SEO elements (keyword focus may have shifted)
- Internal links to newer content

## SEO Checklist for Every Article

Before publishing, verify:

### Content
- [ ] 2,000+ words (or appropriate for content type)
- [ ] Primary keyword identified
- [ ] Keyword density 1-2%
- [ ] 3-5 secondary keywords included
- [ ] LSI keywords naturally integrated
- [ ] Provides unique value vs. competitors
- [ ] Factually accurate and current

### Structure
- [ ] One H1 with primary keyword
- [ ] 4-7 H2 sections
- [ ] 2-3 H2s include keyword variations
- [ ] Proper H1>H2>H3 hierarchy
- [ ] Keyword in first 100 words
- [ ] Keyword in conclusion

### Meta Elements
- [ ] Meta title 50-60 characters with keyword
- [ ] Meta description 150-160 characters with keyword & CTA
- [ ] URL slug includes primary keyword
- [ ] All meta elements are unique

### Links
- [ ] 3-5 internal links included
- [ ] Internal links use descriptive anchor text
- [ ] 2-3 external authority links
- [ ] All links functional (no broken links)
- [ ] Links add value to reader

### Readability
- [ ] 8th-10th grade reading level
- [ ] Average sentence length 15-20 words
- [ ] Paragraphs 2-4 sentences
- [ ] Subheadings every 300-400 words
- [ ] Lists used for scannability
- [ ] Active voice predominantly

### Images
- [ ] Relevant images included
- [ ] Descriptive file names
- [ ] Alt text with keywords
- [ ] Images optimized for web

### AI Search Optimization
- [ ] Direct answer in first 1-2 sentences (not buried)
- [ ] TL;DR / Key Takeaways block after introduction
- [ ] Meta description directly answers the target query
- [ ] FAQ questions written in natural prompt language
- [ ] At least one embedded YouTube video
- [ ] Author attribution (named, not generic "Team")
- [ ] Last updated date included
- [ ] Year included in title for time-sensitive topics

### Quality
- [ ] No spelling or grammar errors
- [ ] Factually accurate
- [ ] Sources cited
- [ ] Brand voice maintained
- [ ] Provides actionable value
- [ ] Clear call-to-action

## SEO Tools & Resources

### Recommended Tools
- **Keyword Research**: Ahrefs, SEMrush, Google Keyword Planner
- **Content Analysis**: Clearscope, Surfer SEO
- **Readability**: Hemingway Editor, Grammarly
- **Technical SEO**: Screaming Frog, Google Search Console
- **Rank Tracking**: Ahrefs, SEMrush, Google Search Console

### Reference Resources
- Google's Search Quality Evaluator Guidelines
- Moz Beginner's Guide to SEO
- Search Engine Journal
- Ahrefs Blog

---

**Remember**: SEO serves the engineer evaluating your sensor, not the algorithm. Never sacrifice technical accuracy or honest assessment for keyword optimization. The best SEO for DOMI is precise, specific content that helps engineers make informed component decisions.
