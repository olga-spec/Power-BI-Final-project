# Power-BI-Final-project
Power BI Sales and logistic project

Project Objective:

Prototype design, utilizing UX/UI
Selection and proper formatting of diagrams
Use of scalar DAX (including iterative), table DAX expressions
Creation of calculated columns
Data modeling, relationship management, data transformation
Utilization of Power BI features (groups, hierarchies, filters, cross-filtering, tooltips, detail pages, content switching, etc.)

1. Interface

Develop a theme, choose complementary colors and fonts. Ensure consistent style throughout the project.
Consider the logical structure of content, organized by blocks/tabs, applying knowledge of UX/UI.
Provide opportunities for data interaction: buttons, bookmarks, additional pages, pop-up windows, info blocks, navigation.
Create concise and clear titles/captions for all project sections.
2. Sales Metrics

Average check
Revenue - total from completed transactions
Value of ongoing deals
Conversion - Sales / Leads
Geographic sales
Sales rankings
Active customer base - number of unique customers who completed at least one transaction (in a completed state) during the specified period.
3. Logistics Metrics

On-time delivery rate
Transportation cost per unit
Average order processing time
Average order cycle time
4. Modeling and Transformation

Establish relationships between tables.
Use Power Query (PQ) to denormalize the olist_orders_dataset table for funnel creation.
Remove fields (at the end of the project) that are not needed.
In the olist_products_dataset table, create a calculated column to define product categories. Define groups and the logic for filling them independently.
5. Functionality

Date filter (dynamic calendar) and two additional metrics of choice.
Implement comparison with the previous year in terms of growth or decline.
Implement content switching through DAX.
6. Visualizations

Four tabs: Sales, Logistics, Payments, Reviews.
Events funnel on the Sales tab (order created, order confirmed, etc.). The funnel is controlled by the calendar.
Dynamics of orders or growth (by total and quantity) on the Sales tab.
Use of a map on any of the tabs, with a randomly chosen metric.
Independent analytics block (metric selection, visual selection).
Payments tab.
Reviews tab.

