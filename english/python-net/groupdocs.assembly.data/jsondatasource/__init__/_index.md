---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new data source with data from a JSON file using default parsing options."
type: docs
url: /python-net/groupdocs.assembly.data/jsondatasource/__init__/
is_root: false
weight: 10
---


## __init__ {#json_path}

Initializes a new data source with data from a JSON file using default parsing options.

```python
def __init__(self, json_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| json_path | `str` | The path to the JSON file to be used as the data source. |

### Example

```python
from groupdocs.assembly.data import JsonDataSource

json_data_source = JsonDataSource("staff-member.json")
```

## __init__ {#json_path-options}

Initializes a new data source with data from a JSON file using the specified options for parsing JSON data.

```python
def __init__(self, json_path, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| json_path | `str` | The path to the JSON file to be used as the data source. |
| options | `JsonDataLoadOptions` | Options for parsing JSON data. |

## __init__ {#json_stream}

Initializes a new data source with data from a JSON stream using default parsing options.

```python
def __init__(self, json_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| json_stream | `io.RawIOBase` | The stream of JSON data to be used as the data source. |

### Example

```python
import io
from groupdocs.assembly.data import JsonDataSource

json_array = """[
    { "name": "Amara Osei", "age": 41 },
    { "name": "Jonas Weber", "age": 37 },
    { "name": "Lena Park", "age": 29 }
]"""

json_data_source = JsonDataSource(io.BytesIO(json_array.encode("utf-8")))
```

## __init__ {#json_stream-options}

Initializes a new data source with data from a JSON stream using the specified options for parsing JSON data.

```python
def __init__(self, json_stream, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| json_stream | `io.RawIOBase` | The stream of JSON data to be used as the data source. |
| options | `JsonDataLoadOptions` | Options for parsing JSON data. |

### See Also
* class [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource/)
