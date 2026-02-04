**Income Data Analysis: Exploratory Data Analysis with Python**

This repository contains a detailed Exploratory Data Analysis (EDA) of the Adult Income dataset (also known as the "Census Income" dataset). The project focuses on data cleaning, handling formatting issues, and visualizing demographic distributions.

📌 **Project Highlights**
 * Data Cleaning: Fixed column naming inconsistencies (leading spaces), removed over 7,000 duplicate rows, and verified data integrity.
 * Demographic Profiling: Identified the oldest (90) and youngest (17) individuals in the dataset.
 * Feature Analysis: Explored work classes, education levels, and income brackets.
 * Visualization: Created professional-grade Bar and Pie charts using Matplotlib and Seaborn.

🛠️ **Tech Stack**
 * Python
 * Pandas: Data manipulation and cleaning.
 * Matplotlib: Core visualization and figure customization.
 * Seaborn: Statistical data visualization.

📊 **Key Insights from the Data**
 * Income Distribution: A significant majority of individuals in this dataset earn less than $50,000 annually.
 * Work Class: The private sector is the most represented employment category.
 * Gender Gap: The dataset shows a higher representation of male entries compared to female entries.
 * Education: High School graduates form the largest group within the education column.

🗂️ **Data Processing Steps**
 * Initial Inspection: Used .shape, .head(), and .columns to understand the 32,561 entries.
 * Formatting: Identified and removed leading spaces in column headers to prevent indexing errors.
 * Deduplication: Successfully identified and dropped ~7,000 duplicate records using drop_duplicates(inplace=True).
 * Scaling Visuals: Utilized matplotlib.rc to globally adjust figure sizes for better clarity in presentations.

🚀 **How to Use**
 * Clone the repo:
   git clone https://github.com/lady-dot/income-analysis-eda.git

 * Download the Dataset: The data link is provided in the repository (or include the adult.csv file).
 * Run the Analysis: Open the Jupyter Notebook or run the .py script to see the cleaning process and plots.

**If you find this project useful, please consider giving it a ⭐!**
