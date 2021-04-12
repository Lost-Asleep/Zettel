# Random Pandas Notes

More info in the [\<Official Documentation\>](https://pandas.pydata.org/docs/).

### Read and write from .csv files

```python
data = pandas.read_csv("path_to_csv_file")

some_other_data.to_csv("path_to_new_csv_file")
```

### Create a list from one column of a dataframe

```python
# data is a dataframe, column_name is the name of a column.
new_list = data.column_name.to_list()
```

## Connections

[Python Programing Language Index](../zettel/000E--python-lang-index.md)
