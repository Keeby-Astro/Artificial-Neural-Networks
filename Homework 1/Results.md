# Results for Homework 1

Stock price prediction using yfinance data from 1-1-2023 to 12-31-2024 for MSFT stock price

---
## Linear Regression model
- Train Error: 80.22625277128465
- Test Loss: 7971.891519172626

--- 
## STOCKNN model
- Standard Model Parameters: 1921
- Best Combination: Optimizer = SGD, Scheduler = OneCycleLR
- Test Loss on scaled data: 0.7239
- Test MSE in original scale: 2531.6323

---
## ADVANCEDSTOCKNN model
- Advanced Model Parameters: 1441
- Best Combination: Optimizer = SGD, Scheduler = ReduceLROnPlateau
- Test Loss on scaled data: 0.1073
- Test MSE in original scale: 375.2691
