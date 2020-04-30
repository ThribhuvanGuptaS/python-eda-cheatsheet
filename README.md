# Python - Exploratory Data Analysis CheatSheet

## Reading a file
Use _header=None_ when the columns are not labeled in your csv file
### CSV file
```python
df = pd.read_csv("pathToFile.csv", header=None)
```
### Excel(.xlsx) file
```python
df = pd.read_excel("pathToFile.xlsx", header=None)
```
## Show first 5 rows of a DataFrame
```python 
df.head()
```
## Show last 5 rows of a DataFrame
```python
df.tail()
```
## Show all column names in the DataFrame
```python
df.columns
```
## Count occurances of all unique values in a column
```python
df['column_name'].value_counts()
```













