# Disease Prediction Using Machine Learning

## Overview
This project utilizes machine learning algorithms to predict diseases based on patient data. By analyzing various health parameters, the model provides a probabilistic diagnosis, aiding in early detection and intervention.

## Features
- Data preprocessing and feature engineering
- Implementation of multiple machine learning models
- Performance evaluation using key metrics
- Visualizations for data distribution and model performance

## Dataset
- The dataset used is `Training_Disease_prediction.csv`.
- It consists of various health-related features and the target variable `prognosis`.
- Missing values are handled by removing empty columns.

## Machine Learning Models Used
- Support Vector Machine (SVM)
- Naïve Bayes (GaussianNB)
- Random Forest Classifier

## Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/disease-prediction.git
   cd disease-prediction
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
4. **Open and execute** the `Disease Prediction Using Machine Learning.ipynb` file.

## Results & Evaluation
- The model's accuracy was evaluated using accuracy score and confusion matrix.
- Data visualization was used to check dataset balance and feature distribution.

## Future Enhancements
- Integration with a web-based UI for real-time predictions.
- Deployment using Flask/Django.
- Expansion to cover more diseases with additional datasets.

## License
This project is open-source and available under the [MIT License/other].

