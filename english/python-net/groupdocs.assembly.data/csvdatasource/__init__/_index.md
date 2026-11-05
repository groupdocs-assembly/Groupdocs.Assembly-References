---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new data source with data from a CSV file using default parsing options."
type: docs
url: /python-net/groupdocs.assembly.data/csvdatasource/__init__/
is_root: false
weight: 10
---


## __init__ {#csv_path}

Initializes a new data source with data from a CSV file using default parsing options.

```python
def __init__(self, csv_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| csv_path | `str` | The path to the CSV file to be used as the data source. |

## __init__ {#csv_path-options}

Initializes a new data source with data from a CSV file using the specified options for parsing CSV data.

```python
def __init__(self, csv_path, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| csv_path | `str` | The path to the CSV file to be used as the data source. |
| options | `CsvDataLoadOptions` | Options for parsing the CSV data. |

### Example

```python
from groupdocs.assembly.data import CsvDataSource, CsvDataLoadOptions

persons = CsvDataSource("persons.csv", CsvDataLoadOptions(True))
```

## __init__ {#csv_stream}

Initializes a new data source with data from a CSV stream using default parsing options.

```python
def __init__(self, csv_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| csv_stream | `io.RawIOBase` | The stream of CSV data to be used as the data source. |

## __init__ {#csv_stream-options}

Initializes a new data source with data from a CSV stream using the specified options for parsing CSV data.

```python
def __init__(self, csv_stream, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| csv_stream | `io.RawIOBase` | The stream of CSV data to be used as the data source. |
| options | `CsvDataLoadOptions` | Options for parsing the CSV data. |

### See Also
* class [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource/)
