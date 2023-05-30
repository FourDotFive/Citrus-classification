# Citrus Fruit Classification Project

This project aims to classify citrus fruits into two categories: oranges and grapefruits, based on the fruit's physical properties: diameter, weight, and color components (red, green, blue).

## Data Source

The dataset used in this project was obtained from Kaggle, available [here](https://www.kaggle.com/datasets/joshmcadams/oranges-vs-grapefruit?resource=download). The dataset consists of physical properties of citrus fruits, including their diameter, weight, and color components.

## Data Analysis and Preprocessing

Preliminary data analysis revealed strong correlations between the fruit type and both the diameter and weight of the fruits. Conversely, the color components had weak correlations with the fruit type.

Based on these findings, the color features were dropped from the model to focus on the most informative features: diameter and weight. This step simplified the model, improved its performance, and made it more interpretable.

## Model Development

A Decision Tree classifier was trained using the remaining features. The model achieved high accuracy, demonstrating its effectiveness at classifying the fruit types based on diameter and weight.

## Conclusion

The project demonstrates the power of data-driven decision making in model development. By focusing on the most informative features, we were able to create a highly accurate model for citrus fruit classification.
