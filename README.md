# Airbnb-Global-Market-Analysis
This Power BI project analyzes Airbnb market performance across listings, hosts, cities, property types, reviews, pricing, ratings, seasonality, and host trust indicators. The dashboard provides insights into market growth, city performance, room type pricing, customer satisfaction, review behavior, and verification patterns.
You’re right. Thank you for the screenshot. Now the correct KPI values are clearly visible:

# Airbnb Global Market Analysis Dashboard

## Project Background

Airbnb is a global short-term rental marketplace that connects hosts with guests looking for short-term stays. The company operates in the travel, hospitality, and property-rental industry, where key business metrics include listings, hosts, cities, property types, reviews, pricing, ratings, and host trust signals.

This Power BI project analyzes Airbnb market performance across multiple cities. The goal is to understand listing growth, city-level market share, room type pricing, guest ratings, review behavior, seasonality, and host trust indicators.

Insights and recommendations are provided on the following key areas:

- Listing Growth & Market Overview
- City and Room Type Performance
- Ratings & Customer Satisfaction
- Reviews, Seasonality & Trust Signals

This project was created using **Power BI, Power Query, and DAX**. 

An interactive Power BI dashboard can be found here: -<a href="https://drive.google.com/file/d/1_z7KCZtpWB3g7u8w2f9kJZTiKvgSYUGE/view?usp=drive_link">Dashboard</a>
## Data Structure & Initial Checks

The dashboard is built using two main tables:

- **Listings**
- **Reviews**

The dashboard summary metrics are:

- **Listings:** 279,712
- **Cities:** 10
- **Hosts:** 182,024
- **Property Types:** 144
- **Reviews:** 5,372,983

### Listings Table

The `Listings` table contains property, host, location, room type, pricing, and rating information. Important fields include:

- `listing_id`
- `host_id`
- `host_since`
- `city`
- `district`
- `room_type`
- `property_type`
- `price`
- `host_is_superhost`
- `host_identity_verified`
- `host_has_profile_pic`
- `host_total_listings_count`
- `accommodates`
- `bedrooms`
- `latitude`
- `longitude`

### Reviews Table

The `Reviews` table contains guest review activity. Important fields include:

- `review_id`
- `reviewer_id`
- `listing_id`
- `date`
- `Review Month`
- `Reviews per Reviewer`
- `Reviewers`
- `% of Monthly Reviews`
- `Cumulative % review frequency`
<img width="1145" height="803" alt="image" src="https://github.com/user-attachments/assets/184c44cf-fea6-4fdd-80af-4aa177849865" />


## Executive Summary

### Overview of Findings

The dashboard shows that Airbnb listing growth increased strongly before reaching its highest point around **2015**. Growth slowed during **2016 and 2017**, and the market was further disrupted around the **COVID-19** period.

Market activity is concentrated in a few major cities, especially **Paris, New York, and Sydney**. Room type pricing also shows clear differences, with **hotel rooms** and **entire places** priced higher than **private rooms**.


## 1. Listing Growth & Market Overview

Airbnb reached its highest number of new listings around **2015**.

After 2015, listing growth slowed during **2016 and 2017**, possibly due to market maturity and tighter local regulations.

The dashboard frames Airbnb’s growth through stages such as introduction, growth, maturity, decline, reinvention, and COVID-19 impact.

The overview page summarizes the market with **279,712 listings**, **10 cities**, **182,024 hosts**, **144 property types**, and **5,372,983 reviews**.

<img width="961" height="723" alt="image" src="https://github.com/user-attachments/assets/d486ea05-55cb-4126-a206-e4f733fce07b" />


## Insights Deep Dive

## 2. City and Room Type Performance

Paris, New York, and Sydney are the leading cities in the market share visual.

The top cities account for a large share of total activity, showing that Airbnb performance is concentrated in a few major travel markets.

Average price varies by room type:

- Hotel room: **$800**
- Entire place: **$673**
- Shared room: **$580**
- Private room: **$462**

Hotel rooms are the most expensive room type, while private rooms are the most affordable.
<img width="962" height="726" alt="image" src="https://github.com/user-attachments/assets/129bec9e-c25d-47b8-93a9-2dfe8b37de8c" />

## 3. Ratings & Customer Satisfaction

The ratings page compares cities using detailed rating categories:

- Accuracy
- Cleanliness
- Communication
- Location
- Value

The matrix heatmap shows that most cities have strong ratings overall.

Mexico City and Rio de Janeiro appear among the strongest-rated cities, with several scores around **9.7 to 9.8**.

Hong Kong and Istanbul appear weaker in some rating categories compared with other cities.
<img width="939" height="392" alt="image" src="https://github.com/user-attachments/assets/14561902-b268-47c1-b7eb-5c97ef587e08" />
<img width="938" height="414" alt="image" src="https://github.com/user-attachments/assets/d0323c70-8e41-41ab-8b72-a3f1ea4cc6c7" />

## 4. Reviews, Seasonality & Trust Signals

Most reviewers leave only one review. The review frequency chart shows that **86.3%** of reviewers reviewed once.

Around **96.4%** of reviewers reviewed two times or less, showing that repeat review behavior is limited.

The seasonality visual shows monthly review share by city, helping identify travel demand patterns throughout the year.

The trust section analyzes host identity verification and profile picture status. The dashboard shows:

- Not verified + no profile picture: **0.3%**
- Not verified + profile picture: **32.6%**
- Verified + no profile picture: **0.1%**
- Verified + profile picture: **66.9%**

This suggests that most hosts provide at least one trust signal, and around two-thirds are fully verified with a profile picture.

<img width="960" height="721" alt="image" src="https://github.com/user-attachments/assets/f9c156af-8667-44ee-b1d7-59751976e0e3" />

## Recommendations

Based on the findings, I would recommend the Airbnb marketplace strategy team to consider the following:

### 1. Focus on high-performing cities

Paris, New York, and Sydney should be prioritized for market monitoring, demand forecasting, and host support because they represent major Airbnb markets.

### 2. Improve weaker rating categories

Some cities show lower scores in categories such as cleanliness and value. Airbnb could provide hosts with clearer quality standards and improvement guidance.

### 3. Customize pricing strategy by room type

Hotel rooms and entire places have higher average prices, while private rooms are more affordable. Pricing strategy should be segmented by room type.

### 4. Strengthen host trust signals

Airbnb should encourage hosts to complete identity verification and maintain a profile picture, since trust signals are important for guest confidence.

### 5. Plan around seasonal demand

Review activity changes by month and city. Seasonal pricing, marketing, and host readiness should be planned around peak travel periods.

## Assumptions and Caveats

The dashboard uses historical Airbnb data, so findings may not reflect current market conditions.

Review activity is used as a proxy for guest engagement, but not every guest leaves a review.

Host trust analysis is based only on available fields such as identity verification and profile picture status.

Some insights are based on dashboard visuals and should be rechecked if filters or slicers are changed.

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data modeling
- Data visualization

