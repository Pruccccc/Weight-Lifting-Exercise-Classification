# Weight Lifting Exercise Classification

**Author:** Rofi Fitriyani  
This project uses sensor data from wearable devices to classify barbell lift exercises. By applying machine learning techniques, especially a Random Forest classifier, it identifies how accurately participants perform these exercises.

## Dataset Source
Provided by: [PUC-Rio Human Activity Recognition Project](http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har)

- Training Data: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv
- Testing Data: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

## Summary Workflow
1. Load & clean the dataset
2. Split data for training and validation
3. Train the model using Random Forest
4. Evaluate performance with confusion matrix
5. Predict test cases and export individual results

## Model Accuracy
> Achieved over 99% classification accuracy on validation set.