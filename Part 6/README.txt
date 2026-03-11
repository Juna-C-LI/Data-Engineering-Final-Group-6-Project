Vehicle Emissions, Demand, and Revenue Dashboard

Link to dashboard: https://gjeddesedzrnx2vjjwve8s.streamlit.app/     

Folder Structure

dashboard-data-engineering/
│
├── app.py
├── build_outputs.py
├── requirements.txt
├── CO2 Emissions_Canada(1).csv
│
└── dashboard_outputs/
    ├── cleaned_data.csv
    ├── emissions_results.csv
    ├── demand_results.csv
    ├── revenue_results.csv
    ├── emissions_sample_predictions.csv
    ├── demand_sample_predictions.csv
    ├── revenue_sample_predictions.csv
    ├── emissions_feature_importance.csv
    ├── demand_feature_importance.csv
    ├── revenue_feature_importance.csv
    ├── scenario_results.csv
    └── summary_metrics.csv

Overview

In part six of our research report, known as our modelling approach, we created an interactive dashboard for researchers and our customers to interact with to better understand the data and results that we are working with.

This interactive dashboard presents the modelling results developed for the Vehicle Emissions and Scenario Analysis project. The dashboard integrates machine learning models with scenario simulation tools to explore how vehicle engineering characteristics influence environmental performance, market demand, and revenue outcomes.

The primary objective of the dashboard is to translate model outputs into a visual decision-support tool. The interface allows users to explore model performance, compare prediction accuracy, and test how different vehicle production mixes affect fleet-level outcomes.

The system therefore moves from vehicle-level engineering attributes to strategic insights for our customers

Key Insights

The modelling results demonstrate that:

• Vehicle engineering characteristics strongly influence emissions outcomes
• Ensemble machine learning models outperform linear regression approaches
• Certain vehicle classes can achieve lower emissions while maintaining strong demand
• Portfolio composition can significantly influence fleet-level environmental performance
