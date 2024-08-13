# Customer Journey Analytics


### Table of Contents
1. [Introduction](#intro)
2. [Objectives](#objectives)
4. [Project Organization](#organization)
3. [Key Findings](#keyfindings)
5. [Insights](#insights)
6. [File Overview](#overview)

## Introduction<a name="intro"></a>

This project delves into the analysis of user behavior data collected from 365’s online subscription-based learning platform. 
The "user journey" refers to the sequence of actions taken by users as they navigate the platform, particularly focusing on the steps leading up to a subscription purchase. 
Understanding these journeys is vital for businesses to identify the most impactful pages or sequences that drive conversions. 
Additionally, this analysis offers a deeper understanding of user behavior, helping to optimize marketing strategies and streamline the user experience by removing redundant or less effective pages.

## Objectives<a name="objectives"></a>

The primary aim of this project is to develop comprehensive tools and methodologies in Python for the analysis of user journeys on the website. 
The goal is to create robust metrics that yield valuable insights into user behavior, enabling data-driven decisions to enhance user engagement and conversion rates.

## Project Organization<a name="organization"></a>

1. **Data Exploration:** Initial exploration of user journey data to extract valuable metrics.
2. **Data Cleaning:** Implementation of preprocessing functions to ensure the data is ready for detailed analysis.
3. **Metrics Development:** Creation of functions to generate key metrics such as the number of pages visited, page importance, user destinations, page sequences, and the overall length of user journeys.
4. **Subscription Plan Analysis:** Incorporation of parameters to analyze user behavior across different subscription plans (e.g., monthly vs. annual).

## Key Findings<a name="keyfindings"></a>

The detailed results of the analysis are documented in the file user_journey_anaysis.ipynb.

## Insights<a name="insights"></a>

The analysis yielded several important insights:

* **Page Engagement Across Plans:** The Resource Center's presence is notably higher among users who opt for the annual subscription, suggesting that the high-quality resources may encourage long-term commitments.
  However, this could also be a result of pre-existing interest in long-term learning, as these users are more likely to explore the Resource Center.

* **Journey Patterns:** There is a noticeable difference in user behavior between monthly and annual subscribers.
  For instance, users on annual plans are more likely to visit the Pricing page early in their journey, indicating a readiness to purchase.
  In contrast, monthly subscribers frequently visit the Career Tracks page, which organizes courses into sequences for specific career goals.
  This suggests that monthly users may have more immediate, short-term learning objectives.

* **Session Grouping and Clutter:** The early sessions in a user’s journey can reveal initial expectations and goals, while later sessions often involve multiple log-ins and checkouts.
  Identifying these patterns can help highlight the pages that ultimately lead to a purchase, despite the clutter.

## File Overview<a name="overview"></a>

* **user_journey_raw.csv:** Contains the raw data of user journeys before any preprocessing.
* **user_journey_anaysis.ipynb:** Contains the detailed analysis of user journeys, including metrics generation and insights.
