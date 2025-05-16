---
title: DocumentTableSet constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttableset/__init__/
is_root: false
weight: 10
---

## __init__ {#str}

Creates a new instance of this class loading all tables from a document using default 
[`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions).



```python
def __init__(self, document_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document_path | str | The path to a document containing tables to be accessed. |


## __init__ {#io.RawIOBase}

Creates a new instance of this class loading all tables from a document using default 
[`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions).



```python
def __init__(self, document_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document_stream | io.RawIOBase | The stream containing a document with tables to be accessed. |


## __init__ {#str-groupdocs.assembly.data.IDocumentTableLoadHandler}

Creates a new instance of this class.



```python
def __init__(self, document_path, load_handler):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document_path | str | The path to a document containing tables to be accessed. |
| load_handler | [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler) | An [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler) implementation controlling how document tables are loaded. |


## __init__ {#io.RawIOBase-groupdocs.assembly.data.IDocumentTableLoadHandler}

Creates a new instance of this class.



```python
def __init__(self, document_stream, load_handler):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document_stream | io.RawIOBase | The stream containing a document with tables to be accessed. |
| load_handler | [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler) | An [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler) implementation controlling how document tables are loaded. |



### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions)
* class [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset)
* class [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler)
