---
title: "Όνομα"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει το όνομα αυτού του πίνακα που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πίνακα σε ένα έγγραφο προτύπου που περνά στο DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 40
url: /el/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

Λαμβάνει ή ορίζει το όνομα αυτού του πίνακα που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πίνακα σε ένα έγγραφο προτύπου που περνά στο [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### Παρατηρήσεις

Εάν το όνομα του πίνακα διαβαστεί από ένα έγγραφο, το όνομα διορθώνεται αυτόματα ώστε να είναι έγκυρο. Ωστόσο, εάν το όνομα του πίνακα οριστεί χειροκίνητα μέσω αυτής της ιδιότητας και το όνομα είναι μη έγκυρο, ρίχνεται εξαίρεση.

Το όνομα του πίνακα θεωρείται έγκυρο εάν πληρούνται οι ακόλουθες προϋποθέσεις:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTableSet`](../../documenttableset) object does not contain a [`DocumentTable`](../../documenttable) instance with the same name.

### Δείτε επίσης

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
