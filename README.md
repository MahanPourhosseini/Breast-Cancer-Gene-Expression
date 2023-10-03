### Problem Statement
This project aims to perform an exploratory data analysis (EDA) on the "Breast Cancer Gene Expression Profiles (METABRIC)" dataset. The primary goal is to gain insights and understanding from the dataset, especially regarding clinical information and its relationship with breast cancer survival. Additionally, I aim to prepare the data for further analysis and modeling.

### Data Documentation
We will use "Breast Cancer Gene Expression Profiles (METABRIC)" data.
- **Clinical Data**: The first 31 columns contain clinical information, including patient demographics, treatment details, and overall survival status.
- **Gene Expression Data**: These columns include gene expression values and provide insights into the genetic characteristics of patients.
- **Gene Mutation Data**: These columns contain information about gene mutations, which can be critical in cancer research. Gene's mutation info columns have been marked with \"\\_mut\" at the end of the names of the columns.
  
For more information please read the [data documentation](https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric).


### Code Explanation
In this project, I performed the following key tasks:

1. **Data Loading**: I load the dataset from a CSV file and explore the initial records to understand its structure.

2. **Data Preparation**:
   - I splited the data into three separate datasets: clinical data, gene expression data, and gene mutation data. Each dataset includes the `patient_id` and `overall_survival` columns for future analysis.
   - Data type warnings are addressed to ensure data consistency.

3. **Exploratory Data Analysis (EDA)**:
   - I conducted an EDA on the clinical data, including:
     - Identifying missing values and visualizing their percentages.
     - Creating box plots to explore the distribution of numerical attributes.
     - Plotting histograms for key clinical variables based on overall survival status to uncover potential patterns.

4. **Data Transformation**:
   - I created dummy variables for categorical columns in the clinical data, making them suitable for modeling.

This analysis provides an initial understanding of the dataset, identifies potential relationships between clinical variables and breast cancer survival, and prepares the data for further predictive modeling or in-depth research.

For a detailed explanation and code implementation, please refer to the code file.

