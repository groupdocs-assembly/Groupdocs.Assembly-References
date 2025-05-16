---
title: resource_load_base_uri property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/resource_load_base_uri/
is_root: false
weight: 30
---

## resource_load_base_uri property


Gets or sets a base URI to resolve external resource files' relative URIs to absolute ones while loading an HTML 
template document to be assembled and saved to a non-HTML format. The default value is an empty string.

### Remarks 


When loading an HTML document from a file, its containing folder is used as a base URI by default, which cannot 
happen when loading an HTML document from a stream. Set this property to specify a base URI when loading an HTML 
document from a stream or to override the default base URI when loading an HTML document from a file.




A value of this property is ignored in the following cases:


|
|
 |
 |
### Definition:
```python
@property
def resource_load_base_uri(self):
    ...
@resource_load_base_uri.setter
def resource_load_base_uri(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly`](../../)
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions)
