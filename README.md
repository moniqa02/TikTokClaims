## TikTok Analysis

This is a project created for educational purposes. It analyzes TikTok data using Python and presents the results in an interactive dashboard built with Tableau.
The goal of this project is to train a machine learning model that can help identify videos making factual claims, which are more likely to violate TikTok’s terms of service.

#### Dashboard
Interactive dashboard here:
https://public.tableau.com/views/TikTokAnalysis_17494551128290/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

#### Tools used:
- Python (Pandas, Numpy, Matplotlib, Seaborn, scikit-learn)
- Jupyter Notebook
- Tableau

The classification task was performed using several models (including Random Forest and XGBoost), and the Random Forest Classifier was selected as the final model due to its high recall and zero false positives.
The trained model was saved using pickle for future reuse without retraining.

This project was made for learning and demonstration purposes only. The data used may be simplified or incomplete.
All code was written as part of a personal learning process.
