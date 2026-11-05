---
title: name property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The name of the data source object used to access it in a template document."
type: docs
url: /python-net/groupdocs.assembly/datasourceinfo/name/
is_root: false
weight: 2020
---


## name property

The name of the data source object used to access it in a template document.

When the name of the data source object is specified, you can access the data source object and its members in a template document using the name.

When the name of the data source object is None or empty, you can still access members of the data source object in a template document using context object member access (see Template Syntax Reference for more information), but you cannot access the data source object itself.

When passing multiple [`DataSourceInfo`](/assembly/python-net/groupdocs.assembly/datasourceinfo/) instances to [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/), only the name of the first data source object can be None or empty. Names of the remaining instances must be specified and unique.

### Definition:
```python
@property
def name(self):
    ...
@name.setter
def name(self, value):
    ...
```

### See Also
* class [`DataSourceInfo`](/assembly/python-net/groupdocs.assembly/datasourceinfo/)
