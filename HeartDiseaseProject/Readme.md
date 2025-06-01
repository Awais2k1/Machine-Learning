# Heart Disease Prediction using PCA and Decision Tree

This project focuses on predicting heart disease using a dataset of patient health metrics. Principal Component Analysis (PCA) is used for dimensionality reduction, and a Decision Tree Classifier is applied for prediction.

## 📁 Project Structure

- **Heart_Disease.ipynb** – Main Jupyter notebook containing data preprocessing, PCA, and classification pipeline.

## 📊 Features

The dataset originally contains 13 features, including:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Max Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression
- Slope of Peak Exercise ST
- Number of Major Vessels Colored by Fluoroscopy
- Thalassemia

## 🧪 Methods Used

- **Preprocessing:** Scaling and encoding using `ColumnTransformer`.
- **Dimensionality Reduction:** Principal Component Analysis (PCA) with 3 components.
- **Classification:** Decision Tree Classifier.
- **Evaluation:** Accuracy score, confusion matrix, and performance metrics.

## 📈 Results

- The model achieved good performance after dimensionality reduction.
- PCA helped simplify the feature space while maintaining accuracy.

## 📚 Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## 📥 Dataset

The dataset is assumed to be available locally or loaded in the notebook. You can replace it with any standard heart disease dataset (e.g., from UCI).

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is open-source under the [MIT License](LICENSE).

