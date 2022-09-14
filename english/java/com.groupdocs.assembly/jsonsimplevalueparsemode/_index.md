---
title: JsonSimpleValueParseMode
second_title: GroupDocs.Assembly for Java API Reference
description: A utility class providing constants.
type: docs
weight: 28
url: /java/com.groupdocs.assembly/jsonsimplevalueparsemode/
---
**Inheritance:**
java.lang.Object
```
public final class JsonSimpleValueParseMode
```

A utility class providing constants. Specifies a mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. Such a mode does not affect parsing of date-time values.
## Fields

| Field | Description |
| --- | --- |
| [LOOSE](#LOOSE) | Specifies the mode where types of JSON simple values are determined upon parsing of their string representations. |
| [STRICT](#STRICT) | Specifies the mode where types of JSON simple values are determined from JSON notation itself. |
| [length](#length) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName(int jsonSimpleValueParseMode)](#getName-int-) |  |
| [toString(int jsonSimpleValueParseMode)](#toString-int-) |  |
| [fromName(String jsonSimpleValueParseModeName)](#fromName-java.lang.String-) |  |
| [getValues()](#getValues--) |  |
### LOOSE {#LOOSE}
```
public static final int LOOSE
```


Specifies the mode where types of JSON simple values are determined upon parsing of their string representations. For example, the type of 'prop' from the JSON snippet '\{ prop: "123" \}' is determined as integer in this mode.

### STRICT {#STRICT}
```
public static final int STRICT
```


Specifies the mode where types of JSON simple values are determined from JSON notation itself. For example, the type of 'prop' from the JSON snippet '\{ prop: "123" \}' is determined as string in this mode.

### length {#length}
```
public static final int length
```


### getName(int jsonSimpleValueParseMode) {#getName-int-}
```
public static String getName(int jsonSimpleValueParseMode)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jsonSimpleValueParseMode | int |  |

**Returns:**
java.lang.String
### toString(int jsonSimpleValueParseMode) {#toString-int-}
```
public static String toString(int jsonSimpleValueParseMode)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jsonSimpleValueParseMode | int |  |

**Returns:**
java.lang.String
### fromName(String jsonSimpleValueParseModeName) {#fromName-java.lang.String-}
```
public static int fromName(String jsonSimpleValueParseModeName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jsonSimpleValueParseModeName | java.lang.String |  |

**Returns:**
int
### getValues() {#getValues--}
```
public static int[] getValues()
```




**Returns:**
int[]
