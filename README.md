# Prosthetic Access Atlas 🦾🗺️

An open-access data repository, research synthesis, and geospatial atlas dedicated to evaluating clinical trial developments, global research distribution, and rural geographic coverage gaps in prosthetic and orthotic care.

---

## 🎯 Mission

Access to modern prosthetic care remains deeply inequitable. While cutting-edge innovations—such as **Agonist-Antagonist Myoneural Interfaces (AMI)**, **osseointegration**, and **machine-learning electromyographic controllers**—are advancing rapidly in academic medical centers, millions of individuals in rural and historically underserved regions live in **"prosthetic deserts."**

The **Prosthetic Access Atlas** bridges evidence and geography by:
1. Aggregating and analyzing global clinical trial trends from **ClinicalTrials.gov**.
2. Quantifying geographic disparities and transit barriers in rural healthcare deserts (focusing on **Rural West Virginia**, **Eastern Kentucky**, and the **Mississippi Delta**).
3. Providing actionable blueprints for policy reform, mobile clinics, and decentralized open prosthetic technologies.

---

## 📂 Repository Structure

```
prosthetic-access-atlas/
├── README.md                               # Project overview and executive summary
├── data/
│   └── trials_summary.json                 # Structured dataset of ClinicalTrials.gov metrics & trials
├── analysis/
│   ├── clinical_trials_report.md           # Deep dive into global status, phases, and tech trends
│   └── geographic_gap_analysis.md          # Geospatial transit & coverage gap study (WV, KY, MS Delta)
└── recommendations/
    └── action_plan.md                      # Strategic roadmap: mobile clinics, telehealth, policy parity
```

---

## 📊 Key Findings Summary

### 1. Clinical Trials Landscape (ClinicalTrials.gov)
* **Dataset Scale:** 2,189 prosthetic clinical studies indexed globally.
* **Active Research Pipeline:** 689 studies (~31.5%) actively enrolling or preparing to enroll (379 Recruiting, 148 Not Yet Recruiting, 121 Active Not Recruiting, 41 Enrolling by Invitation).
* **Device vs. Drug Paradigm:** Over 88% of studies are classified as **Phase N/A** (1,279) or **Unknown** (654), reflecting medical device pathways (FDA 510(k), IDE, PMA) rather than classical 4-phase pharmaceutical trials.
* **Geographic Hegemony:** Extreme concentration in the Global North:
  * **Top 3:** United States (2,383 study site instances), France (825), Germany (533).
  * **Global South Deficit:** Sub-Saharan Africa and Southeast Asian low-income countries account for fewer than 0.2% of trials (e.g., Kenya: 2, Rwanda: 1, Indonesia: 1, Vietnam: 2).
* **Technological Frontiers:** Rapid growth in biological nerve-muscle interfaces (AMI/Ewing amputation), robotic emulators for personalized prescription, osseointegration eliminating sockets, and bidirectional closed-loop sensory feedback tactors.

### 2. Rural Coverage Gap Analysis (OSM Geospatial Routing)
* **Rural West Virginia (Central Appalachia):**
  * *Beckley, WV to Charleston Area Medical Center:* **94.5 km (58.7 mi)**, **75 min** driving one-way over winding mountainous terrain.
  * *Outlying Coal Counties (McDowell, Wyoming):* Frequently exceeds **2.5 hours one-way**, creating severe socket maintenance delays.
* **Eastern Kentucky (Cumberland Plateau):**
  * *Hazard, KY to Lexington / UK HealthCare:* **185.6 km (115.3 mi)**, **138 min (2.3 hours)** driving one-way along the Mountain Parkway.
  * Severe geographic isolation where 4.6-hour round trips lead to high prosthesis abandonment and secondary diabetic limb loss.
* **Mississippi Delta:**
  * *Clarksdale, MS to Regional Hub (Memphis, TN):* **121.3 km (75.4 mi)**, **98 min (1.63 hours)** driving one-way along US-61.
  * Highest per-capita diabetes and amputation rates in the United States, yet devoid of full-time, independent certified orthotic & prosthetic (O&P) facilities.

---

## 🚀 Getting Started & Contributing

Researchers, clinicians, and geospatial analysts are invited to contribute data, regional surveys, and open-source models:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/liang23333/prosthetic-access-atlas.git
   cd prosthetic-access-atlas
   ```
2. **Review the Data & Analyses:**
   * Explore `data/trials_summary.json` for machine-readable trial records.
   * Read `analysis/clinical_trials_report.md` for technological trajectories.
   * Inspect `analysis/geographic_gap_analysis.md` for road routing and transit metrics.
   * Check `recommendations/action_plan.md` for implementation frameworks.

---

## 📜 License & Citation

This project is released under the **Open Access Creative Commons Attribution 4.0 International (CC BY 4.0)** license. Feel free to use, share, and expand with attribution.
