---
title: "DocumentTable"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Παρέχει πρόσβαση στα δεδομένα ενός μόνο πίνακα ή λογιστικού φύλλου που βρίσκεται σε εξωτερικό έγγραφο και χρησιμοποιείται κατά τη συναρμολόγηση ενός εγγράφου."
type: docs
weight: 120
url: /el/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

Παρέχει πρόσβαση σε δεδομένα ενός μοναδικού πίνακα (ή λογιστικού φύλλου) που βρίσκεται σε εξωτερικό έγγραφο και θα χρησιμοποιηθεί κατά τη συναρμολόγηση ενός εγγράφου.

```csharp
public class DocumentTable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | Δημιουργεί μια νέα παρουσία αυτής της κλάσης χρησιμοποιώντας τις προεπιλεγμένες επιλογές [`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTable](documenttable#constructor_2)(string, int) | Δημιουργεί μια νέα παρουσία αυτής της κλάσης χρησιμοποιώντας τις προεπιλεγμένες επιλογές [`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | Δημιουργεί ένα νέο αντίγραφο αυτής της κλάσης. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | Δημιουργεί ένα νέο αντίγραφο αυτής της κλάσης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | Αποκτά τη συλλογή των αντικειμένων [`DocumentTableColumn`](../documenttablecolumn) που αντιπροσωπεύουν τις στήλες του αντίστοιχου πίνακα. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | Αποκτά τον αρχικό μηδενικό δείκτη του αντίστοιχου πίνακα σύμφωνα με το πηγαίο έγγραφο. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | Αποκτά ή ορίζει το όνομα αυτού του πίνακα που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πίνακα σε ένα έγγραφο προτύπου που περνά στο [`DocumentAssembler`](../../groupdocs.assembly/documentassembler). |

### Παρατηρήσεις

Για έγγραφα μορφής Spreadsheet, μια παρουσία [`DocumentTable`](../documenttable) αντιπροσωπεύει ένα μόνο φύλλο. Για έγγραφα άλλων μορφών αρχείων, μια παρουσία [`DocumentTable`](../documenttable) αντιπροσωπεύει έναν μόνο πίνακα.

Για να αποκτήσετε πρόσβαση στα δεδομένα του αντίστοιχου πίνακα κατά τη συναρμολόγηση ενός εγγράφου, περάστε μια παρουσία αυτής της κλάσης ως πηγή δεδομένων σε μία από τις υπερφορτώσεις του [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Σε έγγραφα προτύπου, μια παρουσία [`DocumentTable`](../documenttable) πρέπει να αντιμετωπίζεται με τον ίδιο τρόπο όπως μια παρουσία DataTable. Δείτε την αναφορά σύνταξης προτύπου για περισσότερες πληροφορίες.

### Δείτε επίσης

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
