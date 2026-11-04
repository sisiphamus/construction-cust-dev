---
date: 2026-06
type: Construction
persona: Vendor
pains: []
buy-signal: None
contact_role: Product/content rep at a building-code publisher (code and specs tools)
org_type: Large national building-code standards organization with code platform, AI Q&A chatbot and a new specs tool
summary: Interviewer 2 asked a rep at a major building-code publisher how its code platform tracks local amendments. A 40+ person content team calls city halls and monitors government change-notification services, and an in-house web scraper reads city sites. The organization only knows amendments it is told about; users report missing ones and it then works with that jurisdiction to improve the pipeline. Code is public law so amendments are documented somewhere, but municipal websites are inconsistent. A new specs tool for architects layers AI plan review on top of the code base.
actions: Interviewer is interested in learning more about the specs tool and integration strategy.
---

# Code Publisher Rep A (national building-code standards organization) - how local amendments are sourced; new specs tool

Interviewer 2 on a call (recorded).

## Amendment sourcing
- **Manual outreach:** 40+ people on the content team call city halls to learn of amendments. Some large cities and states proactively email amendment databases or list changes; others require calling.
- **Automated monitoring:** subscribes to the government notification services that cities/states use to publish changes. Coverage varies with the jurisdiction's infrastructure maturity.
- **Web scraping:** built in-house, not purchased. Challenge: municipal sites vary widely in quality, age and structure. Backup: amendments are always in public documents (meeting minutes, council agendas, official code repositories).
- **Gap detection:** users report "you don't have amendment X that's live". The rep: "Happens all the time." If one city repeatedly has unreported amendments, they contact it and ask how to get all its amendments reliably, treating it as a discovery problem.
- Candid limit: "We only know what's given to us." No way to guarantee 100% coverage, especially of obscure, locally published amendments.

## Specs tool (brief)
- Building specs tool for architects specifying materials/products; comparable to existing spec tools but "sleeker, faster, easier to use". Built on the organization's code platform plus an AI layer; follow-on to its AI Q&A chatbot (about 150K questions answered).
- Workflow: architect loads specs; AI checks specs against code; architect uploads plans; AI checks plans against code and specs (code, spec and plan review). After submittal, if the municipal reviewer flags issues the architect can re-upload a revised plan to re-run the check. If the architect disagrees with the reviewer, arguing is on the architect, not the vendor.
- Coverage: California, LA, San Diego, Texas (Houston, Austin), New York (state and city), Chicago/Illinois; some full, some partial, depending on whether the jurisdiction adopted the vendor's codes.
- Team: engineering ~40 people, content ~40 people.
