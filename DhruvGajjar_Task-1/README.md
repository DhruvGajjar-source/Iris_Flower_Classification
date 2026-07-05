# Iris Flower Classification

This project builds a machine learning model to classify iris flowers into three species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

The model uses the classic Iris dataset with sepal and petal measurements.

## Project Structure

```text
Iris_Flower_Classification/
├── dataset/
│   └── Iris.csv
├── images/
│   ├── species_count.png
│   └── confusion_matrix.png
├── models/
│   └── iris_random_forest.pkl
├── Iris_Flower_Classification.ipynb
├── README.md
└── requirements.txt
```

## Workflow

1. Load and inspect the Iris dataset.
2. Check missing values and duplicate rows.
3. Visualize class distribution and feature relationships.
4. Encode species labels for model training.
5. Split the data into training and testing sets.
6. Train a Random Forest classifier.
7. Evaluate the model with accuracy, classification report, and confusion matrix.
8. Save the trained model to the `models` folder.

## How to Run

Install the dependencies:

```bash
pip install -r requirements.txt
```

Open and run the notebook:

```bash
jupyter notebook Iris_Flower_Classification.ipynb
```

## Model

The notebook trains a `RandomForestClassifier` from scikit-learn and saves it as:

```text
models/iris_random_forest.pkl
```

## Output

The completed notebook generates:

- `images/species_count.png`
- `images/confusion_matrix.png`
- `models/iris_random_forest.pkl`
