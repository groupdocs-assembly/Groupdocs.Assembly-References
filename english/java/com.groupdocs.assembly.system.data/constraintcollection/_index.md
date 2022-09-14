---
title: ConstraintCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a collection of constraints for a com.groupdocs.assembly.system.data.DataTable.
type: docs
weight: 11
url: /java/com.groupdocs.assembly.system.data/constraintcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class ConstraintCollection implements Iterable
```

Represents a collection of constraints for a com.groupdocs.assembly.system.data.DataTable.
## Methods

| Method | Description |
| --- | --- |
| [get(String name)](#get-java.lang.String-) | Gets the com.groupdocs.assembly.system.data.Constraint from the collection with the specified name. |
| [get(int index)](#get-int-) | Gets the com.groupdocs.assembly.system.data.Constraint from the collection at the specified index. |
| [add(Constraint constraint)](#add-com.groupdocs.assembly.system.data.Constraint-) | Adds the specified com.groupdocs.assembly.system.data.Constraint object to the collection. |
| [remove(Constraint constraint)](#remove-com.groupdocs.assembly.system.data.Constraint-) | Removes the specified com.groupdocs.assembly.system.data.Constraint from the collection. |
| [contains(Constraint cc)](#contains-com.groupdocs.assembly.system.data.Constraint-) | Indicates whether the Constraint object specified by name exists in the collection. |
| [getCount()](#getCount--) | Gets the total number of elements in a collection. |
| [iterator()](#iterator--) |  |
### get(String name) {#get-java.lang.String-}
```
public final Constraint get(String name)
```


Gets the com.groupdocs.assembly.system.data.Constraint from the collection with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The com.groupdocs.assembly.system.data.Constraint\#getConstraintName() / com.groupdocs.assembly.system.data.Constraint\#setConstraintName(java.lang.String) of the constraint to return. |

**Returns:**
[Constraint](../../com.groupdocs.assembly.system.data/constraint) - The com.groupdocs.assembly.system.data.Constraint with the specified name; otherwise a null value if the com.groupdocs.assembly.system.data.Constraint does not exist.
### get(int index) {#get-int-}
```
public final Constraint get(int index)
```


Gets the com.groupdocs.assembly.system.data.Constraint from the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the constraint to return. |

**Returns:**
[Constraint](../../com.groupdocs.assembly.system.data/constraint) - The com.groupdocs.assembly.system.data.Constraint at the specified index.
### add(Constraint constraint) {#add-com.groupdocs.assembly.system.data.Constraint-}
```
public final void add(Constraint constraint)
```


Adds the specified com.groupdocs.assembly.system.data.Constraint object to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constraint | [Constraint](../../com.groupdocs.assembly.system.data/constraint) | The Constraint to add. |

### remove(Constraint constraint) {#remove-com.groupdocs.assembly.system.data.Constraint-}
```
public final void remove(Constraint constraint)
```


Removes the specified com.groupdocs.assembly.system.data.Constraint from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constraint | [Constraint](../../com.groupdocs.assembly.system.data/constraint) | The com.groupdocs.assembly.system.data.Constraint to remove. |

### contains(Constraint cc) {#contains-com.groupdocs.assembly.system.data.Constraint-}
```
public final boolean contains(Constraint cc)
```


Indicates whether the Constraint object specified by name exists in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cc | [Constraint](../../com.groupdocs.assembly.system.data/constraint) | The Constraint to remove. |

**Returns:**
boolean - true if the collection contains the specified constraint; otherwise, false.
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the total number of elements in a collection.

**Returns:**
int - The total number of elements in a collection.
### iterator() {#iterator--}
```
public final Iterator iterator()
```




**Returns:**
java.util.Iterator
