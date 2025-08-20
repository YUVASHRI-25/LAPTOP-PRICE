**💻 Predicting Laptop Price from RAM**

**📌 Project Overview**

This project demonstrates how Linear Regression can be used to predict Laptop Price based on RAM size (in GB).

Dataset contains information about laptops such as RAM, Price, Processor, Storage, and more.

For simplicity, we trained a regression model using only RAM as the feature to predict laptop prices.

**The task: Predict the price of a laptop with 16GB RAM.**

**📊 Dataset**

Source: Provided dataset (Laptop_Price.csv)

Target Variable: Price (Laptop price in INR)

Feature Used (for simple regression): RAM (GB)


**Steps followed in the notebook:**

Load the dataset using pandas.

Select features: X = RAM (GB), y = Price.

Train Linear Regression model using scikit-learn.

Predict price for a laptop with 16GB RAM.

Visualize the regression line vs. actual data.

**📈 Results**
The model successfully predicts a price for 16GB RAM laptops.

However, the predictions are not very accurate, since price depends on many other features.

**⚠️ Why Using Only RAM Is Not Accurate?**

Laptop prices are influenced by multiple factors, not just RAM.
Some key reasons:

Multiple Features Matter – Processor, Storage, GPU, Screen Size, Brand, etc.

Non-Linear Growth – Price does not increase in a straight line with RAM.

Overlapping Prices – Some 8GB laptops cost more than 16GB laptops.

Premium Devices – MacBooks and gaming laptops cost much more despite same RAM.

Better with Multiple Regression – Using all features improves accuracy significantly.

**✅ Conclusion**

Simple Regression (using only RAM): Works, but predictions are rough.

Multiple Regression (using all features): More realistic and accurate.

👉 This project shows how feature selection impacts model accuracy, and why using only one feature (RAM) is not enough for predicting laptop prices.
