# ece5300/au20 Default Project (student repo)

This repository contains data and starter notebooks for the default project. 
The [data](./training_data) consists of
* K=20 classes
* n/K=5000 samples per class
* d=20 features per sample

The [model_validation.ipynb](./model_validation.ipynb) notebook shows how to 
* load the data, which is stored as per-class .csv files,
* load and evaluate a trained [sklearn model saved via pickle](https://machinelearningmastery.com/save-load-machine-learning-models-python-scikit-learn)
* load and evaluate a trained [PyTorch model saved via the trace](https://stackoverflow.com/questions/59287728/saving-pytorch-model-with-no-access-to-your-code) 

The [pytorch_saving_demo.ipynb](./pytorch_saving_demo.ipynb) provides additional details about saving and loading PyTorch models.
