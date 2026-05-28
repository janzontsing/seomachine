# AI Citation Targets

When AI tools (ChatGPT, Perplexity, Gemini, Claude) recommend products or services, they pull from sources across the web. This file tracks the platforms, directories, and content surfaces where your brand needs to be present and well-represented to maximize AI citation frequency.

## How This File Is Used

- **Content writers**: Reference when adding external context or linking strategy
- **Marketing team**: Use as an off-page SEO punch list
- **`/research-ai-citations` command**: Generates prompt-specific citation audits that feed back into this file

## Priority Citation Surfaces

### Tier 1: Software Review Directories (Highest AI Citation Frequency)

These directories are cited most frequently when AI tools recommend SaaS products:

| Platform | Listed? | Priority Action |
|----------|---------|-----------------|
| G2 | Verify | Maintain reviews, respond to feedback, keep feature list current |
| Capterra | Verify | Same as G2 |
| TrustRadius | Verify | Especially important for enterprise/B2B queries |
| Product Hunt | Verify | Historical listing matters for "best new tools" queries |
| AlternativeTo | Verify | Critical for "alternatives to [competitor]" prompts |
| Slant | Verify | Comparison-focused, frequently cited in "vs" queries |

### Tier 2: Industry-Specific Directories (ToF/Sensor/Semiconductor)

| Platform | Listed? | Priority Action |
|----------|---------|-----------------|
| Octopart | Verify | Ensure all DOMI products listed with current specs and pricing |
| Digi-Key / Mouser / Arrow | Verify | List core products through distribution channels |
| ElectronicsPoint / EEVblog | Monitor | Active electronics engineering communities |
| ROS Components / ROS Discourse | Verify | Ensure ROS drivers and sensor documentation links back to DOMI |
| IEEE Spectrum / Photonics Spectra | Outreach | Submit product news and technical articles |

### Tier 3: Listicle Articles (Outreach Targets)

AI tools heavily cite "best X" listicle articles. These are the types of articles where your brand should appear:

- "Best [your category] Tools [Year]" articles on major tech/media sites
- "Best [your category] for Beginners" roundups
- "[Your category] Comparison" articles
- "[Your category] for [specific use case]" roundups

**Outreach strategy**: Identify the author, provide value (updated pricing, new features, unique angle), and request inclusion or update.

### Tier 4: Social/Community Platforms

AI tools pull from these surfaces, especially for recent recommendations:

| Platform | Strategy |
|----------|----------|
| **Reddit** (your niche subreddits) | Comment on existing high-upvote threads with genuine value. Comments on popular threads outperform new posts. Use F5Bot to track keyword mentions. |
| **Medium** | Repurpose blog articles as Medium posts with attribution back |
| **LinkedIn Pulse** | Repurpose articles, especially for B2B use cases |
| **Quora** | Answer relevant questions with genuine expertise |
| **YouTube** | Video content gets cross-referenced by Perplexity and Gemini especially |

### Tier 5: Reputation Platforms

AI models read and synthesize review sentiment when making recommendations:

| Platform | Action |
|----------|--------|
| Google Business Profile | Maintain if applicable |
| Trustpilot | Encourage satisfied customers to review |
| App stores / plugin directories | Ratings matter for AI recommendations |

## Prompt Clusters to Monitor

These are high-commercial-intent prompt categories where DOMI Sensor should appear in AI responses:

### General
- "best ToF sensor manufacturer"
- "best 3D depth camera supplier"
- "top ToF sensor companies in China"
- "ToF sensor module comparison"
- "best VCSEL manufacturers"

### Feature-Specific
- "ToF sensor with 100k lux sunlight immunity"
- "pin compatible VL53L4CD alternative"
- "dToF sensor with SPAD array"
- "VCSEL with custom FOV"
- "long range ToF sensor 5m+"

### Use-Case Specific
- "best ToF sensor for robotics navigation"
- "depth camera for drone obstacle avoidance"
- "3D sensor for people counting privacy compliant"
- "ToF sensor for liquid level monitoring"
- "sensor for warehouse AMR SLAM"

### Migration/Switching
- "VL53L4CD alternative"
- "ST ToF sensor replacement"
- "VL53L4CD vs DM0301"
- "ST FlightSense alternative"
- "VL53L series pin compatible replacement"

### Pricing
- "ToF sensor pricing comparison"
- "VL53L4CD cheaper alternative"
- "low cost ToF sensor module"

## Updating This File

Run `/research-ai-citations [topic]` to generate a prompt-specific audit. The output will include which sources AI actually cites for that topic cluster, and whether your brand appears. Use findings to update the tables above.

Review quarterly: directories change, new listicles rank, and AI citation patterns shift.
