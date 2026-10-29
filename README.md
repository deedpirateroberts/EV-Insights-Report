# ⚡ EV Insights Report
## Electric Vehicle Market Performance & Insights

An interactive data-analytics project exploring electric-vehicle (EV) market data using **Tableau**. The project helps users compare manufacturers, vehicle categories, battery technologies, sales, driving range, customer ratings, model years, and manufacturing countries through visual dashboards.

<p align="center">
  <a href="https://public.tableau.com/app/profile/shreyam.richhariya/viz/EVMarketPerformanceInsights_17933009278830/Dashboard1?publish=yes">
    <strong>🔎 View the Interactive Tableau Dashboard</strong>
  </a>
</p>

---

## 📌 Project Overview

Electric-vehicle data can be difficult to explore in spreadsheet form alone. This project turns the dataset into visual summaries and comparisons, making it easier to investigate patterns across EV categories, manufacturers, battery types, and manufacturing countries.

### Project Goals

- Explore EV market data with interactive visualizations.
- Compare recorded sales across vehicle categories and manufacturers.
- Examine customer ratings and driving range.
- Explore battery technology and manufacturing-country distributions.
- Present key views in a Tableau dashboard and Story.
- Provide a simple Flask webpage to embed the published dashboard.

## 📊 Dataset

**File:** `ev_market_test.csv`

| Item | Details |
|---|---|
| Records | 100,000 rows |
| Columns | 37 |
| Format | CSV |

The dataset includes fields such as `vehicle_id`, `manufacturer`, `model_year`, `manufacturing_country`, `category`, `battery_type`, `range_km`, `price_usd`, `annual_sales_units`, and `customer_rating`.

> **Note:** Confirm these details against the actual dataset before relying on them. Check for missing values and validate fields before drawing conclusions.

## 📈 Dashboard Visualizations

The intended dashboard views include:

1. **Market Overview** — summary indicators for vehicle models, manufacturers, average driving range, and customer ratings.
2. **Sales by Category** — compares recorded annual sales across EV categories.
3. **Manufacturer Sales** — compares manufacturers by recorded annual sales.
4. **Customer Ratings** — compares ratings across categories.
5. **Sales by Model Year** — shows sales grouped by model year.
6. **Battery Technology** — explores sales distribution by battery type.
7. **Country Sales** — compares recorded sales by manufacturing country.

The published Tableau workbook is the source of truth for which views and features are currently implemented.

## 🧰 Tools & Technologies

- **Tableau Public / Tableau Desktop** — data visualization, dashboard, and Story.
- **CSV** — dataset format.
- **Python + Flask** — lightweight webpage for embedding the published Tableau dashboard.
- **HTML/CSS** — webpage structure and styling.

## 🌐 Interactive Dashboard

[**Open EV Market Performance & Insights on Tableau Public**](https://public.tableau.com/app/profile/shreyam.richhariya/viz/EVMarketPerformanceInsights_17933009278830/Dashboard1?publish=yes)

## 🖥️ Run the Flask Webpage Locally

These instructions apply if `app.py` and `templates/index.html` are included in the repository.

### 1. Install Python

Install Python 3 if it is not already installed.

### 2. Install Flask

Run this command in your terminal:

```bash
python -m pip install flask
```

On some Windows systems, use:

```bash
py -m pip install flask
```

### 3. Start the application

From the project folder, run:

```bash
python app.py
```

Or on Windows:

```bash
py app.py
```

### 4. Open the local webpage

Visit:

```text
http://127.0.0.1:5000
```

An internet connection is needed to load the published Tableau dashboard inside the webpage.

## 📁 Suggested Repository Structure

```text
EV-Insights-Report/
├── README.md
├── ev_market_test.csv
├── EV_Market_Performance_Project_Documentation.docx
├── app.py
└── templates/
    └── index.html
```

If you saved your Tableau workbook, you can include it too, preferably as a packaged workbook (`.twbx`). Use the actual filenames in your repository; remove any example files from this tree that you have not uploaded.

## ✅ Final Checklist

- [ ] Confirm the dataset filename, row count, and columns.
- [ ] Upload the Tableau workbook (`.twb` or `.twbx`) if available.
- [ ] Verify that the dashboard opens on Tableau Public.
- [ ] Test dashboard filters and chart labels.
- [ ] Test the Flask webpage locally, if included.
- [ ] Add the documentation and demonstration-video links when available.

## ⚠️ Notes

- The Tableau dashboard is publicly accessible. Do not publish confidential or personal data.
- A CSV connected directly to Tableau does not, by itself, satisfy a separate database/SQL requirement.
- Only describe database operations, data cleaning, performance tests, or deployment as completed if you actually performed them.
- The Flask instructions above run the app locally; public hosting requires a separate deployment step.

## 👤 Repository

[**deedpirateroberts/EV-Insights-Report**](https://github.com/deedpirateroberts/EV-Insights-Report)

---

*Built as an EV market data-visualization project using Tableau.*
