# Marketing Campaign Performance & Analysis

This project contains an exploratory data analysis (EDA) of a marketing campaign dataset. The goal is to uncover key insights into campaign performance and guide strategic decision-making based on various metrics.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Findings & Insights](#findings--insights)
- [Actionable Recommendations](#actionable-recommendations)
- [Installation & Usage](#installation--usage)
- [Technologies Used](#technologies-used)
- [Next Steps](#next-steps)
- [Contact](#contact)

## Overview

This repository holds the code and analysis performed on the Marketing Campaign Dataset to evaluate the effectiveness of various marketing strategies. It covers performance metrics by campaign type, marketing channels, geographical locations, and target audiences.

*Presented By: Araoye A. A.*  
*Presentation Date: 2/13/2025*

## Dataset

- **Name:** Marketing Campaign Dataset
- **Size:** 200,005 rows (~24.5 MB)
- **Key Columns:**  
  - Company  
  - Campaign_Type  
  - Target_Audience  
  - Duration  
  - Channels_Used  
  - Conversion_Rate  
  - Acquisition_Cost  
  - ROI  
  - Location  
  - Date  
  - Clicks  
  - Impressions  
  - Engagement_Score  
  - Customer_Segment

## Objectives

- **Evaluate Campaign Effectiveness:**  
  Analyze performance by Campaign Type, Channel Used, Location, and Target Audience.

- **Uncover Patterns:**  
  Identify trends in key performance indicators such as ROI, CTR, CPC, and Conversion Rate.

- **Provide Actionable Insights:**  
  Recommend optimizations for ad spend, targeting strategies, and regional focus to improve overall marketing performance.

## Methodology

The project employs Python and its data analysis libraries to process and visualize the dataset. The key steps include:

- **Data Cleaning & Preprocessing:**  
  Handling missing values, ensuring correct data types, and filtering relevant records.

- **Exploratory Data Analysis (EDA):**  
  Investigating distributions and relationships among variables using statistical techniques and visualizations.

- **Statistical Analysis:**  
  Assessing correlations and deriving patterns from the data.

- **Visualization & Interpretation:**  
  Creating plots and charts to illustrate findings, such as the relationship between impressions and CTR and performance differences across channels and regions.

## Findings & Insights

- **CTR vs. Impressions:**  
  Higher impressions do not always lead to higher CTR. For example, Google Ads and Website channels show high impressions but varied CTR results.

- **Audience Insights:**  
  - **Men (18-24):** Highest conversion rate.  
  - **Women (25-34):** Balanced performance between Conversion Rate and CPC.

- **Channel Performance:**  
  - **Facebook Ads & Websites:** Deliver strong ROI with relatively low CPA.  
  - **Facebook Ads:** Particularly effective, demonstrating lower CPA and better conversion efficiency.

- **Regional Performance:**  
  - **Los Angeles & Miami:** Generated the highest ROI.  
  - **Houston:** More cost-effective with a lower CPA.

## Actionable Recommendations

- **Optimize Ad Spend:**  
  Shift budget towards high ROI channels like Facebook and Websites, and improve ad creatives for channels like Google Ads and Instagram.

- **Refine Targeting Strategy:**  
  Focus on audience segments that demonstrate high CTR and conversions, such as:  
  - Men aged 18-24  
  - Men aged 25-34  
  - Women aged 34-44  
  Adjust strategies for underperforming segments accordingly.

- **Leverage Regional Insights:**  
  Increase efforts in regions with strong performance (Los Angeles and Miami) and expand campaigns in cost-effective areas (Houston).

## Installation & Usage

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Required Python libraries:
  - Pandas
  - Matplotlib
  - Seaborn
  - NumPy
  - DateUtil (Parser)

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/abrokinla/https://github.com/abrokinla/eda_marketing_campaign_analysis_python.git
   cd eda_marketing_campaign_analysis_python

2. **Install Dependencies:**
```bash
   pip install -r requirements.txt
```

### Running the Analysis

Execute the analysis by first opening Jupyter-Notebook:
```bash
  jupyter-notebook
```
### Technologies Used

- Programming Language: Python
- Libraries:
  - Pandas
  - Matplotlib
  - Seaborn
  - NumPy
  - DateUtil (Parser)

### Next Steps

- Implement A/B testing to further validate findings.
- Continuously  refine targeting strategies based on new data.
- Optimize campaigns by reallocating budgets according to high-ROI channels and reginonal performance.

### Contact

For any questions or further information, please contact:

- **Name**: Araoye Abraham A.
- **Email**: <abrokinla@gmail.com>
