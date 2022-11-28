# Covid-Analysis-Python-File

# -*- coding: utf-8 -*-
"""
Created on Thu Oct  6 21:47:22 2022

@author: zachm
"""
import pandas as pd
import numpy as np
x = pd.read_csv("C:/Research/data analytics/Research Projects/Covid project/deathratecalculation.csv")
x.head()
x.info()
deathmean = np.mean(x)
stddeathmean = np.std(x)
print("Avg Death Rate:", deathmean*100)
print("std_deviation:", stddeathmean*100)
