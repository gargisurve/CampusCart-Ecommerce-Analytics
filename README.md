# CampusCart : E-commerce Web Analytics

CampusCart Web Analytics is an end-to-end Web Analytics project developed to understand user behaviour, engagement patterns, and purchasing activities on a student-oriented e-commerce website.

The project combines website development, event tracking, data collection, behavioural analysis, statistical examination, and interactive dashboard development to study the complete online shopping journey.

CampusCart provides a shopping environment featuring academic and everyday college essentials such as notebooks, stationery, calculators, headphones, planners, and USB drives. User interactions across the website are tracked and analysed to understand how visitors discover products, interact with the cart, proceed through checkout, and complete purchases.

## Objectives

- Track user interactions across an e-commerce website.
- Analyse website traffic, user engagement, and session behaviour.
- Understand customer progression through the purchasing journey.
- Identify conversion rates and potential drop-off points.
- Examine product-level engagement and purchasing patterns.
- Compare user behaviour across mobile and desktop devices.
- Analyse user segments and navigation paths.
- Present analytical findings through an interactive dashboard.

## Key Features

### 1. E-commerce Website

- Developed a student-oriented e-commerce website using Python and Flask.
- Includes academic and everyday college essentials.
- Supports product browsing, cart operations, and checkout activities.
- Deployed online using PythonAnywhere to collect website interaction data.

### 2. Event Tracking and Data Collection

- Integrated Google Tag Manager (GTM) to configure and manage tracking events.
- Used Google Analytics 4 (GA4) to collect website interaction data.
- Tracked activities including page views, product views, searches, category selection, add-to-cart actions, quantity changes, checkout initiation, and purchases.
- Monitored user activity, sessions, engagement, and revenue.

### 3. Funnel Analysis

- Examines the progression of users through four purchasing stages:
  - Product View
  - Add to Cart
  - Begin Checkout
  - Purchase
- Evaluates stage-wise conversion rates and abandonment.
- Supports device-level comparison of funnel progression.

### 4. User Segment Analysis

- Examines behavioural segments such as Product Viewers, Purchasers, and Searchers.
- Identifies overlaps between browsing and purchasing behaviour.
- Helps understand differences between user groups.

### 5. Path Exploration and Page Navigation

- Uses GA4 Path Exploration to study user navigation sequences.
- Examines how users move between website pages and events.
- Identifies commonly visited pages and product navigation patterns.

### 6. Device Performance Analysis

- Compares mobile and desktop user activity.
- Examines product views and purchases across device categories.
- Uses a contingency table and Chi-square test to investigate the association between device type and purchase outcome.

### 7. Interactive Analytics Dashboard

- Developed using Google Looker Studio.
- Presents key performance indicators through scorecards.
- Includes a conversion funnel, user segment treemap, product view distribution, and device performance visualisations.
- Consolidates major analytical findings into a unified dashboard.

## Analytical Methodology

The project follows an end-to-end Web Analytics workflow consisting of the following stages:

1. **Website Development:** Developed and deployed the CampusCart e-commerce website using Python, Flask, and PythonAnywhere.
2. **Event Implementation:** Configured website interaction tracking through Google Tag Manager.
3. **Data Collection:** Collected user interaction and behavioural data using Google Analytics 4.
4. **Data Preparation:** Exported and organized GA4 data using Google Sheets for further analysis.
5. **Data Analysis:** Used Python and Google Colab for data validation, derived metric calculation, product analysis, revenue analysis, and statistical examination.
6. **Behavioural Analysis:** Performed funnel exploration, user segmentation, and path exploration using GA4.
7. **Dashboard Development:** Connected prepared datasets to Google Looker Studio and developed interactive visualisations.
8. **Insight Generation:** Interpreted the analytical results to understand engagement, conversion, product performance, and device-level behaviour.

## Technology Stack

- **Python** — Backend development and data analysis.
- **Flask** — E-commerce website development.
- **PythonAnywhere** — Website hosting and deployment.
- **Google Tag Manager (GTM)** — Website event tracking implementation.
- **Google Analytics 4 (GA4)** — Web analytics and behavioural analysis.
- **Google Sheets** — Data organization and preparation.
- **Google Colab** — Python-based data analysis and statistical examination.
- **Pandas & NumPy** — Data manipulation and calculations.
- **Matplotlib & Seaborn** — Statistical data visualization.
- **SciPy** — Chi-square statistical testing.
- **Google Looker Studio** — Interactive dashboard development.

## Dataset

The project uses website interaction data collected through Google Analytics 4 during the analysis period documented in the project report.

The collected data includes information related to:

- Users and sessions.
- Page views and website events.
- Product interactions.
- Add-to-cart and checkout activities.
- Purchases and revenue.
- Device categories.
- User segments and navigation paths.

The exported GA4 data was organized and prepared for behavioural analysis, statistical calculations, and dashboard development.

## Results and Key Findings

The analysis produced the following results for the observed dataset:

| Metric | Recorded Value |
|---|---:|
| Active Users | 30 |
| New Users | 30 |
| Sessions | 42 |
| Engaged Sessions | 32 |
| Engagement Rate | 76.19% |
| Average Engagement Time | 50 seconds |
| Total Events | 1,100 |
| Events per Session | 27 |
| Product Viewers | 23 |
| Purchasers | 15 |
| Total Revenue | ₹4,947 |

### Conversion Funnel

The purchasing journey recorded the following progression:

| Funnel Stage | Users | Completion Rate |
|---|---:|---:|
| Product View | 23 | 100% |
| Add to Cart | 20 | 86.96% |
| Begin Checkout | 19 | 95.00% |
| Purchase | 15 | 78.95% |

Overall, 65.22% of product viewers completed a purchase. The checkout-to-purchase transition showed the highest stage-wise drop-off.

### Additional Findings

- **Product Engagement:** Premium Notebook received the highest share of product views, followed by Pen Set and Scientific Calculator.
- **User Segmentation:** The analysis identified 23 Product Viewers and 15 Purchasers, with 15 users appearing in both groups.
- **Device Analysis:** Mobile users accounted for 16 product viewers and 9 purchasers, while desktop users accounted for 7 product viewers and 6 purchasers.
- **Statistical Analysis:** The Chi-square test did not identify a statistically significant association between device type and purchase outcome in the observed sample (p = 0.3738).

These findings describe the collected dataset and should not be interpreted as representative of all e-commerce customers.

## Business Impact

CampusCart demonstrates how Web Analytics can help understand customer behaviour and evaluate e-commerce performance through measurable indicators.

By combining event tracking, funnel analysis, user segmentation, and interactive visualization, the project provides a structured approach to examining customer engagement, identifying potential conversion bottlenecks, and understanding product and device-level behaviour.

## Limitations

- The analysis is based on a limited observation period and a relatively small user sample.
- Behavioural findings may not generalize to larger or different customer populations.
- Funnel analysis depends on the accuracy and consistency of event tracking.
- Device-level statistical results require validation using a larger dataset.
- Dashboard insights are dependent on the available GA4 data and its reporting configuration.

## Future Scope

- Collect website interaction data over a longer period and from a larger user base.
- Introduce customer retention and cohort analysis.
- Examine traffic sources and acquisition channels.
- Expand product-level and customer segmentation analysis.
- Explore predictive analytics for customer conversion and engagement.
- Implement automated data refresh and reporting workflows.

## Live Dashboard

Explore the interactive CampusCart Web Analytics dashboard:

**[View CampusCart Dashboard — Google Looker Studio](https://datastudio.google.com/reporting/927eaf23-faad-4ce8-a7dd-3ca6c75b33c1)**

## Project Documentation

The detailed project report, including the methodology, analytical workflow, visualisations, and results, is available in the `report/` directory.

## Author

**Gargi Ashish Surve**
