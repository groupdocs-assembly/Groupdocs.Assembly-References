---
title: License
second_title: GroupDocs.Assembly for Java API Reference
description: Provides methods to license the component.
type: docs
weight: 30
url: /java/com.groupdocs.assembly/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Provides methods to license the component.
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenses the component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [isLicensed()](#isLicensed--) | Returns true if a valid license has been applied; false if the component is running in evaluation mode. |
### License() {#License--}
```
public License()
```


Initializes a new instance of this class.

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licenses the component.

Tries to find the license in the following locations:

1. Explicit path.

2. The folder that contains the GroupDocs component JAR file.

3. The folder that contains the client's calling JAR file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Can be a full or short file name. Use an empty string to switch to evaluation mode. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licenses the component.

Use this method to load a license from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream that contains the license. |

### isLicensed() {#isLicensed--}
```
public boolean isLicensed()
```


Returns true if a valid license has been applied; false if the component is running in evaluation mode.

**Returns:**
boolean - True if a valid license has been applied; false if the component is running in evaluation mode.
