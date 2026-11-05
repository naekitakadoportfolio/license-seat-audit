<p align="center"><img src="assets/banner.svg" alt="License Seat Audit" width="100%"></p>

<p align="center">
<img src="https://img.shields.io/badge/stack-Apps_Script_·_Sheets_·_Slack-5B3A3A?style=flat-square">
<img src="https://img.shields.io/badge/data-fictional-FBE3EC?style=flat-square">
<a href="https://sider.ai/agents/web-creator/share/695ea81100a621619985fdfb"><img src="https://img.shields.io/badge/Portfolio-Nae_Kitakado-F4B4CD?style=flat-square"></a>
</p>

<p align="center"><a href="https://naekitakadoportfolio.github.io/license-seat-audit/"><img src="https://img.shields.io/badge/%E2%96%B6%20Try%20the%20live%20demo-5B3A3A?style=for-the-badge" alt="Live demo"></a></p>

# License Seat Audit

Finds unused software seats before renewal and reclaims them safely. Adjust the inactivity threshold, stage or exempt users, confirm removals and watch the savings and weekly report update.

> **Portfolio rebuild.** This is a from-scratch recreation of a production system I designed and run, rebuilt with **fictional data** and no client names, code or branding. The live demo runs entirely in the browser.

## The problem
A per-seat software renewal was coming up, and nobody knew which of 100+ seats were actually used. Removing the wrong person would break their work, so manual audits never happened.

## Impact in production
A repeatable audit with staging, lifecycle tracking and exemptions meant seats could be reclaimed safely before renewal, with a weekly report keeping leadership informed.

## What it demonstrates
| Capability | How |
|---|---|
| Lifecycle state machine | Active → Flagged → Staged → Removed, with Restore |
| Configurable rules | Inactivity threshold and pricing |
| Exemptions | Override protection with a recorded reason |
| Savings reporting | Annual savings rolled up live |
| Stakeholder comms | Auto-generated weekly chat report |

## Production architecture
Apps Script pulls workspace members and activity via REST API → Sheets staging tab → dashboard web app → weekly Slack webhook report

## Try it
Open the **[live demo](https://naekitakadoportfolio.github.io/license-seat-audit/)** or run `index.html` locally. No install needed.

---
<p align="center"><sub>Built by <b>Nae Kitakado</b>, AI Automation Consultant · <a href="https://www.linkedin.com/in/nae-k-203194265">LinkedIn</a> · <a href="https://sider.ai/agents/web-creator/share/695ea81100a621619985fdfb">Portfolio</a> · open to retainer &amp; part-time consulting</sub></p>
