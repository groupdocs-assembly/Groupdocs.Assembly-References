---
title: XmlDataSource constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/xmldatasource/__init__/
is_root: false
weight: 10
---

## __init__ {#str}

Creates a new data source with data from an XML file using default options for XML data loading.



```python
def __init__(self, xml_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_path | str | The path to the XML file to be used as the data source. |


## __init__ {#io.RawIOBase}

Creates a new data source with data from an XML stream using default options for XML data loading.



```python
def __init__(self, xml_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_stream | io.RawIOBase | The stream of XML data to be used as the data source. |


## __init__ {#str-str}

Creates a new data source with data from an XML file using an XML Schema Definition file. Default options
are used for XML data loading.



```python
def __init__(self, xml_path, xml_schema_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_path | str | The path to the XML file to be used as the data source. |
| xml_schema_path | str | The path to the XML Schema Definition file that provides schema for the XML<br/>file. |


## __init__ {#io.RawIOBase-io.RawIOBase}

Creates a new data source with data from an XML stream using an XML Schema Definition stream. Default options
are used for XML data loading.



```python
def __init__(self, xml_stream, xml_schema_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_stream | io.RawIOBase | The stream of XML data to be used as the data source. |
| xml_schema_stream | io.RawIOBase | The stream of XML Schema Definition that provides schema for the XML data. |


## __init__ {#str-groupdocs.assembly.data.XmlDataLoadOptions}

Creates a new data source with data from an XML file using the specified options for XML data loading.



```python
def __init__(self, xml_path, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_path | str | The path to the XML file to be used as the data source. |
| options | [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions) | Options for XML data loading. |


## __init__ {#io.RawIOBase-groupdocs.assembly.data.XmlDataLoadOptions}

Creates a new data source with data from an XML stream using the specified options for XML data loading.



```python
def __init__(self, xml_stream, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_stream | io.RawIOBase | The stream of XML data to be used as the data source. |
| options | [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions) | Options for XML data loading. |


## __init__ {#str-str-groupdocs.assembly.data.XmlDataLoadOptions}

Creates a new data source with data from an XML file using an XML Schema Definition file. The specified
options are used for XML data loading.



```python
def __init__(self, xml_path, xml_schema_path, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_path | str | The path to the XML file to be used as the data source. |
| xml_schema_path | str | The path to the XML Schema Definition file that provides schema for the XML<br/>file. |
| options | [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions) | Options for XML data loading. |


## __init__ {#io.RawIOBase-io.RawIOBase-groupdocs.assembly.data.XmlDataLoadOptions}

Creates a new data source with data from an XML stream using an XML Schema Definition stream. The specified
options are used for XML data loading.



```python
def __init__(self, xml_stream, xml_schema_stream, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_stream | io.RawIOBase | The stream of XML data to be used as the data source. |
| xml_schema_stream | io.RawIOBase | The stream of XML Schema Definition that provides schema for the XML data. |
| options | [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions) | Options for XML data loading. |



### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource)
