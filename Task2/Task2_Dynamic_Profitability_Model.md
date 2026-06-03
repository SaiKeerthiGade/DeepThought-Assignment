📌 TASK 2: DYNAMIC PROFITABILITY MODEL
Objective

To build a dynamic Google Sheets model that calculates Amazon advertising profitability based on input parameters like SP, COGS, Ad Spend, and Units sold.

📊 INPUT SECTION (Google Sheet)
Parameter	Value
Selling Price (SP)	800
COGS	280
Amazon Fee %	12%
Monthly Ad Spend	300000
Units Sold via Ads	1500
Organic Units Sold	2000
Fixed Costs	150000

⚙️ OUTPUT FORMULAS USED
1. Gross Margin per Unit
SP - COGS = 800 - 280 = 520
2. Amazon Fee per Unit
SP × 12% = 96
3. Ad Cost per Unit
Ad Spend ÷ Ad Units = 300000 ÷ 1500 = 200
4. Net Margin (Ad Units)
520 - 96 - 200 = 224
5. Net Margin (Organic Units)
520 - 96 = 424
6. Total Revenue
800 × (1500 + 2000) = 2,800,000
7. Total Profit
(224 × 1500) + (424 × 2000) - 150000
= 1,034,000
8. ACOS
Ad Spend ÷ Ad Revenue
= 300000 ÷ (800 × 1500)
= 25%
9. TACOS
Ad Spend ÷ Total Revenue
= 300000 ÷ 2800000
= 10.71%


📈 SCENARIO ANALYSIS
Scenario 1: SP increases → ₹950
Profit increases due to higher margin
TACOS decreases (better efficiency)

Scenario 2: COGS increases by 20%
Net margin decreases
Break-even ad spend reduces

Scenario 3: Organic growth increases to 3500 units
TACOS drops significantly
Business becomes healthier

Scenario 4: Price drops to ₹700
Margin compression occurs
ACOS tolerance reduces


📌 KEY INSIGHT

This model shows that:

Profitability depends more on unit economics than ad spend
TACOS is a better long-term health indicator than ACOS
Organic growth reduces dependency on ads

📎 GOOGLE SHEET LINK

https://docs.google.com/spreadsheets/d/1q8LsIW249sfNMAHrZtF4U7L8LIoiFlkFNbq8LTh84J0/edit?usp=sharing


