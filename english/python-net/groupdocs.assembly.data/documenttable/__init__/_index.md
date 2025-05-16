---
title: DocumentTable constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttable/__init__/
is_root: false
weight: 10
---

## __init__ {#str-int}

Creates a new instance of this class using default [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions).



```python
def __init__(self, document_path, index_in_document):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document_path | str | The path to a document containing the table to be accessed. |
| index_in_document | int | The zero-based index of the table in the document. |


## __init__ {#io.RawIOBase-int}

Creates a new instance of this class using default [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions).



```python
def __init__(self, document_stream, index_in_document):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document_stream | io.RawIOBase | The stream containing a document with the table to be accessed. |
| index_in_document | int | The zero-based index of the table in the document. |


## __init__ {#str-int-groupdocs.assembly.data.DocumentTableOptions}

Creates a new instance of this class.



```python
def __init__(self, document_path, index_in_document, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document_path | str | The path to a document containing the table to be accessed. |
| index_in_document | int | The zero-based index of the table in the document. |
| options | [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions) | A set of options controlling extraction of data from the table. If null, default options are applied. |


## __init__ {#io.RawIOBase-int-groupdocs.assembly.data.DocumentTableOptions}

Creates a new instance of this class.



```python
def __init__(self, document_stream, index_in_document, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document_stream | io.RawIOBase | The stream containing a document with the table to be accessed. |
| index_in_document | int | The zero-based index of the table in the document. |
| options | [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions) | A set of options controlling extraction of data from the table. If null, default options are applied. |



### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable)
* class [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions)
