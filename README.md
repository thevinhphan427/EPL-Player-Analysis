# English Premier League (EPL) Player Statistics Analysis

## Overview

This repository contains a data analysis project focusing on player statistics from the English Premier League (EPL). The analysis includes creating DataFrames for four different player positions (Goalkeeper, Defender, Midfielder, Attacker) and performing linear and logistic regression to gain insights into player performance.

## Project Structure

The project is organized into the following components:

- `data/`: Directory containing CSV files with player statistics for each position.
- `notebooks/`: Jupyter notebooks for data preprocessing, analysis, and modeling.
- `README.md`: This README file providing an overview of the project.

## Data Collection and Preparation

Player statistics data for the 2021 EPL season were collected and organized into separate DataFrames for each position: Goalkeeper, Defender, Midfielder, and Attacker. These DataFrames were preprocessed to handle missing values, format data types, and create new columns for analysis.

## Analysis

1. **Linear Regression:**
   Linear regression was performed with the target variable 'Wins' to understand the relationship between player statistics and team wins. Separate regression models were built for each position.

2. **Logistic Regression:**
   Logistic regression was used to predict whether a player is a "High Performer" or "Low Performer" based on their statistics. The 'High Performer' column was created as the target variable.
   High performer was created by analyzing the win ratio a player has over their career. The threshold ratio for this was 0.4, as in the EPL a "draw" can be a result. 

## Getting Started

To explore the project:

1. Clone this repository:
   ```sh
   git clone https://github.com/thevinhphan427/epl-player-analysis.git
