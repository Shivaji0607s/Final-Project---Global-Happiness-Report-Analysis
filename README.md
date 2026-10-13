# 🌍 Global Happiness Report 2019 — Data Analysis

## 📌 Project Overview

The **Global Happiness Report 2019 Analysis** is a data analysis project that explores happiness scores across countries and regions worldwide. It examines the relationship between happiness and key socioeconomic indicators, including GDP per capita, social support, healthy life expectancy, freedom to make life choices, and other contributing factors.

Using Python and popular data analysis and visualization libraries, this project performs data cleaning, exploratory data analysis (EDA), statistical analysis, correlation analysis, and graphical visualization to uncover meaningful patterns in global happiness data.

The project aims to understand how different social and economic factors are associated with reported happiness levels across countries.

## 🎯 Project Objectives

- Analyze happiness scores across countries and regions.
- Identify the countries with the highest and lowest happiness scores.
- Explore the distribution of global happiness scores.
- Investigate the relationship between happiness and GDP per capita.
- Examine the associations between happiness, social support, life expectancy, and freedom.
- Calculate descriptive statistics and correlation coefficients.
- Visualize relationships between happiness indicators.
- Generate meaningful insights from the 2019 dataset.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis and documentation |

## 📂 Project Structure

The project contains the following files:

- **2019.csv** — Dataset containing country-level happiness scores and related indicators.
- **Global_Happiness_2019_Analysis.ipynb** — Jupyter Notebook containing data loading, preprocessing, analysis, visualizations, and findings.

## 📊 Analysis Performed

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Examined the dataset's dimensions and column names.
- Inspected the first and last records.
- Reviewed data types and overall dataset structure.
- Checked for missing values and duplicate records.

### 2. Data Cleaning and Preparation
- Removed duplicate records where present.
- Standardized column names and country names.
- Converted relevant measurement columns to numeric data types.
- Prepared the dataset for statistical analysis and visualization.

### 3. Descriptive Statistical Analysis
- Calculated summary statistics for numerical columns.
- Examined the mean, median, minimum, maximum, and distribution of numerical measurements.
- Reviewed the data types of individual columns.

### 4. Happiness Score Analysis
- Identified the ten highest-scoring countries.
- Identified the ten lowest-scoring countries.
- Analyzed the distribution of happiness scores.
- Calculated the average and median happiness scores.

### 5. Correlation Analysis
Investigated relationships between happiness scores and the following indicators:

- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Other available happiness-related indicators

Correlation coefficients and a correlation heatmap help illustrate the strength and direction of relationships between numerical variables.

### 6. Data Visualization
The project includes several visualizations to make the findings easier to understand:

- Bar charts showing the top and bottom countries by happiness score.
- Histograms illustrating the distribution of happiness scores.
- Scatter plots examining relationships between happiness and socioeconomic indicators.
- Regression plots showing the relationship between GDP per capita and happiness.
- Correlation heatmaps comparing numerical indicators.
- Comparative charts of average indicator values.
- Visual comparisons of GDP per capita, social support, and happiness scores.

### 7. Key Findings
The notebook generates summary statistics and identifies the highest- and lowest-scoring countries in the dataset. It also examines correlations between happiness scores and selected socioeconomic indicators.

The results can help identify patterns in the data, although correlation alone does not establish causation.

## 📈 Expected Outcomes

After completing the analysis, users can:

- Understand the distribution of happiness scores across countries.
- Compare countries with relatively high and low happiness scores.
- Explore the association between economic prosperity and happiness.
- Examine the importance of social support, health, and freedom indicators.
- Interpret statistical summaries and correlation results.
- Develop practical experience in exploratory data analysis and visualization.

## 🚀 Getting Started

### Prerequisites

Before running the project, ensure that the following are available on your system:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Installation and Setup

1. Download or clone this repository to your local machine.
2. Open the project folder in Visual Studio Code or another Python-compatible editor.
3. Create and activate a Python virtual environment if desired.
4. Install the required libraries listed in the prerequisites.
5. Ensure that the dataset, **2019.csv**, is located in the same folder as the Jupyter Notebook.
6. Open `Global_Happiness_2019_Analysis.ipynb` in Jupyter Notebook or Visual Studio Code.
7. Run the notebook cells in sequence to reproduce the analysis and visualizations.

## 📁 Dataset Information

The project uses the **World Happiness Report 2019 dataset**, which contains country-level happiness scores, rankings, and associated indicators.

The dataset includes measurements such as:

- Overall rank
- Happiness score
- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption

These variables provide a basis for exploring differences in reported happiness and its association with economic and social conditions.

## 💡 Skills Demonstrated

This project demonstrates practical skills in:

- Python programming
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data manipulation with Pandas
- Numerical analysis with NumPy
- Descriptive statistics
- Correlation analysis
- Data visualization using Matplotlib and Seaborn
- Jupyter Notebook workflows
- Analytical thinking and interpretation of data

## 🔮 Future Improvements

Potential improvements to this project include:

- Comparing happiness reports across multiple years.
- Building an interactive dashboard with Plotly or Streamlit.
- Adding geographical visualizations using country-level maps.
- Investigating additional socioeconomic variables.
- Developing a predictive model to estimate happiness scores.
- Creating a more detailed country-by-country comparison.
- Adding automated data validation and reporting.

## ⚠️ Limitations

- The analysis focuses on the 2019 dataset rather than changes over multiple years.
- Correlations indicate statistical associations and do not prove causal relationships.
- Country-level indicators may not represent differences among individuals within each country.
- Findings depend on the quality, definitions, and coverage of the original dataset.

## 👨‍💻 Author

**Ankul Rajbhar**

Aspiring Data Analyst | Python Enthusiast

**Areas of Interest:** Python, Data Analytics, Data Visualization, and Exploratory Data Analysis.

## 📄 License

This project is intended for educational and portfolio purposes. Please refer to the original dataset's terms and attribution requirements before redistributing the data.

## 🙌 Acknowledgements

Thanks to the publishers of the World Happiness Report 2019 dataset and the open-source Python community for providing the tools and data that make this analysis possible.

---

⭐ **If you find this project useful, consider giving the repository a star on GitHub!**
