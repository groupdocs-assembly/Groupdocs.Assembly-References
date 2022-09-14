---
title: DataRowState
second_title: GroupDocs.Assembly for Java API Reference
description: Specifies the state of a com.groupdocs.assembly.system.data.DataRow object.
type: docs
weight: 22
url: /java/com.groupdocs.assembly.system.data/datarowstate/
---
**Inheritance:**
java.lang.Object
```
public final class DataRowState
```

Specifies the state of a com.groupdocs.assembly.system.data.DataRow object.
## Fields

| Field | Description |
| --- | --- |
| [DETACHED](#DETACHED) | Specifies that the row has been created but is not part of any com.groupdocs.assembly.system.data.DataRowCollection. |
| [UNCHANGED](#UNCHANGED) | Specifies that the row has not changed. |
| [ADDED](#ADDED) | Specifies that the row has been added to a com.groupdocs.assembly.system.data.DataRowCollection. |
| [DELETED](#DELETED) | Specifies that the row was deleted using the com.groupdocs.assembly.system.data.DataRow\#delete() method of the com.groupdocs.assembly.system.data.DataRow. |
| [MODIFIED](#MODIFIED) | Specifies that the row has been modified. |
### DETACHED {#DETACHED}
```
public static final int DETACHED
```


Specifies that the row has been created but is not part of any com.groupdocs.assembly.system.data.DataRowCollection. A com.groupdocs.assembly.system.data.DataRow is in this state immediately after it has been created and before it is added to a collection, or if it has been removed from a collection.

### UNCHANGED {#UNCHANGED}
```
public static final int UNCHANGED
```


Specifies that the row has not changed.

### ADDED {#ADDED}
```
public static final int ADDED
```


Specifies that the row has been added to a com.groupdocs.assembly.system.data.DataRowCollection.

### DELETED {#DELETED}
```
public static final int DELETED
```


Specifies that the row was deleted using the com.groupdocs.assembly.system.data.DataRow\#delete() method of the com.groupdocs.assembly.system.data.DataRow.

### MODIFIED {#MODIFIED}
```
public static final int MODIFIED
```


Specifies that the row has been modified.

