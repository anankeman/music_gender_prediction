## Music gender classifcation
This is the 2020-S2 COMP90049 playground for Assignment 2.

In this project the task is to perform music genre classification. Test different classification algorythms, experiment with different features, and analyse models through evaluation.

The code is in a Jupyter Notebook that it is divided in two parts that can be run independently.

### Analysis

The first is the analysis part that leaded to build the final model and contains comments of the research process documented in the final paper, as other metrics.

## Model development 
The second has the final train, predict and evaluate function requested in the specs. They uses as arguments the dataset provided in the specs to develop the model.

Main functions:
 - `train(train dataset, test dataset, train labels, test labels, random seed (default to 0))` 
Returns a trained model and a transformed testing dataset.

- `predict(model, test dataset transformed)`
Returns a list with predicted labels

- `evaluate(prediction list, test labels)`
Returns a classification report includin Accuracy, presicion, recall and f1- scores for each class.

## The dependencies are:
- Pandas, 
- Numpy, 
- Matplotlib, 
- Sklearn
- Imblearn
