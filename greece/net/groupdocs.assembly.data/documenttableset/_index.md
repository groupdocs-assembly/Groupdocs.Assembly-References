---
title: "DocumentTableSet"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Παρέχει πρόσβαση στα δεδομένα πολλαπλών πινάκων ή λογιστικών φύλλων που βρίσκονται σε εξωτερικό έγγραφο και χρησιμοποιούνται κατά τη συναρμολόγηση ενός εγγράφου. Επίσης, επιτρέπει τον ορισμό σχέσεων γονέα‑παιδιού για τους πίνακες του εγγράφου, απλοποιώντας έτσι την πρόσβαση σε σχετικά δεδομένα μέσα σε έγγραφα προτύπων."
type: docs
weight: 200
url: /el/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

Παρέχει πρόσβαση σε δεδομένα πολλαπλών πινάκων (ή λογιστικών φύλλων) που βρίσκονται σε εξωτερικό έγγραφο και θα χρησιμοποιηθούν κατά τη συναρμολόγηση ενός εγγράφου. Επίσης, επιτρέπει τον ορισμό σχέσεων γονέα-παιδιού για τους πίνακες εγγράφου, απλοποιώντας έτσι την πρόσβαση σε σχετικά δεδομένα μέσα στα πρότυπα εγγράφων.

```csharp
public class DocumentTableSet
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | Δημιουργεί μια νέα παρουσία αυτής της κλάσης φορτώνοντας όλους τους πίνακες από ένα έγγραφο χρησιμοποιώντας τις προεπιλεγμένες [`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTableSet](documenttableset#constructor_2)(string) | Δημιουργεί μια νέα παρουσία αυτής της κλάσης φορτώνοντας όλους τους πίνακες από ένα έγγραφο χρησιμοποιώντας τις προεπιλεγμένες [`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | Δημιουργεί ένα νέο αντίγραφο αυτής της κλάσης. |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | Δημιουργεί ένα νέο αντίγραφο αυτής της κλάσης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | Αποκτά τη συλλογή των σχέσεων γονέα‑παιδιού που έχουν οριστεί για τους πίνακες εγγράφου αυτού του συνόλου. |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | Αποκτά τη συλλογή των αντικειμένων [`DocumentTable`](../documenttable) που αντιπροσωπεύουν τους πίνακες αυτού του συνόλου. |

### Παρατηρήσεις

Για έγγραφα σε μορφές αρχείων Spreadsheet, ένα αντικείμενο [`DocumentTableSet`](../documenttableset) αντιπροσωπεύει ένα σύνολο φύλλων. Για έγγραφα σε άλλες μορφές αρχείων, ένα αντικείμενο [`DocumentTableSet`](../documenttableset) αντιπροσωπεύει ένα σύνολο πινάκων.

Για να έχετε πρόσβαση στα δεδομένα των αντίστοιχων πινάκων κατά τη συναρμολόγηση ενός εγγράφου, περάστε μια παρουσία αυτής της κλάσης ως πηγή δεδομένων σε μία από τις υπερφορτώσεις του [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Σε έγγραφα προτύπων, ένα αντικείμενο [`DocumentTableSet`](../documenttableset) πρέπει να αντιμετωπίζεται με τον ίδιο τρόπο όπως ένα αντικείμενο DataSet. Δείτε την αναφορά σύνταξης προτύπων για περισσότερες πληροφορίες.

### Δείτε επίσης

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
