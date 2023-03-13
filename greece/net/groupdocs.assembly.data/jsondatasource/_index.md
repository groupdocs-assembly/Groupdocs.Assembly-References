---
title: JsonDataSource
second_title: GroupDocs.Assembly για Αναφορά API .NET
description: Παρέχει πρόσβαση σε δεδομένα ενός αρχείου JSON ή ροής που θα χρησιμοποιηθούν κατά τη συναρμολόγηση ενός εγγράφου.
type: docs
weight: 150
url: /el/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

Παρέχει πρόσβαση σε δεδομένα ενός αρχείου JSON ή ροής που θα χρησιμοποιηθούν κατά τη συναρμολόγηση ενός εγγράφου.

```csharp
public class JsonDataSource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από μια ροή JSON χρησιμοποιώντας προεπιλεγμένες επιλογές για την ανάλυση δεδομένων JSON. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από ένα αρχείο JSON χρησιμοποιώντας προεπιλεγμένες επιλογές για την ανάλυση δεδομένων JSON. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από μια ροή JSON χρησιμοποιώντας τις καθορισμένες επιλογές για την ανάλυση δεδομένων JSON. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από ένα αρχείο JSON χρησιμοποιώντας τις καθορισμένες επιλογές για την ανάλυση δεδομένων JSON. |

### Παρατηρήσεις

Για να αποκτήσετε πρόσβαση σε δεδομένα του αντίστοιχου αρχείου ή ροής κατά τη συναρμολόγηση ενός εγγράφου, περάστε μια παρουσία αυτής της κλάσης ως μια πηγή δεδομένων σε μια από τις[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument overloads.

Σε έγγραφα προτύπου, εάν ένα στοιχείο JSON ανώτατου επιπέδου είναι ένας πίνακας, α[`JsonDataSource`](../jsondatasource) η περίπτωση θα πρέπει να αντιμετωπίζεται με με τον ίδιο τρόπο σαν να ήταν aDataTable παράδειγμα. Εάν ένα στοιχείο JSON ανώτερου επιπέδου είναι αντικείμενο, α[`JsonDataSource`](../jsondatasource) η περίπτωση θα πρέπει να αντιμετωπίζεται με τον ίδιο τρόπο σαν να ήταν aDataRowπαράδειγμα. Για περισσότερες πληροφορίες, ανατρέξτε στην αναφορά σύνταξης προτύπου (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Σε έγγραφα προτύπου, μπορείτε να εργαστείτε με πληκτρολογημένες τιμές στοιχείων JSON. Για ευκολία, ο κινητήρας αντικαθιστά το σετ απλών τύπων JSON με το ακόλουθο:

* `μακρύς?`
* `διπλό?`
* `bool;`
* `Ημερομηνία ώρα?`
* `σειρά`

Ο κινητήρας αναγνωρίζει αυτόματα τις τιμές των επιπλέον τύπων στις αναπαραστάσεις JSON τους.

Για να παρακάμψετε την προεπιλεγμένη συμπεριφορά της φόρτωσης δεδομένων JSON, αρχικοποιήστε και περάστε α[`JsonDataLoadOptions`](../jsondataloadoptions)instance σε έναν κατασκευαστή αυτής της κλάσης.

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* συνέλευση [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->