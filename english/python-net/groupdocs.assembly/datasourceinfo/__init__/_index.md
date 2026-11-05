---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new DataSourceInfo instance with no properties set."
type: docs
url: /python-net/groupdocs.assembly/datasourceinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new DataSourceInfo instance with no properties set.

```python
def __init__(self):
    ...
```

## __init__ {#data_source}

Initializes a new instance of this class with the specified data source object.

The data source object can be one of the following types:

- [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource/)
- [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource/)
- [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource/)
- [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/)
- [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/)
- `System.Data.DataSet`
- `System.Data.DataTable`
- `System.Data.DataRow`
- `System.Data.IDataReader`
- `System.Data.IDataRecord`
- `System.Data.DataView`
- `System.Data.DataRowView`
- Any other arbitrary non-dynamic and non-anonymous .NET type

For information on how to work with data sources of different types in template documents, see the template syntax reference: https://docs.groupdocs.com/assembly/python-net/template-syntax-part-1-of-2/

```python
def __init__(self, data_source):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| data_source | `Any` | The data source object. |

## __init__ {#data_source-name}

Initializes a new instance of this class with the data source object and its name specified.

The data source object can be of one of the following types:

- [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource/)
- [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource/)
- [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource/)
- [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/)
- [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/)
- `System.Data.DataSet`
- `System.Data.DataTable`
- `System.Data.DataRow`
- `System.Data.IDataReader`
- `System.Data.IDataRecord`
- `System.Data.DataView`
- `System.Data.DataRowView`
- Any other arbitrary non-dynamic and non-anonymous .NET type

For information on how to work with data sources of different types in template documents, see template syntax reference (https://docs.groupdocs.com/assembly/python-net/template-syntax-part-1-of-2/).

When the name of the data source object is specified, you can access the data source object and its members in a template document using the name.

When the name of the data source object is null or empty, you can still access members of the data source object in a template document using context object member access (see Template Syntax Reference for more information), but you cannot access the data source object itself.

When passing multiple [`DataSourceInfo`](/assembly/python-net/groupdocs.assembly/datasourceinfo/) instances to [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/), only the name of the first data source object can be null or empty. Names of the rest ones must be specified and unique.

```python
def __init__(self, data_source, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| data_source | `Any` | The data source object. |
| name | `str` | The name of the data source object to be used to access the data source object in a template document. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler

assembler = DocumentAssembler()
assembler.assemble_document(
    "inserting-hyperlink.msg",
    "inserting-hyperlink-report.msg",
    [
        DataSourceInfo("https://harborlane.example/", "uriExpression"),
        DataSourceInfo("Harbor Lane Provisions", "displayTextExpression"),
        DataSourceInfo("Harbor Lane Provisions <orders@harborlane.example>", "sender"),
        DataSourceInfo(
            ["Quayside Bistro <orders@quaysidebistro.example>", "jonas.weber@harborlane.example"],
            "recipients",
        ),
        DataSourceInfo("amara.osei@harborlane.example", "cc"),
        DataSourceInfo("Inserting hyperlink", "subject"),
    ],
)
```

### See Also
* class [`DataSourceInfo`](/assembly/python-net/groupdocs.assembly/datasourceinfo/)
