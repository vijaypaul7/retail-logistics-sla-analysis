📦 Retail Logistics SLA & Delivery Performance Analysis

Turning 10,998 shipment records into operational insights using Microsoft Excel.

⸻

🎯 Project Overview

This project explores retail shipment and delivery performance using Excel-based data analysis.

The goal was simple:

Start with raw shipment data → clean and organise it → analyse delivery performance → identify operational problem areas.

The analysis focuses on SLA performance, shipment weight, delivery delays, and shipment mode.

Rather than only reporting numbers, the project looks at what those numbers could mean from an operations and logistics perspective.

⸻

🏢 Business Questions

The analysis was designed around practical questions an Operations Manager might ask:

* 🚚 What percentage of shipments arrive on time?
* 📦 Which weight categories contain the most shipments?
* ⏱️ Which weight categories experience the highest delay rates?
* 🔎 Which segments contribute most to overall delays?
* 🚢 Does shipment mode provide additional context around delivery performance?
* ⚠️ Where should the operations team investigate first?

⸻

📊 Executive Snapshot

KPI	Result
Total Shipments	10,998
On-Time Shipments	59.67%
Delayed Shipments	40.33%
Largest Weight Category	Heavy — 54.25%
Heavy Shipment Delay Rate	56.8%
Heavy Share of All Delays	76.4%
Ship Share of Total Volume	67.85%
Heavy + Ship Share of All Delays	52.0%

🔴 Main finding

Heavy shipments are the clearest operational area requiring further investigation.

They represent 54.25% of total shipment volume, but account for 76.4% of all recorded delays.

⸻

📦 Shipment Distribution

The dataset contains three weight categories:

Weight Class	Shipments	Share
Heavy	5,966	54.25%
Light	3,245	29.51%
Medium	1,787	16.25%
Total	10,998	100%

Heavy shipments represent more than half of the total shipment volume.

This makes their delivery performance particularly important because even a moderate operational issue within this category can have a significant effect on overall SLA performance.

⸻

⏱️ SLA Performance by Weight

Weight Class	Late %	On-Time %
🔴 Heavy	56.8%	43.2%
🟠 Light	32.2%	67.8%
🟢 Medium	0.1%	99.9%

What stands out?

The difference between the categories is significant.

Heavy shipments:

* 5,966 total shipments
* 3,389 were late
* Only 43.2% arrived on time

Light shipments:

* 3,245 total shipments
* 1,046 were late
* 67.8% arrived on time

Medium shipments:

* 1,787 total shipments
* Only 1 recorded delay
* 99.9% arrived on time

The results identify Heavy shipments as the strongest concentration of observed delivery delays.

⸻

🚨 Where Are the Delays Coming From?

Of the 4,436 late shipments:

3,389 were Heavy shipments.

That means:

76.4% of all recorded delays came from Heavy shipments.

This is an important operational signal.

It does not prove that shipment weight causes delays.

Instead, it identifies Heavy shipments as a segment where further investigation could potentially produce the greatest operational value.

⸻

🚢 Shipment Mode Analysis

Shipment mode was analysed alongside shipment weight.

The three shipment modes were:

* ✈️ Flight
* 🚚 Road
* 🚢 Ship

Across the complete dataset, Ship represented approximately 67.85% of total shipment volume.

When analysing the late-shipment population, Heavy + Ship represented approximately 52.0% of all observed late shipments.

This highlights Heavy + Ship as an interesting segment for deeper investigation.

Possible areas for further analysis could include:

* Carrier performance
* Route
* Warehouse
* Shipment processing time
* Delivery network
* Product characteristics
* Customer-service interactions

⸻

🔍 Analytical Approach

The analysis was completed using Microsoft Excel.

Data Preparation

* Converted raw data into structured Excel Tables
* Reviewed and cleaned the dataset
* Applied filtering and segmentation
* Created calculated fields

Analysis

* Conditional formulas
* IF
* AND
* AVERAGEIFS
* PivotTables
* Shipment segmentation
* Percentage analysis
* KPI calculations

Business Analysis

The analysis moved through a simple workflow:

Raw Data
   ↓
Data Preparation
   ↓
Calculated Fields
   ↓
PivotTable Analysis
   ↓
Segmentation
   ↓
KPI Analysis
   ↓
Operational Insights

The emphasis was not simply on producing tables, but on using those tables to answer practical business questions.

⸻

💡 Business Interpretation

The strongest finding from this analysis is the concentration of delays within the Heavy shipment category.

Heavy shipments:

* Represent 54.25% of total volume
* Have a 56.8% delay rate
* Account for 76.4% of all recorded delays

This makes Heavy shipments a logical starting point for operational investigation.

However, the analysis only identifies an association.

It does not establish that weight itself causes delivery delays.

Additional analysis would be required to determine whether the observed pattern is related to factors such as shipment mode, carrier, route, warehouse operations, or other variables.

⸻

🎯 Recommended Next Steps

Based on the findings, a deeper analysis could focus on:

1. Investigate Heavy Shipments

Identify why Heavy shipments have substantially lower on-time performance.

2. Drill into Shipment Mode

Compare Flight, Road and Ship performance within each weight category.

3. Investigate Operational Drivers

Analyse whether warehouse, carrier, route or processing factors are contributing to delays.

4. Validate the Medium Result

The 99.9% on-time rate for Medium shipments is unusually high and should be validated against the source data before making strong operational conclusions.

5. Build a Management Dashboard

The next stage could transform these findings into an interactive Excel or Power BI logistics SLA dashboard.

⸻

🧠 What I Learned

This project helped develop practical skills in:

Excel

PivotTables · Excel Tables · IF · AND · AVERAGEIFS · Filtering · Calculated Columns · KPI Analysis

Data Analysis

SLA Analysis · Segmentation · Delay Analysis · Percentage Analysis · Operational KPI Analysis

Business Thinking

Business Question → Data → Metric → Segmentation → Finding → Recommendation

The most important lesson was that creating a calculation is only the beginning.

The real value comes from understanding what the number means for the business.

⸻

🛠️ Tools

Microsoft Excel

Used for:

* Data preparation
* Data cleaning
* Conditional calculations
* PivotTable analysis
* KPI development
* Operational segmentation

⸻

📸 Project Evidence

Selected screenshots from the analysis are available in the screenshots folder.

The screenshots demonstrate the underlying Excel analysis and PivotTable outputs used to produce the findings in this project.

⸻

📁 Repository Structure

retail-logistics-sla-analysis/
│
├── README.md
│
├── docs/
│   └── Retail_Logistics_SLA_Analysis.pdf
│
└── screenshots/
    ├── sla-overview.png
    ├── weight-performance.png
    └── logistics-insights.png

⸻

⚠️ Disclaimer

This is a portfolio analysis project created for learning and demonstration purposes.

The dataset and findings should not be interpreted as representing the performance of any specific real-world organisation.

The analysis identifies patterns and potential areas for investigation but does not establish causation.

⸻

🚀 Next Stage

From Excel analysis → deeper SQL analysis → Power BI dashboard → operational storytelling.
