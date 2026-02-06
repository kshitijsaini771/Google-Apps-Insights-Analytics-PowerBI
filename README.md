# Google Apps Insights & Analytics (Power BI)

## Problem Statement
The Google Play ecosystem hosts thousands of apps across diverse categories, but understanding **which segments succeed and why** requires deep data intelligence. This project leverages Power BI to transform a dataset of **10,350 Google Play Store apps** into an interactive analytical dashboard that uncovers key patterns in **ratings, installs, content suitability**, and **market performance**—enabling smarter strategic, marketing, and product decisions.

---

## Analysis Done
- Cleaned and standardized the dataset (`googleplaystore.csv`) using Python (`Google_Play_Store_Analytics_Cleaned.ipynb`), resolving duplicates, normalizing sizes, and ensuring data consistency.
- Segmented the app lifecycle into success tiers:  
  **All Apps → Reviewed → Popular (1K+) → Successful (100K+) → Top Tier (10M+) → Elite (100M+)**.
- Built calculated metrics and DAX measures in Power BI for **Review Performance**, **Success Classification**, and **Market Share**.
- Integrated dynamic slicers for **Content Rating** (Everyone, Teen, Mature 17+, Everyone 10+) to support audience-specific insights.
- Key results:  
  - **Average rating:** 4.19  
  - **Total installs:** 147B  
  - **Positive rating trend:** 84% of apps  
  - **Free apps dominance**, but paid apps maintain higher average ratings.
- Utilized consistent color-coding (green/red for performance trends) and a clean Power BI theme for professional, easy-to-interpret visuals.

---

## Dashboard Overview
The dashboard delivers a comprehensive, data-driven view of the Android app marketplace:
- **Apps Updated Over Time (2010–2018):** Highlights the rise of COMMUNICATION and decline of DATING categories.  
- **Categories by Performance:** GAME leads in installs, followed by COMMUNICATION and SOCIAL—showcasing dominant market players.  
- **Content Rating Insights:** “Everyone” apps form over 50% of the ecosystem; “Teen” and “Mature 17+” follow as secondary demographics.  
- **App Size by Content Rating:** Majority of larger apps target “Everyone,” aligning with accessibility and scale.  
- **Free vs Paid Apps:** Shows that while **free apps dominate volume**, paid ones achieve **higher quality scores**.  
- **Top Apps by Rating & Reviews:** Pinpoints top performers like **ROBLOX** and **Subway Surfers**, correlating rating excellence with engagement scale.  
- **User Engagement:** Average of **406K reviews per app**, emphasizing strong community participation across top apps.

![Power BI Dashboard](PowerBi.PNG)

---

## Recommendations
- **Prioritize High-Impact Categories:** Focus investment on GAME, COMMUNICATION, and SOCIAL, where engagement and install volume are highest.  
- **Optimize Freemium Strategy:** Capitalize on the free-app majority through in-app purchases and ads.  
- **Target Broad Audiences:** Design for “Everyone” and “Teen” content ratings to maximize reach.  
- **Invest in Frequent Updates:** Apps with consistent updates (notably 2017–2018) outperform in ratings and installs.  
- **Benchmark Against Elite Apps:** Use metrics from top-tier and elite apps to refine development and marketing strategies.

---

**Author:** [Kshitij Saini](https://www.linkedin.com/in/kshitijsaini-b950b7299?utm_source=share_via&utm_content=profile&utm_medium=member_android)
