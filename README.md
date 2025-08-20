# Medical-Insurance-Price-Prediction
📌 About the Project

This project predicts medical insurance charges based on user details such as age, gender, BMI, number of children, smoking habits, and region.
The goal is to build a machine learning regression model that can estimate the insurance cost for an individual.

The notebook walks through:

Data preprocessing & cleaning
Exploratory Data Analysis (EDA)
Feature encoding
Model training & evaluation
Prediction on test inputs

⚙️ Tech Stack
Python 🐍
Jupyter Notebook
Pandas, NumPy (Data Handling)
Matplotlib, Seaborn (Visualization)
Scikit-learn (Machine Learning)

🚀 How to Run
1️⃣ Clone the repository
git clone https://github.com/rOHan1122333/Medical-Insurance-Price-Prediction
cd medical-insurance-prediction

2️⃣ Install dependencies

Make sure you have Python 3.8+ installed. Then run:
pip install -r requirements.txt (If requirements.txt is not created yet, I can generate it for you from the notebook.)

3️⃣ Open Jupyter Notebook
jupyter notebook

4️⃣ Run the notebook
Open Medical_Insurance_Price_Prediction_using ML.ipynb
Run all cells in order (Kernel > Restart & Run All)

▶️ Execution Flow
Load dataset – Import insurance dataset (CSV).
Exploratory Data Analysis (EDA) – Visualize distributions, correlations.
Preprocessing – Handle categorical features, normalize numeric values.
Model Training – Train models (Linear Regression, Random Forest, etc.).
Evaluation – Compare performance metrics (R², MSE).
Prediction – Input custom values to predict insurance charges.

📊 Results

The trained model can predict medical insurance costs with reasonable accuracy.
Feature importance analysis shows smoking and BMI as major cost drivers.
📂 Project Structure
├── Medical_Insurance_Price_Prediction_using ML.ipynb   # Main notebook
├── requirements.txt                                    # Python dependencies
├── data/                                               # (Optional) Dataset storage
└── README.md                                           # Project documentation
