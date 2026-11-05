---
title: exact_date_time_parse_formats property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The exact formats for parsing JSON date-time values while loading JSON."
type: docs
url: /python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_formats/
is_root: false
weight: 2030
---


## exact_date_time_parse_formats property

The exact formats for parsing JSON date-time values while loading JSON. The default is None.

Strings encoded using Microsoft® JSON date-time format (e.g., "/Date(1224043200000)/") are always recognized as date-time values regardless of the value of this property. The property defines additional formats to be used while parsing date-time values from strings in the following way:

- When [`JsonDataLoadOptions.exact_date_time_parse_formats`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_formats/) is None, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
- When it contains strings, they are used as additional date-time formats utilizing the current culture.
- When it is empty, no additional date-time formats are used.

### Definition:
```python
@property
def exact_date_time_parse_formats(self):
    ...
@exact_date_time_parse_formats.setter
def exact_date_time_parse_formats(self, value):
    ...
```

### See Also
* class [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/)
