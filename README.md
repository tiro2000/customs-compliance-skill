# customs-compliance-skill
AI agent skill for customs trade document validation. domain expertise encoding WCO, ICC Incoterms 2020, and WTO standards. 6/6 eval scenarios passed, 0 false positives. Defers HS classification to deterministic tools — validates everything around it.

## Standards & References
This skill validates documents against internationally published standards:
- WCO HS Nomenclature 2022 (7th Edition)
- ICC Incoterms 2020 (Publication No. 723E)
- WTO Agreement on Customs Valuation (Article VII GATT 1994)
- WCO General Rules of Interpretation (GRI 1-6)

All evaluation scenarios use synthetic, fictional trade documents. 
No real trader data, shipment records, or customs authority data was used.

## Scope
This skill is an educational and research tool for demonstrating 
AI agent architecture with domain-encoded knowledge. It supports 
human officer decision-making and does not replace customs authority.
