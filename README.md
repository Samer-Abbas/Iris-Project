# Iris Flower Prediction Project

This project demonstrates the application of machine learning techniques to classify iris flowers into three species: Setosa, Versicolor, and Virginica using the famous Iris dataset.

## Project Structure

- `Iris Project.ipynb`: Main Jupyter notebook containing code, visualizations, and explanations.
- `logistic_regression_model.pkl`: Saved logistic regression model for future use.
- `iris_test_predictions.csv`: CSV file containing test set predictions.

## Features

- **Data Exploration & Visualization**: Visualizes feature relationships and species separability using pairplots.
- **Model Training**: Trains a logistic regression model and compares with Random Forest and SVM classifiers.
- **Evaluation Metrics**: Includes accuracy, confusion matrix, classification report, and ROC curves.
- **Feature Importance**: Visualizes the importance of each feature in the model.
- **Model Persistence**: Saves and reloads the trained model using `joblib`.
- **Export Predictions**: Exports test predictions to a CSV file.

## Getting Started

1. Clone the repository or download the files.
2. Open `Iris Project.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook cells sequentially to reproduce the analysis and results.

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- joblib

Install dependencies with:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn joblib
```

## Results

- Achieved high accuracy on the test set.
- Visualizations and metrics confirm the model's effectiveness.
- Model and predictions are saved for future use.

## License

This project is for educational purposes.