# Millwright — state

## What just changed

`disc.named-buyer` is met. Five real GTA companies are named in
[PROSPECTS.md](PROSPECTS.md), with contact details, live URLs, and a
site-specific reason each would buy. Discovery's hardest-to-fake criterion is no
longer blocking.

## What was learned, and is worth remembering

**Millwright's prospect list already existed under another product.** ZipQuarry's
enrichment run scored 992 GTA businesses against an offer that is Millwright's
pitch verbatim — custom apps, workflows and AI agents for established local
businesses. 43 scored companies survive deduplication in
`zipquarry-platform/outreach/batch-*.md`. Nobody has to go find buyers for
Millwright; the finding was that they had already been found and filed elsewhere.

**This changes the read on the project.** Shipshape has Millwright at 6% against
Discovery, paused, and calls it "the clearest candidate for a deliberate kill."
That assessment was made without knowing a scored, contactable buyer list was
sitting one repo over. A kill decision should be re-made with that on the table.

## Next

- [ ] `disc.spoken-to-five` — talk to five of them. The five in PROSPECTS.md have
      drafted emails already written in the same batch files. Sending is the
      blocker, not writing. Note the workspace-wide constraint: bulk sending is
      not CASL-clean yet, but five hand-sent emails from a real inbox is not bulk.
- [ ] `disc.problem-statement` — in progress on the board; the "why they'd buy"
      lines in PROSPECTS.md are raw material for it, written from real sites.
- [ ] `disc.smallest-version`, `disc.kill-criteria` — untouched, both required.
- [ ] Update `shipshape-platform/docs/projects/millwright.md` — its "What it is"
      section still says Not documented, and its board still lists
      `disc.named-buyer` in Backlog. A person moves the status, so that edit is
      Melanie's call, not this session's.

## House rules for this repo

Static site, no build step. `index.html` is the entire site. Verify changes by
opening the page in a browser. Several agent sessions share this workspace — run
`git status` and add paths explicitly before committing.
