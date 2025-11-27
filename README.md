Iris Dataset Analysis and Visualization
📌 Objective

The goal of this project is to:

Load and explore a dataset using pandas.

Perform basic data analysis (statistics, grouping, filtering).

Visualize the dataset with matplotlib and seaborn.

Handle errors (file loading, missing values, incorrect data types).

This assignment demonstrates core skills in data wrangling, analysis, and visualization.

📂 Dataset

We use the Iris Flower Dataset (Iris.csv), which contains 150 samples of iris flowers across 3 species:

Iris-setosa

Iris-versicolor

Iris-virginica

Each sample includes:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Species

⚙️ Installation

Clone or download this project. Then install the required libraries:

pip install pandas matplotlib seaborn

📊 Project Workflow
🔹 Task 1: Load and Explore the Dataset

Load the dataset with pandas.read_csv().

Inspect the first rows with .head().

Check data types and missing values.

Handle missing values (drop or fill).

Ensure numeric columns are correctly converted.

🔹 Task 2: Basic Data Analysis

Compute summary statistics with .describe().

Perform grouping by Species and calculate average measurements.

Identify key insights such as which species has the longest petals, widest sepals, etc.

🔹 Task 3: Data Visualization

We create four visualizations:

Line Plot → Trends of Sepal Length across samples.

Bar Chart → Average Petal Length by species.

Histogram → Distribution of Sepal Width.

Scatter Plot → Sepal Length vs Petal Length (with species coloring).

Each plot includes proper titles, axis labels, and legends.

🚨 Error Handling

The script includes error handling for:

File not found (try-except).

Missing values (df.isnull().sum()).

Incorrect data types (safe numeric conversion with pd.to_numeric).

📈 Insights & Findings

Iris-setosa flowers are distinctly different (short petals, wide sepals).

Iris-virginica generally has the longest petals and sepals.

Sepal length and petal length show a positive correlation.

Petal measurements are stronger predictors of species than sepal measurements.

▶️ How to Run

Place Iris.csv in your working directory.

Run the Python script or Jupyter Notebook:

python iris_analysis.py


or open iris_analysis.ipynb in Jupyter Notebook.

View the printed analysis and generated charts.
