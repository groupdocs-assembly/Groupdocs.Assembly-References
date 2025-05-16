---
title: JsonDataSource constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/jsondatasource/__init__/
is_root: false
weight: 10
---

## __init__ {#str}

Creates a new data source with data from a JSON file using default options for parsing JSON data.



```python
def __init__(self, json_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| json_path | str | The path to the JSON file to be used as the data source. |


## __init__ {#io.RawIOBase}

Creates a new data source with data from a JSON stream using default options for parsing JSON data.



```python
def __init__(self, json_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| json_stream | io.RawIOBase | The stream of JSON data to be used as the data source. |


## __init__ {#str-groupdocs.assembly.data.JsonDataLoadOptions}

Creates a new data source with data from a JSON file using the specified options for parsing JSON data.



```python
def __init__(self, json_path, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| json_path | str | The path to the JSON file to be used as the data source. |
| options | [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions) | Options for parsing JSON data. |


## __init__ {#io.RawIOBase-groupdocs.assembly.data.JsonDataLoadOptions}

Creates a new data source with data from a JSON stream using the specified options for parsing JSON data.



```python
def __init__(self, json_stream, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| json_stream | io.RawIOBase | The stream of JSON data to be used as the data source. |
| options | [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions) | Options for parsing JSON data. |



### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource)
