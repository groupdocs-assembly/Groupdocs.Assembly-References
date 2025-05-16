---
title: resource_save_folder property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/resource_save_folder/
is_root: false
weight: 40
---

## resource_save_folder property


Gets or sets a path to a folder to store external resource files while an assembled document loaded from a non-HTML 
format is being saved to HTML. The default value is an empty string.

### Remarks 


By default, when saving an assembled document to an HTML file, external resource files are stored to a folder
having the same name as the HTML file without extension plus the "_files" suffix. This folder is located in
the same folder as the HTML file. However, this cannot be done when saving an assembled document to an HTML stream.
Set this property to specify a path to a folder to store external resource files when saving an assembled document
to an HTML stream or to override the default folder when saving an assembled document to an HTML file.




A value of this property is ignored if an assembled document being saved to HTML was loaded from HTML as well
(external resource files are not stored and links to them are not changed then).
### Definition:
```python
@property
def resource_save_folder(self):
    ...
@resource_save_folder.setter
def resource_save_folder(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly`](../../)
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions)
