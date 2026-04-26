Iris Dataset — EDA & Visualization

Task 1 — DevelopersHub Data Science Internship
Name: Muneeb Ur Rehman
Email: mu181842@gmail.com
Objective
Explore and visualize the Iris dataset to understand feature distributions, relationships, and patterns across 3 flower species.
Dataset

Source: Seaborn built-in dataset
Shape: 150 rows × 5 columns
Features: sepal_length, sepal_width, petal_length, petal_width
Target: species (setosa, versicolor, virginica)
Missing values: None ✅
Balanced: 50 samples per species ✅

Analysis & Key Findings
Scatter Plot — Sepal Length vs Petal Length clearly separates all 3 species. Setosa is completely isolated at the bottom.
Histogram — Petal length and width show bimodal distribution — setosa forms a separate spike on the left, confirming it is the most distinct species.
Box Plot — Setosa has the smallest and most consistent petal measurements. Virginica has the largest. A few outliers exist in sepal width across all species.
Correlation Heatmap:

Petal length & petal width: 0.96 (extremely strong)
Sepal length & petal length: 0.87 (strong)
Sepal width negatively correlates with petal features

Conclusion
Petal measurements are the strongest indicators for distinguishing iris species. Setosa is the most separable species — making this dataset ideal for classification tasks.
