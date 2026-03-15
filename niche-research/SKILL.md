---
name: niche-research
description: Deep market research and niche analysis for any industry or vertical. Use this skill whenever the user wants to research a market, understand an industry, find pain points in a niche, discover what software to build for a specific audience, do competitive analysis, or explore business opportunities. Trigger on phrases like "research this niche", "tell me about the X industry", "what do Y professionals struggle with", "find me a SaaS idea", "analyze this market", or any request to deeply understand an industry, profession, or market segment - even if they don't use the word "niche" or "research".
---

# Niche Research: Deep Market Intelligence

You are conducting deep market research to turn a niche or industry into a complete intelligence briefing. The goal is to make the user an instant expert — someone who understands the market's real problems, speaks the language of the people in it, and can identify the right software product to build and sell to them.

This is not surface-level googling. You're pulling from real conversations, real complaints, real communities. The output should feel like the user spent 3 months embedded in the industry.

## Research Process

### Phase 1: Landscape Scan

Start broad. Get the lay of the land before going deep.

1. **Industry overview search** — Search for the industry/niche + "market size", "trends", "challenges". Understand the basic landscape: who are the key players, what's the market structure, how big is it, what's changing.

2. **Find their communities** — Search for where these people actually talk to each other:
   - Reddit: `site:reddit.com [niche] OR [profession]` — find the active subreddits
   - Forums: `[niche] forum` or `[profession] community`
   - Facebook groups: `[niche] facebook group`
   - Slack/Discord: `[niche] slack community` or `[niche] discord`
   - Industry associations and events

3. **Find their tools** — Search review sites to understand what software they already use:
   - `site:g2.com [niche] software`
   - `site:capterra.com [niche]`
   - `[niche] software reviews`

### Phase 2: Pain Point Mining

This is where the real value is. Go into the communities and conversations and extract what actually hurts.

4. **Reddit deep dive** — For each relevant subreddit found, search for complaint and frustration patterns:
   - `site:reddit.com r/[subreddit] "frustrated" OR "hate" OR "wish" OR "struggle" OR "pain" OR "annoying"`
   - `site:reddit.com r/[subreddit] "looking for" OR "anyone know" OR "recommendation" OR "alternative to"`
   - `site:reddit.com r/[subreddit] "software" OR "app" OR "tool" OR "system"`

5. **Forum and community mining** — Fetch and analyze the top threads from communities found in Phase 1. Look for:
   - Repeated complaints
   - Workarounds people have built (spreadsheets, manual processes = opportunity)
   - Questions about software that doesn't exist yet
   - Frustrations with existing tools

6. **Review site analysis** — Look at 1-star and 2-star reviews of existing software in the space:
   - `site:g2.com [existing tool] reviews`
   - `[existing tool] complaints OR problems OR "switched from"`
   - What are people consistently unhappy about?

### Phase 3: Language & Culture

Understanding how these people talk is as important as understanding their problems.

7. **Terminology extraction** — From all the content gathered, identify:
   - Industry jargon and acronyms
   - How they describe their own problems (their words, not yours)
   - Common phrases when asking for help
   - How they refer to different roles, tools, and processes

8. **Influencers and events** — Search for:
   - `[niche] conference OR summit OR expo 2026`
   - `[niche] podcast OR youtube OR influencer`
   - `[niche] newsletter OR blog`
   - Who do they listen to? Where do they learn?

### Phase 4: Opportunity Synthesis

Now bring it all together into actionable intelligence.

9. **Gap analysis** — Cross-reference pain points with existing solutions:
   - What problems have no software solution?
   - What existing solutions are universally hated?
   - Where are people using spreadsheets, paper, or manual processes?
   - What's overpriced for what it delivers?

10. **Solution design** — Based on everything gathered, identify the highest-opportunity software product:
    - What it does (core features)
    - Why now (what's changed that makes this viable)
    - Who specifically buys it (job title, company size)
    - How to price it (based on what they currently pay)
    - How to reach them (based on where they hang out)
    - What to call it and how to pitch it (using their language)

## Research Execution Guidelines

- **Run at least 10-15 web searches.** This is deep research, not a quick lookup. Cover Reddit, forums, review sites, industry publications, and events.
- **Fetch and read actual pages** when you find promising threads, reviews, or articles. Don't just rely on search snippets — the real gold is in the comments and replies.
- **Quote real language.** When reporting pain points and terminology, use actual quotes from real people whenever possible. This is what makes the output valuable.
- **Be specific, not generic.** "They struggle with scheduling" is useless. "Dental hygienists consistently complain that most practice management software doesn't let them block time for instrument sterilization between patients, forcing them to use paper sticky notes on the schedule" is gold.
- **Prioritize by frequency.** If 50 people complain about X and 3 complain about Y, lead with X.
- **Use parallel subagents** when available to speed up the research. Phase 1 searches can run in parallel. Phase 2 Reddit and forum dives can run in parallel.

## Output Format

Deliver the research as a structured markdown report saved to a file. Use this template:

```markdown
# Niche Research Report: [Industry/Niche]

## Executive Summary
[2-3 paragraph overview: what this market is, what their biggest problems are, and the #1 software opportunity you've identified]

## Market Landscape
- **Market size**: [estimate with source]
- **Key segments**: [sub-niches within this market]
- **Major trends**: [what's changing right now]
- **Key players**: [dominant companies/tools in the space]

## Where They Hang Out
| Platform | Community | Size/Activity | Notes |
|----------|-----------|---------------|-------|
| Reddit | r/example | 50k members, very active | Main hub for complaints |
| Facebook | Example Group | 12k members | More established pros |
| Forum | example-forum.com | Moderate | Technical discussions |
| Events | ExampleCon 2026 | 5k attendees | Main industry event |
| Podcast | The Example Show | Popular | Trusted voice |

## Pain Points (Ranked by Frequency)

### 1. [Pain Point Name]
**How they describe it:** "[actual quotes from forums/reddit]"
**Current workaround:** [what they do now — spreadsheets, manual process, etc.]
**Existing solutions and why they fail:** [tools that try to solve this and why people hate them]
**Severity:** [High/Medium/Low — how much does this actually cost them in time/money/stress?]

### 2. [Pain Point Name]
[same structure...]

### 3. [Pain Point Name]
[same structure...]

[Continue for top 5-8 pain points]

## Their Language
- **Industry jargon**: [key terms and what they mean]
- **How they describe problems**: [actual phrases they use]
- **How they search for solutions**: [what they type into Google]
- **Emotional triggers**: [what makes them angry, stressed, or excited]

## Competitive Landscape
| Tool | What it does | Pricing | Key complaints | Rating |
|------|-------------|---------|----------------|--------|
| Tool A | Description | $X/mo | "quote from review" | 3.2/5 |
| Tool B | Description | $Y/mo | "quote from review" | 2.8/5 |

## The Opportunity

### What to Build
[Specific product concept — not vague, but a concrete product with a name suggestion, core features, and clear differentiation]

### Core Features (MVP)
1. [Feature] — solves [pain point #X]
2. [Feature] — solves [pain point #Y]
3. [Feature] — solves [pain point #Z]

### Who Buys It
- **Job title**: [specific role]
- **Company size**: [range]
- **Current spend**: [what they pay for existing tools]
- **Decision process**: [who approves the purchase]

### Pricing Strategy
[Recommended pricing based on market research — what competitors charge, what the market will bear]

### Go-to-Market
- **Positioning**: [one-line pitch using their language]
- **Channels**: [based on where they hang out]
- **Content strategy**: [what to write/create to attract them]
- **Quick wins**: [low-effort ways to get first 10 customers]

## Raw Research Notes
[Links to sources, notable threads, key quotes that didn't fit above]
```

## Important Notes

- Save the report as `[niche-name]-niche-research.md` in the current working directory.
- If the niche is very broad (e.g., "healthcare"), ask the user to narrow it down to a specific segment before beginning research. The skill works best with specific verticals (e.g., "dental practices", "independent pharmacies", "HVAC contractors").
- When presenting findings, distinguish between things you found evidence for (with sources) and inferences you're making. Be honest about confidence levels.
- The report should be long and detailed — this is a reference document, not a summary. 2000+ words is normal.
