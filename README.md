#  Global Terrorism Analysis Dashboard Report


![global](https://github.com/user-attachments/assets/f98b090d-ba6b-4b64-8f1b-4e7d1d401dc2)

#  Global Terrorism Analysis Dashboard (1970–2017)

> **Role:** Data Analyst | **Tools:** SQL Server · Power BI · DAX · Excel | **Domain:** Security Analytics · Policy Research

---

##  Project Overview

Analyzed **96,000+ terrorism records spanning 47 years (1970–2017)** to uncover patterns in attack types, regional distribution, terrorist group activity, and weapon usage. The interactive Power BI dashboard transforms large, unstructured historical data into **actionable intelligence** — supporting informed decision-making by security professionals, policymakers, and researchers.

---

##  Business Problem

Terrorism intelligence is often trapped in large, unstructured datasets making it difficult to:

- Detect **regional hotspots** and high-risk zones
- Identify the **most lethal terrorist groups** and their methods
- Track **year-over-year attack trends** and peak periods
- Understand which **target types** face the greatest threat
- **Allocate security resources** effectively based on evidence

---

## Key KPIs & Scale

| Metric | Value |
|---|---|
| Total Records Analyzed | 96,000+ |
| Time Period Covered | 1970 – 2017 (47 years) |
| Peak Attack Year | 2017 |
| Most Deadly Group | Taliban |
| Most Used Weapon | Explosives |
| Highest Risk Region | South Asia |
| Most Targeted Group | Civilians and Government Entities |
| Highest Success Rate Methods | Bombings and Armed Assaults |

---

##  Key Findings

### Most Deadly Groups
- **Taliban** identified as the most deadly group based on attack count and success rate
- **ISIS** and **Boko Haram** also show consistently high success rates
- Group profiling reveals distinct geographic footprints and preferred attack methods

### Attack Trends Over Time
- **2017 recorded the highest number** of global terrorist attacks in the dataset
- Post-2010 shows a sharp escalation in attack frequency globally
- Historical trend modeling can predict future hotspots based on regional escalation patterns

### Weapon and Attack Methods
- **Explosives** are the most commonly used weapon — preferred for high-impact, high-casualty attacks
- **Bombings and armed assaults** have the highest success rates across all regions
- Weapon preference varies significantly by group and geographic region

### Regional Impact
- **South Asia** experiences the most frequent and successful attacks globally
- **Middle East and North Africa** ranks second in attack frequency and severity
- High attack concentration in specific countries creates data imbalance requiring normalization

### Target Types
- **Civilians** are the most frequently targeted group across all regions and time periods
- **Government entities, police, and military** are also consistently high-priority targets
- Transportation and infrastructure attacks show increasing trend post-2010

---

##  Policy Recommendations

| Area | Recommendation |
|---|---|
| South Asia | Allocate more intelligence and prevention resources to the most affected region |
| Explosive Detection | Invest in advanced detection systems at high-risk civilian and government sites |
| Civic Protection | Reinforce security around civilians, police, and government officials |
| Predictive Modeling | Use post-2010 trend data to identify and prepare for emerging hotspots |
| Group Profiling | Develop detailed operational profiles for Taliban, ISIS, and Boko Haram |
| Resource Allocation | Redirect security budgets based on regional attack frequency and severity data |

---

##  Technical Approach

### SQL Server
- **Aggregations** — Count of attacks, average success rates, and total casualties by group and region
- **GROUP BY** — Regional, yearly, weapon-type, attack-type, and group-level breakdowns
- **JOINs** — Combined region metadata with attack records for enriched analysis
- **Date-Based Trend Analysis** — Yearly attack pattern identification and peak period detection
- **Data Cleaning** — Null value removal, categorical standardization, coordinate validation
- **Query Optimization** — Efficient handling of 96,000+ records with aggregation strategies

### Power BI
- **Interactive dashboard** with filters by region, year, group, weapon type, and target category
- **Map visual** for geographic attack distribution and regional hotspot identification
- **Time-series charts** for 47-year trend analysis and YoY comparison
- **Bar and donut charts** for group-wise, weapon-wise, and target-wise breakdowns
- **DAX measures** for success rate calculations, attack density, and YoY growth metrics

### Excel
- Initial data profiling and quality review
- Category standardization for weapon types and attack methods

---

##  Challenges Faced & Solutions

| Challenge | Solution |
|---|---|
| Data Imbalance — High attack frequency in certain countries skewed results | Applied normalization techniques for balanced regional comparison |
| Categorical Inconsistency — Weapon and attack type naming varied across records | Standardized all category labels through SQL CASE statements |
| Missing Coordinates — Incomplete location data impacted map visuals | Used only complete coordinate entries for geographic accuracy |
| Data Volume — 96,000+ records caused performance issues | Applied efficient aggregation strategies and query optimization |

---

##  Project Impact

This analysis can directly support:

- ✅ **Data-driven counterterrorism strategies** at national and international levels
- ✅ **Policy formulation** for security resource allocation in high-risk regions
- ✅ **Predictive modeling** frameworks to anticipate future threats
- ✅ **Journalism and research** — providing structured insight into global terrorism dynamics
- ✅ **Public safety planning** for civilian and infrastructure protection

---

##  Repository Structure

```
 Global-Terrorism-Analysis-Dashboard-Report
├── 📄 GlobalTerrorism_Analysis.sql        — Full SQL scripts and queries
├── 📊 GlobalTerrorism_Dashboard.pbix      — Interactive Power BI dashboard
├── 🖼️  Global terrorism Analysis Dashboard.jpg — Dashboard preview
├── 🖼️  global.jpg                          — Project cover image
└── 📄 README.md                           — Project documentation
```

---

##  Dashboard Preview

![Global Terrorism Analysis Dashboard](Global%20terrorism%20Analysis%20Dashboard.jpg)

---

## 👤 About

**Khurram Naveed** — Data Analyst specializing in SQL, Power BI, and business intelligence.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/khurramnaveed3233)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com/Khurramnaveed3233)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:khurramnaveed4545@gmail.com)

---

>  *This project demonstrates how advanced SQL querying combined with Power BI storytelling can transform 47 years of unstructured historical data into strategic intelligence — directly applicable to counter-terrorism policy, security planning, and academic research.*
