🏥 Hospital General Information Analysis (CSM Project)
---
📌 Overview
---
This project explores hospital-level data from the CSM Hospital General Information dataset. The goal was to clean, structure, and analyze hospital service availability and performance indicators using Python, SQL, and Tableau. The project culminates in an interactive dashboard designed to highlight key insights for data-driven decision-making.

🎯 Objectives
---
Clean and prepare hospital data for analysis

Load and query the dataset using PostgreSQL

Visualize hospital features such as location, service availability, and ratings

Build a shareable dashboard with filters and state-level summaries

🛠️ Tools & Technologies
---
Python (in Visual Studio Code) – for data cleaning and preprocessing

PostgreSQL – for storing and querying structured data

SQL – for extracting relevant subsets of data

Tableau Public – for interactive dashboard creation

GitHub – for project documentation and version control

📁 Dataset
---
Source: CSM Hospital General Information Dataset

Key Fields Used:

Facility ID, Facility Name, City, State

Hospital Type, Emergency Services

Overall Rating, Birthing-Friendly status

🧹 Data Preparation Steps
---
Raw Data Cleaning:

* Handled missing values, standardized categorical fields

* Reformatted columns for consistent schema

Database Integration:

* Loaded the cleaned dataset into PostgreSQL

* Used SQL queries to filter and transform the data for analysis

Visualization:

* Imported refined datasets into Tableau

* Built an interactive dashboard to explore hospital characteristics

📊 Dashboard Highlights
---
The Tableau dashboard provides a comprehensive visual summary of hospital characteristics across the U.S. using state-level and facility-level data. Key features include:

Bar Chart: Displays the average overall rating of hospitals by state, including Washington D.C. and U.S. territories. States are color-coded based on rating from low (red) to high (blue).

Summary Metrics:

* Average hospital rating across the dataset

* Percentage of hospitals with Birthing-Friendly (BF) designation

* Percentage of hospitals offering Emergency Services (EMS)

Pie Charts: Show distributions of hospitals that provide birthing services or emergency care.

Map Visualizations:

* A choropleth map showing average hospital rating by state

* A dot map of all U.S. hospitals with color-coded service combinations:

  * Birthing-Friendly only

  * Emergency only

  * Both

  * Neither

Interactive Filters:

* State selector to drill down into individual state-level insights

* Legend filter to toggle hospital service combinations on the map

These visual elements allow users to quickly identify geographic patterns in hospital quality and service availability.

📷 Dashboard Preview
---
<img width="1919" height="1001" alt="image" src="https://github.com/user-attachments/assets/02cf4ca7-d5f0-4c5e-8c08-9440d7f8ecbd" />


🔗 View the Dashboard
Check out the interactive Tableau dashboard here:
👉 [Tableau Public Link](https://public.tableau.com/app/profile/david.jian4862/viz/Medicare_Hospital_Dashboard/Dashboard2?publish=yes)

📜 License
---
This project is licensed under the MIT License. Feel free to use or adapt the work with proper attribution.

📬 Contact
---
For questions or collaborations:

📧 [koifish.analytics@gmail.com]

💼 [LinkedIn](https://www.linkedin.com/in/davidjian00/)
