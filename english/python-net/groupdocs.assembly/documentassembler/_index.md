---
title: DocumentAssembler class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/documentassembler/
is_root: false
weight: 30
---

## DocumentAssembler class

Provides routines to populate template documents with data and a set of settings to control these routines.



The DocumentAssembler type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly/documentassembler/__init__/#) | Initializes a new instance of this class. |


### Properties
| Property | Description |
| :- | :- |
| [options](/assembly/python-net/groupdocs.assembly/documentassembler/options) | Gets or sets a set of flags controlling behavior of this [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler) instance <br/>while assembling a document. |
| [barcode_settings](/assembly/python-net/groupdocs.assembly/documentassembler/barcode_settings) | Gets a set of settings controlling barcode generation while assembling a document. |
| [known_types](/assembly/python-net/groupdocs.assembly/documentassembler/known_types) | Gets an unordered set (that is, a collection of unique items) containing Type objects <br/>which fully or partially qualified names can be used within document templates processed by this <br/>assembler instance to invoke the corresponding types' static members, perform type casts, etc. |
| [use_reflection_optimization](/assembly/python-net/groupdocs.assembly/documentassembler/use_reflection_optimization) | Gets or sets a value indicating whether invocations of custom type members performed via reflection API are <br/>optimized using dynamic class generation or not. The default value is true. |


### Methods
| Method | Description |
| :- | :- |
| [assemble_document](/assembly/python-net/groupdocs.assembly/documentassembler/assemble_document/#str-str-list) | Loads a template document from the specified source path, populates the template document with data from <br/>the specified single or multiple sources, and stores the result document to the target path using default<br/>[`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions). |
| [assemble_document](/assembly/python-net/groupdocs.assembly/documentassembler/assemble_document/#str-str-groupdocs.assembly.LoadSaveOptions-list) | Loads a template document from the specified source path, populates the template document with data from <br/>the specified single or multiple sources, and stores the result document to the target path using the given<br/>[`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions). |
| [assemble_document](/assembly/python-net/groupdocs.assembly/documentassembler/assemble_document/#io.RawIOBase-io.RawIOBase-list) | Loads a template document from the specified source stream, populates the template document with data from <br/>the specified single or multiple sources, and stores the result document to the target stream using default<br/>[`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions). |
| [assemble_document](/assembly/python-net/groupdocs.assembly/documentassembler/assemble_document/#io.RawIOBase-io.RawIOBase-groupdocs.assembly.LoadSaveOptions-list) | Loads a template document from the specified source stream, populates the template document with data from <br/>the specified single or multiple sources, and stores the result document to the target stream using the given<br/>[`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions). |



### See Also
* module [`groupdocs.assembly`](..)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions)
