This dataset contains over 7,500 synthetic user records designed to analyze smartphone usage patterns and predict levels of digital addiction. 
It simulates real-world behavioral data, including screen time, social media usage, gaming activity, sleep patterns, stress levels, and productivity impact.

The purpose of this analysis is to examine the Smartphone Usage & Addiction Prediction dataset in order to understand how each feature relates to the target variable, 
and to identify the most important features for building an effective predictive model.

To determine the best-performing model, K-Fold Cross-Validation was applied. Selected features were used to train multiple models, which were then scaled, combined using 
stacking techniques, and evaluated. The models were compared based on their average F1-scores, and the best model was selected accordingly.

Data cleaning and preprocessing were performed using Python. Visualizations created in both Python and Power BI illustrate how each feature relates to the target variable. 
The Addiction Level is categorized into four classes: No (0), Mild (1), Moderate (2), and Severe (3). Also it shows how the evaluation result is changed after stacking.
