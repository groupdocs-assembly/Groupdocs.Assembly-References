---
title: exact_date_time_parse_formats property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_formats/
is_root: false
weight: 50
---

## exact_date_time_parse_formats property


Gets or sets exact formats for parsing JSON date-time values while loading JSON. The default is **null** .

### Remarks 


Strings encoded using Microsoft® JSON date-time format (for example, "/Date(1224043200000)/") are always 
recognized as date-time values regardless of a value of this property. The property defines additional 
formats to be used while parsing date-time values from strings in the following way:


|
|
 |
 |
 |
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
* module [`groupdocs.assembly.data`](../../)
* class [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions)
