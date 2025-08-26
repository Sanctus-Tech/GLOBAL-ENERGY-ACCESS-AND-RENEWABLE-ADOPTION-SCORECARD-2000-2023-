# Global Energy Access & Renewable Adoption Scorecard (2000–2023)

##  Introduction

This project analyzes **global progress in energy access and renewable adoption between 2000–2023**, highlighting success stories, bottlenecks, and future challenges. The study examines how different countries are advancing toward universal electricity access, reducing energy intensity, and adopting renewables as part of their sustainable energy transitions.

---

##  Background

Energy access and renewable adoption are critical pillars for achieving **Sustainable Development Goal 7 (Affordable and Clean Energy)**.

* Many countries still struggle with electricity access below 50%.
* Others have improved rapidly but face **rising energy intensity**, which threatens sustainability.
* At the same time, renewable adoption varies significantly, shaping countries’ **CO₂ trajectories** and energy security.

By tracking access growth rates, renewable penetration, and efficiency indicators, this project identifies:

* **Top improvers** in energy access
* **Countries at risk of stalling progress**
* **Policy bright spots** where efficiency gains accompany access growth
* **Links between renewable adoption and CO₂ reduction**

---

##  Tools Used

* **PostgreSQL** → Data extraction, cleaning, and query-based analysis (SQL scripts provided).
* **Power BI** → Interactive dashboards and visualizations.
* **World Bank WDI Dataset** → Indicators:

  * `EG_ELC_ACCS_ZS` (Electricity Access %)
  * `EG_FEC_RNEW_ZS` (Renewable Energy Share of Final Consumption %)
  * `EG_EGY_PRIM_PP_KD` (Energy Intensity – MJ per \$2017 PPP GDP)
  * `EN_GHG_CO2_PC_CE_AR5` (CO₂ Emissions per Capita)

---

##  Analysis

### 1️⃣ Track Energy Access CAGR (2000–2023)

* Calculated **Compound Annual Growth Rate (CAGR)** in access.
* Identified **Top 15 Improvers** (e.g., Timor-Leste, Nepal, Bangladesh, Rwanda).
* Insight: Small economies with donor-backed electrification programs often outperform larger peers.

### 2️⃣ Compare Renewables Adoption vs Energy Intensity

* Cross-analyzed **renewable energy share vs energy intensity** in 2022.
* Found that countries like **Bhutan, Burundi, and Burkina Faso** lead in renewable share while maintaining relatively **low energy intensity**.
* Insight: Renewable-heavy systems can also be efficient, but not always (e.g., some islands adopt renewables but remain energy-intensive).

### 3️⃣ Countries Below 50% Access – Years to 90%

* Estimated years required for lagging countries to reach **90% access at current CAGR**.
* Example: **Papua New Guinea** needs \~68 years, while **Chad** may need \~35 years.
* Insight: Current pace is insufficient—many Sub-Saharan nations risk missing **SDG7 targets**.

### 4️⃣ CO₂ Trajectories – High vs Low Renewable Adopters

* Compared **CO₂ emissions per capita trends** for countries with ≥30% renewables vs <30%.
* Result: High adopters show **slower or declining emissions**, while low adopters continue rising.
* Insight: Renewables adoption correlates with **flattening CO₂ curves**.

### 5️⃣ Policy Bright Spots – Rising Access + Falling Energy Intensity

* Countries like **Afghanistan, Cambodia, Bhutan, Rwanda** improved access **while reducing/stabilizing energy intensity**.
* Insight: These are **case studies for decoupling growth from energy use**.

### 6️⃣ Country Watchlist – Stalled Progress

* Identified countries with **stalled/negative access growth in the last 5 years**.
* Examples: **Afghanistan (-6.8%), Syria, Nigeria, Yemen**.
* Insight: Conflict and weak infrastructure investment are major barriers.

---

##  What I Learned

* **Energy transitions are uneven** – while some regions move quickly, others are decades behind.
* **CAGR-based forecasting is powerful** for estimating future progress but exposes huge disparities.
* **High renewable adoption aligns with lower CO₂ intensity**, though not universally.
* **Energy access is not enough**—intensity and efficiency must also improve to ensure sustainability.
* **Data visualization in Power BI** enhances communication of complex global comparisons.

---

##  Conclusions

* Several countries are on track to achieve **near-universal energy access**, but many will miss SDG7 without **accelerated investments**.
* Renewable adoption is proving essential for **sustainable growth and CO₂ reduction**.
* Policymakers should focus on **countries stuck below 50% access** and those **stalled in the last 5 years**.
* A few **bright spots** show it is possible to **expand access while reducing intensity**, offering **policy lessons for others**.
* The global challenge remains significant: without **targeted interventions**, energy inequality will persist well beyond 2030.

