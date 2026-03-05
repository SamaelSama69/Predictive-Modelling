::: {align="center"}
# 📊 OTT Content Viewership Prediction

### Machine Learning Project -- Predictive Modelling with Linear Regression
:::

------------------------------------------------------------------------

# 🚀 Project Overview

OTT platforms rely heavily on **data-driven decision making** to
maximize content performance.

This project builds a **predictive machine learning model** to determine
the key drivers of **first‑day content viewership** using platform data
such as:

-   Platform visitors
-   Advertising exposure
-   Trailer engagement
-   Release timing
-   Genre of content

The goal is to help OTT platforms **optimize release strategies,
marketing investment, and content planning.**

------------------------------------------------------------------------


# 📂 Dataset

The dataset contains **1000 records and 8 variables** describing OTT
content performance.

  Feature              Description
  -------------------- ------------------------------------------------
  visitors             Avg. platform visitors in past week (millions)
  ad_impressions       Advertising impressions
  major_sports_event   Indicates presence of major sports event
  genre                Genre of content
  dayofweek            Release day
  season               Season of release
  views_trailer        Trailer views
  views_content        First‑day content views *(Target)*

------------------------------------------------------------------------

# 🔍 Exploratory Data Analysis

EDA was performed to understand relationships between features.

Key analyses:

• Distribution plots\
• Correlation heatmap\
• Genre analysis\
• Release day patterns\
• Seasonal patterns\
• Outlier detection

### Key Findings

-   **Trailer views strongly correlate with content views**
-   **Platform visitors drive viewership**
-   **Ad impressions show weak correlation**
-   **Weekend releases perform better**
-   **Sports events reduce OTT engagement**

------------------------------------------------------------------------

# ⚙️ Feature Engineering

The following transformations were applied:

• One‑Hot Encoding for categorical variables\
• Cyclical encoding for time features\
• Log transformations for skewed variables\
• Interaction features\
• Engagement metrics\
• Feature scaling

These expanded the dataset to **28 engineered features**.

------------------------------------------------------------------------

# 🤖 Machine Learning Model

Model used:

### Linear Regression

Target variable:

    views_content

The model predicts **first‑day content viewership** based on marketing
and platform metrics.

------------------------------------------------------------------------

# 📈 Model Performance

  Metric        Train    Test
  ------------- -------- --------
  MAE           0.0389   0.0399
  MSE           0.0024   0.0025
  RMSE          0.0489   0.0500
  R²            0.7868   0.7743
  Adjusted R²   ---      0.7661

The model explains **\~77% of the variance in content viewership.**

------------------------------------------------------------------------

# 🧪 Regression Diagnostics

Model assumptions were validated using:

✔ Residual vs Fitted plots\
✔ Q‑Q plots\
✔ Shapiro‑Wilk test\
✔ Variance Inflation Factor (VIF)

Multicollinearity detected in:

-   visitors
-   ad_impressions

------------------------------------------------------------------------

# 💡 Key Insights

### 📈 Platform Traffic

Higher visitor numbers significantly increase content views.

### 🎬 Trailer Engagement

Trailer views are the **strongest predictor** of first‑day viewership.

### 📅 Release Timing

Weekend releases attract more engagement.

### ⚽ Sports Competition

Major sports events reduce OTT viewership.

### 🎭 Genre Impact

Certain genres consistently outperform others.

------------------------------------------------------------------------

# 📊 Business Recommendations

### Increase Platform Traffic

Promotions, partnerships, and marketing campaigns can increase visitors.

### Optimize Release Timing

Avoid clashes with major sports events.

### Invest in Trailer Marketing

High‑quality trailers drive anticipation and engagement.

### Genre‑Focused Strategy

Invest more in high‑performing genres.

### Seasonal Planning

Align releases with periods of higher platform activity.

------------------------------------------------------------------------

# 🛠 Tech Stack

  Category           Tools
  ------------------ ---------------------
  Programming        Python
  Data Analysis      Pandas, NumPy
  Visualization      Matplotlib, Seaborn
  Machine Learning   Scikit‑Learn
  Environment        Jupyter Notebook

------------------------------------------------------------------------

# 📁 Project Structure

    OTT-Viewership-Prediction
    │
    ├── data
    │   └── dataset.csv
    │
    ├── notebooks
    │   └── predictive_modelling.ipynb
    │
    ├── report
    │   └── predictive_modelling_report.pdf
    │
    ├── images
    │   └── visualizations
    │
    └── README.md

------------------------------------------------------------------------

# ⭐ Future Improvements

-   Random Forest
-   Gradient Boosting
-   XGBoost
-   Feature selection
-   Model deployment
-   Interactive dashboard

------------------------------------------------------------------------

# 👨‍💻 Author

**Sham Solanki**\
Masters in Data Science -- Deakin University

------------------------------------------------------------------------

# 📜 License

MIT License
