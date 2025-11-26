# Iris Dataset Exploration and Visualization

## 📊 Project Overview
This Jupyter Notebook provides a comprehensive exploration and visualization of the famous **Iris dataset**. The project demonstrates fundamental data analysis techniques including data loading, inspection, summarization, and visualization using popular Python libraries.

## 🎯 Objective
Understand how to read, summarize, and visualize a dataset using Python's data science ecosystem.

## 📁 Dataset
**Iris Dataset** - A classic dataset in pattern recognition containing measurements of 150 iris flowers from three species:
- Setosa
- Versicolor  
- Virginica

**Features:**
- `sepal_length` (cm)
- `sepal_width` (cm)
- `petal_length` (cm)
- `petal_width` (cm)
- `species` (categorical)

## 🛠️ Technologies Used
- **Python 3**
- **Pandas** - Data manipulation and analysis
- **Seaborn** - Statistical data visualization
- **Matplotlib** - Comprehensive plotting library
- **Jupyter Notebook** - Interactive development environment

## 📈 Visualizations
The notebook creates three types of visualizations:

### 1. Scatter Plot
- Analyzes relationships between different variables
- Helps identify correlations and patterns

### 2. Histogram  
- Examines data distribution patterns
- Shows frequency distributions of features

### 3. Box Plot
- Detects outliers in the data
- Visualizes spread and quartiles of values

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas seaborn matplotlib jupyter
```
## Usage

1. Clone the repository

2. Navigate to the project directory

3. Launch Jupyter Notebook:

```bash
jupyter notebook iris_dataset.ipynb
```
4. Run cells sequentially to reproduce the analysis

## File Structure
```
├── iris_dataset.ipynb    # Main notebook with analysis
├── iris.csv             # Dataset file (auto-generated)
└── README.md           # Project documentation
```

## Skills Demonstrated

- ✅ Data loading and inspection using pandas
- ✅ Basic data summarization techniques
- ✅ Data visualization with matplotlib and seaborn
- ✅ Exploratory Data Analysis (EDA) fundamentals
- ✅ Handling categorical and numerical data
- ✅ Statistical plotting and chart interpretation
  
## 📋 Code Structure
The notebook is organized into clear steps:

1. Import Libraries - Load required dependencies

2. Load Dataset - Load Iris data from seaborn and save to CSV

3. Inspect Data - Examine shape, columns, head/tail, and info

4. Visualizations - Create scatter plots, histograms, and box plots
   
## 🔍 Key Insights
- Dataset contains 150 samples with 5 columns (4 features + 1 target)

- No missing values in the dataset

- Features are numerical (float64), target is categorical (object)

- Visualizations reveal clear separations between species
  
## 📄 License
This project is open source and available under the MIT License.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
