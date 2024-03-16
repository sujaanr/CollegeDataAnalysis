# College Data Analysis

This script is designed to analyze and classify college data using Python. It utilizes several popular Python libraries, including pandas, matplotlib, seaborn, and scikit-learn, as well as various machine learning algorithms.

## Functionality 

analyze_college_data(data_path): This function loads the college dataset from the specified path and performs data analysis and visualization. sers can anticipate a detailed exploration of the dataset, showcasing:

- Dataset summaries to grasp the essentials at a glance.

- Correlation heatmaps to understand inter-variable relationships.

- Scatter plots and kernel density estimation plots to uncover distribution and density of data points.

- Additional graphical insights to enrich understanding of the dataset's characteristics.


classify_college_data(data_path): This function, also loads the dataset from a specified path but focuses on data preprocessing, feature selection, and model training. It employs multiple classification algorithms, returning critical evaluation metrics such as recall, accuracy, precision, and the F1 score for each model, thus facilitating a comprehensive model comparison.

## Technical Stack

Data Processing: Utilizes pandas for efficient data manipulation and analysis.

Visualization: Employs Matplotlib and seaborn for creating insightful and aesthetically pleasing visualizations.

Machine Learning Models: Incorporates a suite of models from the sci-kit-learn library, including but not limited to Random Forest, Support Vector Machine, Logistic Regression, K-Nearest Neighbors, Naive Bayes, Decision Tree, AdaBoost, Gradient Boosting, XGBoost, and CatBoost, for robust data classification.

## How to Run the Program

Download and Prepare: Download CollegeDataAnalysis to your local machine. Make sure the 'College_Data.csv' file resides in the working directory or adjust the file path as needed.

Execute the Script: Run the program on your local machine to kickstart the analysis and classification processes.

Review the Output: The script generates a comprehensive output report, 'output_report.pdf', encapsulating various analyses and visualizations for in-depth insights into the college dataset. This includes descriptive visualizations like pie charts, countplots, and barplots to illustrate different facets of the college data.

# Example of Running the Program

1. Run the program using the provided execution instructions.
2. The program will automatically load the 'College_Data.csv' file for analysis.
3. Ensure the CSV file is present in the /content/ directory.
4. The results of the analyses and visualizations will be saved in 'output_report.pdf' and can be viewed for insights into the college dataset.
5. Descriptive visualizations and analytics (e.g., pie charts, countplots, barplots) showing various aspects of college data.

## Notes

Make sure you have installed the necessary Python libraries, such as pandas, matplotlib, seaborn, scikit-learn, xgboost, catboost, etc.
