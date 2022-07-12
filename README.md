# SuicideWatch
Multinomial Model to detect suicidal ideation 

Received data from [Kaggle: Suicide and Depression Detection](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch). The file was modified to have ';' as seperator. 
```
>>> python
>>> import pandas as pd
>>> sets = pd.read_csv('Suicide_Detection.csv', header=0)
>>> sets.to_csv('saved.csv', sep=';')
```
