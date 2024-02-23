# Bird_Species_Classification

The file with extension ".ipynb" contains a code which provides taken steps to create a model for classificating 525 bird species from images.
The dataset used for the model:
https://www.kaggle.com/datasets/gpiosenka/100-bird-species/data

The model was created in following order:
* Feature Extraction model using EfficientNetV2
* Fine-tuned, above model

The model were evaluated using:
* confusion matrix
* loss and accuracy curve plots
* precision, accuracy, recall and F1-score metrics
  
The fine-tuned model achieves accuracy around 97% on a validation set and 99% on a training set.
