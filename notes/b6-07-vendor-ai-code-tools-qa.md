---
date: 2026-06
type: Construction
persona: Vendor
contact_role: Presenters from a national building-code standards organization, plus a past president and code-official panelists (Q&A)
org_type: National building-code standards organization presenting AI tools at an industry conference
pains:
  - "Code interpretation inconsistency"
  - "Local officials override written code"
  - "Permitting delays"
  - "Plan review friction and cost"
buy-signal: Strong interest from Interviewer 2 in the tools and methodology for a queryable code database; no purchase.
summary: "Conference presentation on AI in building-code tools (Q&A chatbot, design-software plugins, automated plan pre-check) followed by Interviewer 2 asking how they handle code officials who interpret code differently than written. Led to a long discussion of appeals, state interpretations, expert witnesses, and case studies of official overreach."
decisions:
  - "Organization is partnering with 10+ vendors on AI code tools rather than building everything itself"
  - "Next-generation AI Q&A tool releasing the following month"
  - "Expanding to amended codes (state level first, then major cities)"
actions:
  - "Interviewer 2 to follow up with the past president about interpretation issues and appeals"
  - "Interviewer 2 interested in the organization's tools and methodology for a queryable code database"
---

# Code-standards organization presentation (AI code tools) plus Interviewer 2 Q&A on official overreach

## What was presented
- Problem: architects spend too much time researching code instead of designing; decisions are scattered across books, emails, phone calls; compliance verified late at plan review.
- AI agents monitor jurisdiction amendments and update the product suite (some cities email updates, others need manual outreach; a 40+ person content team keeps relationships with city halls for amendment intel).
- Products: AI Q&A chatbot trained only on building code and safety content (150K+ questions answered); free plugins for Revit and AutoCAD (2025-2027 versions; Bluebeam on the roadmap) showing compliance guidance at the moment of design; automated pre-check before municipal submission (similar to collision detection) via ~10 partner vendors; drag-and-drop code element library for construction documents.
- Technical approach: model restricted to 8-15 code books per jurisdiction to reduce hallucination. Limits: some noise leaks in (partial reliance on a general LLM vendor), full commentary behind a premium paywall, state amendments in training, city amendments in progress (not every town coverable).

## Interviewer 2's question
He said the queryable standardized-code idea is strong, but municipal reviewers treat code as open to interpretation even when the manual is clear; what are they doing about it? Answer: "Absolutely nothing. I have no power over those officials," but surfacing commentary, changes and historical documentation helps because officials often do not read them.

## Discussion: interpretation authority
- Past president view: officials have authority to interpret through the appeals process, but many misuse it as a "power trip." Leverage: appeals, state interpretations, expert-witness testimony. A formal ICC opinion carries weight legally.
- Case studies from code-official panelists:
  1. Plumbing reviewer denied a toilet-placement exception the code allows, citing hearsay from a fire marshal at a seminar; took weeks to expose.
  2. Some fire officials will not budge even with a national interpretation; a state fire marshal letter helps, but clients cannot wait and keep building while fighting.
  3. Engineers misread a "2-inch" overflow scupper rule that applies only to one drainage type.
  4. Concrete podium structural frame (2-hour) with non-structural partitions (1-hour) challenged by an official who "didn't like it" although correct.
  5. A mall tenant space under ~750 sqft where an official demanded a 2-hour fire wall with a wrong citation, then said "not in my jurisdiction"; architect had to escalate to a supervisor.
  6. A county event-center expansion from carport where an official's demands moved water/sewer and ballooned cost from ~$100K to $1.9M; he later admitted on record he was not the authority having jurisdiction (elected officials are).
  7. A private third-party inspector tried to override an approved plan with a 2-hour rating; inspectors cannot override plan reviewers, but it happens often.
- Panel consensus: ~3 in 10 officials give wrong citations (have not read the code in years), ~5 in 10 read one line and miss exceptions; "interpret" often means "I'm the authority and I do what I want"; many do not feel contractors' pain; better officials see their role as advising on life safety.
- Workarounds: state-level interpretations (fire marshal, a state building commission's declaratory statements, whose website is poor and hard to search), expert witnesses.

## Interviewer takeaway
Code queryability is essential infrastructure, but the deeper issue is official behavior. Needed: consistent training/oversight of officials, public access to jurisdictional interpretations, accessible appeals, expert-witness access, and state guidance when locals go rogue. Competing/adjacent vendors mentioned: Deltek, RIB.
