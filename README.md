# Soccer MVP Dataset

This repository contains a dataset of soccer player statistics collected and processed for the development of an Artificial Intelligence model focused on selecting the Most Valuable Player (MVP).

## 📊 Dataset Description
The dataset includes performance indicators of players in individual matches. Each record represents the performance of a player in a specific game.

### Variables include:
- Offensive metrics (goals, assists, shots, etc.)
- Defensive metrics (tackles, interceptions, etc.)
- General performance indicators
- Target variable: **rating** (0–10 scale)

## 🧹 Data Preprocessing
The dataset has undergone the following preprocessing steps:
- Removal of duplicate records
- Handling of missing values (rows without rating were removed)
- Conversion of percentage values into numerical format (0–1)
- Encoding of categorical variables (player roles)

## 🤖 Purpose
This dataset is used to train and evaluate machine learning models for predicting player performance and selecting the MVP objectively.

## 📁 Dataset Usage
Although separate files for training and testing were used during model development, this repository provides a unified cleaned dataset. 

## 📌 Notes
- The dataset was adapted for academic purposes.
- It supports the development of intelligent systems in sports analytics.
