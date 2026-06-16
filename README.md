# Supply-Chain-Analysis

# PROJECT OVERVIEW
This project presents a full end-to-end supply chain analysis for a beauty product company operating across five Indian cities. The analysis covers 100 product SKUs spanning 3 categories(Skincare, Haircare, and Cosmetics) and examines performance across pricing, inventory, Logistics, and Product quality.
The project was executed across five structured phases: data profiling, data cleaning,and transformation, KPI development via Power Query and DAX, dashboard design in Power BI, and this final insights and recommendation report. The objective was to move from raw, uncleaned operational data to a decision-ready analytical product suitable for executive consumption and operational action.

# KEY FINDINGS
**REVENUE AND PROFITABILITY
Total recorded revenue across all 100 SKUs stands at approximately £577,600, with skincare contributing the largest share at £241,628 driven by its higher SKU count of 40. Cosmetics, despite having the fewest SKUs at 26, records the highest average revenue per SKU at £6,212 suggesting stronger individual product performance in that category.
Average gross margin across the portfolio sits at a healthy level, though this figure is qualified by a significant data anomaly: 57 of 100 SKUs show recorded revenue below 50% of what would be expected from their price and units sold.

**PRODUCT QUALITY
The overall average defect rate across the portfolio is 2.28%, with 32 SKUs exceeding the 3% high-defect threshold. Haircare records the worst average defect rate at 2.48%, while cosmetics performs best at 1.92%. Only 23 of the 100 SKUs passed quality inspection outright. Thirty-six failed, and 41 remain pending meaning the business currently has a clear quality picture for fewer than a quarter of its active SKUs. This is the most operationally urgent finding in the dataset.

**SUPPLIER PERFORMANCE
Supplier 1 is the strongest performer across all measured dimensions: lowest average defect rate at 1.80%, highest inspection pass count at 13 of its 27 SKUs, and competitive lead times. 
Supplier 5 carries the highest average defect rate in the portfolio at 2.67%. 
Supplier 4 is the most critical concern  across its 18 SKUs, it recorded 12 inspection failures and zero passes, with the remaining 6 still pending. No SKU supplied by Supplier 4 has passed a quality inspection. 
This represents a systemic quality risk that warrants immediate escalation regardless of lead time or cost performance.

# Recommendations
**Immediate actions
Conduct a formal audit of Supplier 4 across all 18 affected SKUs. Given the complete absence of passing inspections, no new procurement orders should be placed with this supplier until root cause is established and resolved. Simultaneously, the 41 pending inspections represent an unknown quality exposure completing these should be treated as an operational priority before the next demand cycle.

Investigate the defect rate gap between haircare (2.48%) and cosmetics (1.92%) to determine whether this is a supplier issue, a product complexity issue, or a measurement inconsistency. Formalise supplier scorecards using the KPIs developed in Phase 3 (defect rate, pass rate, average lead time, and logistics cost ratio) and review them on a quarterly cadence. Consider consolidating volume from Supplier 4 toward Supplier 1 and Supplier 2 while quality remediation is underway.
