# Game Recommender System with Collaborative Filtering
## What it does
This project builds a recommender system that suggests games to users based on collaborative filtering. It uses the Steam dataset to learn patterns in what players tend to like, then recommends similar games to new users.

## Why I built it
This was a coursework assignment for my MSc in Artificial Intelligence at the University of Salford.

## Tools used
PySpark, PySpark MLlib, Alternating Least Squares (ALS), MLflow.

## How to run it
1. Clone this repository and install the dependencies listed.

2. Place the Steam dataset in the input folder.

3. Run the training script to build the ALS collaborative filtering model.

4. Use MLflow to run the hyperparameter tuning across the different configurations and compare the results.

## Results
The model was tuned across four different configurations of rank, maxIter, and regParam using MLflow multi-run tracking. RMSE was used to select the best performing configuration as the final model.
