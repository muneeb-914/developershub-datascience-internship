# Iris Dataset — Exploratory Data Analysis & Visualization

## Objective
Explore and visualize the Iris dataset to understand feature distributions, relationships, and patterns across 3 flower species using Python.

## Dataset
- **Source:** Seaborn built-in dataset
- **Shape:** 150 rows × 5 columns
- **Features:** sepal_length, sepal_width, petal_length, petal_width
- **Target:** species (setosa, versicolor, virginica)
- **Missing Values:** None
- **Class Balance:** 50 samples per species

## Approach
1. Loaded dataset directly using seaborn
2. Explored structure using `.shape`, `.dtypes`, `.describe()`
3. Analyzed missing values and class distribution
4. Created 4 visualizations to understand the data

## Visualizations
| Chart | Purpose |
|-------|---------|
| Scatter Plot | Sepal Length vs Petal Length by species |
| Histogram | Feature distribution across all columns |
| Box Plot | Spread and outliers per species |
| Correlation Heatmap | Relationships between all features |

## Results & Insights
- **Zero missing values** — perfectly clean dataset
- **Setosa is completely separable** from other species based on petal measurements
- **Petal length & width correlation: 0.96** — extremely strong relationship
- **Sepal length & petal length correlation: 0.87** — strong relationship
- **Petal measurements** are the strongest indicators for distinguishing species
- Histograms show **bimodal distribution** in petal features — setosa forms a separate cluster

## Technologies Used
- Python
- Pandas
- Seaborn
- Matplotlib
- NumPy
