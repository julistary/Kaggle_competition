# 💎 KAGGLE COMPETITION 💎

<img width=300 src="https://www.wallpapertip.com/wmimgs/11-111305_jewelery-bokeh-bling-abstraction-abstract-sparkle-wallpaper-diamond.jpg">

## Goal 🏁
This is a machine learning project that was sent to us at the Ironhack data analytics bootcamp. 

The objective of the project is to find the best machine learning model and params for a given dataset from [kaggle](https://www.kaggle.com/c/diamonds-datamad0321).


## Libraries 👩🏼‍🏫
- [Pandas](https://pandas.pydata.org/docs/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Numpy](https://numpy.org/doc/)
- [Sklearn](https://scikit-learn.org/stable/)
- [Xgboost](https://xgboost.readthedocs.io/en/latest/)


## My project 👩🏼‍💻
The first thing I did was importing and cleaning the `Diamonds` dataset.

For the prediction I trained the following models (in the best ones I adjusted the parameters through grid search)
* Linear Regression (MSE : 0.12)
* Ridge (MSE : 0.12)
* Lasso (MSE : 1.03)
* SGD (MSE : 2992133515461431)
* KNeighbors (MSE : 0.22)
* Gradient (MSE : 0.13)
* Random Forest (MSE : 0.0105)
* XGBoost (MSE : 0.0093)
* SVR (MSE : 0.133)
* MLP Regressor (MSE : 0.0208)

Although it seems that the best model is XgBoost, when submitting to Kaggle, the best model is Boosting. This must be because the model is overfitting. 

## Content of the repository 👀

- Data folder with the Kaggle dataset
- Img folder with some helpful images for understandig the dataset
- Models with the main predictions
- Models.ipynb with all the cleaning and predictions. 

## TO DO
- Compare test and train to analyze overfitting
- [H20](https://www.cienciadedatos.net/documentos/py04_machine_learning_con_h2o_y_python)