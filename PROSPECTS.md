# Named buyers

Discovery criterion `disc.named-buyer` — *"You can name five people who would buy
this. Real names of real people or companies, not a market segment."*

Five are named below. Each is a real, operating company in the GTA with a
reachable address, a live site, and a specific, observable reason it would buy
what Millwright sells. None of them is a persona, a segment, or a placeholder.

## Where these came from

Not invented for this file. ZipQuarry — the sibling product in this workspace —
enriched 992 GTA businesses and scored them against a services offer that is
Millwright's, word for word:

> We build custom apps, internal workflows and AI agents for established local
> businesses — quoting and estimating, scheduling, intake, follow-up, and the
> manual admin that eats a day a week.

That means Millwright's prospect list already existed; it was just filed under
another product. The five below are the top of that corpus by fit score, chosen
one per industry and one per Millwright build type so the list reads as a buyer
profile rather than five copies of the same shop.

Provenance for every row: `zipquarry-platform/outreach/batch-*.md`, generated
2026-08-27 and 2026-08-28. The "why they'd buy" line is the observation
ZipQuarry's enrichment drew from that company's own live site on those dates —
re-check it against the site before quoting it back to anyone.

---

## 1. Thermex Heating and Air Conditioning Inc.

- **What they do:** HVAC, Toronto out to Oshawa.
- **Where:** 11 Dallas Rd, North York, ON M2R 2J3
- **Site:** https://www.thermexheat.ca/ · **Contact:** thermex.heat@gmail.com
- **Why they'd buy:** eleven service options in the quote form, and every
  emergency call and free-estimate request still lands in a phone line or a
  Gmail inbox.
- **The Millwright build:** lead intake system — capture, qualify, auto-reply.
- **Evidence:** `batch-20260827-1633.md` (rank 88, fit score 9 — highest in the corpus)

## 2. Wilson Blanchard Management, An Associa Company

- **What they do:** condo and property management, five regions, 23M+ sq ft.
- **Where:** 10 Four Seasons Pl Suite 1000, Etobicoke, ON M9B 6H7
- **Site:** https://www.wilsonblanchard.com/ · **Contact:** torontoinfo@wilsonblanchard.com
- **Why they'd buy:** resident requests and new-business proposals both arrive
  through one web form, and after-hours emergencies route to a phone extension.
- **The Millwright build:** client portal plus request routing.
- **Evidence:** `batch-20260827-1633.md` (rank 84.9, fit score 8)

## 3. Castlemore Dental

- **What they do:** dental group, eleven locations.
- **Where:** 12 Harrison Garden Blvd, North York, ON M2N 7K6
- **Site:** http://www.castlemoredental.ca/ · **Contact:** dental22732@outlook.com
- **Why they'd buy:** eleven locations, each with its own phone number and
  Outlook address, and "Book An Appointment" still routes every new patient
  through a call or an email.
- **The Millwright build:** booking intake plus automated email/SMS confirmations
  and reminders.
- **Evidence:** `batch-20260827-1633.md` (rank 84.9, fit score 8)

## 4. BCF Contracting Group

- **What they do:** construction and development contracting.
- **Where:** 20 Bermondsey Rd Unit 100A, East York, ON M4B 1Z5
- **Site:** http://www.bcfcontracting.com/ · **Contact:** info@bcfcontracting.com
- **Why they'd buy:** they offer a free feasibility and zoning review before
  anyone spends a dollar, and every one of those requests arrives as a phone
  call, an email, or a form to work through by hand.
- **The Millwright build:** document and proposal generator — form answers in,
  drafted feasibility summary out.
- **Evidence:** `batch-20260828-2349.md` (rank 80, fit score 8)

## 5. GSK Law

- **What they do:** personal injury law.
- **Where:** 5255 Yonge St Unit 1111, North York, ON M2N 6P4
- **Site:** https://gsklaw.ca/ · **Contact:** info@gsklaw.ca
- **Why they'd buy:** the site promotes a 24/7 injury line and a free case
  evaluation, but posted hours are Mon–Fri 9–5, so after-hours intake sits in a
  phone or form queue until morning.
- **The Millwright build:** AI first-pass intake assistant — capture and triage
  overnight, a human reviews at 9am.
- **Evidence:** `batch-20260827-1633.md` (rank 79.4, fit score 8)

---

## What this does and does not establish

**Met:** five real companies are named, each reachable, each with a documented
reason it fits the offer. That is the whole of `disc.named-buyer`.

**Not established:** none of them has been contacted, and none has said it would
pay. That is the next criterion, `disc.spoken-to-five`, and it is still open. Do
not read a fit score of 8 as demand — it is a machine's read of a website, not a
person's answer.

**The bench:** 43 scored companies survive deduplication across the outreach
batches, 38 of them not listed here. If one of these five goes nowhere, the
replacement is already sourced.
