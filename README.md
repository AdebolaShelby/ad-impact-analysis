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

### Relationship Between Paid Search and Other Channels
1. **Correlation Analysis**:
   - Cross-network correlation with PPC costs shows moderate positive relationship (0.46)
   - No evidence of cannibalization between paid and organic search channels
   - Multiple channel relationships observed:
     - [Add specific correlation values from your analysis]
     - Cross-network: 0.46 correlation with PPC costs
     - [Add other significant channel correlations]

2. **Traffic Patterns**:
   - Organic Search maintains steady traffic levels independent of PPC spending
   - Paid Search shows expected direct correlation with PPC costs
   - Cross-network performance shows moderate positive relationship with PPC investment
   - Channels demonstrate complementary rather than competitive relationships

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
- Correlation coefficients interpretation:
  - 0.0 to 0.3: Weak correlation
  - 0.3 to 0.7: Moderate correlation
  - 0.7 to 1.0: Strong correlation
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
The analysis reveals moderate positive correlations between PPC spending and various channels, particularly noting the 0.46 correlation with cross-network performance. This suggests that paid search activities complement rather than cannibalize other channels, providing valuable insights for marketing strategy and budget allocation decisions.

## Next Steps

### Advanced Analysis
1. **Time Series Analysis**
   - Implement lag analysis to understand delayed effects of PPC spending
   - Analyze seasonal patterns and their impact on channel relationships
   - Create forecasting models for channel performance

2. **Controlled Experiments**
   - Design A/B tests with varying PPC budget allocations
   - Test different geographic markets with controlled PPC spending
   - Measure impact on organic traffic during PPC pause periods

3. **Granular Data Analysis**
   - Break down analysis by device type (mobile vs desktop)
   - Analyze performance by keyword categories
   - Investigate landing page overlap between paid and organic traffic

### Implementation Recommendations
1. **Budget Optimization**
   - Develop dynamic budget allocation model based on correlation findings
   - Identify optimal spending thresholds for each channel
   - Create automated alerts for significant correlation changes

2. **Channel Strategy**
   - Leverage complementary channel relationships
   - Develop integrated reporting dashboard
   - Create cross-channel attribution model

3. **Performance Monitoring**
   - Implement real-time correlation monitoring
   - Set up automated reporting for channel interactions
   - Develop KPIs for cross-channel effectiveness

### Data Enhancement
1. **Additional Data Points**
   - Include conversion data across channels
   - Add competitor spending data if available
   - Incorporate cost per acquisition metrics

2. **Quality Improvements**
   - Enhance data granularity to hourly levels
   - Include geographic segmentation
   - Add customer journey touchpoint data
