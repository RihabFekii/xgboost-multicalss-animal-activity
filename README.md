# xgboost-multicalss-animal-activity

Training an XGboost for multiclass classification for animal activity based on coordinates 

- The data used for training is in a tabular format 

## Imbalanced dataset handling 

The target class in this data is imbalanced and below you can see the distribution
![alt text](http://url/to/img.png)

In this notebook, you can find ways to handle this class imbalance with the following techniques: 
- Choosing the right classification model: I used XGboost because it is robust to class imbalance 
- Model metrics: F1 score is a better metric than accuracy to evaluate the model performance
- Stratified train-test-splits are desirable in some cases, like when you’re classifying an imbalanced dataset, 
  a dataset with a significant difference in the number of samples that belong to distinct classes.
  


