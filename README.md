# insuranceCostPrediction
Developed a Machine Learning project using Linear Regression to predict individual medical insurance costs based on factors such as age, gender, BMI, number of children, smoking habits, and region. Performed data cleaning, exploratory data analysis, correlation analysis, model training, and performance evaluation using Python, Pandas, NumPy,
# Insurance Cost Prediction Using Linear Regression

## Project Overview
This project uses Machine Learning to predict individual medical insurance costs based on personal and lifestyle factors. A Linear Regression model is trained on the Kaggle Insurance Dataset to estimate insurance charges.

## Dataset
- **Source:** Kaggle – Medical Cost Personal Dataset
- **Target Variable:** `charges`

### Features
- Age
- Sex
- BMI
- Children
- Smoker
- Region

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Workflow
1. Import required Python libraries.
2. Load the Kaggle dataset.
3. Perform data cleaning and preprocessing.
4. Conduct Exploratory Data Analysis (EDA).
5. Analyze feature correlations.
6. Encode categorical variables.
7. Split the dataset into training and testing sets.
8. Train the Linear Regression model.
9. Generate predictions.
10. Evaluate model performance.

## Model Used
**Linear Regression**

Linear Regression is used to establish the relationship between input features and medical insurance charges.

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd Insurance-Cost-Prediction
```

Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## How to Run
1. Download the dataset from Kaggle.
2. Place the CSV file in the project directory.
3. Open the Jupyter Notebook or Google Colab.
4. Execute the cells sequentially.

## Project Structure

```text
Insurance-Cost-Prediction/
│
├── insurance.csv
├── insurance_prediction.ipynb
├── README.md
└── requirements.txt
```

## Learning Outcomes
- Understanding Linear Regression.
- Data preprocessing and feature encoding.
- Exploratory Data Analysis.
- Correlation and feature relationships.
- Model training and testing.
- Regression model evaluation.

## Future Improvements
- Experiment with Ridge and Lasso Regression.
- Compare multiple regression algorithms.
- Perform feature engineering.
- Deploy the model using Flask or FastAPI.

## Author
**Aniket Singh**


---

⭐ If you find this project useful, consider giving it a star!
