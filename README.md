# Titanic-Passenger-Data-Analytics

# 🚢 Titanic Passenger Data Analysis

A comprehensive data analysis project on the Titanic dataset using Python. This notebook demonstrates data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning techniques to predict passenger survival.

## 📌 Project Overview
The Titanic dataset is a classic problem for binary classification, containing details about passengers such as age, sex, ticket class, and survival status. This project aims to extract insights and build a predictive model using a Decision Tree Classifier.

## 🛠 Tech Stack
- Python
- Jupyter Notebook
- Libraries: Pandas, NumPy, Seaborn, Matplotlib, scikit-learn

## 🔍 Key Objectives
1. Perform data cleaning and transformation
2. Explore survival trends using visualizations
3. Engineer features to enhance model performance
4. Train a Decision Tree model to predict survival
5. Evaluate model accuracy

## 📊 Data Insights
- Analyzed data for **891** Titanic passengers
- Overall survival rate: **~38%**
- Higher survival among **females** and **1st class** passengers
- **Children** and passengers with smaller families had higher survival chances
- Key influencing factors included **Age**, **Fare**, **Pclass**, and **FamilySize**

## 🤖 Model Summary
- **Model Used**: Decision Tree Classifier (`criterion='entropy'`)
- **Accuracy Achieved**: **77.65%** on test data
- **Input Features**:
  - One-hot encoded categorical data
  - Dropped irrelevant features like Name, Ticket, Title, and AgeCategory
  - Added engineered features like FamilySize

## 📁 Folder Structure



## 🧠 Learnings
- Preprocessing and cleaning are crucial for ML accuracy
- Feature engineering significantly improves model performance
- Visualizations help uncover hidden patterns in the data
- Decision Trees offer interpretability and quick insights

## ✅ How to Run
1. Clone the repository:
   `git clone https://github.com/apurv2004/Titanic-Passengers-Data-Analysis.git`
2. Navigate to the project folder:
   `cd Titanic-Passengers-Data-Analysis`
3. (Optional) Create a virtual environment and install dependencies:
   `pip install -r requirements.txt`
4. Launch the notebook:
   `jupyter notebook` and open `Titanic Passengers Data Analysis.ipynb`

## 📬 Contact
- **GitHub**: [apurv2004](https://github.com/apurv2004)
- **LinkedIn**: [Apurv Kulkarni](https://linkedin.com/in/apurv2004)

## 📄 License
This project is licensed under the [MIT License](LICENSE).
