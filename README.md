# 🎶 Grammys Website Analysis 
**Analyzing audience behavior across Grammys website and The Recording Academy website**

---

## Project Overview

The Recording Academy has split itself and the Grammys into two websites:
- **[grammy.com](https://www.grammy.com/)** this website is more fans and awards focused
- **[https://www.recordingacademy.com/](https://www.recordingacademy.com/)** this website is more for professionals in the industry or education

This project aims to analyze the impact of splitting the websites by comparing the engagement and the metrics of the two websites. The analysis focuses on trends in visitors, pageviews, bounce rates, and session duration, using real-world web analytics data. 

---

## Data Description

The two datasets were used:
- `grammys_live_web_analytics.csv`
- `ra_live_web_analytics.csv`

These files will contain the following information:

- `date`: The date the data was confirmed. It is in yyyy-mm-dd format.
- `visitors`: The number of users who went on the website on that day.
- `pageviews`: The number of pages that all users viewed on the website.
- `sessions`: The total number of sessions on the website. 
- `bounced_sessions`: The total number of bounced sessions on the website.
- `avg_session_duration_secs`: The average length for all session durations
- `awards_week`: A binary flag if the dates align with marketing campaigns before and after the Grammys award ceremony was held.(1 = Yes)
- `awards_night`: The actual night that Grammy Awards event was held. (1 = Yes)

---

## Analysis Breakdown 

- Preformed exploratory data analysis using `pandas`, `numpy`, and `plotly.express`
- Compared engagement patterns during awards-related periods
- Analyzed bounce rates and session durations across both websites
- Visualized trends using interactive line and bar plots

---

## Key Findings 

- **Awards Season Spikes**: Both websites experienced major traffic increases during the Grammy awards week and night
- **Visitor Behavior**: grammy.com drew significantly more pageviews per user, suggesting more causal browsing, while recordingacademy.com users had more focused session behavior.
- **Bounce Rate Differences**: Bounce sessions were on grammy.com, possibly refelcting its more general audience and content type.

---

## Tools & Libraries 

- `pandas` for data manipulation
- `numpy` for numerical operations
- `plotly.express` for interactive visualizations

--

## To Run 

1. Download the `.ipynp` file
2. Install dependencies (if need be):
   ```bash
   pip install pandas numpy plotly

