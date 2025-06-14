# Aircraft Risk Analysis

## Overview
This project analyzes historical aviation accident data to identify low-risk aircraft types for commercial and private acquisition. The goal is to provide data-driven recommendations to support strategic investment decisions in the aviation sector.

**[Explore the Interactive Power BI Dashboard]()**

## Business Understanding

### Stakeholder
The head of the aviation division at a company exploring entry into the aviation sector by acquiring aircraft.

### Key Business Questions:
1. What are the key factors contributing to aircraft risk?
2. Which aircraft types have the historically safest records?
3. What three specific aircraft models should the company prioritize for purchase?

## Data Understanding and Analysis

### Source of Data
The dataset comes from the National Transportation Safety Board (NTSB) and contains over 90,000 aviation accident records from 1962-2023.

### Data Description
The dataset includes 31 columns with information about:
- Aircraft specifications (Make, Model, Engine Type, etc.)
- Accident details (Date, Location, Weather Conditions)
- Outcomes (Injuries, Damage, Fatalities)
- Flight details (Phase, Purpose)

Key features selected for analysis:
- Make & Model
- Aircraft damage
- Injury severity
- Number of engines
- Weather conditions
- Phase of flight

### Data Visualizations

1. **Trend of Aircraft Incidents Over Time**
   - Shows how incident rates have evolved from 1962-2023
   - Reveals whether overall risk has increased or decreased
   - Helps identify patterns related to industry regulations and technological advancements

2. **Aircraft Risk by Manufacturer**
   - Compares accident rates across different aircraft manufacturers
   - Visualizes which brands have the best safety records
   - Helps identify potentially safer manufacturers

3. **Accident Severity by Engine Type**
   - Analyzes whether single vs. multi-engine aircraft show different risk profiles
   - Examines how different engine technologies correlate with incident severity
   - Provides insights into engine-related safety factors

## Power BI Dashboard
[![Power BI Dashboard Screenshot](https://example.com/path-to-screenshot.png)](https://app.powerbi.com/link-to-your-dashboard)

Explore the interactive version of these visualizations and more in our [Power BI Dashboard](https://app.powerbi.com/link-to-your-dashboard). The dashboard allows you to:

- Filter by time period, aircraft type, and manufacturer
- Drill down into specific accident details
- Compare safety metrics across different dimensions
- Download customized reports

## Conclusion

### Summary of Findings:
1. **Modern aircraft show improved safety**: Analysis reveals a general trend of decreasing accident rates over time, particularly for aircraft manufactured after 2000.

2. **Certain manufacturers demonstrate consistently better safety records**: The analysis identified three manufacturers whose models showed significantly lower accident rates and less severe outcomes.

3. **Engine configuration impacts safety**: Multi-engine aircraft demonstrated lower fatality rates in accidents compared to single-engine models, particularly in adverse weather conditions.

### Recommendations:
Based on the analysis, three aircraft models are recommended for acquisition due to their combination of:
- Low accident rates
- Minimal severe outcomes when accidents occur
- Reliability across different flight conditions
