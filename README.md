# data_analytics_template
# Homework 5 - November 17th

# Retail Consumer Behavior Analysis Project

## Project Overview
This project aims to analyze the impact of economic trends on retail consumer behavior using two primary data sources:
1. **Retail Sales Data** from the U.S. Census Bureau.
2. **Consumer Sentiment Data** from the University of Michigan’s Consumer Sentiment Index.

By combining retail sales figures with consumer sentiment scores, we can observe trends, correlations, and insights that reflect the relationship between economic conditions and retail sector performance.

## Data Sources
- **Retail Sales Data**: Monthly trade data by retail category, including sectors like food services, apparel, and electronics. Downloaded from the U.S. Census Bureau in CSV format.
- **Consumer Sentiment Data**: Consumer confidence scores accessed through the University of Michigan’s Consumer Sentiment API, capturing attitudes towards spending and economic outlook.

## Data Processing1. **Retail Sales Data**: Processed using the Pandas library to filter by category and time. Focus on columns such as `sales` and `date`.
2. **Consumer Sentiment Data**: Accessed using Python’s `requests` library. The data is stored in a Pandas DataFrame and aligned with retail sales data by date.

## Analysis Goals
- **Integrate Data**: Merge retail sales and consumer sentiment data by date to compare trends.
- **Trend Analysis**: Identify how consumer sentiment shifts correspond with retail sales changes.
- **Category Comparison**: Examine specific retail sectors (e.g., electronics, apparel) in relation to economic phases.

## Data Fields
| Field           | Type       | Description                                                      |
|-----------------|------------|------------------------------------------------------------------|
| `Date`          | DateTime   | Month and year of data observation                               |
| `Retail Category` | Text      | Retail industry classification (e.g., electronics, apparel, etc.) |
| `Sales`         | Numeric    | Monthly sales figures in USD                                     |
| `Sentiment Index` | Numeric   | Consumer sentiment score                                        |
| `Economic Phase` | Text       | Economic classification as "Expansion," "Recession," or "Stable" |

## Subfolder Name: Data Storage 
