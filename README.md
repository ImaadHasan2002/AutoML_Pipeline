# Automated ML Pipeline

This notebook is a template for creating an end-to-end machine learning pipeline using the programming language Python, which aims to automate the process of data preprocessing, feature engineering, feature selection/importance, and model evaluation. The pipeline is built using the following steps:
The pipeline includes the following steps:

1. Data Preprocessing

2. Feature Engineering

3. Feature Importance

4. Model Evaluation

The pipeline is built using the following libraries:

- pandas
- numpy
- scikit-learn
- xgboost
- seaborn
- matplotlib
- joblib
- featuretools
- scikit-plot
- tqdm
- woodwork
- scipy
  
## Proposed Architecture Of Pipeline

The pipeline is built using the following architecture:

![image](https://github.com/user-attachments/assets/b1ba5e9e-add8-4c83-8f85-7ff19a1ed6a3)


## Directory Structure

- `data/`: Contains the various datasets evaluated for the proposed pipeline.
- `notebooks/`: Contains the notebooks used in the pipeline.
- `misc/`: Contains the csv images used in the README.md file.Also contains the Main_processed.csv file which is generated when the pipeline is executed on a lone table(containing all the features) and the cleaned_feature_matrix.csv file is generated when the pipeline is executed on a feature matrix and is cleaned using correlation analysis and other statistical methods.
- `requirements.txt`: Contains the required libraries for the pipeline.
- `README.md`: Contains the information about the pipeline.

## How to Run

1. **Install dependencies**: Install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

2. **Run the pipeline**: Run the pipeline using the following command:
```bash
Pipeline can be run by running the notebook named 'Automated_ML_Pipeline.ipynb' in the notebooks folder after installing the required libraries mentioned in the requirements.txt file.
```
3. Example inputs are:-
```bash
data_path = 'data/loan_data.csv'
target = 'bad_loan'
```
## Author

Imaad Hasan

