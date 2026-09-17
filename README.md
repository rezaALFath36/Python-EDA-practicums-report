# **EDA PRACTICUMS REPORT**  
## Implementing Data Analysis with NumPy and Pandas
Source DataSet:
*data_kantin.csv*

## NUMPY / Latihan 1 and Latihan 2 (Numerical Python) 
Python library to operate a calculate task for array  
Including:  
-np.mean  
-np.median  
-np.min / np.max  

## PANDAS / Latihan 3 until Latihan 6  
Main tool in EDA for processing dataset sucs as spreadsheet or excel  
Including:  
### Data Loading  
Latihan 3  
import pandas as pd  
df = pd.read_csv('data_kantin.csv')  

### Data Inspection  
Latihan 3  
print(df.head())  
print(df.info())  
print(df.describe())  
print(df.shape)  

### Data Cleaning  
Latihan 4 and Latihan 5  
df.fillna  
df.drop  
df.duplicated  


### Data Manipulaton  
Latihan 6  
df.sort_values  
df.groupby  
