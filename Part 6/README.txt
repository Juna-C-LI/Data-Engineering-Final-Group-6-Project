Vehicle Emissions, Demand, and Revenue Dashboard

Folder Structure

dashboard-business-model/
│
├── streamlit_dashboard.py
├── business_model.py
├── requirements.txt
├── Canada_JP_SUV_FILLED_FINAL_v2.xlsx
│
└── business_outputs/
    ├── executive_kpis.csv
    ├── japanese_suv_business_model_output.csv
    ├── brand_summary.csv
    ├── cluster_profile.csv
    ├── top10_brand_share.csv
    ├── top10_business_index.png
    ├── brand_business_index.png
    ├── engine_vs_co2.png
    ├── avg_co2_by_brand.png
    ├── price_vs_co2_clusters.png
    ├── cluster_positioning_map.png
    └── underperforming_brands.png


Link to dashboard:  


Overview

In Part Six of our research report, the modelling approach, we developed an interactive dashboard for customers, researchers, and high-level decision-makers to explore the commercial and environmental performance of Japanese SUV brands in the Canadian market.

This dashboard presents the results of our business-oriented vehicle analysis using the updated Japanese SUV dataset. The dashboard combines business scoring, clustering analysis, and visual portfolio diagnostics to show how price, CO2 emissions, and engine size shape vehicle competitiveness.

The primary objective of the dashboard is to translate analytical results into a management decision-support tool. Rather than presenting the project as a purely technical modelling exercise, the interface helps users identify the strongest-performing Japanese vehicles, compare brand positioning, and understand why some brands underperform relative to their peers.

The system therefore moves from vehicle-level specifications to strategic business insight for customers and stakeholders.

Dashboard Purpose

The dashboard is designed around two audiences.

1. Business customers and high-level stakeholders

These users need concise, visual, decision-focused outputs. For this reason, the dashboard highlights:

Best Japanese car by business index

Lowest CO2 Japanese brand

Most price-competitive brand

Worst underperforming brand

Number of market clusters identified

It also presents portfolio-level visuals that show which brands are strongest, which vehicles offer the best value, and which segments may create commercial or environmental risk.

2. Academic reviewers and professors

These users may want access to the underlying model logic, processed data, clustering outputs, and ranking methodology. For that reason, the dashboard also includes dedicated sections with the cleaned data tables, scoring outputs, brand summaries, and cluster profiles.

Key Insights

The modelling results show that:

Price and CO2 emissions are the most important commercial screening variables in the current business model.

A weighted business index can identify the strongest Japanese SUVs by balancing affordability, lower emissions, and smaller engine size.

KMeans clustering helps explain underperformance by grouping vehicles with similar commercial and environmental characteristics.

Some brands underperform not because of one isolated model, but because of broader portfolio patterns such as higher average CO2, weaker price competitiveness, or larger engine sizes.

Portfolio composition matters. Brand-level performance changes depending on how many vehicles fall into stronger or weaker business clusters.

Dashboard Sections
Executive KPIs

This section gives a high-level management summary of the strongest and weakest performers in the dataset.

Portfolio Performance

This section shows average business index by brand and brand share within the top-ranked vehicles.

Efficiency and Emissions

This section focuses on engine size, CO2 emissions, and average emissions by brand.

Commercial Competitiveness

This section shows price versus CO2 positioning and the cluster-based market map.

Underperformance Diagnosis

This section identifies likely reasons for weak brand performance, such as high CO2, high price, or large engine size.

Professor Data Room

This section contains the supporting tables, ranking outputs, cluster summaries, and underlying processed data for academic review.

Closing
The Japanese SUV Business Performance Dashboard was developed as an interactive decision-support tool within the modelling approach section of this project. Using the updated Canadian market dataset, the dashboard evaluates Japanese SUV brands through a business-oriented framework based on price, CO2 emissions, and engine size. A weighted business index is used to rank vehicles, while KMeans clustering is applied to explain why certain brands underperform relative to peers. The dashboard is designed for both business stakeholders and academic reviewers, with executive-level visuals for strategic interpretation and detailed analytical tabs for methodological transparency.
