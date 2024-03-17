# Weather Prediction Model Evaluation

This project aims to evaluate various machine learning models for predicting whether it will rain tomorrow based on historical weather data from the Australian Bureau of Meteorology.

## Dataset

The dataset used in this project is the `Weather_Data.csv` file, which contains observations of weather metrics for each day from 2008 to 2017. The dataset includes features such as minimum and maximum temperatures, rainfall, evaporation, sunshine, wind speed and direction, humidity, pressure, and cloud cover.

## Models

The following machine learning models are trained and evaluated on the dataset:

1. Linear Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Logistic Regression
5. Support Vector Machine (SVM)

## Evaluation Metrics

The models are evaluated using the following metrics:

- Accuracy
- Jaccard Index
- F1-Score
- Log Loss (for Logistic Regression only)

## Usage

1. Clone the repository or download the source code.
2. Install the required dependencies (pandas, scikit-learn, etc.).
3. Run the Jupyter Notebook file (`Weather Prediction Model Evaluation.ipynb`).
4. The notebook will preprocess the data, train the models, and evaluate their performance.
5. The final report with the evaluation metrics for each model will be displayed at the end.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
