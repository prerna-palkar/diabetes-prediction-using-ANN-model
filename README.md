# Diabetes Prediction using ANN

A Deep Learning project that predicts whether a person is likely to have diabetes using an Artificial Neural Network (ANN).

## Dataset

Pima Indians Diabetes Dataset.

* 768 records
* 8 input features
* 1 target variable: `Outcome`

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Seaborn

## Project Workflow

1. Load and understand the dataset
2. Separate features (`X`) and target (`y`)
3. Split data into training and testing sets
4. Scale the features
5. Build an ANN
6. Compile and train the model
7. Evaluate the model
8. Analyze predictions using a confusion matrix
9. Calculate precision, recall and F1-score
10. Test predictions on new data

## Model

The ANN contains:

* Input layer: 8 features
* Hidden layer: 8 neurons
* Hidden layer: 4 neurons
* Output layer: 1 neuron with sigmoid activation

## Results

The model was evaluated using:

* Accuracy
* Confusion Matrix
* Precision
