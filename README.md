# Project Route Step Up Data Science and AI Challenge: Can we trust the ride? When Autonomous vehicles take the Drive

## Project Overview
This project explores whether an autonomous vehicle can be trusted to operate safely across different driving conditions. The analysis is based on a synthetic dataset designed for a data science and AI challenge, using journey-level data, vehicle profiles, road environment information, weather risk factors, and intervention records.

The goal is to identify patterns behind safety incidents, assess which conditions contribute most to performance issues, and evaluate whether a machine learning model can help predict when problems are likely to occur.

## Aim of the Project
The main objective of this project is to answer the question: "Can we trust the ride?"

Specifically, the project aims to:
- identify operating conditions that have the clearest impact on autonomous vehicle performance
- analyze which sensor, road, and vehicle factors are most associated with risk
- predict when a journey is likely to experience a problem before it happens
- evaluate model performance using metrics such as accuracy, precision, recall, and confusion matrix
- assess ethical considerations and limitations of using AI in safety-critical systems
- provide a practical recommendation on whether the system should be trusted under certain conditions

## Dataset and Business Context
The project uses synthetic autonomous vehicle journey data provided in the CSV dataset pack. It includes:
- autonomous vehicle journey records
- vehicle and sensor profiles
- road and infrastructure factors
- weather conditions and risk assumptions
- intervention and incident history
- a data dictionary describing the variables

The target variable for the predictive task is `problem_occurred`, while variables such as `risk_level`, `human_intervention`, `emergency_stop`, and `safety_incident` are treated carefully because they are closely related to the outcome and may not be appropriate as predictors for a real-world early-warning model.

## Tech Stack Used
This project uses a Python-based data science workflow, including:
- Python
- Jupyter Notebook
- Pandas for data manipulation and analysis
- NumPy for numerical operations
- Matplotlib for data visualization
- Seaborn for statistical graphics
- scikit-learn for preprocessing, model training, evaluation, and metrics

## Project Structure
- `project_route_datascience_AI.ipynb` — main analysis notebook containing data exploration, visualizations, and model building
- `Project-Route-Step-Up-Data-Science-CSV-Pack/` — dataset folder containing the CSV files used in the challenge
- `README.txt` — data package guidance and challenge instructions

## How to Use
1. Open the notebook in Jupyter or Google Colab.
2. Ensure the CSV files remain in the same folder structure as provided.
3. Load the dataset and follow the analysis steps in the notebook.
4. Review the visualizations, evaluate the model, and form a recommendation based on evidence.

## Important Note
This dataset is synthetic and intended for educational use. The patterns in the data are designed to demonstrate data science principles, not to model real autonomous vehicle safety performance.

## Summary
This project combines data analysis, machine learning, and critical thinking to assess the trustworthiness of autonomous vehicle performance in different scenarios. It demonstrates how data-driven evidence can support decisions in complex, safety-sensitive systems while also highlighting risk, ethics, and model limitations.
