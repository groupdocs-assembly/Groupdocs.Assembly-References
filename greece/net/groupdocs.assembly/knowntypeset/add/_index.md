---
title: "Προσθήκη"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Προσθέτει το καθορισμένο αντικείμενο Type στο σύνολο."
type: docs
weight: 20
url: /el/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

Προσθέτει το καθορισμένο αντικείμενο Type στο σύνολο.

Εκτοπίζει ArgumentException στις ακόλουθες περιπτώσεις:

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | Τύπος | Ένα αντικείμενο Type για προσθήκη. |

### Δείτε επίσης

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
