---
title: LoadSaveOptions class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/
is_root: false
weight: 60
---

## LoadSaveOptions class

Specifies additional options for loading and saving of a document to be assembled.



The LoadSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly/loadsaveoptions/__init__/#) | Creates a new instance of this class without any properties specified. |
| [__init__](/assembly/python-net/groupdocs.assembly/loadsaveoptions/__init__/#groupdocs.assembly.FileFormat) | Creates a new instance of this class with the specified file format to save an assembled document to. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/assembly/python-net/groupdocs.assembly/loadsaveoptions/save_format) | Gets or sets a file format to save an assembled document to. [`FileFormat.UNSPECIFIED`](/assembly/python-net/groupdocs.assembly/fileformat#UNSPECIFIED) is the default. |
| [resource_load_base_uri](/assembly/python-net/groupdocs.assembly/loadsaveoptions/resource_load_base_uri) | Gets or sets a base URI to resolve external resource files' relative URIs to absolute ones while loading an HTML <br/>template document to be assembled and saved to a non-HTML format. The default value is an empty string. |
| [resource_save_folder](/assembly/python-net/groupdocs.assembly/loadsaveoptions/resource_save_folder) | Gets or sets a path to a folder to store external resource files while an assembled document loaded from a non-HTML <br/>format is being saved to HTML. The default value is an empty string. |



### See Also
* module [`groupdocs.assembly`](..)
