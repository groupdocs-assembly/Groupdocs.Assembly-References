---
title: resource_load_base_uri property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The base URI used to resolve external resource files' relative URIs to absolute ones when loading an HTML template document to be assembled and saved to a non‑HTML format."
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/resource_load_base_uri/
is_root: false
weight: 2020
---


## resource_load_base_uri property

The base URI used to resolve external resource files' relative URIs to absolute ones when loading an HTML template document to be assembled and saved to a non‑HTML format. The default value is an empty string.

When loading an HTML document from a file, its containing folder is used as a base URI by default, which cannot happen when loading an HTML document from a stream. Set this property to specify a base URI when loading an HTML document from a stream or to override the default base URI when loading an HTML document from a file.

A value of this property is ignored in the following cases:
- An HTML document being loaded contains a BASE HTML element providing a base URI.
- An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

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
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/)
