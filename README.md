# 🍄 Mushroom Classification Model 🍄
Dive into the world of fungi and discover whether a mushroom is edible or poisonous with the help of our cutting-edge machine learning model!

## 📋 Table of Contents
- Introduction
- Features
- Data Cleaning and Preprocessing
- Model Selection
- Hyperparameter Tuning
- Conclusion
- 
## 📌 Introduction
In the vast world of fungi, it's crucial to distinguish between the edible and the dangerous. Our dataset consists of 8000 mushrooms, among which:

- 🟢 90 are edible but not eaten
- 🔴 0 are poisonous and have been consumed.
Our objective is to classify these mushrooms accurately to ensure safety and enjoyability.

## 📘 Features
Our dataset consists of six categorical features which provide insights into the characteristics of each mushroom. The features are:

1. cap shape
2. cap color
3. bruises
4. stalk color above ring
5. stalk color below ring
6. population
   
## 🔧 Data Cleaning and Preprocessing
Due to the categorical nature of our features, a significant portion of our preprocessing involves cleaning and encoding:

1. Cleaning: We've cleaned up missing values, outliers, and any inconsistencies present in the data.
2. Encoding: To make our data suitable for machine learning, we've employed encoding techniques to transform our categorical features into a numerical format.

## 🤖 Model Selection
After analyzing the performance of various classification models using a confusion matrix, the MLP Classifier emerged as the most promising model for our task. The reasons for selecting the MLP Classifier include:

- High accuracy on the validation set
- Effective handling of categorical data
- Versatility in adapting to the data distribution

## ⚙️ Hyperparameter Tuning
To get the best out of our MLP Classifier, we undertook a rigorous hyperparameter tuning process. Using techniques like grid search and random search, we ensured that our model performs at its peak capability.

## 📝 Conclusion
Safety first! With the help of our Mushroom Classification Model, you can confidently navigate the world of mushrooms and ensure that your culinary adventures are both delicious and safe. Enjoy the wonders of nature with the assurance of our model by your side!
