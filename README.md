# E-commerce-Data-Analysis
**E-Commerce Database Analysis & Interactive Business Dashboard**

An end-to-end exploratory data analysis and interactive dashboard project in Python evaluating transactional retail data to identify revenue trends, seasonal sales patterns, category profitability, and product performance.

**Project Highlights**

* **Data Preprocessing & Date Engineering:** Cleaned column headers to standardized snake_case format, verified zero null values, and converted string timestamps into datetime features to extract `order_month`, `order_year`, and `Order_dayofweek`.

* **Temporal & Trend Analysis:** Aggregated monthly sales and profit trajectories with Plotly line charts, isolating peak demand windows (such as Q4 sales spikes in November/December).

* **Category & Donut Visualizations:** Computed market-share revenue across major departments (Technology, Furniture, Office Supplies) using interactive Plotly donut charts.

* **Sub-Category Sales Breakdown:** Evaluated granular product lines using ranked bar charts, highlighting top revenue drivers like Chairs and Phones versus lower-volume categories.

* **Profitability & Margin Analysis:** Compared top-line sales against net profits across product categories to pinpoint high-margin segments versus margin-compressed items.

**Tech Stack**

* **Language:** Python 3
* **Libraries:** Pandas, Plotly Express (`px`), Plotly Graph Objects (`go`), Plotly IO (`pio`)
* **Environment:** Jupyter Notebook

**Key Business Insights**

* **Seasonality:** Strong revenue surges in late Q3 through Q4, with peak monthly sales exceeding $350k in November.

* **Leading Categories:** Technology leads overall sales ($836k+) and total profit ($145k+), while Furniture experiences higher discount impact and lower relative margins.

* **High-Performing Sub-Categories:** Phones (~$330k) and Chairs (~$328k) generate the largest revenue shares across the entire product catalog.
