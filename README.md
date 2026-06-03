# 🎵 Spotify Customers Churn Analysis

## 📌 Project Overview
The objective of this project is to build a data-driven predictive model that estimates the probability of a user discontinuing or canceling their Spotify subscription. This predictive framework empowers the business to proactively intervene through targeted marketing campaigns, personalized offers, or user experience enhancements—minimizing customer churn and maximizing long-term revenue growth.

---

## 🛠️ Tech Stack & Processing
* **Data Processing & EDA:** Python (`NumPy`, `Pandas`)
* **Exploratory Visualizations:** `Matplotlib`, `Seaborn`
* **Business Intelligence Dashboarding:** Power BI
* **Data Source:** User activity and subscription metrics sourced via Kaggle Datasets

---

## 📊 Core Dashboard Insights

### 1. Engagement Levels
* Low engagement strongly predicts churn.
* Users with fewer listening hours or session counts are highly likely to leave.
* Consistent listening habits act as the strongest driver of customer retention.

### 2. Subscription & Device Formats
* Premium users show significantly higher loyalty and lower churn rates than free users.
* Mobile app listeners engage heavily, while desktop-only users churn sooner due to convenience issues.

### 3. Demographics & Outliers
* Specific age groups and regional sectors display higher loyalty patterns.
* A small segment of users display extreme behavioral outliers that require isolated monitoring to avoid skewing data averages.

---

## 💡 Strategic Business Recommendations

* **Retention Campaigns:** Launch customized playlists, reminders, and target push notifications at users with declining activity metrics.
* **Premium Conversion Incentives:** Highlight ad-free features and exclusive limited-time offers to moderately active free-tier users.
* **Habit-Building Onboarding:** Deliver curated playlists and guided audio suggestions during a new user's vital first week on the platform.
* **Mobile Experience Scaling:** Continuously enhance the mobile UI and predictive recommendations to capture high-value mobile listener hours.


## 🚀 Getting Started

### Prerequisites
Install the necessary Python library stack:
```bash
pip install numpy pandas matplotlib seaborn
```

### Quick Start
1. Clone this repository to your local machine.
2. Run the processing notebooks to observe data handling, cleaning, and correlation metrics.
3. Launch the Power BI file to interactively explore user segment distributions and churn breakdowns.
