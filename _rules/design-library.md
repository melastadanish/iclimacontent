# Design Library — iCLIMA AIR
## Section Components & Layout Variants

> Before writing any section, find its variant here.
> Copy the variant code into the page outline.
> Write copy to fit the defined slots exactly.

---

## HOW TO USE

1. Open this file when building a page outline
2. Find the section type needed
3. Pick the variant that fits the page type
4. In the outline table, write: `[VARIANT-CODE]`
5. Write copy to fill only the defined slots — no extras

---

## HERO SECTIONS

### HERO-A — Homepage Hero
**Use for:** Homepage only
**Layout:** Full-width, centered content, background image or gradient

```
Eyebrow         3–4 words · ALL CAPS · category label
H1              6–10 words · primary keyword · outcome-led
Subtext         20–25 words · one sentence · who we supply + proof number
CTA Primary     [Action verb] + [what buyer gets] · max 5 words
CTA Secondary   WhatsApp CTA · max 5 words
Trust Strip     4 items: capacity · lead time · MOQ · certifications
```

**Example slots:**
```
Eyebrow:      AC MANUFACTURER · CHINA
H1:           Air Conditioner Manufacturer for B2B Projects
Subtext:      Factory-direct supply from a 30,000 sqm facility — 3,000,000 units per year, 15-day lead time.
CTA Primary:  Request a Project Quote
CTA Secondary: Contact Us on WhatsApp
Trust Strip:  3M Units/Year | 15-Day Lead Time | Low MOQ | CB · CE · SASO · INMETRO
```

---

### HERO-B — Product Page Hero
**Use for:** Wall Mount · Window AC · Cassette · Ducted · Ceiling Floor · Light Commercial
**Layout:** Two-column — copy left, product image right

```
Eyebrow         3–4 words · ALL CAPS · product category
H1              6–10 words · primary keyword · exact match
Subtext         15–20 words · primary use case + buyer type
Spec Strip      3–4 specs inline: BTU range · refrigerant · compressor · certifications
CTA             1 only: Request a Quote / Download Spec Sheet
```

**Example slots:**
```
Eyebrow:     WALL MOUNT SPLIT AC
H1:          Wall Mount AC Manufacturer for B2B Supply
Subtext:     9,000–24,000 BTU range — built for housing projects, hotels, and bulk distributor orders.
Spec Strip:  9,000–24,000 BTU · R32 / R410a · GMCC · Sanyo · Highly · CE · CB Certified
CTA:         Request a Project Quote
```

---

### HERO-C — Solution Page Hero
**Use for:** All 9 solution pages
**Layout:** Full-width, background image of the sector, overlay text centered

```
Eyebrow         3–4 words · ALL CAPS · sector label
H1              6–10 words · primary keyword · sector + AC supply
Subtext         20 words max · project scale + product fit
CTA             1 only: Request a Project Quote
```

**Example slots:**
```
Eyebrow:    HOTEL AIR CONDITIONING
H1:         Hotel Air Conditioning Supplier for Project Orders
Subtext:    Cassette, ceiling floor, and wall mount AC — supplied direct from factory for hotel projects at any scale.
CTA:        Request a Project Quote
```

---

## PROOF / STATS SECTIONS

### STATS-A — Four-Stat Trust Bar
**Use for:** Homepage · All product pages · All solution pages (below hero)
**Layout:** Horizontal strip, 4 columns, icon + number + label

```
Stat 1    [Number] · [Label] · [one-line context]
Stat 2    [Number] · [Label] · [one-line context]
Stat 3    [Number] · [Label] · [one-line context]
Stat 4    [Number] · [Label] · [one-line context]
```

**Standard iCLIMA stats (use these — do not vary):**
```
Stat 1:   3,000,000 · Units Per Year · Production capacity from a single factory
Stat 2:   15 Days · Lead Time · From order confirmation to production-ready
Stat 3:   15+ Years · Manufacturing · Founded 2011, Zhongshan Guangdong
Stat 4:   Low MOQ · Minimum Order · Entry orders accepted
```

> NOTE: This is also available as [STATIC: trust-bar] — reference the static section instead of rewriting.

---

### STATS-B — Certification Strip
**Use for:** Product pages · Solution pages where market compliance is relevant
**Layout:** Horizontal strip, certification logos + labels

```
CB · CE · SASO · INMETRO
One-line subtext: Pre-certified for your target market — no delays, no re-testing costs.
```

---

## FEATURE / WHY CHOOSE SECTIONS

### FEAT-A — Three-Column Card Grid
**Use for:** "Why iCLIMA" sections on product pages and homepage
**Layout:** 3 cards in a row, icon + heading + body

```
Section Eyebrow    2–3 words · ALL CAPS
Section H2         5–8 words · outcome-led
Card (×3):
  Heading          3–5 words · benefit label
  Body             2 sentences max · outcome + proof number
```

**Slot counts:** 3 cards. Each card: heading (4 words max) + body (30 words max).

---

### FEAT-B — Two-Column Image + Copy
**Use for:** Technology or process sections, OEM/ODM explanation
**Layout:** Image one side, copy other side. Alternate left/right per section.

```
Eyebrow       2–3 words · ALL CAPS
H2            5–8 words · outcome-led
Body          3 paragraphs max · 2 sentences each
CTA           1 optional
```

---

### FEAT-C — Horizontal Icon List
**Use for:** Quick-feature lists, certification lists, market availability
**Layout:** 4–6 items in a row, icon + short label + one-line description

```
Item (×4–6):
  Icon label    2–3 words
  Description   1 sentence · max 15 words
```

---

## PRODUCT RANGE SECTIONS

### PROD-A — Product Card Grid
**Use for:** Homepage product overview · Light Commercial parent page
**Layout:** 3-column card grid

```
Section Eyebrow    ALL CAPS
Section H2         5–8 words
Card (×3 or more):
  Product image
  Product name     3–5 words
  Positioning      1 sentence · what makes this the right choice
  BTU range        inline spec
  CTA              "View [Product Name]" or "Request a Quote"
```

---

### PROD-B — Product Spec Table
**Use for:** Individual product pages — below hero
**Layout:** Full-width table or two-column spec list

```
Model name
BTU range
Cooling capacity (kW)
Heating capacity (kW)
Refrigerant
Compressor brand
Energy rating
Certifications
Operating temperature range
```

> Pull spec data from company-intro.md only. Do not estimate.

---

## APPLICATION / SOLUTION LINK SECTIONS

### APP-A — Sector Card Grid
**Use for:** Product pages — "Where is this used?" section
**Layout:** 3-column card grid, sector image + name + one-line + link

```
Section Eyebrow    ALL CAPS
Section H2         5–8 words · "Built for [X] and [Y] projects"
Card (×3–6):
  Sector name      2–3 words
  One-line         1 sentence · what this product does in this sector
  Link             [[solution-page]] · anchor = solution page primary keyword
```

---

### APP-B — Two-Column Sector List
**Use for:** Solution pages — related products section
**Layout:** Two columns, product name + one-line description + link

```
Section H2         5–8 words · "Recommended Products for [Sector]"
Item (×2–4):
  Product name
  One-line         why this product fits this sector
  Link             [[product-page]] · anchor = product page primary keyword
```

---

## FAQ SECTIONS

### FAQ-A — Standard Accordion
**Use for:** Product pages · Solution pages
**Layout:** Full-width, expandable rows

```
Section H2         "Common Questions from [Buyer Type]"
Question (×4–6):   Written as the buyer would ask it — plain language
Answer:            PAS format — Problem named, proof number given, outcome stated
                   Max 3 sentences per answer
```

**B2B standard questions (use as starting point):**
1. What is the minimum order quantity?
2. What is the lead time from order to delivery?
3. Do you offer OEM and ODM services?
4. Which certifications do your products carry?
5. What refrigerant do your units use?
6. Can I order a sample before placing a bulk order?

---

## OEM / PROJECT SECTIONS

### OEM-A — OEM/ODM Explainer
**Use for:** Homepage · Light Commercial page · wherever OEM is a primary CTA
**Layout:** Two-column or full-width, 3-step process

```
Section Eyebrow    ALL CAPS · "OEM & ODM"
Section H2         5–8 words · outcome for the importer/distributor
Step (×3):
  Step number
  Step label       3–4 words
  Description      2 sentences · what happens at this step
CTA                "Start Your OEM Enquiry"
```

---

## CTA SECTIONS

### CTA-A — Primary Quote CTA
> Also available as [STATIC: primary-cta] — use the static version on most pages.
**Layout:** Centered, colored background

```
H2          5–8 words · project-specific outcome
Subtext     15 words max · reinforce lead time or MOQ
CTA Button  "Request a Project Quote"
```

---

### CTA-B — WhatsApp CTA
> Also available as [STATIC: whatsapp-cta]
**Layout:** Banner with WhatsApp icon, one line + button

```
Line        "Speak to our sales team directly — available on WhatsApp"
CTA Button  "Contact Us on WhatsApp"
```

---

## CROSS-LINK SECTIONS

### XLINK-A — Related Solutions
**Use for:** Bottom of all product pages
**Layout:** Card row, 3–5 solution page links

```
Section H2    "Industries We Supply"
Cards:        Sector name · one line · [[link]]
```

### XLINK-B — Related Products
**Use for:** Bottom of all solution pages
**Layout:** Card row, 2–4 product page links

```
Section H2    "Recommended Products for This Sector"
Cards:        Product name · one line · [[link]]
```

---

## VARIANT QUICK REFERENCE

| Code | Section | Use on |
|---|---|---|
| HERO-A | Homepage hero | Homepage |
| HERO-B | Product page hero | All product pages |
| HERO-C | Solution page hero | All 9 solution pages |
| STATS-A | Four-stat trust bar | All pages |
| STATS-B | Certification strip | Product + solution pages |
| FEAT-A | 3-col card grid | Why iCLIMA sections |
| FEAT-B | 2-col image + copy | OEM, technology sections |
| FEAT-C | Horizontal icon list | Quick features |
| PROD-A | Product card grid | Homepage, Light Commercial |
| PROD-B | Spec table | Individual product pages |
| APP-A | Sector card grid | Product pages |
| APP-B | 2-col product list | Solution pages |
| FAQ-A | Accordion FAQ | Product + solution pages |
| OEM-A | OEM/ODM explainer | Homepage, Light Commercial |
| CTA-A | Primary quote CTA | All pages |
| CTA-B | WhatsApp CTA | All pages |
| XLINK-A | Related solutions | Bottom of product pages |
| XLINK-B | Related products | Bottom of solution pages |
