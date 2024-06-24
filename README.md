Project: Cross Selling Boosting using ML and Apriori Algorithm

Cross Selling Boosting using ML and Apriori Algorithm is a data analysis and machine learning project aimed at predicting and boosting cross-selling opportunities using the Apriori algorithm. 
This project includes various notebooks and scripts for exploratory data analysis (EDA), data cleaning, implementing the Apriori algorithm for association rule mining, 
and training machine learning models with hyperparameter tuning.

Project Overview

The Cross Selling Boosting using ML and Apriori Algorithm project focuses on analyzing sales data to identify potential cross-selling opportunities. It includes:
- Exploratory Data Analysis (EDA) to understand and preprocess the data
- Implementation of the Apriori algorithm for association rule mining to find interesting patterns and associations
- Hyperparameter tuning to optimize machine learning models and improve their performance

Directory Structure:

The project is organized as follows:

CrossSellingBoost/

├── Data/

    ├── MergedData.csv  # Primary dataset used for analysis and modeling
    └── final_cleaned_data.csv  # Cleaned and preprocessed data

├── Notebooks/

    ├── EDA_and_Cleaning.ipynb  # Notebook for exploratory data analysis and data cleaning
    ├── Apriori_Algorithm.ipynb  # Notebook for implementing the Apriori algorithm
    ├── ML_Model_Training.ipynb  # Notebook for training machine learning models and hyperparameter tuning

├── README.md  # Project documentation

└── requirements.txt  # List of required Python packages



Installation

To set up the project locally, follow these steps:

1. Clone the repository:
    git clone https://github.com/sachinmorre-git/Cross-Selling-Boosting-using-ML-and-Apriori-Algorithm.git
    cd Cross-Selling-Boosting-using-ML-and-Apriori-Algorithm

2. Set up a virtual environment and activate it:
    python3 -m venv myenv
    source myenv/bin/activate  # On Windows: myenv\Scripts\activate

3. Install the required packages:
    pip install -r requirements.txt

Usage

1. Loading Data:
    Ensure your data files are in the Data directory.
    Example script to load data:
        import pandas as pd

        file_path = './Data/MergedData.csv'
        df = pd.read_csv(file_path)
        print(df.head())

2. Running Notebooks:
    Navigate to the Notebooks directory and open the desired notebook using Jupyter:
        jupyter notebook

3. EDA and Cleaning:
    Open and run the EDA_and_Cleaning.ipynb notebook to perform exploratory data analysis and data cleaning.

4. Apriori Algorithm:
    Open and run the Apriori_Algorithm.ipynb notebook to implement and analyze the Apriori algorithm for cross-selling opportunities.

5. Machine Learning Training and Tuning:
    Open and run the ML_Model_Training.ipynb notebook to train and tune machine learning models for cross-selling predictions.

Data

The data used in this project is stored in the Data directory. Key datasets include:
- MergedData.csv: The primary dataset used for analysis and modeling.
- final_cleaned_data.csv: Cleaned and preprocessed data.

Contributing

Contributions are welcome! If you would like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch:
    git checkout -b feature/your-feature
3. Make your changes and commit them:
    git commit -m 'Add some feature'
4. Push to the branch:
    git push origin feature/your-feature
5. Create a new Pull Request.


