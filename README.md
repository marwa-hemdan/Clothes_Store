# Clothes_Store

# Big Fashion Sales Group Dashboard Project

## Overview
This project features an interactive Excel dashboard designed to visualize and analyze sales data for the Big Fashion Group, an Australian fashion retail entity. The dashboard aggregates sales metrics across various dimensions such as chains (e.g., Fashions Direct and Next Look), categories (e.g., Mens, Womens, Shoes), managers, states, and time periods. It uses PivotTables, charts, slicers, and conditional formatting to provide dynamic insights into sales performance and trends.

The data spans financial years from 2015/16 to 2017/18, focusing on Australian states like NSW, VIC, QLD, and others. This is based on a tutorial-style workbook, ideal for learning advanced Excel techniques like data modeling, visualization, and dashboard protection.

## Key Features

- **Filters/Slicers**: Interactive controls for Financial Year (FY), State, and Category to slice data on the fly.
- **Visualizations**:
  - Pie chart showing sales distribution by chain (e.g., Fashions Direct ~71%, Next Look ~29%).
  - Line chart for monthly sales trends (2016-2017), highlighting growth patterns.
  - Bar charts for sales by category and by manager (sorted ascending by totals).
  - Table with sales totals and sparkline trends by state.
  - Map chart (for Excel 2019/Office 365) displaying sales heat map across Australia. # this data are provided from MyOnlineTrainingHub  youtube channel
    

- **Dynamic Elements**: GETPIVOTDATA formulas, conditional formatting bars, and IFERROR handling for robust display.

## Data Summary
The underlying data (in 'Data' and 'Data Aug' sheets) includes ~72,000+ records with columns like Month, Financial Year, Chain, Suburb, State, Postcode, Country, Manager, Category, Buyer, and Sales.

### Key Insights from the Data:
- **Total Sales**: ~$54.5 million across all chains and periods.
- **Sales by Chain**:
  - Fashions Direct: ~$38.5 million (71%).
  - Next Look: ~$15.9 million (29%).
- **Top Categories by Sales** (approximate totals):
  - Mens: ~$11.6 million.
  - Shoes: ~$9.8 million.
  - Home: ~$9.7 million.
  - Juniors: ~$7.7 million.
  - Womens: ~$6.1 million.
  - Kids: ~$5.8 million.
  - Accessories: ~$3.6 million.
  - Intimate: ~$2.4 million.
  - Groceries: ~$1.7 million.
  - Hosiery: ~$1.7 million.
- **Sales by State** (descending order):
  - NSW: ~$19.9 million.
  - VIC: ~$13.2 million.
  - QLD: ~$10.9 million.
  - WA: ~$5.7 million.
  - SA: ~$2.0 million.
  - TAS: ~$1.1 million.
  - NT: ~$1.2 million.
  - ACT: ~$0.6 million.
- **Trends**: Sales show seasonal fluctuations, with peaks in September (~$4.2 million) and growth from 2016 to 2017. Example monthly breakdown (2016): Jan ~$2.5M, rising to Sep ~$4.2M.
- **Managers**: Sales distributed across managers like John Gardner (NSW), Jeremy Garcia (NSW), Lillian Pruitt (NSW), etc., with top performers in high-sales states.
- **Additional Data**: 'Data Aug' sheet adds August 2017/18 data for extension/testing.

Data is fictional/sample for tutorial purposes, with sales in AUD (Australian Dollars), often displayed in thousands in charts.

## How to Use
1. **Prerequisites**: Microsoft Excel 2016+ (Excel 2019/Office 365 recommended for map charts).
2. **Setup**:
   - Clone/download the repository.
   - Open `dashboard_webinar.xlsx`.
   - Navigate to the 'Dashboard' sheet.
3. **Interaction**:
   - Use slicers (top-left) to filter by State (e.g., NSW, VIC), FY (e.g., 2016/17), or Category (e.g., Mens, Shoes).
   - Charts and tables update automatically.
   - To add new data: Append to 'Data' sheet, then right-click any PivotTable > Refresh.
4. **Customization**:
   - Follow the 'Build Steps' sheet for recreating/modifying pivots and charts.
   - Example: Group dates by month/year in PivotTables for trends.
5. **Protection**:
   - The dashboard is protected (no password). To edit: Review > Unprotect Sheet.
   - Re-protect after changes to maintain integrity.

## Repository Structure
- `dashboard_webinar.xlsx`: The main Excel workbook with all sheets (Copyright, File Index, Dashboard, Build Steps, Pivots, Data, Data Aug).
- `README.md`: This file.
- 
<img width="1502" height="652" alt="proj1" src="https://github.com/user-attachments/assets/9d778bd8-f7c7-487c-bbcd-152337e5b12b" />

<img width="1543" height="358" alt="proj2" src="https://github.com/user-attachments/assets/27dc2965-4880-4377-b1aa-223d72b3ed8b" />


## Build and Learning
This dashboard demonstrates Excel best practices:
- Data formatting as Tables.
- PivotTable creation and grouping.
- Chart insertion (line, bar, pie, map).
- Slicers and connections.
- Sparklines and conditional formatting.
- Dynamic labels and formulas (e.g., IF for handling blanks, GETPIVOTDATA for mapping).

For step-by-step recreation, see the 'Build Steps' sheet. This is great for learning data visualization in Excel without external tools.

## Copyright and License
- All the instructions and tips from Mynda Treacy from [My Online Training Hub](https://www.myonlinetraininghub.com/).

