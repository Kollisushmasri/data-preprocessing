# data-preprocessing
Data standardization
Data standardization is a crucial data preprocessing technique used to transform features in a dataset to a common scale without distorting differences in the ranges of values. It involves rescaling the data so that it has a mean of 0 and a standard deviation of 1. 
This is particularly important when the dataset contains features with different units or scales, such as age (ranging from 0 to 100) and income (ranging from thousands to millions). Standardization ensures that no feature dominates the model due to its scale, making it easier for machine learning algorithms, particularly those that rely on distance metrics (like K-nearest neighbors or support vector machines), to perform optimally. 
The most common method of standardization is the Z-score normalization, where each feature value is transformed using the formula:  
![image](https://github.com/user-attachments/assets/162d37f6-e159-4785-93a9-99674c0f69c0)


