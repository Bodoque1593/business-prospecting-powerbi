# Business Prospecting & First Contact Analysis – Real Estate (Power BI) 🏢📞

This repository contains a **Power BI dashboard** designed to analyze the **early stages of the commercial funnel**, specifically focused on **prospecting activities and first-contact interactions** between vendors and potential clients.

It provides visibility into how effectively the commercial team is generating new business opportunities.

---

## 🎯 Business Objective

The real estate company needs to understand:

- How many **new potential clients** vendors are contacting
- How many leads complete a **successful first interaction**
- The amount of **potential m²** requested or explored
- Which **segments** (Premium / Medium / Standard) are more active at the prospecting level
- Which **areas or assets** the prospects are interested in:
  - Shopping Centers
  - Logistic Parks
  - Offices
  - Storage
- Which vendors are generating more early-stage opportunities
- How many prospects advance to the next stage vs. how many stay inactive

This dashboard focuses on the **top of the funnel**, where opportunities begin.

---

## 🗂️ Project Structure

```text
business-prospecting-powerbi/
│
├── report/
│   └── Prospecting-FirstContact.pbix   # Main Power BI report
│
├── images/
│   ├── prospecting-overview.png        # Key prospecting indicators
│   ├── prospecting-detail.png          # Detailed table (client, vendor, m²)
│   └── prospecting-funnel.png          # Optional funnel view
│
└── README.md

🔍 Key Metrics & Insights
🧩 Prospecting Overview

Total # of prospects generated

Successful first contacts

Potential m² requested by prospects

Leads by:

Segment (Premium / Medium / Standard)

Asset type (Shopping Centers, Logistics, Offices, Storage)

Vendor / Commercial agent

🧭 First Contact Analysis

How many prospects were actually contacted

Contact success rate (%)

Average response time (if available)

Follow-up needed vs. completed

📞 Lead Quality Indicators

Estimated m²

Client’s brand or company profile

Fit with property type

Prospect priority level

🏬 Asset Interest Distribution

Where prospects show more interest:

Shopping malls

Logistic parks

Office towers

Storage units

This helps commercial planning and resource allocation.

🔁 Prospecting Funnel

Typical stages:

Prospect Identified

First Contact Attempt

First Contact Successful

Discovery / Needs Identified

Forwarded to Commercialization

Shows leakage points in the earliest stages of the funnel.



🛠️ Tools & Techniques

Power BI Desktop

Relationship modelling (prospects, assets, segments, vendors)

DAX measures:

Contacts completed

Contact rate

Potential m²

Vendor comparison

Slicers for asset, segment, vendor, date, and contact status

Excel / CSV

Data extracted from CRM or prospecting logs

Power Query for cleaning and shaping the data

