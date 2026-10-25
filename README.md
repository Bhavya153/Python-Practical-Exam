
# 🏃 Fitness Activity Tracker

A Python-based data analysis project built using **Jupyter Notebook**. This project helps track fitness activities, calculate workout statistics, filter activity records, and visualize fitness data through interactive analysis and charts.

## ✨ Features

- 📋 **Dataset Creation:** Creates a sample fitness dataset and saves it as a CSV file.
- 🧹 **Data Cleaning:** Converts dates to datetime format, removes duplicate records, and handles missing values.
- 🔥 **Calories Analysis:** Calculates calories burned per minute.
- 🏋️ **Activity Tracking:** Uses an object-oriented `FitnessTracker` class to manage fitness data.
- ➕ **Log Activities:** Adds new activities with duration and calories burned.
- 📊 **Fitness Metrics:** Calculates total calories, average workout duration, and total activities.
- 🔎 **Activity Filtering:** Filters records by activity type, such as Running or Walking.
- 📈 **Data Visualization:** Creates bar charts, line charts, pie charts, and correlation heatmaps.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive development environment |

## 📁 Project Structure

```text
Fitness-Activity-Tracker/
│
├── fitness_activity_tracker.ipynb
├── fitness_activities.csv
└── README.md
```

*Note: Replace `fitness_activity_tracker.ipynb` with your actual notebook filename.*

## 📊 Visualizations

### 1. Duration by Activity
A bar chart compares the total workout duration for Running, Walking, and Yoga.

### 2. Calories Burned Over Time
A line chart displays calories burned across different dates.

### 3. Activity Distribution
A pie chart shows the distribution of recorded fitness activities.

### 4. Fitness Data Correlation
A heatmap visualizes the correlation between workout duration and calories burned.

## 🚀 Getting Started

### Step 1: Install Dependencies

Run the following command in a Jupyter Notebook cell if the libraries are not already installed:

```python
%pip install pandas numpy matplotlib seaborn
```

### Step 2: Open the Notebook

Open your Jupyter Notebook file in Jupyter Notebook or JupyterLab.

### Step 3: Run the Cells

Execute the notebook cells in order from top to bottom. The notebook creates the dataset, processes the data, initializes the fitness tracker, performs calculations, and generates visualizations.

## 💻 Example Usage

Create a fitness tracker:

```python
tracker = FitnessTracker("fitness_activities.csv")
```

Calculate fitness metrics:

```python
tracker.calculate_metrics()
```

Generate a fitness report:

```python
tracker.generate_report()
```

Filter Running activities:

```python
running_data = tracker.filter_activities("Running")
print(running_data)
```

Add a new activity:

```python
tracker.log_activity("Walking", 30, 150)
```

## 🧠 What I Learned

- Working with Pandas DataFrames and CSV files.
- Cleaning and processing datasets.
- Performing numerical calculations using NumPy.
- Implementing object-oriented programming in Python.
- Grouping and filtering data.
- Creating charts using Matplotlib.
- Visualizing correlations using Seaborn.
- Building a complete data analysis workflow in Jupyter Notebook.

## 🎯 Project Objective

The main objective of this project is to demonstrate practical Python programming and data analysis skills by organizing fitness activity data, calculating useful metrics, and presenting insights through visualizations.

## ⚠️ Note

This project uses sample fitness data for educational and demonstration purposes. The recorded calories are illustrative and should not be treated as medically accurate measurements.

## 👨‍💻 Author

**Your Name**

BCA | Python | Data Analysis | Data Visualization

---

⭐ If you find this project useful, consider giving the repository a star!
