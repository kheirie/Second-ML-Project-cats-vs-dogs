# cats-vs-dogs

This project was created for learning purposes.
The objective was to:
- Explore deep learning and neural networks
- Understand the basics of Convolutional Neural Networks (CNNs)
- Use Keras to train a simple model that classifies images as cats or dogs
  
For a better comprehensive understanding of the architecture of convolutional neural networks, I wrote the following article: https://kheirie-elhariri.medium.com/convolutional-neural-networks-for-image-classification-c403159e81af

## About the Data 
Data used in this project can be found here: https://www.kaggle.com/tongpython/cat-and-dog

## Requirements
The following are necessary to run the notebook:
- Python == 3.12.11
- TensorFlow == 2.19
- Pandas == 2.2.2
- NumPy == 2.0.2
- scikit-learn == 1.6.1
- Matplotlib == 3.10

## Evaluation and Metrics 
This is a binary classification problem (cats vs dogs), and the dataset is balanced (roughly equal number of cat and dog images). Therefore, accuracy was chosen as the primary evaluation metric.
- The model achieved an accuracy of ~90% on the test set.
- Both training accuracy/loss and validation accuracy/loss were plotted across epochs to analyze performance.
- Early stopping was applied on the validation loss to prevent overfitting and stop training once the model stopped improving.
