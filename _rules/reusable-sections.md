# Reusable Sections — iCLIMA AIR

Static blocks used across multiple pages. Referenced as `[STATIC: name]` in page outlines.
When a fact changes in `writer-profile.md`, update that block here — then all pages referencing it are current.

---

## RULE — Every Section Must Have a Description

**A bare `[STATIC: tag]` line with nothing else is never acceptable.**

Every section — including sections that contain a static block — must have at least one sentence of page-specific context written above or below the static block reference.

**Format:**

```markdown
## SECTION X — CERTIFICATIONS

iCLIMA AIR holds CE, CB, UL, AHRI, RETIQ, RTCA, GMRK, and ISO 9001 certifications — covering Europe, North America, Latin America, and the Gulf. Certification documentation ships with every container.

[STATIC: certifications]
```

**Rationale:** Static blocks render as UI components. Without surrounding copy, the section has no SEO value, no buyer context, and no narrative continuity. The description sentence(s) must be written for the specific page — not generic filler.

---

## RS-01 — Trust Strip
**Tag:** `[STATIC: trust-strip]`
**Used on:** Every page — directly below the Hero section
**Layout:** 4 horizontal metrics, equal-weight tiles

```
30-Day Lead Time* · 3 Million Units/Year · CE · CB · UL · AHRI Certified · Low MOQ

*10 days from stock
```

**Rules:**
- Lead time asterisk is mandatory — 30 days standard / 10 days from stock
- Certifications shown: CE · CB · UL · AHRI only (full list in RS-03)
- Do not change the order or remove the asterisk note

---

## RS-02 — Why iCLIMA AIR
**Tag:** `[STATIC: why-iclima]`
**Used on:** Product pages · Solution pages · Buyer type pages
**Layout:** 5 benefit cards, no icons required

```
**Italian-Designed. Factory-Built.**
iCLIMA AIR runs its own brand — designed in Italy, manufactured in China.
Distributors get a finished brand, not a private-label commodity.

**<0.1% Defect Rate**
Every unit passes 100% leakage testing before shipment.
30,000 sqm factory running 3 million units per year — built for volume without quality compromise.

**30-Day Lead Time**
Standard orders ship in 30 days. Stock items ship in 10.
7-day rapid sampling for new OEM partners.

**Certified for Your Market**
CE · CB · UL · AHRI · RETIQ · RTCA · GMRK · ISO 9001.
One manufacturer. Certifications covering Europe, North America, Latin America, and the Middle East.

**Low MOQ — Flexible Orders**
No large minimum order commitment required.
Scale from trial order to full container without renegotiating terms.
```

**Rules:**
- Cards must appear in this order
- Do not add a 6th card without user approval
- Numbers must match writer-profile.md exactly

---

## RS-03 — Certifications Block
**Tag:** `[STATIC: certifications]`
**Used on:** Product pages · Market pages · About page · Homepage
**Layout:** 2-column table or horizontal badge strip

```
| Certification | Market Coverage |
|---|---|
| CE | Europe |
| CB | Global baseline |
| UL | North America |
| AHRI | North America |
| RETIQ | Colombia |
| RTCA | Honduras · El Salvador · Central America |
| GMRK | Gulf / Middle East |
| ISO 9001 | Quality management — global |
```

**Rules:**
- Do not mention SASO or INMETRO — removed from client-confirmed list
- Do not mention ETL — not in confirmed list
- Do not say "140+ country certifications" — use "worldwide" or list specific regions
- R410a-related certifications are not mentioned

---

## RS-04 — Primary CTA Block
**Tag:** `[STATIC: primary-cta]`
**Used on:** Mid-page CTA break on every page
**Layout:** Heading + 2 lines + 2 buttons

```
**Ready to Source Direct from the Manufacturer?**
Tell us your product type, target market, and annual volume.
We'll confirm certifications, lead time, and MOQ within 24 hours.

[Get a Quote]  [Contact on WhatsApp]
```

**Rules:**
- "Get a Quote" is always the primary button (left)
- "Contact on WhatsApp" is always secondary (right)
- Do not change the 24-hour response promise — it is a confirmed claim
- Do not add a third CTA button

---

## RS-05 — Footer CTA
**Tag:** `[STATIC: footer-cta]`
**Used on:** Bottom of every page, above the global footer
**Layout:** Full-width strip, single heading + single button

```
**iCLIMA AIR — Air Conditioner Manufacturer for Distributors & Importers**
CE · CB · UL · AHRI · RETIQ · RTCA · GMRK certified · Ships in 30 days

[Request a Quote]
```

**Rules:**
- Heading mirrors the H1 of the homepage — entity consistency for GEO
- Certification strip must match RS-03 (no extras, no omissions)
- Single CTA only — "Request a Quote"

---

## Usage in Page Outlines

When building a page outline (Rule 2, Step 1 of workflow-rules.md), reference static sections like this:

```
| # | Section | Type | Notes |
|---|---|---|---|
| 1 | Hero | VARIABLE | H1: primary keyword |
| 2 | Trust Strip | [STATIC: trust-strip] | No edits |
| 3 | [Page-specific content] | VARIABLE | ... |
| 4 | Why iCLIMA AIR | [STATIC: why-iclima] | No edits |
| 5 | [Page-specific content] | VARIABLE | ... |
| 6 | Certifications | [STATIC: certifications] | No edits |
| 7 | FAQ | VARIABLE | 6 required topics |
| 8 | Mid CTA | [STATIC: primary-cta] | No edits |
| 9 | Footer CTA | [STATIC: footer-cta] | No edits |
```

STATIC sections are not rewritten per page — they are referenced only.
Only update a STATIC section here, not inside individual page files.
