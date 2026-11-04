---
date: 2026-06
type: Construction
persona: Vendor
contact_role: Rep at a building-code publisher (product on the specs/code tool side)
org_type: Large national building-code standards publisher with a code platform, a Q&A chatbot and a new specs tool
pains: []
buy-signal: "None"
summary: "Interviewer 2 spoke with a rep at a building-code publisher about how they source local code amendments for their platform. The publisher has 40+ people on a content team calling city halls and monitoring government change-notification services, plus in-house web scraping of city sites. Challenge: they only know amendments they are told about; users report missing amendments, which forces them to improve discovery. Code is public law so amendments are documented somewhere, but municipal websites are difficult and inconsistent."
decisions: "None explicit."
actions: "Interviewer interested in learning more about the specs tool and the integration strategy."
---

# Vendor Rep A (building-code publisher) - how code amendments are tracked, plus a specs tool

## Summary
Interviewer 2 asked about methodology for tracking building code amendments across municipalities. Key insight: a 40-person content team calling city halls, plus automated subscriptions to government change-notification services, plus in-house web scraping (built, not bought). Gaps are discovered when users report missing amendments; when patterns emerge (one city repeatedly missed), they contact that jurisdiction to improve the pipeline. Code is public law, so amendments are always documented somewhere, but municipal websites are often poor (inconsistent, old platforms).

## Amendment sourcing process
- **Manual outreach:** 40+ people dedicated to calling city halls. Some large cities and states proactively email amendment databases or list changes; others require calling.
- **Automated monitoring:** cities/states publish through government notification services; the publisher subscribes to the same ones. Varies with jurisdiction maturity.
- **Web scraping:** built in-house. Municipal sites vary widely in quality, age and structure. Backup: amendments always appear in public documents (meeting minutes, council agendas, official code repositories).

## Gap detection loop
- Users report "you don't have amendment X that's live"; the rep says this "happens all the time."
- If one city repeatedly has unreported amendments, they contact the jurisdiction and ask how to get all amendments reliably, establishing a better data pipeline. Treated as a discovery problem.
- Candid limit: "We only know what's given to us." No way to guarantee 100% coverage, especially obscure amendments published only locally.

## Specs tool (brief)
- A building specs tool for architects specifying materials/products; comparable to existing spec tools but "sleeker, faster, easier to use," built on the publisher's code base plus an AI layer; follow-on to its earlier Q&A chatbot (which has answered ~150K questions).
- Workflow: (1) architect loads specs; (2) AI checks specs against building code; (3) architect uploads plans; (4) AI checks plans against code plus specs; (5) post-submittal, if a municipal plan reviewer flags issues, the architect re-uploads the revised plan to re-run the check; (6) if the architect disagrees with the reviewer, it is on the architect to argue; the publisher does not mediate.
- Coverage: California, Texas, New York, Illinois and others; some full, some partial, depending on whether the jurisdiction adopted the publisher's codes.
- Team: engineering ~40 people, content ~40 people.

## Related
Existing spec databases are the competition; CAD/BIM integrations exist; municipal web scraping quality is the shared challenge.
