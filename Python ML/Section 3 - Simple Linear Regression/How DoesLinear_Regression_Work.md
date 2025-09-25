# 🏠 Example: How Linear Regression Works

Let’s explore **linear regression** using a real-world example: predicting **house prices** based on the **area** of the house.

---

## 🔹 Dataset
We have a table with the **area (in sq. ft.)** and the **corresponding price** of several houses.  
Our goal: **Predict the price of a 330 sq. ft. apartment** using this data.

---

## 🔹 Visualizing the Data
- Plot the given data points on a **scatter plot**.  
- Red dots represent the **actual house prices** for the corresponding areas.

![Linear Regression](https://github.com/sahilkarande/Machine-Learning-Algorithms-Course/blob/main/Python%20ML/Images/s3_Regression.png)

---

## 🔹 Fitting the Best Line
- Linear regression tries to fit a **line** through the data points to predict prices.  
- We can draw many possible lines, but **which one is the best?**

### Step 1: Calculate Errors
- For each line, calculate the **difference (error) between the actual points and the line**.  
- Denote these errors as `Δ1, Δ2, ... Δn`.

### Step 2: Compute Squared Errors
- Square each error to avoid negative values.  
- Sum all squared errors for the line:  
  \[
  \text{Total Error} = \sum (\text{predicted} - \text{actual})^2
  \]

### Step 3: Find the Minimum Error
- Repeat the process for multiple lines.  
- The line with the **minimum total squared error** is chosen as the **best fit**.  
- In our example, this is shown as the **blue line**.

---

## 🔹 Making Predictions
- Once the **best fit line** is determined, we can use it to **predict the price** of any house.  
- Example: Using the blue line to predict the price of a **330 sq. ft. apartment**.

---

## 📌 Key Point
Linear regression minimizes the **sum of squared errors** between the predicted and actual values to find the **line of best fit**.
