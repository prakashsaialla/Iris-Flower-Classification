
# 🌸 Iris Flowers Classification

This project applies **Machine Learning classification algorithms** to the famous **Iris dataset**, which contains measurements of iris flowers from three species: *Setosa, Versicolor, Virginica*. The goal is to classify flowers based on features such as sepal length, sepal width, petal length, and petal width.

## 🚀 Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA) with visualizations
* Model training with multiple algorithms (Logistic Regression, SVM, Decision Trees, Random Forest, KNN)
* Model evaluation with metrics like **Accuracy, Precision, Recall, Confusion Matrix**
* Simple and effective dataset for ML beginners

## 🛠️ Tech Stack

* **Python 3.x**
* **Pandas, NumPy** – data handling
* **Matplotlib, Seaborn** – visualization
* **Scikit-learn** – ML models & evaluation metrics

## 📂 Workflow

1. **Load Dataset** – Iris dataset (available in scikit-learn)
2. **Data Preprocessing**

   * Check for missing values
   * Normalize/scale features (if needed)
3. **Exploratory Data Analysis (EDA)**

   * Pair plots of features
   * Correlation analysis
   * Distribution of species
4. **Model Training**

   * Train multiple models (Logistic Regression, SVM, Decision Trees, KNN, Random Forest, etc.)
   * Compare their performance
5. **Evaluation**

   * Accuracy score
   * Confusion matrix & classification report
6. **Prediction**

   * Input flower features → predict species

## ▶️ How to Run

1. Clone this repository

   ```bash
   git clone https://github.com/prakashsaialla/iris-flower-classification.git
   cd iris-flower-classification
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook

   ```bash
   jupyter notebook Iris-Flowers-Classification.ipynb
   ```

4. Example prediction:

   ```python
   input_data = [[5.1, 3.5, 1.4, 0.2]]
   model.predict(input_data)
   # Output: ['Setosa']
   ```

## 📊 Example Results

* Logistic Regression: Accuracy = 95%
* KNN: Accuracy = 96%
* Random Forest: Accuracy = 97%
* SVM: Accuracy = 97% (best model)

## 📌 Future Improvements

* Deploy as a **web app** with Flask/Django + Streamlit
* Use deep learning models (though dataset is small)
* Expand to other flower classification datasets

## 📜 License

This project is licensed under the MIT License – feel free to use and modify.
