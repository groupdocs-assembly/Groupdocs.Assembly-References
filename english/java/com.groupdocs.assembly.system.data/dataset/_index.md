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
| [DataSet()](#DataSet--) | Initializes a new instance of the DataSet class.
 |
| [DataSet(Connection connection)](#DataSet-java.sql.Connection-) | Initializes a new instance of the DataSet class with data taken from Connection.
 |
| [DataSet(Connection connection, String schemaName)](#DataSet-java.sql.Connection-java.lang.String-) | Initializes a new instance of the DataSet class with data taken from Connection.
 |
| [DataSet(String name)](#DataSet-java.lang.String-) | Initializes a new instance of a DataSet class with the given name.
 |
## Methods

| Method | Description |
| --- | --- |
| [getDataSetName()](#getDataSetName--) | Gets the name of the current DataSet.
 |
| [setDataSetName(String newDataSetName)](#setDataSetName-java.lang.String-) | Sets the name of the current DataSet.
 |
| [getNamespace()](#getNamespace--) |  |
| [getTables()](#getTables--) | Gets the collection of tables contained in the DataSet.
 |
| [getRelations()](#getRelations--) | Get the collection of relations that link tables and allow navigation from parent tables to child tables.
 |
| [close()](#close--) |  |
| [clear()](#clear--) | Clears the DataSet of any data by removing all rows in all tables.
 |
| [reset()](#reset--) | Clears all tables and removes all relations, foreign constraints, and tables from the DataSet.
 |
| [readXml(InputStream xmlStream, XmlReadMode mode)](#readXml-java.io.InputStream-com.groupdocs.assembly.system.data.XmlReadMode-) | Reads XML schema and data into the DataSet using the specified InputStream and [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode).
 |
| [readXml(System.IO.Stream xmlStream)](#readXml-com.aspose.ms.System.IO.Stream-) | Reads XML schema and data into the DataSet using the specified InputStream.
 |
| [readXml(InputStream xmlStream)](#readXml-java.io.InputStream-) | Reads XML schema and data into the DataSet using the specified InputStream.
 |
| [readXml(String xmlPath)](#readXml-java.lang.String-) | Reads XML schema and data into the DataSet using the specified file.
 |
| [readXml(String xmlPath, XmlReadMode readMode)](#readXml-java.lang.String-com.groupdocs.assembly.system.data.XmlReadMode-) | Reads XML schema and data into the DataSet using the specified file and [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode).
 |
| [readXmlSchema(System.IO.Stream xmlStream)](#readXmlSchema-com.aspose.ms.System.IO.Stream-) | Reads the XML schema from the specified Stream into the DataSet.
 |
| [readXmlSchema(InputStream xmlStream)](#readXmlSchema-java.io.InputStream-) | Reads the XML schema from the specified Stream into the DataSet.
 |
| [readXmlSchema(String xmlPath)](#readXmlSchema-java.lang.String-) | Reads the XML schema from the specified file into the DataSet.
 |
| [setLocale(Locale locale)](#setLocale-java.util.Locale-) | Sets the locale information used to compare strings within the table.
 |
| [isLocaleSpecified()](#isLocaleSpecified--) |  |
| [getEnforceConstraints()](#getEnforceConstraints--) |  |
| [setEnforceConstraints(boolean enforceConstraints)](#setEnforceConstraints-boolean-) |  |
### DataSet() {#DataSet--}
```
public DataSet()
```


Initializes a new instance of the DataSet class.


### DataSet(Connection connection) {#DataSet-java.sql.Connection-}
```
public DataSet(Connection connection)
```


Initializes a new instance of the DataSet class with data taken from Connection. Tables, Relations, Constraints and Indexes will be copied into DataSet.


By default no schema name will be used.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | java.sql.Connection | which contains DB data.
 |

### DataSet(Connection connection, String schemaName) {#DataSet-java.sql.Connection-java.lang.String-}
```
public DataSet(Connection connection, String schemaName)
```


Initializes a new instance of the DataSet class with data taken from Connection. Tables, Relations, Constraints and Indexes will be copied into DataSet.


`
DataSet dataSet = new DataSet(conn, "PUBLIC"); // HSQLDB
`


or


`
DataSet dataSet = new DataSet(conn); // MYSQL's default schema name.
`


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| connection | java.sql.Connection | which contains DB data.
 |
| schemaName | java.lang.String | which contains the tables to be imported.
 |

### DataSet(String name) {#DataSet-java.lang.String-}
```
public DataSet(String name)
```


Initializes a new instance of a DataSet class with the given name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the DataSet.
 |

### getDataSetName() {#getDataSetName--}
```
public String getDataSetName()
```


Gets the name of the current DataSet.


**Returns:**
java.lang.String - the name of the current DataSet

### setDataSetName(String newDataSetName) {#setDataSetName-java.lang.String-}
```
public void setDataSetName(String newDataSetName)
```


Sets the name of the current DataSet.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newDataSetName | java.lang.String | DataSet name
 |

### getNamespace() {#getNamespace--}
```
public String getNamespace()
```




**Returns:**
java.lang.String
### getTables() {#getTables--}
```
public DataTableCollection getTables()
```


Gets the collection of tables contained in the DataSet.


**Returns:**
[DataTableCollection](../../com.groupdocs.assembly.system.data/datatablecollection) - collection of tables in this DataSet

### getRelations() {#getRelations--}
```
public DataRelationCollection getRelations()
```


Get the collection of relations that link tables and allow navigation from parent tables to child tables.


**Returns:**
[DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection) - collection of relations in this DataSet

### close() {#close--}
```
public void close()
```




### clear() {#clear--}
```
public void clear()
```


Clears the DataSet of any data by removing all rows in all tables.


### reset() {#reset--}
```
public void reset()
```


Clears all tables and removes all relations, foreign constraints, and tables from the DataSet.


### readXml(InputStream xmlStream, XmlReadMode mode) {#readXml-java.io.InputStream-com.groupdocs.assembly.system.data.XmlReadMode-}
```
public XmlReadMode readXml(InputStream xmlStream, XmlReadMode mode)
```


Reads XML schema and data into the DataSet using the specified InputStream and [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | The Stream from which to read.
 |
| mode | [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) | One of the [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) values.
 |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - The XmlReadMode used to read the data.

### readXml(System.IO.Stream xmlStream) {#readXml-com.aspose.ms.System.IO.Stream-}
```
public XmlReadMode readXml(System.IO.Stream xmlStream)
```


Reads XML schema and data into the DataSet using the specified InputStream. The #readXml(InputStream, XmlReadMode).readXml(InputStream, XmlReadMode) method provides a way to read either data only, or both data and schema into a DataSet from an XML document, whereas the #readXmlSchema(InputStream).readXmlSchema(InputStream) method reads only the schema. To read both data and schema, use one of the `readXML` overloads that includes the mode parameter, and set its value to ReadSchema. If an in-line schema is specified, the in-line schema is used to extend the existing relational structure prior to loading the data. If there are any conflicts (for example, the same column in the same table defined with different data types) an exception is raised.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | com.aspose.ms.System.IO.Stream | data stream
 |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - mode which was used while reading

### readXml(InputStream xmlStream) {#readXml-java.io.InputStream-}
```
public XmlReadMode readXml(InputStream xmlStream)
```


Reads XML schema and data into the DataSet using the specified InputStream. The #readXml(InputStream, XmlReadMode).readXml(InputStream, XmlReadMode) method provides a way to read either data only, or both data and schema into a DataSet from an XML document, whereas the #readXmlSchema(InputStream).readXmlSchema(InputStream) method reads only the schema. To read both data and schema, use one of the `readXML` overloads that includes the mode parameter, and set its value to ReadSchema. If an in-line schema is specified, the in-line schema is used to extend the existing relational structure prior to loading the data. If there are any conflicts (for example, the same column in the same table defined with different data types) an exception is raised.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | data stream
 |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - mode which was used while reading

### readXml(String xmlPath) {#readXml-java.lang.String-}
```
public XmlReadMode readXml(String xmlPath)
```


Reads XML schema and data into the DataSet using the specified file.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlPath | java.lang.String | the specified file
 |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - mode which was used while reading

### readXml(String xmlPath, XmlReadMode readMode) {#readXml-java.lang.String-com.groupdocs.assembly.system.data.XmlReadMode-}
```
public XmlReadMode readXml(String xmlPath, XmlReadMode readMode)
```


Reads XML schema and data into the DataSet using the specified file and [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlPath | java.lang.String | the specified file
 |
| readMode | [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) | [XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode)
 |

**Returns:**
[XmlReadMode](../../com.groupdocs.assembly.system.data/xmlreadmode) - mode which was used while reading

### readXmlSchema(System.IO.Stream xmlStream) {#readXmlSchema-com.aspose.ms.System.IO.Stream-}
```
public void readXmlSchema(System.IO.Stream xmlStream)
```


Reads the XML schema from the specified Stream into the DataSet.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | com.aspose.ms.System.IO.Stream | won't be closed after the schema has been read.
 |

### readXmlSchema(InputStream xmlStream) {#readXmlSchema-java.io.InputStream-}
```
public void readXmlSchema(InputStream xmlStream)
```


Reads the XML schema from the specified Stream into the DataSet.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | won't be closed after the schema has been read.
 |

### readXmlSchema(String xmlPath) {#readXmlSchema-java.lang.String-}
```
public void readXmlSchema(String xmlPath)
```


Reads the XML schema from the specified file into the DataSet.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlPath | java.lang.String | The file name (including the path) from which to read.
 |

### setLocale(Locale locale) {#setLocale-java.util.Locale-}
```
public void setLocale(Locale locale)
```


Sets the locale information used to compare strings within the table.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| locale | java.util.Locale | of this data set
 |

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




**Returns:**
boolean - true if [UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) and [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) must be taken into account

### setEnforceConstraints(boolean enforceConstraints) {#setEnforceConstraints-boolean-}
```
public void setEnforceConstraints(boolean enforceConstraints)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enforceConstraints | boolean | indicates whether check constraints violation or not
 |

