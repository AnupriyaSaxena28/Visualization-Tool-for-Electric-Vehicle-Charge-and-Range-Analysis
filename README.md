# Visualization-Tool-for-Electric-Vehicle-Charge-and-Range-Analysis

**Project Title
**

Electric Vehicle Charge & Range Analysis

**Project Overview
**
1. EV Growth

Electric Vehicles (EVs) are rapidly transforming the automotive industry due to advancements in battery technology, increasing environmental awareness, and government support for sustainable transportation. As EV adoption grows, efficient charging infrastructure, battery performance monitoring, and cost analysis become essential for long-term scalability.

2. Need for Data Analytics

The EV ecosystem generates large amounts of data related to charging usage, battery efficiency, driving range, and pricing. Data analytics helps convert this raw data into meaningful insights, enabling better grid management, fleet optimization, and informed consumer decisions. Visualization tools like Tableau make it easier to analyze trends and patterns effectively.

3. Project Goal

This project aims to develop an interactive Electric Vehicle Charge and Range Analysis system using SQL, Tableau, and Flask. The system focuses on:

Analyzing charging patterns and infrastructure usage

Evaluating battery performance vs driving range

Comparing EV models based on efficiency, cost, and features

The final solution integrates database management, data visualization, and web deployment to support data-driven decision-making in the EV domain.

**Scenarios Covered
**

Charging Pattern & Usage Analysis

Battery Performance vs Driving Range

Comparative EV Model Efficiency

**Tech Stack
**

SQL

Tableau Desktop

Python (Flask)

Google Colab

**Project Structure
**

EV-Charge-Range-Analysis/

│

├── dataset/

│   ├── raw_data/                     # Original CSV files

│   └── cleaned_data/                 # Cleaned datasets used for SQL

│

├── notebooks/

│   └── data_cleaning.ipynb           # Colab notebook for validation & preprocessing

│

├── sql/

│   ├── create_database.sql           # Database creation script

│   ├── create_tables.sql             # Table schema definitions

│   └── data_import.sql               # Data import queries

│

├── tableau/

│   ├── EV_Dashboard.twb              # Tableau workbook

│   ├── EV_Dashboard.twbx             # Packaged workbook

│   └── screenshots/                  # Dashboard & story screenshots

│

├── flask_app/

│   ├── app.py                        # Main Flask application

│   ├── templates/                    # HTML files

│   ├── static/                       # CSS / JS / assets

│   └── requirements.txt              # Python dependencies

│

├── documentation/

│   ├── data_understanding.md         # Dataset explanation

│   ├── architecture.md               # Technical architecture

│   └── performance_testing.md        # Performance analysis notes

│

├── README.md                         # Project overview & instructions

└── .gitignore                        # Ignored files

**Dashboard Features
**

Heatmaps

Price vs Range graphs

Efficiency comparisons

Filters & calculated fields

Web Integration

Explain Flask embedding.

**Future Enhancements
**

Real-time charging data

Live API integration

Predictive modeling
