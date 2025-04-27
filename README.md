
⸻

🏢 Smart HVAC Optimization Using Machine Learning | Project Series 1/50

⸻

Project Overview

This project replicates and adapts a real-world research paper focused on optimizing HVAC electricity consumption based on occupancy forecasting. Using machine learning, I predict short-term HVAC energy usage and implement rule-based controls to simulate energy savings.

⸻

Problem Statement

HVAC systems consume ~50% of a building’s energy. The goal was to reduce energy usage by forecasting occupancy and adjusting HVAC operations accordingly.

⸻

Dataset
	•	Source: A Synthetic Building Operation Dataset
	•	Size: 1.2TB
	•	Link: AWS Dataset Viewer

⸻

Approach & Methodology
	1.	Occupancy Forecasting:
	•	STL decomposition for seasonal-trend extraction (10-min intervals).
	2.	Machine Learning Models:
	•	Support Vector Regression (SVR)
	•	Feedforward Neural Network (FNN)
	3.	Feature Engineering:
	•	Occupancy lag features (±0.5h, ±1h, ±2h).
	•	Time-based features (hour, weekday, working hours).
	•	Weather data (temperature, precipitation, snow).
	4.	Simulation:
	•	Rule-based logic for HVAC operation based on predicted occupancy.
	•	Energy consumption adjusted for working and non-working hours.
	5.	Results:
	•	Energy savings: 0.08% in one week.
	•	Models accurately captured occupancy-HVAC dynamics.

⸻

Tools & Technologies
	•	Python (pandas, numpy, scikit-learn)
	•	AWS SageMaker for dataset extraction.
	•	Power BI for KPI visualization.

⸻

Inspiration

This project is inspired by the research paper:
	•	Title: “Occupancy-based one-year-ahead HVAC electricity consumption optimization using machine learning”
	•	Authors: Maher Alaraj et al. (2023)

⸻

Project Structure
	•	Part_1.ipynb – Occupancy Forecasting
	•	Part_2-3_Final.ipynb – HVAC Energy Prediction + Optimization
	•	Reports: Full PDF/DOCX reports summarizing methodology and results.
	•	Dashboard: Power BI visuals showcasing KPIs (optional screenshots).
