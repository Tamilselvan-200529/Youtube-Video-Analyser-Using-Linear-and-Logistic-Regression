# 🎥 YouTube Video Analyser Using Linear and Logistic Regression

This project performs an in-depth analysis of YouTube trending video data using **Linear Regression**, **data visualization**, and **statistical analysis** to identify insights about what makes videos trend in India.

## 📁 Dataset Sources

- 📊 **Trending Video Data**: `IN_youtube_trending_data.csv`  
- 📂 **Category Mapping**: `IN_category_id.json`  
Both datasets are sourced from the **YouTube Trending Videos Dataset** by Kaggle.

---

## 📌 Key Features

1. **Data Cleaning and Preprocessing**
   - Conversion of datetime columns
   - Handling missing values
   - Feature extraction from date fields

2. **Trend Analysis**
   - Most trending video categories
   - Top channels with frequent trending videos
   - Time taken for videos to trend after publishing
   - Duration of trend per video/category/channel

3. **Machine Learning**
   - **Linear Regression**:
     - Predicting `view_count` based on `likes` and `dislikes`
     - Evaluating using MAE, MSE, and R²
   - **Scatter Plot Analysis**:
     - Likes vs. Dislikes
     - Actual vs. Predicted Views

4. **Visualization**
   - Category-wise trend frequency
   - Top trending channels
   - Time-to-trend and duration visualized with seaborn barplots

---

## 🛠️ Tools and Libraries

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `datetime`

---

## 🧠 Insights Uncovered

- Which categories and channels trend the most
- Time it takes for different content types to trend
- Channels whose videos stay trending longer
- Relationship between likes, dislikes, and views

---

## 🏃 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Youtube-Video-Analyser-Using-Linear-and-Logistic-Regression.git
