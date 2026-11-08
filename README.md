# CampusCart — E-commerce Web Analytics

CampusCart Web Analytics is an end-to-end Web Analytics project developed to understand user behaviour, engagement patterns, and purchasing activities on a student-oriented e-commerce website.

The project combines website development, event tracking, data collection, behavioural analysis, statistical examination, and interactive dashboard development to study the complete online shopping journey.

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
- Deployed using PythonAnywhere.

### 2. Event Tracking and Data Collection
- Integrated Google Tag Manager (GTM) for event tracking.
- Used Google Analytics 4 (GA4) to collect website interaction data.
- Tracked page views, product views, searches, category selection, add-to-cart actions, checkout activities, and purchases.

### 3. Funnel Analysis
- Examines four stages of the purchasing journey:
  - Product View
  - Add to Cart
  - Begin Checkout
  - Purchase
- Evaluates stage-wise conversion rates and abandonment.

### 4. User Segment Analysis
- Analyses Product Viewers, Purchasers, and Searchers.
- Identifies overlaps between browsing and purchasing behaviour.

### 5. Path Exploration
- Examines user navigation sequences and commonly visited pages.
- Studies interactions across website pages and events.

### 6. Device Performance Analysis
- Compares mobile and desktop user activity.
- Examines product views and purchases across device categories.
- Uses a contingency table and Chi-square test to investigate the association between device type and purchase outcome.

### 7. Interactive Analytics Dashboard
- Developed using Google Looker Studio.
- Presents KPIs, conversion funnel, user segments, product distribution, and device performance visualisations.

## Analytical Methodology

1. **Website Development:** Developed the CampusCart website using Python and Flask.
2. **Event Implementation:** Configured interaction tracking using Google Tag Manager.
3. **Data Collection:** Collected website activity through Google Analytics 4.
4. **Data Preparation:** Organized and prepared exported analytics data using Google Sheets.
5. **Data Analysis:** Used Python and Google Colab for data validation, metric calculations, and statistical analysis.
6. **Behavioural Analysis:** Performed funnel exploration, user segmentation, and path exploration using GA4.
7. **Dashboard Development:** Created interactive visualisations using Google Looker Studio.
8. **Insight Generation:** Interpreted results to understand engagement, conversion, product performance, and device behaviour.

## Technology Stack

- Python
- Flask
- PythonAnywhere
- Google Tag Manager (GTM)
- Google Analytics 4 (GA4)
- Google Sheets
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Looker Studio

## Results and Key Findings

The analysis produced the following results for the observed dataset:

| Metric | Value |
|---|---:|
| Active Users | 30 |
| Sessions | 42 |
| Engaged Sessions | 32 |
| Engagement Rate | 76.19% |
| Average Engagement Time | 50 seconds |
| Total Events | 1,100 |
| Product Viewers | 23 |
| Purchasers | 15 |
| Total Revenue | ₹4,947 |

### Conversion Funnel

| Stage | Users | Completion Rate |
|---|---:|---:|
| Product View | 23 | 100% |
| Add to Cart | 20 | 86.96% |
| Begin Checkout | 19 | 95.00% |
| Purchase | 15 | 78.95% |

Overall, 65.22% of product viewers completed a purchase. The checkout-to-purchase transition recorded the highest stage-wise drop-off.

### Additional Findings

- **Product Engagement:** Premium Notebook received the highest share of product views.
- **User Segmentation:** 23 Product Viewers and 15 Purchasers were identified, with 15 users belonging to both groups.
- **Device Analysis:** Mobile users accounted for 16 product viewers and 9 purchasers, while desktop users accounted for 7 product viewers and 6 purchasers.
- **Statistical Analysis:** The Chi-square test did not identify a statistically significant association between device type and purchase outcome in the observed sample.

## Limitations

- Analysis is based on a limited observation period and a relatively small user sample.
- Findings may not generalize to larger customer populations.
- Funnel analysis depends on accurate and consistent event tracking.
- Device-level statistical results require validation using a larger dataset.

## Future Scope

- Collect interaction data over a longer period and from a larger user base.
- Introduce customer retention and cohort analysis.
- Examine traffic sources and acquisition channels.
- Expand customer segmentation and product-level analysis.
- Explore predictive analytics for customer conversion and engagement.
- Implement automated data refresh and reporting workflows.

## Live Dashboard

**[Explore CampusCart — Google Looker Studio](https://datastudio.google.com/reporting/927eaf23-faad-4ce8-a7dd-3ca6c75b33c1)**

## Author

**Gargi Ashish Surve**
