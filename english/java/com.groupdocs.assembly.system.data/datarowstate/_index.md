---
title: DataRowState
second_title: GroupDocs.Assembly for Java API Reference
description: Specifies the state of a  object.
type: docs
weight: 22
url: /java/com.groupdocs.assembly.system.data/datarowstate/
---
**Inheritance:**
java.lang.Object
```
public final class DataRowState
```

Specifies the state of a [DataRow](../../com.groupdocs.assembly.system.data/datarow) object.
## Fields

| Field | Description |
| --- | --- |
| [DETACHED](#DETACHED) | Specifies that the row has been created but is not part of any [DataRowCollection](../../com.groupdocs.assembly.system.data/datarowcollection). |
| [UNCHANGED](#UNCHANGED) | Specifies that the row has not changed. |
| [ADDED](#ADDED) | Specifies that the row has been added to a [DataRowCollection](../../com.groupdocs.assembly.system.data/datarowcollection). |
| [DELETED](#DELETED) | Specifies that the row was deleted using the [DataRow\#delete()](../../com.groupdocs.assembly.system.data/datarow\#delete--) method of the [DataRow](../../com.groupdocs.assembly.system.data/datarow). |
| [MODIFIED](#MODIFIED) | Specifies that the row has been modified. |
### DETACHED {#DETACHED}
```
public static final int DETACHED
```


Specifies that the row has been created but is not part of any [DataRowCollection](../../com.groupdocs.assembly.system.data/datarowcollection). A [DataRow](../../com.groupdocs.assembly.system.data/datarow) is in this state immediately after it has been created and before it is added to a collection, or if it has been removed from a collection.

### UNCHANGED {#UNCHANGED}
```
public static final int UNCHANGED
```


Specifies that the row has not changed.

### ADDED {#ADDED}
```
public static final int ADDED
```


Specifies that the row has been added to a [DataRowCollection](../../com.groupdocs.assembly.system.data/datarowcollection).

### DELETED {#DELETED}
```
public static final int DELETED
```


Specifies that the row was deleted using the [DataRow\#delete()](../../com.groupdocs.assembly.system.data/datarow\#delete--) method of the [DataRow](../../com.groupdocs.assembly.system.data/datarow).

### MODIFIED {#MODIFIED}
```
public static final int MODIFIED
```


Specifies that the row has been modified.

