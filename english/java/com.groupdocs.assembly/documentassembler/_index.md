---
title: DocumentAssembler
second_title: GroupDocs.Assembly for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.groupdocs.assembly/documentassembler/
---
**Inheritance:**
java.lang.Object
```
public class DocumentAssembler
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentAssembler()](#DocumentAssembler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [assembleDocument(String sourcePath, String targetPath, DataSourceInfo[] dataSourceInfos)](#assembleDocument-java.lang.String-java.lang.String-com.groupdocs.assembly.DataSourceInfo...-) |  |
| [assembleDocument(String sourcePath, String targetPath, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos)](#assembleDocument-java.lang.String-java.lang.String-com.groupdocs.assembly.LoadSaveOptions-com.groupdocs.assembly.DataSourceInfo...-) |  |
| [assembleDocument(InputStream sourceStream, OutputStream targetStream, DataSourceInfo[] dataSourceInfos)](#assembleDocument-java.io.InputStream-java.io.OutputStream-com.groupdocs.assembly.DataSourceInfo...-) |  |
| [assembleDocument(InputStream sourceStream, OutputStream targetStream, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos)](#assembleDocument-java.io.InputStream-java.io.OutputStream-com.groupdocs.assembly.LoadSaveOptions-com.groupdocs.assembly.DataSourceInfo...-) |  |
| [getOptions()](#getOptions--) |  |
| [setOptions(int value)](#setOptions-int-) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) |  |
| [getKnownTypes()](#getKnownTypes--) |  |
| [getUseReflectionOptimization()](#getUseReflectionOptimization--) |  |
| [setUseReflectionOptimization(boolean value)](#setUseReflectionOptimization-boolean-) |  |
### DocumentAssembler() {#DocumentAssembler--}
```
public DocumentAssembler()
```


### assembleDocument(String sourcePath, String targetPath, DataSourceInfo[] dataSourceInfos) {#assembleDocument-java.lang.String-java.lang.String-com.groupdocs.assembly.DataSourceInfo...-}
```
public boolean assembleDocument(String sourcePath, String targetPath, DataSourceInfo[] dataSourceInfos)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | java.lang.String |  |
| targetPath | java.lang.String |  |
| dataSourceInfos | [DataSourceInfo\[\]](../../com.groupdocs.assembly/datasourceinfo) |  |

**Returns:**
boolean
### assembleDocument(String sourcePath, String targetPath, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos) {#assembleDocument-java.lang.String-java.lang.String-com.groupdocs.assembly.LoadSaveOptions-com.groupdocs.assembly.DataSourceInfo...-}
```
public boolean assembleDocument(String sourcePath, String targetPath, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | java.lang.String |  |
| targetPath | java.lang.String |  |
| loadSaveOptions | [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions) |  |
| dataSourceInfos | [DataSourceInfo\[\]](../../com.groupdocs.assembly/datasourceinfo) |  |

**Returns:**
boolean
### assembleDocument(InputStream sourceStream, OutputStream targetStream, DataSourceInfo[] dataSourceInfos) {#assembleDocument-java.io.InputStream-java.io.OutputStream-com.groupdocs.assembly.DataSourceInfo...-}
```
public boolean assembleDocument(InputStream sourceStream, OutputStream targetStream, DataSourceInfo[] dataSourceInfos)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | java.io.InputStream |  |
| targetStream | java.io.OutputStream |  |
| dataSourceInfos | [DataSourceInfo\[\]](../../com.groupdocs.assembly/datasourceinfo) |  |

**Returns:**
boolean
### assembleDocument(InputStream sourceStream, OutputStream targetStream, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos) {#assembleDocument-java.io.InputStream-java.io.OutputStream-com.groupdocs.assembly.LoadSaveOptions-com.groupdocs.assembly.DataSourceInfo...-}
```
public boolean assembleDocument(InputStream sourceStream, OutputStream targetStream, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | java.io.InputStream |  |
| targetStream | java.io.OutputStream |  |
| loadSaveOptions | [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions) |  |
| dataSourceInfos | [DataSourceInfo\[\]](../../com.groupdocs.assembly/datasourceinfo) |  |

**Returns:**
boolean
### getOptions() {#getOptions--}
```
public int getOptions()
```




**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```




**Returns:**
[BarcodeSettings](../../com.groupdocs.assembly/barcodesettings)
### getKnownTypes() {#getKnownTypes--}
```
public KnownTypeSet getKnownTypes()
```




**Returns:**
[KnownTypeSet](../../com.groupdocs.assembly/knowntypeset)
### getUseReflectionOptimization() {#getUseReflectionOptimization--}
```
public static boolean getUseReflectionOptimization()
```




**Returns:**
boolean
### setUseReflectionOptimization(boolean value) {#setUseReflectionOptimization-boolean-}
```
public static void setUseReflectionOptimization(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

