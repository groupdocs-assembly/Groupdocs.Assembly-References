---
title: DocumentAssemblyOptions
second_title: GroupDocs.Assembly for Java API Reference
description: A utility class providing constants.
type: docs
weight: 15
url: /java/com.groupdocs.assembly/documentassemblyoptions/
---
**Inheritance:**
java.lang.Object
```
public final class DocumentAssemblyOptions
```

A utility class providing constants. Specifies options controlling behavior of com.groupdocs.assembly.DocumentAssembler while assembling a document.
## Fields

| Field | Description |
| --- | --- |
| [NONE](#NONE) | Specifies default options. |
| [ALLOW_MISSING_MEMBERS](#ALLOW-MISSING-MEMBERS) | Specifies that missing object members should be treated as null literals by the assembler. |
| [UPDATE_FIELDS_AND_FORMULAS](#UPDATE-FIELDS-AND-FORMULAS) | Specifies that fields of result Word Processing documents and formulas of result Spreadsheet documents should be updated by the assembler. |
| [REMOVE_EMPTY_PARAGRAPHS](#REMOVE-EMPTY-PARAGRAPHS) | Specifies that the assembler should remove paragraphs becoming empty after template syntax tags are removed or replaced with empty values. |
| [INLINE_ERROR_MESSAGES](#INLINE-ERROR-MESSAGES) | Specifies that the assembler should inline template syntax error messages into output documents. |
| [length](#length) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName(int documentAssemblyOptions)](#getName-int-) |  |
| [getNames(int documentAssemblyOptions)](#getNames-int-) |  |
| [toString(int documentAssemblyOptions)](#toString-int-) |  |
| [fromName(String documentAssemblyOptionsName)](#fromName-java.lang.String-) |  |
| [fromNames(Set documentAssemblyOptionsNames)](#fromNames-java.util.Set-) |  |
| [getValues()](#getValues--) |  |
### NONE {#NONE}
```
public static final int NONE
```


Specifies default options.

### ALLOW_MISSING_MEMBERS {#ALLOW-MISSING-MEMBERS}
```
public static final int ALLOW_MISSING_MEMBERS
```


Specifies that missing object members should be treated as null literals by the assembler. This option affects only access to instance (that is, non-static) object members and extension methods. If this option is not set, the assembler throws an exception when encounters a missing object member.

### UPDATE_FIELDS_AND_FORMULAS {#UPDATE-FIELDS-AND-FORMULAS}
```
public static final int UPDATE_FIELDS_AND_FORMULAS
```


Specifies that fields of result Word Processing documents and formulas of result Spreadsheet documents should be updated by the assembler.

### REMOVE_EMPTY_PARAGRAPHS {#REMOVE-EMPTY-PARAGRAPHS}
```
public static final int REMOVE_EMPTY_PARAGRAPHS
```


Specifies that the assembler should remove paragraphs becoming empty after template syntax tags are removed or replaced with empty values. At the moment, this option is supported only for templates of Word Processing, Presentation, and Email file formats.

### INLINE_ERROR_MESSAGES {#INLINE-ERROR-MESSAGES}
```
public static final int INLINE_ERROR_MESSAGES
```


Specifies that the assembler should inline template syntax error messages into output documents. If this option is not set, the assembler throws an exception when encounters a syntax error.

### length {#length}
```
public static final int length
```


### getName(int documentAssemblyOptions) {#getName-int-}
```
public static String getName(int documentAssemblyOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentAssemblyOptions | int |  |

**Returns:**
java.lang.String
### getNames(int documentAssemblyOptions) {#getNames-int-}
```
public static Set getNames(int documentAssemblyOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentAssemblyOptions | int |  |

**Returns:**
java.util.Set
### toString(int documentAssemblyOptions) {#toString-int-}
```
public static String toString(int documentAssemblyOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentAssemblyOptions | int |  |

**Returns:**
java.lang.String
### fromName(String documentAssemblyOptionsName) {#fromName-java.lang.String-}
```
public static int fromName(String documentAssemblyOptionsName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentAssemblyOptionsName | java.lang.String |  |

**Returns:**
int
### fromNames(Set documentAssemblyOptionsNames) {#fromNames-java.util.Set-}
```
public static int fromNames(Set documentAssemblyOptionsNames)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentAssemblyOptionsNames | java.util.Set |  |

**Returns:**
int
### getValues() {#getValues--}
```
public static int[] getValues()
```




**Returns:**
int[]
