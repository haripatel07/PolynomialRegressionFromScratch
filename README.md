# Polynomial Regression: Custom Implementation vs Sklearn

## Project Overview  
This project explores **Polynomial Regression** by implementing it from scratch and comparing it with **Scikit-Learn's Polynomial Regression**. The goal is to understand how polynomial features influence regression models and evaluate their effectiveness using key metrics.

## Dataset  
The dataset used for this project is the **Real Estate Price Prediction Dataset** from Kaggle, containing numerical features suitable for polynomial regression. The independent variable **X** is transformed into polynomial features, and the dependent variable **Y** represents the target prices.

## Tools & Technologies  
- **Python**  
- **NumPy & Pandas** – Data manipulation & mathematical operations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-Learn** – Polynomial regression implementation  

## Project Workflow  
1. **Data Preprocessing**  
   - Feature selection and missing value handling  
   - Standardization of input features  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing data distribution  
   - Correlation analysis of features  

3. **Model Implementation**  
   - Implementing Polynomial Regression from scratch using NumPy  
   - Training and evaluating the custom model  
   
4. **Comparison with Scikit-Learn**  
   - Using `PolynomialFeatures` from Scikit-Learn  
   - Training and evaluating the Scikit-Learn model  
   - Comparing performance metrics  
   
5. **Evaluation Metrics**  
   - **Mean Squared Error (MSE)**  
   - **R² Score**  
   - Error analysis through visualization  

## Installation & Usage  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/haripatel07/PolynomialRegressionFromScratch.git  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the Jupyter Notebook:  
   ```bash  
   jupyter notebook polynomialregressionfromscratch.ipynb  
   ```  

## Future Enhancements  
- Extend the model to higher-degree polynomials  
- Implement regularization techniques (Lasso, Ridge)  
- Optimize hyperparameter selection  

## Author  
Developed by [Hari Patel](https://github.com/haripatel07)  

## License  
This project is open-source and available under the MIT License.

