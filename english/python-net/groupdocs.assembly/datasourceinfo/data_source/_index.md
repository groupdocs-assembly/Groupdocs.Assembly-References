---
title: data_source property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The data source object."
type: docs
url: /python-net/groupdocs.assembly/datasourceinfo/data_source/
is_root: false
weight: 2010
---


## data_source property

The data source object.

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

### Definition:
```python
@property
def data_source(self):
    ...
@data_source.setter
def data_source(self, value):
    ...
```

### See Also
* class [`DataSourceInfo`](/assembly/python-net/groupdocs.assembly/datasourceinfo/)
