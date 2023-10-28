# Albundy Shoe Shop Inventory Management

**Company Overview**: Albundy Shoe Shop is a USA-based company operating in Canada, the UK, and Germany. We offer shoes priced between $120 and $200.

**The Inventory Challenge**: Managing inventory can be challenging, especially when there's excess stock with slow product turnover.

**Using Confidence Intervals**: To address this issue, we employ confidence intervals. Our dataset includes information such as invoice number, date, country, product ID, shop, gender, shoe size, unit price, sales price, and discounts.

**Data Segmentation**: We segment the data by shoe size, country, and gender to answer two problem statements.

**Problem Statement 1**: What's the likely number of shoes to be sold based on historical data? We find the 95% confidence interval for the last 12 months of sales, considering only men's shoes in the USA.

**Insights from CI**: The upper bound of the confidence interval shows us the maximum number of pairs needed, enabling better inventory management and planning.

**Problem Statement 2**: We compare two shops' sales performance. With data from the last 12 months, we use a t-test with 95% confidence and 22 degrees of freedom.

**Shop Comparison Insights**: Our analysis shows that the two shops perform comparably, with some size variations. On average, they are expected to remain identical.

This project demonstrates how confidence intervals can help optimize inventory and assess shop performance in the shoe retail business.
