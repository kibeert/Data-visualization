# Data-visualization
# 📊 Student Performance Analysis

This project analyzes student performance data to uncover how factors like gender, race/ethnicity, parental education level, lunch type, and test preparation affect scores in math, reading, and writing.

## Objectives

- Understand the relationship between student demographics and academic performance
- Identify key factors that influence test scores
- Use visualizations to gain insights from the data
- Build a machine learning model to predict student performance

## 🗃 Dataset

The dataset contains the following features:

- `gender`: student's gender (`female`/`male`)
- `race/ethnicity`: student's group (A to E)
- `parental level of education`: highest education level of the parent(s)
- `lunch`: lunch type (`standard` or `free/reduced`)
- `test preparation course`: course status (`completed` or `none`)
- `math score`, `reading score`, `writing score`: scores (0–100)

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (for ML modeling)
- Jupyter Notebook / Google Colab

## 📌 Key Research Questions

1. Does gender affect performance in math, reading, and writing?
2. What role does parental education play in student achievement?
3. Are students who complete test preparation courses more likely to score higher?
4. How does lunch type correlate with academic performance?
5. Can we predict student scores based on demographic features?

## 📈 Visualizations

- Distribution plots of test scores
- Comparison of scores by gender, race, lunch, and test prep
- Correlation heatmaps
- Boxplots and violin plots for deep insights

##  Machine Learning

We trained a model to predict student performance using:

- Classification: Performance category (e.g., high, medium, low)
- Regression: Predict actual test scores

##  How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-analysis.git
   cd student-performance-analysis
