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
The model uses the "Star Type Classification" dataset available on Kaggle. You can find it at the following link: Star Type Classification Dataset.

### Results
The final k-NN model (using n_neighbors=3), after implementing StandardScaler for feature scaling, achieved an accuracy of 94% on the unseen test data. Feature scaling was found to be a critical step, improving the accuracy from an initial 77%.

The model demonstrates high precision and recall for most star types, proving its effectiveness.




<img width="851" height="120" alt="Screenshot 2025-08-21 at 4 24 49 PM" src="https://github.com/user-attachments/assets/5bd0c093-8f94-4e0d-b2df-4ae484601895" />


<img width="437" height="50" alt="Screenshot 2025-08-21 at 4 18 48 PM" src="https://github.com/user-attachments/assets/9f12541f-3cc4-41d2-a5b6-6aa2f0bfab96" />


