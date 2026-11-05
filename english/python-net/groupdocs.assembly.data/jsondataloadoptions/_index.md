---
title: JsonDataLoadOptions class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Represents options for parsing JSON data."
type: docs
url: /python-net/groupdocs.assembly.data/jsondataloadoptions/
is_root: false
weight: 130
---


## JsonDataLoadOptions class

Represents options for parsing JSON data.

An instance of this class can be passed into constructors of [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource/).

The JsonDataLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/__init__/) | Initializes a new instance of this class with default options. |

### Properties
| Property | Description |
| :- | :- |
| [always_generate_root_object](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/always_generate_root_object/) | The flag indicating whether a generated data source will always contain an object for a JSON root element; if the root element contains a single complex property, such an object is not created by default. |
| [exact_date_time_parse_format](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_format/) | The exact format for parsing JSON date-time values while loading JSON. The default is None. |
| [exact_date_time_parse_formats](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_formats/) | The exact formats for parsing JSON date-time values while loading JSON. The default is None. |
| [simple_value_parse_mode](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/simple_value_parse_mode/) | The mode used for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. This mode does not affect parsing of date-time values. The default is `JsonSimpleValueParseMode.loose`. |

### Example

```python
from groupdocs.assembly.data import JsonDataLoadOptions, JsonDataSource, JsonSimpleValueParseMode

options = JsonDataLoadOptions()
options.always_generate_root_object = True
options.simple_value_parse_mode = JsonSimpleValueParseMode.STRICT

json_source = JsonDataSource("trade-accounts.json", options)
```

### Guides
Task guides that use `JsonDataLoadOptions`:

* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)

### See Also
* module [`groupdocs.assembly.data`](/assembly/python-net/groupdocs.assembly.data/)
