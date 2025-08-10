# Movies Dataset Analysis & Insights

## Overview
This project performs a full analysis of a movies dataset — from raw data validation and cleaning to detailed exploratory data analysis (EDA) and storytelling.  
The goal was to uncover trends in **profitability**, **audience vs critic reception**, **worldwide gross**, and **genre/studio performance** over time.  
It also explores correlations between variables and answers key business-oriented questions about the movie industry.

---

## 📂 Project Structure
This repository contains two primary Jupyter notebooks:

1. **`main.ipynb`**  
   - **Focus**: Dataset validation and preprocessing  
   - Tasks:  
     - Import and schema validation of dataset  
     - Handling missing values  
     - Removing duplicates  
     - Ensuring consistent data types  

2. **`EDA.ipynb`**  
   - **Focus**: Exploratory Data Analysis and Visual Insights  
   - Tasks:  
     - Genre, studio, and decade distributions  
     - Profitability analysis by genre and studio  
     - Audience vs critic score comparisons  
     - Worldwide gross analysis  
     - Correlation analysis between variables  
     - Storytelling with actionable insights

---

## 📊 Dataset Information
- **Columns**:  
  - Film  
  - Genre  
  - Lead Studio  
  - Audience Score %  
  - Profitability  
  - Rotten Tomatoes %  
  - Worldwide Gross  
- **Source**: [Insert source link or description]  
- **Cleaning Steps**:  
  - Removed duplicate rows while keeping first occurrences  
  - Filled missing numeric values with means where appropriate  
  - Validated dataset schema against expected column names

---

## Key Insights
- **Popular & Profitable Genres**: *Animation* and *Adventure* consistently deliver high profits and audience scores.  
- **Studio Dominance**: *Pixar*, *Marvel Studios*, and *Disney* lead in worldwide gross; some smaller studios excel in ratings despite lower revenue.  
- **Critic Scores & Profitability**: Weak-to-moderate correlation; financial success depends heavily on marketing, branding, and genre trends.  
- **Trends Over Time**: Strong growth in global box office during the 2000s–2010s, peaking with major franchise releases.

---

## Visual Highlights
Below are some of the visualizations generated in this analysis:

- Genre distribution pie chart  
- Profitability trends over time  
- Scatter plot comparing critic vs audience scores  
- Worldwide gross bar plots by genre and studio  
- Correlation heatmap between profitability, ratings, and gross

*(You can add actual image files in a `/images` folder and link them here for GitHub.)*

---

## 💻 Technologies Used
- **Python 3.x**  
- **pandas** for data manipulation  
- **NumPy** for numerical operations  
- **matplotlib** & **seaborn** for visualizations  
- **Jupyter Notebook** for development and analysis

---

## 🚀 How to Run This Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/movies-dataset-analysis.git
   cd movies-dataset-analysis
