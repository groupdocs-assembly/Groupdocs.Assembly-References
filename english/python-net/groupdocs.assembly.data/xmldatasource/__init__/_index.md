---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new data source with data from an XML file using default options for XML data loading."
type: docs
url: /python-net/groupdocs.assembly.data/xmldatasource/__init__/
is_root: false
weight: 10
---


## __init__ {#xml_path}

Initializes a new data source with data from an XML file using default options for XML data loading.

```python
def __init__(self, xml_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_path | `str` | The path to the XML file to be used as the data source. |

### Example

```python
from groupdocs.assembly.data import XmlDataSource

xml_data_source = XmlDataSource("staff-profile.xml")
```

## __init__ {#xml_stream}

Initializes a new data source with data from an XML stream using default options for XML data loading.

```python
def __init__(self, xml_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_stream | `io.RawIOBase` | The stream of XML data to be used as the data source. |

### Example

```python
import io
from groupdocs.assembly.data import XmlDataSource

xml_string = """<Person>
    <Name>Jonas Weber</Name>
    <Age>37</Age>
    <Birth>1988-07-04 2:00:00 pm</Birth>
    <Email>jonas.weber@harborlane.example</Email>
</Person>"""

xml_data_source = XmlDataSource(io.BytesIO(xml_string.encode("utf-8")))
```

## __init__ {#xml_path-xml_schema_path}

Initializes a new data source with data from an XML file using an XML Schema Definition file. Default options are used for XML data loading.

```python
def __init__(self, xml_path, xml_schema_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_path | `str` | The path to the XML file to be used as the data source. |
| xml_schema_path | `str` | The path to the XML Schema Definition file that provides schema for the XML file. |

## __init__ {#xml_stream-xml_schema_stream}

Initializes a new data source with data from an XML stream using an XML Schema Definition stream. Default options are used for XML data loading.

```python
def __init__(self, xml_stream, xml_schema_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_stream | `io.RawIOBase` | The stream of XML data to be used as the data source. |
| xml_schema_stream | `io.RawIOBase` | The stream of XML Schema Definition that provides schema for the XML data. |

## __init__ {#xml_path-options}

Initializes a new data source with data from an XML file using the specified options for XML data loading.

```python
def __init__(self, xml_path, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_path | `str` | The path to the XML file to be used as the data source. |
| options | `XmlDataLoadOptions` | Options for XML data loading. |

## __init__ {#xml_stream-options}

Initializes a new data source with data from an XML stream using the specified options for XML data loading.

```python
def __init__(self, xml_stream, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_stream | `io.RawIOBase` | The stream of XML data to be used as the data source. |
| options | `XmlDataLoadOptions` | Options for XML data loading. |

### Example

```python
    import io
    from groupdocs.assembly.data import XmlDataSource, XmlDataLoadOptions

    xml = """<root><item>Value</item></root>"""
    stream = io.BytesIO(xml.encode("utf-8"))
    load_options = XmlDataLoadOptions()  # configure as needed
    data_source = XmlDataSource(stream, load_options)
    ```

## __init__ {#xml_path-xml_schema_path-options}

Initializes a new data source with data from an XML file using an XML Schema Definition file.

```python
def __init__(self, xml_path, xml_schema_path, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_path | `str` | The path to the XML file to be used as the data source. |
| xml_schema_path | `str` | The path to the XML Schema Definition file that provides schema for the XML file. |
| options | `XmlDataLoadOptions` | Options for XML data loading. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler
from groupdocs.assembly.data import XmlDataSource

xml_data_source = XmlDataSource("staff-profile.xml", "staff-schema.xsd", None)

assembler = DocumentAssembler()
assembler.assemble_document(
    "staff-profile.docx",
    "staff-profile-report.docx",
    DataSourceInfo(xml_data_source, "data")
)
```

## __init__ {#xml_stream-xml_schema_stream-options}

Initializes a new data source with XML data from a stream and an optional XML Schema Definition stream, using the specified loading options.

```python
def __init__(self, xml_stream, xml_schema_stream, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| xml_stream | `io.RawIOBase` | The stream containing XML data to be used as the data source. |
| xml_schema_stream | `io.RawIOBase` | The stream containing an XML Schema Definition that provides a schema for the XML data. |
| options | `XmlDataLoadOptions` | Options for XML data loading. |

### Example

```python
import io
from groupdocs.assembly.data import XmlDataSource, XmlDataLoadOptions

xml_content = """<Person>
    <Name>Jonas Weber</Name>
    <Age>37</Age>
</Person>"""
xml_stream = io.BytesIO(xml_content.encode('utf-8'))

# Optional XSD schema stream
xsd_content = b"""<?xml version="1.0"?>
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:element name="Person">
    <xs:complexType>
      <xs:sequence>
        <xs:element name="Name" type="xs:string"/>
        <xs:element name="Age" type="xs:int"/>
      </xs:sequence>
    </xs:complexType>
  </xs:element>
</xs:schema>"""
schema_stream = io.BytesIO(xsd_content)

options = XmlDataLoadOptions()  # configure loading options as needed

data_source = XmlDataSource(xml_stream, schema_stream, options)
```

### See Also
* class [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource/)
