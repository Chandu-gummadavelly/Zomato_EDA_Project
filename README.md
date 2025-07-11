# Zomato Restaurant Data - Exploratory Data Analysis (EDA)

This project provides a comprehensive **Exploratory Data Analysis (EDA)** on the Zomato restaurant dataset. The primary goal is to extract meaningful insights about restaurant trends, customer behavior, and geographical patterns that can assist in business decisions or machine learning model development.

---

## Project Structure

- `zomato_EDA.ipynb`: Main Jupyter Notebook containing the entire EDA process.
- `zomato.csv`: Primary dataset with restaurant information.
- `Country-Code.xlsx`: Supplementary file mapping country codes to country names.
- `README.md`: This file.

---

## Project Objectives

- Understand the structure and characteristics of the Zomato dataset.
- Merge country information to enhance geographical insights.
- Identify trends in ratings, price range, popular cuisines, and delivery features.
- Visualize data for better interpretability using charts and graphs.
- Provide business and product-level insights for strategic applications.

---

## Steps Performed

### 1. Data Loading & Inspection
- Loaded `zomato.csv` using pandas.
- Inspected dataset with `.head()`, `.shape()`, `.info()`, `.describe()`.
- Identified missing values (especially in the `'Cuisines'` column).

### 2. Data Merging
- Merged `Country-Code.xlsx` with the main dataset using a left join on `'Country Code'`.

### 3. Geographical Distribution
- Analyzed restaurant spread across countries.
- India emerged as the country with the most Zomato entries.

### 4. Rating Analysis
- Explored `Aggregate rating`, `Rating color`, and `Rating text`.
- Identified countries with zero ratings, possibly indicating inactive markets.

### 5. Price Range Analysis
- Visualized restaurant cost categories.
- Found most restaurants fall into lower pricing tiers.

### 6. Cuisine and City Trends
- Identified most popular cuisines globally.
- Highlighted cities with the highest Zomato presence.

### 7. Online Delivery & Table Booking
- Analyzed availability of online delivery and table booking.
- Explored correlation between these features and ratings/prices.

### 8. Currency Analysis
- Mapped the types of currencies used in different countries.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Outcomes

- India dominates Zomato usage by volume.
- Most rated restaurants fall into the "Good" or "Very Good" category.
- Online delivery and table booking are popular features in high-demand cities.
- Price and cuisine preferences vary widely by region.

---

## Future Scope

- Use the cleaned dataset for **clustering cities** based on customer and restaurant behavior.
- Build **recommendation systems** using cuisine and rating patterns.
- Deploy interactive dashboards with **Plotly/Dash or Power BI**.

---

## Author

**Chandu GUMMADELLi**  
*Aspiring Data Scientist | Python Enthusiast | SQL Explorer*

---

## License

This project is for **educational and non-commercial use** only. All rights belong to the original data source (Zomato).
