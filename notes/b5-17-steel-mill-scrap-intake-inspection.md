---
date: 2026-06
type: Construction
persona: Vendor
contact_role: Raw materials / scrap intake inspector at a steel mill
org_type: Large US steel mini-mill (scrap-fed electric furnace)
pains: ["Fragmented tools and admin tax (manual Excel inventory reporting)", "Material procurement and supply volatility", "Cannot see below the top layer of scrap piles", "Cannot trace unsealed or non-ferrous containers back to the source"]
buy-signal: None
summary: "Scrap Inspector A does intake QC on scrap from ~50 scrapyards, catching sealed or non-ferrous containers before they reach the furnace, since a sealed container can explode and kill people. Pains: drones only show the top layer of a pile, tracing bad material in a 10-19K-ton pile (zeroed out every 6 months) is near-impossible, and his weekly/monthly scrap inventory report took 8 hours in Excel (automated to 35 minutes, but he does not yet trust it)."
decisions: None
actions: []
---

# Scrap Inspector A (steel mill raw materials) - intake inspection and material tracking

## Role and flow
- Bulk inspection of incoming scrap, riding around the yard and flying drones looking for bad loads. Scrap is offloaded at a bulk terminal operator, which is allowed a certain amount of downtime each week. Lots of scrap comes from Texas, from about 50 different scrapyards, some very large ("stuff just gets through").
- Four operators offload trucks and barges and know what to look for so unsealed containers do not slip through.
- Ordering scale: ~120K tons of scrap bought for the next month from a single supplier.

## Pains
- **Safety/quality:** non-ferrous material or unsealed (sealed-container) items that reach the furnace can blow up, break equipment and kill people. Keeping track of them and finding them is the biggest issue.
- **Visibility:** drones only see the top layer; he wants to scan everything somehow. Piles of 10-19K tons must be zeroed out every 6 months; if unsealed material is found at that point there is no way to trace it back to a source.
- **Mitigation so far:** big fines ($25-30K) on scrapyards have reduced bad loads.
- **Reporting:** weekly and monthly scrap reports (what is on the ground, weeks of each material, in transit versus just bought for next month) took 8 hours in spreadsheets; an automation now makes it 35 minutes, but he spent two weeks double-checking because he does not trust it.

## Read
Adjacent-industry example of material tracking and distrust of automated output. No purchase intent.
