# Marketing Campaign Effectiveness Analysis
___

## Executive Summary:


## Business Problem:
For marketing teams, campaign effectiveness directly influences customer acquisition, engagement, and return on ads spend. In this organisation, management ran multiple marketing campaigns across different channels but lacked a clear understanding of which campaigns were driving meaningful results and which were underperforming. The objective was to analyse campaign performance data to evaluate key metrics such as impressions, conversion, and cost efficiency across campaigns.

This analysis aimed to identify high-performing channels, uncover drivers of conversion, and provide actionable insights to optimise future campaigns and improve overall marketing ROAS.

## Methodology:
1. Created database Marketing_db and a table "marketing_campaigns" using MySQL.
2. Imported CSV file and populated table.
3. Dropped two columns irrelevant for analysis - "Campaign_ID" not required since the analysis involved only a single table, while "Quarter" is wrong compared to the "Date" column in the same table, with the view to create a new "Quarter" if required.
4. A VIEW "fact_marketing_campaigns" was created from the cleaned "marketing_campaigns" table.
5. The "fact_marketing_campaigns" VIEW was imported into Power BI for visualization.

## Skills:
- SQL: data cleaning, data querying, MySQL
- Power BI: DAX measures, data visualization

## Insights & Recommendation:
### 1. Search Engine and Social Media show promising results for ROAS. More Ads budget should be invested here.

### 2. The Revenue in March and August when higher despite dips in the Ads Spend for these months. The Ad creatives might have played a role in this gains and should be replicated.

### 3. The Eastern region show promising result for ROAS. More Ads budget should be invested here.
  
### 4. 

### 5. 

___

### `Additional Materials`

#### `Marketing Campaign Effectiveness Report:`

#### `Model View:`

#### 


[Data set](https://docs.google.com/spreadsheets/d/1zKB4b_TUJ1xeMzPTr4lXjYxogQJ1bZg-/edit?usp=drive_link&ouid=112542181955809320845&rtpof=true&sd=true)
