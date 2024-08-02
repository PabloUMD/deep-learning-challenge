
# Alphabet Soup Charity Analysis

This project aims to build and optimize a neural network model to predict the success of charity funding applications for the Alphabet Soup nonprofit foundation. The project is structured in three main steps:

1. **Preprocess the Data:** 
   - Data was loaded and preprocessed to remove unnecessary columns and encode categorical variables.
   - The data was then split into training and testing sets, and the features were scaled.

2. **Compile, Train, and Evaluate the Model:** 
   - A neural network model was designed with input, hidden, and output layers.
   - The model was compiled and trained on the scaled training data.
   - The model's performance was evaluated using the test data, and the results were saved.

3. **Optimize the Model:** 
   - The model was optimized by adding more neurons, layers, and dropout to prevent overfitting.
   - The optimized model was trained and evaluated, and the results were compared with the initial model.

## Files in this repository:

- **AlphabetSoupCharity_Model.ipynb:** The complete notebook containing the preprocessing, model training, and optimization steps.
- **AlphabetSoupCharity.h5:** The HDF5 file containing the trained model.
- **AlphabetSoupCharity_Optimization.h5:** The HDF5 file containing the optimized model.
- **README.md:** This file, providing an overview of the project.

## Model Performance:

- **Initial Model:**
  - Loss: (insert loss)
  - Accuracy: (insert accuracy)

- **Optimized Model:**
  - Loss: (insert loss)
  - Accuracy: (insert accuracy)

## Summary:

The neural network model was able to predict the success of charity funding applications with a certain degree of accuracy. Optimization efforts, including increasing neurons, adding dropout layers, and extending training epochs, led to a measurable improvement in model performance. Further experimentation with other models like Random Forests or Support Vector Machines may provide additional insights and potentially better performance.

