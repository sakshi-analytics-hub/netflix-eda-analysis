
---

🎬 Netflix Content Insights — Exploratory Data Analysis (EDA)

Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter / Colab


---

📌 Project Overview

This project analyzes Netflix’s content dataset to uncover patterns in movies and TV shows. The goal is to understand how content is distributed across countries, genres, ratings, and time.

The analysis highlights Netflix’s content strategy, growth trends, and audience targeting using Exploratory Data Analysis (EDA) techniques.


---

🎯 Objectives

Analyze distribution of Movies vs TV Shows

Identify top content-producing countries

Explore most common genres

Study trends in content addition over time

Compare growth of Movies vs TV Shows

Examine ratings distribution

Analyze movie durations and TV show seasons

Identify frequently appearing directors and actors

Understand regional content preferences


---

📁 Project Structure

Netflix-Content-Insights/
│
├── Netflix_Content_Insights.ipynb   # Main notebook
├── netflix_titles_2021.csv         # Dataset
└── README.md                       # Documentation


---

📊 Dataset Information

Field	Details

Source	Netflix Movies & TV Shows Dataset
Platform	Kaggle
Format	CSV
Records	~8,800 titles
Columns	type, title, director, cast, country, date_added, release_year, rating, duration, listed_in


---

🧹 Data Cleaning Steps

Handled missing values in director, cast, and country fields

Converted date_added to datetime format

Split multi-value columns (country, genre, cast)

Removed duplicates

Created new features for analysis (year-wise trends)


---

📈 Analysis Performed

🔹 1. Univariate Analysis

Movies vs TV Shows distribution

Top 10 countries

Ratings distribution

Genre frequency

Movie duration distribution

TV show seasons distribution


---

🔹 2. Bivariate & Time-Series Analysis

Year-wise content addition trend

Movies added per year

TV Shows added per year

Country-wise content comparison

Rating comparison (Movies vs TV Shows)


---

🔍 Key Insights

🎥 Movies dominate Netflix’s catalog 

🌍 USA and India are major content contributors 

📈 Content growth surged after 2015 and peaked around 2018–2020 

🎭 Dramas and Comedies are the most popular genres 

🔞 TV-MA and TV-14 are the most common ratings 

📺 TV Shows have grown rapidly after 2017 

⏱️ Most movies are 80–120 minutes long 

📉 Growth stabilized after peak expansion years


---

🛠️ Technologies Used

Tool	Purpose

Python	Programming language
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib	Visualization
Seaborn	Statistical plots
Jupyter / Colab	Development environment


---

▶️ How to Run

1️⃣ Clone the Repository

git clone <your-github-link>
cd Netflix-Content-Insights

2️⃣ Install Dependencies

pip install pandas numpy matplotlib seaborn jupyter

3️⃣ Run Notebook

jupyter notebook

4️⃣ Load Dataset

df = pd.read_csv("netflix_titles_2021.csv")


---

📊 Sample Visualizations

Movies vs TV Shows (Countplot)

Top Countries (Bar Chart)

Yearly Trend (Line Plot)

Ratings Distribution

Genre Analysis

Duration Histogram


---

🚀 Future Scope

NLP analysis on descriptions

Recommendation system based on genres

Director & actor network analysis

Regional content comparison

Interactive dashboard (Power BI / Plotly)


---

📬 Contact

👩‍💻 Author: Sakshi Runghe

📧 Email: sakshi.runghe2002@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/sakshi-runghe-84a4582b2?utm_source=share_via&utm_content=profile&utm_medium=member_android

🐙 GitHub: https://github.com/sakshi-analytics-hub


---

📄 License

This project is open-source and available under the MIT License.


---

⭐ If you found this project useful, consider giving it a star!


