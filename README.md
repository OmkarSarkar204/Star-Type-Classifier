# Star-Type-Classifier

## **Star Type Classifier**
A machine learning model that classifies stars into one of six types based on their physical and spectral characteristics.

## **Description**
This model uses a k-Nearest Neighbors (k-NN) algorithm to predict the type of a star, which can be a Brown Dwarf, Red Dwarf, White Dwarf, Main Sequence, Supergiant, or Hypergiant. The model is trained on a dataset containing stellar properties like temperature, luminosity, radius, and spectral class.

The notebook demonstrates a full machine learning pipeline, including:

* Data loading and exploration.

* Preprocessing of categorical and numerical features.

* Model training and evaluation.

* Making predictions on new, real-world examples (Sirius and Betelgeuse and many more).

### **Dataset**
Of course. Adding sections on features and formulas is an excellent way to make your README more detailed and professional. It shows you have a deeper understanding of the data and the mechanics of your model.

Here is an updated version of your README template with these new sections included.

Star-Type-Classifier
A machine learning project that classifies stars into one of six different types based on their physical and spectral characteristics.

Description
This project uses a k-Nearest Neighbors (k-NN) machine learning model to predict the type of a star. The model is trained on a dataset of stellar properties and demonstrates a complete ML workflow, including data preprocessing, feature scaling, model training, and evaluation.

## Dataset
The project uses the "Star Type Classification" dataset available on Kaggle. You can find it here: Star Type Classification Dataset

## Features
The model is trained using the following features. The categorical features (Star color, Spectral Class) are numerically encoded before being used.

* Temperature: Surface temperature in Kelvin (K).
* Luminosity (L/Lo): Relative luminosity compared to the Sun.
* Radius (R/Ro): Relative radius compared to the Sun.
*Absolute Magnitude (A_M): The intrinsic brightness of the star at a standard distance.
* Star Color: The apparent color of the star (e.g., Red, Blue-White).
* Spectral Class: The standard stellar classification (O, B, A, F, G, K, M).

## Target Variable
Star Type: The main goal of the model is to predict this value, which corresponds to one of six star classes:

* 0: Brown Dwarf
* 1: Red Dwarf
* 2: White Dwarf
* 3: Main Sequence
* 4: Supergiant
* 5: Hypergiant


### Results
The final k-NN model (using n_neighbors=3), after implementing StandardScaler for feature scaling, achieved an accuracy of 94% on the unseen test data. Feature scaling was found to be a critical step, improving the accuracy from an initial 77%.

The model demonstrates high precision and recall for most star types, proving its effectiveness.




<img width="851" height="120" alt="Screenshot 2025-08-21 at 4 24 49 PM" src="https://github.com/user-attachments/assets/5bd0c093-8f94-4e0d-b2df-4ae484601895" />


<img width="437" height="50" alt="Screenshot 2025-08-21 at 4 18 48 PM" src="https://github.com/user-attachments/assets/9f12541f-3cc4-41d2-a5b6-6aa2f0bfab96" />


