# 🚗 Car Price Prediction Project

This project predicts the **selling price of used cars** using Machine Learning.  
It demonstrates an end-to-end ML pipeline: data preprocessing, train-test splitting, feature selection, model building, and predictions on new data.

---

## 📂 Project Structure

- **car data.csv** → Original raw dataset  
- **car_data_cleaned.csv** → Dataset after cleaning (Car_Age created, Year dropped)  
- **car_data_encoded.csv** → Encoded dataset (categorical features converted to numeric)  
- **car_data_new.csv** → New dataset for prediction (without Selling_Price)  
- **predicted_prices.csv** → Model predictions (Linear Regression & Random Forest)  

- **data understanding.ipynb** → Step 1: Explore dataset  
- **data_preprocessing.ipynb** → Step 2: Data cleaning & encoding  
- **testing_and_training_data.ipynb** → Step 3A: Train-Test Split  
- **clear view.ipynb** → Step 3B: Feature Selection  
- **test_data.ipynb** → Step 4: Model training & evaluation  

---

##  Workflow

1. **Data Understanding** – Initial exploration of features and target variable.  
2. **Preprocessing** – Cleaning dataset, encoding categorical variables, creating `Car_Age`.  
3. **Train-Test Split & Feature Selection** – Split data into train/test and identify top predictors.  
4. **Model Building** – Train **Linear Regression** and **Random Forest Regressor**.  
5. **Prediction** – Apply trained models to `car_data_new.csv` to predict car prices.  

---

## Results

- **Linear Regression** provided a simple baseline.  
- **Random Forest** performed better by capturing non-linear relationships.  
- Predictions saved in `predicted_prices.csv`.

---



