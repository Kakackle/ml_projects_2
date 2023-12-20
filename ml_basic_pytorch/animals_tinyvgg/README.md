Data from: https://www.kaggle.com/datasets/alessiocorrado99/animals10
Changes made:
* renamed folders to english names from italian
* split images into two folders: test and train at a 0.8 / 0.2 ratio
* 

Files included:
* data_setup.py - create pytorch dataloaders for image classification data, expects paths to train dir and test dir, returns dataloaders and class names
* model_builder.py - create model with selected input shape (channels), hidden_units, output classes shape
* engine.py - test and train steps, train function
* utils.py - saving the model
* train.py -train, evaluate and save the model