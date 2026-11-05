---
title: exact_date_time_parse_format property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The exact format for parsing JSON date-time values while loading JSON."
type: docs
url: /python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_format/
is_root: false
weight: 2020
---


## exact_date_time_parse_format property

The exact format for parsing JSON date-time values while loading JSON. The default is None.

Strings encoded using Microsoft® JSON date-time format (for example, `"/Date(1224043200000)/"`) are always recognized as date-time values regardless of the value of this property. The property defines additional formats to be used while parsing date-time values from strings in the following way:

- When [`JsonDataLoadOptions.exact_date_time_parse_format`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_format/) is None, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
- When [`JsonDataLoadOptions.exact_date_time_parse_format`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_format/) is a non-empty string, it is used as a single additional date-time format utilizing the current culture.
- When [`JsonDataLoadOptions.exact_date_time_parse_format`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_format/) is an empty string, no additional date-time formats are used.

### Definition:
```python
@property
def exact_date_time_parse_format(self):
    ...
@exact_date_time_parse_format.setter
def exact_date_time_parse_format(self, value):
    ...
```

### See Also
* class [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/)
