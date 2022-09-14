---
title: XmlDataLoadOptions
second_title: GroupDocs.Assembly for Java API Reference
description: Represents options for XML data loading.
type: docs
weight: 33
url: /java/com.groupdocs.assembly/xmldataloadoptions/
---
**Inheritance:**
java.lang.Object
```
public class XmlDataLoadOptions
```

Represents options for XML data loading. An instance of this class can be passed into constructors of com.groupdocs.assembly.XmlDataSource.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmlDataLoadOptions()](#XmlDataLoadOptions--) | Initializes a new instance of this class with default options. |
## Methods

| Method | Description |
| --- | --- |
| [getAlwaysGenerateRootObject()](#getAlwaysGenerateRootObject--) | Gets a flag indicating whether a generated data source will always contain an object for an XML root element. |
| [setAlwaysGenerateRootObject(boolean value)](#setAlwaysGenerateRootObject-boolean-) | Sets a flag indicating whether a generated data source will always contain an object for an XML root element. |
### XmlDataLoadOptions() {#XmlDataLoadOptions--}
```
public XmlDataLoadOptions()
```


Initializes a new instance of this class with default options.

### getAlwaysGenerateRootObject() {#getAlwaysGenerateRootObject--}
```
public boolean getAlwaysGenerateRootObject()
```


Gets a flag indicating whether a generated data source will always contain an object for an XML root element. If an XML root element has no attributes and all its child elements have same names, such an object is not created by default. The default value is **false**.

**Returns:**
boolean - A flag indicating whether a generated data source will always contain an object for an XML root element.
### setAlwaysGenerateRootObject(boolean value) {#setAlwaysGenerateRootObject-boolean-}
```
public void setAlwaysGenerateRootObject(boolean value)
```


Sets a flag indicating whether a generated data source will always contain an object for an XML root element. If an XML root element has no attributes and all its child elements have same names, such an object is not created by default. The default value is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A flag indicating whether a generated data source will always contain an object for an XML root element. |

