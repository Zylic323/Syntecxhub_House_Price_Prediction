# House Price Prediction Using Linear Regression

## Project Overview
This project uses Machine Learning to predict median house values using the California Housing dataset and a Linear Regression algorithm.

The goal is to understand how housing-related features influence predicted house values and evaluate the performance of a regression model.

## Objectives
- Load and explore a housing dataset.
- Clean and prepare the data.
- Select relevant input features and target variable.
- Split the dataset into training and testing sets.
- Train a Linear Regression model.
- Evaluate the model using RMSE and R².
- Interpret model coefficients.
- Save and reuse the trained model.
- Generate predictions for new housing data.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Dataset
The project uses the California Housing dataset provided by Scikit-learn.

It contains housing information for California districts, including:
- Median income
- House age
- Average rooms
- Average bedrooms
- Population
- Average occupancy
- Latitude
- Longitude

The target variable is `MedHouseVal`, measured in units of $100,000.

## Methodology
1. Data loading and exploration
2. Data cleaning
3. Exploratory data analysis and visualization
4. Feature selection
5. Train-test splitting (80% training and 20% testing)
6. Linear Regression model training
7. Prediction and model evaluation
8. Coefficient interpretation
9. Model saving and loading
10. Example predictions

## Evaluation Metrics
The model was evaluated using:

- **RMSE (Root Mean Squared Error):** Measures prediction error.
- **R² Score:** Measures how much variation in the target is explained by the model.

Actual evaluation results are available in the Jupyter Notebook.

## Project Files
- `house_price_prediction.ipynb` — Complete source code, analysis and results.
- `README.md` — Project documentation.
- `requirements.txt` — Required Python libraries.
- `house_price_model.pkl` — Saved trained model, if included.

## How to Run
1. Install the required libraries using `pip install -r requirements.txt`.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run the cells sequentially.

## Important Note
This project predicts median housing values for California districts, not individual houses or Nigerian property prices. The dataset target is capped at $500,000.

## Author
Machine Learning Project — Syntecxhub Internship Submission
