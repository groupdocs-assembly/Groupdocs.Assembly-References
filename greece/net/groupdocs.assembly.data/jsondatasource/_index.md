---
title: "JsonDataSource"
second_title: "GroupDocs.Assembly για .NET Αναφορά API"
description: "Παρέχει πρόσβαση σε δεδομένα αρχείου JSON ή ροής που θα χρησιμοποιηθούν κατά τη συναρμολόγηση ενός εγγράφου."
type: docs
weight: 230
url: /el/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

Παρέχει πρόσβαση σε δεδομένα αρχείου JSON ή ροής που θα χρησιμοποιηθούν κατά τη συναρμολόγηση ενός εγγράφου.

```csharp
public class JsonDataSource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από ροή JSON χρησιμοποιώντας τις προεπιλεγμένες επιλογές για την ανάλυση δεδομένων JSON. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από αρχείο JSON χρησιμοποιώντας τις προεπιλεγμένες επιλογές για την ανάλυση δεδομένων JSON. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από ροή JSON χρησιμοποιώντας τις καθορισμένες επιλογές για την ανάλυση δεδομένων JSON. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από αρχείο JSON χρησιμοποιώντας τις καθορισμένες επιλογές για την ανάλυση δεδομένων JSON. |

### Παρατηρήσεις

Για να αποκτήσετε πρόσβαση στα δεδομένα του αντίστοιχου αρχείου ή ροής κατά τη συναρμολόγηση ενός εγγράφου, περάστε ένα αντικείμενο αυτής της κλάσης ως πηγή δεδομένων σε μία από τις υπερφορτώσεις του [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Σε έγγραφα προτύπων, εάν ένα στοιχείο JSON ανώτερου επιπέδου είναι ένας πίνακας, ένα αντικείμενο [`JsonDataSource`](../jsondatasource) πρέπει να αντιμετωπίζεται με τον ίδιο τρόπο όπως ένα αντικείμενο DataTable. Εάν ένα στοιχείο JSON ανώτερου επιπέδου είναι ένα αντικείμενο, ένα αντικείμενο [`JsonDataSource`](../jsondatasource) πρέπει να αντιμετωπίζεται με τον ίδιο τρόπο όπως ένα αντικείμενο DataRow. Για περισσότερες πληροφορίες, δείτε την αναφορά σύνταξης προτύπου (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Σε έγγραφα προτύπων, μπορείτε να εργαστείτε με τυποποιημένες τιμές στοιχείων JSON. Για ευκολία, η μηχανή αντικαθιστά το σύνολο των απλών τύπων JSON με τον ακόλουθο:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Η μηχανή αναγνωρίζει αυτόματα τις τιμές των επιπλέον τύπων βάσει των JSON αναπαραστάσεών τους.

Για να παρακάμψετε τη προεπιλεγμένη συμπεριφορά της φόρτωσης δεδομένων JSON, αρχικοποιήστε και περάστε ένα αντικείμενο [`JsonDataLoadOptions`](../jsondataloadoptions) σε έναν κατασκευαστή αυτής της κλάσης.

### Δείτε επίσης

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.Assembly.dll -->
