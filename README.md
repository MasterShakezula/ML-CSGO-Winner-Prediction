# ML-CSGO-Winner-Prediction
ML project done in Jupyter Notebook to process Counter-Strike: Global Offensive data and determine the winner.
Initial datasets are picks.csv, results.csv, economy.csv, and players.csv. 
Other .csv files were generated during runtime for easier use, but the only .csv files that must be included prior to execution are picks.csv, results.csv, economy.csv, and players.csv. 
Necessary imports are listed below. For simplicity, I imported these packages at the very beginning of the program. 
import numpy as np
import pandas as pd
import plotly.graph_objects as go
import plotly.express as px
import requests
import matplotlib.pyplot as plt
import seaborn as sns
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler 
from sklearn.ensemble import RandomForestClassifier


#Installation tips

You will need data science stack(s) and packages installed on your computer, as well as Python and Anaconda.
Python: https://www.python.org/downloads/release/python-3114/
Anaconda: https://www.anaconda.com/
When installing Anaconda, you may install Juypter Notebook alongside it. 
