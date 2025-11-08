🥝 Fruit Classification using Random Forest
📘 Overview

This project builds a machine learning model to classify different types of fruits based on their features such as shape, color, taste, and other physical attributes.
The model is trained using a Random Forest Classifier and achieves high accuracy on both training and testing datasets.

📂 Dataset

The dataset used is named fruit_classification_dataset.csv and contains labeled examples of fruits.
Each record includes categorical and numerical features describing each fruit.

Example columns:

shape

color

taste

(Other numeric or descriptive features)

fruit_name (target label)

⚙️ Project Steps

Load and clean the data

Removed duplicates

Checked for missing or duplicated rows

Feature Encoding

Applied OneHotEncoder on categorical columns (shape, color, taste)

Used LabelEncoder on the target variable fruit_name

Feature Scaling

Used StandardScaler to normalize numeric data

Model Training

Trained a RandomForestClassifier using the preprocessed data

Evaluation

Calculated training and testing accuracy using accuracy_score

🧠 Model Used

Algorithm: Random Forest Classifier

Framework: scikit-learn

Language: Python

Development Environment: Google Colab

📊 Results
Metric	Accuracy
Train Accuracy	~ (displayed in output)
Test Accuracy	~ (displayed in output)

(You can update the actual numbers after running your notebook.)

🧩 How to Run
1. Clone this repository
git clone https://github.com/<your-username>/fruit-classification.git
cd fruit-classification

2. Install dependencies
pip install pandas scikit-learn

3. Run the notebook or Python script

If you’re using Google Colab:

Upload fruit_classification_dataset.csv to your Drive

Update the dataset path in the code

Run all cells

If you’re using local Python:

python fruit_classification.py
