# 📊 Simple vs. Multiple Linear Regression

In regression, the main difference between **Simple Linear Regression** and **Multiple Linear Regression** lies in the **number of input (independent) variables**.

---

## 🔹 Simple Linear Regression
- Uses **only one independent variable (X)** to predict the dependent variable (Y).  
- The relationship is represented by a straight line:

\[
Y = mX + b
\]

Where:  
- **Y** = Dependent variable (output)  
- **X** = Independent variable (input)  
- **m** = Slope (rate of change in Y with respect to X)  
- **b** = Intercept (value of Y when X = 0)  

---

## 🔹 Multiple Linear Regression
- Uses **two or more independent variables** to predict the dependent variable (Y).  
- The model considers the effect of each input variable individually.  

\[
Y = b_0 + b_1X_1 + b_2X_2 + b_3X_3 + \dots + b_nX_n + \varepsilon
\]

![Mulitple Linear Regression](https://github.com/sahilkarande/Machine-Learning-Algorithms-Course/blob/main/Python%20ML/Images/s4_multiple_linear_regression.png)


Where:  
- **Y** = Dependent variable (output)  
- **X₁, X₂, …, Xₙ** = Independent variables (inputs)  
- **b₀** = Intercept (baseline value of Y when all X = 0)  
- **b₁, b₂, …, bₙ** = Slopes (effect of each independent variable on Y)  
- **ε (error term)** = Captures noise and unexplained variation  

---

## 📌 Interpretation
- Each **slope coefficient (bₖ)** tells us how much **Y changes when Xₖ increases by one unit**, while keeping all other inputs constant.  
- For example:  
  - If **b₁ = 2**, then increasing **X₁** by 1 increases **Y** by 2 (assuming other variables remain fixed).  
- Graphically:  
  - **Simple regression** is a **straight line** in 2D space.  
  - **Multiple regression** is repres
