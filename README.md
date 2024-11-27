# Real-Time Twitter Analytics Dashboard - Power BI

## Introduction

This project focuses on building a **Real-Time Twitter Analytics Dashboard** using Power BI to analyze and visualize key insights from Twitter data. The project highlights tasks such as identifying top-performing tweets, calculating engagement rates, and comparing tweets with app opens versus those without.

---

## Features

- **Top 10% Engagement Rates:** Display tweets with the highest engagement rates posted on weekdays with over 50 likes, filtered by specific time ranges and tweet word limits.
- **Top 10 Tweets by Engagement:** Identify tweets with the highest sum of retweets and likes while considering tweet impressions, date, and word count constraints.
- **Engagement Rate Comparison:** Analyze and visualize tweets with app opens versus those without, based on engagement rates and other defined filters.

---

## Prerequisites

To replicate this project, you need the following:

- **Power BI Desktop**
- **Python** installed with necessary libraries like `pandas` and `matplotlib`
- **Twitter Dataset:** A dataset containing columns like `Tweet`, `Date`, `Time`, `Likes`, `Retweets`, and `Impressions`

---

## How to Run

1. **Prepare the Dataset:**
   - Ensure your dataset includes required fields: `Tweet`, `Date`, `Time`, `Likes`, `Retweets`, `Impressions`.
   - The dataset should be cleaned and structured before importing into Power BI.

2. **Data Transformation in Power BI:**
   - Import your dataset into Power BI.
   - Use Power Query Editor to filter and clean data based on specified conditions (e.g., weekdays, time range, engagement metrics).

3. **Python Integration in Power BI:**
   - Enable Python scripting in Power BI to use Python visuals.
   - Copy the provided Python scripts to generate visualizations for:
     - Engagement rate analysis
     - Top 10 tweets by engagement
     - Comparison of tweets with/without app opens

4. **Create Visualizations:**
   - Use Power BI visuals and Python-generated charts to build your dashboard.
   - Customize appearance and interactivity based on project requirements.

---

## Project Tasks

### 1. Top Engagement Rate Chart
- **Description:** Displays tweets in the top 10% of engagement rates, meeting criteria like over 50 likes, weekdays only, specific times (1 PM–4 PM), and word count under 30.

### 2. Top 10 Tweets by Retweets & Likes
- **Description:** Lists top 10 tweets by the sum of retweets and likes, filtered for weekdays, odd-numbered dates, and word count below 30.

### 3. Engagement Rate Comparison
- **Description:** Compares tweets with and without app opens based on engagement rate, filtered for weekdays, impressions, and tweet length constraints.

---

## Challenges Faced

- **Dataset Cleaning:** Addressing inconsistencies in date and time formats.
- **Filter Optimization:** Ensuring multiple filter conditions are applied dynamically in Power BI.
- **Time Constraints:** Adapting visualizations to specific time ranges.

---

## Outcomes

- A dynamic, real-time analytics dashboard providing actionable insights on tweet performance.
- Enhanced understanding of Power BI's capabilities and Python integration for custom visualizations.

---

## Skills Acquired

- Data Visualization with Power BI
- Python scripting for advanced analytics
- Dataset preparation and cleaning
- Real-time analytics dashboard design

---

## Contact

For queries or collaboration, feel free to reach out:

**Name:** Menaka M
**Email:**  menakamohan2003@gmail.com
