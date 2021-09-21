# Auto-ML

## Auto-Ml involces the selection of  data preparation, machine learning model and model hyperparameters for a predictive modeling task.
Central to the approach is defining a large hierarchical optimization problem that involves identifying **data transforms and the machine learning models themselves**, in addition to the **hyperparameters** for the models.

**Key words :** Search Space, Bayesian Optimization,

## Libraries 
1.Scikit-learn 
  - Auto-Sklearn  [official paper](https://papers.nips.cc/paper/2015/file/11d0e6287202fced83f79975ec59a3a6-Paper.pdf).**(pip install autosklearn)**
  - Tree-based Pipeline Optimization Tool,  TPOT . **(pip install tpot)**
  - Hyperop-Sklearn, suited for large-scale optimization with hundreds of parameters that can be scaled across multiple cores. **(pip install hyperopt)**

2. Keras
  - Auto-Keras, built to find the best performing deep learning model for classification and regression. Searches for architecture and hyperparameters for deep learning models and trains them using the training data, and returns the best performing deep learning model are the final result . **(pip install autokeras )**

3. AutoGluon
  Amazon's autoML framework open sourced by AWS. It also supports Image classification, Object detection, Text, and real-world applications spanning image. Searches for  best performing deep learning architecture and hyperparameters,Model selection and Automatic hyperparameter tuning,Automatic data preprocessing. 
  It uses MXNet as a backend.
