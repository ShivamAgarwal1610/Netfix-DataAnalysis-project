# 🎬 Netflix Data Analysis

An exploratory data analysis (EDA) project on **Netflix's movies & TV shows dataset**, uncovering patterns in **genres, popularity, ratings, and release years**.  
The analysis includes **data cleaning, feature categorization, and insightful visualizations** to answer key business questions.

---

## 📖 Table of Contents
1. [Project Overview](#-project-overview)
2. [Dataset](#-dataset)
3. [Tools & Libraries](#-tools--libraries)
4. [Key Insights](#-key-insights)
5. [Visualizations](#-visualizations)
6. [How to Run](#-how-to-run)
7. [Conclusion](#-conclusion)

---

## 📝 Project Overview
The goal of this project is to:
- Clean and preprocess Netflix's dataset for accurate analysis.
- Categorize movies based on **Vote Average** into descriptive classes.
- Visualize trends in **genres, popularity, and yearly releases**.
- Provide actionable insights for content trends on Netflix.

---

## 📂 Dataset
The dataset contains details such as:
| Column Name       | Description |
|-------------------|-------------|
| **Title**         | Name of the movie or show |
| **Genre**         | One or more genres assigned |
| **Popularity**    | Popularity score on Netflix |
| **Vote Average**  | Average viewer rating |
| **Release Year**  | Year of release |

---

## ⚙️ Tools & Libraries
- **Python 3.x**
- **Pandas** → Data manipulation & cleaning  
- **NumPy** → Numerical computations  
- **Matplotlib / Seaborn** → Data visualization  
- **Jupyter Notebook** → Interactive analysis environment  

---

## 📊 Key Insights
1. **Most Frequent Genre** → 🎭 *Drama* (appears in ~14% of the dataset).  
2. **Highest Vote Average Category** → *Average* rating dominates.  
3. **Most Popular Movie** → *Spider-Man: No Way Home* *(Action, Adventure, Sci-Fi)*.  
4. **Least Popular Movie** → *The United States vs. Billie Holiday* *(Music, Drama, War, History, Sci-Fi, Horror)*.  
5. **Year with Most Releases** → 📅 **2020** recorded the highest number of films.

---

## 📈 Visualizations
The notebook includes:
- **Genre Distribution** 📊  
- **Popularity Trends** 📈  
- **Yearly Content Releases** 📅  
- **Vote Average Categories** 🏆  



---

## 🚀 How to Run
```bash
# Clone this repository
git clone https://github.com/yourusername/netflix-data-analysis.git

# Navigate to project folder
cd netflix-data-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Open Jupyter Notebook
jupyter notebook "Netflix Data Analysis project.ipynb"
