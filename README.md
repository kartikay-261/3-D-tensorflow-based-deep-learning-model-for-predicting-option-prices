# 3-D-tensorflow-based-deep-learning-model-for-predicting-option-prices
The project is organized into three main folders: "data," "core," and "main," corresponding to different aspects of the research on 3D Tensor-based Deep Learning Models for Predicting Option Price. 

1. **Data Folder:**
   - The "data" folder contains 50ETF option and stock option data collected from the Chinese stock and fund market.
   - The data is split into training and test sets.
   - The "test_data_BS.py" file is specifically designed for the Black-Scholes (B-S) model, a classic option pricing model.
   - A subfolder named "torch-data" stores torch tensors generated by the "data_process.py" script.

2. **Core Folder:**
   - The "core" folder contains four files responsible for constructing the deep learning models discussed in the manuscript.
   - Additionally, there is a single file dedicated to data processing.

3. **Main Folder:**
   - In the "main" part, the models and data can be applied to predict option prices.
   - The performance of different models can be compared using five metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), Mean Absolute Error (MAE), and Pearson Correlation Coefficient (PCC).
   
For a comprehensive understanding of the project and its methodologies, readers are encouraged to refer to the original manuscript titled "3D Tensor-based Deep Learning Models for Predicting Option Price" available on arXiv at [https://arxiv.org/abs/2106.02916](https://arxiv.org/abs/2106.02916).
