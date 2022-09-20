---
title: DocumentAssembler
second_title: GroupDocs.Assembly for Java API Reference
description: Provides routines to populate template documents with data and a set of settings to control these routines.
type: docs
weight: 14
url: /java/com.groupdocs.assembly/documentassembler/
---
**Inheritance:**
java.lang.Object
```
public class DocumentAssembler
```

Provides routines to populate template documents with data and a set of settings to control these routines.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentAssembler()](#DocumentAssembler--) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [assembleDocument(String sourcePath, String targetPath, DataSourceInfo[] dataSourceInfos)](#assembleDocument-java.lang.String-java.lang.String-com.groupdocs.assembly.DataSourceInfo...-) | Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path using default [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions). |
| [assembleDocument(String sourcePath, String targetPath, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos)](#assembleDocument-java.lang.String-java.lang.String-com.groupdocs.assembly.LoadSaveOptions-com.groupdocs.assembly.DataSourceInfo...-) | Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path using the given [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions). |
| [assembleDocument(InputStream sourceStream, OutputStream targetStream, DataSourceInfo[] dataSourceInfos)](#assembleDocument-java.io.InputStream-java.io.OutputStream-com.groupdocs.assembly.DataSourceInfo...-) | Loads a template document from the specified source stream, populates the template document with data from the specified single or multiple sources, and stores the result document to the target stream using default [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions). |
| [assembleDocument(InputStream sourceStream, OutputStream targetStream, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos)](#assembleDocument-java.io.InputStream-java.io.OutputStream-com.groupdocs.assembly.LoadSaveOptions-com.groupdocs.assembly.DataSourceInfo...-) | Loads a template document from the specified source stream, populates the template document with data from the specified single or multiple sources, and stores the result document to the target stream using the given [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions). |
| [getOptions()](#getOptions--) | Gets a set of flags controlling behavior of this [DocumentAssembler](../../com.groupdocs.assembly/documentassembler) instance while assembling a document. |
| [setOptions(int value)](#setOptions-int-) | Sets a set of flags controlling behavior of this [DocumentAssembler](../../com.groupdocs.assembly/documentassembler) instance while assembling a document. |
| [getBarcodeSettings()](#getBarcodeSettings--) | Gets a set of settings controlling barcode generation while assembling a document. |
| [getKnownTypes()](#getKnownTypes--) | Gets an unordered set (that is, a collection of unique items) containing java.lang.Class objects which fully or partially qualified names can be used within document templates processed by this assembler instance to invoke the corresponding types' static members, perform type casts, etc. |
| [getUseReflectionOptimization()](#getUseReflectionOptimization--) | Gets a value indicating whether invocations of custom type members performed via reflection API are optimized using dynamic class generation or not. |
| [setUseReflectionOptimization(boolean value)](#setUseReflectionOptimization-boolean-) | Sets a value indicating whether invocations of custom type members performed via reflection API are optimized using dynamic class generation or not. |
### DocumentAssembler() {#DocumentAssembler--}
```
public DocumentAssembler()
```


Initializes a new instance of this class.

### assembleDocument(String sourcePath, String targetPath, DataSourceInfo[] dataSourceInfos) {#assembleDocument-java.lang.String-java.lang.String-com.groupdocs.assembly.DataSourceInfo...-}
```
public boolean assembleDocument(String sourcePath, String targetPath, DataSourceInfo[] dataSourceInfos)
```


Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path using default [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | java.lang.String | The path to a template document to be populated with data. |
| targetPath | java.lang.String | The path to a result document. |
| dataSourceInfos | [DataSourceInfo\[\]](../../com.groupdocs.assembly/datasourceinfo) | Provides information on data source objects to be used. |

**Returns:**
boolean - A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the [getOptions()](../../com.groupdocs.assembly/documentassembler.getOptions--) / [setOptions(int)](../../com.groupdocs.assembly/documentassembler.setOptions-int-) property includes the [DocumentAssemblyOptions.INLINE\_ERROR\_MESSAGES](../../com.groupdocs.assembly/documentassemblyoptions.INLINE-ERROR-MESSAGES) option.
### assembleDocument(String sourcePath, String targetPath, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos) {#assembleDocument-java.lang.String-java.lang.String-com.groupdocs.assembly.LoadSaveOptions-com.groupdocs.assembly.DataSourceInfo...-}
```
public boolean assembleDocument(String sourcePath, String targetPath, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos)
```


Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path using the given [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | java.lang.String | The path to a template document to be populated with data. |
| targetPath | java.lang.String | The path to a result document. |
| loadSaveOptions | [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions) | Specifies additional options for document loading and saving. |
| dataSourceInfos | [DataSourceInfo\[\]](../../com.groupdocs.assembly/datasourceinfo) | Provides information on data source objects to be used. |

**Returns:**
boolean - A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the [getOptions()](../../com.groupdocs.assembly/documentassembler.getOptions--) / [setOptions(int)](../../com.groupdocs.assembly/documentassembler.setOptions-int-) property includes the [DocumentAssemblyOptions.INLINE\_ERROR\_MESSAGES](../../com.groupdocs.assembly/documentassemblyoptions.INLINE-ERROR-MESSAGES) option.
### assembleDocument(InputStream sourceStream, OutputStream targetStream, DataSourceInfo[] dataSourceInfos) {#assembleDocument-java.io.InputStream-java.io.OutputStream-com.groupdocs.assembly.DataSourceInfo...-}
```
public boolean assembleDocument(InputStream sourceStream, OutputStream targetStream, DataSourceInfo[] dataSourceInfos)
```


Loads a template document from the specified source stream, populates the template document with data from the specified single or multiple sources, and stores the result document to the target stream using default [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | java.io.InputStream | The stream to read a template document from. |
| targetStream | java.io.OutputStream | The stream to write a result document. |
| dataSourceInfos | [DataSourceInfo\[\]](../../com.groupdocs.assembly/datasourceinfo) | Provides information on data source objects to be used. |

**Returns:**
boolean - A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the [getOptions()](../../com.groupdocs.assembly/documentassembler.getOptions--) / [setOptions(int)](../../com.groupdocs.assembly/documentassembler.setOptions-int-) property includes the [DocumentAssemblyOptions.INLINE\_ERROR\_MESSAGES](../../com.groupdocs.assembly/documentassemblyoptions.INLINE-ERROR-MESSAGES) option.
### assembleDocument(InputStream sourceStream, OutputStream targetStream, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos) {#assembleDocument-java.io.InputStream-java.io.OutputStream-com.groupdocs.assembly.LoadSaveOptions-com.groupdocs.assembly.DataSourceInfo...-}
```
public boolean assembleDocument(InputStream sourceStream, OutputStream targetStream, LoadSaveOptions loadSaveOptions, DataSourceInfo[] dataSourceInfos)
```


Loads a template document from the specified source stream, populates the template document with data from the specified single or multiple sources, and stores the result document to the target stream using the given [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | java.io.InputStream | The stream to read a template document from. |
| targetStream | java.io.OutputStream | The stream to write a result document. |
| loadSaveOptions | [LoadSaveOptions](../../com.groupdocs.assembly/loadsaveoptions) | Specifies additional options for document loading and saving. |
| dataSourceInfos | [DataSourceInfo\[\]](../../com.groupdocs.assembly/datasourceinfo) | Provides information on data source objects to be used. |

**Returns:**
boolean - A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the [getOptions()](../../com.groupdocs.assembly/documentassembler.getOptions--) / [setOptions(int)](../../com.groupdocs.assembly/documentassembler.setOptions-int-) property includes the [DocumentAssemblyOptions.INLINE\_ERROR\_MESSAGES](../../com.groupdocs.assembly/documentassemblyoptions.INLINE-ERROR-MESSAGES) option.
### getOptions() {#getOptions--}
```
public int getOptions()
```


Gets a set of flags controlling behavior of this [DocumentAssembler](../../com.groupdocs.assembly/documentassembler) instance while assembling a document.

**Returns:**
int - A set of flags controlling behavior of this [DocumentAssembler](../../com.groupdocs.assembly/documentassembler) instance while assembling a document. The returned value is a bitwise combination of [DocumentAssemblyOptions](../../com.groupdocs.assembly/documentassemblyoptions) constants.
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Sets a set of flags controlling behavior of this [DocumentAssembler](../../com.groupdocs.assembly/documentassembler) instance while assembling a document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A set of flags controlling behavior of this [DocumentAssembler](../../com.groupdocs.assembly/documentassembler) instance while assembling a document. The value must be a bitwise combination of [DocumentAssemblyOptions](../../com.groupdocs.assembly/documentassemblyoptions) constants. |

### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


Gets a set of settings controlling barcode generation while assembling a document.

**Returns:**
[BarcodeSettings](../../com.groupdocs.assembly/barcodesettings) - A set of settings controlling barcode generation while assembling a document.
### getKnownTypes() {#getKnownTypes--}
```
public KnownTypeSet getKnownTypes()
```


Gets an unordered set (that is, a collection of unique items) containing java.lang.Class objects which fully or partially qualified names can be used within document templates processed by this assembler instance to invoke the corresponding types' static members, perform type casts, etc.

**Returns:**
[KnownTypeSet](../../com.groupdocs.assembly/knowntypeset) - An unordered set (that is, a collection of unique items) containing java.lang.Class objects which fully or partially qualified names can be used within document templates processed by this assembler instance to invoke the corresponding types' static members, perform type casts, etc.
### getUseReflectionOptimization() {#getUseReflectionOptimization--}
```
public static boolean getUseReflectionOptimization()
```


Gets a value indicating whether invocations of custom type members performed via reflection API are optimized using dynamic class generation or not. The default value is true. There are some scenarios where it is preferrable to disable this optimization. For example, if you are dealing with small collections of data items all the time, then an overhead of dynamic class generation can be more noticeable than an overhead of direct reflection API calls.

**Returns:**
boolean - A value indicating whether invocations of custom type members performed via reflection API are optimized using dynamic class generation or not.
### setUseReflectionOptimization(boolean value) {#setUseReflectionOptimization-boolean-}
```
public static void setUseReflectionOptimization(boolean value)
```


Sets a value indicating whether invocations of custom type members performed via reflection API are optimized using dynamic class generation or not. The default value is true. There are some scenarios where it is preferrable to disable this optimization. For example, if you are dealing with small collections of data items all the time, then an overhead of dynamic class generation can be more noticeable than an overhead of direct reflection API calls.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A value indicating whether invocations of custom type members performed via reflection API are optimized using dynamic class generation or not. |

