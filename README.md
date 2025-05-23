# 🚗 Car Sales & Weather Analysis Dashboard - Power BI Project

## 📌 Project Overview

This project presents a comprehensive **Power BI Dashboard** that analyzes car sales performance alongside weather indicators to uncover patterns that may impact business decisions. It combines internal sales KPIs with external environmental data to enable data-driven strategies.

The data was cleaned and processed using **Python** and **Excel**, and visualized using **Power BI** with interactive dashboards, slicers, and drill-downs.

## 📊 Dashboards Overview

### 1. **Sales Overview Dashboard**
Provides an in-depth view of:
- **Total Profit**: $78M  
- **Total Quantity Sold**: 58K  
- **Average Profit per Sale**: $7.84M  
- **Monthly Trends**: Profit and Quantity Sold by Month  
- **Regional Performance**: Profit and Quantity by City  
- **Product Analysis**: Sales by Car Model  
- **Interactive Map**: Customer Contacts by City  
- **Dynamic Slicers**: Model, Contact Name  

### 2. **Weather Indicators Follow-up Dashboard**
Highlights how weather variables may influence buying behavior:
- **Average Wind Speed**: 11.24 mph  
- **Average Visibility**: 8.12 mi  
- **Average Humidity**: 62%  
- **Average Temperature**: 52.21°F  
- **Weather Breakdown**:  
  - Rainy vs Dry Days  
  - Foggy vs Clear Days  
  - Snowy vs Snow-Free Days  
- **Seasonal Trends**: Temperature across quarters  
- **Slicers**: City, Date Range, Weather Condition, Wind Direction  

### 3. **Key Influencers Dashboard – Dealers & Weather**
Uses **AI-driven Key Influencers Visual** to uncover the top variables impacting unit sales and profit:
- Key variables include: Temperature, Humidity, Wind Speed, City, Car Model, and Weather Conditions  
- Left pane: Top influencing factors ranked by significance  
- Right pane: Bar chart comparing influence across categories  
- Built for interpretability and strategic planning  

![Key Influencers Dashboard](file-WK88GK6vknZK9WGiHUwe71)

### 4. **Car Recalls Dashboard**
Monitors product recalls and affected systems:
- **Total Units by Model**  
- **Total Units by Affected System** (e.g., Airbag, Suspension, Engine)  
- **Trend by Month**  
- **Table View**: Includes Car ID, Quarter, System Affected, Unit Count  
- Dynamic slicers: Model, Affected System  

![Car Recalls Dashboard](file-1GxJGVxYitQWvxgifN3gaZ)

## 📐 DAX Measures

### Sales Metrics
- `Total Profit`  
- `Total Quantity Sold`  
- `AVG Profit Per Sale`  
- `%GTT Sum of Quantity`  
- `%GTT Sum of Profit`  
- `Profit by City`  
- `Quantity Sold by City`  
- `Profit by Model`  
- `Quantity Sold by Model`  
- `Profit by Month`  
- `Quantity by Month`

### Weather Metrics
- `AVG Wind Speed`, `AVG Visibility`, `AVG Humidity`, `AVG Temperature`  
- `AVG Precipitation`, `Max/Min Humidity`, `Max/Min Temperature`  
- `Max/Min Precipitation`, `Max/Min Visibility`, `Max/Min Wind Speed`  
- `Correct Humidity`, `Ideal Wind Speed`, `Ideal Visibility`  
- `Ideas Humidity`, `Ideas Temperature`, `Ideas Precipitation`  

## 🧹 Data Cleaning & Transformation (Python)

Data preparation was performed using **Jupyter Notebook** with the following Python libraries:

- `pandas`: for data manipulation and cleaning  
- `numpy`: for numerical operations  
- `matplotlib` & `seaborn`: for exploratory data visualization and insights validation  

### Key Cleaning Steps:
- Handled missing values  
- Converted data types  
- Created new features  
- Exported cleaned data to Excel/CSV for use in Power BI  

**Notebook file**: `Phones_Cleaning.ipynb`

## 📁 Project Files

- `Phones_Cleaning.ipynb` – Python data cleaning script  
- `car_sales_raw.xlsx` – Raw data  
- `car_sales_cleaned.xlsx` – Cleaned data  
- `Car_Dashboard.pbix` – Power BI report file  
- `README.md` – Project documentation  

## 🚀 Business Insights & Value

This solution helps stakeholders:
- Identify top-performing car models and cities  
- Monitor profit and sales trends over time  
- Explore how weather impacts purchasing behavior  
- Combine internal and external data for strategic decision-making  

## 🧠 Future Enhancements

- Add ML-based sales forecasting using regression models  
- Integrate real-time weather API for dynamic analysis  
- Create drill-through pages for customer segmentation and dealership performance  

## 📬 Contact

**Mahmoud Elzayat**  
Email: mahmoudelzeiat7@gmail.com  
LinkedIn: [linkedin.com/in/mahmoud-elzayat-data-analysis](https://www.linkedin.com/in/mahmoud-elzayat-data-analysis)
