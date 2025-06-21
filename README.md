# 📊 Google Play Store Data Analysis

This project presents an in-depth analysis of Google Play Store data, combining data preprocessing, visualization, sentiment analysis, machine learning, and word cloud generation to extract meaningful insights from app data and user reviews.

## 📁 Files Included

- `Play Store Data.csv` — App-level information including ratings, installs, category, size, etc.
- `User Reviews.csv` — Contains text reviews and sentiment polarity
- `NullClass Data Analysis 1.ipynb` — Full notebook with step-by-step analysis and visualizations

---

## 🔍 Features & Workflow

### 1. 🧹 Data Cleaning
- Removed nulls, and duplicates
- Standardized formats (e.g.- install counts, size units, date etc.)
- Processed categorical and numerical features

### 2. 📊 Exploratory Data Analysis & Visualizations
- Created interactive visualizations using **Plotly**:
  - Grouped bar charts of average rating and review count by number of installs
  - Pie charts of review distributions
  - Scatter plots of rating vs. size
  - Time series line chart of trend of total installs over time, etc.

### 3. ☁️ Word Cloud Generation
- Used **WordCloud** library to visualize the most frequent words in 5-star reviews
- Excluded stopwords and app names for clarity
- Helps highlight key user interests and keywords

### 4. 💬 Sentiment Analysis
- Leveraged **NLTK** and **VADER SentimentIntensityAnalyzer**
- Classified user reviews as positive, neutral, or negative
- Visualized sentiment distribution per category

### 5. 🌐 Web Integration
- Optional use of **webbrowser** module to open HTML visualizations interactively

---

## 📦 Technologies Used

- **Python**
- **Pandas & NumPy**
- **Plotly Express** (visualizations)
- **NLTK** (text processing & sentiment)
- **WordCloud** (keyword visualization)
- **Scikit-learn** (machine learning)
- **Timezone and Datetime**(to show the plot at a specific time)

---

## ▶️ How to Run

1. Clone the repository or download the files.
2. Install required packages:
   ```bash
   pip install pandas numpy plotly scikit-learn nltk wordcloud datetime pytz
   ```
3. Download the VADER lexicon:
   ```python
   import nltk
   nltk.download('vader_lexicon')
   ```
4. Open the notebook:
   ```bash
   jupyter notebook "NullClass Data Analysis 1.ipynb"
   ```

---

## 📈 Sample Outcomes

-  Most downloaded app categories
-  Word cloud showing dominant review terms
-  Sentiment trends by category
---

## 👨‍💻 Author

Developed by **Vinay Kumar** during a Data Analysis Internship with **NullClass**.
