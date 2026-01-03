# House Price Prediction - AI Model

This project aims to predict residential house prices in Ames, Iowa, using advanced regression techniques. The model is built on the **Ames Housing Dataset**, which contains 82 features describing various aspects of residential homes.

## 🚀 Project Overview
The project follows a standard data science pipeline:

1. **Data Loading & Initial Exploration**: Loading the dataset and examining its structure (2930 rows, 82 columns).
2. **Data Preprocessing**: 
    * Removal of redundant or low-correlation features.
    * Handling missing values and ensuring data consistency.
    * Selection of high-impact features for the final model.

## 📊 Data Features
The final processed dataset includes key features such as:

* **Overall Qual**: Overall material and finish quality.
* **Gr Liv Area**: Above grade (ground) living area square feet.
* **Year Built**: Original construction date.
* **Garage Cars**: Size of garage in car capacity.
* **Total Bsmt SF**: Total square feet of basement area.
* **SalePrice**: The target variable to be predicted.

## 🤖 Model Details
The project utilizes **CatBoost** for regression. Key steps in the implementation include:

* **Mounting Google Drive**: For seamless data access and storage.
* **Feature Engineering**: Splitting data into features ($X$) and target ($y$).
* **Model Training**: Training the regressor to minimize prediction error and maximize accuracy.

## 🌐 Gradio Interface
The project includes a **Gradio-based web app**. Once launched, it provides a public URL (e.g., `https://291a224ce53a945c3a.gradio.live`) where users can interact with the model by entering property details to see instant price predictions.

## 📁 File Structure
* `HousePricePrediction_AImodel.ipynb`: The main Jupyter notebook containing the code.
* `AmesHousing.csv`: The raw dataset (referenced in the code).
* `AmesHousing_ClearColumns.csv`: Cleaned dataset after feature selection.

---
**Project developed by Imer Imeri.**
