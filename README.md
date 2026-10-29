# FI/CO Demo API: Demo Wholesale

Fictional demo data for a cash and carry wholesaler, used by a SAP Joule budget check agent. Not real company data.

- 4 company codes: 1000 Germany, 2000 Austria, 3000 Netherlands, 4000 Belgium
- 154 cost centers (Germany 88, Austria 20, Netherlands 26, Belgium 20): 101 stores, food service delivery, fleets, warehouses, purchasing, digital, marketing, IT, administration
- 22 GL accounts, fiscal year 2026, actuals for periods 001-010, EUR
- 12,449 actual posting lines, 689 open purchase orders
- Available budget = budget - actuals - commitments (open purchase orders)

Full overview of all cost centers: summary.csv

## Endpoints (GitHub Pages)

- /companycodes.json
- /costcenters.json
- /costcenters/{ID}.json
- /budgets/{ID}.json
- /actuals/{ID}.json
- /commitments/{ID}.json
- /glaccounts.json
