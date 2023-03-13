---
title: CsvDataSource
second_title: GroupDocs.Assembly για Αναφορά API .NET
description: Παρέχει πρόσβαση στα δεδομένα ενός αρχείου CSV ή ροής που θα χρησιμοποιηθούν κατά τη συναρμολόγηση ενός εγγράφου.
type: docs
weight: 30
url: /el/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

Παρέχει πρόσβαση στα δεδομένα ενός αρχείου CSV ή ροής που θα χρησιμοποιηθούν κατά τη συναρμολόγηση ενός εγγράφου.

```csharp
public class CsvDataSource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από μια ροή CSV χρησιμοποιώντας προεπιλεγμένες επιλογές για την ανάλυση δεδομένων CSV. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από ένα αρχείο CSV χρησιμοποιώντας προεπιλεγμένες επιλογές για την ανάλυση δεδομένων CSV. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από μια ροή CSV χρησιμοποιώντας τις καθορισμένες επιλογές για την ανάλυση δεδομένων CSV. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | Δημιουργεί μια νέα πηγή δεδομένων με δεδομένα από ένα αρχείο CSV χρησιμοποιώντας τις καθορισμένες επιλογές για την ανάλυση δεδομένων CSV. |

### Παρατηρήσεις

Για να αποκτήσετε πρόσβαση σε δεδομένα του αντίστοιχου αρχείου ή ροής κατά τη συναρμολόγηση ενός εγγράφου, περάστε μια παρουσία αυτής της κλάσης ως μια πηγή δεδομένων σε μια από τις[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument overloads.

Σε πρότυπα έγγραφα, α[`CsvDataSource`](../csvdatasource) η περίπτωση θα πρέπει να αντιμετωπίζεται με τον ίδιο τρόπο σαν να ήταν aDataTableπαράδειγμα. Για περισσότερες πληροφορίες, ανατρέξτε στην αναφορά σύνταξης προτύπου (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Οι τύποι δεδομένων των τιμών διαχωρισμένων με κόμμα προσδιορίζονται αυτόματα σύμφωνα με τις αναπαραστάσεις συμβολοσειρών τους. Έτσι, στα έγγραφα template , μπορείτε να εργαστείτε με πληκτρολογημένες τιμές και όχι απλώς με συμβολοσειρές. Ο κινητήρας είναι σε θέση να αναγνωρίζει αυτόματα τιμές των ακόλουθων τύπων:

* `μακρύς?`
* `διπλό?`
* `bool;`
* `Ημερομηνία ώρα?`
* `σειρά`

Σημειώστε ότι για να λειτουργήσει η αυτόματη αναγνώριση τύπων δεδομένων, οι αναπαραστάσεις συμβολοσειρών τιμών διαχωρισμένων με κόμματα θα πρέπει να σχηματιστούν χρησιμοποιώντας αμετάβλητες ρυθμίσεις καλλιέργειας.

Για να παρακάμψετε την προεπιλεγμένη συμπεριφορά της φόρτωσης δεδομένων CSV, αρχικοποιήστε και περάστε α[`CsvDataLoadOptions`](../csvdataloadoptions)instance σε έναν κατασκευαστή αυτής της κλάσης.

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* συνέλευση [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->