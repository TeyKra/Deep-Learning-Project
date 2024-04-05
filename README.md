# Project_Deep_Learning_M1

# Deep Learning on Image Data

In this project, we focus on developing and comparing deep learning models on image data. Due to time constraints, we fix the total epoch number to 50 with a patience of 5. All models incorporate regularization techniques covered in the course. The final submission will be in HTML format; please refer to the attached document for instructions on generating this file.

## Getting Started

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

You'll need to download the X and y data using the load function from the numpy package.

### Installation

No installation is required other than the numpy package for loading data. You can install numpy using pip if you haven't already:

## Project Tasks

1. **Data Loading**
   - Use the load function from the numpy package to download the X and y data.

2. **Data Visualization**
   - Plot 8 images and display their corresponding labels.

3. **Data Splitting**
   - Split the data into training and test sets with 12% of the data reserved for testing.

4. **Baseline Model**
   - Define a baseline learning model without CNN layers, featuring 4 hidden dense layers. Report validation and test scores.

5. **Prediction Visualization Function**
   - Write a function to plot the predicted labels, coloring correct predictions in blue and incorrect ones in red, along with the probability of the predicted label.

6. **CNN Model Training**
   - Train a second model using the following CNN architecture: `Conv−Pool−Conv−Pool−Conv−Conv−Pool−Dense−Dense`.

7. **Performance Evaluation**
   - Calculate and report the validation and test scores for the CNN model.

8. **Transfer Learning**
   - Train a transfer learning model using an approach from the Keras API that was not covered during the course.

9. **Comparative Table**
   - Compare the best test scores of the three models by putting them in a single table and print it.

10. **Hyperparameter Tuning**
    - Fine-tune two hyperparameters: dropout and kernel initializers, of the deep neural network obtained in step 5 using scikit-learn.

11. **Denoising Autoencoder**
    - Train a CNN denoising autoencoder on the data. Show before and after images of the denoising process. For noise generation, use a normal distribution with a mean of 0.1 and variance of 0.3. Reduce the initial size of images by at least a factor of 10 and compute this rate (include it in a comment).
