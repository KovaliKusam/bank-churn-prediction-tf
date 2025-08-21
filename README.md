# 🏦 Customer Churn Prediction (TensorFlow + Streamlit)

This project is a **Customer Churn Prediction Web App** built using **TensorFlow, Scikit-learn, Pandas,** and **Streamlit**.  
It predicts whether a bank customer is likely to **churn** (leave the bank) based on their profile and financial information.

🚀 **Live Demo**: [👉 Streamlit App](https://bank-churn-prediction-tf.streamlit.app)

#

### ✨ Features
- 📊 Interactive UI built with **Streamlit**  
- 🤖 Deep learning model trained using **TensorFlow**  
- 🔢 Preprocessing with **Scikit-learn** (LabelEncoder, OneHotEncoder, StandardScaler)  
- 📈 Outputs **probability of churn** and **prediction (Churn / Not Churn)**  
- 🖥️ Can be run **locally** or deployed on **Streamlit Cloud**  

#

### 📂 Project Structure

```
ANNCLASSIFICATION
├── logs/                      # Log files
├── venv/                      # Virtual environment (not uploaded to repo)
├── .gitignore                 # Git ignore file
├── app.py                     # Streamlit application
├── Churn_Modelling.csv        # Dataset
├── experiments.ipynb          # Jupyter notebook for model experiments
├── label_encoder_gender.pkl   # LabelEncoder for gender
├── model.h5                   # Trained TensorFlow model
├── onehot_encoder_geo.pkl     # OneHotEncoder for geography
├── prediction.ipynb           # Notebook for testing predictions
├── requirements.txt           # Dependencies
└── scaler.pkl                 # StandardScaler used in training
```

#

### ⚙️ Installation (Run Locally)
#### 1. Clone the repository
```
git clone https://github.com/your-username/bank-churn-prediction-tf.git
cd bank-churn-prediction-tf
```
#### 2. Create a virtual environment (recommended)
```
python -m venv venv
source venv/bin/activate   # for Linux/Mac
venv\Scripts\activate      # for Windows
```
#### 3. Install dependencies
```
pip install -r requirements.txt
```
#### 4. Run the app
```
streamlit run app.py
```
Then open your browser at 👉 [http://localhost:8501](http://localhost:8501)

#

### 📊 Input Features
The model uses the following features to predict churn:
- **Geography** (encoded with OneHotEncoder)
- **Gender** (encoded with LabelEncoder)
- **Age**
- **Balance**
- **Credit Score**
- **Estimated Salary**
- **Tenure**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**

#

### 📌 Example Prediction
- Input customer details using the Streamlit UI.
- The app displays:
  - ✅ **Churn Probability** (e.g., 0.72)
  - ✅ **Prediction**: Likely to churn / Not likely to churn

#

### 🛠 Tech Stack
- [Streamlit](https://streamlit.io/) - Web framework
- [TensorFlow](https://www.tensorflow.org/) - Deep learning
- [Scikit-learn](https://scikit-learn.org/stable/) - Data preprocessing
- [Pandas](https://pandas.pydata.org/) - Data manipulation
- [NumPy](https://numpy.org/) - Numerical computing

#

### 📢 Deployment
This project is deployed on **Streamlit Cloud**.
Make sure your repo includes:
- ```requirements.txt``` - dependencies
- ```runtime.txt``` - Python version (e.g., ```python-3.10```)
- Model + encoders (```.h5```, ```.pkl```)

#

### 👤 Author
- Kovali Kusam
- GitHub: [@KovaliKusam](https://github.com/KovaliKusam)
