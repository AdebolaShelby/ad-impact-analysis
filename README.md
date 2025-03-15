# Correlation vs Causation - Ad Impact Analysis

## Project Overview
The objective of this project is to statistically analyze whether Paid Search is cannibalizing Organic Search through a combination of correlation analysis, causal inference techniques, and controlled experiments.

## Data Processing & Methodology

### Data Cleaning and Preprocessing
- **Campaign Performance Data**:
  - Removed unnecessary columns (Currency code, CTR, Avg. CPC, etc.)
  - Standardized date formats
  - Converted string dates to datetime format

- **Google Analytics (GA4) Data**:
  - Created date components (Year, Month, Day)
  - Aggregated metrics by channel, year, and month
  - Filtered out irrelevant channels (Display, Email, Referral, SMS, etc.)
  - Focused on primary channels: Organic Search, Paid Search, and Direct

### Analysis Focus
The analysis primarily concentrates on 2023-2024 data due to:
- Data recency and relevance to current market conditions
- Complete and consistent GA4 data availability
- More reliable comparison between channels
- Better reflection of current marketing strategies

## Key Findings

### Relationship Between Paid Search and Organic Search
1. **Correlation Analysis**:
   - Positive trend observed between PPC costs and organic search sessions
   - No evidence of cannibalization between paid and organic search
   - Both channels show independent seasonal patterns

2. **Traffic Patterns**:
   - Organic Search maintains steady traffic levels
   - Paid Search shows more variation in traffic
   - Channels appear to complement rather than cannibalize each other

3. **Channel Performance (2024 Snapshot)**:
   - Organic Search:
     - February: 176,548 sessions
     - May: 171,732 sessions
     - July: 194,749 sessions
   - Paid Search:
     - February: 102,637 sessions
     - May: 99,269 sessions
     - July: Shows fluctuating patterns

## Important Considerations
- Correlation does not imply causation
- Analysis accounts for:
  - Seasonality
  - Market conditions
  - Recent changes in search algorithms
  - Post-pandemic traffic patterns

## Methodology Notes
- Focus on primary channels (Organic Search, Paid Search, Direct) for targeted analysis
- Excluded channels with insufficient or inconsistent data
- Used recent data (2023-2024) for more actionable insights
- Applied statistical analysis to understand channel relationships

## Conclusions
The analysis suggests that paid search complements rather than cannibalizes organic search traffic. This relationship provides valuable insights for marketing strategy and budget allocation decisions.
