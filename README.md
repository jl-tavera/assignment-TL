## Transfer Learning and Neural Network README

### Authors:
- Carlos Rubiano (202013484)
- Jose Luis Tavera (201821999)

### Point 1: Neural Network for Predicting 'Target'

We created a neural network model to predict the 'target' column using the remaining covariates in the `df_bd.pkl` dataset. 

Steps:
1. Loaded the dataset.
2. Split the dataset into predictor variables (X) and the target variable (y).
3. Normalized the features if necessary.
4. Built a neural network model using Keras.
5. Compiled the model specifying the loss function and optimizer.
6. Trained the model using training data.
7. Evaluated the model's performance on test data using accuracy metric.

### Point 2: Transfer Learning for Image Classification

We used transfer learning to classify images in the datasets folder and compared the results of the model considering the best prediction result or the best two.

Steps:
1. Loaded training and validation sets using `image_dataset_from_directory`.
2. Chose a base model from `keras.applications`.
3. Applied data augmentation layers like `RandomFlip` and `RandomRotation`.
4. Created `keras.Input` for model input.
5. Applied preprocessing of the base model to the data.
6. Used the base model with preprocessed data.
7. Added new layers to the model.
8. Compiled the model using `compile` method and trained it with `fit` method.

For more details, please refer to the specific code implementations provided in the previous responses.

---
This README summarizes the steps taken to implement transfer learning for image classification and create a neural network for predicting a target variable, as requested.

