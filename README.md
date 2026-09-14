# Super-Store-Sales-Dashboard

1. **Headline**

The process started in Power Query, where I used M language to clean and reshape the raw data — correcting data types, removing unnecessary fields, and building a custom column (including date transformations) so everything downstream would work reliably. Rather than relying only on the Power Query UI, I wrote M directly to handle the transformations.
Before building any visuals, I set up the core DAX measures — sales, profit, margin %, average order value — to establish a reliable foundation for the analysis rather than working things out ad hoc later.

2. The dashboard itself is organized into a few layers:

Overview page with KPIs and slicers for year, region, and segment
Category and sub-category breakdowns
State-level map
Monthly sales and profit trends side by side
Top 10 customers by sales and profit
Waterfall charts highlighting the most and least profitable sub-categories
To add a forward-looking element, I forecasted sales for the next two quarters at a 90% confidence level, so the dashboard points ahead rather than only explaining past performance.

3. Tools Used
Power Query (M Language) – data cleaning, transformation, custom columns
DAX – calculated measures (sales, profit, margin %, AOV)
Data Modeling – table relationships and schema design for reliable downstream analysis
Power BI – dashboard build, visuals, slicers, forecasting

4. Key Insights / Findings
Generated $2.3M in total sales with $286.4K profit (12.47% margin).
Technology was the top category by sales ($836K); Phones and Chairs led at the sub-category level.
Tables was a top-5 sub-category by sales ($207K) but the biggest drag on profitability, losing -$17.7K — a key pricing/discounting flag.
Top customer by revenue (Sean Miller, $25K) was actually unprofitable (-$2K), while Tamara Chand generated the highest profit ($9K) despite lower sales — revenue ≠ profitability.
Consumer segment drove 51% of sales, followed by Corporate (31%) and Home Office (19%).
Sales and profit show clear seasonality, peaking in Q4 each year.
Forecasted next-period sales (90% confidence) at ~$137K, signaling the 2026 spike ($518K) as an anomaly rather than a trend.

5. Data Source
   CSV

6. Dashboard preview: - (https://github.com/Ramshukl10/Super-Store-Sales-Dashboard/blob/main/Pg1.png)
                      (https://github.com/Ramshukl10/Super-Store-Sales-Dashboard/blob/main/Pg2.png)
