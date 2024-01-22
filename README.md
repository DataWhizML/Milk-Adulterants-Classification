# Milk Adulteration Detection 

## Abstract

Globally, milk adulteration poses a significant challenge with economic losses to consumers and severe impacts on public health. Traditional detection methods are often costly, time-consuming, and labor-intensive. This project explores on-site detection systems, particularly digital imaging, and applies machine learning algorithms to achieve efficient and accurate results.

## Dataset

The dataset used for this project is sourced from "Milk Adulteration data.csv." It includes relevant features such as 'Nr,' 'Cells,' 'QValue,' 'FFA,' 'Citrate,' and the target variable 'IsRawMilk.'

## Code Overview

The provided Python code utilizes various machine learning algorithms for binary and multi-class classification. Key steps include:

1. **Data Preprocessing:**
   - Loading and exploring the dataset.
   - Handling missing values and checking ingredient distribution.

2. **Feature Engineering:**
   - Standardizing the features using StandardScaler.
   - Splitting the data into training and testing sets.

3. **Model Implementation:**
   - Employing Support Vector Machine (SVM), Random Forest, and Gaussian Naive Bayes for binary classification.
   - Utilizing Random Forest for multi-class classification.

4. **Model Evaluation:**
   - Assessing each model's performance using confusion matrices and accuracy scores.

5. **Results:**
   - Binary Classification:
     - SVM Accuracy: 96%
     - Random Forest Accuracy: 95%
     - Gaussian Naive Bayes Accuracy: 96%
   - Multi-class Classification:
     - SVM Accuracy: 87.62%

## Instructions

To run the code locally, follow these steps:

1. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the main script:

    ```bash
    python milk_adulteration_detection.py
    ```

## Dependencies

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Acknowledgments

- The project acknowledges the challenges of milk adulteration globally.
- The use of digital imaging for on-site detection is explored.
- Machine learning algorithms, including SVM, Random Forest, and Gaussian Naive Bayes, are applied for efficient classification.

