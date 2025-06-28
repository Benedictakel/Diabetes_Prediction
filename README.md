

# 🩺 Diabetes Prediction

Predicting whether a person has diabetes (1) or not (0) using medical data such as glucose level, blood pressure, BMI, age, and other relevant features.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Project Objectives](#project-objectives)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Model Building](#model-building)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

The **Diabetes Prediction** project leverages machine learning techniques to classify whether an individual has diabetes based on their health and medical data. Early detection can assist in timely medical intervention, health education, and disease management.



## 📊 Dataset

* **Source:** Diabetes Dataset 
* **Link:** [)
* **Attributes:**

| Feature                  | Description                      |
| ------------------------ | -------------------------------- |
| Pregnancies              | Number of pregnancies            |
| Glucose                  | Plasma glucose concentration     |
| BloodPressure            | Diastolic blood pressure (mm Hg) |
| SkinThickness            | Triceps skin fold thickness (mm) |
| Insulin                  | 2-Hour serum insulin (mu U/ml)   |
| BMI                      | Body mass index (weight/height²) |
| DiabetesPedigreeFunction | Diabetes pedigree function       |
| Age                      | Age (years)                      |
| Outcome                  | Class variable (0 or 1)          |



## 🎯 Project Objectives

✅ Load and explore the diabetes dataset

✅ Perform data preprocessing (handle missing values, normalization)

✅ Visualize data for patterns and insights

✅ Build classification models (Logistic Regression, Decision Tree, Random Forest, etc.)

✅ Evaluate model performance using accuracy, precision, recall, and F1-score

✅ Predict diabetes outcome for new patients



## 🛠️ Technologies Used

* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/diabetes_prediction.git
cd diabetes_prediction
```

2. **Create virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate      # On Linux/Mac
venv\Scripts\activate         # On Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```



## ▶️ Usage

1. **Run the Jupyter Notebook**

```bash
jupyter notebook Diabetes_Prediction.ipynb
```

2. **Follow the notebook steps to:**

* Explore the data
* Visualize distributions and correlations
* Preprocess data
* Build, train, and evaluate classification models
* Predict diabetes status from new input data



## 🏗️ Model Building

The following classification models were implemented and compared:

| Model                      | Description                         |
| -------------------------- | ----------------------------------- |
| **Logistic Regression**    | Baseline classification model       |
| **Decision Tree**          | Tree-based classifier               |
| **Random Forest**          | Ensemble method for better accuracy |
| **K-Nearest Neighbors**    | Instance-based learning algorithm   |
| **Support Vector Machine** | Effective for complex boundaries    |

**Evaluation Metrics:**

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix



## 📈 Results

* **Best performing model:** *Specify model name here*
* **Accuracy:** *Value here*
* **Precision:** *Value here*
* **Recall:** *Value here*
* **F1-Score:** *Value here*

> The Random Forest Classifier achieved the highest performance due to its ensemble learning capabilities and handling of feature interactions effectively.



## 🤝 Contributing

Contributions are welcome to improve the model, add deployment scripts, or integrate with APIs for real-time diabetes prediction.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi@gmail.com) | [Portfolio Website](#)



### ⭐️ If you find this project useful, please give it a star!


