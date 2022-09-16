---
title: JsonDataLoadOptions
second_title: GroupDocs.Assembly for Java API Reference
description: Represents options for parsing JSON data.
type: docs
weight: 26
url: /java/com.groupdocs.assembly/jsondataloadoptions/
---
**Inheritance:**
java.lang.Object
```
public class JsonDataLoadOptions
```

Represents options for parsing JSON data. An instance of this class can be passed into constructors of [JsonDataSource](../../com.groupdocs.assembly/jsondatasource).
## Constructors

| Constructor | Description |
| --- | --- |
| [JsonDataLoadOptions()](#JsonDataLoadOptions--) | Initializes a new instance of this class with default options. |
## Methods

| Method | Description |
| --- | --- |
| [getSimpleValueParseMode()](#getSimpleValueParseMode--) | Gets a mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. |
| [setSimpleValueParseMode(int value)](#setSimpleValueParseMode-int-) | Sets a mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. |
| [getExactDateTimeParseFormat()](#getExactDateTimeParseFormat--) | Gets an exact format for parsing JSON date-time values while loading JSON. |
| [setExactDateTimeParseFormat(String value)](#setExactDateTimeParseFormat-java.lang.String-) | Sets an exact format for parsing JSON date-time values while loading JSON. |
| [getExactDateTimeParseFormats()](#getExactDateTimeParseFormats--) | Gets exact formats for parsing JSON date-time values while loading JSON. |
| [setExactDateTimeParseFormats(Iterable value)](#setExactDateTimeParseFormats-java.lang.Iterable-) | Sets exact formats for parsing JSON date-time values while loading JSON. |
| [getAlwaysGenerateRootObject()](#getAlwaysGenerateRootObject--) | Gets a flag indicating whether a generated data source will always contain an object for a JSON root element. |
| [setAlwaysGenerateRootObject(boolean value)](#setAlwaysGenerateRootObject-boolean-) | Sets a flag indicating whether a generated data source will always contain an object for a JSON root element. |
### JsonDataLoadOptions() {#JsonDataLoadOptions--}
```
public JsonDataLoadOptions()
```


Initializes a new instance of this class with default options.

### getSimpleValueParseMode() {#getSimpleValueParseMode--}
```
public int getSimpleValueParseMode()
```


Gets a mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. Such a mode does not affect parsing of date-time values. The default is [JsonSimpleValueParseMode\#LOOSE](../../com.groupdocs.assembly/jsonsimplevalueparsemode\#LOOSE).

**Returns:**
int - A mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. The returned value is one of [JsonSimpleValueParseMode](../../com.groupdocs.assembly/jsonsimplevalueparsemode) constants.
### setSimpleValueParseMode(int value) {#setSimpleValueParseMode-int-}
```
public void setSimpleValueParseMode(int value)
```


Sets a mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. Such a mode does not affect parsing of date-time values. The default is [JsonSimpleValueParseMode\#LOOSE](../../com.groupdocs.assembly/jsonsimplevalueparsemode\#LOOSE).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. The value must be one of [JsonSimpleValueParseMode](../../com.groupdocs.assembly/jsonsimplevalueparsemode) constants. |

### getExactDateTimeParseFormat() {#getExactDateTimeParseFormat--}
```
public String getExactDateTimeParseFormat()
```


Gets an exact format for parsing JSON date-time values while loading JSON. The default is **null**.

Strings encoded using Microsoft® JSON date-time format (for example, "/Date(1224043200000)/") are always recognized as date-time values regardless of a value of this property. The property defines additional formats to be used while parsing date-time values from strings in the following way:

 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormat--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormat--) / [JsonDataLoadOptions\#setExactDateTimeParseFormat-java.lang.String-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormat-java.lang.String-) is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormat--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormat--) / [JsonDataLoadOptions\#setExactDateTimeParseFormat-java.lang.String-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormat-java.lang.String-) is a non-empty string, it is used as a single additional date-time format utilizing the current culture.
 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormat--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormat--) / [JsonDataLoadOptions\#setExactDateTimeParseFormat-java.lang.String-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormat-java.lang.String-) is an empty string, no additional date-time formats are used.

**Returns:**
java.lang.String - An exact format for parsing JSON date-time values while loading JSON.
### setExactDateTimeParseFormat(String value) {#setExactDateTimeParseFormat-java.lang.String-}
```
public void setExactDateTimeParseFormat(String value)
```


Sets an exact format for parsing JSON date-time values while loading JSON. The default is **null**.

Strings encoded using Microsoft® JSON date-time format (for example, "/Date(1224043200000)/") are always recognized as date-time values regardless of a value of this property. The property defines additional formats to be used while parsing date-time values from strings in the following way:

 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormat--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormat--) / [JsonDataLoadOptions\#setExactDateTimeParseFormat-java.lang.String-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormat-java.lang.String-) is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormat--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormat--) / [JsonDataLoadOptions\#setExactDateTimeParseFormat-java.lang.String-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormat-java.lang.String-) is a non-empty string, it is used as a single additional date-time format utilizing the current culture.
 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormat--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormat--) / [JsonDataLoadOptions\#setExactDateTimeParseFormat-java.lang.String-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormat-java.lang.String-) is an empty string, no additional date-time formats are used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An exact format for parsing JSON date-time values while loading JSON. |

### getExactDateTimeParseFormats() {#getExactDateTimeParseFormats--}
```
public Iterable getExactDateTimeParseFormats()
```


Gets exact formats for parsing JSON date-time values while loading JSON. The default is **null**.

Strings encoded using Microsoft® JSON date-time format (for example, "/Date(1224043200000)/") are always recognized as date-time values regardless of a value of this property. The property defines additional formats to be used while parsing date-time values from strings in the following way:

 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormats--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormats--) / [JsonDataLoadOptions\#setExactDateTimeParseFormats-java.lang.Iterable-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormats-java.lang.Iterable-) is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormats--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormats--) / [JsonDataLoadOptions\#setExactDateTimeParseFormats-java.lang.Iterable-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormats-java.lang.Iterable-) contains strings, they are used as additional date-time formats utilizing the current culture.
 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormats--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormats--) / [JsonDataLoadOptions\#setExactDateTimeParseFormats-java.lang.Iterable-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormats-java.lang.Iterable-) is empty, no additional date-time formats are used.

**Returns:**
java.lang.Iterable - Exact formats for parsing JSON date-time values while loading JSON.
### setExactDateTimeParseFormats(Iterable value) {#setExactDateTimeParseFormats-java.lang.Iterable-}
```
public void setExactDateTimeParseFormats(Iterable value)
```


Sets exact formats for parsing JSON date-time values while loading JSON. The default is **null**.

Strings encoded using Microsoft® JSON date-time format (for example, "/Date(1224043200000)/") are always recognized as date-time values regardless of a value of this property. The property defines additional formats to be used while parsing date-time values from strings in the following way:

 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormats--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormats--) / [JsonDataLoadOptions\#setExactDateTimeParseFormats-java.lang.Iterable-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormats-java.lang.Iterable-) is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormats--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormats--) / [JsonDataLoadOptions\#setExactDateTimeParseFormats-java.lang.Iterable-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormats-java.lang.Iterable-) contains strings, they are used as additional date-time formats utilizing the current culture.
 *  When [JsonDataLoadOptions\#getExactDateTimeParseFormats--](../../com.groupdocs.assembly/jsondataloadoptions\#getExactDateTimeParseFormats--) / [JsonDataLoadOptions\#setExactDateTimeParseFormats-java.lang.Iterable-](../../com.groupdocs.assembly/jsondataloadoptions\#setExactDateTimeParseFormats-java.lang.Iterable-) is empty, no additional date-time formats are used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Iterable | Exact formats for parsing JSON date-time values while loading JSON. |

### getAlwaysGenerateRootObject() {#getAlwaysGenerateRootObject--}
```
public boolean getAlwaysGenerateRootObject()
```


Gets a flag indicating whether a generated data source will always contain an object for a JSON root element. If a JSON root element contains a single complex property, such an object is not created by default. The default value is **false**.

**Returns:**
boolean - A flag indicating whether a generated data source will always contain an object for a JSON root element.
### setAlwaysGenerateRootObject(boolean value) {#setAlwaysGenerateRootObject-boolean-}
```
public void setAlwaysGenerateRootObject(boolean value)
```


Sets a flag indicating whether a generated data source will always contain an object for a JSON root element. If a JSON root element contains a single complex property, such an object is not created by default. The default value is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A flag indicating whether a generated data source will always contain an object for a JSON root element. |

