# Flight Delay Prediction with TensorFlow

This project is dedicated to predicting flight delays using machine learning with TensorFlow. The dataset used is equipped with pertinent features to train the model, and the target variable is 'DEP_DEL15', indicating whether a departure delay occurred (1 for yes, 0 for no).

## Objectives:

1. **Data Cleaning:**
   The dataset is cleaned by removing unnecessary columns, and missing values are handled. Categorical columns like 'ORIGIN', 'DEST', and 'DEP_TIME_BLK' are label-encoded for model compatibility.

2. **Label Encoding:**
   Categorical columns are encoded to numeric values to facilitate model training.

3. **Model Architecture:**
   The project explores three different model architectures to compare their performances:
   - Model 1 (baseline): ReLU activation, 'adam' optimizer.
   - Model 2: ELU activation, 'adamax' optimizer.
   - Model 3: SELU activation, 'nadam' optimizer.

4. **Training and Evaluation:**
   Each model is trained on separate sets—`model.fit` records training history for later evaluation. The models are evaluated on validation sets, and their performance is compared.

## Benefits:

- **Customizable Architecture:**
  The architecture of each model is customizable, providing users with the flexibility to experiment with different layer sizes and activation functions.

- **Data Preprocessing:**
  The code includes comprehensive data preprocessing steps, ensuring the dataset is ready for model training.

- **Model Comparison:**
  Three distinct models are implemented for users to compare and contrast. This enables a deeper understanding of how different architectures and configurations impact predictive accuracy.
