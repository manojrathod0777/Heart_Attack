# Heart Attack Prediction

This repository contains a machine learning project designed to predict the likelihood of heart attacks based on a dataset of medical parameters. The project demonstrates the end-to-end process of data preprocessing, feature engineering, model building, and evaluation.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

## Overview
Heart disease is one of the leading causes of death worldwide. Early prediction of heart attacks can save lives by enabling timely intervention. This project employs machine learning techniques to predict the risk of a heart attack based on various medical attributes.

## Dataset
The dataset used in this project contains medical parameters such as age, cholesterol levels, resting blood pressure, and other indicators. It is assumed to be sourced from a publicly available medical dataset (e.g., UCI Heart Disease dataset).

### Features:
- Age
- Gender
- Chest Pain Type (e.g., asymptomatic, typical angina)
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Resting Electrocardiographic Results
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression Induced by Exercise
- Slope of the Peak Exercise ST Segment
- Number of Major Vessels Colored by Fluoroscopy
- Thalassemia

## Dependencies
To run this project, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyterlab (optional, for running the notebook)

## Project Workflow
1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical features.
   - Scaling numerical features.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzing feature distributions.
   - Visualizing correlations between features and target.
3. **Feature Selection**:
   - Identifying the most significant features using statistical methods.
4. **Model Building**:
   - Training machine learning models such as Logistic Regression, Decision Trees, and Random Forests.
   - Hyperparameter tuning using GridSearchCV.
5. **Evaluation**:
   - Assessing model performance using metrics like accuracy, precision, recall, and F1-score.

## Results
The trained models were evaluated on a test dataset, achieving the following results:
- **Logistic Regression**: ~85% accuracy
- **Random Forest**: ~88% accuracy

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-attack-prediction.git
   cd heart-attack-prediction
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter lab Heart_Attack.ipynb
   ```
4. Run the notebook cells sequentially to reproduce the results.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with improvements or additional features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out with any questions or suggestions!
