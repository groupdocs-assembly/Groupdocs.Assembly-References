---
title: "Add"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Fügt das angegebene Typ‑Objekt zur Menge hinzu."
type: docs
weight: 20
url: /de/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

Fügt das angegebene Typ‑Objekt zur Menge hinzu.

Wirft ArgumentException in den folgenden Fällen:

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typ | Typ | Ein Typ-Objekt zum Hinzufügen. |

### Siehe auch

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
