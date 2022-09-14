---
title: DataSourceInfo
second_title: GroupDocs.Assembly for Java API Reference
description: Provides information on a single data source object to be used to assemble a document from a template.
type: docs
weight: 13
url: /java/com.groupdocs.assembly/datasourceinfo/
---
**Inheritance:**
java.lang.Object
```
public class DataSourceInfo
```

Provides information on a single data source object to be used to assemble a document from a template.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataSourceInfo()](#DataSourceInfo--) | Creates a new instance of this class without any properties specified. |
| [DataSourceInfo(Object dataSource)](#DataSourceInfo-java.lang.Object-) | Creates a new instance of this class with the data source object specified. |
| [DataSourceInfo(Object dataSource, String name)](#DataSourceInfo-java.lang.Object-java.lang.String-) | Creates a new instance of this class with the data source object and its name specified. |
## Methods

| Method | Description |
| --- | --- |
| [getDataSource()](#getDataSource--) | Gets the data source object. |
| [setDataSource(Object value)](#setDataSource-java.lang.Object-) | Sets the data source object. |
| [getName()](#getName--) | Gets the name of the data source object to be used to access the data source object in a template document. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name of the data source object to be used to access the data source object in a template document. |
### DataSourceInfo() {#DataSourceInfo--}
```
public DataSourceInfo()
```


Creates a new instance of this class without any properties specified.

### DataSourceInfo(Object dataSource) {#DataSourceInfo-java.lang.Object-}
```
public DataSourceInfo(Object dataSource)
```


Creates a new instance of this class with the data source object specified.

The data source object can be of one of the following types:

 *  com.groupdocs.assembly.XmlDataSource
 *  com.groupdocs.assembly.JsonDataSource
 *  com.groupdocs.assembly.CsvDataSource
 *  com.groupdocs.assembly.DocumentTableSet
 *  com.groupdocs.assembly.DocumentTable
 *  com.groupdocs.assembly.system.data.DataSet
 *  com.groupdocs.assembly.system.data.DataTable
 *  com.groupdocs.assembly.system.data.DataRow
 *  com.groupdocs.assembly.system.data.IDataReader
 *  com.groupdocs.assembly.system.data.IDataRecord
 *  com.groupdocs.assembly.system.data.DataView
 *  com.groupdocs.assembly.system.data.DataRowView
 *  Any other arbitrary Java type

For information on how to work with data sources of different types in template documents, see template syntax reference(https://docs.groupdocs.com/display/assemblyjava/Template+Syntax+-+Part+1+of+2\#TemplateSyntax-Part1of2-UsingDataSources).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSource | java.lang.Object | The data source object. |

### DataSourceInfo(Object dataSource, String name) {#DataSourceInfo-java.lang.Object-java.lang.String-}
```
public DataSourceInfo(Object dataSource, String name)
```


Creates a new instance of this class with the data source object and its name specified.

The data source object can be of one of the following types:

 *  com.groupdocs.assembly.XmlDataSource
 *  com.groupdocs.assembly.JsonDataSource
 *  com.groupdocs.assembly.CsvDataSource
 *  com.groupdocs.assembly.DocumentTableSet
 *  com.groupdocs.assembly.DocumentTable
 *  com.groupdocs.assembly.system.data.DataSet
 *  com.groupdocs.assembly.system.data.DataTable
 *  com.groupdocs.assembly.system.data.DataRow
 *  com.groupdocs.assembly.system.data.IDataReader
 *  com.groupdocs.assembly.system.data.IDataRecord
 *  com.groupdocs.assembly.system.data.DataView
 *  com.groupdocs.assembly.system.data.DataRowView
 *  Any other arbitrary Java type

For information on how to work with data sources of different types in template documents, see template syntax reference(https://docs.groupdocs.com/display/assemblyjava/Template+Syntax+-+Part+1+of+2\#TemplateSyntax-Part1of2-UsingDataSources).

When the name of the data source object is specified, you can access the data source object and its members in a template document using the name.

When the name of the data source object is null or empty, you can still access members of the data source object in a template document using context object member access (see Template Syntax Reference for more information), but you cannot access the data source object itself.

When passing multiple com.groupdocs.assembly.DataSourceInfo instances to com.groupdocs.assembly.DocumentAssembler, only the name of the first data source object can be null or empty. Names of the rest ones must be specified and unique.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSource | java.lang.Object | The data source object. |
| name | java.lang.String | The name of the data source object to be used to access the data source object in a template document. |

### getDataSource() {#getDataSource--}
```
public Object getDataSource()
```


Gets the data source object.

The data source object can be of one of the following types:

 *  com.groupdocs.assembly.XmlDataSource
 *  com.groupdocs.assembly.JsonDataSource
 *  com.groupdocs.assembly.CsvDataSource
 *  com.groupdocs.assembly.DocumentTableSet
 *  com.groupdocs.assembly.DocumentTable
 *  com.groupdocs.assembly.system.data.DataSet
 *  com.groupdocs.assembly.system.data.DataTable
 *  com.groupdocs.assembly.system.data.DataRow
 *  com.groupdocs.assembly.system.data.IDataReader
 *  com.groupdocs.assembly.system.data.IDataRecord
 *  com.groupdocs.assembly.system.data.DataView
 *  com.groupdocs.assembly.system.data.DataRowView
 *  Any other arbitrary Java type

For information on how to work with data sources of different types in template documents, see template syntax reference(https://docs.groupdocs.com/display/assemblyjava/Template+Syntax+-+Part+1+of+2\#TemplateSyntax-Part1of2-UsingDataSources).

**Returns:**
java.lang.Object - The data source object.
### setDataSource(Object value) {#setDataSource-java.lang.Object-}
```
public void setDataSource(Object value)
```


Sets the data source object.

The data source object can be of one of the following types:

 *  com.groupdocs.assembly.XmlDataSource
 *  com.groupdocs.assembly.JsonDataSource
 *  com.groupdocs.assembly.CsvDataSource
 *  com.groupdocs.assembly.DocumentTableSet
 *  com.groupdocs.assembly.DocumentTable
 *  com.groupdocs.assembly.system.data.DataSet
 *  com.groupdocs.assembly.system.data.DataTable
 *  com.groupdocs.assembly.system.data.DataRow
 *  com.groupdocs.assembly.system.data.IDataReader
 *  com.groupdocs.assembly.system.data.IDataRecord
 *  com.groupdocs.assembly.system.data.DataView
 *  com.groupdocs.assembly.system.data.DataRowView
 *  Any other arbitrary Java type

For information on how to work with data sources of different types in template documents, see template syntax reference(https://docs.groupdocs.com/display/assemblyjava/Template+Syntax+-+Part+1+of+2\#TemplateSyntax-Part1of2-UsingDataSources).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The data source object. |

### getName() {#getName--}
```
public String getName()
```


Gets the name of the data source object to be used to access the data source object in a template document.

When the name of the data source object is specified, you can access the data source object and its members in a template document using the name.

When the name of the data source object is null or empty, you can still access members of the data source object in a template document using context object member access (see Template Syntax Reference for more information), but you cannot access the data source object itself.

When passing multiple com.groupdocs.assembly.DataSourceInfo instances to com.groupdocs.assembly.DocumentAssembler, only the name of the first data source object can be null or empty. Names of the rest ones must be specified and unique.

**Returns:**
java.lang.String - The name of the data source object to be used to access the data source object in a template document.
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets the name of the data source object to be used to access the data source object in a template document.

When the name of the data source object is specified, you can access the data source object and its members in a template document using the name.

When the name of the data source object is null or empty, you can still access members of the data source object in a template document using context object member access (see Template Syntax Reference for more information), but you cannot access the data source object itself.

When passing multiple com.groupdocs.assembly.DataSourceInfo instances to com.groupdocs.assembly.DocumentAssembler, only the name of the first data source object can be null or empty. Names of the rest ones must be specified and unique.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the data source object to be used to access the data source object in a template document. |

