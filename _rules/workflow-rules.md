# Workflow Rules — iCLIMA AIR

## Rule 0 — How Claude Works in This Vault

**Never dump full copy in a response. Follow this sequence every time, no exceptions.**

---

## Rule 1 — Session Start Protocol

At the start of every session, read these files in this order. Nothing else until needed.

1. `CLAUDE.md` — routing only
2. `_rules/workflow-rules.md` — this file
3. `4. Brand Assets/client-data.md` — all verified product specs and client facts
4. `4. Brand Assets/writer-profile.md` — copywriting system, objections, voice rules
5. The specific page being worked on — nothing else

Do NOT read seo-rules, copywriting-rules, or solution-page-template unless the task requires them. Read on demand only.

---

## Rule 2 — Page Writing Workflow

Follow this sequence for every page. No steps skipped. No steps reordered.

### Step 1 — Build the outline

Before writing anything, read `_rules/reusable-sections.md` and build the outline table.

**Buyer Journey — every page must answer these 7 questions in this order:**
1. What does iCLIMA AIR offer that is relevant to me?
2. Is this built for buyers like me — my volume, my market, my product type?
3. What are the specs — BTU, capacity, certifications, lead time?
4. What is the process — how do I order, what is the MOQ?
5. What could go wrong — and how does iCLIMA prevent it?
6. Why iCLIMA over another manufacturer?
7. What is my next step?

Map each section in the outline to the question it answers. No question can be skipped.
Present the outline and wait for approval. Do not write copy until the outline is confirmed.

**Outline format:**
```
PAGE: [page name]
PRIMARY KEYWORD: [exact phrase]
SECONDARY KEYWORDS: [list]

| # | Section | Variant | Keyword slot | Notes |
|---|---|---|---|---|
| 1 | Hero | HERO-B | H1: primary keyword | |
| 2 | Trust Bar | [STATIC: trust-bar] | — | |
| 3 | Why iCLIMA | [STATIC: why-iclima] | Secondary keyword | |
| 4 | Product Range | PROD-B | BTU specs | |
| 5 | Applications | APP-A | Cross-links | |
| 6 | FAQ | FAQ-A | Long-tail keywords | |
| 7 | CTA | [STATIC: primary-cta] | Primary keyword | |
| 8 | Footer CTA | [STATIC: footer-cta] | — | |

Meta Title: [under 60 chars]
Meta Description: [under 155 chars]

Confirm or revise before I write.
```

### Step 2 — Write the full page

After the outline is approved:
- Write all sections in one response
- Run Tier 1 checks on each section as it is written (internal — not shown unless a failure is found)
- Static sections are referenced as `[STATIC: name]` — not rewritten
- If a Tier 1 check fails on any section, fix it before including it in the output

### Step 3 — Run Pass A → B → N → D → C

After the full page is written, run all five passes in sequence.
Present the final output only — do not split across responses or show intermediate drafts.

### Step 4 — Save and update status

Save the page to the correct file path.
Update the `status:` header to `REVIEW`.
List any `[DATA NEEDED]` items flagged during writing.

---

## Rule 3 — Response Format Rules

- **Never show full page copy in the response.** Write directly to the file. Show the user a short summary only.
- **Summary format after writing a page:**
  - File path saved to
  - Sections written (count + names only)
  - Any decisions made
  - Next step
- **Never present full copy and ask the user to choose from it.** Choices happen at the section list stage only.
- **Pass A + B + N + D + C run internally** — output only the pass/fail scores, not the full annotated list.
- **Keep every response under 150 words.** If longer, something is wrong.
- **Lead with the file path and status.** Explanation after, one line max per point.

---

## Rule 4 — Tier 1 Quality Checks (run after every section)

Run all five checks before presenting a section to the user.

**Check 1 — Banned phrase scan**
Zero tolerance. If found: remove and rewrite the sentence with a verified number or outcome.

Banned: cutting-edge · state-of-the-art · world-class · innovative · revolutionary · seamless · robust · leverage · elevate · empower · streamline · reliable (alone) · durable (alone) · versatile · comprehensive · holistic · end-to-end · tailor-made · In today's world · Look no further · Our team of experts · Years of experience (without a number) · Peace of mind · Don't hesitate · We are proud to · We are committed to · Learn more · Click here · Find out more

**Check 2 — Claims verification**
Every number traces to `4. Brand Assets/writer-profile.md`. If it is not there, remove it.
No project references, no client names, no award claims unless confirmed.

Specificity ladder — every claim must reach Level 3:
- Level 1 (fails): "Large factory"
- Level 2 (fails): "Very large factory"
- Level 3 (passes): "30,000 sqm factory in China"
- Level 4 (target): "30,000 sqm factory — the production floor of a manufacturer running 3,000,000 units per year"

**Check 3 — Readability**
- No sentence over 20 words
- Active voice only
- Technical terms allowed — B2B buyers know AC. Do not over-explain.

**Check 4 — Benefit-first**
Every sentence opens with what the buyer's business gains. Product features support — never lead.

**Check 5 — CTA specificity**
Substitution test: replace CTA with "Click here." If meaning does not change, rewrite.
Format: [Action verb] + [specific thing the buyer gets]

---

## Rule 5 — Five-Pass System (run after full page compile)

### Pass A — Full-page audit
Score 6 dimensions. Produce annotated failure list.
Dimensions: Clarity · Specificity · Human Voice · B2B Fit · Benefit-First · Originality

Scoring: 0 failures = 10/10 · 1 = 9/10 · 2–3 = 7–8/10 · 4–6 = 5–6/10 · 7+ = below 5/10

Output format:
```
PASS A — [Page name]
Clarity: X/10 — [note]
Specificity: X/10 — [note]
Human Voice: X/10 — [note]
B2B Fit: X/10 — [note]
Benefit-First: X/10 — [note]
Originality: X/10 — [note]
Overall: X/10
Failure list:
- [Section]: [sentence] — [check failed] — [fix instruction]
```

### Pass B — Surgical rewrite
Fix only what failed in Pass A. Nothing else.
Eight rules: sentence start variation · number grounding · 20-word limit · active voice · one idea per sentence · sentence rhythm · buyer language · no urgency language.

Output format:
```
PASS B — [Page name]
Items fixed: [count]
Sections touched: [list]
Data needed from client: [list if any]
```

### Pass N — NLP & Semantic Coverage

Run after Pass B. Checks that the page covers the full semantic landscape a top-ranking AC page contains. Add missing terms naturally — never as a list, never forced.

**Five checks — pass or fail:**

| Check | Pass condition |
|---|---|
| Semantic term coverage | Required AC terms present in body copy (see list below) |
| Keyword variant presence | Primary keyword + at least 2 natural variants in different sections |
| Question intent coverage | Page answers one Who, one How, one What, one Why a buyer would search |
| Subtopic completeness | Covers: product specs, BTU sizing, energy efficiency, installation context, warranty, cost signals |
| Entity density | Brand name (iCLIMA AIR), product category, location context, certification — all named explicitly |

**Required semantic terms — AC pages:**
BTU · SEER rating · EER · inverter compressor · split system · refrigerant · cooling capacity · heat pump · thermostat · air handler · condenser · evaporator · energy efficiency · noise level (dB) · installation

Any check that fails: add the missing element, re-run before moving to Pass D.

Output format:
```
PASS N — [Page name]
Semantic terms: pass/fail — [missing if any]
Keyword variants: pass/fail — [variants used]
Question intent: pass/fail — [gaps if any]
Subtopics: pass/fail — [missing if any]
Entity density: pass/fail — [missing entities if any]
```

---

### Pass D — GEO & E-E-A-T Check

Run after Pass N. Six binary checks — any fail means fix before Pass C.

| Check | Pass condition |
|---|---|
| AI-quotable paragraph | Present in opening section. Self-contained. Contains brand name, product category, one spec, one differentiator. |
| FAQ coverage | All 6 required topics answered. Each answer 3+ sentences. Each answer spec-anchored. |
| Comparison signal | One section or FAQ directly compares iCLIMA AIR to a generic alternative — spec-to-spec, no vague claims. |
| Entity clarity block | Brand name, product category, primary use case, key differentiator — all within first 100 words. |
| Expertise signals | Correct AC terms used. Each term explained inline on first use. At least one spec with "why it matters" bridge. |
| Authority signals | At least 2 verified authority statements from `writer-profile.md` present. No unverified claims. |

**Required FAQ topics — every product/solution page:**
| Topic | Example question |
|---|---|
| Sizing / capacity | "What BTU capacity do I need for my space?" |
| Energy efficiency | "What SEER rating does iCLIMA AIR offer?" |
| Installation | "How long does installation take?" |
| Warranty | "What warranty does iCLIMA AIR provide?" |
| Cost / pricing | "How much does a wall-mount split AC cost?" |
| Comparison | "How does iCLIMA AIR compare to [competitor type]?" |

**AI-quotable paragraph format:**
```
[Brand] [product] [specific capability] — [key spec] — [use case] — [differentiator].
```

Output format:
```
PASS D — [Page name]
AI-quotable paragraph: pass/fail
FAQ coverage: pass/fail — [missing topics if any]
Comparison signal: pass/fail
Entity clarity block: pass/fail
Expertise signals: pass/fail
Authority signals: pass/fail — [statements used]
```

---

### Pass C — Conversion review
Six tests: 3-second headline · first 10 words · objection coverage · CTA journey · differentiation · read-aloud
AI-written score target: 15% or below.

Output format:
```
PASS C — [Page name]
3-second headline: pass/fail — [note]
First 10 words: pass/fail — [note]
Objection coverage: pass/fail — [uncovered if any]
CTA journey: pass/fail — [note]
Differentiation: pass/fail — [differentiators present]
Read-aloud: pass/fail — [flagged sentences]
AI-written score: X%
Page status: READY / NEEDS WORK
```

---

## Rule 6 — Page File Format

Every copy file follows this exact structure:

```markdown
---
status: DRAFT | REVIEW | READY
last-updated: YYYY-MM-DD
primary-keyword: [exact phrase]
---

# [Page Title]

## SEO
- **Meta Title:** [under 60 chars]
- **Meta Description:** [under 155 chars]
- **Primary Keyword:** [exact phrase]
- **Secondary Keywords:** [list]

## Internal Links
- Links to: [[page]] (anchor: [anchor text])
- Links to: [[page]] (anchor: [anchor text])
- Linked from: [[page]]

## Sections
[Content sections in order]

## Developer Notes
[Image names, component variants, build instructions]

## Quality Log
- Pass A: [score] — [date]
- Pass B: [date]
- Pass C: [AI score]% — [date]
```

---

## Rule 7 — Single Source of Truth

Facts live in ONE place. Pages embed or reference — they never duplicate.

| Fact type | Owner file |
|---|---|
| Factory facts, certifications, capacity, lead time | `4. Brand Assets/writer-profile.md` |
| Brand voice, tone, CTAs | `4. Brand Assets/brand-voice.md` |
| Company history, product range | `4. Brand Assets/company-intro.md` |
| Keywords, cross-links | `_rules/seo-rules.md` |

**Rule:** If a fact appears in a copy page, it was sourced from the owner file. If the owner file changes, the copy page must be updated.

---

## Rule 8 — Sync Protocol

When the user says "update [fact/information]":

1. Update the owner file first
2. State exactly what changed and what the old value was
3. List every copy page that contains that fact — these need review
4. Update each affected page in the same session before closing

**Format when flagging affected pages:**
```
SYNC REQUIRED
Changed: [what changed] in [owner file]
Old value: [X]
New value: [Y]
Pages to update: [list with file paths]
```

---

## Rule 9 — Obsidian Link Protocol

Every copy page must declare its links at the top in the Internal Links section.
Use `[[wikilink]]` format throughout — never plain text URLs.

Cross-link map is enforced from `_rules/seo-rules.md`.
Anchor text must be the exact primary keyword of the destination page.

When a new page is added:
1. Add `[[link]]` to its parent page
2. Add it to the cross-link section in `_rules/seo-rules.md`
3. Add it to `CLAUDE.md` routing

---

## Rule 10 — What Improves This Workflow Further

Run these habits every session:

- **Read on demand** — only load files the current task actually needs
- **One page per session** — finish a page completely before starting another
- **Status header first** — update `status:` in the file header before closing
- **Sync before closing** — if any fact was discussed but not yet written, write it before the session ends
- **Never write placeholder copy** — if data is missing, write `[DATA NEEDED: X]` and stop
