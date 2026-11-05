---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new instance of this class with default options."
type: docs
url: /python-net/groupdocs.assembly.data/csvdataloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of this class with default options.

```python
def __init__(self):
    ...
```

## __init__ {#has_headers}

Initializes a new instance of this class with specifying whether CSV data contains column names at the first line.

```python
def __init__(self, has_headers):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| has_headers | `bool` |  |

### Example

```python
from groupdocs.assembly.data import CsvDataLoadOptions, CsvDataSource

options = CsvDataLoadOptions(True)  # first line contains column names
source = CsvDataSource("persons.csv", options)
```

### See Also
* class [`CsvDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions/)
