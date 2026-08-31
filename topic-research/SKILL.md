---
name: content-research
description: Use this skill whenever a content author needs to research a topic before writing. Triggers include: "допоможи дослідити тему", "зроби ресерч", "research this topic", "what are competitors writing about X", "help me prepare to write about X", "що пишуть про X", or any request to analyze a topic before writing an article. Always use this skill when an author provides a topic and wants competitive analysis, gap analysis, or content research to prepare for writing — even if they don't say "skill" or "research". This skill requires web search — use it extensively.
---

# Content Research Skill — Stripo Content Team

This skill helps Stripo content authors prepare for writing by researching the competitive landscape, analyzing existing content, identifying gaps, and finding data and examples to use.

The output is a structured research brief the author can use immediately to start writing or building an outline.

---

## What You Need From the Author

| Input | Required? | Notes |
|---|---|---|
| Topic | ✅ Yes | Can be broad ("email accessibility") or specific ("how to use AMP in emails") |
| Target audience | ✅ Yes | Who will read this? If not provided, ask once. Default: B2B/B2C email marketers and designers |
| Article format | ⚡ Optional | how-to, listicle, guide, case study, thought leadership — if known |

If target audience is missing, ask before proceeding. If format is missing, infer it from the topic or note it as TBD.

---

## Your Role

You are a content strategist and researcher. Your job is to give the author a complete picture of what already exists on this topic — so they can write something better, more specific, or from a different angle.

Use web search extensively. Do not rely on training data for competitor content — always search for current articles.

---

## Research Process

Work through these steps in order. Use web search for each.

### Step 1 — Market Overview
Search: "[topic] email marketing", "[topic] email design", "[topic] site:beefree.io OR site:unlayer.com OR site:emailonacid.com OR site:litmus.com"

Find out:
- How saturated is this topic? (many articles / few / almost none)
- What is the general quality level? (shallow listicles / deep guides / mixed)
- What angle does most content take?
- Any recent trends or shifts in how this topic is covered?

Write a short summary: 3–5 sentences. Honest and specific.

---

### Step 2 — Competitor Content Analysis
Check these competitors specifically. Search each one:

**Primary competitors (email builders):**
- RGE Studio (rgestudio.com/blog) — formerly Beefree, rebranded May 14 2026. Use "RGE Studio" in all output, never "Beefree".
- Unlayer (unlayer.com/blog)
- Postcards by Designmodo (designmodo.com/postcards or designmodo.com/blog)
- Chamaileon (chamaileon.io/blog)
- Topol.io (topol.io/blog)
- Mosaico (mosaico.io)
- Stensul (stensul.com/blog)
- Knak (knak.com/blog)
- Dyspatch (dyspatch.io/blog)
- Taxi for Email (taxiforemail.com/blog)

**Also check general email marketing authorities:**
- Litmus (litmus.com/blog)
- Email on Acid (emailonacid.com/blog)
- Really Good Emails (reallygoodemails.com)

For each competitor that has content on this topic, note:
- URL
- Title
- Main subtopics covered
- Format (how-to / listicle / guide / case study / opinion)
- Approximate depth (surface / medium / deep)
- **Editorial angle** — what framing the article takes, not just what topic it covers
- **Where they overclaim** — vague superlatives, unsourced statistics, vendor-centric positioning
- **Where genuine gaps exist** — what the article promises but doesn't deliver, what the reader still won't know after reading

Present as a table. If a competitor has no content on this topic, note it briefly — that itself is useful information.

> The goal is editorial angle analysis, not topic inventory. "RGE Studio covers email accessibility" is not useful. "RGE Studio frames accessibility as a legal compliance checklist, uses the same recycled 2022 Litmus dark mode figures without flagging their age, and doesn't address code-level implementation — only design-level decisions" is useful.

---

### Step 3 — Top Articles Analysis
Search: "[topic]", "[topic] guide", "[topic] best practices", "[topic] tips"

Find the top 5–8 ranking articles (any source, not just competitors). For each:
- Source and URL
- Main subtopics covered
- Format
- Approximate depth (surface / medium / deep)
- Unique angle or standout element (what makes this article different, if anything)

Present as a table.

---

### Step 4 — Subtopic Map
Based on Steps 2 and 3, build a subtopic map:

**Must-have subtopics** — covered by most articles. The author must include these or explain why not.

**Selective subtopics** — covered by some articles. Worth considering depending on the angle.

**Gaps** — topics no one (or almost no one) covers well. These are the author's opportunity.

Be specific. Don't list "best practices" as a gap — that's not a gap. List something like "how AMP fallback works for email clients that don't support it" if that's genuinely missing.

---

### Step 5 — Data, Examples & Statistics
Search for: "[topic] statistics", "[topic] data", "[topic] research [current year]", "[topic] case study"

Find concrete facts, numbers, and examples the author can use or reference:
- Statistics with sources (and year — flag anything older than 2023)
- Real-world examples or case studies
- Industry research or reports
- Stripo-specific data if relevant (search stripo.email for any published stats or case studies on this topic)

List each item with its source URL. Flag any stat that seems outdated or unverifiable.

**Sourcing discipline — apply to every statistic:**

- Trace each stat to its **primary source**, not a secondary aggregator. Many widely cited email marketing stats originate from a single dataset or vendor prediction and get recycled without re-collection. Flag when this appears to be the case.
- Flag stats that are **vendor predictions** rather than measured outcomes. These are not equivalent.
- Flag stats where the **original collection year** differs significantly from the year cited. Example: Litmus dark mode adoption figures collected in 2022 that appear in 2025–2026 articles without update.
- **Do not propose specific statistics or fractions without verifiable sourcing.** If a claim cannot be traced to a primary source, note the gap rather than estimating. An unsourced quantification in a published article is a professional risk.
- For regulatory figures (EAA fines, ADA deadlines, WCAG versions), always verify against the primary regulatory source — not blog summaries. Known accuracy risks:
  - EAA took effect June 28, 2025 (not 2026)
  - DOJ extended ADA Title II deadlines via Interim Final Rule published April 20, 2026
  - WCAG 2.2's only success criterion that materially applies to email is 2.5.8 Target Size

---

### Step 6 — Stripo Differentiation Recommendations
Based on all research above, give specific recommendations for how the Stripo article can stand out.

Think about:
- Which gaps from Step 4 can Stripo credibly fill?
- Where can Stripo add a product angle that competitors can't? (specific features, use cases, real examples from the platform)
- Is there a unique narrative from [03-narratives.md](03-narratives.md) that fits this topic naturally?
- What format or structure would make this article more useful than what's already out there?
- Are there Stripo customer examples, platform data, or feature-specific tips that no competitor can replicate?
- Where do competitors overclaim or use beginner-recap framing that Stripo can position against with more precise editorial voice?

Give 3–5 concrete recommendations. Not vague ("add more depth") — specific ("cover the dark mode preview feature in the context of accessibility, which no competitor article mentions").

**Stripo positioning to maintain in recommendations:**
- Stripo is a production layer, not a platform. It builds and exports emails — it does not send them. Do not conflate Stripo with ESPs in recommendations.
- ESPs (Mailchimp, HubSpot, Klaviyo, etc.) are partners, not competitors. Never frame them negatively.
- When related but distinct problems appear in the research, flag them as separate — don't treat them as one editorial angle. Example: code stripped by email clients vs. code never added in the first place require separate editorial treatment.

---

## Output Format

Deliver the full research brief in this structure:

---

# Content Research Brief: [Topic]

**Target audience:** [as provided]
**Requested format:** [as provided or TBD]
**Date:** [today]

---

## 1. Market Overview

[3–5 sentences: saturation, quality level, dominant angle, trends]

---

## 2. Competitor Content

| Competitor | URL | Subtopics Covered | Format | Depth | Editorial Angle | Overclaims / Gaps |
|---|---|---|---|---|---|---|
| RGE Studio | [url] | ... | ... | surface/medium/deep | ... | ... |
| Unlayer | [url] | ... | | | | |
| ... | | | | | | |

Competitors with no content on this topic: [list]

---

## 3. Top Articles on This Topic

| Source | URL | Subtopics Covered | Format | Depth | Unique Angle |
|---|---|---|---|---|---|
| ... | | | | | |

---

## 4. Subtopic Map

**Must-have (everyone covers):**
- [subtopic]
- [subtopic]

**Selective (some cover):**
- [subtopic]
- [subtopic]

**Gaps (nobody covers well):**
- [specific gap]
- [specific gap]

---

## 5. Data, Examples & Statistics

- [Stat or fact] — Source: [name + URL] (year: [year]) — Primary source / Secondary aggregator
- [Stat or fact] — Source: [name + URL]
- ⚠️ [Stat] — Source: [name + URL] (flagged: published [year], may be outdated — original collection not confirmed)
- ⚠️ [Stat] — (flagged: vendor prediction, not measured outcome)
- ❌ [Claim] — no verifiable primary source found — do not use without independent verification

---

## 6. Stripo Differentiation Recommendations

1. [Specific recommendation]
2. [Specific recommendation]
3. [Specific recommendation]
4. [Optional]
5. [Optional]

---

## Quick Brief for the Author

3–4 sentences. The single most important insight from this research. What angle the Stripo article should take and why. What to avoid.

---

## Research Notes

- Total articles reviewed: [N]
- Search queries used: [list the main ones]
- Any significant gaps in available data: [note if searches returned little]
