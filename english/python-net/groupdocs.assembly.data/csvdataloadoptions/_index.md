---
title: CsvDataLoadOptions class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Represents options for parsing CSV data."
type: docs
url: /python-net/groupdocs.assembly.data/csvdataloadoptions/
is_root: false
weight: 10
---


## CsvDataLoadOptions class

Represents options for parsing CSV data.

An instance of this class can be passed into constructors of [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource/).

The CsvDataLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions/__init__/) | Initializes a new instance of this class with default options. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions/__init__/#has_headers) | Initializes a new instance of this class with specifying whether CSV data contains column names at the first line. |

### Properties
| Property | Description |
| :- | :- |
| [comment_char](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions/comment_char/) | The character used to comment lines of CSV data. |
| [delimiter](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions/delimiter/) | The character used as a column delimiter. |
| [has_headers](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions/has_headers/) | The property indicating whether the first line of CSV data contains column names. |
| [quote_char](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions/quote_char/) | The character used to quote field values. |

### Example

```python
from groupdocs.assembly.data import CsvDataLoadOptions, CsvDataSource

options = CsvDataLoadOptions(True)  # first line contains column names
data_source = CsvDataSource("persons.csv", options)
```

### Guides
Task guides that use `CsvDataLoadOptions`:

* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)

### See Also
* module [`groupdocs.assembly.data`](/assembly/python-net/groupdocs.assembly.data/)
