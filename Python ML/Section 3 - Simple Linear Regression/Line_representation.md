# 📐 The Equation of a Line in Linear Regression

You may already be familiar with the general equation of a line:

\[
y = mx + b
\]
<img src="https://github.com/sahilkarande/Machine-Learning-Algorithms-Course/blob/main/Python%20ML/Images/s3_Line_rep.png" alt="Linear Regression" width="250" />

Where:
- **y** → Dependent variable (what we want to predict)  
- **x** → Independent variable (input feature)  
- **m** → Slope of the line (rate of change)  
- **b** → Intercept (value of y when x = 0)  

---

## 🔹 Applying to Our House Price Example
- **Dependent variable (y):** `Price of the house`  
- **Independent variable (x):** `Surface area (sq. ft.)`  
- **m (slope):** How much the price changes per unit increase in surface area  
- **b (intercept):** The predicted price when the surface area is zero  

Thus, our regression model can be written as:

\[
\text{Price} = m \times \text{Area} + b
\]

---

## 🔹 Goal
- Find the **best values** of **m** and **b** such that the line fits the data with minimum error.  
- Once fitted, we can **predict the price** of any house by plugging in its surface area.

Example:  
If the area = `330 sq. ft.`, substitute into the equation to get the predicted price.
