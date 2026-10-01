---
title: "Όνομα"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Αποκτά ή ορίζει το όνομα αυτής της στήλης που χρησιμοποιείται για την πρόσβαση στα δεδομένα των στηλών σε ένα έγγραφο προτύπου που περνά στο DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 30
url: /el/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

Αποκτά ή ορίζει το όνομα αυτής της στήλης που χρησιμοποιείται για την πρόσβαση στα δεδομένα της στήλης σε ένα έγγραφο προτύπου που περνά στο [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### Παρατηρήσεις

Εάν το όνομα της στήλης διαβαστεί από ένα έγγραφο (δείτε [`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames)), το όνομα διορθώνεται αυτόματα ώστε να είναι έγκυρο. Ωστόσο, εάν το όνομα της στήλης οριστεί χειροκίνητα μέσω αυτής της ιδιότητας και το όνομα είναι μη έγκυρο, ρίχνεται εξαίρεση.

Το όνομα της στήλης θεωρείται έγκυρο, εάν πληρούνται οι παρακάτω προϋποθέσεις:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### Δείτε επίσης

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
