# Retail Customer Segmentation with KNN Algorithm

## Overview

This repository contains the code for a retail customer segmentation project using the K-Nearest Neighbors (KNN) algorithm. The goal is to predict customer purchasing behavior based on features such as age, salary, and past purchase history. By classifying customers into buying groups, we aim to personalize marketing strategies and improve sales effectiveness.

## Problem Statement

A retail company wants to understand and target specific customer segments more effectively. To achieve this, they are using machine learning techniques to predict customer behavior and classify customers into potential buying groups. This predictive model will help the company tailor marketing strategies to different customer segments, ultimately increasing sales and enhancing customer satisfaction.

## Key Features

- **Data Preprocessing**: The dataset includes features like age, salary, and past purchase history. Standardization is applied using the `StandardScaler` to ensure uniformity in feature scales.
- **Model Training**: The KNN algorithm is employed for customer classification. The `KNeighborsClassifier` from scikit-learn is used to train the model.
- **Model Evaluation**: Model accuracy is evaluated using the test dataset to assess its performance in predicting customer segments.

## Getting Started

1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/your_username/retail-customer-segmentation.git
    ```
2. **Navigate to the Project Directory**: 
    ```bash
    cd retail-customer-segmentation
    ```
3. **Install Dependencies**: 
    ```bash
    pip install -r requirements.txt
    ```
4. **Run the Jupyter Notebook**: 
    ```bash
    jupyter notebook customer_segmentation.ipynb
    ```

## Requirements

- Python 3.x
- NumPy
- scikit-learn

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
