# Virtual Reality Immersion Prediction

This repository contains the machine learning code and analysis for predicting user immersion levels in virtual reality (VR) experiences. The aim is to identify how various factors such as age, gender, VR headset type, duration, and motion sickness levels contribute to the overall immersion of VR experiences.

## Project Structure

```text
.
├── VR_ImmersionLevel_Prediction.ipynb  # Jupyter notebook with the main analysis                           # The license file
└── README.md                            # The README file for understanding the project structure
```

## Dataset


- `Age`: Age of the VR user
- `Gender`: Gender of the VR user
- `VRHeadset`: Type of VR headset used
- `Duration`: Duration of the VR experience
- `MotionSickness`: Level of motion sickness reported
- `ImmersionLevel`: Target variable indicating the level of immersion experienced

## Features

The data has been processed to create specific features for predictive modeling:

- Age groups are binned and one-hot encoded.
- Gender is one-hot encoded.
- VR headset types are one-hot encoded.
- Duration is binned and one-hot encoded.
- Motion sickness levels are one-hot encoded.

## Machine Learning Model

The main machine learning model used in this project is a Logistic Regression classifier, selected for its interpretability and efficiency. The model's performance is evaluated using multiple metrics including Mean Absolute Error (MAE), Accuracy Score, Confusion Matrix, and a Classification Report.

