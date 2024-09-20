# IPL Match Outcome Prediction

This project aims to predict the total runs scored by a batting team in an IPL match using historical match data. The model leverages Support Vector Regression (SVR) and Gaussian Naive Bayes for prediction.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Evaluation Metrics](#evaluation-metrics)
- [Prediction Function](#prediction-function)
- [Contributing](#contributing)
- [License](#license)

## Introduction

With the increasing popularity of the Indian Premier League (IPL), predicting match outcomes has become a fascinating challenge. This project utilizes machine learning techniques to forecast the total runs scored by a batting team based on various match statistics.

## Dataset

The dataset used in this project is named `ipl_data.csv`, which contains historical match data. Key features include:
- Batting team
- Bowling team
- Runs scored
- Wickets lost
- Overs bowled
- Runs scored in the last 5 overs
- Wickets lost in the last 5 overs

## Installation

To run this project, ensure you have the following packages installed:

```bash
pip install pandas numpy scikit-learn matplotlib
