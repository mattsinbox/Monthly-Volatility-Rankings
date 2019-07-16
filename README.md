# Monthly-Volatility-Rankings

## Introduction:
Monthly Volatility Ranking is a Jupyter notebook written in python that ultimately tranforms and analyzes daily market data
with respect to it's monthly volatility.  It compares the average daily movement, ranking and analyzing them by month to find statistically meaningful relationships.  The code references the file SP which is a csv file containing the date, open, high, low, close, adjusted close and volume for the S&P 500 from January 1989 to December 2018.  The csv file was downloaded from Yahoo Finaance but any csv file with the date and closing price could be substituted.  

## Motivation:
Many market forecasters and pundits will reference certain months or seasons with respect to their volatilities without any data to 
substantiate their claims.  I wanted to create a program that could take a csv file with basic daily market information, Open, High, Low,
Change etc....and transform it to a dataframe which ranks the month by it's volatility within a given year and for a 
user defined time frame.  After transformation, users could use the dataframe to 
run visuals, perform statistical operations and feed the rankings into a machine learning algorithm.  This notebook could be 
used to analyze and transform daily data from a variety of markets to help determine seasonality.    

## Install:
import pandas as pd
import numpy as np

from IPython.display import display # Allows the use of display() for DataFrames
Pretty display for notebooks: %matplotlib inline
import matplotlib.pyplot as plt

## Contributing:
Monthly-Volatility-Rankings was originally written by Matthew Aronowitz.  I intend on improving this software to further enhance 
the automation of the transfomation, visualizations and analysis.  

## Monthly-Volatility-Rankings is Copyright © 20019 Matthew Aronowitz. 
It is free software, and may be redistributed under the terms specified in the:
[LICENSE](https://choosealicense.com/licenses/mit/#) file.


