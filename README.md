# venture_funding
This application uses several binary classifier models to predict whether a perspective business applicant will become a successful business.  It does this by first preprocessing the data for the model.  Then it uses the model-fit-predict pattern to compile and evaluate the binary classification model.  The model is then optimized several times to determine how much loss and accuracy the model has in its prediction compared to the actual results from the data.

---


## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [pandas](https://github.com/pandas-dev/pandas) - A flexible and power data analysis/manipulation Python library used in financial calculations.

* [path](https://docs.python.org/3/library/pathlib.html) - Used to define file path

* [tensorflow](https://www.tensorflow.org/) - A Python library that is a proven platform to create models and productionize machine learning.

* [keras](https://keras.io/about/) - A deep learning API written in Python, which runs on top of the machine learning platform TensorFlow.

* [scikit-learn](https://scikit-learn.org/) - A Python machine learning library that provides supervised and unsupervised learning algorithms.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
pip install --upgrade tensorflow
pip install -U scikit-learn
python -c "import tensorflow as tf;print(tf.keras.__version__)"
```

---

## Usage

To use the venture funding application you must first launch Jupyter Lab by executing the following command within Git Bash:

```python
jupyter lab
```

Within Jupyter Lab you should then be able to run and execute the following notebook:

``` python
venture_funding_with_deep_learning.ipynb
```
---

## Contributors

Brought to you by [Drew Herrera](https://www.linkedin.com/in/drew94591).

---

## License

Licensed under the MIT License. Copyright 2022 Drew Herrera.


