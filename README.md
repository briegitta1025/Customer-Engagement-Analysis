# Customer Engagement Analysis: Statistical Impact Assessment

## Project Overview

Statistical analysis of student engagement data for 365 Data Science platform to evaluate the impact of gamification features (XP system, leaderboards, streaks) introduced in 2022. This study examines engagement changes between Q4 2021 and Q4 2022 across different user segments.

## Business Context

In 2022, 365 Company introduced several platform enhancements:
- **XP System:** Progress tracking with level-ups and rewards
- **In-app Coins:** Exchangeable for special awards  
- **Leaderboards:** Competitive tracking with weekly rewards
- **Streaks:** Consistent learning habit motivation
- **Expanded Course Library:** Broader topic coverage

## Dataset Information

**Source:** 365 Company student engagement data  
**Time Period:** Q4 2021 vs Q4 2022  
**Privacy:** Personal information masked, dataset volume reduced for analysis  

### Variables
- `student_id`: Unique student identifier
- `student_country`: Geographic location for regional analysis
- `Paid`: Binary indicator (1 = paid account, 0 = free account)
- `minutes_watched_21`: Q4 2021 engagement minutes
- `minutes_watched_22`: Q4 2022 engagement minutes

## Methodology

### Statistical Analysis Performed
- **Descriptive Statistics:** Central tendency and variability for low-engagement users (1-100 minutes)
- **Distribution Analysis:** Skewness and kurtosis calculations
- **Confidence Intervals:** 95% confidence intervals for user segments
- **Hypothesis Testing:** Two-sample t-tests with unequal variances
- **Geographic Comparison:** US vs India engagement patterns

### Tools Used
- Microsoft Excel with Data Analysis ToolPak
- Statistical functions: T-tests, F-tests, descriptive statistics

## Key Findings

### Paid Subscribers
- Average engagement increased **708%** (34 → 273 minutes)
- Median engagement rose **53%** (26.3 → 40.3 minutes)
- Statistically significant improvement (t = -3.05, p < 0.05)

### Free Users  
- Average usage increased **363%** but median usage decreased **16%**
- High variance indicates polarized behavior patterns
- Small subset achieved high engagement while majority showed limited improvement

### Geographic Analysis
- No significant difference between US and India engagement (t = -1.21)
- Similar market potential across regions

## Business Implications

- **Premium Strategy:** Gamification features demonstrate clear ROI for paid subscribers
- **Free Tier Challenge:** Different engagement strategies needed beyond gamification
- **Market Opportunity:** Equal potential across US and India markets
- **Statistical Confidence:** All conclusions backed by rigorous testing (p < 0.05)
