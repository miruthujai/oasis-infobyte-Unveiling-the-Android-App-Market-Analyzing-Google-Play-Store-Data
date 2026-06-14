# 📱 Unveiling the Android App Market - Google Play Store Analysis

## 🏢 Internship Details
- **Organization:** Oasis Infobyte
- **Domain:** Data Analytics
- **Level:** Level 2
- **Project Number:** Project 4
- **Project Title:** Unveiling the Android App Market - Analyzing Google Play Store Data

---

## 📌 What is This Project About?

This project involves cleaning, categorizing, and visualizing
Google Play Store data to understand app market dynamics.
The goal is to gain in-depth insights into the Android app
market by leveraging data analytics, visualization, and
sentiment analysis on user reviews.

---

## 📁 About the Dataset

| Property | Details |
|----------|---------|
| Source | Kaggle |
| Total Rows (Apps) | 9,659 |
| Total Columns | 13 |
| Missing Values | Rating (1463), Size (1227) |
| Second Dataset | user_reviews.csv (for Sentiment Analysis) |
| File Format | CSV |

### Column Names (apps.csv):
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

## 📊 Steps Performed

### Step 1 - Data Loading
- Loaded the CSV file using Pandas
- Checked shape, columns, data types and duplicates

### Step 2 - Data Preparation (Cleaning)
- Removed duplicate rows
- Filled missing Rating values with median
- Filled missing Size values with median
- Removed rows with missing version information
- Cleaned Installs column → removed '+' and ',' → numeric
- Cleaned Price column → removed '$' → numeric
- Converted Last Updated to datetime format

### Step 3 - Descriptive Statistics
- Calculated Total Apps, Average Rating
- Found Category counts and Free vs Paid split

### Step 4 - Category Exploration
- Analyzed app distribution across top 10 categories
- Analyzed top 10 categories by total installs

### Step 5 - Metrics Analysis
- Rating distribution analysis
- App Size vs Rating relationship
- Content Rating distribution
- Correlation heatmap between Rating, Reviews, Size, 
  Installs, and Price

### Step 6 - Sentiment Analysis
- Loaded user reviews dataset
- Analyzed sentiment (Positive/Negative/Neutral) from 
  translated user reviews

### Step 7 - Interactive Visualization
Created 7+ professional charts covering categories, 
ratings, pricing, and sentiment

### Step 8 - Business Recommendations
Actionable insights derived from the full analysis

---

## 📈 Key Findings

| # | Finding |
|---|---------|
| 1 | Most apps belong to a few dominant categories |
| 2 | Majority of apps are Free |
| 3 | Average rating is above 4.0 - users prefer quality apps |
| 4 | Larger app size does not guarantee higher rating |
| 5 | Certain categories drive the highest total installs |
| 6 | User review sentiment is mostly positive |

---

## 💡 Business Recommendations

1. **Target High-Demand Categories** - focus development on 
   categories with most installs
2. **Maintain Rating above 4.0** - directly affects visibility 
   and downloads
3. **Optimize App Size** - smaller, efficient apps perform 
   equally well
4. **Free + In-App Purchases** - aligns with majority market trend
5. **Monitor User Sentiment** - respond to negative reviews 
   to improve ratings

---

## 📂 Files in This Repository

| File Name | Description |
|-----------|-------------|
| `Distribution_of_App_Ratings_on_Google_Play_Store.ipynb` | Main Python Notebook |
| `apps.csv` | Main app dataset |
| `user_reviews.csv` | User reviews dataset (for sentiment analysis) |
| `chart1_category_distribution.png` | Top 10 App Categories |
| `chart2_rating_distribution.png` | App Rating Distribution |
| `chart3_free_vs_paid.png` | Free vs Paid Apps |
| `chart4_size_vs_rating.png` | App Size vs Rating |
| `chart5_installs_by_category.png` | Top 10 Categories by Installs |
| `chart6_content_rating.png` | Content Rating Distribution |
| `chart7_heatmap.png` | Correlation Heatmap |
| `chart8_sentiment_distribution.png` | User Review Sentiment Distribution |

---

## 🚀 How to Run This Project

### Option 1 - Google Colab (Recommended for Beginners)
1. Download the `.ipynb` file from this repository
2. Go to [colab.research.google.com](https://colab.research.google.com)
3. Click **File** → **Upload notebook**
4. Upload the `.ipynb` file
5. Also upload `apps.csv` and `user_reviews.csv` to Colab files
6. Click **Runtime** → **Run all**
7. All charts will be generated automatically!

### Option 2 - Jupyter Notebook (Local)
1. Install Python on your computer
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn
3. Open the `.ipynb` file in Jupyter Notebook
4. Run all cells one by one

---

## 👨‍💻 About Me

- **Name:** Miruthu Jai
- **Internship:** Oasis Infobyte Data Analytics
- **LinkedIn:** https://www.linkedin.com/in/miruthujais/
- **GitHub:** https://github.com/miruthujai
