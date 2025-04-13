# Moroccan-Real-Estate-Trends-and-Price-Predictions
# Exploring Moroccan Real Estate: Trends and Price Predictions

This project aims to predict real estate prices in Morocco based on various features such as location, surface area, and property type. Using machine learning techniques, the goal is to provide valuable insights into the trends and price predictions of Moroccan real estate.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Development](#model-development)
- [Model Deployment](#model-deployment)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Contributors](#contributors)

## Project Overview

This project uses a dataset scraped from real estate listings on [mu.ma](https://www.mu.ma/) and performs the following tasks:

- **Data Collection:** Scraping real estate listings with Python.
- **Data Cleaning:** Preparing the data for analysis, including handling missing values and encoding categorical variables.
- **Exploratory Data Analysis (EDA):** Visualizing trends and relationships in the data.
- **Model Development:** Creating machine learning models to predict real estate prices using TensorFlow.
- **Model Deployment:** Deploying the final model as a web app using Hugging Face Spaces.

## Data Collection

The dataset used in this project is collected through a web scraping process from [mu.ma](https://www.mu.ma/), where various properties such as location, price, and surface area are extracted.

### Key Features Collected:
- Property Name
- Price
- Location (City)
- Surface Area
- Number of Rooms
- Property Type (e.g., apartment, villa)

## Data Cleaning

The collected data goes through several preprocessing steps to ensure it is ready for analysis and modeling:
- Handling missing values
- Removing duplicates
- Feature engineering (e.g., one-hot encoding for categorical features)

## Exploratory Data Analysis (EDA)

We use various visualization techniques to explore the relationships in the dataset, including:
- Histograms of price distribution
- Scatter plots of price vs. surface area
- Heatmaps for correlation analysis

## Model Development

We developed several machine learning models to predict the price of properties in Morocco based on the features mentioned above. The models include:
- Linear Regression
- Decision Trees
- Random Forest
- Neural Networks (TensorFlow)

The model with the best performance in terms of Mean Absolute Error (MAE) was chosen as the final model.

## Model Deployment

The trained model has been deployed as a web app using [Hugging Face Spaces](https://huggingface.co/spaces). You can interact with the model and make predictions on real estate prices in Morocco.

### [Link to Model Deployment](https://huggingface.co/spaces/saaara/real_estate_price_prediction)

## Installation Instructions

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/moroccan-real-estate-price-prediction.git
   cd moroccan-real-estate-price-prediction
