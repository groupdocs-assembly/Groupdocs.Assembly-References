---
title: always_generate_root_object property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/xmldataloadoptions/always_generate_root_object/
is_root: false
weight: 30
---

## always_generate_root_object property


Gets or sets a flag indicating whether a generated data source will always contain an object for an XML root 
element. If an XML root element has no attributes and all its child elements have same names, such an object 
is not created by default.

### Remarks 


The default value is **false** .
### Definition:
```python
@property
def always_generate_root_object(self):
    ...
@always_generate_root_object.setter
def always_generate_root_object(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions)
