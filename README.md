# Image-Classification
### This project demonstrates a complete pipeline for building an image classification model, from data preprocessing to model training, evaluation, and saving. The key components include handling data, designing a neural network, training the model with TensorFlow, and finally testing and deploying the model.

 
## Data Preparation:

Organize your images in the data/ directory, with subfolders for each class.
## Remove Invalid Images:

The script automatically removes images that don't match expected formats (jpeg, jpg, bmp, png).
## Load and Preprocess Data:

Images are loaded, labeled, and normalized (scaled between 0 and 1).
## Build and Train the Model:

A CNN model is built using Keras and trained on the dataset for 20 epochs.
## Evaluate the Model:

The model is evaluated using precision, recall, and accuracy metrics.
## Test the Model:

Test the model with new images to predict the class (e.g., "Happy" or "Sad").
## Save the Model:

The trained model is saved to the models/ directory for future use.
