# Marketing A/B Testing Campaign Analysis
This notebook explores an A/B testing dataset sourced from https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing to assess the effectiveness of marketing campaigns.

### Background
Marketing companies aim to run successful campaigns, but the market's complexity requires rigorous experimentation. One common approach is A/B testing, a randomized process where multiple variations (e.g., web pages, banners) are tested simultaneously on different user groups to determine which variation has the greatest impact on business metrics.

### In this dataset:
- The experimental group is exposed to advertisements.
- The control group sees a Public Service Announcement (PSA) or nothing in the same placement as the ad.
Objective

### This analysis seeks to answer:

Would the campaign be successful?
How much of the success can be attributed to the ads?
To address these questions, statistical testing will determine:

If the difference between groups is statistically significant.
The business impact of the campaign's success.

### Dataset Overview
The dataset includes the following columns:

- Index: Row identifier.
- user_id: Unique user identifier.
- test_group: Indicates if the user was in the experimental group ("ad") or control group ("psa").
- converted: Indicates if the user made a purchase (True/False).
- total_ads: The number of ads viewed by the user.
- most_ads_day: The day on which the user saw the most ads.
- most_ads_hour: The hour at which the user saw the most ads.

### Approach
The analysis combines exploratory data analysis, hypothesis testing, and visualization to derive actionable insights about user behavior and campaign effectiveness.
