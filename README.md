# Customer Engagement Analysis: Statistical Impact Assessment

## Project Overview

Statistical analysis of student engagement data for 365 Data Science platform to evaluate the impact of gamification features (XP system, leaderboards, streaks) introduced in 2022. This study examines engagement changes between Q4 2021 and Q4 2022 across different user segments using rigorous statistical methods.

## Business Context

In 2022, 365 Company introduced several platform enhancements:
- **XP System:** Progress tracking with level-ups and rewards
- **In-app Coins:** Exchangeable for special awards  
- **Leaderboards:** Competitive tracking with weekly rewards
- **Streaks:** Consistent learning habit motivation
- **Expanded Course Library:** Broader topic coverage

## Dataset Information

**Source:** 365 Company student engagement data  
**Time Period:** Q4 2021 vs Q4 2022 comparison  
**Privacy:** Personal information masked, dataset volume reduced for analysis  
**Geographic Scope:** US and India markets only 

### Variables
- `student_id`: Unique student identifier
- `student_country`: Geographic location (US vs India comparison)
- `Paid`: Binary indicator (1 = paid account, 0 = free account)
- `minutes_watched_21`: Q4 2021 engagement minutes
- `minutes_watched_22`: Q4 2022 engagement minutes

## Methodology

### Statistical Analysis Performed
- **Descriptive Statistics:** Central tendency and variability measurements for user segments
- **Distribution Analysis:** Skewness and kurtosis calculations to understand behavioral patterns
- **Confidence Intervals:** 95% confidence intervals for different user groups
- **Hypothesis Testing:** Two-sample t-tests with unequal variances for statistical validation
- **Comparative Analysis:** US vs India engagement pattern examination

### Tools Used
- Microsoft Excel with Data Analysis ToolPak
- Statistical functions: T-tests, F-tests, descriptive statistics

## Key Findings

### Paid Subscribers
- Average engagement increased **708%** (34 → 273 minutes)
- Median engagement rose **53%** (26.3 → 40.3 minutes)
- Statistically significant improvement (t = -3.05, p < 0.05)
- Results indicate widespread positive response to gamification features

### Free Users  
- Average usage increased **363%** but median usage decreased **16%**
- High variance (468.93 vs 26.23) indicates polarized behavior patterns
- Small subset achieved high engagement while majority showed limited response
- Statistical evidence suggests different user response patterns to gamification

### Geographic Analysis (US vs India)
- No statistically significant difference in engagement patterns (t = -1.21)
- 95% confidence intervals support similar behavioral responses across both markets
- Consistent platform performance regardless of geographic location

## Statistical Conclusions

### Key Insights
- **Gamification Effectiveness:** Features demonstrate statistically significant engagement impact for paid users (p < 0.05 significance level)
- **User Segmentation:** Free users exhibit polarized response patterns, with majority maintaining baseline engagement levels
- **Geographic Consistency:** No significant behavioral differences between US and India user bases
- **Statistical Reliability:** All findings validated through rigorous hypothesis testing and confidence interval analysis

### Limitations
- Analysis limited to two geographic markets (US and India)
- Dataset reduced for practical analysis while maintaining representative patterns
- Focus on engagement metrics only (watch time), not conversion or revenue impact

## Technical Notes
- All statistical tests performed at 95% confidence level
- Appropriate handling of unequal variances in t-test procedures
- Comprehensive descriptive analysis supporting hypothesis testing conclusions
