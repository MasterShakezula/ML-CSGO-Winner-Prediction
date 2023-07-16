# ML-CSGO-Winner-Prediction
ML project done in Jupyter Notebook to process Counter-Strike: Global Offensive data and determine the winner.
Initial datasets are picks.csv, results.csv, economy.csv, and players.csv. 
Other .csv files were generated during runtime for easier use, but the only .csv files that must be included prior to execution are picks.csv, results.csv, economy.csv, and players.csv. 
Necessary imports are listed below. For simplicity, I imported these packages at the very beginning of the program. 
You will need these data science stack(s) and packages installed on your computer, as well as Python and Anaconda.
It is important to note that for this iteration of my model, I focused only on results.csv to relimit the scope of this project. However, the other initial csv files are still avaliable for use. 

import numpy as np (useful for data transformation and complex array operations)
import pandas as pd (pandas is especially important for manipulating data in the form of CSVs and dataframes for easy processing)

(These four imports below are important for data visualization and graphical information)
import plotly.graph_objects as go 
import plotly.express as px
import matplotlib.pyplot as plt
import seaborn as sns


(facilitate a system to train our model of choice and test give it a set of data to test and predict an output based on what it was trained on)
from sklearn.model_selection import train_test_split

(can scale data that may be skewed for additional preprocessing)
from sklearn.preprocessing import StandardScaler 

(import a RandomForestClassifier to use as our model)
from sklearn.ensemble import RandomForestClassifier


#Installation tips



Python: https://www.python.org/downloads/release/python-3114/

Anaconda: https://www.anaconda.com/

When installing Anaconda, you may install Juypter Notebook alongside it. Juypter Notebook is not only way to run the code within this project, but it is how I personally ran it. If desired, https://www.kaggle.com/ is a quick and easy alternative to running the code.

#How to run

If using Kaggle, just copy each cell of code from this project and run it inside a new Notebook in Kaggle (be sure to import picks.csv, results.csv, economy.csv, and players.csv. as datasets first).

If using Juypter, be sure Python is installed. Then navigate to your command prompt and run:  pip install pandas numpy matplotlib seaborn scikit-learn 

Proceed with installation until Juypter is set up. Open Juypter Notebook and you will be taken to a web browser tab with the Juypter interface.

Make an empty notebook wherever (or, simply import the notebook within this project into yours).
Then, run each cell of the project code one by one until you have executed the last cell (at this point, you will have gotten the score of the model).
Remember to include picks.csv, results.csv, economy.csv, and players.csv in the same location your notebook is in. 
This project's raw code will also be available in a pdf format.

