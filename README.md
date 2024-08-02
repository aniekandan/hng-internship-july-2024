# HNG Internship - July 2024

This repository contains the tasks completed as part of the HNG Internship for July 2024. The tasks focus on data analysis.

## Table of Contents

1. [Task 0: Retail Sales Data Analysis](#task-0-retail-sales-data-analysis)
2. [Task 1: Geospatial Analysis of Voting Behavior](#task-1-geospatial-analysis-of-voting-behavior)
3. [Task 3: Identifying Undervalued Companies Using Finviz](#task-3-identifying-undervalued-companies-using-finviz)

## Task 0: Retail Sales Data Analysis

**Report Title**: Rapid Insights: What I Learned from a Glance at the Kaggle Sample Retail Dataset  
**Author**: Aniekan Daniel

**Summary**: This task demonstrates how a quick analysis of retail sales data can reveal valuable insights into seasonal trends, sales patterns, and deal distributions. The objective is to review a retail sales dataset from Kaggle to identify preliminary insights. 

**Key Steps**:
1. **Dataset Familiarization**: Understanding the structure and key variables of the dataset.
2. **Data Exploration**: Conducting a quick review to identify patterns, trends, or anomalies.
3. **Visualization**: Creating bar charts and other visualizations to observe trends and distributions.
4. **Insight Identification**: Highlighting seasonal trends, deal sizes, and summary statistics.

**Code and Data**:
- Follow [this link](https://github.com/aniekandan/hng-internship-july-2024-task0) to view the complete code for this analysis.
- The dataset used is [`sales_data_sample.csv`](https://github.com/aniekandan/hng-internship-july-2024-task0/blob/main/data/sales_data_sample.csv).

The complete Technical Report can be found by following [this link](https://medium.com/@aniekandan05/rapid-insights-what-i-learned-from-a-glance-at-the-kaggle-sample-retail-dataset-0104bd55bdb4).

## Task 1: Geospatial Analysis of Voting Behavior

**Report Title**: From Polling Stations to Data Points: A Spatial Analysis of Voting Behavior  
**Author**: Aniekan Daniel

**Summary**: This study employs geospatial analysis techniques to detect voting irregularities in Akwa Ibom state’s election data, identifying and visualizing outlier polling units to enhance election integrity and transparency. The objective is to identify potential voting irregularities using geospatial analysis techniques.

**Key Steps**:
1. **Data Preparation and Initial Exploration**: Geocoding the dataset and examining its structure and contents.
2. **Spatial Clustering**: Grouping polling units based on their geographical proximity.
3. **Calculating Outlier Scores**: Measuring how each polling unit’s votes deviate from the average of its neighbors.
4. **Sorting and Visualizing Outliers**: Identifying top outliers and creating histograms and maps to visualize the results.

**Code and Data**:
- Follow [this link](https://github.com/aniekandan/hng-internship-july-2024-task1) to view the complete code for this analysis.
- The dataset used is [`AKWA IBOM_crosschecked_geocoded.csv`](https://github.com/aniekandan/hng-internship-july-2024-task1/blob/main/data/AKWA%20IBOM_crosschecked_geocoded.csv).

**Outputs**:
- The outlier scores for each party are saved in an Excel file: [`Polling_Unit_Outlier_Scores.xlsx`](https://github.com/aniekandan/hng-internship-july-2024-task1/blob/main/deliverables/Polling_Unit_Outlier_Scores.xlsx).
- Visualizations include histograms of outlier scores and maps showing the spatial distribution of outliers.

The complete Technical Report can be found by following [this link](https://medium.com/@aniekandan05/rapid-insights-what-i-learned-from-a-glance-at-the-kaggle-sample-retail-dataset-0104bd55bdb4).

## Task 3: Identifying Undervalued Companies Using Finviz

**Report Title**: Identifying Undervalued Companies Using Finviz
**Author**: Aniekan Daniel

**Summary**: This task involves analyzing companies using Finviz to identify undervalued firms by examining gross profit (GP) and gross profit growth (GPG) in comparison to their sector peers. The goal is to develop a valuation model that projects each company's true value in four years and assess if they are currently undervalued or overvalued. An additional variable will be factored into the model to enhance accuracy.

**Key Steps**:
1. **Data Collection**: Identify undervalued companies using Finviz and gather data on their GP and GPG, along with data from sector peers.
2. **Comparative Analysis**: Compare GP and GPG of the selected company with its peers, and assess current valuations.
3. **Valuation Model**: Create a model to project the company's value in four years based on GP, GPG, and sector trends.
4. **Additional Variable and Explanation**: Identify and include an additional variable (e.g., market conditions) in the model. Explain this variable and justify its impact on the company’s valuation.

**Code and Data**:
- Follow [this link](https://github.com/aniekandan/hng-internship-july-2024-task3) to view the complete code for this analysis.
- The datasets used are [found here](https://github.com/aniekandan/hng-internship-july-2024-task3/tree/main/data)

The complete Technical Report can be found in the [README](https://github.com/aniekandan/hng-internship-july-2024-task3/blob/main/README.md).

## Author

[Aniekan Daniel](https://www.datascienceportfol.io/aniekandan) is an intern at HNG, working on data analysis projects. For more information about the HNG Internship program, visit the [internship page](https://hng.tech/) or learn about how to hire elite Freelance Talent [here](https://hng.tech/hire-freelancers).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
