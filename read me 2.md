## Mushroom Classification using Decision Tree
- This project builds a machine learning model to classify mushrooms as edible or poisonous based on their physical characteristics. A Decision Tree classifier is used due to its ability to handle non-linear classification boundaries, making it suitable for this categorical dataset.

## Dataset
- The dataset consists of various categorical features describing mushrooms, including cap shape, cap color, bruises, odor, gill characteristics, stalk shape and color, and more. The target variable "class" indicates whether a mushroom is edible or poisonous.

## Requirements
- Python 3.x

- pandas

- scikit-learn

- matplotlib

## Project Overview
- Data Preprocessing:
- Label encoding is applied to convert all categorical variables into numeric format suitable for training the model.

## Train Test Split:
- The dataset is divided into training and testing subsets (80-20 split).

## Model Training:
- A Decision Tree classifier is trained with pruning parameters (e.g., min samples per split/leaf, complexity pruning) to improve accuracy and prevent overfitting.

## Evaluation:
- Model performance is quantified using accuracy score on the test set.

## Visualization:
- The trained Decision Tree is visualized to interpret how feature splits differentiate edible from poisonous mushrooms.

## How to Run
- Place the mushrooms.csv dataset file in the project directory.

## Run the provided Python script.

- The console will print the model's accuracy on the test set.

- A plot of the decision tree will be displayed showing the classification rules.

## Notes
- Increasing model complexity and applying pruning parameters improves classification accuracy to approximately 98%.

- The decision tree visualization depth is limited for interpretability.

- Decision Trees are effective for non-linear classification with categorical input features.

- Additional feature engineering or hyperparameter tuning can further enhance model performance.
