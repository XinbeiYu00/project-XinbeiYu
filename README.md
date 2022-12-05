This project explores which factors affect the easiness of taking a mental health leave from work in tech companies. It used machine learning models such as SVC, XGBClassifier, KNN, Logistic Regression and Random Forest. The result accuracy for the five classes of target variable is around 0.5 generated by SVC model. 

This project is developed using 3.10.5, for all other configuration, reference yaml file.

For an overview of the yaml file:
name: projectXinbeiYu
channels:
- conda-forge
- defaults
dependencies:
- python=3.10.5
- matplotlib=3.5.2
- pandas=1.4.2
- scikit-learn=1.1.1
- numpy=1.22.4
- xgboost=1.5.1
- shap=0.40.0
- jupyter_client=7.3.1
- jupyter_core=4.10.0
- jupyterlab=3.4.2
- jupyter_server=1.17.0
- jupytext=1.13.8
- rise=5.7.1
- plotly=5.8.0
- ipywidgets=7.7.0
prefix: /opt/conda
