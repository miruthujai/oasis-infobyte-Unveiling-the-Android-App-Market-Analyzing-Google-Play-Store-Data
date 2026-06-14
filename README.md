# 📱 Unveiling the Android App Market - Analyzing Google Play Store Data

## 🏢 Internship Details
- **Organization:** Oasis Infobyte
- **Domain:** Data Analytics
- **Level:** Level 2
- **Project Number:** Project 4
- **Project Title:** Unveiling the Android App Market - Analyzing Google Play Store Data

---

## 📌 What is This Project About?

In this project, I worked with a Google Play Store dataset.
The goal was to clean, categorize, and visualize the data to
understand app market dynamics and gain in-depth insights into
the Android app market by leveraging data analytics,
visualization, and sentiment analysis on user reviews.

---

## 📁 About the Dataset

| Property | Details |
|----------|---------|
| Source | Kaggle |
| Total Rows | 9,659 |
| Total Columns | 13 |
| Missing Values | Rating (1463), Size (1227) |
| Second Dataset | user_reviews.csv (for Sentiment Analysis) |
| File Format | CSV |

### Column Names:
1. **App** - Name of the application
2. **Category** - Category of the app
3. **Rating** - User rating of the app (1-5)
4. **Reviews** - Number of user reviews
5. **Size** - Size of the app (in MB)
6. **Installs** - Number of installs
7. **Type** - Free or Paid
8. **Price** - Price of the app
9. **Content Rating** - Target age group
10. **Genres** - Genre of the app
11. **Last Updated** - Last update date
12. **Current Ver** - Current version
13. **Android Ver** - Required Android version

---

## 🛠️ Tools and Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Programming Language |
| Pandas | Data Loading and Cleaning |
| NumPy | Numerical Calculations |
| Matplotlib | Creating Charts |
| Seaborn | Beautiful Visualizations |
| Google Colab | Online Coding Platform |

---

## 📊 Steps I Performed

### Step 1 - Data Loading
- Loaded the CSV file using Pandas
- Checked the shape, columns, and data types

### Step 2 - Data Preparation (Cleaning)
- Removed duplicate rows
- Filled missing Rating values with median
- Filled missing Size values with median
- Removed rows with missing Current Ver / Android Ver
- Cleaned Installs column → removed '+' and ',' → numeric
- Cleaned Price column → removed '$' → numeric
- Converted Last Updated to datetime format

### Step 3 - Descriptive Statistics
- Calculated Total Apps Analyzed = 9,659
- Calculated Average Rating = 4.17 / 5.0
- Found Total Categories
- Found Free Apps and Paid Apps count

### Step 4 - Category Exploration
- Analyzed app distribution across top 10 categories
- Analyzed top 10 categories by total installs

### Step 5 - Metrics Analysis
- Analyzed rating distribution
- Compared app size vs rating
- Analyzed content rating distribution
- Created correlation heatmap between Rating, Reviews,
  Size, Installs and Price

### Step 6 - Sentiment Analysis
- Loaded user reviews dataset
- Analyzed sentiment (Positive/Negative/Neutral) from
  translated user reviews

### Step 7 - Data Visualization
Created 8 professional charts:
- Horizontal Bar - Top 10 App Categories
- Histogram - App Rating Distribution
- Pie Chart - Free vs Paid Apps
- Scatter Plot - App Size vs Rating
- Bar Chart - Top 10 Categories by Installs
- Bar Chart - Content Rating Distribution
- Heatmap - Correlation Between Variables
- Bar Chart - User Review Sentiment Distribution

### Step 8 - Business Recommendations
Provided actionable insights based on analysis

---

## 📈 Key Findings

| # | Finding |
|---|---------|
| 1 | **Total Apps Analyzed = 9,659** |
| 2 | **Average Rating = 4.17** out of 5.0 |
| 3 | Few categories dominate the app market |
| 4 | Majority of apps are **Free** |
| 5 | Certain categories drive the highest total installs |
| 6 | User review **sentiment is mostly positive** |

---

## 💡 Business Recommendations

1. **Target High-Demand Categories** - Focus development on categories with most installs
2. **Maintain Rating above 4.0** - Directly affects visibility and downloads
3. **Optimize App Size** - Smaller, efficient apps perform equally well
4. **Free + In-App Purchases** - Aligns with majority market trend
5. **Monitor User Sentiment** - Respond to negative reviews to improve ratings

---

## 📂 Files in This Repository

| File Name | Description |
|-----------|-------------|
| `Android_App_Market_Analysis.ipynb` | Main Python Jupyter Notebook with all code |
| `apps.csv` | Main app dataset used for analysis |
| `user_reviews.csv` | User reviews dataset for sentiment analysis |
| `chart1_category_distribution.png` | Horizontal Bar - Top 10 App Categories |
| `chart2_rating_distribution.png` | Histogram - App Rating Distribution |
| `chart3_free_vs_paid.png` | Pie Chart - Free vs Paid Apps |
| `chart4_size_vs_rating.png` | Scatter Plot - App Size vs Rating |
| `chart5_installs_by_category.png` | Bar Chart - Top 10 Categories by Installs |
| `chart6_content_rating.png` | Bar Chart - Content Rating Distribution |
| `chart7_heatmap.png` | Heatmap - Correlation Between Variables |
| `chart8_sentiment_distribution.png` | Bar Chart - User Review Sentiment Distribution |

---

## 🚀 How to Run This Project

### Option 1 - Google Colab (Recommended for Beginners)
1. Download `Android_App_Market_Analysis.ipynb` from this repository
2. Go to [colab.research.google.com](https://colab.research.google.com)
3. Click **File** → **Upload notebook**
4. Upload the `.ipynb` file
5. Also upload `apps.csv` and `user_reviews.csv` to Colab files
6. Click **Runtime** → **Run all**
7. All charts will be generated automatically!

### Option 2 - Jupyter Notebook (Local)
1. Install Python on your computer
2. Install required libraries:

---

## 👨‍💻 About Me

- **Name:** Miruthu Jai
- **Internship:** Oasis Infobyte Data Analytics
- **LinkedIn:** https://www.linkedin.com/in/miruthujais/
- **GitHub:** https://github.com/miruthujai

🏷️ Tags #oasisinfobyte #oasisinfobytefamily #internship #python #datacleaning #datanalytics #pandas #matplotlib #seaborn #datascience
