# Linear Regression from Scratch – House Price Prediction (Islamabad)

This repository contains an implementation of **Linear Regression from scratch using Gradient Descent** to predict **house prices in Islamabad**. The project strictly avoids any machine learning libraries for training and implements all mathematical operations manually, following the given academic constraints.

The dataset consists of **1000+ real house listings scraped from Zameen.com**, and the model is evaluated using **MSE during training** and **RMSE and R² score on the test dataset**.

## 📌 Project Objectives

- Implement Linear Regression **from scratch** using Gradient Descent
- Scrape a real-world dataset of Islamabad house listings
- Select meaningful features to improve prediction accuracy
- Train and test the model without using ML training libraries
- Visualize data, training loss, and final regression results
- Evaluate model performance using RMSE and R-squared


## 📊 Dataset Collection

- **Source:** Zameen.com
- **Number of Samples:** 1000+ houses
- **Collection Method:** Chrome data scraping extension (no AI used)
- **City:** Islamabad

### 🧰 Scraping Tool Used
Instant Web Scraper 

### 🖼️ Proof of Work
Screenshots demonstrating scraping are
are attached in the repository.

## 🧾 Selected Features

The following features were selected based on their relevance to house pricing:

- Area (square feet)
- Number of bedrooms
- Number of bathrooms
- Location (encoded)
- Price (target variable)

Better feature selection directly improved model accuracy.

## 🧠 Model Description

- **Algorithm:** Linear Regression
- **Optimization:** Gradient Descent
- **Loss Function (Training):** Mean Squared Error (MSE)
- **Evaluation Metrics (Testing):**
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)

All formulas were implemented manually without using any ML training library.

## 🔧 Libraries Used

Only supporting libraries were used:

- `numpy`
- `pandas`
- `matplotlib`


## 📁 Dataset Split

- **Training Set:** 80%
- **Testing Set:** 20%

## 📈 Visualizations

The following plots are included:

- Feature vs Price plots
- Loss (MSE) vs Epochs
- Final regression line using two selected features

All plots are generated using `matplotlib`.


## 📉 Results & Evaluation

After training, the model was evaluated on unseen test data:

- **RMSE:** Calculated manually using formula
- **R-squared (R²):** Calculated manually without any library

These metrics demonstrate the goodness of fit of the trained model.
