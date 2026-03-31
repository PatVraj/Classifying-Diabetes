# Classifying Diabetes (Data Mining Final Project)

## Overview
A comprehensive machine learning project evaluating multiple models (SVM, Neural Networks, Decision Trees, Logistic Regression, Random Forests) for diabetes prediction. This project represents a culmination of exploratory data analysis and classification modeling, highlighting a strong data mining workflow from data preparation to complex deep learning hyperparameter tuning using real-world health datasets.

[View the Project Presentation](./Diabetes.pptx)

## Architecture / Tech Stack
- **Models**: SVM, Neural Networks, Decision Trees, Random Forest, Logistic Regression
- **Data Stack**: Pandas, NumPy
- **ML Frameworks**: scikit-learn, TensorFlow/Keras
- **Environment**: Jupyter Notebooks

```mermaid
flowchart TD
    A[Raw Patient Data] --> B[Data Preprocessing & Cleaning]
    B --> C[Feature Engineering]
    C --> D1[SVM]
    C --> D2[Neural Network (Keras Tuner)]
    C --> D3[Random Forest]
    D1 & D2 & D3 --> E[Model Evaluation & Comparison]
```

## Local Setup Instructions
```bash
git clone https://github.com/PatVraj/Classifying-Diabetes.git
cd Classifying-Diabetes
python -m venv .venv
source .venv/bin/activate
pip install pandas numpy scikit-learn tensorflow jupyter
jupyter notebook
```

## Key Results / Metrics
- Compared various architectures to find the optimal trade-off between recall and precision for medical diagnoses.
- Handled class imbalances effectively, showcasing robust data mining methodologies.
- Extracted top features utilizing distinct ML models: `GenHealth`, `BMI`, `Age`, `HighBP`, and `Income`.
- Achieved stable accuracies across tuned algorithms (e.g., Logistic Regression: 75.3%, SVM: 74.8%, Decision Tree: 74.3%).
- Explored extensive hyperparameter tuning strategies for Neural Networks.

## Data Provenance & Licensing
- Dataset based on BRFSS (Behavioral Risk Factor Surveillance System) tabular data.

## Collaborators
- Vraj Patel, Nikhil Chakka, Kavin Ramesh
