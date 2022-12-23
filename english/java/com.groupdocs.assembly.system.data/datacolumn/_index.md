---
title: DataColumn
second_title: GroupDocs.Assembly for Java API Reference
description: Represents the schema of a column in a .
type: docs
weight: 14
url: /java/com.groupdocs.assembly.system.data/datacolumn/
---
**Inheritance:**
java.lang.Object
```
public final class DataColumn
```

Represents the schema of a column in a [DataTable](../../com.groupdocs.assembly.system.data/datatable).
## Constructors

| Constructor | Description |
| --- | --- |
| [DataColumn()](#DataColumn--) | Initializes a new instance of a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class as type string. |
| [DataColumn(String columnName)](#DataColumn-java.lang.String-) | Inititalizes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class, as type string, using the specified column name. |
| [DataColumn(String name, DataTable table)](#DataColumn-java.lang.String-com.groupdocs.assembly.system.data.DataTable-) | Initializes a new instance of the @\{link DataColumn\} class using the specified column name and table it belongs to. |
| [DataColumn(String columnName, Class dataType)](#DataColumn-java.lang.String-java.lang.Class-) | Inititalizes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class using the specified column name and data type. |
| [DataColumn(String name, Class type, DataTable table)](#DataColumn-java.lang.String-java.lang.Class-com.groupdocs.assembly.system.data.DataTable-) | Initializes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class using the specified column name, data type and data table it belongs to. |
## Methods

| Method | Description |
| --- | --- |
| [getColumnName()](#getColumnName--) | Gets the name of the column in the [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection). |
| [setColumnName(String value)](#setColumnName-java.lang.String-) | Sets the name of the column in the [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection). |
| [getAllowDBNull()](#getAllowDBNull--) | Gets a value that indicates whether null values are allowed in this column for rows that belong to the table. |
| [setAllowDBNull(boolean value)](#setAllowDBNull-boolean-) | Sets a value that indicates whether null values are allowed in this column for rows that belong to the table. |
| [getDataType()](#getDataType--) | Gets the type of data stored in the column. |
| [setDataType(Class value)](#setDataType-java.lang.Class-) | Sets the type of data stored in the column. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Sets the default value for the column when you are creating new rows. |
| [getDefaultValue()](#getDefaultValue--) | Gets the default value for the column when you are creating new rows. |
| [getOrdinal()](#getOrdinal--) | Gets the position of the column in the [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection) collection. |
| [setOrdinal(int ordinal)](#setOrdinal-int-) | Changes the ordinal or position of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) to the specified ordinal or position. |
| [getColumnMapping()](#getColumnMapping--) | Gets the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) of the column. |
| [setColumnMapping(int value)](#setColumnMapping-int-) | Sets the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) of the column. |
| [getNamespace()](#getNamespace--) | Gets the namespace of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn). |
| [setNamespace(String value)](#setNamespace-java.lang.String-) | Sets the namespace of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn). |
| [getPrefix()](#getPrefix--) | Gets an XML prefix that aliases the namespace of the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | Sets an XML prefix that aliases the namespace of the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [getTable()](#getTable--) | Gets the [DataTable](../../com.groupdocs.assembly.system.data/datatable) to which the column belongs to. |
| [getAutoIncrement()](#getAutoIncrement--) | Gets a value that indicates whether the column automatically increments the value of the column for new rows added to the table. |
| [setAutoIncrement(boolean value)](#setAutoIncrement-boolean-) | Sets a value that indicates whether the column automatically increments the value of the column for new rows added to the table. |
| [setMaxLength(int value)](#setMaxLength-int-) | Sets the maximum length of a text column. |
| [getMaxLength()](#getMaxLength--) | Gets the maximum length of a text column. |
| [getCaption()](#getCaption--) | Gets the caption for the column. |
| [setCaption(String value)](#setCaption-java.lang.String-) | Sets the caption for the column. |
| [getAutoIncrementSeed()](#getAutoIncrementSeed--) | Gets the starting value for a column that has its [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) property set to true. |
| [setAutoIncrementSeed(long value)](#setAutoIncrementSeed-long-) | Sets the starting value for a column that has its [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) property set to true. |
| [getAutoIncrementStep()](#getAutoIncrementStep--) | Gets the increment used by a column with its [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) property set to true. |
| [setAutoIncrementStep(long value)](#setAutoIncrementStep-long-) | Sets the increment used by a column with its [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) property set to true. |
| [setReadOnly(boolean value)](#setReadOnly-boolean-) | Sets a value that indicates whether the column allows for changes as soon as a row has been added to the table. |
| [isReadOnly()](#isReadOnly--) |  |
| [getReadOnly()](#getReadOnly--) | Gets a value that indicates whether the column allows for changes as soon as a row has been added to the table. |
| [getUnique()](#getUnique--) | Gets a value that indicates whether the values in each row of the column must be unique. |
| [isUnique()](#isUnique--) |  |
| [setUnique(boolean value)](#setUnique-boolean-) | Sets a value that indicates whether the values in each row of the column must be unique. |
| [getExpression()](#getExpression--) | Gets the expression used to filter rows, calculate the values in a column, or create an aggregate column. |
| [areColumnSetsTheSame(DataColumn[] columnSet, DataColumn[] compareSet)](#areColumnSetsTheSame-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---) |  |
| [toString()](#toString--) | Gets the [getExpression()](../../com.groupdocs.assembly.system.data/datacolumn\#getExpression--) of the column, if one exists. |
### DataColumn() {#DataColumn--}
```
public DataColumn()
```


Initializes a new instance of a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class as type string.

### DataColumn(String columnName) {#DataColumn-java.lang.String-}
```
public DataColumn(String columnName)
```


Inititalizes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class, as type string, using the specified column name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | A string that represents the name of the column to be created. If set to null or an empty string (""), a default name will be specified when added to the columns collection. |

### DataColumn(String name, DataTable table) {#DataColumn-java.lang.String-com.groupdocs.assembly.system.data.DataTable-}
```
public DataColumn(String name, DataTable table)
```


Initializes a new instance of the @\{link DataColumn\} class using the specified column name and table it belongs to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name of the DataColumn |
| table | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | the table this column belongs to |

### DataColumn(String columnName, Class dataType) {#DataColumn-java.lang.String-java.lang.Class-}
```
public DataColumn(String columnName, Class dataType)
```


Inititalizes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class using the specified column name and data type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | A string that represents the name of the column to be created. If set to null or an empty string (""), a default name will be specified when added to the columns collection. |
| dataType | java.lang.Class | A supported [getDataType()](../../com.groupdocs.assembly.system.data/datacolumn\#getDataType--) / [setDataType(java.lang.Class)](../../com.groupdocs.assembly.system.data/datacolumn\#setDataType-java.lang.Class-). |

### DataColumn(String name, Class type, DataTable table) {#DataColumn-java.lang.String-java.lang.Class-com.groupdocs.assembly.system.data.DataTable-}
```
public DataColumn(String name, Class type, DataTable table)
```


Initializes a new instance of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) class using the specified column name, data type and data table it belongs to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name of the DataColumn |
| type | java.lang.Class | data type |
| table | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | the table this column belongs to |

### getColumnName() {#getColumnName--}
```
public final String getColumnName()
```


Gets the name of the column in the [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection).

**Returns:**
java.lang.String - The name of the column.
### setColumnName(String value) {#setColumnName-java.lang.String-}
```
public final void setColumnName(String value)
```


Sets the name of the column in the [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the column. |

### getAllowDBNull() {#getAllowDBNull--}
```
public final boolean getAllowDBNull()
```


Gets a value that indicates whether null values are allowed in this column for rows that belong to the table.

**Returns:**
boolean - true if null values values are allowed; otherwise, false. The default is true.
### setAllowDBNull(boolean value) {#setAllowDBNull-boolean-}
```
public final void setAllowDBNull(boolean value)
```


Sets a value that indicates whether null values are allowed in this column for rows that belong to the table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if null values values are allowed; otherwise, false. The default is true. |

### getDataType() {#getDataType--}
```
public final Class getDataType()
```


Gets the type of data stored in the column.

**Returns:**
java.lang.Class - A java.lang.Class object that represents the column data type.
### setDataType(Class value) {#setDataType-java.lang.Class-}
```
public final void setDataType(Class value)
```


Sets the type of data stored in the column.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Class | A java.lang.Class object that represents the column data type. |

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public final void setDefaultValue(Object value)
```


Sets the default value for the column when you are creating new rows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | A value appropriate to the column's [getDataType()](../../com.groupdocs.assembly.system.data/datacolumn\#getDataType--) / [setDataType(java.lang.Class)](../../com.groupdocs.assembly.system.data/datacolumn\#setDataType-java.lang.Class-). |

### getDefaultValue() {#getDefaultValue--}
```
public final Object getDefaultValue()
```


Gets the default value for the column when you are creating new rows.

**Returns:**
java.lang.Object - A value appropriate to the column's [getDataType()](../../com.groupdocs.assembly.system.data/datacolumn\#getDataType--) / [setDataType(java.lang.Class)](../../com.groupdocs.assembly.system.data/datacolumn\#setDataType-java.lang.Class-).
### getOrdinal() {#getOrdinal--}
```
public final int getOrdinal()
```


Gets the position of the column in the [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection) collection.

**Returns:**
int - The position of the column. Gets -1 if the column is not a member of a collection.
### setOrdinal(int ordinal) {#setOrdinal-int-}
```
public final void setOrdinal(int ordinal)
```


Changes the ordinal or position of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) to the specified ordinal or position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int | The specified ordinal. |

### getColumnMapping() {#getColumnMapping--}
```
public final int getColumnMapping()
```


Gets the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) of the column.

**Returns:**
int - One of the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) values. The returned value is one of [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) constants.
### setColumnMapping(int value) {#setColumnMapping-int-}
```
public final void setColumnMapping(int value)
```


Sets the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) of the column.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | One of the [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) values. The value must be one of [MappingType](../../com.groupdocs.assembly.system.data/mappingtype) constants. |

### getNamespace() {#getNamespace--}
```
public final String getNamespace()
```


Gets the namespace of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn).

**Returns:**
java.lang.String - The namespace of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn).
### setNamespace(String value) {#setNamespace-java.lang.String-}
```
public final void setNamespace(String value)
```


Sets the namespace of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The namespace of the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn). |

### getPrefix() {#getPrefix--}
```
public final String getPrefix()
```


Gets an XML prefix that aliases the namespace of the [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Returns:**
java.lang.String - The XML prefix for the [DataTable](../../com.groupdocs.assembly.system.data/datatable) namespace.
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public final void setPrefix(String value)
```


Sets an XML prefix that aliases the namespace of the [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The XML prefix for the [DataTable](../../com.groupdocs.assembly.system.data/datatable) namespace. |

### getTable() {#getTable--}
```
public final DataTable getTable()
```


Gets the [DataTable](../../com.groupdocs.assembly.system.data/datatable) to which the column belongs to.

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - The [DataTable](../../com.groupdocs.assembly.system.data/datatable) that the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) belongs to.
### getAutoIncrement() {#getAutoIncrement--}
```
public final boolean getAutoIncrement()
```


Gets a value that indicates whether the column automatically increments the value of the column for new rows added to the table.

**Returns:**
boolean - true if the value of the column increments automatically; otherwise, false. The default is false.
### setAutoIncrement(boolean value) {#setAutoIncrement-boolean-}
```
public final void setAutoIncrement(boolean value)
```


Sets a value that indicates whether the column automatically increments the value of the column for new rows added to the table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if the value of the column increments automatically; otherwise, false. The default is false. |

### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Sets the maximum length of a text column.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum length of the column in characters. If the column has no maximum length, the value is -1 (default). |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Gets the maximum length of a text column.

**Returns:**
int - The maximum length of the column in characters. If the column has no maximum length, the value is -1 (default).
### getCaption() {#getCaption--}
```
public final String getCaption()
```


Gets the caption for the column.

**Returns:**
java.lang.String - The caption of the column. If not set, returns the [getColumnName()](../../com.groupdocs.assembly.system.data/datacolumn\#getColumnName--) / [setColumnName(java.lang.String)](../../com.groupdocs.assembly.system.data/datacolumn\#setColumnName-java.lang.String-) value.
### setCaption(String value) {#setCaption-java.lang.String-}
```
public final void setCaption(String value)
```


Sets the caption for the column.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The caption of the column. If not set, returns the [getColumnName()](../../com.groupdocs.assembly.system.data/datacolumn\#getColumnName--) / [setColumnName(java.lang.String)](../../com.groupdocs.assembly.system.data/datacolumn\#setColumnName-java.lang.String-) value. |

### getAutoIncrementSeed() {#getAutoIncrementSeed--}
```
public final long getAutoIncrementSeed()
```


Gets the starting value for a column that has its [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) property set to true.

**Returns:**
long - The starting value for the [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) feature.
### setAutoIncrementSeed(long value) {#setAutoIncrementSeed-long-}
```
public final void setAutoIncrementSeed(long value)
```


Sets the starting value for a column that has its [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) property set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The starting value for the [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) feature. |

### getAutoIncrementStep() {#getAutoIncrementStep--}
```
public final long getAutoIncrementStep()
```


Gets the increment used by a column with its [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) property set to true.

**Returns:**
long - The number by which the value of the column is automatically incremented. The default is 1.
### setAutoIncrementStep(long value) {#setAutoIncrementStep-long-}
```
public final void setAutoIncrementStep(long value)
```


Sets the increment used by a column with its [getAutoIncrement()](../../com.groupdocs.assembly.system.data/datacolumn\#getAutoIncrement--) / [setAutoIncrement(boolean)](../../com.groupdocs.assembly.system.data/datacolumn\#setAutoIncrement-boolean-) property set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The number by which the value of the column is automatically incremented. The default is 1. |

### setReadOnly(boolean value) {#setReadOnly-boolean-}
```
public final void setReadOnly(boolean value)
```


Sets a value that indicates whether the column allows for changes as soon as a row has been added to the table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if the column is read only; otherwise, false. The default is false. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```




**Returns:**
boolean
### getReadOnly() {#getReadOnly--}
```
public final boolean getReadOnly()
```


Gets a value that indicates whether the column allows for changes as soon as a row has been added to the table.

**Returns:**
boolean - true if the column is read only; otherwise, false. The default is false.
### getUnique() {#getUnique--}
```
public final boolean getUnique()
```


Gets a value that indicates whether the values in each row of the column must be unique.

**Returns:**
boolean - true if the value must be unique; otherwise, false. The default is false.
### isUnique() {#isUnique--}
```
public final boolean isUnique()
```




**Returns:**
boolean
### setUnique(boolean value) {#setUnique-boolean-}
```
public final void setUnique(boolean value)
```


Sets a value that indicates whether the values in each row of the column must be unique.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if the value must be unique; otherwise, false. The default is false. |

### getExpression() {#getExpression--}
```
public final String getExpression()
```


Gets the expression used to filter rows, calculate the values in a column, or create an aggregate column.

**Returns:**
java.lang.String - An expression to calculate the value of a column, or create an aggregate column. The return type of an expression is determined by the [getDataType()](../../com.groupdocs.assembly.system.data/datacolumn\#getDataType--) / [setDataType(java.lang.Class)](../../com.groupdocs.assembly.system.data/datacolumn\#setDataType-java.lang.Class-) of the column.
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
public final String toString()
```


Gets the [getExpression()](../../com.groupdocs.assembly.system.data/datacolumn\#getExpression--) of the column, if one exists.

**Returns:**
java.lang.String - The [getExpression()](../../com.groupdocs.assembly.system.data/datacolumn\#getExpression--) value, if the property is set; otherwise, the [getColumnName()](../../com.groupdocs.assembly.system.data/datacolumn\#getColumnName--) / [setColumnName(java.lang.String)](../../com.groupdocs.assembly.system.data/datacolumn\#setColumnName-java.lang.String-) property.
