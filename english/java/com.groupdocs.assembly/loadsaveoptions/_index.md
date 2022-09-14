---
title: LoadSaveOptions
second_title: GroupDocs.Assembly for Java API Reference
description: Specifies additional options for loading and saving of a document to be assembled.
type: docs
weight: 31
url: /java/com.groupdocs.assembly/loadsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadSaveOptions
```

Specifies additional options for loading and saving of a document to be assembled.
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadSaveOptions()](#LoadSaveOptions--) | Creates a new instance of this class without any properties specified. |
| [LoadSaveOptions(int saveFormat)](#LoadSaveOptions-int-) | Creates a new instance of this class with the specified file format to save an assembled document to. |
## Methods

| Method | Description |
| --- | --- |
| [getSaveFormat()](#getSaveFormat--) | Gets a file format to save an assembled document to. |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Sets a file format to save an assembled document to. |
| [getResourceLoadBaseUri()](#getResourceLoadBaseUri--) | Gets a base URI to resolve external resource files' relative URIs to absolute ones while loading an HTML template document to be assembled and saved to a non-HTML format. |
| [setResourceLoadBaseUri(String value)](#setResourceLoadBaseUri-java.lang.String-) | Sets a base URI to resolve external resource files' relative URIs to absolute ones while loading an HTML template document to be assembled and saved to a non-HTML format. |
| [getResourceSaveFolder()](#getResourceSaveFolder--) | Gets a path to a folder to store external resource files while an assembled document loaded from a non-HTML format is being saved to HTML. |
| [setResourceSaveFolder(String value)](#setResourceSaveFolder-java.lang.String-) | Sets a path to a folder to store external resource files while an assembled document loaded from a non-HTML format is being saved to HTML. |
### LoadSaveOptions() {#LoadSaveOptions--}
```
public LoadSaveOptions()
```


Creates a new instance of this class without any properties specified.

### LoadSaveOptions(int saveFormat) {#LoadSaveOptions-int-}
```
public LoadSaveOptions(int saveFormat)
```


Creates a new instance of this class with the specified file format to save an assembled document to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | int | A file format to save an assembled document to. The value must be one of com.groupdocs.assembly.FileFormat constants. |

### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Gets a file format to save an assembled document to. com.groupdocs.assembly.FileFormat\#UNSPECIFIED is the default.

When the value of this property is not specified, com.groupdocs.assembly.DocumentAssembler behaves as follows:

\- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

\- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

Beware that it is not always possible to save an assembled document to any file format using GroupDocs.Assembly. For example, it is impossible to save a document loaded from a Word Processing file format (such as DOCX) to a Spreadsheet file format (such as XLSX). For more information on possible combinations of load and save file formats supported by GroupDocs.Assembly, please check GroupDocs.Assembly online documentation.

**Returns:**
int - A file format to save an assembled document to. The returned value is one of com.groupdocs.assembly.FileFormat constants.
### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Sets a file format to save an assembled document to. com.groupdocs.assembly.FileFormat\#UNSPECIFIED is the default.

When the value of this property is not specified, com.groupdocs.assembly.DocumentAssembler behaves as follows:

\- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

\- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

Beware that it is not always possible to save an assembled document to any file format using GroupDocs.Assembly. For example, it is impossible to save a document loaded from a Word Processing file format (such as DOCX) to a Spreadsheet file format (such as XLSX). For more information on possible combinations of load and save file formats supported by GroupDocs.Assembly, please check GroupDocs.Assembly online documentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A file format to save an assembled document to. The value must be one of com.groupdocs.assembly.FileFormat constants. |

### getResourceLoadBaseUri() {#getResourceLoadBaseUri--}
```
public String getResourceLoadBaseUri()
```


Gets a base URI to resolve external resource files' relative URIs to absolute ones while loading an HTML template document to be assembled and saved to a non-HTML format. The default value is an empty string.

When loading an HTML document from a file, its containing folder is used as a base URI by default, which cannot happen when loading an HTML document from a stream. Set this property to specify a base URI when loading an HTML document from a stream or to override the default base URI when loading an HTML document from a file.

A value of this property is ignored in the following cases:

 *  An HTML document being loaded contains a BASE HTML element providing a base URI.
 *  An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

**Returns:**
java.lang.String - A base URI to resolve external resource files' relative URIs to absolute ones while loading an HTML template document to be assembled and saved to a non-HTML format.
### setResourceLoadBaseUri(String value) {#setResourceLoadBaseUri-java.lang.String-}
```
public void setResourceLoadBaseUri(String value)
```


Sets a base URI to resolve external resource files' relative URIs to absolute ones while loading an HTML template document to be assembled and saved to a non-HTML format. The default value is an empty string.

When loading an HTML document from a file, its containing folder is used as a base URI by default, which cannot happen when loading an HTML document from a stream. Set this property to specify a base URI when loading an HTML document from a stream or to override the default base URI when loading an HTML document from a file.

A value of this property is ignored in the following cases:

 *  An HTML document being loaded contains a BASE HTML element providing a base URI.
 *  An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A base URI to resolve external resource files' relative URIs to absolute ones while loading an HTML template document to be assembled and saved to a non-HTML format. |

### getResourceSaveFolder() {#getResourceSaveFolder--}
```
public String getResourceSaveFolder()
```


Gets a path to a folder to store external resource files while an assembled document loaded from a non-HTML format is being saved to HTML. The default value is an empty string.

By default, when saving an assembled document to an HTML file, external resource files are stored to a folder having the same name as the HTML file without extension plus the "\_files" suffix. This folder is located in the same folder as the HTML file. However, this cannot be done when saving an assembled document to an HTML stream. Set this property to specify a path to a folder to store external resource files when saving an assembled document to an HTML stream or to override the default folder when saving an assembled document to an HTML file.

A value of this property is ignored if an assembled document being saved to HTML was loaded from HTML as well (external resource files are not stored and links to them are not changed then).

**Returns:**
java.lang.String - A path to a folder to store external resource files while an assembled document loaded from a non-HTML format is being saved to HTML.
### setResourceSaveFolder(String value) {#setResourceSaveFolder-java.lang.String-}
```
public void setResourceSaveFolder(String value)
```


Sets a path to a folder to store external resource files while an assembled document loaded from a non-HTML format is being saved to HTML. The default value is an empty string.

By default, when saving an assembled document to an HTML file, external resource files are stored to a folder having the same name as the HTML file without extension plus the "\_files" suffix. This folder is located in the same folder as the HTML file. However, this cannot be done when saving an assembled document to an HTML stream. Set this property to specify a path to a folder to store external resource files when saving an assembled document to an HTML stream or to override the default folder when saving an assembled document to an HTML file.

A value of this property is ignored if an assembled document being saved to HTML was loaded from HTML as well (external resource files are not stored and links to them are not changed then).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A path to a folder to store external resource files while an assembled document loaded from a non-HTML format is being saved to HTML. |

