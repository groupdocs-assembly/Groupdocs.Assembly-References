---
title: Add
second_title: GroupDocs.Assembly για Αναφορά API .NET
description: Προσθέτει το καθορισμένοType αντικείμενο στο σύνολο.
type: docs
weight: 20
url: /el/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

Προσθέτει το καθορισμένοType αντικείμενο στο σύνολο.

ΡίψειςArgumentException στις ακόλουθες περιπτώσεις:

-*type* είναι μηδενικό.

-*type* αντιπροσωπεύει έναν τύπο κενού.

-*type* αντιπροσωπεύει έναν αόρατο τύπο, δηλαδή έναν μη δημόσιο τύπο ή έναν δημόσιο ένθετο τύπο που έχει έναν μη δημόσιο εξωτερικό τύπο.

-*type* αντιπροσωπεύει έναν γενικό τύπο.

-*type* αντιπροσωπεύει έναν τύπο πίνακα.

-*type* έχει ήδη προστεθεί στο σετ.

```csharp
public void Add(Type type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | Type | ΕΝΑType αντικείμενο για προσθήκη. |

### Δείτε επίσης

* class [KnownTypeSet](../../knowntypeset)
* χώρος ονομάτων [GroupDocs.Assembly](../../knowntypeset)
* συνέλευση [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->