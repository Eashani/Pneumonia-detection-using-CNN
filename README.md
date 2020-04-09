# Pneumonia-detection-using-CNN
Using neural networks for pneumonia detection

## Dataset
The dataset was sourced from Kaggle: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
It consists of a set of X-ray images that have scans of patients with and without pneumonia
<div class="row">
  <div class="column">
<img src="https://github.com/Eashani/Pneumonia-detection-using-CNN/blob/master/IM-0003-0001.jpeg" alt="Sample data_no_pneumonia" width="300" height="300">
</div>
  <div class="column">
<img src="https://github.com/Eashani/Pneumonia-detection-using-CNN/blob/master/person18_virus_49.jpeg" alt="Sample data_pneumonia" width="300" height="300">
</div></div>

## Data Exploration
The training dataset had a class imbalance and so only a part of the dataset was used where examples of both the classes were equal

<img src="https://github.com/Eashani/Pneumonia-detection-using-CNN/blob/master/class%20imbalance.png" alt="Sample data_pneumonia" width="400" height="300">

The balanced training set and the validation set and testing had a split of (2682,16,468)


## Model Statistics and Accuracy

4 convolution layers with relu activation function and 1 softmax layer at the end. A dropout layer after every convolution with the adam optimizer and 15 epochs


## Confusion Matrix
<img src="https://github.com/Eashani/Pneumonia-detection-using-CNN/blob/master/confusion%20matrix.png" alt="Sample data_pneumonia" width="300" height="300">

This model has a precision of 0.74 and a recall of 0.94
