# Netflix Content Analysis Using Python

This project focuses on analyzing Netflix’s content data using Python. It includes steps for data cleaning, analysis, and visualization to uncover key trends and insights about Netflix's content library.

## 📌 Objective

To explore and visualize Netflix content data to gain actionable insights into:
- Content type distribution (Movies vs TV Shows)
- Yearly content growth
- Top producing countries
- Popular genres and duration patterns

## 📂 Dataset

The dataset used is a public Netflix dataset containing information like:
- Title, Director, Cast  
- Country, Date Added  
- Release Year, Duration  
- Genre (listed as "Category")  
- Type (Movie or TV Show)  

## 🛠️ Technologies Used

- **Python**
- **Pandas** – data cleaning & preprocessing  
- **Matplotlib & Seaborn** – data visualization  
- **Jupyter Notebook** – development environment  

## 🔍 Steps Performed

### 1. Data Cleaning
- Removed duplicate records
- Filled missing values (`country`, `director`, `cast`)
- Converted `date_added` to datetime
- Extracted `year_added` and `month_added` for trend analysis

### 2. Data Analysis
- Distribution of content types (Movies vs TV Shows)
- Year-wise content additions
- Top contributing countries
- Popular genres and average content durations

### 3. Data Visualization
- Bar plots for content type and year-wise additions
- Word cloud for genres
- Charts for country-wise content production

## 📈 Key Insights

- ~70% of the content is **Movies**, and ~30% is **TV Shows**
- Content additions peaked in **2019**
- **United States, India, UK, Japan, and Canada** are top content producers
- Most popular genres include **International TV Shows**, **TV Dramas**, and **Comedies**

## ✅ Conclusion

This analysis provides a solid understanding of Netflix’s content strategy and user preferences. It can be extended further with recommendation models or interactive dashboards using tools like Plotly or Streamlit.

---

**⭐ Don’t forget to star the repo if you found it useful!**

