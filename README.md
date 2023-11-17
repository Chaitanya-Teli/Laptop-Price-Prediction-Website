# Laptop-Price-Prediction-Website

A collection of machine learning models for predicting laptop prices.


<details>
<summary style="font-size: 20px;">Dependencies</summary>
To install the required Python packages you can use the following command:

```bash
pip install -r requirements.txt
```
</details>

<details>
<summary style="font-size: 20px;">Datasets Reference</summary>
The dataset is about laptops configuration with prices containing 1304 laptops data with 12 columns Company name,type namee, laptop size in (inches), Screen resolution, CPU, RAM, Memory, GP, Operating system, Price in INR.
</details>

<details>
<summary style="font-size: 20px;">Regressor Model Choices</summary>

- Multiple Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest
- ExtraTrees
- Adaptive Boost (AdaBoost)
- Gradient
- Extreme Gradient Boost (XGBoost)
- Random Forest Regressor Model
- Votingt Regressor Model (RF+GBDT+XGB+ET) - Personal Customization
- Stacking Regressor Model (RF+GBDT+XGB) - Personal Customization
</details>

<details>
<summary style="font-size: 20px;">Selected Regression Model</summary>

- Votingt Regressor Model (RF+GBDT+XGB+ET) - Personal Customization

```
R2 Score: 0.89 (89.02 %)
Mean Absolute Error: 0.15 (15.02 %)
```
- Stacking Regressor Model (RF+GBDT+XGB) - Personal Customization

```
R2 Score: 0.88 ( 88.08 %)
Mean Absolute Error: 0.17 ( 16.78 %)
```
</details>


<details>
<summary style="font-size: 20px;">Run <i>app.py</i></summary>
To run the app.py, load the dependecies requirements and use the following command:
<br><br>
  
```
streamlit run app.py
```
✨ Enjoy the demo
</details>

<hr>
<footer>
  Feel free to send issues if you face any problem. </br>
  ✨ Don't forget to star the repo :)
</footer>
