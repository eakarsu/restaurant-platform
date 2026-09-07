# Feature status — Restaurants, catering & food operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 346 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 2 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 2 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 3 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 9 | 0 | Native records/view |
| Activity & audit trail | audit | 5 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Distributor agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand SKU registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory account mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Depletion report ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account eligibility validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume tier calculation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Promotional period control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Billback calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Display allowance evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate claim detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distributor deduction matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim approval workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit memo reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accrual true-up | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand distributor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gourmet Beef Gyro | records | 1 | 0 | Native records/view |
| Signature Chicken Fiesta Hero | records | 1 | 0 | Native records/view |
| Custom Garden Salad | records | 1 | 0 | Native records/view |
| Superfood Acai Bowl | records | 1 | 0 | Native records/view |
| Restaurants | records | 1 | 0 | Native records/view |
| How it works | records | 1 | 0 | Native records/view |
| Faq | records | 2 | 0 | Native records/view |
| Menu | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Blog | records | 1 | 0 | Native records/view |
| Orders | records | 5 | 0 | Native records/view |
| Automated calls | records | 1 | 0 | Native records/view |
| Dashboard | records | 1 | 0 | Native records/view |
| Inventory | records | 3 | 0 | Native records/view |
| Staff | records | 3 | 0 | Native records/view |
| Schedules | records | 1 | 0 | Native records/view |
| Reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wait time | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Upsell | records | 1 | 0 | Native records/view |
| Dynamic pricing | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Predictive inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staff optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Affiliate network | records | 1 | 0 | Native records/view |
| Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sustainability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voice order | records | 1 | 0 | Native records/view |
| Group order | records | 1 | 0 | Native records/view |
| Demand forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver route optimization | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Menu recommendation cold | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Churn prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic surge pricing | records | 1 | 0 | Native records/view |
| Loyalty rewards | records | 1 | 0 | Native records/view |
| Affiliate payouts | records | 1 | 0 | Native records/view |
| Restaurant health score | records | 1 | 0 | Native records/view |
| Kds integration | integration | 1 | 0 | Provider request records only |
| Outbound webhooks | integration | 1 | 0 | Provider request records only |
| Multimodal intake | records | 1 | 0 | Native records/view |
| Driver incentive | records | 1 | 0 | Native records/view |
| Post delivery feedback | records | 1 | 0 | Native records/view |
| Supply warnings | records | 1 | 0 | Native records/view |
| Kds streaming | records | 1 | 0 | Native records/view |
| Supplier agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Item and category master | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase and receipt ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume-tier qualification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth incentive calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deviated pricing reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| New-location allowance tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Promotional allowance calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Private-label incentive tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Freight and fuel allowance audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate accrual accounting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier statement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier response management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit and cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier and category yield analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broker agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory customer mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product eligibility registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distributor depletion ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross sales calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Returns deduction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Promotion exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Net sales calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commission tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draw recovery control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate commission detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broker dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment correction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broker territory analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Platform agreement library | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Restaurant and brand registry | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Order ingestion | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| POS order matching | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Commission-rate validation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Delivery and service-fee audit | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Promotion funding allocation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Refund responsibility analysis | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Cancellation validation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Menu price and tax reconciliation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Sponsored-listing fee audit | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Chargeback reconciliation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Settlement statement audit | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Platform dispute workflow | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Recovered settlement ledger | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Brand platform and location analytics | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Supplier program library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Approved product registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Franchise location mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distributor purchase ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Net eligible volume | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth incentive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketing allowance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality shortfall credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return spoilage exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate accrual ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recipes | records | 3 | 0 | Native records/view |
| Production Schedule | records | 1 | 0 | Native records/view |
| Production Sheet PDF | records | 1 | 0 | Native records/view |
| Batch Tracking | records | 1 | 0 | Native records/view |
| Oven Scheduling | records | 1 | 0 | Native records/view |
| Wholesale Orders | records | 1 | 0 | Native records/view |
| Custom Cakes | records | 2 | 0 | Native records/view |
| Ingredients | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Inventory Alerts | records | 1 | 0 | Native records/view |
| Suppliers | records | 1 | 0 | Native records/view |
| Supplier Orders | records | 1 | 0 | Native records/view |
| Batch Alerts | records | 1 | 0 | Native records/view |
| Allergen Tracking | records | 3 | 0 | Native records/view |
| Temperature Logs | records | 2 | 0 | Native records/view |
| Waste Tracking | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Staff Scheduling | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Equipment | records | 5 | 0 | Native records/view |
| Fresh Markdown | records | 1 | 0 | Native records/view |
| Recipe Scaling AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand Forecast AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketing Copy AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nutrition Label AI | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cake Design AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seasonal Menu AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seasonal Forecast AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost Analysis AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bottleneck Detector AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Batch Quality AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI History | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Brew Log | records | 1 | 0 | Native records/view |
| Tank Management | records | 1 | 0 | Native records/view |
| Raw Materials | records | 1 | 0 | Native records/view |
| Fermentation Logs | records | 1 | 0 | Native records/view |
| Packaging Runs | records | 1 | 0 | Native records/view |
| Keg Tracking | records | 1 | 0 | Native records/view |
| Taproom POS | records | 1 | 0 | Native records/view |
| Distribution | records | 1 | 0 | Native records/view |
| Lab Results | records | 1 | 0 | Native records/view |
| Loyalty Program | records | 1 | 0 | Native records/view |
| Financial Records | records | 1 | 0 | Native records/view |
| CIP Schedules | records | 1 | 0 | Native records/view |
| Vendors | records | 2 | 0 | Native records/view |
| Batch Manager | records | 1 | 0 | Native records/view |
| Alerts | records | 1 | 0 | Native records/view |
| Webhooks | integration | 2 | 0 | Provider request records only |
| Fermentation deviation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance | records | 1 | 0 | Native records/view |
| Work Orders | records | 1 | 0 | Native records/view |
| Parts Inventory | records | 1 | 0 | Native records/view |
| Diagnostics | records | 1 | 0 | Native records/view |
| Compliance | records | 2 | 0 | Native records/view |
| Energy | records | 1 | 0 | Native records/view |
| Cost Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Technicians | records | 1 | 0 | Native records/view |
| Parts Triage | records | 1 | 0 | Native records/view |
| Lab | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Virtual Brands | records | 1 | 0 | Native records/view |
| Menus | records | 2 | 0 | Native records/view |
| Kitchen Stations | records | 1 | 0 | Native records/view |
| Packaging | records | 1 | 0 | Native records/view |
| Drivers | records | 1 | 0 | Native records/view |
| Delivery Zones | records | 1 | 0 | Native records/view |
| Kitchen Schedules | records | 2 | 0 | Native records/view |
| Labor Scheduling | records | 1 | 0 | Native records/view |
| Food Costs | records | 1 | 0 | Native records/view |
| Platform Fees | records | 1 | 0 | Native records/view |
| Revenue | records | 1 | 0 | Native records/view |
| Profitability | records | 1 | 0 | Native records/view |
| Quality Control | records | 1 | 0 | Native records/view |
| Temp Logs | records | 1 | 0 | Native records/view |
| Health Inspections | records | 1 | 0 | Native records/view |
| Cleaning | records | 2 | 0 | Native records/view |
| Loyalty | records | 2 | 0 | Native records/view |
| Menu Optimization | records | 1 | 0 | Native records/view |
| Brand Concepts | records | 1 | 0 | Native records/view |
| Demand Forecast | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social Media | records | 1 | 0 | Native records/view |
| Site Selection | records | 1 | 0 | Native records/view |
| Brand Portfolio | records | 1 | 0 | Native records/view |
| Ingredient Sub | records | 1 | 0 | Native records/view |
| Driver Routing | records | 1 | 0 | Native records/view |
| Cannibalization | records | 1 | 0 | Native records/view |
| Prep Load Balancer | records | 1 | 0 | Native records/view |
| Generate | records | 1 | 0 | Native records/view |
| List | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Scan | records | 2 | 0 | Native records/view |
| Run | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overrides | records | 1 | 0 | Native records/view |
| Customer comms | records | 1 | 0 | Native records/view |
| agentic kitchen automation prioritizing | records | 1 | 0 | Native records/view |
| cross brand cannibalization detection fl | records | 1 | 0 | Native records/view |
| seasonal menu advisor tracking ingredien | records | 1 | 0 | Native records/view |
| delivery zone heat map with surge | records | 1 | 0 | Native records/view |
| workforce burnout prediction based on la | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| camera based food safety monitor detecti | records | 1 | 0 | Native records/view |
| ghost kitchen site selection ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| brand portfolio optimization | records | 1 | 0 | Native records/view |
| ingredient substitution ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| video based quality control | records | 1 | 0 | Native records/view |
| payment processing surface | integration | 1 | 0 | Provider request records only |
| vendor supplier directory beyond inve | records | 1 | 0 | Native records/view |
| real time websocket order board | records | 1 | 0 | Native records/view |
| multi location franchise rollup | records | 1 | 0 | Native records/view |
| file upload module for menu | records | 1 | 0 | Native records/view |
| Nutrition | records | 1 | 0 | Native records/view |
| Calories | records | 2 | 0 | Native records/view |
| Prices | records | 1 | 0 | Native records/view |
| Recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Translate | records | 2 | 0 | Native records/view |
| Menu Engineer | records | 1 | 0 | Native records/view |
| Dietary Filters | records | 1 | 0 | Native records/view |
| Seasonal | records | 1 | 0 | Native records/view |
| Locations | records | 2 | 0 | Native records/view |
| Costs | records | 1 | 0 | Native records/view |
| AI Cost Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Price Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Dish Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plate margin reprice | records | 1 | 0 | Native records/view |
| Completions | records | 1 | 0 | Native records/view |
| Purchase recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cert grade | records | 1 | 0 | Native records/view |
| Market trends | records | 1 | 0 | Native records/view |
| Menu pairings | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cellar allocation | records | 1 | 0 | Native records/view |
| Auction predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tasting event guide | records | 1 | 0 | Native records/view |
| Distributor reorder | records | 1 | 0 | Native records/view |
| Quote Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dietary Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Logistics Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Follow-up Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review Request | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proposal Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Timeline Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Menu success | records | 1 | 0 | Native records/view |
| Delivery routing | records | 1 | 0 | Native records/view |
| Equipment scheduling | records | 1 | 0 | Native records/view |
| Staffing prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Satisfaction prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier autoorder | records | 1 | 0 | Native records/view |
| Rules & Jobs | records | 1 | 0 | Native records/view |
| Categories | records | 2 | 0 | Native records/view |
| Build your own | records | 1 | 0 | Native records/view |
| Checkout | records | 1 | 0 | Native records/view |
| Offers | records | 1 | 0 | Native records/view |
| Order tracking | records | 1 | 0 | Native records/view |
| Returns refunds | records | 1 | 0 | Native records/view |
| Support | records | 1 | 0 | Native records/view |
| Privacy policy | records | 1 | 0 | Native records/view |
| Customer Map | records | 1 | 0 | Native records/view |
| Financial | records | 1 | 0 | Native records/view |
| Permits | records | 1 | 0 | Native records/view |
| Verify email | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Generic ordering service enhanced work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Users | records | 3 | 0 | Native records/view |
| Schedule | records | 1 | 0 | Native records/view |
| Time clock | records | 1 | 0 | Native records/view |
| Tip distribution | records | 1 | 0 | Native records/view |
| Performance record | records | 1 | 0 | Native records/view |
| Training record | records | 1 | 0 | Native records/view |
| Table | records | 1 | 0 | Native records/view |
| Reservation | records | 1 | 0 | Native records/view |
| Waitlist | records | 1 | 0 | Native records/view |
| Menu category | records | 1 | 0 | Native records/view |
| Menu item | records | 1 | 0 | Native records/view |
| Modifier group | records | 1 | 0 | Native records/view |
| Modifier | records | 1 | 0 | Native records/view |
| Menu item modifier group | records | 1 | 0 | Native records/view |
| Ingredient | records | 1 | 0 | Native records/view |
| Menu item ingredient | records | 1 | 0 | Native records/view |
| Vendor | records | 1 | 0 | Native records/view |
| Purchase order | records | 1 | 0 | Native records/view |
| Purchase order item | records | 1 | 0 | Native records/view |
| Stock movement | records | 1 | 0 | Native records/view |
| Waste record | records | 1 | 0 | Native records/view |
| Order | records | 1 | 0 | Native records/view |
| Order event | records | 1 | 0 | Native records/view |
| Inventory reservation | records | 1 | 0 | Native records/view |
| Inventory reservation line | records | 1 | 0 | Native records/view |
| Payment attempt | records | 1 | 0 | Native records/view |
| Refund | records | 1 | 0 | Native records/view |
| Webhook event | integration | 1 | 0 | Provider request records only |
| Outbox event | records | 1 | 0 | Native records/view |
| Order item | records | 1 | 0 | Native records/view |
| Order item modifier | records | 1 | 0 | Native records/view |
| Delivery info | records | 1 | 0 | Native records/view |
| Payment | records | 1 | 0 | Native records/view |
| Split check | records | 1 | 0 | Native records/view |
| Split check item | records | 1 | 0 | Native records/view |
| Loyalty points | records | 1 | 0 | Native records/view |
| Loyalty transaction | records | 1 | 0 | Native records/view |
| Feedback | records | 1 | 0 | Native records/view |
| Recommendation | records | 1 | 0 | Native records/view |
| Sales report | records | 1 | 0 | Native records/view |
| Integration | integration | 1 | 0 | Provider request records only |
| Integration log | integration | 1 | 0 | Provider request records only |
| Promotion | records | 1 | 0 | Native records/view |
| Notification | records | 1 | 0 | Native records/view |
| Notification template | records | 1 | 0 | Native records/view |
| Recipe | records | 1 | 0 | Native records/view |
| Location | records | 1 | 0 | Native records/view |
| Result | records | 1 | 0 | Native records/view |
| Dynamic price suggestion | records | 1 | 0 | Native records/view |
| No show risk score | records | 1 | 0 | Native records/view |
| Tip fairness report | records | 1 | 0 | Native records/view |
| Concierge message | records | 1 | 0 | Native records/view |
| Operation receipt | records | 1 | 0 | Native records/view |
| Operation audit | records | 1 | 0 | Native records/view |
| Restaurant ai run | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Restaurant knowledge | records | 1 | 0 | Native records/view |
| Menu items | records | 1 | 0 | Native records/view |
| Posts | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 346 feature pages were visited in the browser; 344 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 135 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

135 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
