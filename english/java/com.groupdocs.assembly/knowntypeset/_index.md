---
title: KnownTypeSet
second_title: GroupDocs.Assembly for Java API Reference
description: Represents an unordered set that is a collection of unique items containing java.lang.Class objects which fully or partially qualified names can be used within document templates to invoke the corresponding types static members perform type casts etc.
type: docs
weight: 29
url: /java/com.groupdocs.assembly/knowntypeset/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class KnownTypeSet implements Iterable
```

Represents an unordered set (that is, a collection of unique items) containing java.lang.Class objects which fully or partially qualified names can be used within document templates to invoke the corresponding types' static members, perform type casts, etc.
## Methods

| Method | Description |
| --- | --- |
| [add(Class type)](#add-java.lang.Class-) | Adds the specified java.lang.Class object to the set. |
| [remove(Class type)](#remove-java.lang.Class-) | Removes the specified java.lang.Class object from the set. |
| [clear()](#clear--) | Removes all items from the set. |
| [iterator()](#iterator--) | Returns An java.util.Iterator object to iterate over items of the set. |
| [getCount()](#getCount--) | Gets the count of items in the set. |
### add(Class type) {#add-java.lang.Class-}
```
public void add(Class type)
```


Adds the specified java.lang.Class object to the set.

Throws java.lang.IllegalArgumentException in the following cases:

\-  type  is null.

\-  type  represents a void type.

\-  type  represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

\-  type  represents an array type.

\-  type  has been added to the set already.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.Class | A java.lang.Class object to add. |

### remove(Class type) {#remove-java.lang.Class-}
```
public void remove(Class type)
```


Removes the specified java.lang.Class object from the set.

Throws java.lang.IllegalArgumentException if  type  is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.Class | A java.lang.Class object to remove. |

### clear() {#clear--}
```
public void clear()
```


Removes all items from the set.

### iterator() {#iterator--}
```
public Iterator iterator()
```


Returns An java.util.Iterator object to iterate over items of the set.

**Returns:**
java.util.Iterator - An java.util.Iterator object to iterate over items of the set.
### getCount() {#getCount--}
```
public int getCount()
```


Gets the count of items in the set.

**Returns:**
int - The count of items in the set.
