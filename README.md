# house_price_prediction

```markdown
# California House Price Prediction

This repository contains a project for predicting house prices in California using various machine learning techniques. The project is based on the book "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by Aurélien Géron.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Models](#models)
- [Evaluation](#evaluation)
- [Results](#results)

## Introduction

The goal of this project is to predict house prices in California based on various features such as the number of rooms, the population, the median income, and more. The project demonstrates the use of several machine learning algorithms and techniques to achieve accurate predictions.

## Dataset

The dataset used in this project is the California housing dataset. It includes information collected by the U.S. Census Service concerning housing in California.

## Project Structure

The repository is organized as follows:

```
house-price-prediction/
│
├── data/
│   ├── housing.csv            # Raw data file
│
├── notebooks/
│   ├── house_price_prediction.ipynb   # Training And Evaluating
├── requirements.txt
├── README.md

```

## Installation

To run this project, you'll need Python 3.6+ and the following libraries:

- numpy
- pandas
- matplotlib
- scikit-learn
- jupyter

You can install the necessary dependencies using pip:

```bash
pip install -r requirements.txt
```

## Models

The project includes the following machine learning models:

- Linear Regression
- Decision Tree
- Random Forest

## Evaluation

The models are evaluated using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). Cross-validation is used to ensure the robustness of the models.

## Results

The Random Forest model provided the best performance with the lowest error metrics.