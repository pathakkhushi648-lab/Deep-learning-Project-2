# Deep-learning-Project-2 
# Deep Learning PR 2 – Adult Income Classification

## 1. Project Overview

This project focuses on developing and evaluating Artificial Neural Network (ANN) models to predict an individual's income category using demographic, educational, and employment-related information.

The project uses the Adult Income dataset to classify individuals into two categories:

- `<=50K` — Income less than or equal to $50,000
- `>50K` — Income greater than $50,000

Different deep learning techniques are explored to understand their impact on model performance.

## 2. Objectives

- Load, clean, and explore the Adult Income dataset.
- Perform data preprocessing for deep learning.
- Build a baseline Artificial Neural Network.
- Compare different activation functions.
- Experiment with weight initialization techniques.
- Compare loss functions.
- Evaluate the effect of Batch Normalization.
- Compare optimizers and learning rates.
- Train and evaluate a final combined model.
- Compare model performance using evaluation metrics and ROC curves.

## 3. Dataset Description

**Dataset name:** Adult Income Dataset (`adult.csv`)

The dataset contains information about individuals, including:

- Age
- Workclass
- Education
- Educational number
- Marital status
- Occupation
- Relationship
- Race
- Sex
- Capital gain
- Capital loss
- Hours worked per week
- Native country

**Target variable:** `income`

The target variable is used to classify individuals into the two income categories.

## 4. Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## 5. Project Structure

The repository is organized as follows:

```text
DL-PR2-Deep-Learning/
│
├── DL_PR2.ipynb
│   └── Complete project notebook with code and outputs
│
├── DL_PR2.html
│   └── HTML version of the notebook
│
├── README.md
│   └── Project documentation
│
├── requirements.txt
│   └── Required Python libraries
│
├── video_link.txt
│   └── Project presentation video link
│
└── plots/
    ├── training_accuracy.png
    ├── training_loss.png
    ├── confusion_matrix.png
    └── roc_curve.png
```

*Note: Include only the files and plots that you have actually created. The dataset can be stored separately or downloaded from its permitted source.*

## 6. Project Methodology

### Task 1: Data Loading and Exploratory Data Analysis

- Load the dataset.
- Inspect the dataset structure.
- Identify missing or inconsistent values.
- Explore feature distributions and income categories.
- Prepare the data for model training.

### Task 2: Baseline ANN Model

Build a baseline neural network using Dense layers and ReLU and sigmoid activation functions. Train and evaluate the model to establish a performance baseline.

### Task 3: Activation Function Comparison

Compare the following activation functions:

- ReLU
- Tanh
- Sigmoid
- ELU

### Task 4: Weight Initialization Comparison

Experiment with:

- Glorot Uniform
- Glorot Normal
- He Uniform
- He Normal
- Zeros

### Task 5: Loss Function Comparison

Evaluate the following loss functions:

- Binary Cross-Entropy
- Mean Squared Error
- Weighted Binary Cross-Entropy
- Focal Loss

### Task 6: Batch Normalization

Compare neural networks with and without Batch Normalization to examine their training and validation performance.

### Task 7: Optimizer Comparison and Final Model

Compare different optimizers:

- SGD
- SGD with Momentum
- RMSprop
- Adam

Evaluate learning-rate sensitivity, train the final combined model, and compare ROC curves.

## 7. Model Evaluation Metrics

The models are evaluated using the following metrics:

- **Accuracy:** Measures the overall proportion of correct predictions.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **Recall:** Measures how many actual positive cases are correctly identified.
- **F1-score:** Combines precision and recall into one metric.
- **ROC-AUC:** Measures the model's ability to distinguish between the two income classes.
- **Confusion Matrix:** Displays correct and incorrect classifications.

Training and validation accuracy and loss curves are also used to analyze model performance.

## 8. Advantages of the Project

1. **Practical deep learning experience:** Demonstrates how to develop and train an ANN for a real-world classification problem.
2. **Model comparison:** Evaluates different activation functions, initializers, loss functions, and optimizers.
3. **Performance evaluation:** Uses multiple metrics rather than relying only on accuracy.
4. **Imbalanced data awareness:** Explores weighted loss and focal loss techniques that may help improve the identification of minority-class examples.
5. **Training analysis:** Uses graphs to compare training and validation performance.
6. **Reusable workflow:** The notebook provides a structured process that can be adapted to other binary classification datasets.
7. **Reproducibility:** A documented environment and consistent random seed can help make experiments easier to reproduce.

## 9. Future Scope

The project can be improved and extended in several ways:

1. **Hyperparameter tuning:** Use Grid Search, Random Search, or other tuning methods to identify suitable network configurations.
2. **Advanced architectures:** Experiment with deeper neural networks and alternative architectures.
3. **Feature engineering:** Investigate additional features, feature selection, and different preprocessing strategies.
4. **Class imbalance handling:** Compare class weighting, focal loss, and resampling techniques to improve minority-class detection.
5. **Threshold optimization:** Evaluate different classification thresholds to balance precision and recall.
6. **Model explainability:** Apply explainability techniques such as SHAP to understand which features influence predictions.
7. **Deployment:** Develop a simple web application using Flask or Streamlit to demonstrate predictions.
8. **Fairness analysis:** Investigate whether prediction performance differs across demographic groups and assess potential bias before any real-world use.

## 10. How to Run the Project

1. Clone or download this repository.
2. Install Python and the required libraries.
3. Place `adult.csv` at the path expected by the notebook, or update the dataset path.
4. Open `DL_PR2.ipynb` in Google Colab or Jupyter Notebook.
5. Run the notebook cells in order.
6. Review the generated graphs, comparison tables, and evaluation metrics.

Install the required libraries using:

```bash
pip install -r requirements.txt
```

## 11. Results

The notebook generates comparison tables, training graphs, and evaluation metrics for the tested models.

The final model's performance should be reported using the actual values generated during execution. Results may vary depending on preprocessing, model configuration, and training settings.

**Results:** Refer to the outputs in `DL_PR2.ipynb`.

## 12. Conclusion

This project demonstrates the use of Artificial Neural Networks for binary income classification using the Adult Income dataset. It explores the effects of activation functions, weight initialization, loss functions, Batch Normalization, and optimizers on model training and evaluation.

By comparing different configurations and evaluating models with multiple performance metrics, the project provides practical experience in building and analyzing deep learning models using TensorFlow and Keras.

The project also provides a foundation for future work involving hyperparameter tuning, model explainability, fairness evaluation, and deployment.

## 13. Author Information 
Name :  Swarna Pathak 
