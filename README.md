# SBU-ML-Fall2022  

[![Python-package GitHub Actions Build Status](https://github.com/microsoft/LightGBM/workflows/Python-package/badge.svg?branch=master)](https://github.com/microsoft/LightGBM)
[![Documentation Status](https://readthedocs.org/projects/lightgbm/badge/?version=latest)](https://lightgbm.readthedocs.io/)
[![License](https://img.shields.io/github/license/microsoft/lightgbm.svg)](https://github.com/microsoft/LightGBM/blob/master/LICENSE)
[![Python Versions](https://img.shields.io/pypi/pyversions/lightgbm.svg?logo=python&logoColor=white)](https://pypi.org/project/lightgbm)
[![PyPI Version](https://img.shields.io/pypi/v/lightgbm.svg?logo=pypi&logoColor=white)](https://pypi.org/project/lightgbm)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12ngDNadTrmApMRvIqsHMCzzS1UZRqRfN?usp=sharing)  

+ Review for **LightGBM** [paper](https://proceedings.neurips.cc/paper/2017/file/6449f44a102fde848669bdd9eb6b76fa-Paper.pdf).  
+ [Implementation](https://github.com/Mojtaba-Alehosseini/SBU-ML-Fall2022/blob/21dce5a2b61da957d58386f0c4fb7d11ffd6e16a/LightGBM.ipynb) of Gradient Boosting and LightGBM framework on Apple Inc (AAPL) NASDAQ prices [dataset](https://github.com/Mojtaba-Alehosseini/SBU-ML-Fall2022/blob/21dce5a2b61da957d58386f0c4fb7d11ffd6e16a/AAPL%20Historical%20Data.csv).  

<img src=https://github.com/microsoft/LightGBM/blob/master/docs/logo/LightGBM_logo_black_text.svg width=300 />

> **Ensemble learning** is a machine learning technique that combines the predictions of multiple models to produce a more accurate and robust prediction. It leverages the idea that multiple models can learn complementary information from the data and therefore can produce a more robust prediction than any single model. The combination of predictions from multiple models can be done by either voting (for classification problems) or by averaging (for regression problems). Some popular ensemble methods include bagging, boosting, random forests, and stacking.  

> **LightGBM** is a machine learning algorithm that uses decision trees to make predictions. It is fast and efficient, especially for large datasets, and is used for both regression (predicting a continuous value) and classification (predicting a label) tasks. It works by building multiple trees and combining their predictions to make the final result. This approach is called "boosting" and helps improve the accuracy of the model.  


Reference Papers
----------------
Guolin Ke, Qi Meng, Thomas Finley, Taifeng Wang, Wei Chen, Weidong Ma, Qiwei Ye, Tie-Yan Liu. "[LightGBM: A Highly Efficient Gradient Boosting Decision Tree](https://papers.nips.cc/paper/6907-lightgbm-a-highly-efficient-gradient-boosting-decision-tree)". Advances in Neural Information Processing Systems 30 (NIPS 2017), pp. 3149-3157.

Dataset
----------------
Apple - 10 Year Stock Price History [kaggle](https://www.kaggle.com/datasets/aleksandrdubrovin/apple-stock-price-history).  
Source [investing.com](https://www.investing.com/equities/apple-computer-inc-historical-data).  
Coverage: Temporal coverage start date ***03/25/2012*** and Temporal coverage end date ***03/25/2022***.
