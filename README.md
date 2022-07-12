# SuicideWatch
Multinomial Model to detect suicidal ideation 

Received data from [Kaggle: Suicide and Depression Detection](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch). The file was modified to have ';' as seperator. 
```
>>> import pandas as pd
>>> sets = pd.read_csv('Suicide_Detection.csv', header=0)
>>> sets.to_csv('saved.csv', sep=';')
```
This allowed the model to ignore blank lines and quotes that were interferring with file reading. 

To test the model, changing the sentence at NewSen and calling predict gives the results.
