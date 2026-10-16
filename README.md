AI-Powered Food Waste Prediction & Redistribution System
Files
Food_Waste_Project_Report.docx -> assignment report
food_waste_dashboard.html -> web dashboard (double-click to open in a browser)
step1_generate_data.py -> creates the dataset
step2_eda_train.py -> EDA, features, model training, evaluation
step3_redistribute.py -> optimized NGO pickup plan
app.py -> Streamlit dashboard
requirements.txt
data/ (food_waste.csv, stores.csv, ngos.csv, featured.pkl)
models/ (waste_model.joblib)
reports/ (eda.png, model_eval.png, model_comparison.csv, pickup_plan.csv)
How to run (Windows, inside this folder)
pip install -r requirements.txt python step1_generate_data.py python step2_eda_train.py python step3_redistribute.py python -m streamlit run app.py
