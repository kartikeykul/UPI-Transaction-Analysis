
# Project # UPI Transaction-Dashboard

### Dashboard Link :https://app.powerbi.com/groups/me/reports/1d12abdd-2c32-4676-ade9-41b941639dc5/07b81a7817d9b00c0753?experience=power-bi&bookmarkGuid=8dcda762a44846356f59

Unified Payments Interface (UPI) has revolutionized digital payments in India by enabling instant money transfers between bank accounts via mobile devices. The volume and value of UPI transactions have grown exponentially, making it an important area for financial institutions, policymakers, and businesses to monitor. However, the sheer scale of transaction data makes it challenging to extract actionable insights without a robust analytical framework.

## Problem Statement

Developed a Power BI dashboard to analyze UPI transaction patterns, visualizing monthly customer transaction volumes using column and line charts, and tracking account balance trends over the same year to enhance customer insights and decision-making.


### Steps followed 

-Step 1: Imported UPI transaction data from Excel into Power BI Desktop and performed data exploration and transformation using Power Query Editor, including renaming queries, splitting columns, and ensuring accurate data types for reliable modeling and reporting. Applied best practices in data preparation to enhance report accuracy, performance, and usability.

-Step 2: Performed data profiling to assess data quality and understand distribution, ensuring accuracy and reliability for subsequent analysis and reporting

-Step 3: Optimized the sizing and positioning of slicers and visuals in Power BI to ensure a well-aligned and user-friendly report layout. Calculated slicer dimensions by factoring in total available space, margins, and inter-slicer spacing, and applied precise vertical positioning for multiple rows to maintain visual consistency and clarity.

-Step 4: Customized Power BI report aesthetics by configuring canvas background colors, wallpapers, and dimensions using predefined ratios or custom sizes. Ensured neat and aligned layouts through precise sizing and positioning of slicers, calculating optimal width and spacing to accommodate multiple slicers in a single row.

-Step 4: Created an Age Groups column using DAX with nested IF functions to segment customer demographics. Configured multiple slicers for fields such as bank names, cities, device types, gender, age groups, merchant names, payment methods, purposes, and transaction types. Duplicated report pages to maintain consistent slicer settings while planning unique visuals for each page, including a matrix visual and interactive chart-switching between line and clustered column formats.


-Step 5: Developed a line chart to visualize transaction amounts over time, applying smooth interpolation, custom colors, markers, and data labels for enhanced clarity. Implemented cross-page filters to accurately handle multiple currencies, and formatted axes, titles, and borders to improve chart readability and overall presentation quality

-Step 6: Added and configured a matrix visual on the second report page to display transaction amounts, remaining balances, months, cities, and currencies. Customized values, rows, and columns with number formatting, font styling, grid lines, and borders. Implemented dynamic data filtering through slicers and report-level filters to ensure the matrix visual updates interactively based on user selections.

-Step 7: Configured slicer syncing across multiple report pages in Power BI to ensure consistent filtering without repeated selections, enabling changes on one page to reflect across all synced pages. Applied conditional formatting to matrix visuals, using color gradients on numerical columns to highlight data intensity and improve interpretability.

-Step 8: Implemented bookmarks in Power BI to allow users to switch between different chart types on the same report page. Utilized the selection pane to manage visual visibility and enable bookmark functionality. Added bookmark navigator buttons for interactive toggling between views, ensuring proper naming and updates to accurately reflect desired visual states.

Step 9: Added bookmarks to toggle between different chart types representing transaction amounts and remaining balances by month. Designed and formatted additional line and column charts for balance data, updating bookmarks to control chart visibility and ensure the bookmark navigator remained on top. Applied filters to charts and planned slicer synchronization across bookmarks for consistent, unified filtering.

-Step 10: Published reports to Power BI Service to enable online access and interactive exploration. Followed a structured process of signing in, selecting the target workspace, publishing the report, and accessing it via the Power BI Service for seamless sharing and collaboration.


### Slicers Used ![Slicer_page](https://github.com/user-attachments/assets/97d3dd6e-4b80-4645-adbe-b57b6eecf570)

 


# Insights

A two page report was created on Power BI Desktop & it was then published to Power BI Service.

PAGE 1:Following inferences can be drawn from the dashboard:

 
 ### Developed the Page 1 dashboard, featuring key UPI transaction metrics and visualizations to provide an at-a-glance overview of monthly trends, balances, and overall performance.
 ![Dashboard_Page1](https://github.com/user-attachments/assets/c501cdaf-e927-4eed-8589-3724e697fd84)
 

### 1) Displayed the total UPI transactions for each month using combined line and column charts, providing an overall trend analysis without applying slicer filters.

![Transactions_by_month_Line_chart](https://github.com/user-attachments/assets/c3acd7fa-dded-4a75-beb1-3f7f446e0d1c)

 
 
 
 ![Transactions_by_month_Column_chart](https://github.com/user-attachments/assets/af862b21-61cb-43ce-90e6-41f71183f11d)

      
### [2] Visualized the remaining account balance after monthly transactions using a combination of line and column charts to illustrate trends and comparisons over time.
.
 
 
![Balance_By_Month_Line_chart](https://github.com/user-attachments/assets/d45c1137-1e12-44f3-a089-549a0cc84f02)



![Balance_By_month_Column_chart](https://github.com/user-attachments/assets/bee03cc5-b655-4b22-a1bf-830946b34b1a)





 ### PAGE 2: Designed a report page displaying data in a tabular format segmented by city, enabling clear comparison and analysis across different locations.

![Dashboard_Page2](https://github.com/user-attachments/assets/6d48bcbc-f85d-4f9f-b66b-b755cc3d3460)

