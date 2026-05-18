# The Ancillary Playbook · Quick Reference

During-call companion tool for Clear Path Coverage MA agents. Designed for at-a-glance lookup while on live cross-sell calls.

**Live URL:** https://duynomite.github.io/unl-ancillary-quickref/
**Iframed at:** clearpathcoverage.com (WordPress shell)
**Parent tool:** [The Ancillary Playbook](https://github.com/Duynomite/unl-ancillary-playbook)

## What this is

A focused single-page reference tool agents keep open during live calls. Two tabs:

- **Tab 1 — Quick Reference:** linear call-flow with 10+ cards (Lexicon · CPC Fit Filters · Customer Profile Decoder · 4 NEPQ Discovery Questions · Preference Question · Tier Match + HHC Trigger · The Money Talk · Mid-Call DQ · Pre-emptive Reframes · Q1-Q4 Close · Application + Signature · Post-Sale 60 Seconds · Customer FAQ).
- **Tab 2 — Full Script:** verbatim end-to-end integrated CPC MA + Ancillary call script with both Scenario 3 (harvest) and Scenario 4 (pivot) paths.

Sticky right sidebar always visible: Compliance "Never Say" table + Top 6 Objections.

## Deploy structure

This repo is the **public deploy artifact only**. Contains a single static HTML file (`index.html`) served by GitHub Pages.

- **Source:** lives in the private `Duynomite/claude-projects` repo at `TOOLS/MA_Crosssell_Quick_Reference.html`.
- **Parent:** `Duynomite/unl-ancillary-playbook` — the full training course.

## Update flow

1. Edit `TOOLS/MA_Crosssell_Quick_Reference.html` in the private source repo.
2. Copy to `/tmp/unl-ancillary-quickref/index.html`.
3. `git commit -am "..."` and `git push`.
4. GitHub Pages auto-rebuilds; WordPress iframe picks up new content. No WP touch needed.
