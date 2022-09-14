---
title: CsvDataLoadOptions
second_title: GroupDocs.Assembly for Java API Reference
description: Represents options for parsing CSV data.
type: docs
weight: 11
url: /java/com.groupdocs.assembly/csvdataloadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CsvDataLoadOptions
```

Represents options for parsing CSV data. An instance of this class can be passed into constructors of com.groupdocs.assembly.CsvDataSource.
## Constructors

| Constructor | Description |
| --- | --- |
| [CsvDataLoadOptions()](#CsvDataLoadOptions--) | Initializes a new instance of this class with default options. |
| [CsvDataLoadOptions(boolean hasHeaders)](#CsvDataLoadOptions-boolean-) | Initializes a new instance of this class with specifying whether CSV data contains column names at the first line. |
## Methods

| Method | Description |
| --- | --- |
| [hasHeaders()](#hasHeaders--) | Gets a value indicating whether the first line of CSV data contains column names. |
| [hasHeaders(boolean value)](#hasHeaders-boolean-) | Sets a value indicating whether the first line of CSV data contains column names. |
| [getDelimiter()](#getDelimiter--) | Gets the character to be used as a column delimiter. |
| [setDelimiter(char value)](#setDelimiter-char-) | Sets the character to be used as a column delimiter. |
| [getQuoteChar()](#getQuoteChar--) | Gets the character that is used to quote field values. |
| [setQuoteChar(char value)](#setQuoteChar-char-) | Sets the character that is used to quote field values. |
| [getCommentChar()](#getCommentChar--) | Gets the character that is used to comment lines of CSV data. |
| [setCommentChar(char value)](#setCommentChar-char-) | Sets the character that is used to comment lines of CSV data. |
### CsvDataLoadOptions() {#CsvDataLoadOptions--}
```
public CsvDataLoadOptions()
```


Initializes a new instance of this class with default options.

### CsvDataLoadOptions(boolean hasHeaders) {#CsvDataLoadOptions-boolean-}
```
public CsvDataLoadOptions(boolean hasHeaders)
```


Initializes a new instance of this class with specifying whether CSV data contains column names at the first line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hasHeaders | boolean |  |

### hasHeaders() {#hasHeaders--}
```
public boolean hasHeaders()
```


Gets a value indicating whether the first line of CSV data contains column names. The default value is **false**.

**Returns:**
boolean - A value indicating whether the first line of CSV data contains column names.
### hasHeaders(boolean value) {#hasHeaders-boolean-}
```
public void hasHeaders(boolean value)
```


Sets a value indicating whether the first line of CSV data contains column names. The default value is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A value indicating whether the first line of CSV data contains column names. |

### getDelimiter() {#getDelimiter--}
```
public char getDelimiter()
```


Gets the character to be used as a column delimiter. The default value is ',' (comma).

**Returns:**
char - The character to be used as a column delimiter.
### setDelimiter(char value) {#setDelimiter-char-}
```
public void setDelimiter(char value)
```


Sets the character to be used as a column delimiter. The default value is ',' (comma).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char | The character to be used as a column delimiter. |

### getQuoteChar() {#getQuoteChar--}
```
public char getQuoteChar()
```


Gets the character that is used to quote field values.

The default value is '"' (quotation mark).

Double the character to place it into quoted text.

**Returns:**
char - The character that is used to quote field values.
### setQuoteChar(char value) {#setQuoteChar-char-}
```
public void setQuoteChar(char value)
```


Sets the character that is used to quote field values.

The default value is '"' (quotation mark).

Double the character to place it into quoted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char | The character that is used to quote field values. |

### getCommentChar() {#getCommentChar--}
```
public char getCommentChar()
```


Gets the character that is used to comment lines of CSV data. The default value is '\#' (number sign).

**Returns:**
char - The character that is used to comment lines of CSV data.
### setCommentChar(char value) {#setCommentChar-char-}
```
public void setCommentChar(char value)
```


Sets the character that is used to comment lines of CSV data. The default value is '\#' (number sign).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char | The character that is used to comment lines of CSV data. |

