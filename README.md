# corona-virus-dataset
 data analysis with python code
import pandas as pd
import numpy as np

df1 = pd.read_csv("total_cases.csv",encoding='utf8')
df1.head()
df1.columns
df1.columns= df.columns.str.upper()
df1.rename(columns={'DURATION':'TIME'})
df.isnull().sum()int
df.isnull().any()bool
df.isnull().any()
df.isnull().any().any()
df.isnull().sum()
df.isnull().sum.sum()
df_with_0=df.fillna(0)
df_with_0.head()
df['DURATION'].mean()
df_with_mean = df.DURATION.fillna(df['DURATION'].mean())
df.head()
df.isnull().sum().sum()
df.shape
df_drop = df.dropna()
df_drop.shape
df_drop
df_with_condition = df.dropna(how='any')

