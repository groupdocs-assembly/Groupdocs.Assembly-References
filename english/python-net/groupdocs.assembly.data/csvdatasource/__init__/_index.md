---
title: CsvDataSource constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/csvdatasource/__init__/
is_root: false
weight: 10
---

## __init__ {#str}

Creates a new data source with data from a CSV file using default options for parsing CSV data.



```python
def __init__(self, csv_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| csv_path | str | The path to the CSV file to be used as the data source. |


## __init__ {#io.RawIOBase}

Creates a new data source with data from a CSV stream using default options for parsing CSV data.



```python
def __init__(self, csv_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| csv_stream | io.RawIOBase | The stream of CSV data to be used as the data source. |


## __init__ {#str-groupdocs.assembly.data.CsvDataLoadOptions}

Creates a new data source with data from a CSV file using the specified options for parsing CSV data.



```python
def __init__(self, csv_path, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| csv_path | str | The path to the CSV file to be used as the data source. |
| options | [`CsvDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions) | Options for parsing the CSV data. |


## __init__ {#io.RawIOBase-groupdocs.assembly.data.CsvDataLoadOptions}

Creates a new data source with data from a CSV stream using the specified options for parsing CSV data.



```python
def __init__(self, csv_stream, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| csv_stream | io.RawIOBase | The stream of CSV data to be used as the data source. |
| options | [`CsvDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions) | Options for parsing the CSV data. |



### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource)
