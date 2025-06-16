### Prostate Cancer Volume Prediction
This project analyzes clinical data to predict the logarithm of prostate-specific antigen (lpsa) using a range of machine learning models. The dataset contains features such as age, prostate volume, Gleason score, and other diagnostic indicators relevant to prostate cancer. The goal is to explore which variables are most influential and to evaluate model performance in predicting lpsa values.

📁 Project Structure
bash
Copy
Edit
├── prostate_cancer_organized.ipynb  # Main Jupyter Notebook with code and analysis
├── prostate.csv                     # Dataset used for training and testing
└── README.md                        # Project description and usage guide
📊 Dataset
The dataset includes the following features:

lcavol: log cancer volume

lweight: log prostate weight

age: patient age

lbph: log benign prostatic hyperplasia amount

svi: seminal vesicle invasion (binary)

lcp: log capsular penetration

gleason: Gleason score

pgg45: % of Gleason scores 4 or 5

lpsa: log PSA (target variable)

train: indicator for training/testing split

🧪 Models Used
Linear Regression

Decision Tree Regressor

Random Forest Regressor

Extra Trees Regressor

Gradient Boosting Regressor

Each model was evaluated using:

R² Score

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Learning curves via cross-validation

📈 Key Findings
Ensemble models like Random Forest and Gradient Boosting achieved the highest accuracy.

Feature standardization improved model performance.

Visualizations (heatmaps, learning curves) were instrumental in understanding data behavior and model performance.

⚙️ How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/prostate-cancer-analysis.git

## Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt

## Open the notebook:

bash
Copy
Edit
jupyter notebook prostate_cancer_organized.ipynb

🧰 Dependencies
Python 3.8+

NumPy

pandas

matplotlib

seaborn

scikit-learn

TensorFlow (for optional neural net models)

Install all required packages using:

bash
Copy
Edit
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
📜 License
This project is open-source and free to use under the MIT License.
