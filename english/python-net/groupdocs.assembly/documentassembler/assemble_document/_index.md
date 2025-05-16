---
title: assemble_document method
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/documentassembler/assemble_document/
is_root: false
weight: 20
---

## assemble_document {#str-str-list}

Loads a template document from the specified source path, populates the template document with data from 
the specified single or multiple sources, and stores the result document to the target path using default
[`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions).


### Returns 


A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if 
a value of the [`DocumentAssembler.options`](/assembly/python-net/groupdocs.assembly/documentassembler#options) property includes the [`DocumentAssemblyOptions.INLINE_ERROR_MESSAGES`](/assembly/python-net/groupdocs.assembly/documentassemblyoptions#INLINE_ERROR_MESSAGES)
option.


```python
def assemble_document(self, source_path, target_path, data_source_infos):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_path | str | The path to a template document to be populated with data. |
| target_path | str | The path to a result document. |
| data_source_infos | list | Provides information on data source objects to be used. |


## assemble_document {#io.RawIOBase-io.RawIOBase-list}

Loads a template document from the specified source stream, populates the template document with data from 
the specified single or multiple sources, and stores the result document to the target stream using default
[`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions).


### Returns 


A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if 
a value of the [`DocumentAssembler.options`](/assembly/python-net/groupdocs.assembly/documentassembler#options) property includes the [`DocumentAssemblyOptions.INLINE_ERROR_MESSAGES`](/assembly/python-net/groupdocs.assembly/documentassemblyoptions#INLINE_ERROR_MESSAGES)
option.


```python
def assemble_document(self, source_stream, target_stream, data_source_infos):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_stream | io.RawIOBase | The stream to read a template document from. |
| target_stream | io.RawIOBase | The stream to write a result document. |
| data_source_infos | list | Provides information on data source objects to be used. |


## assemble_document {#str-str-groupdocs.assembly.LoadSaveOptions-list}

Loads a template document from the specified source path, populates the template document with data from 
the specified single or multiple sources, and stores the result document to the target path using the given
[`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions).


### Returns 


A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if 
a value of the [`DocumentAssembler.options`](/assembly/python-net/groupdocs.assembly/documentassembler#options) property includes the [`DocumentAssemblyOptions.INLINE_ERROR_MESSAGES`](/assembly/python-net/groupdocs.assembly/documentassemblyoptions#INLINE_ERROR_MESSAGES)
option.


```python
def assemble_document(self, source_path, target_path, load_save_options, data_source_infos):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_path | str | The path to a template document to be populated with data. |
| target_path | str | The path to a result document. |
| load_save_options | [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions) | Specifies additional options for document loading and saving. |
| data_source_infos | list | Provides information on data source objects to be used. |


## assemble_document {#io.RawIOBase-io.RawIOBase-groupdocs.assembly.LoadSaveOptions-list}

Loads a template document from the specified source stream, populates the template document with data from 
the specified single or multiple sources, and stores the result document to the target stream using the given
[`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions).


### Returns 


A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if 
a value of the [`DocumentAssembler.options`](/assembly/python-net/groupdocs.assembly/documentassembler#options) property includes the [`DocumentAssemblyOptions.INLINE_ERROR_MESSAGES`](/assembly/python-net/groupdocs.assembly/documentassemblyoptions#INLINE_ERROR_MESSAGES)
option.


```python
def assemble_document(self, source_stream, target_stream, load_save_options, data_source_infos):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_stream | io.RawIOBase | The stream to read a template document from. |
| target_stream | io.RawIOBase | The stream to write a result document. |
| load_save_options | [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions) | Specifies additional options for document loading and saving. |
| data_source_infos | list | Provides information on data source objects to be used. |



### See Also
* module [`groupdocs.assembly`](../../)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions)
