Executive Summary
This project transforms 204,130 public health records from the Centers for Disease Control and Prevention Chronic Disease Indicators dataset into a state-level structural risk intelligence framework.
Rather than treating health data as purely epidemiological, this model reframes chronic disease burden as a leading indicator of workforce cost, economic drag, and regional investment risk.
The output is a normalized, tiered, and variability-adjusted decision model suitable for consulting, corporate strategy, insurance, and public-sector analytics applications.
Business Problem
Chronic disease is one of the largest structural cost drivers in the U.S., but:
Risk exposure varies significantly by geography
Disease indicators use inconsistent measurement units
Public datasets are not packaged for strategic decision-making
Objective:
Convert heterogeneous public health data into a standardized, decision-grade comparative framework.
Dataset
Source: CDC U.S. Chronic Disease Indicators (2015–2022)
Records Analyzed: 204,130
Indicators: 115 (19 domains consolidated)
Geographic Scope: 50+ states & territories
Domains include cardiometabolic disease, respiratory conditions, behavioral risk factors, and socioeconomic determinants.
Analytical Framework
1️⃣ Indicator Normalization
Problem: Mixed units (%, rates per 100k, counts) prevent comparison.
Solution:
Normalized each domain to a 0–100 scale
Preserved relative intensity while eliminating unit distortion
Enabled cross-state comparability
2️⃣ Composite Structural Burden Score
For each state:
Aggregated normalized scores across 19 domains
Produced a Composite Chronic Burden Index
Results:
Score range: 28.00 – 57.55
Mean: 41.70
24.6× spread between lowest and highest burden states
➡️ Indicates major structural exposure differences across regions.
3️⃣ Tier-Based Risk Stratification
States classified into three tiers:
Tier	Count	Interpretation
High Burden	12	Elevated structural cost exposure
Medium Burden	22	Moderate systemic exposure
Low Burden	20	Lower relative risk
Geographic Insight:
Southeast & parts of Midwest → Concentrated high-burden cluster
Western states → Predominantly low-burden
Consulting application:
Regional expansion risk modeling
Workforce cost forecasting
Insurance pricing segmentation
4️⃣ Burden + Variability Matrix (Systemic vs. Localized Risk)
Beyond averages, I introduced a Coefficient of Variation (CV) layer to assess dispersion across states.
Pattern	Strategic Meaning
High Burden + High Variability	Localized hotspot risk
High Burden + Low Variability	National structural exposure
Moderate + Moderate	Mixed systemic + regional risk
Key consulting insight:
Not all “hotspots” represent real epidemiological differences.
Some reflect data fragmentation or reporting inconsistency.
Capital allocation decisions should distinguish between structural and artifact-driven risk.
5️⃣ Comorbidity Convergence Modeling
Cluster analysis revealed recurring disease bundles:
Cardiometabolic cluster (diabetes + CVD + obesity)
Mental health + obesity in younger populations
Hypertension + cholesterol + arthritis in aging populations
Multi-condition patients show:
6–14× higher hospitalization rates
Exponential cost escalation
Strategic takeaway:
Integrated prevention models outperform single-condition programs.
6️⃣ Socioeconomic Overlay Analysis
Cross-analysis of burden scores with socioeconomic stress indicators revealed:
Higher stress → Higher preventable burden
Higher education & insurance coverage → Lower burden intensity
Implication:
Structural socioeconomic variables may be stronger drivers of health cost exposure than individual behavior alone.
Key Consulting Insights
1. Health Burden Is an Economic Signal
Chronic disease intensity can serve as a proxy for:
Workforce productivity drag
Healthcare cost escalation
Long-term disability exposure
2. Geographic Risk Is Clustered, Not Random
Burden concentration suggests structural regional inequities that impact:
Insurance markets
Employer benefit design
Public spending allocation
3. Variability Matters as Much as Mean
Decision-makers must differentiate:
Systemic nationwide exposure
Localized volatility
Measurement artifacts
This model introduces dispersion-adjusted risk interpretation.
Applications
Corporate Strategy
Geographic expansion modeling
Benefit cost exposure forecasting
Location-based workforce risk scoring
Insurance & Healthcare
Risk-tier premium structuring
Preventive care bundle deployment
Market segmentation
Public Sector
Structural vulnerability mapping
Resource prioritization
Trend monitoring frameworks
Tools & Technical Stack
Microsoft Excel (data cleaning, normalization, scoring, clustering logic)
Powerdrill AI (pattern extraction, analytical synthesis)
Statistical dispersion metrics (Coefficient of Variation)
Future Technical Extensions
K-Means clustering validation
PCA for dimensionality reduction
Random Forest feature importance modeling
Time-series burden forecasting
Predictive modeling linking socioeconomic shifts to burden changes
What This Demonstrates
This project showcases:
Multi-variable normalization under heterogeneous units
Risk stratification & tier modeling
Variability-adjusted interpretation
Translation of public data into strategic intelligence
Business framing of epidemiological data
