📌 Project Overview
This project analyzes 204,130 state-level health records from the U.S. Chronic Disease Indicators dataset provided by the Centers for Disease Control and Prevention (CDC).
The goal was to transform public health data into a decision-intelligence framework that can support:
Workforce risk assessment
Geographic economic exposure modeling
Health system planning
Data-driven business strategy
Using Microsoft Excel and AI-assisted pattern extraction (Powerdrill AI), I built a multi-indicator normalization and clustering framework to identify structural chronic disease risk across U.S. states.
📊 Dataset
Source: CDC U.S. Chronic Disease Indicators (CDI)
Indicators: 115 total (19 chronic disease domains analyzed)
States/Territories: 50+
Records Analyzed: 204,130
Time Range: 2015–2022
The CDI dataset enables standardized cross-state comparisons of:
Chronic disease prevalence
Incidence rates
Social determinants of health
⚙️ Methodology
1️⃣ Indicator Normalization
The dataset includes heterogeneous units:
Percentages
Rates per 100,000
Raw counts
To ensure comparability:
Each disease topic was normalized to a 0–100 scale within its domain
This removed unit inconsistencies while preserving relative burden intensity
2️⃣ Composite Chronic Burden Score
For each state:
Averaged normalized scores across 19 disease domains
Produced a Composite Structural Burden Score
This enabled:
Direct cross-state comparison
Regional aggregation
Ranking and tier classification
Burden Score Range: 28.00 – 57.55
Mean Score: 41.70
Spread: 24.6× difference between lowest and highest burden states
➡️ Insight: Structural chronic exposure varies substantially across the U.S.
3️⃣ State Tier Classification (Risk Stratification)
States were clustered into three tiers:
Tier	# of States	Interpretation
High Burden	12	Elevated structural health risk
Medium Burden	22	Moderate systemic exposure
Low Burden	20	Lower relative burden
Regional Pattern Observed:
Southeast + parts of Midwest → Concentrated high burden
Western states → Predominantly low burden
Strategic Applications:
Geographic workforce cost modeling
Insurance risk pricing frameworks
Regional investment decision-making
4️⃣ Burden + Variability Risk Matrix
Beyond average burden, I calculated the coefficient of variation (CV) across states for each disease topic.
This created a systemic classification model:
Pattern	Interpretation	Strategic Response
High Burden + High Variability	Geographic hotspot risk	Targeted regional intervention
High Burden + Low Variability	National structural exposure	Standardized national policy
Moderate + Moderate	Mixed structural + geographic risk	Hybrid strategy
Key Insight:
Some extreme “hotspots” may reflect measurement fragmentation
Others represent true systemic national exposure
This distinction is critical before allocating capital or designing policy.
5️⃣ Comorbidity & Multi-Condition Clustering
State-level clustering revealed recurring disease bundles:
Cardiometabolic convergence (diabetes + cardiovascular disease)
Obesity + depression clustering in younger adults
Cholesterol + hypertension + arthritis triad in older populations
Research indicates multi-chronic patients experience:
6–14× higher hospitalization rates
Exponential cost increases per additional condition
💡 Business Implication:
Wellness and insurance models should target metabolic bundles, not siloed conditions.
6️⃣ Socioeconomic Overlay Modeling
Cross-analysis included:
Preventable disease burden
Social determinants & socioeconomic stress indicators
Findings show moderate-to-strong structural correlation:
Higher socioeconomic stress → Elevated preventable burden
Higher education & insurance coverage → Lower disease intensity
➡️ Structural policy variables may drive outcomes more strongly than individual behavior alone.
🔎 Key Insights
1. Structural Health Risk Is Uneven
There is a 24.6× spread in burden scores across states. Chronic disease exposure is geographically concentrated.
2. Workforce & Economic Risk Is Clustered
High-burden states face:
Higher healthcare cost exposure
Increased absenteeism & presenteeism
Elevated long-term disability probability
Health burden can function as a leading indicator of productivity drag.
3. Some “Hotspots” May Be Data Artifacts
High variability suggests potential surveillance inconsistencies.
Standardization should precede capital allocation.
4. Cardiometabolic Risk Is the Dominant Cluster
Diabetes, cardiovascular disease, obesity, and sleep-related risk form the strongest structural convergence pattern.
Integrated prevention yields higher ROI than disease-specific programs.
5. Social Determinants Act as Force Multipliers
Insurance gaps, income disparity, and education levels correlate with preventable burden intensity.
Structural interventions likely outperform behavior-only campaigns.
💼 Business Applications
Corporate Strategy Teams
Integrate burden scoring into geographic expansion decisions
Adjust workforce benefit allocation by regional exposure
Health Insurers
Risk-tier state pricing models
Deploy region-specific preventive care bundles
Public Policy Analysts
Identify structural vulnerability zones
Monitor burden score trendlines over time
🛠 Tools Used
Microsoft Excel (normalization, scoring, tier modeling)
Powerdrill AI (pattern extraction & clustering logic)
Data visualization dashboards (see included PDF)
📦 Deliverables
Full analytical PowerPoint (included in repository)
Composite scoring model
Tier classification framework
Regional distribution visualizations
Variability matrix model
🚀 Future Enhancements
K-Means clustering for unsupervised tier validation
PCA dimensionality reduction across 19 domains
Random Forest to identify strongest burden predictors
Time-series forecasting (burden trajectory)
Predictive modeling linking socioeconomic variables to burden shifts
🎯 Author Intent
This project demonstrates applied skills in:
Multi-variable normalization
Risk stratification
Geographic clustering
Variability modeling
Translating public datasets into business decision frameworks
It reflects an interest in Information Systems, AI-driven analytics, and data-driven strategy development.
