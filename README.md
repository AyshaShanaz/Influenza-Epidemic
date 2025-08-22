# Influenza-Epidemic-Case-Study

Overview

This case study explores the spread, severity, and temporal dynamics of an influenza epidemic using interactive storytelling in Tableau. The goal is to help public health stakeholders and students understand when, where, and how flu activity intensified and subsided across geographies and demographics.

Objectives

Identify peak influenza periods and compare them across regions.
Visualize geographic spread and hotspots over time.
Examine age or risk-group differences (where available) and hospitalization or mortality patterns.
Provide an interactive narrative to communicate findings to non-technical audiences.


Data Sources

CDC or national surveillance feeds for influenza-like illness (ILI) rates and lab-confirmed cases.
Hospital admissions and mortality records (aggregated) where available.
Population denominators from census data for rate normalization.
Tableau story: https://public.tableau.com/views/InfluenzaEpidemic/Story1

Methodology

Cleaning and harmonization of weekly surveillance data.
Rates per 100,000 using population denominators.
Time-series smoothing (clearly labeled where used).
Choropleth mapping and small multiples for regional comparison.
Story points guiding the reader from overview to drill-down.

Key Views and Interactions

Weekly timeline with highlighted peaks.
Geographic progression by week.
Comparative panels for regions and seasons.
Tooltips and filters (region, week, demographic segments where present).

Findings and Insights

Peaks clustered in winter with staggered timing across regions.
Early signals in urban centers, with lags in peripheral regions.
Severity did not always match case rates, indicating demographic and access differences.
Value of early-warning signals and inter-regional coordination.

Limitations

Under-reporting and testing variability.
Policy and testing changes across seasons.
Aggregation can obscure local outbreaks.


