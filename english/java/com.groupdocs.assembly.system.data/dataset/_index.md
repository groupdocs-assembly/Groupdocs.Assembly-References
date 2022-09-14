---
title: DataSet
second_title: GroupDocs.Assembly for Java API Reference
description: Represents an in-memory cache of data.
type: docs
weight: 24
url: /java/com.groupdocs.assembly.system.data/dataset/
---
**Inheritance:**
java.lang.Object
```
public class DataSet
```

Represents an in-memory cache of data.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataSet()](#DataSet--) | Initializes a new instance of the com.groupdocs.assembly.system.data.DataSet class. |
| [DataSet(Connection connection)](#DataSet-java.sql.Connection-) | Initializes a new instance of the DataSet class with data taken from Connection. |
| [DataSet(Connection connection, String schemaName)](#DataSet-java.sql.Connection-java.lang.String-) | Initializes a new instance of the DataSet class with data taken from Connection. |
| [DataSet(String dataSetName)](#DataSet-java.lang.String-) | Initializes a new instance of a com.groupdocs.assembly.system.data.DataSet class with the given name. |
## Methods

| Method | Description |
| --- | --- |
| [getDataSetName()](#getDataSetName--) | Gets the name of the current com.groupdocs.assembly.system.data.DataSet. |
| [setDataSetName(String value)](#setDataSetName-java.lang.String-) | Sets the name of the current com.groupdocs.assembly.system.data.DataSet. |
| [getNamespace()](#getNamespace--) | Gets the namespace of the com.groupdocs.assembly.system.data.DataSet. |
| [getTables()](#getTables--) | Gets the collection of tables contained in the com.groupdocs.assembly.system.data.DataSet. |
| [getRelations()](#getRelations--) | Get the collection of relations that link tables and allow navigation from parent tables to child tables. |
| [close()](#close--) |  |
| [clear()](#clear--) | Clears the com.groupdocs.assembly.system.data.DataSet of any data by removing all rows in all tables. |
| [reset()](#reset--) | Resets the com.groupdocs.assembly.system.data.DataSet to its original state. |
| [readXml(InputStream xmlStream, XmlReadMode mode)](#readXml-java.io.InputStream-com.groupdocs.assembly.system.data.XmlReadMode-) | Reads XML schema and data into the DataSet using the specified java.io.InputStream and com.groupdocs.assembly.system.data.XmlReadMode. |
| [readXml(InputStream xmlStream)](#readXml-java.io.InputStream-) | Reads XML schema and data into the DataSet using the specified java.io.InputStream. |
| [readXml(String fileName)](#readXml-java.lang.String-) | Reads XML schema and data into the com.groupdocs.assembly.system.data.DataSet using the specified file. |
| [readXml(String xmlPath, XmlReadMode readMode)](#readXml-java.lang.String-com.groupdocs.assembly.system.data.XmlReadMode-) | Reads XML schema and data into the DataSet using the specified file and com.groupdocs.assembly.system.data.XmlReadMode. |
| [readXmlSchema(InputStream xmlStream)](#readXmlSchema-java.io.InputStream-) | Reads the XML schema from the specified Stream into the DataSet. |
| [readXmlSchema(String fileName)](#readXmlSchema-java.lang.String-) | Reads the XML schema from the specified file into the com.groupdocs.assembly.system.data.DataSet. |
| [setLocale(Locale locale)](#setLocale-java.util.Locale-) | Sets the locale information used to compare strings within the table. |
| [isLocaleSpecified()](#isLocaleSpecified--) |  |
| [getEnforceConstraints()](#getEnforceConstraints--) | Gets a value indicating whether constraint rules are followed when attempting any update operation. |
| [setEnforceConstraints(boolean value)](#setEnforceConstraints-boolean-) | Sets a value indicating whether constraint rules are followed when attempting any update operation. |
### DataSet() {#DataSet--}
```
public DataSet()
```


Initializes a new instance of the com.groupdocs.assembly.system.data.DataSet class.

### DataSet(Connection connection) {#DataSet-java.sql.Connection-}
```
public DataSet(Connection connection)
```


Initializes a new instance of the DataSet class with data taken from Connection. Tables, Relations, Constraints and Indexes will be copied into DataSet.

By default no schema name will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | java.sql.Connection | which contains DB data. |

### DataSet(Connection connection, String schemaName) {#DataSet-java.sql.Connection-java.lang.String-}
```
public DataSet(Connection connection, String schemaName)
```


Initializes a new instance of the DataSet class with data taken from Connection. Tables, Relations, Constraints and Indexes will be copied into DataSet.

`DataSet dataSet = new DataSet(conn, "PUBLIC"); // HSQLDB`

or

`DataSet dataSet = new DataSet(conn); // MYSQL's default schema name.`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | java.sql.Connection | which contains DB data. |
| schemaName | java.lang.String | which contains the tables to be imported. |

### DataSet(String dataSetName) {#DataSet-java.lang.String-}
```
public DataSet(String dataSetName)
```


Initializes a new instance of a com.groupdocs.assembly.system.data.DataSet class with the given name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSetName | java.lang.String | The name of the com.groupdocs.assembly.system.data.DataSet. |

### getDataSetName() {#getDataSetName--}
```
public String getDataSetName()
```


Gets the name of the current com.groupdocs.assembly.system.data.DataSet.

**Returns:**
java.lang.String - The name of the com.groupdocs.assembly.system.data.DataSet.
### setDataSetName(String value) {#setDataSetName-java.lang.String-}
```
public void setDataSetName(String value)
```


Sets the name of the current com.groupdocs.assembly.system.data.DataSet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the com.groupdocs.assembly.system.data.DataSet. |

### getNamespace() {#getNamespace--}
```
public String getNamespace()
```


Gets the namespace of the com.groupdocs.assembly.system.data.DataSet.

**Returns:**
java.lang.String - The namespace of the com.groupdocs.assembly.system.data.DataSet.
### getTables() {#getTables--}
```
public DataTableCollection getTables()
```


Gets the collection of tables contained in the com.groupdocs.assembly.system.data.DataSet.

**Returns:**
[DataTableCollection](../../com.groupdocs.assembly.system.data/datatablecollection) - The com.groupdocs.assembly.system.data.DataTableCollection contained by this com.groupdocs.assembly.system.data.DataSet. An empty collection is returned if no com.groupdocs.assembly.system.data.DataTable objects exist.
### getRelations() {#getRelations--}
```
public DataRelationCollection getRelations()
```


Get the collection of relations that link tables and allow navigation from parent tables to child tables.

**Returns:**
[DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection) - A com.groupdocs.assembly.system.data.DataRelationCollection that contains a collection of com.groupdocs.assembly.system.data.DataRelation objects. An empty collection is returned if no com.groupdocs.assembly.system.data.DataRelation objects exist.
### close() {#close--}
```
public void close()
```




### clear() {#clear--}
```
public void clear()
```


Clears the com.groupdocs.assembly.system.data.DataSet of any data by removing all rows in all tables.

### reset() {#reset--}
```
public void reset()
```


Resets the com.groupdocs.assembly.system.data.DataSet to its original state. Subclasses should override com.groupdocs.assembly.system.data.DataSet\#reset() to restore a com.groupdocs.assembly.system.data.DataSet to its original state.

### readXml(InputStream xmlStream, XmlReadMode mode) {#readXml-java.io.InputStream-com.groupdocs.assembly.system.data.XmlReadMode-}
```
public XmlReadMode readXml(InputStream xmlStream, XmlReadMode mode)
```


Reads XML schema and data into the DataSet using the specified java.io.InputStream and com.groupdocs.assembly.system.data.XmlReadMode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | The Stream from which to read. |
| mode | [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) | One of the com.groupdocs.assembly.system.data.XmlReadMode values. |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - The XmlReadMode used to read the data.
### readXml(InputStream xmlStream) {#readXml-java.io.InputStream-}
```
public XmlReadMode readXml(InputStream xmlStream)
```


Reads XML schema and data into the DataSet using the specified java.io.InputStream. The \#readXml(InputStream, XmlReadMode) method provides a way to read either data only, or both data and schema into a DataSet from an XML document, whereas the \#readXmlSchema(InputStream) method reads only the schema. To read both data and schema, use one of the `readXML` overloads that includes the mode parameter, and set its value to ReadSchema. If an in-line schema is specified, the in-line schema is used to extend the existing relational structure prior to loading the data. If there are any conflicts (for example, the same column in the same table defined with different data types) an exception is raised.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | data stream |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - mode which was used while reading
### readXml(String fileName) {#readXml-java.lang.String-}
```
public XmlReadMode readXml(String fileName)
```


Reads XML schema and data into the com.groupdocs.assembly.system.data.DataSet using the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The filename (including the path) from which to read. |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - The XmlReadMode used to read the data. The returned value is one of com.groupdocs.assembly.system.data.XmlReadMode constants.
### readXml(String xmlPath, XmlReadMode readMode) {#readXml-java.lang.String-com.groupdocs.assembly.system.data.XmlReadMode-}
```
public XmlReadMode readXml(String xmlPath, XmlReadMode readMode)
```


Reads XML schema and data into the DataSet using the specified file and com.groupdocs.assembly.system.data.XmlReadMode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlPath | java.lang.String | the specified file |
| readMode | [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) | com.groupdocs.assembly.system.data.XmlReadMode |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - mode which was used while reading
### readXmlSchema(InputStream xmlStream) {#readXmlSchema-java.io.InputStream-}
```
public void readXmlSchema(InputStream xmlStream)
```


Reads the XML schema from the specified Stream into the DataSet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | won't be closed after the schema has been read. |

### readXmlSchema(String fileName) {#readXmlSchema-java.lang.String-}
```
public void readXmlSchema(String fileName)
```


Reads the XML schema from the specified file into the com.groupdocs.assembly.system.data.DataSet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name (including the path) from which to read. |

### setLocale(Locale locale) {#setLocale-java.util.Locale-}
```
public void setLocale(Locale locale)
```


Sets the locale information used to compare strings within the table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| locale | java.util.Locale | of this data set |

### isLocaleSpecified() {#isLocaleSpecified--}
```
public boolean isLocaleSpecified()
```




**Returns:**
boolean - true if locale was set
### getEnforceConstraints() {#getEnforceConstraints--}
```
public boolean getEnforceConstraints()
```


Gets a value indicating whether constraint rules are followed when attempting any update operation.

**Returns:**
boolean - true if rules are enforced; otherwise false. The default is true.
### setEnforceConstraints(boolean value) {#setEnforceConstraints-boolean-}
```
public void setEnforceConstraints(boolean value)
```


Sets a value indicating whether constraint rules are followed when attempting any update operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if rules are enforced; otherwise false. The default is true. |

