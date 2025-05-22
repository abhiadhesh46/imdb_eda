# 🎬 IMDb Movie Data Analysis (2006-2016)

![banner](data:image/jpeg;base64,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)

Welcome to my IMDb Movie Analysis project — a deep dive into the world of cinema from 2006 to 2016. In this exploratory data analysis (EDA) journey, I’ve uncovered trends, visualized insights, and highlighted the brightest stars and genres of the silver screen 🌟.

---

## 📌 Dataset

The dataset used in this project is from [Kaggle - IMDb Movie Dataset](https://www.kaggle.com/datasets) and includes information such as:
- Movie Title
- Release Year
- Genre
- IMDb Rating
- Duration
- Director
- Cast (Stars)
- Number of Votes (if available)

---

## 🔍 What’s Inside?

- ✨ Cleaned and transformed dataset
- 📊 Visually rich charts using Matplotlib and Seaborn
- 🎭 Genre analysis, rating distributions, and yearly trends
- 👥 Top actors & directors by frequency and rating
- 🧠 Smart filtering (e.g. actors with 3+ movies)
- 🎨 Beautiful headings and storytelling in the Jupyter notebook

---

## 🖼️ Sample Visualizations

### 🎬 Top Rated Movies
![top-movies](sample-images/top_movies.png)

### 👑 Most Frequent Actors
![top-actors](sample-images/top_actors.png)

### 🎭 Genre-wise Rating Distribution
![genre-ratings](sample-images/genre_ratings.png)

### 📅 Movie Releases by Year
![release-trend](sample-images/release_trend.png)

> **📁 To add these images:**  
> Create a folder in your repo named `sample-images` and upload your charts as `.png` images with matching names.  
> Use `plt.savefig("sample-images/top_movies.png")` before `plt.show()` to export them directly from Colab!

---

## 🚀 How to Run This Notebook

1. Clone this repository or download the `.ipynb` file  
2. Open with [Google Colab](https://colab.research.google.com/)  
3. Upload the IMDb dataset CSV (from Kaggle)  
4. Run each cell to explore insights, interact with the data, and visualize results

---

## 🧠 Skills Demonstrated

- Data Cleaning & Preprocessing
- Pandas DataFrame Operations
- Exploratory Data Analysis (EDA)
- Data Visualization with Seaborn & Matplotlib
- Insight extraction and storytelling
- Actor/director frequency and performance analysis

---

## 💡 Future Improvements

- Add interactive Plotly visualizations
- Build a Streamlit dashboard
- Compare IMDb ratings to external scores (like Rotten Tomatoes or Metacritic)
- Create a movie recommendation engine based on genres or actors

---

## 🧑‍💻 Author

**Abhi Adhesh G**  
Final Year Computer Science & Engineering Student  
Aspiring Data Scientist, EDA Enthusiast, Visual Storyteller  
[LinkedIn](https://www.linkedin.com/in/your-profile) • [GitHub](https://github.com/your-profile)

---

## ⭐ Like This Project?

Drop a ⭐ on the repo if you enjoyed the journey!  
Movies and data — the perfect crossover 🍿📈

