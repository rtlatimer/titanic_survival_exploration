# Machine Learning Engineer Nanodegree
# Introduction and Foundations
### Project: Titanic Survival Exploration
by Robert Latimer
July 25, 2017

### Description

The goal of this project is to learn the fundamentals of Pandas, Numpy, Scikit-Learn, and matplotlib while exploring Titanic passenger data. In this project we will investigate data on Titanic passengers and try to build an algorithm that can accurately predict whether a passenger lived or died.

See full detail of the project [here](https://github.com/rtlatimer/titanic_survival_exploration/blob/master/titanic_survival_exploration.ipynb).

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

### Code

All original code was completed in the `titanic_survival_exploration.ipynb` file. Additional supporting code can be found in `visuals.py`.

### Run

In a terminal or command window, navigate to the top-level project directory `titanic_survival_exploration/` (that contains this README) and run one of the following commands:

```
jupyter notebook titanic_survival_exploration.ipynb
```
or
```
ipython notebook titanic_survival_exploration.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser.

### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)