# Iris_flower-classification
The Iris flower is one of the most recognizable and widely studied flowers in the world, admired for its elegant structure, vibrant colors, and symbolic meaning. Belonging to the genus Iris, this flowering plant consists of nearly 300 species, many of which grow across Europe, Asia, North America, and the Mediterranean region. The name “Iris” 

Iris Flower Classification – Machine Learning Project

This project performs Iris flower species classification using supervised machine learning. The Iris dataset is one of the most famous datasets in the field of pattern recognition and is commonly used to demonstrate classification algorithms.

The goal of the project is to build a machine learning model that can classify Iris flowers into one of the following three species based on four numerical features:

Iris Setosa

Iris Versicolor

Iris Virginica

📂 Project Structure
iris-flower-classification/
 ├── models/
 │     └── iris_model.pkl
 ├── notebooks/
 │     └── iris_classification.ipynb
 ├── README.md

🌼 About the Iris Dataset

The Iris dataset contains 150 samples, each with the following features:

Sepal Length

Sepal Width

Petal Length

Petal Width

These measurements are used to classify flowers into the three Iris species mentioned above.

🤖 Machine Learning Workflow

The project follows these steps:

1️⃣ Import Libraries

NumPy, Pandas, Scikit-Learn, and Matplotlib are used.

2️⃣ Load Dataset

The dataset is loaded directly from sklearn.datasets.

3️⃣ Exploratory Data Analysis (EDA)

Checked dataset shape

Displayed first few rows

Visualized distributions of features

4️⃣ Model Training

A Logistic Regression model was used due to its simplicity and strong performance on linearly separable data.

5️⃣ Train–Test Split

The dataset was split into:

80% training

20% testing

6️⃣ Model Evaluation

Calculated:

Accuracy Score

Confusion Matrix

Classification Report

7️⃣ Model Saving

The trained model was saved as:

models/iris_model.pkl

🚀 How to Run the Project

Clone the repo:

git clone <your-repo-link>


Open the notebook:

notebooks/iris_classification.ipynb


Run all cells to:

Train the model

Evaluate the results

Save predictions

⭐ Results

The Logistic Regression model achieved high accuracy in predicting the correct flower species based on the four input features.

📌 Author

Ananya
Machine Learning Intern – CodeAlpha
