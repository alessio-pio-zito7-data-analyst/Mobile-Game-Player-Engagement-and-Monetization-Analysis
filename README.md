# Mobile Game Player Engagement & Monetization Analysis

## Project Overview

This data analysis project explores player engagement and monetization patterns in a mobile gaming environment using Python, Pandas, Matplotlib, and NumPy.

The analysis assumes the current date is **mid-August 2025**, providing insights based on player activity recorded from the beginning of the year up to that point.

## Business Problem

A mobile game publisher is preparing the launch of several new titles throughout **2026** and wants to better understand player engagement and spending patterns across its existing player base, with a particular focus on differences between game genres. The dataset covers player activity from **January to mid-August 2025**.

The objective of this analysis is to identify engagement and spending patterns across different player segments, generating insights that can support future engagement and in-app purchase strategies.

## Analytical Approach

The analysis followed a structured data analysis workflow:

**Data Validation & Cleaning → Exploratory Data Analysis → Feature Engineering → Player Segmentation → Data Visualization → Business Insights**

The workflow focused on understanding player engagement and monetization through data cleaning, exploratory analysis, feature engineering, engagement segmentation, and visual storytelling.

## Key Findings

- Player spending is highly concentrated among a relatively small group of users, with a small number of high-value players contributing disproportionately to total revenue.

- High player engagement does not necessarily translate into higher in-app spending, suggesting that monetization is influenced by additional behavioural factors.

- Whale players generate substantially higher revenue despite exhibiting gameplay behaviour similar or lower than Dolphin spending segments.

- Player engagement remains relatively consistent across countries, while average spending differs considerably, indicating potential regional monetization opportunities.

- Several game genres generate above-average in-app purchase revenue despite only average engagement levels, suggesting differences in monetization effectiveness.


2. Dataset Understanding
- **Rows:** 3,024 player records -
- **Columns:** 13 -
- **Granularity:** One record per player
- **Observation Period:** January 2025 – August 2025
- **Data Model:** Single-table analytical dataset

## Dataset Limitations
This dataset has several limitations that should be considered during the analysis: 
- One record represents one player.
- Individual gameplay sessions are not available.
- Individual purchase transactions are not available.
- Installation timestamps are not included.
- Purchase-related fields contain missing values because not all players make in-app purchases.

## Analytical Scope

Given the available data, this analysis focuses on:

- Player engagement
- Monetization behaviour
- Spending segmentation
- Demographic analysis
- Device comparison
- Country-level insights

The dataset does not support cohort analysis, funnel, retention analysis or session-level behavioural tracking due to the absence of installation timestamps and event-level data.

3. Data Validation and Cleaning

