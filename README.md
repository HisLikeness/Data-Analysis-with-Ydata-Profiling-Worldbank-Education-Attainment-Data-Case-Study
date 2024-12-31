# Data-Analysis-with-Ydata-Profiling-Worldbank-Education-Attainment-Data-Case-Study
### Overview
The purpose of this project is to explore and analyze the 'Education Attainment And Enrolment Around The World' dataset, provided by the World Bank Group, using Pandas and ydata-profiling. The scope of this project is limited to data exploration, descriptive analysis, and identification of patterns and correlations in the dataset. The problem addressed by this project is the need to understand and analyze educational attainment rates in different countries around the world, with a focus on identifying patterns, correlations, and insights that can inform education policy and decision-making.

### Key Features
- Data profiling and exploratory analysis of the [Education Attainment And Enrolment Around The World dataset] 
- Automated report generation using **ydata-profiling**.
- Insights and visualizations for key metrics.

### Dataset
Details about the dataset:
- Source: https://drive.google.com/file/d/1v4qPmCg2AGHgUmpc-n4J5e2M8zur7t5N/view
- Description: The structure of the dataset is such that it has 626 entries, 38 Columns, a RangeIndex and 37 column (Various Age Groups) with Float64 datatype and one column (Country) is Object data type.

Columns description : 
Age[15-49]All_gradeX : Percentage of the entire population ages 15 to 49 that has completed grade X
Age[15-49]Male_gradeX : Percentage of the male population ages 15 to 49 that has completed grade X
Age[15-49]Female_gradeX : Percentage of the female population ages 15 to 49 that has completed grade X
X = [1...3]

### Requirements
A list of required libraries or dependencies:
- `pandas`
- `ydata-profiling`
- `numpy`
  
### How to Run
1. Clone this repository:  
   ```bash
   git clone <repo-url>
   cd <repo-folder>
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:  
   ```bash
   jupyter notebook ydata-profiling checkpoint 1-Education Attainment.ipynb
   ```
