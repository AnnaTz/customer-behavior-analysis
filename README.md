This project explores customer behavior in response to marketing strategies implemented by Starbucks. Utilizing transactional data, customer demographics, and marketing interaction records, the project offers insights into customer spending patterns and the effectiveness of promotional strategies.

## Project Files

- **starbucks_data/**: Contains three CSV files with the data used (`profile.csv`, `portfolio.csv`, `transcript.csv`).
- **customer_behavior_analysis.ipynb**: Jupyter notebook containing all the code and detailed analysis.
- **requirements.txt**: A text file listing the libraries required to run the project.

## Key Features

- **Data Preparation and Cleaning:** Initial processing of three distinct datasets to ensure quality and usability for analysis. Tasks include imputation of missing values, handling data anomalies, and extensive feature engineering.
- **In-depth Exploratory Analysis:** Utilizes visualizations to explore relationships between customer demographics, transaction behaviors, and response to offers. Key insights into how different demographics interact with various offer types are derived.
- **Advanced Predictive Modeling:** Implements several machine learning models to predict three main outcomes:
  1. Customer expenditure sizes.
  2. Likelihood of customers viewing promotional offers.
  3. Effectiveness of offers based on completion rates post-viewing.
- **Model Interpretation with SHAP Values:** Applies SHAP (SHapley Additive exPlanations) to interpret the output of the machine learning models, highlighting the impact of each feature on the prediction outcomes, thus providing transparency and deeper understanding of model decisions.

## Getting Started

### Prerequisites
- Python 3.8 or later
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, shap, lightgbm, xgboost
- Jupyter Notebook for running the analysis

### Installation
1. Ensure that Python and pip are installed on your system.
2. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/AnnaTz/customer-behavior-analysis
   ```
3. Navigate to the project directory and install the required Python libraries:
   ```bash
   cd customer-behavior-analysis
   pip install -r requirements.txt
   ```

### Running the Project
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to the notebook file in the Jupyter interface and open it.
3. Run the cells sequentially to perform the analysis.

## References

- Starbucks Capstone dataset on Kaggle: [Link to the dataset](https://www.kaggle.com/datasets/ihormuliar/starbucks-customer-data).
