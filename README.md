# Task 1: Exploring and Visualizing a Simple Dataset

## ✅ Objective
The goal of this task is to learn how to **load, inspect, and visualize** a dataset using Python libraries such as **pandas**, **seaborn**, and **matplotlib**.


## ✅ Dataset
- **Name:** Iris Dataset  
- **Source:** Built-in dataset from Seaborn  
- **Features:**
  - sepal_length
  - sepal_width
  - petal_length
  - petal_width
  - species (target variable)


## ✅ Steps Performed
1. **Loaded dataset** using `seaborn.load_dataset('iris')`.
2. **Inspected the dataset**:
   - Checked shape, column names, and first few records.
   - Reviewed summary statistics using `.info()` and `.describe()`.
3. **Visualized the dataset**:
   - Scatter plot (Sepal length vs Sepal width by species)
   - Histogram (Distribution of sepal length)
   - Box plot (Sepal length by species)
   - Pair plot (Overall feature comparison)
4. **Analyzed insights** from data visualizations.


## ✅ Visualizations
- **Scatter Plot**: Shows relationship between sepal length and sepal width across species.
- **Histogram**: Displays distribution of sepal length.
- **Box Plot**: Compares sepal length among species.
- **Pair Plot**: Highlights differences between species for all features.

## ✅ Tools & Libraries Used
- **Python**
- **pandas**
- **seaborn**
- **matplotlib**

## ✅ Key Insights
- *Setosa* species has the smallest petal size.
- *Virginica* species has the largest petals.
- Pair plot shows clear separation between species.
- No missing values were found in the dataset.
- 
## ✅ How to Run
1. Clone this repository:
   ```bash
   git clone <your-repository-link>
