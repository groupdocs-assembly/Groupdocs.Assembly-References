---
title: DataColumn
second_title: GroupDocs.Assembly for Java API Reference
description: Represents one column of data in a .
type: docs
weight: 14
url: /java/com.groupdocs.assembly.system.data/datacolumn/
---
**Inheritance:**
java.lang.Object
```
public class DataColumn
```

Represents one column of data in a [DataTable](../../com.groupdocs.assembly.system.data/datatable).

## Constructors

| Constructor | Description |
| --- | --- |
| [DataColumn()](#DataColumn--) | Initializes a new instance of a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)
 |
| [DataColumn(String name)](#DataColumn-java.lang.String-) | Initializes a new instance of the DataColumn class, as type string, using the specified column name.
 |
| [DataColumn(String name, DataTable table)](#DataColumn-java.lang.String-com.groupdocs.assembly.system.data.DataTable-) | Initializes a new instance of the @{link DataColumn} class using the specified column name and table it belongs to.
 |
| [DataColumn(String name, Class type)](#DataColumn-java.lang.String-java.lang.Class-) | Initializes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class using the specified column name and data type.
 |
| [DataColumn(String name, Class type, DataTable table)](#DataColumn-java.lang.String-java.lang.Class-com.groupdocs.assembly.system.data.DataTable-) | Initializes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class using the specified column name, data type and data table it belongs to.
 |
## Methods

| Method | Description |
| --- | --- |
| [getColumnName()](#getColumnName--) |  |
| [setColumnName(String name)](#setColumnName-java.lang.String-) |  |
| [getAllowDBNull()](#getAllowDBNull--) |  |
| [setAllowDBNull(boolean allows)](#setAllowDBNull-boolean-) |  |
| [getDataType()](#getDataType--) |  |
| [setDataType(Class aClass)](#setDataType-java.lang.Class-) |  |
| [setDefaultValue(Object defaultValue)](#setDefaultValue-java.lang.Object-) | Gets or sets the default value for the column when creating new rows.
 |
| [getDefaultValue()](#getDefaultValue--) |  |
| [getOrdinal()](#getOrdinal--) |  |
| [setOrdinal(int ordinal)](#setOrdinal-int-) |  |
| [getColumnMapping()](#getColumnMapping--) |  |
| [setColumnMapping(int columnMapping)](#setColumnMapping-int-) | Sets the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) of the column.
 |
| [getNamespace()](#getNamespace--) |  |
| [setNamespace(String namespace)](#setNamespace-java.lang.String-) | Sets namespace.
 |
| [getPrefix()](#getPrefix--) |  |
| [setPrefix(String prefix)](#setPrefix-java.lang.String-) | Sets namespace.
 |
| [getTable()](#getTable--) |  |
| [getAutoIncrement()](#getAutoIncrement--) |  |
| [setAutoIncrement(boolean autoIncrement)](#setAutoIncrement-boolean-) | Sets a value indicating whether the column automatically increments the value of the column for new rows added to the table.
 |
| [setMaxLength(int length)](#setMaxLength-int-) |  |
| [getMaxLength()](#getMaxLength--) |  |
| [getCaption()](#getCaption--) |  |
| [setCaption(String caption)](#setCaption-java.lang.String-) |  |
| [getAutoIncrementSeed()](#getAutoIncrementSeed--) |  |
| [setAutoIncrementSeed(long autoIncrementSeed)](#setAutoIncrementSeed-long-) |  |
| [getAutoIncrementStep()](#getAutoIncrementStep--) |  |
| [setAutoIncrementStep(long autoIncrementStep)](#setAutoIncrementStep-long-) |  |
| [setReadOnly(boolean readOnly)](#setReadOnly-boolean-) |  |
| [isReadOnly()](#isReadOnly--) |  |
| [getReadOnly()](#getReadOnly--) |  |
| [getUnique()](#getUnique--) |  |
| [isUnique()](#isUnique--) |  |
| [setUnique(boolean value)](#setUnique-boolean-) |  |
| [getExpression()](#getExpression--) |  |
| [areColumnSetsTheSame(DataColumn[] columnSet, DataColumn[] compareSet)](#areColumnSetsTheSame-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---) |  |
| [toString()](#toString--) |  |
### DataColumn() {#DataColumn--}
```
public DataColumn()
```


Initializes a new instance of a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)


### DataColumn(String name) {#DataColumn-java.lang.String-}
```
public DataColumn(String name)
```


Initializes a new instance of the DataColumn class, as type string, using the specified column name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name of the DataColumn
 |

### DataColumn(String name, DataTable table) {#DataColumn-java.lang.String-com.groupdocs.assembly.system.data.DataTable-}
```
public DataColumn(String name, DataTable table)
```


Initializes a new instance of the @{link DataColumn} class using the specified column name and table it belongs to.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name of the DataColumn
 |
| table | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | the table this column belongs to
 |

### DataColumn(String name, Class type) {#DataColumn-java.lang.String-java.lang.Class-}
```
public DataColumn(String name, Class type)
```


Initializes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class using the specified column name and data type.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name of the DataColumn
 |
| type | java.lang.Class | data type
 |

### DataColumn(String name, Class type, DataTable table) {#DataColumn-java.lang.String-java.lang.Class-com.groupdocs.assembly.system.data.DataTable-}
```
public DataColumn(String name, Class type, DataTable table)
```


Initializes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class using the specified column name, data type and data table it belongs to.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name of the DataColumn
 |
| type | java.lang.Class | data type
 |
| table | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | the table this column belongs to
 |

### getColumnName() {#getColumnName--}
```
public String getColumnName()
```




**Returns:**
java.lang.String - the name of the column within the [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection).

### setColumnName(String name) {#setColumnName-java.lang.String-}
```
public void setColumnName(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | of the column within the [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection).
 |

### getAllowDBNull() {#getAllowDBNull--}
```
public boolean getAllowDBNull()
```




**Returns:**
boolean - a value indicating whether null values are allowed in this column for rows belonging to the table. true if null values are allowed; otherwise, false. The default is true.

### setAllowDBNull(boolean allows) {#setAllowDBNull-boolean-}
```
public void setAllowDBNull(boolean allows)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allows | boolean | is the flag that indicates whether null values are allowed in this column for rows that belong to the table.
 |

### getDataType() {#getDataType--}
```
public Class getDataType()
```




**Returns:**
java.lang.Class - The type of data stored in the column. String by default.

### setDataType(Class aClass) {#setDataType-java.lang.Class-}
```
public void setDataType(Class aClass)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aClass | java.lang.Class | The type of data stored in the column.
 |

### setDefaultValue(Object defaultValue) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object defaultValue)
```


Gets or sets the default value for the column when creating new rows.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| defaultValue | java.lang.Object | - default value for the newly created row.
 |

### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```




**Returns:**
java.lang.Object
### getOrdinal() {#getOrdinal--}
```
public int getOrdinal()
```




**Returns:**
int - the (zero-based) position of the column in the DataColumnCollection collection.

### setOrdinal(int ordinal) {#setOrdinal-int-}
```
public void setOrdinal(int ordinal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int |  |

### getColumnMapping() {#getColumnMapping--}
```
public int getColumnMapping()
```




**Returns:**
int - the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) of the column.

### setColumnMapping(int columnMapping) {#setColumnMapping-int-}
```
public void setColumnMapping(int columnMapping)
```


Sets the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) of the column.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnMapping | int | type
 |

### getNamespace() {#getNamespace--}
```
public String getNamespace()
```




**Returns:**
java.lang.String - namespace.

### setNamespace(String namespace) {#setNamespace-java.lang.String-}
```
public void setNamespace(String namespace)
```


Sets namespace.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespace | java.lang.String | of the DataColumn
 |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```




**Returns:**
java.lang.String - prefix.

### setPrefix(String prefix) {#setPrefix-java.lang.String-}
```
public void setPrefix(String prefix)
```


Sets namespace.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | of the DataColumn
 |

### getTable() {#getTable--}
```
public DataTable getTable()
```




**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - [DataTable](../../com.groupdocs.assembly.system.data/datatable) to which the column belongs to.

### getAutoIncrement() {#getAutoIncrement--}
```
public boolean getAutoIncrement()
```




**Returns:**
boolean - a value indicating whether the column automatically increments the value of the column for new rows added to the table.

### setAutoIncrement(boolean autoIncrement) {#setAutoIncrement-boolean-}
```
public void setAutoIncrement(boolean autoIncrement)
```


Sets a value indicating whether the column automatically increments the value of the column for new rows added to the table.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| autoIncrement | boolean | flag.
 |

### setMaxLength(int length) {#setMaxLength-int-}
```
public void setMaxLength(int length)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| length | int |  |

### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```




**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```




**Returns:**
java.lang.String
### setCaption(String caption) {#setCaption-java.lang.String-}
```
public void setCaption(String caption)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| caption | java.lang.String |  |

### getAutoIncrementSeed() {#getAutoIncrementSeed--}
```
public long getAutoIncrementSeed()
```




**Returns:**
long
### setAutoIncrementSeed(long autoIncrementSeed) {#setAutoIncrementSeed-long-}
```
public void setAutoIncrementSeed(long autoIncrementSeed)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| autoIncrementSeed | long |  |

### getAutoIncrementStep() {#getAutoIncrementStep--}
```
public long getAutoIncrementStep()
```




**Returns:**
long
### setAutoIncrementStep(long autoIncrementStep) {#setAutoIncrementStep-long-}
```
public void setAutoIncrementStep(long autoIncrementStep)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| autoIncrementStep | long |  |

### setReadOnly(boolean readOnly) {#setReadOnly-boolean-}
```
public void setReadOnly(boolean readOnly)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| readOnly | boolean |  |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Returns:**
boolean
### getReadOnly() {#getReadOnly--}
```
public boolean getReadOnly()
```




**Returns:**
boolean
### getUnique() {#getUnique--}
```
public boolean getUnique()
```




**Returns:**
boolean
### isUnique() {#isUnique--}
```
public boolean isUnique()
```




**Returns:**
boolean
### setUnique(boolean value) {#setUnique-boolean-}
```
public void setUnique(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExpression() {#getExpression--}
```
public String getExpression()
```




**Returns:**
java.lang.String
### areColumnSetsTheSame(DataColumn[] columnSet, DataColumn[] compareSet) {#areColumnSetsTheSame-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---}
```
public static boolean areColumnSetsTheSame(DataColumn[] columnSet, DataColumn[] compareSet)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnSet | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) |  |
| compareSet | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) |  |

**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
