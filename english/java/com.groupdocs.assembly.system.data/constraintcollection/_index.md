---
title: ConstraintCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a collection of constraints for a .
type: docs
weight: 11
url: /java/com.groupdocs.assembly.system.data/constraintcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class ConstraintCollection implements Iterable<Constraint>
```

Represents a collection of constraints for a [DataTable](../../com.groupdocs.assembly.system.data/datatable).

## Methods

| Method | Description |
| --- | --- |
| [get(String constraintName)](#get-java.lang.String-) | Gets the Constraint from the collection with the specified name.
 |
| [get(int idx)](#get-int-) |  |
| [add(Constraint constraint)](#add-com.groupdocs.assembly.system.data.Constraint-) | Adds the specified Constraint object to the collection.
 |
| [remove(Constraint constraint)](#remove-com.groupdocs.assembly.system.data.Constraint-) | Removes the specified Constraint from the collection.
 |
| [contains(Constraint cc)](#contains-com.groupdocs.assembly.system.data.Constraint-) | Indicates whether the Constraint object specified by name exists in the collection.
 |
| [getCount()](#getCount--) | Gets the total number of elements in a collection.
 |
| [iterator()](#iterator--) |  |
### get(String constraintName) {#get-java.lang.String-}
```
public Constraint get(String constraintName)
```


Gets the Constraint from the collection with the specified name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constraintName | java.lang.String | name of the constraint in this collection
 |

**Returns:**
[Constraint](../../com.groupdocs.assembly.system.data/constraint) - constraint by its name or null if not found.

### get(int idx) {#get-int-}
```
public Constraint get(int idx)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| idx | int |  |

**Returns:**
[Constraint](../../com.groupdocs.assembly.system.data/constraint)
### add(Constraint constraint) {#add-com.groupdocs.assembly.system.data.Constraint-}
```
public void add(Constraint constraint)
```


Adds the specified Constraint object to the collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constraint | [Constraint](../../com.groupdocs.assembly.system.data/constraint) | The Constraint to add.
 |

### remove(Constraint constraint) {#remove-com.groupdocs.assembly.system.data.Constraint-}
```
public void remove(Constraint constraint)
```


Removes the specified Constraint from the collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constraint | [Constraint](../../com.groupdocs.assembly.system.data/constraint) | The Constraint to remove.
 |

### contains(Constraint cc) {#contains-com.groupdocs.assembly.system.data.Constraint-}
```
public boolean contains(Constraint cc)
```


Indicates whether the Constraint object specified by name exists in the collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cc | [Constraint](../../com.groupdocs.assembly.system.data/constraint) | The Constraint to remove.
 |

**Returns:**
boolean - true if the collection contains the specified constraint; otherwise, false.

### getCount() {#getCount--}
```
public int getCount()
```


Gets the total number of elements in a collection.


**Returns:**
int - The total number of elements in a collection.

### iterator() {#iterator--}
```
public Iterator<Constraint> iterator()
```




**Returns:**
java.util.Iterator<com.groupdocs.assembly.system.data.Constraint>
