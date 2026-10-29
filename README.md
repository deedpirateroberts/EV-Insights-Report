⚡ EV Insights Report
Electric Vehicle Market Performance & Insights
An interactive data-analytics project exploring electric-vehicle (EV) market data using Tableau. The project is designed to help users compare manufacturers, vehicle categories, battery technologies, sales, driving range, customer ratings, model years, and manufacturing countries through visual dashboards.
<p align="center">
  <a href="https://public.tableau.com/app/profile/shreyam.richhariya/viz/EVMarketPerformanceInsights_17933009278830/Dashboard1?publish=yes">
    <strong>🔎 View the Interactive Tableau Dashboard</strong>
  </a>
</p>
---
📌 Project Overview
Electric-vehicle data can be difficult to explore in spreadsheet form alone. This project turns the dataset into visual summaries and comparisons, making it easier to investigate patterns across EV categories, manufacturers, battery types, and manufacturing countries.
Project goals
Explore EV market data with interactive visualizations.
Compare recorded sales across vehicle categories and manufacturers.
Examine customer ratings and driving range.
Explore battery technology and manufacturing-country distributions.
Present key views in a Tableau dashboard and Story.
Provide a simple Flask webpage to embed the published dashboard.
📊 Dataset
File: `ev_market_test.csv`
Item	Details
Records	100,000 rows
Columns	37
Data format	CSV
The dataset includes fields such as `vehicle_id`, `manufacturer`, `model_year`, `manufacturing_country`, `category`, `battery_type`, `range_km`, `price_usd`, `annual_sales_units`, and `customer_rating`.
> **Data note:** The figures above describe the local dataset used for this project. Check the actual repository files and workbook before relying on these details. The dataset may contain missing values, so validate fields before drawing conclusions.
📈 Visualizations
The planned dashboard views include:
Market Overview — summary indicators for vehicle IDs, manufacturers, average driving range, and customer ratings.
Sales by Category — compares recorded annual sales across EV categories.
Manufacturer Sales — ranks manufacturers by recorded annual sales.
Customer Ratings — compares average customer ratings by category.
Sales by Model Year — shows sales grouped by vehicle model year.
Battery Technology — explores sales distribution by battery type.
Country Sales — compares recorded sales by manufacturing country.
The final published workbook is the source of truth for which views and features are currently implemented.
🧰 Tools & Technologies
Tableau Public / Tableau Desktop — data visualization, dashboard, and Story.
CSV — dataset format.
Python + Flask — lightweight webpage for embedding the published Tableau dashboard.
HTML/CSS — webpage layout.
🌐 Dashboard
Open the published dashboard:
EV Market Performance & Insights — Tableau Public
🖥️ Run the Flask Webpage Locally
These instructions apply if `app.py` and `templates/index.html` are included in the repository.
1. Install Python
Install Python 3 if it is not already installed.
2. Install Flask
```bash
python -m pip install flask
```
On some Windows systems, use:
```bash
py -m pip install flask
```
3. Start the application
From the project folder, run:
```bash
python app.py
```
On Windows, you can also run:
```bash
py app.py
```
4. Open the local webpage
Visit:
```text
http://127.0.0.1:5000
```
The webpage embeds the published Tableau view. You need an internet connection to load the dashboard inside the iframe.
📁 Suggested Repository Structure
```text
EV-Insights-Report/
├── README.md
├── ev_market_test.csv
├── EV_Market_Performance_Project_Documentation.docx
├── app.py
└── templates/
    └── index.html
```
If you have saved your Tableau workbook, consider adding it too:
```text
EV_Market_Performance_Insights.twbx
```
Use the actual filename of your workbook. Do not add a file to the README structure unless it is actually present in the repository.
✅ Validation Checklist
[ ] Confirm the dataset file and its columns.
[ ] Save and include the Tableau workbook (`.twb` or preferably `.twbx`).
[ ] Verify that the dashboard and Story open from Tableau Public.
[ ] Test dashboard filters and chart labels.
[ ] Test the Flask page locally if included.
[ ] Add the documentation and demonstration-video links when available.
⚠️ Notes
The Tableau dashboard is publicly accessible. Do not publish confidential or personal data.
A CSV connected directly to Tableau does not, by itself, satisfy a separate database/SQL requirement.
Only describe database operations, cleaning, performance tests, or web deployment as completed if you actually performed them.
The Flask instructions above run the app locally; public hosting requires a separate deployment step.
👤 Repository
GitHub repository: deedpirateroberts/EV-Insights-Report
---
Built as an EV market data-visualization project using Tableau.
