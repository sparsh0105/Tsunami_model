# Tsunami Prediction Model

Aim: To predict tsunami alerts from seafloor acoustic data using machine learning.

This project uses machine learning, specifically Lightgbm, to predict tsunamis from seafloor acoustic data.  XGBoost classifies data points as tsunami alerts or not based on acoustic and geophysical features.  Addressing the dataset's class imbalance (more "no tsunami" instances) is crucial, and techniques like adjusting class weights are employed.  A key challenge is the imprecise nature of the "tsunami alert" label, as it's a derived value, not a direct measurement.  This impacts model training and evaluation, requiring careful metric selection and interpretation of results.  The project aims to contribute to early warning systems despite these challenges.
