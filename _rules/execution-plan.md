# Execution Plan — iCLIMA AIR

## How to Use
1. Read this file at the start of each session
2. Pick the first unchecked item in the current phase
3. Complete it → check box → update `_rules/progress.md` → commit → push
4. One page per commit. Format: `[WRITE] filename.md — five-pass complete`

## Two Task Types
- **[WRITE]** — Empty or stub file: write full page from scratch, then run passes A→B→N→D→C
- **[REVIEW]** — Existing draft: run all five passes, fix all failures

## Definition of Done Per Page
- [ ] Five passes complete — all failures resolved
- [ ] No banned phrases (per `copywriting-rules.md`)
- [ ] Every number traces to `writer-profile.md`
- [ ] Brand name: "iCLIMA AIR" — not "iClima" or "ICLIMA"
- [ ] Pass log added to file header (Quality Log section)
- [ ] `progress.md` updated to ✅
- [ ] Committed and pushed to `main`

---

## PHASE 0 — SYSTEM FILES (current phase)

### 0A — Templates

> **Build and approve each template before writing any page in that silo.**
> Templates are approved once. All pages in the silo follow them without deviation.

#### Template Formula — how to build each template

A template answers these 5 questions before any copy is written:

**1. Goal**
What buyer decision does this page type serve?
What does the buyer need to believe by the time they reach the CTA?

**2. Buyer Journey (mandatory 7-question sequence)**
Every page must answer these questions in this order:
1. What does iCLIMA AIR offer that is relevant to me?
2. Is this built for buyers like me (my volume, my market, my product type)?
3. What are the specs — BTU, capacity, certifications, lead time?
4. What is the process — how do I order, how long does it take, what is the MOQ?
5. What could go wrong — and how does iCLIMA prevent it?
6. Why iCLIMA over another manufacturer?
7. What is my next step?

**3. Section List**
8–12 sections in order. For each section define:
- Section name and purpose
- STATIC or VARIABLE (STATIC = from reusable-sections.md, unchanged)
- Keyword slot (which keyword goes in this section's heading)
- Word count range
- Required data source (writer-profile.md field name)
- Variant options if applicable (e.g. Hero-A, Hero-B)

**4. Non-Negotiable Rules**
Rules specific to this page type that cannot be skipped or reordered.

**5. Approval Gate**
Present the section list table to the user before writing any copy.
Do not write until the section list is confirmed.

---

#### Templates to Build

- [ ] [WRITE] `_rules/product-page-template.md`
  Goal: convert a product-aware buyer into a quote request
  Silo: covers all 6 product pages
  Sections needed: ~10 (Hero · Trust Strip · AI-quotable block · Specs table · BTU/capacity · Certifications · Applications · Why iCLIMA · FAQ · CTA)

- [ ] [WRITE] `_rules/solution-page-template.md`
  Goal: show a sector buyer that iCLIMA supplies their specific project type at scale
  Silo: covers all 9 solution pages
  Sections needed: ~10 (Hero · Trust Strip · Sector challenge · Recommended products · Project specs · Market coverage · Certifications · Why iCLIMA · FAQ · CTA)

- [ ] [WRITE] `_rules/market-page-template.md`
  Goal: show a buyer in a specific region that iCLIMA holds their local certifications and serves their market
  Silo: covers all 6 market pages
  Sections needed: ~9 (Hero · Certifications for this market · Products available · Lead time · Recommended solutions · Why iCLIMA for this region · FAQ · CTA)

- [ ] [WRITE] `_rules/buyer-type-page-template.md`
  Goal: speak directly to one buyer type (distributor / importer / contractor / developer) and resolve their specific objections
  Silo: covers all 4 buyer type pages
  Sections needed: ~9 (Hero · What we offer this buyer type · OBM option · OEM option · MOQ & lead time · Process · Certifications · FAQ · CTA)

### 0B — Reusable Sections
- [x] ✅ `_rules/reusable-sections.md`

---

## PHASE 1 — CORE PAGES (5)

Writing order: Product Archive first (no template needed — archive page follows homepage pattern)

- [ ] [REVIEW] Homepage `/` — `1.1 Homepage/homepage-copy.md`
  ⏸ Mark READY only after: Solar AC specs · Free Match specs · Alibaba reviews received from client
- [ ] [WRITE] Product Archive `/products/` — `1.2 Product Archive/product-archive-copy.md`
- [ ] [WRITE] Solutions Archive `/solutions/` — `1.3 Solutions Archive/solutions-archive-copy.md`
- [ ] [WRITE] OBM & OEM Services `/oem-odm/` — `1.4 OEM-ODM/oem-odm-copy.md`
- [ ] [WRITE] Contact & Quote `/contact/` — `1.5 Contact/contact-copy.md`

---

## PHASE 2 — PRODUCT PAGES (6)
> Build `product-page-template.md` (Phase 0A) before starting this phase.

- [ ] [WRITE] Inverter Split AC — `2.1 Inverter Split AC/inverter-split-copy.md` ← first, sets template for remaining 4
- [ ] [WRITE] On & Off Split AC — `2.2 On Off Split AC/on-off-split-copy.md`
- [ ] [WRITE] Window AC — `2.5 Window AC/window-ac-copy.md`
- [ ] [WRITE] Duct / Cassette / Ceiling Floor AC — `2.6 Commercial AC/commercial-ac-copy.md`
- [ ] ⏸ [WRITE] Solar AC — `2.3 Solar AC/solar-ac-copy.md` — BLOCKED: awaiting specs from client
- [ ] ⏸ [WRITE] Free Match AC — `2.4 Free Match AC/free-match-copy.md` — BLOCKED: awaiting specs from client

---

## PHASE 3 — SOLUTION PAGES (9)
> Build `solution-page-template.md` (Phase 0A) before starting this phase.

- [ ] [WRITE] Hotels & Hospitality — `3.1 Hotels/hotels-copy.md` ← first, sets template for remaining 8
- [ ] [WRITE] Offices & Commercial — `3.2 Offices/offices-copy.md`
- [ ] [WRITE] Retail & Shopping Centers — `3.3 Retail/retail-copy.md`
- [ ] [WRITE] Schools & Universities — `3.4 Schools/schools-copy.md`
- [ ] [WRITE] Healthcare & Clinics — `3.5 Healthcare/healthcare-copy.md`
- [ ] [WRITE] Housing & Apartments — `3.6 Housing/housing-copy.md`
- [ ] [WRITE] Real Estate & Government — `3.7 Real Estate/realestate-copy.md`
- [ ] [WRITE] Warehouses & Industrial — `3.8 Warehouses/warehouses-copy.md`
- [ ] [WRITE] Mosques & Community — `3.9 Mosques/mosques-copy.md`

---

## PHASE 4 — BUYER TYPE PAGES (4)
> Build `buyer-type-page-template.md` (Phase 0A) before starting this phase.

- [ ] [WRITE] Distributors — `4.1 Distributors/distributors-copy.md`
- [ ] [WRITE] Importers — `4.2 Importers/importers-copy.md`
- [ ] [WRITE] Contractors — `4.3 Contractors/contractors-copy.md`
- [ ] [WRITE] Project Developers — `4.4 Project Developers/developers-copy.md`

---

## PHASE 5 — ABOUT & TRUST PAGES (3)

- [ ] [WRITE] About Us — `5. About/about-copy.md`
- [ ] [WRITE] Certifications — `5. About/certifications-copy.md`
- [ ] [WRITE] Quality & Testing — `5. About/quality-copy.md`

---

## PHASE 6 — MARKET PAGES (6)
> Build `market-page-template.md` (Phase 0A) before starting this phase.

- [ ] [WRITE] Countries Archive — `6. Markets/countries-archive-copy.md`
- [ ] [WRITE] Europe — `6.1 Europe/europe-copy.md`
- [ ] [WRITE] North America — `6.2 North America/north-america-copy.md`
- [ ] [WRITE] Africa — `6.3 Africa/africa-copy.md`
- [ ] [WRITE] Latin America — `6.4 Latin America/latin-america-copy.md`
- [ ] [WRITE] Middle East — `6.5 Middle East/middle-east-copy.md`

---

## PHASE 7 — BLOG

- [ ] [WRITE] Blog Archive — `7. Blog/blog-archive-copy.md`
- [ ] [WRITE] What is OEM vs ODM air conditioner?
- [ ] [WRITE] How to import air conditioners from China
- [ ] [WRITE] What certifications do I need to import AC to Saudi Arabia?
- [ ] [WRITE] How to start your own AC brand
- [ ] [WRITE] R32 vs R410a — what importers need to know

---

## PHASE 8 — LEGAL (2)

- [ ] [WRITE] Privacy Policy — `8. Legal/privacy-policy.md`
- [ ] [WRITE] Terms — `8. Legal/terms.md`
