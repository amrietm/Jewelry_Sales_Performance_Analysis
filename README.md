# Jewelry Sales Performance Analysis

This analysis uses eCommerce purchase history from a medium-sized online jewelry store, covering December 2018 to December 2021. Sourced from [Kaggle](https://www.kaggle.com/datasets/mkechinov/ecommerce-purchase-history-from-jewelry-store) and originally provided by the [Open CDP Project](https://rees46.com/en/open-cdp), it examines revenue trends, order volume, and product demand, highlighting top-performing jewelry categories, metals, gemstones, and colors to identify sales patterns and support data-driven business decisions.

<img width="1212" height="687" alt="image" src="https://github.com/user-attachments/assets/3419c44f-281a-4690-874e-d213c74db666" />



# Problem Statement
The business needs to identify its top-performing jewelry products, monitor and understand changing jewelry trends, identify shifts in customer preferences, and discover opportunities to improve sales across other product categories.


# Methodology
The analysis followed a two-step process to prepare, analyze, and visualize the jewelry store's eCommerce sales data.

1. Data Cleaning – Microsoft Excel
- Checked and removed duplicate records and blank rows.
- Standardized data formats and corrected inconsistent values.
- Reviewed missing data and replaced where appropriate.
- Organized columns to ensure data accuracy and consistency.

2. Data Visualization – Microsoft Power BI
- Imported the cleaned dataset into Power BI.
- Created measures for key performance indicators, including total revenue, orders, and units sold.
- Developed interactive charts to analyze sales trends and product performance.
- Used slicers and filters to explore revenue by jewelry category, metal, gemstone, and color.

Overall Goal: Transform raw sales data into meaningful insights that help identify changing product trends and potential opportunities for sales growth.


# Key Analysis and Visualization

## Who's Buying?

<img width="1430" height="657" alt="image" src="https://github.com/user-attachments/assets/56b10c41-756d-4486-b1a3-91218f0c8f69" />


Customer Gender Distribution (2018–2021)

Female customers accounted for the largest identified buyer segment at 54.22%, while male customers represented only 0.14%. Notably, 45% of buyers had no recorded gender information. Rather than assuming this group identifies as another gender, it is more accurate to view it as an opportunity to recognize gaps in customer data collection and adopt a more inclusive approach to understanding the store's customer base.


## What's driving the revenue?

### JEWELRY TYPE

#### Total Price By Category

<img width="457" height="365" alt="image" src="https://github.com/user-attachments/assets/56d2b009-b6b4-4a9f-a33b-86fcd3ca9fe0" />

#### Total Order Quantity By Category

<img width="460" height="362" alt="image" src="https://github.com/user-attachments/assets/72465978-abac-4b2d-9631-9cd9bd60ad31" />

Jewelry type is one of the key factors influencing the store's revenue. Based on total sales value, the top five contributors are earrings, rings, unspecified jewelry, bracelets, and pendants. In terms of quantity sold, the ranking shifts slightly to earrings, rings, pendants, unspecified jewelry, and bracelets.

This suggests that earrings and rings are the store's strongest product categories, performing well in both revenue and sales volume. Pendants, meanwhile, sell in higher quantities than bracelets but contribute less to revenue, which may indicate a lower average selling price. This presents an opportunity to explore pricing strategies, product bundles, and promotional campaigns to increase revenue across other jewelry categories.


### MAIN METAL

<img width="956" height="452" alt="image" src="https://github.com/user-attachments/assets/98387f1e-fd0f-4fe7-a3fe-e0741476954d" />

Gold is the leading metal in the store's sales performance, ranking highest in both quantity sold and total revenue. This indicates that gold jewelry is a major driver of customer demand and overall sales value.

Its strong performance suggests that gold remains a key product preference among buyers, making it an important category to prioritize. The store can build on this demand while exploring opportunities to promote other metals and diversify product sales.


### MAIN GEM

#### Total Price based on Main Gem used

<img width="781" height="477" alt="image" src="https://github.com/user-attachments/assets/f2b26307-a00c-4c87-89a6-8d3376eafc1d" />

#### Total Order Quantity based on Main Gem used

<img width="782" height="482" alt="image" src="https://github.com/user-attachments/assets/9f838c75-2b89-4ddd-98af-0891214edfc6" />

Diamonds lead the store's gemstone sales, followed by topaz, fianit (cubic zirconia), pearl, garnet, amethyst, sapphire, and emerald. The remaining sales come from various other and unspecified gemstones.

This highlights the strong demand for a few key gemstones while showing the diversity of the store's product offerings. The business can prioritize popular gems in its marketing while promoting less popular options through themed collections and targeted campaigns. Improving records for unknown gemstones could also provide clearer insights into product performance.


### MAIN COLOR

#### Total Price based on Main Color used

<img width="792" height="532" alt="image" src="https://github.com/user-attachments/assets/a9e21796-d496-42d4-9c14-f99671345126" />

#### Total Order Qwuantity based on Main Color used

<img width="782" height="527" alt="image" src="https://github.com/user-attachments/assets/a5c356ae-d527-4d98-8206-7984308045f0" />

Red, white, and yellow are the top three jewelry colors in the store's sales. This suggests that these colors appeal strongly to buyers and contribute significantly to product demand. The store can prioritize these colors in its product selection while exploring other shades to diversify its offerings and attract customers with different style preferences.


## YEARLY TRENDS

### 2019

<img width="792" height="445" alt="image" src="https://github.com/user-attachments/assets/a5a47921-f7b3-4000-ae87-3c47d3813e2a" />

In 2019, both total revenue and order quantity began increasing in July, peaked in August, and declined in September. Sales then steadily recovered from October through December. The July increase may be linked to Independence Day promotions in the US, while the August peak could reflect early shopping activity ahead of Labor Day. The steady growth toward year-end may be driven by holiday shopping events such as Black Friday and Christmas. These seasonal events could help explain the sales pattern, although promotional and campaign data would be needed to confirm their direct impact.

### 2020

<img width="797" height="447" alt="image" src="https://github.com/user-attachments/assets/12453145-4be8-4ca2-8f96-80c298ff3cd8" />

At the start of 2020, sales slowed slightly, but the overall seasonal pattern remained similar to 2019, with revenue and order quantity increasing around July. November revenue was also comparable to the previous year, reaching approximately $700K–$800K. However, sales rebounded significantly in December, generating around $2 million in revenue, suggesting strong year-end holiday demand.

### 2021

<img width="797" height="455" alt="image" src="https://github.com/user-attachments/assets/e4694c5c-38b4-438a-851d-d641577143fa" />

In 2021, sales started slowly after the holiday season, similar to 2020, but began increasing around mid-February, potentially reflecting higher demand during Valentine's Day. The store appears to have maintained a similar seasonal sales pattern since 2019, while achieving stronger results over time. November revenue reached nearly $4 million, almost quadruple the November 2019 figure. However, unlike previous years, sales declined in December 2021. This could indicate that holiday demand shifted earlier toward November, possibly driven by major shopping events such as Black Friday.


## 2019 - 2021 TRENDS

<img width="797" height="455" alt="image" src="https://github.com/user-attachments/assets/f1faa7be-69a6-4dc2-b5f2-fae7497d51a2" />

Overall, the store showed an upward trend in both revenue and order volume from 2019 to 2021, indicating business growth and increasing sales activity over the three-year period. Despite seasonal fluctuations, the store generally achieved stronger performance year over year.


# RECOMMENDATION

1. Maximize Seasonal Promotions: Plan campaigns around Valentine's Day, Black Friday, Christmas, and other key shopping periods. Start promotions early to capture demand.

2. Prioritize Best-Selling Products: Maintain sufficient inventory of popular jewelry categories, gemstones, and colors to meet customer demand.

3. Boost Underperforming Categories: Use bundles, discounts, and targeted campaigns to encourage sales of less popular products.

4. Review Sales Trends: Monitor monthly performance to identify seasonal patterns and adjust marketing and inventory strategies accordingly.

5. Improve Customer Data: Address missing customer information to support better segmentation and more effective marketing.

Overall: Build on the store's growing revenue and order volume through seasonal marketing, strategic inventory planning, and targeted promotions.

