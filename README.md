# NNFS_Project
drilling_dataset.csv contains real-world drilling parameters used for data analysis, machine learning model development, and optimization tasks such as predicting Rate of Penetration (ROP), detecting drilling inefficiencies, and improving operational decision-making. This dataset is structured, numerical, and ready for preprocessing and model training.

Dataset Overview

This dataset includes continuous drilling measurements recorded during well operations. Each row represents a drilling interval or time sample, and the columns describe key surface and downhole parameters that influence drilling performance.

It is commonly used for:

 ROP prediction (Regression)
 Drilling optimization
 Drilling dysfunction detection
 Feature engineering and sensitivity analysis
 ML workflows (Random Forest, XGBoost, Neural Networks)

 Columns Description

⚠ NOTE: If your dataset contains additional or slightly different columns, tell me — I will regenerate this section accurately.

Typical columns include:

Column Name	Description
WOB (Weight on Bit)	Downward force applied to the drill bit (kips or kN). Strongly affects ROP.
RPM (Rotary Speed)	Rotations per minute of the drill string. Higher RPM usually increases ROP.
Torque	Amount of rotational resistance. Helps detect bit wear/dysfunction.
Flow Rate	Mud flow rate inside the wellbore. Affects hole cleaning and pressure.
SPP (Standpipe Pressure)	Surface pressure of the mud pump system. Reflects downhole conditions.
Mud Weight	Density of drilling mud (ppg or g/cc). Affects pressure balance.
Bit Type	Categorical or encoded numeric type of drill bit used.
Depth	Measured depth of drilling interval.
ROP_AVG	Target variable — Average Rate of Penetration (ft/hr or m/hr).
Target Variable

ROP_AVG is the output/label for regression models.
Machine learning goals usually include:

Predicting future ROP

Optimizing drilling parameters for maximum penetration rate

Understanding feature influence using SHAP / importance plots

Data Notes

No missing values are guaranteed—verify before training

Scaling or normalization is recommended for models like Linear Regression/NN

Categorical columns should be one-hot encoded before training

Check for outliers in ROP, WOB, RPM


Ideal For

Data science projects

Regression model development

ROP prediction and optimization

Drilling engineering research

Feature importance & SHAP analysis
