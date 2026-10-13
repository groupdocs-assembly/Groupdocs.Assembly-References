---
title: FolderFontSource
second_title: GroupDocs.Assembly for Java API Reference
description: Represents the folder that contains TrueType fonts.
type: docs
weight: 26
url: /java/com.groupdocs.assembly/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.IFontSource
```
public final class FolderFontSource implements IFontSource
```

Represents the folder that contains TrueType fonts.

## Constructors

| Constructor | Description |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.assembly.SearchOption-) | Initializes a new instance of the FolderFontSource class.
 |
## Methods

| Method | Description |
| --- | --- |
| [getFolderPath()](#getFolderPath--) | Gets the folder path.
 |
| [getSearchOption()](#getSearchOption--) | Gets the search option (SearchOption value).
 |
| [isRecursive()](#isRecursive--) | Returns true if subdirectories should be included.
 |
| [getPriorityInternal()](#getPriorityInternal--) |  |
| [getFontDataInternal()](#getFontDataInternal--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [toString()](#toString--) |  |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.assembly.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Initializes a new instance of the FolderFontSource class.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderPath | java.lang.String | Path to the folder that contains TrueType fonts.
 |
| searchOption | [SearchOption](../../com.groupdocs.assembly/searchoption) | One of SearchOption.TOP_DIRECTORY_ONLY or SearchOption.ALL_DIRECTORIES.
 |

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Gets the folder path.


**Returns:**
java.lang.String
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Gets the search option (SearchOption value).


**Returns:**
[SearchOption](../../com.groupdocs.assembly/searchoption)
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Returns true if subdirectories should be included.


**Returns:**
boolean
### getPriorityInternal() {#getPriorityInternal--}
```
public int getPriorityInternal()
```




**Returns:**
int
### getFontDataInternal() {#getFontDataInternal--}
```
public Iterable<IFontData> getFontDataInternal()
```




**Returns:**
java.lang.Iterable<com.aspose.IFontData>
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
