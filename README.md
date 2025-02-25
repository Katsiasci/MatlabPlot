# 回归分析与可视化
# Regression Analysis and Visualization

本项目提供了一个基于MATLAB的工具，用于执行回归分析并可视化结果。它设计用于处理包含实验（实际）值和预测值的数据集。该工具生成散点图、回归线、误差边界，并包括数据分布的直方图。关键评估指标，如AAE（平均绝对误差）和R²（决定系数），也会与图形一起显示，便于模型评估。
This project provides a MATLAB-based tool for performing regression analysis and visualizing the results. It is designed to work with datasets containing experimental (actual) and predicted values. The tool generates scatter plots, regression lines, and error bounds, and also includes histograms for data distribution. Key evaluation metrics such as AAE (Average Absolute Error) and R² (coefficient of determination) are displayed alongside the plots for better model evaluation.

### 特性：
- **散点图**：显示预测值与实际值的关系。
- **回归线**：可视化拟合效果。
- **误差边界**：显示模型误差范围（±20%）。
- **直方图**：显示实际值和预测值的分布。
- **模型评估指标**：自定义显示AAE和R²等性能指标。

### 要求：
- MATLAB（兼容最近版本）。

### 使用方法：
1. 准备包含实际值和预测值的数据集。
2. 调用 `plotRes2Pre` 函数来可视化回归结果。
3. 查看评估指标和模型性能。
   
### Usage:
1. Prepare your dataset with actual and predicted values.
2. Call the `plotRes2Pre` function to visualize the regression results.
3. View the evaluation metrics and performance.

此工具适用于需要快速、简便地可视化回归模型结果并评估模型性能的MATLAB用户。
This tool is ideal for those working with regression models in MATLAB who need a quick and easy way to visualize their results and assess model performance.

![image](https://github.com/user-attachments/assets/71e2b6e2-9e2c-40eb-b995-2da37e921640)
