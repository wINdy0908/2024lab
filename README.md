# Machine Learning Application on Surface Roughness Forecast and Surface Texture Analysis

This article explores the application of machine learning in predicting various surface roughness parameters, such as arithmetic mean height (Sa), maximum height of the surface (Sz), and texture aspect ratio (Str), from images of aluminum materials. 

Additionally, it conducts a cluster analysis to distinguish surface irregularities. The discussion extends to data processing and manipulation
techniques applied to material image data, starting with the normalization of image data. Subsequently, it utilizes a pre-trained model, such as VGG-16, to extract significant features from the image data. To mitigate extensive computational costs, it implements the Principal Component Analysis (PCA) technique. 

Through this data processing approach, the study builds Convolutional
Neural Network (CNN), XGBoost, and Stack Regression models to fit the image data and forecast the surface roughness parameters.

Furthermore, it employs a Random Forest model in cluster analysis to determine the presence of irregularities in the images. Based
on each model’s performance in forecasting parameters, it’s evident that they accurately forecast Sa and Sz, achieving maximum accuracy of 83% and 77% as defined by R-squared. However, they perform poorly on Str due to 57% maximum accuracy. Random
Forest models excel in classifying images into four groups with a 95% accuracy and determining material surface uniformity with 86% accuracy.
