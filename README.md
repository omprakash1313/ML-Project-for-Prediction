# ML-Project-for-Prediction

Model Evaluation and Validation
Project: Predicting Boston Housing Prices
Install
This project requires Python and the following Python libraries installed:

import numpy as np  # fundamental package for scientific computation in python. provides multidimensional array object, including mathematical logic, shape amuplation 
 sorting selection i/o discrete fourier transoform , basics of linear algebra, basic statiscal operation , random simulation.
# installation --> pip install numpy
#import --> import numpy as np
import pandas as  pd  # important library for Data processing and data analysis. Helpful in datacleaning , restructing, merging etc. working with pandas is fasta 
provides the fast data processing as Numpy with flexible data mauplation techniques as spreedsheet and relational databases. It easily integrates with matplotlib
 most importantly it provides two very important data structures i.e Series and DataFrame.
 Series --> onedimensional array that can stores various types of data types, including mix data types. -- only one type of index --> row lables
 DataFrame --> widely used datastructure of pandas. it work with two dimesional arrays. -- two types of index--Column and row index
 installation --> pip install pandas
# import pandas as pd
import matplotlib.pyplot as plt  # it graphs the data on figure which can can have multiple Axes. Highlt used for data visulazation. it plots 2D plots from data in arrays.it uses numpy 
# for numerical mathematics.
Installation --> pip install matplotlib
# import -->import matplotlib as plt
import seaborn as sns # a data visualization library based on matplotlib. provides high-level of interface for drawing attarative and information statistcal graphics
 it help to explore and understand the data. It plotting functions operate on dataframes and arrays cointaining whole datasets amd internally perform the necessary 
 semantic mapping asn statiscal aggregation to produce informative plots. Provies High level of API for statical graphics.
# installation --> pip install seaborn
# import --> import seaborn as sns

from sklearn.metrics import confusion_matrix, accuracy_score, mean_absolute_error # it is a free software machine learning library for the python. 
 it include various classification, regression and clustering algorthm including Support-vector machine , random-forest, gradient boosting, K-means, DBSCAN
# installation --> pip install -U scikit-learn
# import --> import sklearn
from colorama import Fore, Back, Style  # it is a module to display the text in different colors. it is used to make the code for more readable. Thre formatting options are available
# front, back, style. 
# insatallation --> pip install colorma 
#import --> import colorma 
You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

Code
Template code is provided in the Heart_Failure_Death_Detection.ipynb notebook file . If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

Run
In a terminal or command window, navigate to the top-level project directory boston_housing/ (that contains this README) and run one of the following commands:

ipython notebook Heart_Failure_Death_Detection.ipynb
