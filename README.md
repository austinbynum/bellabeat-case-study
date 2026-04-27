# Bellabeat Fitbit Case Study: Smart Device Usage Analysis

## 📝 Project Overview
This repository contains a comprehensive data analysis project examining consumer smart device usage to guide future marketing strategies for Bellabeat, a high-tech manufacturer of health-focused products for women. 

By analyzing non-Bellabeat smart device data (Fitbit), this case study uncovers fitness, sleep, and lifestyle trends, applying them to the Bellabeat App to provide actionable, data-driven business recommendations.

> **Note:** The full, interactive analysis with code and visualizations is hosted on Kaggle.  
> 🔗 **[View the Full Interactive Notebook on Kaggle Here](INSERT_KAGGLE_LINK_HERE)**

## 🛠️ Tools & Technologies Used
* **Language:** R
* **Database Querying:** SQL (`sqldf`)
* **Data Manipulation:** `dplyr`, `tidyverse`, `lubridate`, `janitor`
* **Data Visualization:** `ggplot2`, `scales`
* **Environment:** Kaggle Jupyter Notebook

## 📊 The Data
The data used in this analysis is the **Fitbit Fitness Tracker Data** (public domain), made available via Kaggle. It contains personal fitness tracker data from 33 users, including minute-level output for physical activity, heart rate, and sleep monitoring over a 31-day period.

## 💡 Key Findings & Strategic Recommendations

Through exploratory data analysis and delta-tracking of expected vs. actual device usage, I identified three key insights and developed the following marketing strategies for Bellabeat:

### 1. Combat "Device Fatigue" with the Bellabeat Leaf
* **The Insight:** Users in the "Low" and "Medium" usage categories actively discard their devices (recording 0 steps while awake) twice as often as consistent users.
* **The Strategy:** Bellabeat should aggressively market the **Bellabeat Leaf** to these segments. By highlighting that the Leaf can be worn as a necklace or clip (eliminating "wrist fatigue") and features a 6-month battery life (eliminating daily charging friction), Bellabeat can capture the market of women who abandon standard smartwatches.

### 2. Reframe the Sleep Narrative
* **The Insight:** A multi-variable correlation analysis revealed two distinct null findings: getting more sleep does *not* correlate with taking more steps the next day, and device usage frequency has zero impact on a user's sleep quality (restlessness).
* **The Strategy:** Bellabeat should avoid marketing claims like *"Wear our tracker more to sleep better."* Instead, marketing should focus on **"Understanding Your Baseline,"** positioning the sleep tracker as a neutral tool for recovery and self-awareness rather than a hack to boost daily productivity.

### 3. Targeted Cross-Selling for the Smart Scale
* **The Insight:** Manual weight logging has extremely low overall adoption (only 8 of 33 users), but "High Use" daily wearers are significantly more likely to engage with it than casual users.
* **The Strategy:** Stop allocating marketing spend to convince casual users to log their weight. Instead, use targeted in-app push notifications to advertise Bellabeat's connected smart scale exclusively to the "High Use" segment, as they are the most likely to purchase a frictionless, auto-syncing product.

---
### 👨‍💻 Connect with Me
* **Portfolio:** [austinbynum.com](https://www.austinbynum.com)
* **GitHub:** [github.com/austinbynum](https://github.com/austinbynum)
* **LinkedIn:** [linkedin.com/in/austin-bynum-323228315](https://www.linkedin.com/in/austin-bynum-323228315/)
* **Kaggle:** [kaggle.com/austinbynumahs10](https://www.kaggle.com/austinbynumahs10)
