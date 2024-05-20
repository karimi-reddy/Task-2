# Task-2
import pandas as pd
file_path = 'your_dataset.csv'
df = pd.read_csv('C:\\Users\\rgukt\\Desktop\\01.Data Cleaning and Preprocessing.CSV')
type(df)
df.info()
df.describe()
print(df.head())
df_n_d = df.drop_duplicates()
print(df_n_d )
print(df_n_d.isnull())
print(df_n_d.isnull().sum())
print(df_n_d.isnull().sum().sum())
df_n_d_f= df_n_d.fillna(0)
print(df_n_d_f)
print(df_n_d_f.isnull().sum())
print(df_n_d_f.describe())
