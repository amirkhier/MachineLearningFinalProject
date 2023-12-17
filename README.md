# Machine Learning Final Project Repository

**Abstract:**
This project aims to delve into various machine learning approaches, exemplifying key models, and showcasing their applications using Python (in Jupyter Notebook format - .ipynb) within Google Colab. The source code serves as a comprehensive guide to understanding the machine learning pipeline. It encompasses data processing, model training, graphical representation, model optimization, and evaluation techniques. Additionally, the project explores methods for model selection based on error metrics, distribution analysis, and accuracy measures for different data types.

**Project Details:**

**1. Data Processing:**
   - Validation for missing values.
   - Imputation techniques applied, such as median, mean, etc.

**2. Data Visualization:**
   - Utilizing matplotlib and pandas libraries, primarily for classification problem-solving.

**3. Normalizing/Scaling Data:**
   - Implementation of the StandardScaler() method within the classification problem-solving section.
   - Utilization of the StandardScaler() method for regression problem-solving before fitting regression models.

**4. Data Sampling:**
   - Leveraging the ADASYN method for classification problem-solving.

**5. Model Fitting/Training:**

   **5.1 Classification Models:**
   - RandomForestClassifier (pipeline)
   - XGBClassifier (pipeline)
   - Neural Network

   **5.2 Regression Models:**
   - Linear Regression
   - Polynomial Regression (including parameter optimization such as best model - Lasso/Ridge, optimal alpha regularization, and degree).
   - RandomForestRegressor
   - XGBRegressor

   **5.3 NN Models for Image Datasets:**
   - Neural Network Model
   - Convolutional Neural Network (CNN) Model

**6. Model Optimization (Cross Validation):**
   - GridSearchCV implemented in the classification problem-solving pipeline.
   - Usage of RidgeCV and LassoCV in the regression section.

**Dataset Bibliography:**
1. Pistachio EDA2023 (Classification): [Pistachio EDA2023 Dataset](https://www.kaggle.com/code/aaditshukla/pistachio-eda2023/input?select=pistachio.csv)
2. Life Expectancy (WHO) (Regression): [Life Expectancy Dataset](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)
3. Chinese MNIST (NN and CNN models): [Chinese MNIST Dataset](https://www.kaggle.com/datasets/gpreda/chinese-mnist)

