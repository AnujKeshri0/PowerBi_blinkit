
 Blinkit Dashboard
 

## 📊 Problem Statement

The **Blinkit Dashboard** provides insights into customer preferences and sales performance across various items and outlets. By analyzing this data, Blinkit can identify areas for improvement, optimize inventory, and enhance customer satisfaction.

## 🔍 Key Insights

- **Customer Preferences:** Understand how item attributes affect sales.
- **Sales Performance:** Identify top-selling items and outlets.
- **Operational Improvements:** Optimize inventory based on sales trends and customer feedback.

## ⚙️ Steps Followed

### 1. Data Import
- Loaded data from a CSV file containing sales, item attributes, and outlet details.

### 2. Data Transformation
- **Duplicate Removal:** Ensured data integrity by eliminating duplicates.
- **Blank Value Filtering:** Cleared any blank entries for clean analysis.
- **Data Type Correction:** Adjusted data types for all relevant columns.

### 3. Data Quality Checks
- Verified the dataset for any remaining issues, focusing on key columns such as:
  - `item_fat_content`
  - `item_identifier`
  - `item_type`
  - `sales`

### 4. Visual Creation
- **Key Metrics Cards:**
  - Total Sales
  - Number of Unique Items
  - Average Items per Order
  - Average Sales per Item

![All](https://github.com/user-attachments/assets/da062f76-577b-4a2e-bc44-ccaf1e9b4140)



### 5. Sales Analysis Visuals
- **Fat Content Analysis:** Visualized total sales by `item_fat_content`.

![Fat Contain By Sales](https://github.com/user-attachments/assets/56cf20d9-a464-408a-aa2a-3d2d753854d9)


- **Line Chart:** Analyzed sales trends over time against `outlet_established_year`.

![Line Chart](https://github.com/user-attachments/assets/761bbd3f-8928-4924-921d-41e580f4c91f)


### 6. Total Sales Overview
- **Pie Chart:** Illustrated distribution of total sales by item category.

![Item Type By Sales](https://github.com/user-attachments/assets/2f9b3470-1dca-416c-ab48-c87c85a7b7ff)


- **Funnel Chart:** Displayed sales by `outlet_location_type` (Tier 1, Tier 2, Tier 3).

![Outlet Location](https://github.com/user-attachments/assets/9511c724-d98c-4ed5-bb93-bb45c126a8fa)


### 7. Matrix Visualization
- Analyzed:
  - Average Rating
  - Average Sales
  - Sales by `item_visibility`
  - Total Sales per `outlet_type`
![Slicer](https://github.com/user-attachments/assets/99057438-229b-4a85-85da-c6dfec91535f)


### 8. Interactivity Enhancements
- Added slicers for:
  - `item_type`
  - `outlet_location_type`
  - `item_fat_content`

  ![Slicer](https://github.com/user-attachments/assets/99057438-229b-4a85-85da-c6dfec91535f)


### 9. Theme Selection
- Chose an aesthetically pleasing yellow theme to enhance user experience.

### 10. Publication
- Published the finalized report to Power BI Service for stakeholder access.

## 📸 Snapshot of Dashboard

![Snapshot](https://github.com/user-attachments/assets/5a8207d3-be56-41c7-9002-db2b52518151)


## 📈 Insights

1. **Total Sales Overview:**
   - **Total Sales:** $1.20M
   - **Unique Items Sold:** 8523
   - **Average Items Sold per Order:** $140.99
   - **Average Sales per Item:** 3.9

2. **Fat Content Analysis:**
   - Sales performance varies by fat content, indicating customer preferences for healthier options.

3. **Sales by Outlet Type:**
   - Breakdown of total sales by outlet type, helping identify the best-performing locations.

4. **Customer Ratings:**
   - Average ratings provide insights into customer satisfaction and potential correlations with sales.

5. **Sales Trends:**
   - Line charts reveal seasonal sales trends, guiding inventory adjustments.

6. **Geographical Insights:**
   - Sales distribution by outlet location type informs marketing strategies and inventory placements.

## 🎯 Conclusion

The **Blinkit Dashboard** empowers decision-makers with a comprehensive overview of sales data, item performance, and customer preferences. Insights from this dashboard can guide marketing strategies, enhance inventory management, and improve customer engagement efforts.

---

### 🖼️ Visuals to Include
- **Key Metrics Cards:** Screenshot showing total sales, unique items, average items, and average sales.
- **Fat Content Analysis:** Bar or pie chart visualizing sales based on fat content.
- **Sales Trend Line Chart:** A line chart showcasing sales over the years.
- **Total Sales Pie Chart:** A pie chart breaking down sales by item category.
- **Sales Funnel Chart:** Funnel visualization of sales by outlet location.
- **Matrix Visualization:** Screenshot of a matrix showing average ratings and sales metrics.


