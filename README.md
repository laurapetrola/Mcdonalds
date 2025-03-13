# McDonald's Nutritional Analysis Project

## Introduction

This project is part of my journey to learn more about **Python for data analysis and data cleaning** using **Jupyter Notebooks**. As someone who is passionate about nutrition and loves eating at McDonald's (especially the McChicken!), I decided to dive into the nutritional facts of McDonald's menu items. The goal is to analyze the data, identify patterns, and create insights to better understand the nutritional value of the food I enjoy.

By working on this project, I aim to:
- Practice data cleaning and preprocessing.
- Explore data visualization techniques.
- Build interactive visualizations to make the data more accessible.
- Create a health score metric to classify menu items as "Healthy" or "Unhealthy."

---

## Project Overview

The project focuses on analyzing McDonald's nutritional data, which includes information such as:
- **Calories**
- **Total Fat**
- **Sodium**
- **Carbohydrates**
- **Dietary Fiber**
- **Protein**
- **Vitamins and Minerals (% Daily Value)**

The analysis is divided into several steps:
1. **Data Cleaning and Preprocessing:**
   - Handling missing values.
   - Normalizing data for fair comparison across different nutritional criteria.

2. **Exploratory Data Analysis (EDA):**
   - Identifying the most and least healthy items.
   - Comparing categories (e.g., burgers, desserts, drinks).

3. **Health Score Calculation:**
   - Creating a custom health score based on nutritional criteria.
   - Classifying items as "Healthy" or "Unhealthy."

4. **Interactive Visualizations:**
   - Using Plotly to create interactive charts.
   - Allowing users to explore the data dynamically.

5. **Nutritional Insights:**
   - Highlighting why certain items are classified as unhealthy (e.g., high calories, fat, or sodium).

---

## Technologies and Libraries Used

### Python Libraries
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Seaborn** and **Matplotlib**: For static data visualizations.
- **Plotly**: For interactive visualizations.

### Key Features of the Libraries
- **Pandas**: Used to load, clean, and preprocess the dataset. It also helps in calculating the health score and classifying items.
- **Seaborn/Matplotlib**: Used to create static charts like bar plots, scatter plots, and heatmaps.
- **Plotly**: Used to create interactive charts that allow users to explore the data dynamically.

---

## How to Use This Project

### Prerequisites
- Python 3.x installed.
- Jupyter Notebook installed.
- Required libraries installed (`pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mcdonalds-nutrition-analysis.git```
2. Navigate to the project directory:
   ```cd mcdonalds-nutrition-analysis```
3.Install the required libraries:
   ```pip install pandas numpy seaborn matplotlib plotly```

### Running the Project
1.Place your McDonald's dataset (e.g., ```mcdonalds.csv```) in the project directory.
2.Open the Jupyter Notebook:
   ```jupyter notebook mcdonalds_analysis.ipynb```
3.Run the cells in the notebook to perform the analysis and generate visualizations.

### Key Features of the Notebook
-**Interactive Visualizations**:
   -Bar charts showing the top 10 healthiest and unhealthiest items.
   -Scatter plots comparing calories vs. total fat.
-**Nutritional Insights**:
   -Displays detailed nutritional information for selected items.
   -Includes health classification and explanations for why an item is unhealthy (e.g., high sodium, low fiber).

## Dataset
The dataset used in this project contains nutritional information for McDonald's menu items. It includes columns such as:
-```Category``` (e.g., Burgers, Desserts, Drinks)
-```Item``` (e.g., Big Mac, McChicken, French Fries)
-```Calories```
-```Total Fat``
-```Sodium```
-```Carbohydrates```
-```Dietary Fiber```
-```Protein```
-```Vitamin A (% Daily Value)```
-```Vitamin C (% Daily Value)```
-```Calcium (% Daily Value)```
-```Iron (% Daily Value)```

## Health Score Calculation
The health score is calculated using a weighted sum of normalized nutritional values. The criteria and weights are:
-**Calories**: Weight = 3 (lower is better)
-**Total Fat**: Weight = 2 (lower is better)
-**Sodium**: Weight = 2 (lower is better)
-**Dietary Fiber**: Weight = 3 (higher is better)
-**Calcium (% Daily Value)**: Weight = 2 (higher is better)
-**Iron (% Daily Value)**: Weight = 2 (higher is better)

Items are classified as:
-**Healthy**: Health Score ≥ 7
-**Unhealthy**: Health Score < 7

## Example Insights
-**Healthiest Item**: Side Salad (High in fiber, low in calories and fat).
-**Unhealthiest Item**: Big Mac (High in calories, fat, and sodium).
-**McChicken Analysis**: The McChicken is moderately healthy but has a high sodium content, which contributes to its lower health score.

## Future Improvements
-Add more nutritional criteria (e.g., sugar content, cholesterol).
-Include recommendations for healthier alternatives.
-Export the visualizations as standalone interactive HTML files.

## Conclusion
This project has been a great way to combine my interest in nutrition with my passion for learning Python. By analyzing McDonald's nutritional data, I gained valuable insights into the healthiness of my favorite foods and improved my data analysis and visualization skills. I hope this project inspires others to explore the nutritional value of their favorite meals!😊
