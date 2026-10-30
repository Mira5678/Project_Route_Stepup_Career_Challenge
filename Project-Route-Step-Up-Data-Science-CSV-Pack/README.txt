PROJECT ROUTE — STEP UP DATA SCIENCE & AI DATASETS

Career challenge: Can We Trust the Ride? When Autonomous Vehicles Take the Drive

This package contains synthetic learning data. It does not describe real vehicles, roads, passengers or safety performance.

GETTING STARTED
1. Extract the ZIP file. Keep README.txt and all six CSV files together in the extracted folder.
2. Read this file and data_dictionary.csv before coding.
3. Use the CSV files with the Python examples in the Project Route how-to guide. Keep their filenames unchanged.
4. For a local notebook, save it in the extracted folder or set your working directory to that folder.
5. In Google Colab, upload all six CSV files into the session before running the code.

FILES
- autonomous_vehicle_journeys.csv: 2,500 journey records and the main analysis table.
- vehicle_sensor_profiles.csv: vehicle and sensor characteristics; join using vehicle_profile_id.
- road_environment_factors.csv: road and infrastructure characteristics; join using road_segment_id.
- weather_risk_factors.csv: weather assumptions; join using weather_code.
- intervention_events.csv: one record for each intervention, emergency stop or safety incident; join using journey_id.
- data_dictionary.csv: plain-language definitions for the main dataset.

BEGINNER PREDICTION TASK
Use problem_occurred as the target. It contains 501 Yes records and 1999 No records. Do not use risk_level as a predictor for this task because it contains information closely related to the target. Consider excluding human_intervention, emergency_stop and safety_incident when predicting problems before they happen.

SUGGESTED WORKFLOW
1. Load and inspect the data.
2. Check data types, missing values and category counts.
3. Join one or more supporting tables.
4. Explore patterns with charts and grouped summaries.
5. Split the data into training and test sets.
6. Build a transparent baseline model such as logistic regression or a decision tree.
7. Evaluate accuracy, precision, recall and the confusion matrix.
8. Explain important factors, limitations, bias and ethical considerations.
9. Decide whether you would trust the ride and justify your answer with evidence.

IMPORTANT
Patterns were deliberately built into the synthetic data for teaching. Association does not prove causation, and a model trained on this dataset should never be used for real transport or safety decisions.

YOUR SUBMISSION
Create a presentation of 4–6 slides, supported by your data science analysis. Include your trust decision, model evidence, a limitation and a practical action. Use the Project Route presentation and how-to guide for full instructions.
