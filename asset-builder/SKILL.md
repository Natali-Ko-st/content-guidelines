---
name: asset-builder
description: Use this skill whenever a content author has a finished article draft and wants to create a downloadable asset from it. Triggers include: "зроби чекліст до статті", "який асет підходить для цього матеріалу", "допоможи зробити гайд", "що з цієї статті зробити асетом", "create a checklist from this article", "help me make a downloadable asset", "what format works for this article", or any request to extract, structure, or adapt article content into a standalone downloadable asset. Always use this skill when an author provides a draft and asks about a downloadable — even if they don't say "skill".
---

# Asset Builder Skill — Stripo Content Team

This skill helps content authors turn finished article drafts into downloadable assets: checklists, infographics, short guides, templates/frameworks, and cheat sheets.

A downloadable asset is not a PDF copy of the article. It's an extract the reader picks up and uses independently — at work, in a meeting, while building an email. The reader who didn't download the asset should feel nothing is missing from the article. The reader who did should get something the article doesn't provide in that form.

---

## What You Need From the Author

| Input | Required? | Notes |
|---|---|---|
| Article draft or full text | ✅ Yes | The complete draft — not a summary |
| Article topic / working title | ✅ Yes | |
| Target audience | ✅ Yes | Who will read and use the asset |
| Preferred asset format | ⚡ Optional | If they already know — checklist, infographic, guide, template, cheat sheet. If not, the skill recommends. |
| How the asset will be used | ⚡ Optional | e.g. "during email production", "before campaign launch", "as a reference while working in Stripo" |

If the article draft is missing — ask for it. The skill cannot determine what belongs in the asset without reading the source material.

---

## Step 1 — Recommend the Format (if not provided)

Read the article. Then match it to the format table below. If multiple formats could work, recommend one primary and note one alternative.

| Article type | Asset format | Why it works |
|---|---|---|
| How-to with a sequence of steps | Checklist | Reader will perform the steps later, not while reading |
| Preparation for something (campaign launch, season, release) | Checklist | Reused repeatedly, campaign after campaign |
| Comparison, research, data-heavy articles | Infographic | Numbers stick better visually; highly shareable |
| Explanation of a process or dependencies | Infographic / diagram | Complex structure reads faster as a visual |
| Overview articles with a methodology inside | Short guide | The methodology can be detached from the article's context |
| Articles about structure (modules, campaigns, email series) | Template / framework | Reader wants to plug in their own data |
| Terminology and educational materials | Cheat sheet | Needs to stay open during work, not be reread |

**Additional format signals to look for:**
- Article has 7+ actionable steps → checklist
- Article contains 5+ statistics or data points that tell a story → infographic
- Article teaches a reusable process → short guide
- Article describes a structure the reader can replicate → template
- Article defines 10+ terms or parameters → cheat sheet
- Article is long and conceptual with one embedded methodology → short guide (extract the method only)

---

## Step 2 — Identify What Belongs in the Asset

This is the most important step. Read the article and extract only the content that:

**Belongs in the asset:**
- Actionable steps the reader will perform (not just read about)
- Criteria the reader will use to evaluate or decide
- Data points that support a single clear message
- Structures or frameworks the reader will replicate
- Terms or parameters the reader needs to reference while working
- Anything the reader will return to after finishing the article

**Does not belong in the asset:**
- Context and background (why the topic matters, industry history)
- Explanations of concepts that require reading to understand
- Narrative examples and case studies (unless they're a template)
- Stripo product descriptions and CTAs from the article
- Anything that only makes sense in the flow of the article

**Test for every item:** Can this be used without reading the surrounding text? If yes → asset. If no → article only.

---

### The no-duplication rule

The asset must not simply repeat the article in a shorter form. If a reader could reconstruct the asset by skimming the article headings — the asset adds no value.

What the asset offers is a different form of the same content, not the same form with less text:
- The article explains *why* each step matters. The asset gives you the steps without the why.
- The article walks you through a process with context. The asset gives you the process alone, ready to run.
- The article presents data with narrative. The asset surfaces the data in a visual that travels independently.

Before writing, ask: **what does this asset give the reader that the article cannot?** If the answer is only "it's shorter" — the asset isn't ready yet.

---

### Step 2b — Recommend what to add

After identifying what to extract, look for gaps: things that would make the asset more useful but aren't in the article.

**When to add content not from the article:**

Assets often need items that weren't worth including in the article — either because they're too obvious to explain, too brief to justify a paragraph, or too practical for narrative text. These are exactly the items that make an asset valuable.

Look for:
- **Missing steps in a checklist** — the article might cover 8 steps but skip 2 practical ones the reader will actually need (e.g. "Save the file before exporting" is too obvious for an article but belongs in a checklist)
- **Missing parameters in a cheat sheet** — the article covers the main ones, but a working reference needs edge cases too
- **Missing fields in a template** — the article describes a framework but the author didn't include every field the reader will need to fill in
- **Missing examples in a guide** — the article's examples are too narrative; a short guide needs minimal, concrete ones

**How to flag recommendations:**

After producing the asset, add a "What to add" section in the Editor's Note. For each gap:
- Name the missing item specifically
- Explain why it would strengthen the asset
- Note whether the author can fill it from their own knowledge or needs to research it

Example:
> **What to add:** The checklist covers pre-send checks but stops at sending. Adding 3–4 post-send checks (check rendering in the inbox, verify UTM tracking is firing, confirm list unsubscribes processed correctly) would make this reusable for the full send cycle, not just the pre-send moment.

Only recommend additions that are clearly within scope — don't suggest expanding the asset into a different format or topic.

---

## Step 3 — Structure for the Format

Apply the correct structure based on the format selected.

---

### Checklist

**What it is:** A list of things to do or verify, in execution order.

**Structure:**
1. Title — specific, outcome-oriented ("Email checklist before sending", not "About email marketing")
2. One sentence: who uses this and when
3. Groups of 4–8 items, organized by stage or area of responsibility
4. Items — verb-first, imperative, one item = one action, one thing to check
5. Checkboxes
6. Link to source article at the bottom

**Volume:** 15–40 items. Fewer — doesn't justify a separate file. More — won't get used.

**What to extract from the article:**
- Every concrete action step
- Every verification criterion ("check that...", "confirm...", "make sure...")
- Every decision point the reader faces in practice

**Rewrite rules for checklist items:**
- Turn statements into actions: "Subject line matters" → "Check that the subject line is under 50 characters"
- Each item must be completable — the reader must be able to unambiguously check it off
- Order must match the actual work sequence, not the article's narrative order
- No explanations inside items — the checklist assumes the reader knows why

**Common mistakes to avoid:**
- Statement items instead of actions
- Items that can't be closed unambiguously ("Think about accessibility")
- Order that doesn't match real workflow
- Duplicate or overlapping items

---

### Infographic

**What it is:** Data or structure presented visually.

**What to prepare for the designer:**
1. Main message — one phrase that justifies the infographic's existence
2. 5–9 data blocks, each: number/fact + 3–8 word label
3. Connection logic between blocks (sequence, comparison, hierarchy, parts of a whole) — the designer needs this to choose a composition
4. Sources for all numbers
5. Title and subtitle

**Volume:** No more than 9 content blocks. More — falls apart visually.

**What to extract from the article:**
- Statistics and research data
- Comparisons that reveal a contrast or surprise
- Process steps that can be shown as a flow
- Before/after pairs
- Numbers that support the main message

**Rewrite rules for infographic copy:**
- Each data block must contribute to the main message — if it doesn't, cut it
- Labels must be readable in isolation (no "see above" references)
- Numbers without comparison say nothing — add context ("4× faster", "vs. 8 hours manually")
- Main message must be a conclusion, not a description ("Most email teams build templates wrong" not "Email template statistics")

**Common mistakes to avoid:**
- Data without a main message — a set of numbers with no takeaway
- Numbers that don't compare or contrast anything
- Trying to fit the whole article into one infographic

---

### Short Guide

**What it is:** A methodology extracted from the article, formatted so it can be applied without reading the original.

**Structure:**
1. Problem — 2–3 sentences
2. Approach in two words — what this guide proposes
3. Steps: 3–7, each with a name + one-paragraph explanation + example
4. What to watch out for / common mistakes
5. What to do next

**Volume:** 2–5 pages.

**What to extract from the article:**
- The methodology or process at the core of the article
- The steps in their correct sequence
- The examples that illustrate each step (not the narrative ones)
- The "why it fails" content (mistakes section)
- The recommended next action

**What to leave in the article:**
- Background and context
- Industry statistics that support the why
- Extended case studies
- Alternative approaches that aren't part of the recommended method

**Rewrite rules for short guide copy:**
- Each step must be self-contained — understandable without reading the others first
- Examples must be concrete and minimal — one scenario that makes the step clear
- The "what to do next" must be a specific action, not a general direction

**Common mistakes to avoid:**
- Retelling the article with cuts instead of extracting the method
- Steps without examples
- Missing answer to "what do I do next"

---

### Template / Framework

**What it is:** A pre-structured form the reader fills in with their own data.

**Structure:**
1. Instructions at the top: how to use, 3–5 lines
2. Filled example — mandatory, otherwise the structure won't be understood
3. Blank form to fill in
4. Hints in fields (what to write here)

**What to extract from the article:**
- The structure or framework the article describes
- The categories or dimensions the reader needs to think through
- The example from the article (adapted into the template)
- The decision criteria that guide what goes into each field

**Rewrite rules for template copy:**
- Every field must have a hint that tells the reader exactly what format to use
- The filled example must be realistic — not "Your text here" but an actual scenario
- The structure must be flexible enough to adapt to different situations

**Common mistakes to avoid:**
- Blank form without an example
- Structure too rigid to adapt to a real use case
- Fields without explanations

---

### Cheat Sheet

**What it is:** A 1–2 page reference the reader keeps open while working.

**Structure:**
1. Grouping by category
2. Minimal text — term/parameter + short explanation
3. Visual hierarchy is more important than completeness
4. Everything fits on 1–2 pages without scrolling through content

**What to extract from the article:**
- Terms and definitions that the reader needs while working
- Parameters and their values or ranges
- Rules of thumb and quick-reference guidelines
- Decision shortcuts ("if X → do Y")

**What to leave in the article:**
- Extended explanations and rationale
- Examples and case studies
- Historical context

**Rewrite rules for cheat sheet copy:**
- Definitions must be 1 line maximum — if a concept needs more, it doesn't belong on a cheat sheet
- Group by how the reader works, not by how the article is structured
- Use parallel structure within each group

**Common mistakes to avoid:**
- Trying to make a complete reference instead of a curated selection of the most-needed items
- Long explanations

---

## Step 4 — Write the Asset Content

After completing steps 1–3, produce the full asset content. Output it as the final text the author can hand to a designer or paste directly.

**Output format:**
- Lead with a brief recommendation note (2–3 sentences): what format, why, and what you extracted
- Then the full asset content, clearly structured
- End with a short editor's note: what was left out and why

**Writing rules for all asset formats:**

**Brevity over completeness.** An asset is not a summary — it's a selection. Cut everything that isn't directly useful in the moment of use.

**Different rhythm than the article.** Articles build understanding. Assets enable action. The language is shorter, more direct, imperative where possible.

**No context dependency.** Every item in the asset must work without the article. Test each one: can the reader use this without having read the source?

**No Stripo CTAs from the article.** The asset may mention Stripo where directly relevant (e.g. a checklist step that involves using a Stripo feature), but it is not a product promotion piece.

**Parallel structure within each format.** Checklist items all use the same grammatical form. Infographic labels all follow the same pattern. Template fields all have the same type of hint.

**Specific over general.** "Check subject line length" is weaker than "Check that the subject line is under 50 characters." Specificity is what makes the asset usable.

---

## Step 5 — Quality Check Before Delivering

Before delivering the asset content, verify:

- [ ] Every item in the asset can be used without reading the article
- [ ] Nothing in the asset requires context from the article to be understood
- [ ] The article reader who didn't download feels nothing is missing
- [ ] The asset reader gets something the article doesn't provide in this form
- [ ] Checklist items are verb-first, completable, in work sequence
- [ ] Infographic has a single main message and no more than 9 blocks
- [ ] Short guide steps are self-contained and include examples
- [ ] Template has a filled example and field hints
- [ ] Cheat sheet fits within 2 pages and uses minimal text
- [ ] No context-dependent items ("as mentioned above", "see section 3")
- [ ] Parallel structure within sections
- [ ] The asset is not a shorter version of the article — it offers a different form, not less text
- [ ] Gaps are identified and flagged in Editor's Note with specific recommendations

---

## Output Format

```
## Asset Recommendation

**Format:** [Checklist / Infographic / Short guide / Template / Cheat sheet]
**Why:** [1–2 sentences]
**What's extracted:** [2–3 sentences on what from the article goes in and what stays out]
**What this gives the reader that the article doesn't:** [1 sentence]

---

## [Asset Title]

[Full asset content, structured for the chosen format]

---

## Editor's Note

**Left out:** [What was excluded and why]
**What to add:** [Specific items missing from the asset that would make it more useful — with explanation of why and whether the author can fill them from their own knowledge or needs to research]
**Alternative format:** [If another format could also work, note it briefly]
```
