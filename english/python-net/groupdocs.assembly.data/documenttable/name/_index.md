---
title: name property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The name of this table used to access the table's data in a template document passed to DocumentAssembler."
type: docs
url: /python-net/groupdocs.assembly.data/documenttable/name/
is_root: false
weight: 2030
---


## name property

The name of this table used to access the table's data in a template document passed to [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/).

If the table's name is read from a document, the name is automatically corrected so that it to be valid. However, if the table's name is set manually through this property and the name is invalid, an exception is thrown.

The table's name is considered to be valid if the following conditions are met:

- The name is not empty.
- The name's first character is a letter or underscore.
- The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
- The corresponding [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/) object does not contain a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/) instance with the same name.

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
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/)
