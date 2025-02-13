# Customer Spending Behavior Investigation

## Overview
This project explores customer spending behavior using demographic and financial data to identify patterns and trends across various product categories. It applies supervised machine learning techniques, including Neural Networks, Support Vector Machines (SVM), and K-Nearest Neighbors (KNN), to predict consumer spending tendencies.

## Objectives
- Analyze the impact of **family size** and **income levels** on spending habits.
- Identify **trends in spending** across product categories such as **wine, fruits, meat, fish, sweets, and gold**.
- Compare different **machine learning models** to assess their predictive accuracy.

## Dataset
The dataset used in this study is the **Customer Personality Analysis Dataset** from Kaggle. It includes demographic and financial attributes such as age, income, marital status, and spending on different products.

## Key Findings
- **Neural Networks** provided the best predictive performance, especially with fine-tuned activation functions (ReLU and Sigmoid).
- **SVM** showed moderate accuracy, with linear kernels being more stable than polynomial kernels.
- **KNN** was highly sensitive to the choice of k-values and struggled to generalize across all product categories.
- Spending on **wine and fruits** was more predictable compared to **gold and meat**, suggesting external factors like cultural preferences and economic conditions play a role.

## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** (for data manipulation)
- **Matplotlib, Seaborn** (for data visualization)
- **Scikit-Learn, TensorFlow** (for machine learning models)

## Installation and Setup
### 1. Clone the Repository
```sh
git clone https://github.com/Ghostlun/CS6440.git
cd CS6440
```

### 2. Set Up a Virtual Environment
It is recommended to use a virtual environment to manage dependencies.

#### Using venv:
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

#### Using Conda:
```sh
conda create --name spending_behavior python=3.9
conda activate spending_behavior
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```sh
jupyter notebook
```

## Usage
1. Open the Jupyter Notebook.
2. Run the **data preprocessing** steps to clean and prepare the dataset.
3. Train and evaluate the **machine learning models** to analyze spending patterns.
4. Visualize results and interpret consumer spending behaviors.

## Future Improvements
- Incorporate **transaction history data** for better prediction accuracy.
- Implement **ensemble learning techniques** to enhance model robustness.
- Improve feature engineering for more insightful analysis.

## Contributors
- **Yoon Kim** – Georgia Institute of Technology ([email](mailto:blue1357a@gmail.com))

## License
This project is licensed under the MIT License.

