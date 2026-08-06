\# Dark Store SLA \& Fraud Analytics



Simulated quick-commerce operations dataset analyzing delivery SLA breaches, delivery partner performance, refund fraud patterns, and inventory health across 6 dark stores.



\## Tools Used

\- MySQL (data modeling, SQL analysis)

\- Power BI (dashboard, DAX measures)



\## Dataset

\- 800 orders, 150 customers, 45 delivery partners, 6 dark stores, 60 products

\- 8 relational tables with foreign key constraints



\## Key Findings

\- \*\*89.3% overall SLA breach rate\*\* across delivered orders — flagged as a systemic delivery-time issue

\- \*\*2 customers flagged for refund fraud\*\* via pure SQL threshold logic (no ML) — both showing 100% claim rates on 3+ orders, totaling ₹3,008 in refund exposure

\- \*\*5+ products across 4 stores\*\* found with 60+ days since last restock despite falling below reorder threshold

\- \*\*E-scooter deliveries\*\* showed the highest SLA breach rate (95.3%) compared to bike (88.7%) and bicycle (85.7%)



\## Dashboard Pages

1\. Ops Overview — KPI cards + SLA breach heatmap (store × hour)

2\. Partner Performance — delivery partner scorecard + vehicle-type comparison

3\. Fraud \& Refunds — flagged customer table + refund reason breakdown

4\. Inventory Health — reorder alerts sorted by days since restock



\## Dashboard

See `DARKSTORE POWERBI.pdf` for all 4 dashboard pages, or open `DARKSTORE POWERBI.pbix` in Power BI Desktop for the interactive version.



\## Files

\- `darkstore\_full\_setup.sql` — full database schema + data (run in MySQL to reproduce)

\- `DARKSTORE POWERBI.pbix` — Power BI dashboard file

\- `DARKSTORE POWERBI.pdf` — dashboard exported as PDF (all 4 pages)

